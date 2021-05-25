# The Beginner's Guide to React

1. Create a user interface with Vanilla JavaScript and DOM
    - `getElementById()`: Get the excess to the element where you want to append extra elements to
    - `createElement()`: create new element
    - `appendChild()`: Append child element with content

2. Create a user interface with React's JSX syntax
    - unpkg.com: We need to include react and react-dom in order to use them. React is used to create elements and react-dom is used to render the page.
    - `React.createElement()`: specify the element and include an object of the children message and class name to create the element through React.
    - `ReactDOM.render`: render element to the specified root element

3. Create a user interface with React's JSX syntax
    - bebel: It's used to translate HTML like syntax to react in JS because using HTML like syntax to construct a page is easier than using React create element and append several children.

4. Use JSX effectively with React
    - `{}`: Anything that's provided within the curly braces will be a JS expression. The value will be the final result for JSX to render.
    - `{...props}`: JSX can take in props at a time by using the spreading operator. If there's duplicate props, the later one will overwrite the former one.  