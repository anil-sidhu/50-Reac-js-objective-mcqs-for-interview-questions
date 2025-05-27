# React-50-Interview-Questions-2025


**1. What is the primary motivation behind the introduction of React Hooks?**
```js
a) To replace ReactDOM.render()
b) To enable state and lifecycle features in functional components
c) To improve React's server-side rendering capabilities
d) To enforce stricter type checking
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: b) To enable state and lifecycle features in functional components
</ul>
</details>


**2. Which function is used to create a root for a React application in React 18 and later??**
```js
a) ReactDOM.render()
b) ReactDOM.hydrate()
c) ReactDOM.createRoot()
d) ReactDOM.mount()
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: c) ReactDOM.createRoot()
</ul>
</details>


**3. What is the main benefit of "Automatic Batching" in React 18?**
```js
a) It automatically re-renders components after every state update.
b) It groups multiple state updates into a single re-render for better performance.
c) It batches API requests for faster data fetching.
d) It automatically optimizes image loading.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) It groups multiple state updates into a single re-render for better performance.
</ul>
</details>


** 4.Which of the following describes JSX??**
```js
a) A template language for defining styles.
b) A runtime environment for JavaScript.
c) A syntax extension for JavaScript that looks like HTML.
d) A database query language.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) A syntax extension for JavaScript that looks like HTML.
</ul>
</details>



**5. What is the significance of the key prop in React lists?**
```js
a) It provides unique styling for each list item.
b) It helps React identify which items have changed, are added, or removed, for efficient updates.
c) It dictates the order of elements in the DOM.
d) It is purely for developer readability and has no functional impact.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) It helps React identify which items have changed, are added, or removed, for efficient updates.
</ul>
</details>



**6.How do you typically pass data from a parent component to a child component in React? **
```js
) Via context only
b) Via props
c) Via state in the child component
d) By directly accessing the parent's DOM
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Via props
</ul>
</details>


*** 7.What is the purpose of the StrictMode component in React? ***
```js
a) To enforce strict JavaScript syntax.
b) To enable server-side rendering.
c) To highlight potential problems and deprecated practices in development mode.
d) To optimize production build performance.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer:c) To highlight potential problems and deprecated practices in development mode.
</ul>
</details>



**8. What is the core concept behind React's "reconciliation" process? **
```js
a) Manually updating the DOM based on state changes.
b) Comparing the Virtual DOM with the real DOM to efficiently update the UI.
c) Fetching data from a server and updating the state.
d) Bundling JavaScript files for deployment.

```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Comparing the Virtual DOM with the real DOM to efficiently update the UI.
</ul>
</details>



**9. Which of the following is considered a best practice for managing component-specific state in functional components? **
```js
a) Using a global state management library.
b) Direct DOM manipulation.
c) The useState hook.
d) Passing data via refs.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) The useState hook.
</ul>
</details>



** 10. What is the benefit of integrating TypeScript with React projects? **
```js

a) Faster compilation times.
b) Better developer tooling, type safety, and reduced runtime errors.
c) Automatic performance optimization.
d) Enables direct database access.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Better developer tooling, type safety, and reduced runtime errors.
</ul>
</details>



** 11. When does the useEffect hook with an empty dependency array ([]) run? **
```

a) After every render.
b) Only on the initial render (mount) and clean-up on unmount.
c) Whenever any state or prop changes.
d) Before the component mounts.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Only on the initial render (mount) and clean-up on unmount.
</ul>
</details>



**12. What does the return statement inside useEffect with a non-empty dependency array typically represent? **
```js 
a) The next state value.
b) A cleanup function for the effect.
c) A JSX element to render.
d) A promise to be resolved.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A cleanup function for the effect.
</ul>
</details>


** 13. Which hook is designed for managing complex state logic that involves multiple sub-values or when the next state depends on the previous one? **
```js
a) useState
b) useEffect
c) useContext
d) useReducer
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) useReducer
</ul>
</details>


**14. What is the primary use case for useRef? t**
```js
a) To manage component state.
b) To perform side effects.
d) To subscribe to external stores.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) To directly access DOM elements or persist mutable values across renders without causing re-renders.
</ul>
</details>


*** 15. When would you typically use useCallback? ***
```js
a) To prevent a function from being called.
b) To memoize a computed value that is expensive to calculate.
c) To memoize a function definition to prevent unnecessary re-creations, often when passing callbacks to optimized child components.
d) To replace a class component.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) To memoize a function definition to prevent unnecessary re-creations, often when passing callbacks to optimized child components.
</ul>
</details>


*** 16. What is the purpose of useMemo? ***
```js
a) To memoize a function so it's not redefined on every render.
b) To memoize a computed value, preventing expensive recalculations unless its dependencies change.
c) To create a persistent reference to a DOM node.
d) To manage asynchronous operations.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) To memoize a computed value, preventing expensive recalculations unless its dependencies change.
</ul>
</details>

*** 17. Which new hook introduced in React is used to generate unique IDs for related elements on both the client and server? ***
```js
a) useTransition
b) useDeferredValue
c) useId
d) useSyncExternalStore
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) useId
</ul>
</details>


** 18. What does the useTransition hook facilitate in React ? **
```js
a) Synchronous updates that block the main thread.
b) Marking specific state updates as "transitions" (non-urgent) to keep the UI responsive.
c) Performing immediate, high-priority updates.
d) Handling component unmounting.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Marking specific state updates as "transitions" (non-urgent) to keep the UI responsive.
</ul>
</details>


**19 The useDeferredValue hook is similar to useTransition but for what purpose? ** 
```js
a) To defer state updates in a queue.
b) To defer updating a value until a more urgent update has completed, improving responsiveness.
c) To defer component unmounting.
d) To defer prop passing.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) To defer updating a value until a more urgent update has completed, improving responsiveness.
</ul>
</details>


**20. What is the role of useSyncExternalStore in React  **
```js
a) To manage local component state.
b) To subscribe to external, mutable data sources (like Redux stores or browser APIs) and ensure React components re-render when they change.
c) To create custom hooks.
d) To optimize network requests.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) To subscribe to external, mutable data sources (like Redux stores or browser APIs) and ensure React components re-render when they change.
</ul>
</details>


**21 What is "prop drilling"? **
```js
a) An optimized way of passing props.
c) A method for drilling into a component's internal state.
d) A technique for validating prop types.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) The practice of passing data through multiple layers of nested components, even if intermediate components don't need the data.
</ul>
</details>

**22. Which React API is most commonly used to avoid "prop drilling"**
```js
a) useRef
b) Context API
c) useReducer
d) ReactDOM.createPortal
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Context API
</ul>
</details>


**23 What is a Higher-Order Component (HOC)? **
```js
a) A component that renders other components.
b) A function that takes a component as an argument and returns a new component with enhanced props or behavior.
c) A component with a very large number of props.
d) A component that uses many hooks.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A function that takes a component as an argument and returns a new component with enhanced props or behavior.
</ul>
</details>


**24 What is the primary benefit of React.memo **
```js
a) To prevent the component from ever rendering.
b) To prevent unnecessary re-renders of functional components if their props (and state, if applicable) haven't shallowly changed.
c) To force a re-render.
d) To manage global state.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) splice()
</ul>
</details>


**25 What is the purpose of "React Fragments"? **
```js
a) To create a new component.
b) To group multiple elements without adding an extra node to the DOM.
c) To conditionally render elements.
d) To enable concurrent mode.

```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) To group multiple elements without adding an extra node to the DOM.
</ul>
</details>

**26 Which concept allows React to "pause" rendering and yield control to the browser, making the UI more responsive during heavy computations? **
```js
a) Synchronous rendering
b) Concurrent Rendering (or Concurrent Mode)
c) Batching
d) Server-Side Rendering (SSR)
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer:  b) Concurrent Rendering (or Concurrent Mode)
</ul>
</details>


**27. What are "React Server Components" (RSCs)? **
```js
a) Components that only render on the server and send pure HTML to the client.
b) Components that allow developers to build UIs that span across server and client, enabling efficient data fetching and reducing client-side JavaScript.
c) Components that run exclusively in Web Workers.
d) Deprecated components for legacy applications.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer:b) Components that allow developers to build UIs that span across server and client, enabling efficient data fetching and reducing client-side JavaScript.
</ul>
</details>


**28 How do "React Server Functions" (RSFs) relate to React Server Components? **
```js
a) They are the client-side counterparts of RSCs.
b) They are functions that run on the server and can be called from client-side code, often used for data mutations.
c) They are internal React core functions.
d) They define the styling for RSCs.
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) They are functions that run on the server and can be called from client-side code, often used for data mutations.
</ul>
</details>


**29.What is the primary benefit of "code splitting" and "lazy loading" in React? **
```js
a) Reduced development time.
b) Improved initial load performance by loading only necessary code on demand.
c) Enhanced security.
d) Simplifies component testing.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Improved initial load performance by loading only necessary code on demand.
</ul>
</details>


** 30. Which React feature typically works with React.lazy to provide a fallback UI while a dynamically imported component is loading **
```
a) React.Fragment
b) React.Suspense
c) React.memo
d) ReactDOM.createPortal
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) React.Suspense
</ul>
</details>



**31 Which of the following is generally considered a good practice for structuring a React project? **
```js
a) Keeping all components in a single file.
b) Grouping files by feature or domain, rather than by type (e.g., all components in one folder, all hooks in another).
c) Avoiding the use of a src directory.
d) Using only inline styles for all components.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Grouping files by feature or domain, rather than by type (e.g., all components in one folder, all hooks in another).
</ul>
</details>


** 32. Which features are not so much useful in react 19? **
```js
a) useMemo
b) useCallback
c) HOC
d) All of above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of above
</ul>
</details>


**33. Which statement about arrow functions is true? **
```js
a) They do not bind this
b) They can be used as constructors
c) They have a prototype property
d) They support arguments keyword
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) They do not bind this
</ul>
</details>


**34 Output of follow code? **
```js
function tryFruits(...fruits)
{
console.log(...fruits)
}

tryFruits('apple','banana','grapes')
```
```js
a) ['apple', 'banana', 'grapes']
b) {'apple', 'banana', 'grapes'}
c) 'apple 'banana grapes'
d) 'apple'
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a)  ['apple', 'banana', 'grapes']
</ul>
</details>


**35. What is the purpose of JavaScript Promises?**
```js
a) Handle synchronous code
b) Handle asynchronous operations
c) Block execution until resolved
d) Replace all callbacks
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Handle asynchronous operations
</ul>
</details>


**36. Which state is NOT valid for a Promise?**
```js
a) Pending
b) Fulfilled
c) Rejected
d) Running
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Running
</ul>
</details>


**37. Use of Await keyword ?**
```js
a) wait for an asynchronous operation to finish before continuing the execution
b) make promise
c) atop execution  
d) all of above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) wait for an asynchronous operation to finish before continuing the execution
</ul>
</details>


**38. Which method selects an element by ID?**
```
a) document.getElementofId()
b) document.getElementById()
c) document.selectElementById()
d) document.selectById()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) document.getElementById()
</ul>
</details>



**39 Which event is triggered when an input field loses focus?**
```js
a) click
b) blur
c) focus
d) change
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) blur
</ul>
</details>


**40. Which method adds an event listener to an element?**
```js
a) element.addEventListener()
b) element.attachEvent()
c) element.onEvent()
d) element.setEventListener()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) element.addEventListener()
</ul>
</details>


**41. What does event.preventDefault() do?**
```js
a) Stops the default action of an event
b) Stops event propagation
c) Prevents event from being attached
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Stops the default action of an event
</ul>
</details>

**43. What is localStorage used for?**
```js
a) Storing session data
b) Storing data persistently in the browser
c) Making API requests
d) Caching images
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Storing data persistently in the browser
</ul>
</details>


**44 Which method converts a JavaScript object into a JSON string?**
```js
a) JSON.stringify()
b) JSON.parse()
c) toJSON()
d) parseJSON()
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) JSON.stringify()
</ul>
</details>


**45 What will console.log(parseInt("10px")) return?**
```js
a) 10
b) NaN
c) "10px"
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) 10
</ul>
</details>


**46. Which method executes a function repeatedly with a time interval? **
```js
a) setInterval()
b) setTimeout()
c) repeat()
d) setLoop()
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) setInterval()
</ul>
</details>



** 47. How do you check if a variable is an array?**
```js
a) typeof x === "array"
b) x.isArray()
c) Array.isArray(x)
d) x instanceof Object
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Array.isArray(x)
</ul>
</details>




** 48. What is a closure in JavaScript?**
```js
a) A function inside another function that has access to its parent’s scope
b) A block of code that runs automatically
c) A way to define private variables
d) Both a and c
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Both a and c
</ul>
</details>



**49. Which of the following is true about closures?**
```js
a) Closures have access to their own scope
b) Closures have access to their parent function's scope
c) Closures have access to global scope
d) All of the above
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>

**50.What will this code output?**
```js
function outer() {
    let count = 0;
    return function inner() {
        count++;
        console.log(count);
    };
}
const counter = outer();
counter();
counter();
```

```js
a) 1 2
b) 0 1
c) 1 1
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) 1 2
</ul>
</details>


**51. Which statement about var and let is true?**
```js
a) Both are function-scoped
b) var is function-scoped, let is block-scoped
c) Both are block-scoped
d) var allows redeclaration, let doesn’t
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) var is function-scoped, let is block-scoped
</ul>
</details>


**52. What will console.log(x); var x = 10; output?**
```js
a) 10
b) undefined
c) ReferenceError
d) NaN
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) undefined
</ul>
</details>


** 53. Which statement is used for error handling in JavaScript?**
```js
a) try...catch
b) throw
c) finally
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


**54 What happens if an error occurs inside the try block?**
```js
a) The script stops execution
b) The error is caught in the catch block
c) The script crashes
d) The error is ignored
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) The error is caught in the catch block
</ul>
</details>


**55. What will console.log(x); inside a try block with no catch or finally do?**
```js
a) Print undefined
b) Print null
c) Throw a ReferenceError
d) Nothing
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Throw a ReferenceError
</ul>
</details>


**56. Which method is used to generate a custom error?**
```js
a) throw new Error()
b) console.error()
c) generateError()
d) raiseError()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) throw new Error()
</ul>
</details>


**57. What will finally do in a try-catch-finally block?**
```js
a) Execute only if no error occurs
b) Execute only if an error occurs
c) Always execute
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Always execute
</ul>
</details>


**58. OOP (Object-Oriented Programming) in JavaScript
Which keyword is used to create a class in JavaScript?**
```js
a) class
b) function
c) Class
d) new Class

```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) class
</ul>
</details>

**59. What is the purpose of the constructor method in a class?**
```js
a) To create private variables
b) To initialize object properties
c) To call another class
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) To initialize object properties
</ul>
</details>



**60. Which keyword is used for inheritance in JavaScript?**
```js
a) implements
b) extends
c) inherits
d) prototype
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) extends
</ul>
</details>



**61. Which method in a class is used to call the parent class constructor?**
```js
a) parent()
b) super()
c) this()
d) constructor()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) super()
</ul>
</details>


**62 Which statement about JavaScript classes is true?**
```js
a) They support multiple inheritance
b) They are syntactic sugar over prototypes
c) They can be redeclared
d) They do not support inheritance
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) They are syntactic sugar over prototypes
</ul>
</details>


**63 Web APIs & Asynchronous JavaScript**
```js
Which API is used for making HTTP requests in JavaScript?
a) XMLHttpRequest
b) Fetch API
c) Axios
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


**64. Which method sends a GET request using Fetch API?** 
```js
a) fetch(url)
b) fetch(url, { method: 'GET' })
c) Both a and b
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Both a and b
</ul>
</details>


**65. What does navigator.geolocation.getCurrentPosition() do?**
```js
a) Gets user’s IP address
b) Gets user’s location
c) Opens a Google Maps page
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Gets user’s location
</ul>
</details>


**66. Which storage API stores data persistently?**
```js
a) localStorage
b) sessionStorage
c) cookies
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) localStorage
</ul>
</details>


**67. How can you set an interval in JavaScript?**
```js
a) setTimeout()
b) setInterval()
c) setRepeat()
d) Interval()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) setInterval()
</ul>
</details>



**68 Which method removes an element from an array?**
```js
a) splice()
b) slice()
c) remove()
d) delete()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) splice()
</ul>
</details>


**69. Which JavaScript engine is used in Google Chrome?**
```js
a) SpiderMonkey
b) V8
c) Chakra
d) Nitro
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) V8
</ul>
</details>

**70. Which method converts a string into a number?**
```js
a) parseInt()
b) Number()
c) + (unary plus)
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


** 71. Which function generates a random number between 0 and 1?**
```js
a) Math.random()
b) random()
c) generateRandom()
d) Math.rand()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Math.random()
</ul>
</details>



** 72. Which of the following is a falsy value in JavaScript?**
```js
a) "false"
b) "0"
c) undefined
d) "undefined"
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) undefined
</ul>
</details>


**73 What will console.log([] == false); return?**
```js
a) true
b) false
c) undefined
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) true
</ul>
</details>



**74. Which of the following is NOT a primitive data type in JavaScript?**
```js
a) Number
b) String
c) Object
d) Symbol
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Object
</ul>
</details>

**75 How do you deep clone an object in JavaScript?**
```js
a) Object.assign({}, obj)
b) JSON.parse(JSON.stringify(obj))
c) obj.clone()
d) obj.copy()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) JSON.parse(JSON.stringify(obj))
</ul>
</details>


**76. What is the output of console.log(2 + "2" - 1);?**
```js
a) "21"
b) 21
c) "22"
d) 1
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) 21
</ul>
</details>



**77. Which method is used to filter elements from an array?**
```js
a) map()
b) filter()
c) reduce()
d) slice()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) filter()
</ul>
</details>



**78 Which function combines array elements into a single value?**
```js
a) reduce()
b) map()
c) join()
d) concat()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) reduce()
</ul>
</details>



**79. What does the following code return?**
```js
console.log([1, 2, 3].map(num => num * 2));
```
```js
a) [2, 4, 6]
b) [1, 4, 9]
c) [1, 2, 3]
d) [2, 3, 4]
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) [2, 4, 6]
</ul>
</details>


**80. Which of the following is NOT an immutable operation?***
```js
a) map()
b) filter()
c) splice()
d) concat()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) splice()
</ul>
</details>


**81. What is the event loop in JavaScript?**
```js
a) A process that handles function calls
b) A mechanism that allows async operations
c) A feature that prevents infinite loops
d) A method to execute code
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A mechanism that allows async operations
</ul>
</details>


**82. Which of the following executes first in the event loop?**
```js
a) setTimeout()
b) setInterval()
c) Promise.resolve().then()
d) console.log()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) console.log()
</ul>
</details>



**83. Which queue does setTimeout() use in JavaScript?**
```js
a) Microtask queue
b) Callback queue
c) Event loop queue
d) Execution stack
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Callback queue
</ul>
</details>


**84. What will be the output of this code?**
```js
console.log("A");
setTimeout(() => console.log("B"), 0);
console.log("C");
```
```js
a) A B C
b) A C B
c) B A C
d) C A B
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A C B
</ul>
</details>

**85. Which of the following is a best practice in JavaScript?**
```js
a) Using == instead of ===
b) Avoiding global variables
c) Using var instead of let
d) Nesting loops as deep as possible
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Avoiding global variables
</ul>
</details>


**86. What does "debouncing" do in JavaScript?**
```js
a) Delays function execution until a pause in events
b) Executes a function immediately
c) Runs a function continuously
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Delays function execution until a pause in events
</ul>
</details>


**87. What does "throttling" do?**
```js
a) Executes a function only at fixed intervals
b) Prevents a function from running
c) Removes unnecessary function calls
d) Stops event propagation
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Executes a function only at fixed intervals
</ul>
</details>


**88. Which of the following improves JavaScript performance?**
```js
a) Minifying JavaScript files
b) Using lazy loading
c) Avoiding unnecessary DOM manipulations
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


**89. What is the best way to check if a variable is null or undefined?**
```js
a) if (x == null)
b) if (typeof x === "null")
c) if (x === null || x === undefined)
d) if (x == undefined)
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) if (x === null || x === undefined)
</ul>
</details>


**90. What does document.createElement('div') do?**
```js
a) Creates and appends a div
b) Creates a div but does not append it
c) Selects an existing div
d) Deletes all div elements
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Creates a div but does not append it
</ul>
</details>


**91. Which API is used to create animations in JavaScript?**
```js
a) WebGL
b) requestAnimationFrame()
c) animateCSS()
d) window.setInterval()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) requestAnimationFrame()
</ul>
</details>



**92. Which function removes whitespace from both ends of a string?**
```js
a) trim()
b) slice()
c) removeSpace()
d) strip()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) trim()
</ul>
</details>


**93. Which method removes the last element from an array?**
```js
a) pop()
b) shift()
c) splice()
d) removeLast()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) pop()
</ul>
</details>

**94. What is the output of the following code?**
```js
console.log(myFunc);
function myFunc() {
    return "Hello";
}
```
```
A) undefined
B) ReferenceError: myFunc is not defined
C) [Function: myFunc]
D) TypeError: myFunc is not a function

```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) ƒ myFunc() { return "Hello"; }
</ul>
</details>

**95. Which of the following is an example of a higher-order function?**
```js
a) A function that returns another function
b) A function with a return type of void
c) A function that has a loop inside
d) A function that only contains if-else statements
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) A function that returns another function
</ul>
</details>

**96. Which method is used to handle asynchronous functions in JavaScript?**
```js
a) setTimeout()
b) Promise.then()
c) async/await
d) All of the above
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>

 **97. Which of the following is NOT true about closures?**
 ```js
 a) A closure allows a function to retain access to variables from its outer scope.
b) Closures are created every time a function is invoked.
c) Closures help in data encapsulation.
d) Closures cannot access global variables.
 ```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Closures cannot access global variables.

</ul>
</details>

**98. What will be the output of the following code?**
```js
const obj = {
    value: 42,
    getValue: () => {
        return this.value;
    }
};
console.log(obj.getValue());
```
```js
a) 42
b) undefined
c) ReferenceError
d) null
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) undefined
</ul>
</details>

**99 What will be the output of the following asynchronous function?**
```js
async function foo() {
    return "Hello";
}
console.log(foo());
```
```js
a) "Hello"
b) Promise { "Hello" }
c) undefined
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Promise { "Hello" }
</ul>
</details>

**100. What is currying in JavaScript?**
```js
a) A technique where a function is transformed into a sequence of unary (one-argument) functions.
b) A method to execute functions asynchronously.
c) A way to cache function results for optimization.
d) A technique to convert a function into a class.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) A technique where a function is transformed into a sequence of unary functions.	
</ul>
</details>


