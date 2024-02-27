# MovieHuB- Movie Recommender

## SASS Features Used:

### Variables

SASS variables allow you to store and reuse values throughout your stylesheets. Variables are used for $bubble_height, $bubble_width, $bubbleColor, $primary_2, etc. These variables help in maintaining and reusing values throughout the stylesheet.

### Custom Properties

Custom properties, also known as CSS variables, provide a way to store values for reuse. It is used in 'style.scss' and '_hero.scss'($bubbleColor).

### Nesting

Nesting in SASS allows you to structure your styles hierarchically, making your code more readable. For example, '&_header' and '&_button' are nested within the .navbar block, which makes the code more readable.

### Interpolation

Interpolation enables you to embed expressions within selectors or property names. '#{$color}' is an example of interpolation. It allows you to insert the value of a variable into a string.

### Placeholder Selectors

Placeholder selectors (denoted by %) are used for reusable styles. It is used in 'style.scss' and '_login.scss'.

### Mixins

Mixins allow you to group styles and reuse them across your stylesheets. Mixins are used with '@mixin bubble' and '@mixin position'. They allow you to define reusable sets of styles that can be included in different selectors. 

### Functions

SASS functions enable you to perform calculations or create dynamic styles. It is used in '_container.scss'.

### Nested Selector

Nested selectors in SASS help maintain a cleaner structure for related styles.The 'a' selector is nested within the .navbar_header block.

### Extend/Inheritance

Extend allows you to share styles between selectors, reducing redundancy. '@extend %align-between;' is used to inherit styles from a placeholder selector named '%align-between'. This allows for aligning the navbar content between two points.

### Media Query

Media queries in SASS help create responsive designs. The '@media' directive is used to apply styles based on the screen width. It adjusts the width property of '.login-container' when the screen width is less than or equal to 768 pixels.

### Hover State

SASS supports pseudo-classes like :hover to style elements on interaction.&':hover' is used to define styles when the mouse hovers over the .navbar_header.