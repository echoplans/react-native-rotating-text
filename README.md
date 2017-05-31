# react-native-rotating-text

[![npm version](https://badge.fury.io/js/react-native-rotating-text.svg)](https://badge.fury.io/js/react-native-rotating-text)

![effect showcase](http://i.imgur.com/AC5g7KD.gif)

A typewriter type effect for text in react native. React-native port of react-rotating-text.

## Installation

```
npm install react-native-rotating-text --save
```

## Usage

```jsx
import RotatingText from 'react-native-rotating-text'

<RotatingText
  style={styles.rotate}
  items={['first', 'second', 'third']}
/>
```

### Properties

**style (*number*)**  
*(default: {})*  
Any style object you want to appy on Text.

**items (*array*)**  
*(default: ['first', 'second', 'third'])*  
The array of strings to be cycled through.

**color (*string*)**  
*(default: 'inherit')*  
This specifies the color of the text.

**cursor (*boolean*)**  
*(default: true)*  
If set to true, it will display the cursor after the text.

**pause (*integer*)**  
*(default: 1500)*  
The number of milliseconds to pause after the text has just finished being typed out.

**emptyPause (*integer*)**  
*(default: 1000)*  
The number of milliseconds to pause while no text is being displayed (i.e. after deleting has just finished).

**eraseMode (*string*)**  
*(default: 'erase')*
This specifies the erasing mode. May be set to "erase" or "overwrite".

**typingInterval (*integer*)**  
*(default: 50)*  
The number of milliseconds between each typing action.

**deletingInterval (*integer*)**  
*(default: 50)*  
The number of milliseconds between each deleting action.

## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Inspiration
https://github.com/adrianmcli/react-rotating-text
