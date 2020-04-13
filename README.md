<p align="left">
  <a href="https://www.npmjs.com/package/react-native-navigation-search-bar" rel="nofollow">
  <img src="https://img.shields.io/npm/v/react-native-navigation-search-bar.svg?style=flat-square" alt="version" style="max-width:100%;" />
  </a>
  <a href="https://www.npmjs.com/package/react-native-navigation-search-bar" rel="nofollow">
  <img src="http://img.shields.io/npm/l/react-native-navigation-search-bar.svg?style=flat-square" alt="license" style="max-width:100%;" />
  </a>
  <a href="https://www.npmjs.com/package/react-native-navigation-search-bar" rel="nofollow">
    <img src="http://img.shields.io/npm/dt/react-native-navigation-search-bar.svg?style=flat-square" alt="downloads" style="max-width:100%;" />
  </a>
  <hr />
</p>

<h1 align="center">
  <img src="https://github.com/lukebrandonfarrell/react-native-navigation-search-bar/blob/master/example%231.gif?raw=true"/><br/>
  React Native Navigation Search Bar
</h1>

A searcbar for [React Native Navigation](https://github.com/wix/react-native-navigation) which collapses the header when focussed. It's that simple!

## Install

```sh
 npm install react-native-navigation-search-bar --save
```

or

```sh
 yarn add react-native-navigation-search-bar
```

## Usage

This component wraps the react-native-elements [<SearchBar />](https://react-native-elements.github.io/react-native-elements/docs/searchbar.html) with extra functionality for React Native Navigation.

```js
import { RNNSearchBar } from "react-native-navigation-search-bar";

// register our drawer component with RNN
<RNNSearchBar
    componentId={componentId} // <-- RNN component id
    statusBarHeight={statusBarHeight} // <-- prop status bar height
    search={...}
    onChangeText={...}
    
 />
```

## Authors

* [**Luke Brandon Farrell**](https://lukebrandonfarrell.com/) - *Author*

## License

This project is licensed under the MIT License
