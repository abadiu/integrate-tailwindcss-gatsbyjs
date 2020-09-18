# Integrating `tailwindcss` with a `gatsby.js` starter

## Motivation

I decided to develop [`aperitivo`](https://github.com/loopsideuk/aperitivo), because I need a consistent basis for kickstarting `gatsby.js` site devlopment. One of the features I want to integrate most into `aperitivo` is the excellent utility class based library [`tailwindcss`](https://tailwindcss.com/). 

## References

Here's a list of resources used to write this guide and references for implementing a frontent based on `tailwindcss` with a modified version of the blocks or components contained in [`tailblocks`](https://github.com/mertJF/tailblocks).

- The official Gatsby docs page on integrating `tailwindcss` at https://www.gatsbyjs.com/docs/tailwind-css.
- This Gatsby starter that uses `tailwindcss` at https://github.com/oddstronaut/gatsby-starter-tailwind.
- This collection of ready-made `tailwindcss` blocks at https://github.com/mertJF/tailblocks.
- Using `PostCSS` as your preprocessor with `tailwindcss` https://tailwindcss.com/docs/using-with-preprocessors#using-post-css-as-your-preprocessor.

## Implementation

First of all let's install some stuff for our development dependencies:

```sh 
npm i --save-dev tailwindcss @tailwindcss/custom-forms autoprefixer cssnano postcss
```

Here we're adding tailiwind and 

As well as adding another dependency:

```sh
npm i --save gatsby-plugin-postcss
```

### Setup 

### Configuration

#### Preprocessing with `postcss`
