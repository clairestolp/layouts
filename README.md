# layouts
A set of SASS generated CSS classes to help customize layouts when using frameworks such as Bootstrap, Bulma, Materialize...ect.

### How to use

#### Basic Use
Using layouts is as simple as copying `layout.css` into your styles folder and importing it into your html page.

#### With SASS

Import layouts to your `.scss` file by copy and pasting `layout.scss` into the location of your scss files in your project. Then import layouts using `@imports ./layout.scss`

### Classes

#### Margins and Padding

Naming: 
  * Padding is named as `.p` and Margins as `.m`
  * Followed by the size
  * (optional) the position

Example: `.p-md-bottom` would be a medium sized padding at the bottom of the element

Sizes:
  * xsm - xsmall - 0.5rem
  * sm - small - 1rem
  * md - medium - 1.5rem
  * lg - large - 2rem
  * xlg - xlarge - 3rem

Positions:
  * right
  * left
  * top
  * bottom

Remove Padding: 
  To remove all of the padding or margins on an element just use the `paddingless` or `.marginless` classes.

### Flex Classes

  * center elements horizontally and vertically
      add `.flex-center` to the parent of the element(s) you want to center

### Images

  * Auto-size images to fit their container's width
      To automatically size an image to it's container just add `.img` to the `<img>` tag.

### Hide Elements

  * Hiding Elements
      Add `.hidden` to any element to set `display: none`. (note: When hidden the element will 'collapse' so it won't take up any space while hidden)

