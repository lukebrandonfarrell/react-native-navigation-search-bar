<h1 align="center">
  <img src="https://github.com/lukebrandonfarrell/react-native-navigation-search-bar/blob/master/example%231.gif?raw=true"/><br/>
  React Native Navigation Search Bar
</h1>

A searcbar for [React Native Navigation](https://github.com/wix/react-native-navigation) which collapses the header when focussed. It's that simple!

## Install

```sh
 npm install react-native-navigation-drawer-extension --save
```

or

```sh
 yarn add react-native-navigation-drawer-extension
```

## Usage

This component wraps the react-native-elements [<SearchBar />](https://react-native-elements.github.io/react-native-elements/docs/searchbar.html) with extra functionality for React Native Navigation.

```js
import { SearchBar } from "react-native-navigation-search-bar";

// register our drawer component with RNN
<SearchBar
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
