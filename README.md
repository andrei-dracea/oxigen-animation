# oxigen-animation

Animation for the Oxigen Website.

<br />

## Setup

1. **Install anime.js dependency**:

Include it from CDN:

```
<script src="https://cdn.jsdelivr.net/npm/animejs@3.2.1/lib/anime.min.js"></script>
```

or

Install it from npm:

```
npm install animejs
```

or simply [download](https://github.com/juliangarnier/anime/) it.

<br />

2. **Install animation package**:

Include it from Github

```
<script src="https://cdn.jsdelivr.net/npm/animejs@3.2.1/lib/anime.min.js"></script>
```

or

Install it from Github:

```
npm install git+https://github.com/andreipfeiffer/oxigen-animation.git
```

or simply [download](https://raw.githubusercontent.com/andreipfeiffer/oxigen-animation/main/docs/index.js) it.

## Usage

```js
// if you have installed it form npm, you have to import it:
import * as oxygen_animation from "oxygen-animation";

// otherwise, you can use the global object "oxygen_animation":
oxygen_animation;
```

### .init()

Should be called when you want to initialize the package:

```js
oxygen_animation.init({
  // the container for the animation
  element: document.querySelector("#animation-scene"),
  total_necesar: 250000000,
});
```

### .update()

```js
oxygen_animation.update({
  total_strans: 1100000,
  donatori: 146,
});
```

### .animate()

```js
oxygen_animation.animate({
  nume: "Andrei P.",
  suma: 200,
});
```
