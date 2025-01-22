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

### ⚡ Optimization Techniques in React

React applications can become slow if not optimized properly. To improve performance, speed, and efficiency, here are the best optimization techniques:

  1️⃣ Use React.memo() to Prevent Unnecessary Re-renders 🧠

  If a component always receives the same props, React re-renders it unnecessarily. React.memo() memoizes (remembers) the last rendered result and skips re-rendering if props haven’t changed.

📌 Example: Using React.memo()
```jsx
import React from "react";

const Button = React.memo(({ handleClick, label }) => {
  console.log(`Rendering button: ${label}`);
  return <button onClick={handleClick}>{label}</button>;
});

function App() {
  const handleClick = () => alert("Button Clicked!");
  return <Button handleClick={handleClick} label="Click Me" />;
}

export default App;
```
✅ Prevents re-renders if handleClick and label don’t change

  2️⃣ Use useCallback() to Memoize Functions 🏎️

  React creates a new function instance every render, which causes child components to re-render unnecessarily.
  Use useCallback() to memoize functions so they don’t get recreated.

📌 Example: Using useCallback()
```jsx
import React, { useState, useCallback } from "react";

const Child = React.memo(({ onClick }) => {
  console.log("Child re-rendered");
  return <button onClick={onClick}>Click Me</button>;
});

function App() {
  const [count, setCount] = useState(0);

  const increment = useCallback(() => {
    setCount((prevCount) => prevCount + 1);
  }, []);

  return (
    <div>
      <h1>Count: {count}</h1>
      <Child onClick={increment} />
    </div>
  );
}

export default App;
```

✅ increment function is memoized, so Child only re-renders when needed

  3️⃣ Use useMemo() to Optimize Expensive Calculations 🔥

  If your component performs heavy calculations, React will recompute them on every render.
  Use useMemo() to cache the result and avoid unnecessary re-computation.

📌 Example: Using useMemo()
```jsx
import React, { useState, useMemo } from "react";

function ExpensiveCalculation({ num }) {
  const computeFactorial = (n) => {
    console.log("Calculating factorial...");
    return n <= 1 ? 1 : n * computeFactorial(n - 1);
  };

  const factorial = useMemo(() => computeFactorial(num), [num]);

  return <h1>Factorial of {num} is {factorial}</h1>;
}

function App() {
  const [number, setNumber] = useState(5);
  return <ExpensiveCalculation num={number} />;
}

export default App;
``` 

✅ Caches factorial calculation, recomputing only when num changes

4️⃣ Use React.lazy() and Suspense for Code-Splitting ⏳

Instead of loading everything at once, use lazy loading to split the code and improve performance.

📌 Example: Lazy Loading Components
```jsx
import React, { Suspense, lazy } from "react";

const HeavyComponent = lazy(() => import("./HeavyComponent"));

function App() {
  return (
    <Suspense fallback={<h1>Loading...</h1>}>
      <HeavyComponent />
    </Suspense>
  );
}

export default App;
```
✅ Only loads HeavyComponent when needed, reducing initial load time

  5️⃣ Avoid Reconciliation with key in Lists 🔑

  React uses keys to track changes in lists.
  Always use unique keys to help React efficiently update the UI.

📌 Example: Using Unique Keys in Lists
```jsx
const users = ["Alice", "Bob", "Charlie"];

function UserList() {
  return (
    <ul>
      {users.map((user, index) => (
        <li key={index}>{user}</li>
      ))}
    </ul>
  );
}
```
✅ Use a unique id instead of index when possible

  6️⃣ Avoid Inline Functions and Objects in JSX 🚀

  Every re-render creates a new function or object, which can trigger unnecessary renders.
  Move functions outside JSX or use useCallback().

📌 Example: Avoiding Inline Function in JSX
```jsx
function App() {
  const handleClick = () => alert("Clicked!");

  return <button onClick={handleClick}>Click Me</button>;
}
```
✅ Prevents re-creating handleClick on every render

  7️⃣ Use Virtualized Lists for Large Data Sets 📜

  Rendering thousands of items at once can slow down performance.
  Use react-window or react-virtualized for efficient list rendering.

📌 Example: Using react-window for Large Lists
```jsx
import { FixedSizeList as List } from "react-window";

const items = new Array(10000).fill("Item");

function LargeList() {
  return (
    <List height={400} itemCount={items.length} itemSize={35} width={300}>
      {({ index, style }) => <div style={style}>{items[index]}</div>}
    </List>
  );
}
```
✅ Only renders visible items instead of all at once

  8️⃣ Optimize Context API with useMemo() 🎯

  React re-renders all components when the Context value changes.
  Use useMemo() to optimize context updates.

📌 Example: Optimizing Context Value with useMemo()
```jsx
import React, { createContext, useState, useMemo } from "react";

const ThemeContext = createContext();

function App() {
  const [theme, setTheme] = useState("light");

  const value = useMemo(() => ({ theme, setTheme }), [theme]);

  return (
    <ThemeContext.Provider value={value}>
      <ChildComponent />
    </ThemeContext.Provider>
  );
}
```
✅ Prevents unnecessary re-renders when context updates

  9️⃣ Avoid Unnecessary State Updates 🔄

  Updating state unnecessarily triggers extra re-renders.
  Make sure state updates only when required.

📌 Example: Preventing Extra State Updates
```jsx
const [count, setCount] = useState(0);

const increment = () => {
  setCount(prevCount => {
    if (prevCount === 10) return prevCount; // Prevent unnecessary update
    return prevCount + 1;
  });
};
```

✅ Avoids re-rendering if count is already 10


### 🛑 Error Boundaries and Error Handling in React

React applications can crash unexpectedly due to unhandled JavaScript errors in components. To prevent this, React provides Error Boundaries, which catch and handle errors gracefully.

🔴 What is an Error Boundary?

An Error Boundary is a special React component that catches JavaScript errors only in class components within its child component tree and prevents the entire app from crashing.

📌 Error Boundaries can handle:

  ✔️ Runtime errors in render(), lifecycle methods, and constructors
  ❌ Cannot handle errors in event handlers or asynchronous code

🛠 Implementing an Error Boundary

1️⃣ Create an Error Boundary Component

Use the componentDidCatch() and getDerivedStateFromError() lifecycle methods to catch errors and display a fallback UI.
```jsx
import React, { Component } from "react";

class ErrorBoundary extends Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false };
  }

  static getDerivedStateFromError(error) {
    // Update state to show fallback UI
    return { hasError: true };
  }

  componentDidCatch(error, errorInfo) {
    console.error("Caught an error:", error, errorInfo);
  }

  render() {
    if (this.state.hasError) {
      return <h1>Oops! Something went wrong. 🚨</h1>;
    }
    return this.props.children;
  }
}

export default ErrorBoundary;
```

2️⃣ Wrap Components with the Error Boundary

Now, use ErrorBoundary to wrap components that might throw errors.
```jsx
import React from "react";
import ErrorBoundary from "./ErrorBoundary";
import BuggyComponent from "./BuggyComponent";

function App() {
  return (
    <div>
      <h1>React Error Boundaries Example</h1>
      <ErrorBoundary>
        <BuggyComponent />
      </ErrorBoundary>
    </div>
  );
}

export default App;
```
3️⃣ Create a Component That Throws an Error

To test the error boundary, create a component that intentionally throws an error.
```jsx
import React, { useState } from "react";

function BuggyComponent() {
  const [throwError, setThrowError] = useState(false);

  if (throwError) {
    throw new Error("Something went wrong!");
  }

  return (
    <div>
      <h2>Click below to trigger an error:</h2>
      <button onClick={() => setThrowError(true)}>Trigger Error</button>
    </div>
  );
}

export default BuggyComponent;
```
✅ Now, when the error occurs, the error boundary catches it and prevents the entire app from crashing.

⚠️ Error Boundaries Don’t Catch These Errors

    Error Boundaries DO NOT catch:
    ❌ Errors inside event handlers
    ❌ Errors in asynchronous code (e.g., setTimeout, Promises)
    ❌ Errors in server-side rendering (SSR)
    ❌ Errors in error boundary components themselves

🛠 Handling Errors in Event Handlers

Since error boundaries don’t catch errors inside event handlers, use try-catch blocks for handling them.

📌 Example: Using try-catch in Event Handlers
```jsx
function ErrorHandlerComponent() {
  const handleClick = () => {
    try {
      throw new Error("Event handler error!");
    } catch (error) {
      alert("Caught an error: " + error.message);
    }
  };

  return <button onClick={handleClick}>Click Me</button>;
}
```
✅ Prevents app crashes by handling event handler errors manually.

🛠 Handling Errors in Async Code

Error Boundaries do not catch async errors like Promises or API calls.

📌 Example: Handling Errors in Async Code
```jsx
import React, { useState } from "react";

function AsyncComponent() {
  const [data, setData] = useState(null);
  const [error, setError] = useState(null);

  const fetchData = async () => {
    try {
      let response = await fetch("https://invalid-api-url.com");
      let result = await response.json();
      setData(result);
    } catch (err) {
      setError(err.message);
    }
  };

  return (
    <div>
      <button onClick={fetchData}>Fetch Data</button>
      {error && <p>Error: {error}</p>}
      {data && <p>Data: {JSON.stringify(data)}</p>}
    </div>
  );
}

export default AsyncComponent;
```
✅ Prevents app crashes when an API call fails.

🛠 Handling Errors in Server-Side Rendering (SSR)

React Error Boundaries do not work in SSR. Instead, use try-catch inside getServerSideProps() or getStaticProps().

📌 Example: Error Handling in SSR (Next.js)
```jsx
export async function getServerSideProps() {
  try {
    const res = await fetch("https://invalid-api-url.com");
    if (!res.ok) throw new Error("Failed to fetch data");
    const data = await res.json();
    return { props: { data } };
  } catch (error) {
    return { props: { error: error.message } };
  }
}
```
✅ Handles SSR errors gracefully.

### 🔥 Redux, React-Redux, and Redux Toolkit Explained

📌 What is Redux?

    Redux is a state management library for JavaScript applications, commonly used with React. It stores and manages global state in a centralized store, making it easier to share data across components.

📌 Key Principles of Redux:

      1.	Single Source of Truth - The entire state is stored in a single store.
      2.	State is Read-Only - Components cannot modify state directly; they must dispatch actions.
      3.	Changes are Made with Pure Functions - Reducers handle state updates purely (without modifying existing state).

🚀 Core Concepts of Redux

1️⃣ Store (Global State)

The store holds the entire application state.
```js
import { createStore } from "redux";
const store = createStore(reducer);
```
2️⃣ Actions (Events to Update State)

An action is a plain JavaScript object that describes what happened.
```js
const increment = { type: "INCREMENT" };
const decrement = { type: "DECREMENT" };
```
3️⃣ Reducers (Pure Functions to Modify State)

A reducer is a function that takes the current state and an action and returns the new state.
```js
const counterReducer = (state = 0, action) => {
  switch (action.type) {
    case "INCREMENT":
      return state + 1;
    case "DECREMENT":
      return state - 1;
    default:
      return state;
  }
};
```
4️⃣ Dispatch (Trigger an Action)

To modify state, we dispatch actions to the store.
```js
store.dispatch({ type: "INCREMENT" });
```
📦 What is React-Redux?

  React-Redux is the official React binding for Redux, allowing React components to connect to the Redux store.

📌 Why use React-Redux?
  ✅ Avoids manual store.subscribe() calls
  ✅ Automatically updates components when state changes
  ✅ Improves performance with selectors & memoization

🚀 Steps to Use React-Redux

	1.	Install React-Redux

  npm install react-redux


	2.	Provide the Redux Store to React
```jsx
import { Provider } from "react-redux";
import { createStore } from "redux";
import counterReducer from "./reducers";

const store = createStore(counterReducer);

function App() {
  return (
    <Provider store={store}>
      <Counter />
    </Provider>
  );
}

export default App;

```
	3.	Connect Components to Redux Store
```jsx
import { useSelector, useDispatch } from "react-redux";

function Counter() {
  const count = useSelector((state) => state);
  const dispatch = useDispatch();

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => dispatch({ type: "INCREMENT" })}>+</button>
      <button onClick={() => dispatch({ type: "DECREMENT" })}>-</button>
    </div>
  );
}

export default Counter;

```

    ✅ useSelector() gets state from the store
    ✅ useDispatch() sends actions to update state

🛠 What is Redux Toolkit? (RTK)

    Redux Toolkit (RTK) is the official, modern way to write Redux logic, reducing boilerplate code.

    📌 Why use Redux Toolkit?
    ✅ Less code (automates action creators & reducers)
    ✅ Built-in thunk support (for async logic)
    ✅ Immer.js for immutable state (simplifies reducers)
    ✅ Best practices included (uses slices & store setup)

🚀 Steps to Use Redux Toolkit

	1.	Install Redux Toolkit

    npm install @reduxjs/toolkit react-redux


	2.	Create a Slice (Reducers + Actions Combined)
```jsx
import { createSlice } from "@reduxjs/toolkit";

const counterSlice = createSlice({
  name: "counter",
  initialState: { value: 0 },
  reducers: {
    increment: (state) => {
      state.value += 1;
    },
    decrement: (state) => {
      state.value -= 1;
    },
  },
});

export const { increment, decrement } = counterSlice.actions;
export default counterSlice.reducer;
```

	3.	Set Up Redux Store
```jsx
import { configureStore } from "@reduxjs/toolkit";
import counterReducer from "./counterSlice";

const store = configureStore({
  reducer: {
    counter: counterReducer,
  },
});

export default store;

```
	4.	Provide the Store to React
```jsx
import { Provider } from "react-redux";
import store from "./store";
import Counter from "./Counter";

function App() {
  return (
    <Provider store={store}>
      <Counter />
    </Provider>
  );
}

export default App;

```
	5.	Use Redux Toolkit in Components
```jsx
import { useSelector, useDispatch } from "react-redux";
import { increment, decrement } from "./counterSlice";

function Counter() {
  const count = useSelector((state) => state.counter.value);
  const dispatch = useDispatch();

  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => dispatch(increment())}>+</button>
      <button onClick={() => dispatch(decrement())}>-</button>
    </div>
  );
}

export default Counter;


```
    ✅ No need to write action types manually
    ✅ Reducers directly modify state (Immer.js handles immutability)
    ✅ Store setup is automatic

### 🚀 Redux-Saga: Handling Side Effects in Redux

📌 What is Redux-Saga?

    Redux-Saga is a middleware for Redux that handles side effects (like API calls, delays, and async tasks) using generators (function*). It allows better control over asynchronous logic and improves performance.

📌 Why Use Redux-Saga?
    ✅ Manages complex async flows (chained API calls, background tasks)
    ✅ Handles concurrent & parallel tasks (like WebSocket updates)
    ✅ Automatic task cancellation (stops unnecessary API calls)
    ✅ Better error handling (using try-catch)
    ✅ Improves Redux performance

🛠 How Redux-Saga Works

    Redux-Saga listens for actions and triggers side effects (like fetching data) before updating the Redux store.

📌 Flow:
    1️⃣ Component Dispatches Action →
    2️⃣ Saga Middleware Listens →
    3️⃣ Performs Side Effect (API Call, Delay, etc.) →
    4️⃣ Dispatches New Action to Update Store

🚀 Steps to Use Redux-Saga

1️⃣ Install Redux-Saga

    npm install redux-saga

2️⃣ Create a Redux Slice (Reducers + Actions)

    Use Redux Toolkit to define the state.

📌 counterSlice.js
```js
import { createSlice } from "@reduxjs/toolkit";

const counterSlice = createSlice({
  name: "counter",
  initialState: { value: 0, loading: false, error: null },
  reducers: {
    increment: (state) => {
      state.value += 1;
    },
    decrement: (state) => {
      state.value -= 1;
    },
    fetchStart: (state) => {
      state.loading = true;
    },
    fetchSuccess: (state, action) => {
      state.value = action.payload;
      state.loading = false;
    },
    fetchFailure: (state, action) => {
      state.error = action.payload;
      state.loading = false;
    },
  },
});

export const { increment, decrement, fetchStart, fetchSuccess, fetchFailure } =
  counterSlice.actions;
export default counterSlice.reducer;
```
3️⃣ Create a Saga Function to Handle API Call

    📌 Saga functions use function* (Generators) to manage async operations.
    📌 Use yield call() to perform API calls and yield put() to dispatch actions.

📌 counterSaga.js
```jsx
import { call, put, takeEvery } from "redux-saga/effects";
import { fetchStart, fetchSuccess, fetchFailure } from "./counterSlice";

// Mock API function
const fetchCount = async () => {
  const response = await fetch("https://api.example.com/counter");
  const data = await response.json();
  return data.value;
};

// Saga to handle API call
function* fetchCounterSaga() {
  try {
    yield put(fetchStart()); // Show loading state
    const value = yield call(fetchCount); // API call
    yield put(fetchSuccess(value)); // Update store
  } catch (error) {
    yield put(fetchFailure(error.message)); // Handle error
  }
}

// Watch for dispatched actions
export function* watchCounterSaga() {
  yield takeEvery("counter/fetchStart", fetchCounterSaga);
}
```
    ✅ call(fetchCount) → Calls the API
    ✅ put(fetchSuccess(value)) → Dispatches success action
    ✅ takeEvery("counter/fetchStart", fetchCounterSaga) → Listens for actions

4️⃣ Configure Redux Store with Redux-Saga

📌 store.js
```jsx
import { configureStore } from "@reduxjs/toolkit";
import createSagaMiddleware from "redux-saga";
import counterReducer from "./counterSlice";
import { watchCounterSaga } from "./counterSaga";

const sagaMiddleware = createSagaMiddleware();

const store = configureStore({
  reducer: {
    counter: counterReducer,
  },
  middleware: (getDefaultMiddleware) =>
    getDefaultMiddleware().concat(sagaMiddleware),
});

sagaMiddleware.run(watchCounterSaga);

export default store;
```
    ✅ Creates Saga Middleware
    ✅ Adds Saga Middleware to Redux Store
    ✅ Runs Saga Watcher Function

5️⃣ Connect Redux-Saga to React Component

📌 Counter.js
```jsx
import { useSelector, useDispatch } from "react-redux";
import { increment, decrement, fetchStart } from "./counterSlice";

function Counter() {
  const { value, loading, error } = useSelector((state) => state.counter);
  const dispatch = useDispatch();

  return (
    <div>
      <h1>Count: {value}</h1>
      <button onClick={() => dispatch(increment())}>+</button>
      <button onClick={() => dispatch(decrement())}>-</button>
      <button onClick={() => dispatch(fetchStart())}>Fetch from API</button>

      {loading && <p>Loading...</p>}
      {error && <p>Error: {error}</p>}
    </div>
  );
}

export default Counter;
```
    ✅ dispatch(fetchStart()) → Triggers Saga
    ✅ Redux-Saga fetches API data and updates state

6️⃣ Provide the Store to React App

📌 App.js
```jsx
import { Provider } from "react-redux";
import store from "./store";
import Counter from "./Counter";

function App() {
  return (
    <Provider store={store}>
      <Counter />
    </Provider>
  );
}

export default App;
```
🎯 Key Redux-Saga Effects

|Effect |	Purpose |
|---|---|
| call(fn, ...args) |	Calls an async function (API call) |
| put(action) |	Dispatches an action to Redux store |
| takeEvery(actionType, sagaFn) |	Runs saga for every action of a type |
| takeLatest(actionType, sagaFn) |	Runs only the latest saga (cancels previous) |
| delay(ms) |	Delays execution (useful for debouncing) |
| fork(sagaFn) |	Runs a saga in parallel (non-blocking) |
| cancel(task) |	Cancels a running saga |


### 🚀 Redux Thunk: Simplifying Async Operations in Redux

📌 What is Redux Thunk?

    Redux Thunk is a middleware that allows Redux actions to return a function instead of a plain object. This enables us to handle asynchronous operations (like API calls) inside action creators, rather than in components.

📌 Why Use Redux Thunk?

    ✅ Handles async operations (API calls, delays, etc.)
    ✅ Simplifies API call logic inside Redux actions
    ✅ Avoids side-effects inside reducers (reducers must be pure functions)
    ✅ Easy to implement compared to Redux-Saga

🚀 How Redux Thunk Works

📌 Without Redux Thunk, Redux actions must return a plain object:
```jsx
const fetchData = () => {
  return { type: "FETCH_DATA" }; // 🚨 Only plain objects allowed
};
```
📌 With Redux Thunk, actions return a function that can handle async operations:
```jsx
const fetchData = () => {
  return async (dispatch) => {
    dispatch({ type: "FETCH_START" });
    const response = await fetch("https://api.example.com/data");
    const data = await response.json();
    dispatch({ type: "FETCH_SUCCESS", payload: data });
  };
};
```
✅ The function receives dispatch as an argument, allowing us to dispatch actions asynchronously.

🛠 Steps to Use Redux Thunk

1️⃣ Install Redux Thunk

    npm install redux-thunk

2️⃣ Create a Redux Slice (Reducers + Actions)

📌 Using Redux Toolkit (createSlice)

📌 counterSlice.js
```jsx
import { createSlice } from "@reduxjs/toolkit";

const counterSlice = createSlice({
  name: "counter",
  initialState: { value: 0, loading: false, error: null },
  reducers: {
    increment: (state) => {
      state.value += 1;
    },
    decrement: (state) => {
      state.value -= 1;
    },
    fetchStart: (state) => {
      state.loading = true;
    },
    fetchSuccess: (state, action) => {
      state.value = action.payload;
      state.loading = false;
    },
    fetchFailure: (state, action) => {
      state.error = action.payload;
      state.loading = false;
    },
  },
});

export const { increment, decrement, fetchStart, fetchSuccess, fetchFailure } =
  counterSlice.actions;
export default counterSlice.reducer;
```
3️⃣ Create a Redux Thunk Function

📌 Thunk function performs async API call and dispatches actions accordingly.

📌 counterThunk.js
```jsx
export const fetchCounter = () => {
  return async (dispatch) => {
    try {
      dispatch(fetchStart()); // Show loading state
      const response = await fetch("https://api.example.com/counter");
      const data = await response.json();
      dispatch(fetchSuccess(data.value)); // Update store
    } catch (error) {
      dispatch(fetchFailure(error.message)); // Handle error
    }
  };
};
```
    ✅ dispatch(fetchStart()) → Updates loading state
    ✅ await fetch(...) → Fetches data from API
    ✅ dispatch(fetchSuccess(data.value)) → Updates store with fetched data

4️⃣ Configure Redux Store with Thunk Middleware

📌 store.js
```jsx
import { configureStore } from "@reduxjs/toolkit";
import counterReducer from "./counterSlice";
import thunk from "redux-thunk";

const store = configureStore({
  reducer: {
    counter: counterReducer,
  },
  middleware: (getDefaultMiddleware) => getDefaultMiddleware().concat(thunk),
});

export default store;
```
    ✅ Adds Redux Thunk as middleware
    ✅ Enables async action dispatching

5️⃣ Connect Redux Thunk to React Component

📌 Counter.js
```jsx
import { useSelector, useDispatch } from "react-redux";
import { increment, decrement } from "./counterSlice";
import { fetchCounter } from "./counterThunk";

function Counter() {
  const { value, loading, error } = useSelector((state) => state.counter);
  const dispatch = useDispatch();

  return (
    <div>
      <h1>Count: {value}</h1>
      <button onClick={() => dispatch(increment())}>+</button>
      <button onClick={() => dispatch(decrement())}>-</button>
      <button onClick={() => dispatch(fetchCounter())}>Fetch from API</button>

      {loading && <p>Loading...</p>}
      {error && <p>Error: {error}</p>}
    </div>
  );
}

export default Counter;
```
    ✅ dispatch(fetchCounter()) triggers the thunk function
    ✅ Thunk function fetches API data and updates state

6️⃣ Provide the Store to React App

📌 App.js
```jsx
import { Provider } from "react-redux";
import store from "./store";
import Counter from "./Counter";

function App() {
  return (
    <Provider store={store}>
      <Counter />
    </Provider>
  );
}

export default App;

```

    ✅ Use Redux Thunk when:
    ✔️ You need simple API calls
    ✔️ You prefer async/await syntax
    ✔️ Your app doesn’t need complex async control

    ✅ Use Redux-Saga when:
    ✔️ You need complex async workflows (chained API calls, WebSockets)
    ✔️ You need background tasks (auto-refreshing data, caching)
    ✔️ You need better error handling & task cancellation

### 🚀 JavaScript for ReactJS: Essential Concepts & Best Practices

  ReactJS is built on JavaScript (ES6+), JSX, and functional programming principles. To master React, you need a strong understanding of modern JavaScript features like ES6+, functional programming, async programming, and state management.

#### 📌 1. ES6+ JavaScript Features for React

##### 1️⃣ Arrow Functions (=>)

  ✅ Concise function syntax
  ✅ Does not bind this (lexical scoping)
```js
const greet = (name) => `Hello, ${name}!`;
console.log(greet("React")); // "Hello, React!"
```

📌 Used for event handlers, map functions, and cleaner JSX components.

Example in a React component:
```jsx
const Button = ({ text }) => <button>{text}</button>;
```
##### 2️⃣ Template Literals (`)

    ✅ Allows multi-line strings & variable interpolation
```js
const name = "React";
console.log(`Welcome to ${name}!`); // "Welcome to React!"
```

📌 Used for dynamic class names, inline styles, and JSX rendering.

##### 3️⃣ Destructuring

✅ Extracts values from objects & arrays easily
```jsx
const user = { name: "John", age: 25 };
const { name, age } = user;
console.log(name, age); // "John", 25

📌 Used in props and state management:

const Card = ({ title, description }) => (
  <div>
    <h2>{title}</h2>
    <p>{description}</p>
  </div>
);
```

##### 4️⃣ Spread & Rest Operators (...)

✅ Copies, merges, and expands objects or arrays
```jsx
const arr1 = [1, 2, 3];
const arr2 = [...arr1, 4, 5]; // [1, 2, 3, 4, 5]

📌 Used to update React state immutably:

const [numbers, setNumbers] = useState([1, 2, 3]);

const addNumber = () => {
  setNumbers([...numbers, 4]); // Updates state immutably
};
```

##### 5️⃣ Default Parameters

✅ Provides default values for function parameters
```jsx
const greet = (name = "Guest") => `Hello, ${name}!`;
console.log(greet()); // "Hello, Guest!"

📌 Useful in React props to set default values

const Button = ({ label = "Click Me" }) => <button>{label}</button>;
```

##### 6️⃣ Object Property Shorthand

✅ Simplifies object creation
```jsx
const name = "React";
const framework = { name }; // { name: "React" }

📌 Used in Redux & API calls:

const fetchData = async () => {
  const response = await fetch("https://api.example.com/data");
  const data = await response.json();
  return { data }; // Shorthand for { data: data }
};
```
##### 7️⃣ Optional Chaining (?.)

✅ Prevents “Cannot read property of undefined” errors
```jsx
const user = { profile: { name: "John" } };
console.log(user.profile?.name); // "John"
console.log(user.address?.street); // undefined (no error)

📌 Used in API responses & conditional rendering:

return <p>{user?.profile?.name || "Guest"}</p>;
```
##### 8️⃣ Nullish Coalescing (??)

✅ Provides a fallback for null or undefined values
```jsx
const value = null;
console.log(value ?? "Default"); // "Default"
```
📌 Used in props & API responses:
```jsx
const title = props.title ?? "No Title Available";
```
#### 📌 2. Functional Programming Concepts in React

React encourages functional programming, using pure functions, immutability, and declarative code.

##### 1️⃣ Higher-Order Functions (HOF)

✅ Functions that take another function as an argument or return a function
```jsx
const withLogging = (fn) => (...args) => {
  console.log("Calling function with args:", args);
  return fn(...args);
};

const add = (a, b) => a + b;
const addWithLogging = withLogging(add);
console.log(addWithLogging(2, 3)); // Logs: "Calling function with args: [2, 3]" then outputs 5
```
📌 Used in Higher-Order Components (HOC):
```jsx
const withAuth = (Component) => (props) =>
  isAuthenticated ? <Component {...props} /> : <Redirect to="/login" />;
```
##### 2️⃣ Map, Filter, Reduce

✅ Transform & process data in JSX components
```js
const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map((n) => n * 2); // [2, 4, 6, 8, 10]
```
📌 Used for rendering lists:
```jsx
const users = [{ name: "Alice" }, { name: "Bob" }];

return (
  <ul>
    {users.map((user, index) => (
      <li key={index}>{user.name}</li>
    ))}
  </ul>
);
```
##### 3️⃣ Immutability

✅ State should never be modified directly
```jsx
const numbers = [1, 2, 3];
const newNumbers = [...numbers, 4]; // Correct (Immutable)
```
📌 Used in React state management:
```jsx
setState((prev) => [...prev, newItem]); // Always return a new array
```
#### 📌 3. Asynchronous JavaScript (Async/Await & Promises)

React often interacts with APIs, making async/await and Promises crucial.

##### 1️⃣ Fetching Data using async/await

```js
const fetchData = async () => {
  try {
    const response = await fetch("https://api.example.com/data");
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.error("Error fetching data:", error);
  }
};

📌 Used in React’s useEffect Hook:

useEffect(() => {
  fetchData();
}, []);
```

#### 📌 4. Event Handling in React

##### 1️⃣ Handling Events with Arrow Functions

```jsx
const handleClick = () => console.log("Button clicked!");
return <button onClick={handleClick}>Click Me</button>;
```

##### 2️⃣ Preventing Default Actions
```jsx
const handleSubmit = (e) => {
  e.preventDefault();
  console.log("Form submitted!");
};
return <form onSubmit={handleSubmit}></form>;
``

#### 📌 5. LocalStorage & SessionStorage

##### Saving & Retrieving Data
```js
localStorage.setItem("user", JSON.stringify({ name: "John" }));
const user = JSON.parse(localStorage.getItem("user"));
console.log(user.name); // "John"
```
📌 Used for authentication tokens, user preferences, etc.


### 🚀 TypeScript for React: A Complete Guide

    TypeScript enhances React development by adding static types, which improves code reliability, maintainability, and IDE support. Let’s explore the key TypeScript features for React!

#### 📌 1. Setting Up TypeScript in a React Project

To create a new React project with TypeScript:

    npx create-react-app my-app --template typescript

For an existing project, install TypeScript and required types:

    npm install typescript @types/react @types/react-dom --save-dev

Then, rename .js files to .tsx (for React components) and .ts (for regular TypeScript files).

#### 📌 2. TypeScript Basics in React

##### 1️⃣ Typing Props in Functional Components

```ts
type ButtonProps = {
  label: string;
  onClick: () => void;
};

const Button: React.FC<ButtonProps> = ({ label, onClick }) => {
  return <button onClick={onClick}>{label}</button>;
};
```

✔️ Ensures label is a string and onClick is a function
✔️ Provides auto-completion and type checking in IDE

##### 2️⃣ Typing Props with Optional & Default Values

```ts
type CardProps = {
  title: string;
  description?: string; // Optional prop
};

const Card: React.FC<CardProps> = ({ title, description = "No description" }) => {
  return (
    <div>
      <h2>{title}</h2>
      <p>{description}</p>
    </div>
  );
};
```

✔️ description is optional (?) and has a default value

##### 3️⃣ Typing State with useState

```ts
import { useState } from "react";

const Counter = () => {
  const [count, setCount] = useState<number>(0); // Explicitly defining type

  return <button onClick={() => setCount(count + 1)}>Count: {count}</button>;
};
```

✔️ Ensures count is always a number
✔️ Prevents unintended type errors

##### 4️⃣ Typing Events in React

```ts
const handleChange = (event: React.ChangeEvent<HTMLInputElement>) => {
  console.log(event.target.value);
};

return <input type="text" onChange={handleChange} />;
```

✔️ Correctly types event handlers
✔️ Prevents unexpected event object issues

##### 5️⃣ Typing Functions in Props

```ts
type CallbackProps = {
  onSubmit: (data: string) => void;
};

const Form: React.FC<CallbackProps> = ({ onSubmit }) => {
  return <button onClick={() => onSubmit("Hello!")}>Submit</button>;
};
```

✔️ Ensures onSubmit receives a string argument

#### 📌 3. Advanced TypeScript in React

##### 1️⃣ Using interface vs type

Both are used to define types, but interfaces are extendable.
```ts
interface User {
  name: string;
  age: number;
}

type UserType = {
  name: string;
  age: number;
};
```

✔️ Use interface for object structures
✔️ Use type for union types and more flexibility

##### 2️⃣ Typing Components with Generics

Generics allow components to be reusable with different data types.
```tsx
type ListProps<T> = {
  items: T[];
  renderItem: (item: T) => JSX.Element;
};

const List = <T,>({ items, renderItem }: ListProps<T>) => (
  <ul>{items.map(renderItem)}</ul>
);

const users = [{ name: "Alice" }, { name: "Bob" }];
<List items={users} renderItem={(user) => <li>{user.name}</li>} />;
```

✔️ Creates a generic list component for any data type

##### 3️⃣ Typing Context API

```ts
import { createContext, useContext } from "react";

type Theme = "light" | "dark";
const ThemeContext = createContext<Theme>("light");

const useTheme = () => useContext(ThemeContext);
```

✔️ Ensures correct types for useContext hooks

##### 4️⃣ Typing Redux with TypeScript

```ts
type CounterState = {
  count: number;
};

const initialState: CounterState = { count: 0 };
```
✔️ Ensures strict state types in Redux

#### 📌 4. TypeScript Utility Types in React

##### 1️⃣ Partial - Makes all properties optional

```ts
type User = { name: string; age: number };
const updateUser = (user: Partial<User>) => {};
updateUser({ name: "John" }); // Valid
```

##### 2️⃣ Pick<T, K> - Picks specific properties

```ts
type User = { name: string; age: number; email: string };
type UserName = Pick<User, "name">; // { name: string }
```

##### 3️⃣ Omit<T, K> - Omits specific properties

```ts
type UserWithoutEmail = Omit<User, "email">; // { name: string, age: number }
```

#### 📌 5. TypeScript Best Practices in React

    ✅ Use type for props & function signatures
    ✅ Use interface for objects & class components
    ✅ Always define return types for functions
    ✅ Prefer React.FC<Props> for components
    ✅ Use useState<Type> for strongly-typed state
    ✅ Use utility types (Pick, Omit, Partial) to enhance maintainability
