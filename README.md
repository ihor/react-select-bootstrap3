Twitter Bootstrap styles for [react-select](https://github.com/JedWatson/react-select) component. Feel free to send PRs with improvements.

Example
=======
![Example](https://github.com/ihor/react-select-bootstrap3/blob/master/example.gif?raw=true)

Installation
============
```npm i react-select-bootstrap3 --save```

Usage
=====
```jsx
import Select from 'react-select';
import { styles } from 'react-select-bootstrap3';

const options = [
    {value: 'chocolate', label: 'Chocolate'},
    {value: 'strawberry', label: 'Strawberry'},
    {value: 'vanilla', label: 'Vanilla'},
];

const select = (
    <Select
        options={options}
        styles={styles}
    />
);
```