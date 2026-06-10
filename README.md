## What I Learned

This project helped me build a stronger foundation in React by creating a small pizza menu application using components, props, JSX, conditional rendering, and JavaScript array methods.

### Component-Based UI

React applications are built using components, which are reusable, self-contained pieces of the user interface. In this project, I separated the UI into multiple components, including:

- `App`
- `Header`
- `Menu`
- `Pizza`
- `Footer`
- `Order`

This helped me understand how a complete application can be broken down into smaller pieces that are easier to read, maintain, and reuse.

### JSX and Declarative Rendering

I learned how JSX allows React components to describe what the UI should look like. JSX looks similar to HTML, but it also allows JavaScript expressions to be used inside curly braces.

For example, this project uses JSX to render pizza names, ingredients, prices, images, and sold-out states directly from JavaScript data.

This helped me understand React’s declarative approach: instead of manually telling the browser how to update the UI step by step, I describe what the UI should look like based on the current data.

### Props and One-Way Data Flow

I learned how props are used to pass data from parent components to child components.

In this application, the `Menu` component loops through an array of pizza objects and passes each pizza object into the `Pizza` component as a prop. This allowed me to reuse one `Pizza` component to render multiple different pizzas.

This also helped reinforce one of React’s most important concepts: data flows down the component tree. Parent components can pass data to child components, but child components should not directly modify the props they receive.

### Rendering Lists with `.map()`

This project helped me practice rendering lists in React using JavaScript’s `.map()` method.

The pizza menu is created by looping over the `pizzaData` array and returning a `Pizza` component for each pizza object. I also learned why React requires a unique `key` prop when rendering lists, so React can efficiently track and update each item.

### Conditional Rendering

I learned how to conditionally render different UI based on application data.

This project includes several examples of conditional rendering, such as:

- Displaying a message when there are no pizzas available.
- Showing `"SOLD OUT"` instead of the pizza price when a pizza is unavailable.
- Applying a different CSS class to sold-out pizzas.
- Displaying an order message only when the restaurant is open.

### Styling and Dynamic Classes

I practiced applying CSS classes in React, including dynamic class names based on component data.

For example, sold-out pizzas receive an additional `sold-out` class, which allows the UI to visually communicate that the item is unavailable.

### React 18 Rendering and Strict Mode

I learned how React 18 uses `ReactDOM.createRoot()` to render the application.

I also used `React.StrictMode`, which helps identify potential issues during development by intentionally running certain checks more than once.

### Additional Concepts Reinforced

This project also helped me better understand several foundational React concepts, including:

- The difference between imperative and declarative programming.
- Why React components should remain pure when possible.
- Why props should not be mutated.
- How to think in terms of reusable UI components.
- How data, JavaScript logic, and JSX work together inside a React component.

Overall, this project gave me hands-on practice with the core building blocks of React and helped me better understand how React applications are structured.
