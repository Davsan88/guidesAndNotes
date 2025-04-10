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

**Setup:**  
In `app-routing.module.ts`:

```ts
const routes: Routes = [
  { path: 'recipes', component: RecipeComponent },
  { path: '', redirectTo: '/recipes', pathMatch: 'full' }
];

@NgModule({
  imports: [RouterModule.forRoot(routes)],
  exports: [RouterModule]
})
export class AppRoutingModule {}
```

**Display the routed component:**  
In your `app.component.html` (or wherever), add:

```html
<router-outlet></router-outlet>
```

**Navigation in HTML:**

```html
<a routerLink="/recipes">Go to Recipes</a>
```

---


## ✅ 4. Services – Shared Logic & Data

A service is a class that holds logic or data you want to share across components (like fetching recipes from an API).

```ts
@Injectable({
  providedIn: 'root' // Available everywhere
})
export class RecipeService {
  getRecipes() {
    return ['Pizza', 'Paella', 'Sushi'];
  }
}
```

To use this in a component:

```ts
constructor(private recipeService: RecipeService) {}

ngOnInit() {
  this.recipes = this.recipeService.getRecipes();
}
```

🧠 **This is Angular’s version of dependency injection:**  
You ask Angular to give you an instance of the service — it does the work.

---


## ✅ 5. Forms & Two-Way Binding

Want a user to type in a field and update a variable? Use `[(ngModel)]`.

**In your component:**

```ts
recipeName = '';
```

**In the HTML:**

```html
<input [(ngModel)]="recipeName" />
<p>You typed: {{ recipeName }}</p>
```

**Important:** You must import `FormsModule` in your `AppModule` for `ngModel` to work.

```ts
import { FormsModule } from '@angular/forms';
```

---


