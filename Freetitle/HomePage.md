

### React Fragment
A common pattern in React is for a component to return multiple elements. Fragments let you **group a list of children** without adding extra nodes to the DOM.
[document](https://reactjs.org/docs/fragments.html#short-syntax)
```
class Columns extends React.Component {
  render() {
    return (
      <React.Fragment>
        <td>Hello</td>
        <td>World</td>
      </React.Fragment>
    );
  }
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzM4MjgxMTgzXX0=
-->