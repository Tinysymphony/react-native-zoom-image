## react-native-zoom-image

ZoomImage component for React Native Application (ios / android)

> **Only works with https network images** [With the limitation of the current react-native, we can't get original size of required images. This component just zooms them with given size (provided by `imgStyle` prop)]

> If you need to support http network images, modify info.plist please :)

### Examples

<a href="#android" id="android"><img src="./GIF/android.gif" align="left" width="240"/></a>

<a href="#ios" id="ios"><img src="./GIF/ios.gif" width="240"/></a>

### Usage

**install from npm**

``` shell
npm install --save react-native-zoom-image

```

**import in project**

``` js
import ZoomImage from 'react-native-zoom-image';
import {Easing} from 'react-native'; // import Easing if you want to customize easing function
```

```js
let styles = {
  img: {} // custom styles of original image component
};
// in render function
<ZoomImage
  source={{uri: 'https://ooo.0o0.ooo/2017/03/31/58de0e9b287f6.jpg'}}
  imgStyle={{width: 250, height: 230}}
  style={styles.img}
  duration={200}
  enableScaling={false}
  easingFunc={Easing.ease}
/>

```

## Properties



### Instance methods

LICENSE MIT
