# 🧳 Angular Survival Kit  

*(For React Devs & Total Angular Newbies)*  
This is all you need to read, understand, and contribute to an Angular codebase without becoming an Angular expert. Focused, clear, and light.

---


## ✅ 1. Components – The Building Blocks

In Angular, components are like React components — they control a part of the UI.  
A typical Angular component has 3 parts:

```ts
@Component({
  selector: 'app-recipe',              // What the tag will look like in HTML: <app-recipe>
  templateUrl: './recipe.component.html',  // The HTML file
  styleUrls: ['./recipe.component.css']    // The CSS file(s)
})
export class RecipeComponent {
  recipeName = 'Paella'; // Some data the component controls
}
```

### 🧠 TL;DR  
You define the UI in `recipe.component.html`.  
You define logic and data in `recipe.component.ts`.  
You can use the component in another template like:

```html
<app-recipe></app-recipe>
```

---


