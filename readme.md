<img src="assets/LOGO.svg" />

<br />

# Blaze Slider

Blazing Fast Slider For High Performance Web ⚡

<br />

⚡ Fastest Slider Library

✨ Feature Rich

🔁 Infinite Looping without cloning slides

📱 Expressive CSS Media-Query based Responsive config

🌀 Written in TypeScript

🤏 Extremely small bundle size (1kB Gzipped)

<br/>
<br/>

## Blazing Fast Performance

<br/>

| Rank | Library  | Time   | Compare |
| ---- | -------- | ------ | ------- |
| 1    | Blaze 👑 | 2.2ms  | 1x      |
| 2    | Glide    | 14.5ms | 6.5x    |
| 3    | Flickity | 18.3ms | 8.2x    |
| 4    | Swiper   | 31.4ms | 14.2x   |
| 5    | Slick    | 67.3ms | 30.5x   |

[See More Benchmarks](/benchmark/readme.md)

<br/>

## Installation and Usage

### Using as NPM Package

```bash
npm i blaze-slider
```

Make sure that you import the styles.css as well. Without this CSS, blaze-slider will not work.

```javascript
import BlazeSlider from 'blaze-slider'
import 'blaze-slider/src/styles.css'

new BlazeSlider(sliderEl, options?)
```

### Using the dist JS and CSS files directly

Get the JS and CSS dist files of a specific version of blaze-slider by from unpkg

Example: V0.0.10

JavaScript

```
https://unpkg.com/blaze-slider@0.0.10/dist/blaze-slider.min.js
```

CSS

```
https://unpkg.com/blaze-slider@0.0.10/dist/blaze.css
```

Including the blaze-slider.min.js will create make the constructor function `BlazeSlider` available globally and can be used as follows:

```javascript
new BlazeSlider(sliderEl, options?)
```
