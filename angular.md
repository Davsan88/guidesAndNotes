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


## ✅ 2. Modules – Grouping Everything

Angular apps are made of modules — think of them like folders of related features.  
The main one is usually `AppModule`, in `app.module.ts`. It tells Angular:

- What components your app has  
- What features you're using (like forms, HTTP, etc.)

Here’s the boilerplate:

```ts
@NgModule({
  declarations: [AppComponent, RecipeComponent], // Your components
  imports: [BrowserModule, FormsModule],         // Built-in tools
  bootstrap: [AppComponent]                      // Starting point
})
export class AppModule {}
```

---


## ✅ 3. Routing – Moving Between Pages

Angular uses routing to show different views based on the URL, without reloading the page (just like React Router).

