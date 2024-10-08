
This is the lesson from codecademy:

https://www.codecademy.com/paths/build-web-apps-with-react/tracks/react-components-interacting/modules/components-and-props/lessons/components-render-each-other/exercises/component-in-render-function-apply



### Components Render Other Components

**Apply a Component in a Render Function**


You may have noticed that you’ve seen this behavior before!

In the previous lessons, when we defined components and exported them. We usually exported them into our top-level file, App.js. Inside App.js, we imported components and returned them inside our App component—which are then exported to be rendered!
```
import Button from './Button'

function App() {
  return <Button />;
}

export default App;
```
Look familiar? This ability allows us to separate components into smaller functions and connect them together to make more complex components!

We can treat it as the Button component is a child of the parent App component. By breaking a component into extracted smaller components, we can reuse the individual parts when necessary.

