Q1. What is react?
React is a library for building composable user interfaces. It encourages the creation of reusable UI components, which present data that changes over time. Lots of people use React as the V in MVC. React abstracts away the DOM from you, offering a simpler programming model and better performance. React can also render on the server using Node, and it can power native apps using React Native. React implements one-way reactive data flow, which reduces the boilerplate and is easier to reason about than traditional data binding.

Q2. Differentiate between functional and class components. What do you prefer to use and in which situation?
First, the clear difference is the syntax. Just like in their names, a functional component is just a plain JavaScript function that returns JSX. A class component is a JavaScript class that extends React. Component which has a render method. I prefer Class Components; class components are important to understand React flow and lifecycle methods.

Q3. What is State and Props in react?
Props allow you to pass data from one component to other components as an argument. State holds information about the components.

Q4. What is the difference between State and Props? How do you decide what is controlled by state and what is controlled by pros?
Props are known as properties it can be used to pass data from one component to another. Props cannot be modified, read-only, and Immutable while State represents parts of an application that can change. Each component can have its State. The state is Mutable, and It is local to the component only. Props are external and controlled by whatever renders the component. The State is internal and controlled by the React Component itself.

Q5. What is Virtual DOM and how it works?
The virtual DOM (VDOM) is a programming concept where an ideal, or “virtual”, representation of a UI is kept in memory and synced with the “real” DOM by a library such as React DOM. This process is called reconciliation. The virtual DOM provides a mechanism that abstracts manual DOM manipulations away from the developer, helping us write more predictable code.

Q6. What is the importance of Key in the map?
Almost every React application displays an array list of some kind using the method map. And react tells us that for each element of that list that we return for rendering, we must provide a unique key prop. 

Q7. What is the life- cycle methods in react?
Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting.


Q8. Which life- cycle method will you use when calling an API?

For the answer on if API call should be made in componentDidMount () or componentWillMount () is a broad discussion topic with most of the people suggesting to making your API calls in componentDidMount ().
Also, componentWillMount () method has been deprecated.
For your code not giving the desired outcome. It is because your API call is returning a promise and to get a result from it you need to use await before it

Q9. How do we access the parent component in a child and vice versa. (in react)?
Ans. Following are the steps to pass data from child component to parent component: 1.In the parent component, create a callback function. ... 2.Pass the callback function to the child as a props from the parent component. 3.The child component calls the parent callback function using props and passes the data to the parent component.

Q10. Have you used Context?
            Yes.

Q11. How to connect react with backend?
Ans. Building the frontend React application. First, we will create a React application. Open your terminal and run the following command to create a React application. ... Step 2: Building the Backend Node. js server. Installing the dependencies. ... Step 3: Connect React with Node. js. Open the App.

Q12. Why use Redux in react?
Ans. Redux itself is a standalone library that can be used with any UI layer or framework, including React, Angular, Vue, Ember, and vanilla JS. Although Redux and React are commonly used together, they are independent of each other.

Q13. Explain how to work with redux?
Ans. The way Redux works is simple. There is a central store that holds the entire state of the application. Each component can access the stored state without having to send down props from one component to another. There are three core components in Redux — actions, store, and reducers.

Q14. What is the container pattern?
Ans. Container is an informal term for a component that is connected to a Redux store.

Q15. What is middleware used for?
Ans. Redux Middleware allows you to intercept every action sent to the reducer so you can make changes to the action or cancel the action.
