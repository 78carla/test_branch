# RadioList

A list of radios with associated descriptions.

## Usage <a href="#usage" id="usage"></a>

```jsx
import { Component } from 'react'
import { RadioList } from '@aragon/ui'

const items = [
  {
    title: 'An option',
    description: 'This is option A',
  },
  {
    title: 'Another option',
    description: 'This is option B',
  },
]

class App extends Component {
  state = {
    selected: 0,
  }
  handleChange = index => {
    console.log(`Selected radio at index: ${index}`)
    this.setState({ selectedItem: index })
  }
  render() {
    return (
      <RadioList
        title="A radio list"
        description="You have two options:"
        items={items}
        selected={this.state.selected}
        onChange={this.handleChange}
      />
    )
  }
}
```

## Demonstration

![](<../../../../.gitbook/assets/Schermata 2022-06-25 alle 23.12.01.png>)

## Props <a href="#props" id="props"></a>

#### `className` <a href="#classname" id="classname"></a>

* Type: `String`

Sets the class name of the container.

#### `description` <a href="#description" id="description"></a>

* Type: `Node`

Use this property to add a description to the radio list.

#### `items` <a href="#items" id="items"></a>

* Type: `Array` containing objects of `{ description, title }`

Use this property to define the radio items.

#### `onChange` <a href="#onchange" id="onchange"></a>

* Type: `Function`

Propagates the `index` of the selected radio back to the parent whenever the user selects a new item.

#### `selected` <a href="#selected" id="selected"></a>

* Type: `Number` (must be an integer less than the length of `items`)
* Default: `0`

Set this property to the index of the active item.

#### `title` <a href="#title" id="title"></a>

* Type: `Node`

Use this property to add a title to the radio list.
