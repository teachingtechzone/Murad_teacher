Advaced javascript started on 15th june
Ended on 6th of july

1. React Introduction
2. React using CDN
    ```
    1. <script src="https://unpkg.com/react@17/umd/react.development.js"></script>
    2. <script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js"></script>
    3. <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    ```
3. React without babel or without JSX
4. React with babel or with JSX
5. React JSX syntax
6. without react
7. VirtualDom
8. difference b/w functional and class component
9. props in class component
10. props in functional component
11. conversion from simple to fat arrow function
12. state , setState
    1. We can't change state value directly
    2. instead we use setState to change the value
13. Adding bootstrap to project
    1. npm install bootstrap
14. to get JSX intellesense goto setting and add
 "emmet.includeLanguages": {
    "javascript": "javascriptreact"
}
15. to use previous value in state , its mandatory to  access previous state
16. Event Handling
    1. don't use parenthesis in event handler 
    2. in class component don't use function keyword
    3. use onClick instead of onclick
17. Binding Event Handlers 
    1. Binding In Render Method
    2. Arrow Function In Render method
    3. Official Docs Apprch Binding in constructor
    4. As class property as arrow function
18. Component Communication
    1. Parent to Child (simple)
    2. Child to parent (tricky)
        1. we can not send data from child to parent but we can send method
        2. so in method parameter we pass data from parent to child
19. Use id as key in list
    1. index of array can cause rendering problem when adding or sorting
20. Destructuring props and state for code readability
    1. there are two ways to destructure in functional component
    2. in class component destructure it in render method
21. Conditional Rendering
    1. if/else
        1. if/else not work inside jsx
    2. Element variables
    3. Ternary conditional operator
    4. Short circuit operator
        1. For something or nothing logic
22. Css styling, inline , module  
    - naming convention for css module style sheet, file name should end with module.css
21. lifecycle methods only for class components while in functional component we use useEffect hook as lifecyle
    - There are three phases of react component
        1. mounting (render on page)
        2. updating (if props cause compoent re-render, if component state change)
        3. unmounting (when you hide a component or no longer want component)
22. Order of mounting lifecycle method
23. Fragments group list of childern without adding extra node to the DOM
24. Context api provides a way to pass data through the component tree without having to pass props down manually at every level
25. There are three steps to implement context
    1. Create Context
    2. Provide Context (In the parent compoent so that child can access them)
    3. Consume the context Value (using a function which return valid jsx)
26. Higher Order components are used to make code DRY
27. Higher Order Components are the functions which takes a component as argument and returna a new enhanced component
28. Pure components are used to render a component if the state or props is changed
29. Memo also works just like pure component but its for functional component
30. to install router `npm install react-router-dom`
