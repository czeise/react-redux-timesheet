- React types
  - Functional components (no state)
  - Class components (keeps track of state, extends React.Component)
  - Minimal performance difference between the two
- `children` prop given to a component contains anything given to a component
  - https://react-training.objectpartners.com/slidedeck/#/3/24
- JSX Expression Bindings
  - Embeds any javascript expression in JSX by wrapping it in curly braces
  - ```
    const Hello = props => {
      return (
        <h1>Hello {props.name}</h1>
      );
    };
    ```