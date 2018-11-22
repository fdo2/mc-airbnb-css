# airbnb CSS challenge

## Learning Outcomes
- Practice implementing a design with CSS
- Practice writing CSS using pre-defined variables (a style guide)
- Exposure to [BEM](https://css-tricks.com/bem-101/), a CSS class-naming convention 

## Task

Your task is to implement the following **mobile design** using CSS:

![mobile design](https://user-images.githubusercontent.com/25960351/48894868-76089800-ee4c-11e8-8125-70f977b0902b.png)

- We have provided CSS Variables to be used in the style rules
- We have provided empty CSS rules for all the classes in the html. Not every CSS rule needs to be filled.
- Have fun!

Stretch Goal:
- Draw your own desktop design and implement it using media queries!


## CSS Variables

We have defined some CSS variables to be used in style rules. Check them out at the top of the `main.css` file.

Variable definition:
```css
html {
  --spacing-x-large: 4rem;
}
```

How to use them:
```css
.my-class {
  margin: var(--spacing-x-large);
}
```

## Colours
Here you can see the colours which we have defined for you:

![colours](https://user-images.githubusercontent.com/16781318/48892918-cfba9380-ee47-11e8-8c9b-2481912c05fe.png)

If you haven't already, add the extension to your editor to allow you to see the colours.
