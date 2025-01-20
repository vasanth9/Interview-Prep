# React JS

## JavaScript Library

### What is React Js?

    React Js is a open source frontend javascript library used to build user interfaces from components. It is used to build Single Page Applications (SPAs) 

### Where is React Js Created?

    ReactJs is created at Facebook in 2013  by Jordwalke (initally FaxJs) in an attempt make write once - render everywhere.

### What are the features of ReactJs?

    1. Component-Based Architecture
    -  UI is divided into reusable and independent components.
    -  Each component has its own logic, making development modular and maintainable.

    2. Virtual DOM (VDOM)

    -   React uses a Virtual DOM to optimize rendering.
    -   Changes are first applied to the Virtual DOM, and only the differences are updated in the real DOM, improving performance.
    
    3. JSX (JavaScript XML)

    -   A syntax extension for JavaScript that allows writing UI elements in a syntax similar to HTML.


    4. One-Way Data Binding

    -   The data flow in React is unidirectional (one-way).
    -   Changes in the state update the UI but not vice versa, making debugging easier.

    5. Declarative UI

    -   React makes it easy to describe what the UI should look like.
    -   Instead of manually handling DOM updates, you just update the state, and React takes care of rendering.

    6. React Hooks

    -   Hooks (e.g., useState, useEffect, useContext) allow functional components to manage state and lifecycle methods without using class components.

    7. Component Lifecycle Methods

    -   Class components have lifecycle methods like componentDidMount(), componentDidUpdate(), and componentWillUnmount().
    -   Functional components handle lifecycle using React Hooks like useEffect().

    8. State Management

    -   React has built-in state management using useState().
    -   For global state management, libraries like Redux, Recoil, or Context API are used.

    9. React Router

    -   Provides navigation between different pages (SPAs).

    10. Server-Side Rendering (SSR) & Static Site Generation (SSG)

    - React supports SSR (via Next.js) for SEO-friendly applications.
    - SSG generates static pages at build time, improving performance.

    11. Code Splitting & Lazy Loading

    - Using React.lazy() and Suspense, React loads only the required parts of the application to optimize performance.

    12. Cross-Platform Development

    - React can be used for mobile development with React Native.

### When Should You Use React?

    ✅ For Single Page Applications (SPAs) → Like dashboards, social media apps.
    ✅ For Scalable & Maintainable Projects → Large teams can work on separate components.
    ✅ For Performance-Optimized Web Apps → With Virtual DOM and SSR capabilities.
    ✅ For Cross-Platform Apps → When you want both web and mobile apps with a shared codebase.

### React.js Architecture 🏗️

    React.js follows a component-based architecture where the UI is divided into reusable, independent components. It is structured to ensure scalability, maintainability, and efficiency.
    1️⃣ User Interacts with UI (Clicks Button, Enters Text)
        ⬇
    2️⃣ React Updates Component State (useState / Redux)
        ⬇
    3️⃣ Virtual DOM Updates (Diffing Algorithm)
        ⬇
    4️⃣ React Re-renders Only the Changed Parts
        ⬇
    5️⃣ Real DOM Updates Efficiently
        ⬇
    6️⃣ User Sees Updated UI

### Comparison of React.js with Other UI Frameworks 🆚

React.js is one of the most popular JavaScript UI libraries, but how does it compare with other frameworks like Angular, Vue.js, Svelte, and Solid.js? Let’s break it down! 🔥

1️⃣ Quick Overview: React vs. Others

| Feature | React.js | Angular | Vue.js | Svelte | Solid.js |
|---|---|---|---|---|---|
| Type | Library | Framework | Framework | Compiler | Library |
| Architecture | Component-based | Component-based (MVC) | Component-based | Component-based | Component-based |
| Learning Curve | Medium | Steep | Easy-Medium | Easy | Medium |
| Performance | Fast (VDOM) | Slower (Real DOM) | Fast (VDOM) | Extremely Fast | Ultra-Fast |
| State Management | Context API, Redux, Recoil, Zustand | Built-in (RxJS, NgRx) | Vuex, Pinia | Built-in (Reactivity) | Built-in |
| DOM Manipulation | Virtual DOM | Real DOM (Incremental DOM) | Virtual DOM | No Virtual DOM | Fine-grained reactivity |
| File Size (Core) | ~42 KB | ~170 KB | ~30 KB | ~5 KB | ~6 KB |
| Mobile Support | React Native | Ionic / NativeScript | Vue Native / Quasar | Svelte Native | None |
| Community Support | ⭐⭐⭐⭐⭐ (Huge) | ⭐⭐⭐⭐ (Large) | ⭐⭐⭐⭐ (Growing) | ⭐⭐⭐ (Emerging) | ⭐⭐ (New) |

2️⃣ Detailed Comparison: React vs. Others

🔹 React.js: The Popular Choice

    ✅ Component-Based Architecture
    ✅ Virtual DOM for Efficient Rendering
    ✅ Unidirectional Data Flow (One-Way Binding)
    ✅ Huge Community and Ecosystem
    ✅ Flexibility (Can integrate with any backend, no restrictions)

❌ Drawbacks:

    • Requires additional libraries for routing (React Router) and state management (Redux, Recoil).
    • Frequent updates lead to breaking changes.

📌 Best For: SPAs, Enterprise Apps, Cross-Platform Development (React Native).

🔹 Angular: The Full-Fledged Framework

    ✅ Full MVC Framework (Built-in Routing, HTTP, Forms, etc.)
    ✅ Two-Way Data Binding (Easier state synchronization)
    ✅ Dependency Injection (DI) for better scalability
    ✅ Built-in RxJS for state management

❌ Drawbacks:

    • Steep Learning Curve (Requires TypeScript, RxJS).
    • Performance Issues (More boilerplate, slower due to real DOM usage).
    • Heavy Framework (170 KB vs. React’s 42 KB).

📌 Best For: Large-scale enterprise applications, Banking Apps, Google Cloud-based apps.

🔹 Vue.js: The Developer-Friendly Framework

    ✅ Simple & Lightweight (~30 KB)
    ✅ Combines Reactivity (Svelte) + Virtual DOM (React) + Two-Way Binding (Angular)
    ✅ Easier State Management (Vuex, Pinia)
    ✅ Better Template System (Uses HTML, JSX, or render functions)

❌ Drawbacks:

    • Smaller Community than React/Angular
    • Less Enterprise Adoption

📌 Best For: Beginners, Small to Medium Projects, Progressive Web Apps.

🔹 Svelte: The Future of UI Development?

    ✅ No Virtual DOM (Faster rendering)
    ✅ Truly Reactive (State management built-in)
    ✅ Smallest Bundle Size (~5 KB)
    ✅ Simplified Syntax (No need for JSX)

❌ Drawbacks:

    • Smaller Ecosystem (Fewer third-party libraries than React).
    • Lack of large-scale enterprise adoption.

📌 Best For: Performance-focused apps, Static Sites, Web Apps with minimal JS.

🔹 Solid.js: React on Steroids?

    ✅ Fine-grained Reactivity (Avoids unnecessary renders)
    ✅ Uses JSX like React, but faster than React
    ✅ No Virtual DOM needed (More like Svelte)
    ✅ Extremely Small (~6 KB)

❌ Drawbacks:

    • Newer Technology (Less Adoption, Smaller Community)
    • Fewer Learning Resources

📌 Best For: High-performance web applications, Modern SPAs, Alternatives to React.

3️⃣ Which One Should You Choose?

|Use Case |Best Choice 🎯|
|---|---|
| General Web Apps, SPAs | ✅ React.js |
| Enterprise-Scale Apps | ✅ Angular |
| Simple & Lightweight UI  | ✅ Vue.js |
| High Performance & Minimalist Apps | ✅ Svelte |
| React-Like, But Faster | ✅ Solid.js |

4️⃣ Final Verdict: React.js vs. Others

🏆 React.js Wins When:

✔ You need a flexible, component-based UI library.
✔ You want high community support & rich ecosystem.
✔ You are building large-scale applications.
✔ You want cross-platform support (React Native).

🚀 Angular Wins When:

✔ You need a fully-fledged framework with everything built-in.
✔ You are developing large-scale, enterprise apps.
✔ You prefer TypeScript & Dependency Injection.

🌿 Vue.js Wins When:

✔ You need an easy-to-learn & lightweight alternative to React.
✔ You are building a progressive web app (PWA).

⚡ Svelte Wins When:

✔ You need extreme performance (No Virtual DOM).
✔ You want simpler syntax & smaller bundle size.

🔥 Solid.js Wins When:

✔ You love React but want better performance.
✔ You need fine-grained reactivity.

5️⃣ Conclusion: Which One is Best for You?

🚀 If you are already using React, stick with it.
⚡ If you are new, Vue or Svelte might be easier.
🏢 If you’re building a large enterprise app, Angular is a strong choice.

### Components in React.js 🚀

    React.js is component-based, meaning the UI is broken down into reusable and independent building blocks called components. These components manage their own state and render UI dynamically.

1️⃣ What is a React Component?

    A React component is a JavaScript function or class that returns JSX (JavaScript XML) to describe what should appear on the screen.

Example of a simple React component:

```jsx
function Greeting() {
  return <h1>Hello, React!</h1>;
}
```

📌 Key Points:

    ✅ Components are reusable.
    ✅ Components return JSX (HTML inside JavaScript).
    ✅ Components can have state and props.

2️⃣ Types of React Components

React components are categorized into two main types:

🔹 1. Functional Components (Modern Approach)

 • Simpler, lightweight, and recommended.
 • Uses React Hooks (useState, useEffect) for state and lifecycle.
 • Stateless by default, but can have state using Hooks.

📌 Example of a Functional Component:

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}!</h1>;
}
```

OR with Hooks (useState):

```jsx
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);
  
  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </div>
  );
}
```

    ✅ Easy to read and write.
    ✅ No need for this keyword.
    ✅ Better performance and easier testing.

🔹 2. Class Components (Older Approach)

 • Uses ES6 classes and extends React.Component.
 • Uses this.state for managing state.
 • Includes lifecycle methods (componentDidMount, componentDidUpdate, etc.).

📌 Example of a Class Component:

```jsx
import React, { Component } from "react";

class Welcome extends Component {
  render() {
    return <h1>Hello, {this.props.name}!</h1>;
  }
}
```

📌 Class Component with State:

```jsx
class Counter extends Component {
  constructor() {
    super();
    this.state = { count: 0 };
  }

  increaseCount = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (
      <div>
        <p>Count: {this.state.count}</p>
        <button onClick={this.increaseCount}>Increase</button>
      </div>
    );
  }
}
```

    ❌ More boilerplate code.
    ❌ this keyword can be confusing.
    ❌ Hooks have made class components less common.

### React Lifecycle Methods 🔄

    React components go through different lifecycle phases, from creation to updating and unmounting. These phases allow you to control the behavior of components at different stages.

🔹 Lifecycle Phases in React

React class components go through three main lifecycle phases:

    Phase Description
    Mounting Component is created and added to the DOM
    Updating Component re-renders due to state/props changes
    Unmounting Component is removed from the DOM

✅ Functional components use the useEffect Hook instead of lifecycle methods.

1️⃣ Mounting Phase (Component Creation)

Occurs when the component is first added to the DOM.

🔹 Lifecycle Methods in Mounting

| Method | Purpose |
|---|---|
| constructor() |  Initialize state and bind event handlers |
| static getDerivedStateFromProps(props, state) |  Sync state with props before rendering |
| render() |  Renders the UI |
| componentDidMount() |  Runs after the component is mounted (ideal for API calls)|

📌 Example of Mounting Lifecycle Methods

```jsx
import React, { Component } from "react";

class LifecycleDemo extends Component {
  constructor() {
    super();
    this.state = { message: "Component is mounting..." };
    console.log("Constructor: Initializing state");
  }

  static getDerivedStateFromProps(props, state) {
    console.log("getDerivedStateFromProps: Syncing props with state");
    return null; // No update to state
  }

  componentDidMount() {
    console.log("componentDidMount: Component has mounted");
  }

  render() {
    console.log("Render: Rendering component UI");
    return <h1>{this.state.message}</h1>;
  }
}

export default LifecycleDemo;
```

    ✅ Best place to make API calls → componentDidMount().
    ✅ Use constructor to initialize state and bind methods.

2️⃣ Updating Phase (Component Re-rendering)

Occurs when props or state change, causing the component to re-render.

🔹 Lifecycle Methods in Updating

| Method | Purpose |
|---|---|
| static getDerivedStateFromProps(props, state) |  Sync state with new props |
| shouldComponentUpdate(nextProps, nextState) | Controls whether to re-render (performance optimization) |
| render() |  Updates the UI |
| getSnapshotBeforeUpdate(prevProps, prevState) | Captures data before DOM update |
| componentDidUpdate(prevProps, prevState, snapshot) |  Runs after the update is committed to the DOM |

📌 Example of Updating Lifecycle Methods

```jsx
class LifecycleDemo extends Component {
  constructor() {
    super();
    this.state = { count: 0 };
  }

  shouldComponentUpdate(nextProps, nextState) {
    console.log("shouldComponentUpdate: Should re-render?");
    return nextState.count % 2 === 0; // Re-render only on even count
  }

  getSnapshotBeforeUpdate(prevProps, prevState) {
    console.log("getSnapshotBeforeUpdate: Capture DOM data before update");
    return null;
  }

  componentDidUpdate(prevProps, prevState, snapshot) {
    console.log("componentDidUpdate: Component updated in DOM");
  }

  render() {
    console.log("Render: Rendering component UI");
    return (
      <div>
        <h1>Count: {this.state.count}</h1>
        <button onClick={() => this.setState({ count: this.state.count + 1 })}>
          Increase Count
        </button>
      </div>
    );
  }
}

export default LifecycleDemo;
```

    ✅ Use shouldComponentUpdate() for performance optimization (prevents unnecessary re-renders).
    ✅ Use componentDidUpdate() for API calls when state changes.

3️⃣ Unmounting Phase (Component Removal)

Occurs when the component is removed from the DOM.

🔹 Lifecycle Method in Unmounting

| Method | Purpose |
|---|---|
| componentWillUnmount() |  Cleanup before the component is removed |

📌 Example of Unmounting Lifecycle Method

```jsx
class LifecycleDemo extends Component {
  componentWillUnmount() {
    console.log("componentWillUnmount: Cleanup before removal");
  }

  render() {
    return <h1>Component is mounted</h1>;
  }
}

export default LifecycleDemo;
```

    ✅ Best place to remove event listeners, cancel timers, or unsubscribe from API calls.

4️⃣ Lifecycle Methods in Functional Components

React Hooks (useEffect) replace lifecycle methods in functional components.

| Lifecycle in Class Components |  Equivalent in Functional Components (useEffect) |
|---|---|
| componentDidMount() | useEffect(() => { }, []) |
| componentDidUpdate() |  useEffect(() => { }, [dependency]) |
| componentWillUnmount() | useEffect(() => { return () => { cleanup } }, []) |

📌 Example of Lifecycle in Functional Component

```jsx
import { useState, useEffect } from "react";

function LifecycleDemo() {
  const [count, setCount] = useState(0);

  useEffect(() => {
    console.log("Component Mounted or Updated");
    return () => {
      console.log("Component Unmounted");
    };
  }, [count]);

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => setCount(count + 1)}>Increase Count</button>
    </div>
  );
}

export default LifecycleDemo;
```

    ✅ useEffect() replaces componentDidMount, componentDidUpdate, and componentWillUnmount.
    ✅ Cleanup function inside useEffect() handles unmounting behavior.

### React Hooks 🎣

    React Hooks are special functions introduced in React 16.8 that allow functional components to use state and lifecycle features without writing class components.

✅ Why Hooks?
    • Avoid complex class components
    • Improve code readability and reuse
    • Enable functional components to manage state and side effects

🔹 Commonly Used React Hooks

| Hook | Purpose |
|---|---|
| useState |  Manage component state |
| useEffect | Handle side effects (API calls, subscriptions) |
| useContext | Access context values |
| useRef | Create references to DOM elements |
| useMemo | Optimize performance with memoization |
| useCallback | Optimize function references |
| useReducer | Manage complex state logic |
| useLayoutEffect | Similar to useEffect, but runs synchronously |
| useImperativeHandle | Customize instance methods of components |
| useDebugValue | Custom hook debugging |

1️⃣ useState – Managing State in Functional Components

    useState allows you to add state to a functional component.

📌 Example: Counter with useState

```jsx
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </div>
  );
}

export default Counter;
```

    ✅ State persists across re-renders
    ✅ setCount triggers a re-render

2️⃣ useEffect – Handling Side Effects

    useEffect replaces lifecycle methods like componentDidMount, componentDidUpdate, and componentWillUnmount.

📌 Example: Fetching Data with useEffect

```jsx
import { useState, useEffect } from "react";

function DataFetcher() {
  const [data, setData] = useState([]);

  useEffect(() => {
    fetch("https://jsonplaceholder.typicode.com/posts")
      .then((response) => response.json())
      .then((data) => setData(data));

    return () => console.log("Cleanup function (component unmounted)");
  }, []); // Runs only once (on mount)

  return (
    <ul>
      {data.slice(0, 5).map((item) => (
        <li key={item.id}>{item.title}</li>
      ))}
    </ul>
  );
}

export default DataFetcher;
```

    ✅ Runs after initial render
    ✅ Use dependencies ([]) to control when it runs
    ✅ Cleanup function prevents memory leaks

    Equivalent in Class Components
    componentDidMount()
    componentDidUpdate()
    componentWillUnmount()

3️⃣ useContext – Avoid Prop Drilling

    useContext provides direct access to context values without passing props manually.

📌 Example: Theme Context

```jsx
import { createContext, useContext } from "react";

const ThemeContext = createContext("light");

function ThemedButton() {
  const theme = useContext(ThemeContext);
  return <button className={theme}>Themed Button</button>;
}

function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedButton />
    </ThemeContext.Provider>
  );
}

export default App;
```

    ✅ Simplifies prop passing
    ✅ Easier global state management

4️⃣ useRef – Reference DOM Elements & Persist Values

    useRef allows you to access and modify DOM elements without re-renders.

📌 Example: Focus Input Field

```jsx
import { useRef } from "react";

function FocusInput() {
  const inputRef = useRef(null);

  return (
    <div>
      <input ref={inputRef} type="text" />
      <button onClick={() => inputRef.current.focus()}>Focus Input</button>
    </div>
  );
}

export default FocusInput;
```

    ✅ Doesn’t cause re-renders
    ✅ Useful for managing DOM elements

5️⃣ useMemo – Optimize Performance

        useMemo caches computed values to avoid unnecessary calculations.

📌 Example: Expensive Computation

```jsx
import { useState, useMemo } from "react";

function ExpensiveCalculation({ number }) {
  const squared = useMemo(() => {
    console.log("Computing square...");
    return number * number;
  }, [number]);

  return <p>Squared Value: {squared}</p>;
}

function App() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <ExpensiveCalculation number={count} />
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </div>
  );
}

export default App;
```

    ✅ Avoids unnecessary re-calculations
    ✅ Improves performance

6️⃣ useCallback – Optimize Function References

    useCallback caches functions to prevent unnecessary re-creations.

📌 Example: Prevent Unnecessary Re-Renders

```jsx
import { useState, useCallback } from "react";

function Button({ handleClick }) {
  console.log("Button re-rendered");
  return <button onClick={handleClick}>Click Me</button>;
}

function App() {
  const [count, setCount] = useState(0);

  const increment = useCallback(() => {
    setCount((prev) => prev + 1);
  }, []);

  return (
    <div>
      <p>Count: {count}</p>
      <Button handleClick={increment} />
    </div>
  );
}

export default App;
```

    ✅ Prevents unnecessary function re-creation
    ✅ Optimizes performance in child components

7️⃣ useReducer – Alternative to useState

    useReducer is useful for complex state logic.

📌 Example: Counter with Reducer

```jsx
import { useReducer } from "react";

const reducer = (state, action) => {
  switch (action.type) {
    case "increment":
      return { count: state.count + 1 };
    case "decrement":
      return { count: state.count - 1 };
    default:
      return state;
  }
};

function Counter() {
  const [state, dispatch] = useReducer(reducer, { count: 0 });

  return (
    <div>
      <h1>Count: {state.count}</h1>
      <button onClick={() => dispatch({ type: "increment" })}>+</button>
      <button onClick={() => dispatch({ type: "decrement" })}>-</button>
    </div>
  );
}

export default Counter;
```

    ✅ Ideal for managing state transitions
    ✅ Similar to Redux reducer

### Props in React JS 🎁

    In React, props (short for “properties”) are read-only arguments passed to components. They allow data to flow from parent to child components, making components reusable and dynamic.

🔹 Key Features of Props

    ✅ Props are immutable (cannot be modified inside the child component).
    ✅ Passed from parent to child as function arguments.
    ✅ Used for dynamic rendering in components.
    ✅ Can pass any data type (strings, numbers, objects, arrays, functions, JSX, etc.).

1️⃣ Passing Props to Components

    Props are passed as attributes when using a component.

📌 Example: Passing Props to a Functional Component

```jsx
function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}

function App() {
  return <Greeting name="John" />;
}

export default App;
```

    ✅ name="John" is passed as a prop
    ✅ Inside Greeting, props.name holds “John”

2️⃣ Default Props

    Use default props when a prop is missing.

📌 Example: Using Default Props

```jsx
function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}

Greeting.defaultProps = {
  name: "Guest",
};

function App() {
  return <Greeting />; // No name passed
}

export default App;
```

    ✅ If no name is passed, “Guest” is used as default

3️⃣ Destructuring Props

    Instead of using props.name, destructure props for cleaner code.

📌 Example: Destructuring in Functional Component

```jsx
function Greeting({ name }) {
  return <h1>Hello, {name}!</h1>;
}

function App() {
  return <Greeting name="Alice" />;
}

export default App;
```

    ✅ More readable and concise

4️⃣ Passing Multiple Props

    Props can hold multiple values of different types.

📌 Example: Passing Multiple Props

```jsx
function UserProfile({ name, age, isOnline }) {
  return (
    <div>
      <h2>{name} ({age} years old)</h2>
      <p>Status: {isOnline ? "Online" : "Offline"}</p>
    </div>
  );
}

function App() {
  return <UserProfile name="Emma" age={25} isOnline={true} />;
}

export default App;
```

    ✅ Pass strings, numbers, and booleans as props

5️⃣ Passing Objects as Props

    Instead of passing multiple props, pass an object.

📌 Example: Passing an Object

```jsx
function UserProfile({ user }) {
  return (
    <div>
      <h2>{user.name} ({user.age} years old)</h2>
      <p>Status: {user.isOnline ? "Online" : "Offline"}</p>
    </div>
  );
}

function App() {
  const userData = { name: "Sophia", age: 30, isOnline: false };
  return <UserProfile user={userData} />;
}

export default App;
```

    ✅ Easier to pass structured data

6️⃣ Passing Arrays as Props

    You can pass arrays and use .map() to render lists.

📌 Example: Passing an Array of Items

```jsx
function ItemList({ items }) {
  return (
    <ul>
      {items.map((item, index) => (
        <li key={index}>{item}</li>
      ))}
    </ul>
  );
}

function App() {
  const fruits = ["Apple", "Banana", "Cherry"];
  return <ItemList items={fruits} />;
}

export default App;
```

    ✅ Dynamically render lists using .map()

7️⃣ Passing Functions as Props (Callback Props)

    Pass a function from parent to child to allow the child to communicate back.

📌 Example: Passing a Function as a Prop

```jsx
function Button({ handleClick }) {
  return <button onClick={handleClick}>Click Me</button>;
}

function App() {
  const showMessage = () => alert("Button Clicked!");

  return <Button handleClick={showMessage} />;
}

export default App;
```

    ✅ Allows child components to trigger actions in the parent

8️⃣ Props in Class Components

    In class components, props are accessed using this.props.

📌 Example: Props in a Class Component

```jsx
import React, { Component } from "react";

class Welcome extends Component {
  render() {
    return <h1>Welcome, {this.props.name}!</h1>;
  }
}

function App() {
  return <Welcome name="David" />;
}

export default App;
```

    ✅ this.props.name is used in class components

9️⃣ PropTypes – Type Checking Props

    Use prop-types to enforce type validation.

📌 Example: Validating Prop Types

```jsx
import PropTypes from "prop-types";

function UserProfile({ name, age }) {
  return <h2>{name} ({age} years old)</h2>;
}

UserProfile.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};

function App() {
  return <UserProfile name="Olivia" age={28} />;
}

export default App;
```

    ✅ Ensures name is always a string and required

### State in React JS 🏛️

    In React, state is an object that holds dynamic data and controls a component’s behavior. When state changes, the component re-renders to reflect the new data.

🔹 Key Features of State

    ✅ Mutable – Unlike props, state can be changed within the component.
    ✅ Triggers Re-renders – When state updates, React automatically re-renders the component.
    ✅ Scoped to Component – State is local to a component and cannot be accessed by others directly.
    ✅ Managed using useState (Functional Components) or this.state (Class Components).

1️⃣ Managing State in Functional Components – useState Hook

    In functional components, useState is used to manage state.

📌 Example: Simple Counter Using useState

```jsx
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </div>
  );
}

export default Counter;
```

    ✅ useState(0) initializes count with 0
    ✅ setCount(count + 1) updates the state and triggers a re-render

2️⃣ Managing State in Class Components – this.state

    In class components, state is initialized in the constructor and updated using this.setState().

📌 Example: Counter Using this.state

```jsx
import React, { Component } from "react";

class Counter extends Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (
      <div>
        <h1>Count: {this.state.count}</h1>
        <button onClick={this.increment}>Increase</button>
      </div>
    );
  }
}

export default Counter;
```

    ✅ this.state holds the state object
    ✅ this.setState() updates the state and triggers re-render

3️⃣ Updating State Correctly

    ✅ Best Practice: Use Functional Updates to Avoid Stale State

React batches updates, so using the previous state is recommended.

📌 Example: Correctly Updating State

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(prevCount => prevCount + 1); // Using previous state
  };

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={increment}>Increase</button>
    </div>
  );
}

export default Counter;
```

    ✅ Ensures count is updated correctly, even in async operations

4️⃣ State with Objects

    State can store objects instead of just numbers or strings.

📌 Example: Managing Multiple Values in State

```jsx
function UserProfile() {
  const [user, setUser] = useState({ name: "Alice", age: 25 });

  return (
    <div>
      <h1>{user.name} ({user.age} years old)</h1>
      <button onClick={() => setUser({ ...user, age: user.age + 1 })}>
        Increase Age
      </button>
    </div>
  );
}

export default UserProfile;
```

    ✅ Use ...user (spread operator) to prevent overwriting other properties

5️⃣ State with Arrays

📌 Example: Adding Items to an Array in State

```jsx
function TodoList() {
  const [tasks, setTasks] = useState(["Buy groceries", "Read a book"]);

  const addTask = () => {
    setTasks([...tasks, `New Task ${tasks.length + 1}`]);
  };

  return (
    <div>
      <ul>
        {tasks.map((task, index) => (
          <li key={index}>{task}</li>
        ))}
      </ul>
      <button onClick={addTask}>Add Task</button>
    </div>
  );
}

export default TodoList;
```

    ✅ Preserve previous state using ...tasks before adding new data

6️⃣ State Lifecycle in Class Components

State Lifecycle Methods

| Method | Purpose |
|---|---|
| constructor() | Initialize state |
| componentDidMount() | Runs after component mounts (e.g., API calls) |
| componentDidUpdate() | Runs when state updates |
| componentWillUnmount() | Runs before component unmounts |

📌 Example: Using Lifecycle Methods in a Class Component

```jsx
class Timer extends React.Component {
  constructor(props) {
    super(props);
    this.state = { seconds: 0 };
  }

  componentDidMount() {
    this.interval = setInterval(() => {
      this.setState((prevState) => ({ seconds: prevState.seconds + 1 }));
    }, 1000);
  }

  componentWillUnmount() {
    clearInterval(this.interval);
  }

  render() {
    return <h1>Time: {this.state.seconds}s</h1>;
  }
}
```

    ✅ componentDidMount() starts a timer
    ✅ componentWillUnmount() clears it to prevent memory leaks

7️⃣ State vs Props – Key Differences

|Feature | State | Props |
|---|---|---|
|Mutability  | Mutable (can change)  | Immutable (read-only) |
|Where Used |  Managed inside the component |  Passed from parent to child |
|Updates  | useState / setState  | Cannot be modified inside child |
|Triggers Re-render? |  Yes, when updated |  No, unless parent re-renders |
