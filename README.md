# react-digital-number
A react component to show digital number

### Demo: [codepen](https://codepen.io/fredxingxing/pen/BajQLxx) | src example

## Use and Setup

`npm install --save react-digital-number`

#### Demo.js

```js
import DigitalNumber from 'react-digital-number'

const Demo = props => (
  <div>
     <DigitalNumber 
     nums={nums}   // nums is the number your wanna show (defualt '123'
     color:'#FF0000', // the active line color of number
     unActiveColor: '#22221e', // the unactive line color of number
     backgroundColor: '#000', // digital number container's background color
     />
  </div>
)
```
![Image text](https://raw.githubusercontent.com/Fredxingxing/react-digital-number/master/images/demo.png)
