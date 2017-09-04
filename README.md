# Custom Select

Sass based custom select, a css-only solution.

![Funky](posterity/custom-select.png)

## Install

    npm i --save custom-select-scss

## Include

Depending on your current directory and frontend stack, you'll want something along the lines of one of:

    @import '../node_modules/custom-select-scss/custom-select';
    @import '~custom-select-scss/custom-select'; // (webpack 3)

## Integrate

    <p class="select">
      <label>Select</label>
      <select>
        <option>Lorem</option>
        <option>Ipsum</option>
      </select>
    </p>

## Interpolate

Written in a non-invasive kinda way, so you can add your own styles to `select {}`, similar to your inputs as per usual, and override the handful of default values set in [the sass file](https://github.com/entozoon/custom-select-scss/blob/master/custom-select.scss).

## Inherit

- [Font awesome](https://github.com/FortAwesome/Font-Awesome/) (CDN is fine)
