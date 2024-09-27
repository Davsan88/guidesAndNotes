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