### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

  A JS framework for building single-page web apps that incorporates a virtual DOM and JSX. 

2.  What is create-react-app?

Facebook's set up for compiling the necessary components to build a react app. 

3.  What is Component Based Architecture?

Reusable sections of code that allow for minimal repetition. 

4.  What is JSX?

Javascript that acts as html and is run through a compiler provided by react. 

5.  What is the virtual DOM?

a virtual copy of the DOM. is synced in memory with the DOM that allows only changed components to have to re-render to save load times.

6.  What is unidirectional (one-way) data flow?

Data flows from top to bottom, parent to child--NOT from child to parent 

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

sets up the environment and components to run a react application, also sets destination for react app

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?

fork, git clone url, npm i, npm start 

9.  Explain what this code does:

```jsx
import React from "react";

the classname is adjusting based on the prop that is passed down from the parent component 

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
