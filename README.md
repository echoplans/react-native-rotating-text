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
[MIT](https://github.com/echoplans/react-native-rotating-text/blob/master/LICENSE)

## Inspiration
https://github.com/adrianmcli/react-rotating-text
