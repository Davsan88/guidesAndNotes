# React Workflow Overview: Working with Data, Props, and Destructuring

In React, managing data efficiently and passing it through components is a core practice. This guide walks you through handling external data files, using `.map()` to render multiple components, and passing data via props. We also explore destructuring to simplify working with props.

## Data File (data.js)

### Where the Data Originates

Your data typically resides in a separate file (like `data.js`), stored as an array of objects. Each object represents an individual entity (like a card, joke, or product) with various properties.

### Data Format Example

```javascript
export default [
  {
    id: 1,
    title: "Life Lessons with Katie Zaferes",
    price: 136,
    coverImg: "katie-zaferes.png",
    stats: {
      rating: 5.0,
      reviewCount: 6
    },
    location: "Online"
  },
  {
    id: 2,
    title: "Learn Wedding Photography",
    price: 125,
    coverImg: "wedding-photography.png",
    stats: {
      rating: 5.0,
      reviewCount: 30
    },
    location: "Online"
  }
];
```

In this example, each object has properties such as `id`, `title`, `price`, `coverImg`, and `stats` (which itself is an object with properties like `rating` and `reviewCount`).

---

## App.jsx

### Central Hub of the Application

The `App.jsx` file is responsible for importing the data and using it to render child components dynamically. In this case, we use `.map()` to iterate over the data array and render a `Card` component for each item.

### Example:

```javascript
import data from './data'; // 1. Importing the data file

function App() {
  // 2. Using .map() to loop over the data array and create a Card component for each item
  const cardElements = data.map(({ id, title, price, coverImg, stats, location }) => (
    <Card 
      key={id} 
      title={title} 
      price={price} 
      coverImg={coverImg} 
      stats={stats} 
      location={location}
    />
  ));

  return (
    <>
      <Navbar />  {/* Static components */}
      <Hero />
      <div>
        { cardElements }  {/* Rendering the mapped Card components */}
      </div>
    </>
  );
}

export default App;
```

### What Happens Here:

1. **Data Import**: The data array is imported from `data.js`.
2. **Mapping the Data**: The `.map()` method iterates over each object in the `data` array, destructuring properties (like `id`, `title`, and `price`) and passing them to the `Card` component.
3. **Passing Props**: Each `Card` component is passed individual props from the current object.

---

## Card.jsx

### Receiving and Destructuring Props

The `Card` component receives props from `App.jsx`, and these props are used to render the UI. Destructuring the props inside the component allows you to access them directly, simplifying the code.

### Example:

```javascript
const Card = ({ title, price, coverImg, stats: { rating, reviewCount }, location }) => {
  return (
    <div className='card'>
      <img className='card__image' src={coverImg} alt={title} />
      <div className='card__info'>
        <img src="star.png" alt="Star icon" className='card__star' />
        <span>{rating}</span>
        <span className='gray'>({reviewCount}) ·</span>
        <span className='gray'>{location}</span>
      </div>
      <h2>{title}</h2>
      <p><b>From ${price}</b> / person</p>
    </div>
  );
}

export default Card;
```
