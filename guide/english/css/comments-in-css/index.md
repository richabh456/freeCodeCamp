---
title: Comments in CSS
---
## Comments in CSS

Comments are used in CSS to explain a block of code or to make any temporary changes during development. The commented code doesn't execute.

The comment syntax in CSS works for both single and multi-line comments. You can add as many comments to your stylesheet as you like.

```css
/*
  This is
  a multi-line
  comment
*/

/* This is a single line comment*/
```

By using CSS comments to make your stylesheets more readable, the CSS will be easier to maintain in the future for you or for another developer. 
It’s good practice to use CSS comments to help identify parts of any stylesheet that might be difficult to understand for someone who didn't write the code. 

You can also make your comments more readable by stylizing them.  

```css
/*
***
* SECTION FOR H2 STYLE
***
* A paragraph where I give information
* about everything that someone who reads the code
* but didn't write it would need to know.
* The asterisks around the paragraph make it more readable.
***
*/
```

You can add as many comments to your stylesheet as you like. It’s good practice to use CSS comments to help identify parts of any stylesheet that might be difficult to understand from a cursory glance. Comments are especially important when working in a team, when your code must be understood by others. Using CSS comments makes your stylesheets more readable, so that the CSS will be easier to maintain in the future.

## Comment Formats

Comments should be used every day in your CSS to keep it maintainable and readable by any dev who dives into said CSS.
Here are a few examples to get you started. These are CSS comments you can use in your daily work to make your life a bit easier.

```css
/* ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
   ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
   CSS TABLE OF CONTENTS

   1.0 - Reset
   2.0 - Fonts
   3.0 - Globals
   4.0 - Color Palette
   5.0 - Header
   6.0 - Body
       6.1 - Sliders
       6.2 - Imagery
   7.0 - Footer
   ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ */


/****************************************************************************
1.0 - Reset */

/****************************************************************************
2.0 - Fonts */

/****************************************************************************
3.0 - Globals */

/****************************************************************************
4.0 - Color Palette */

/****************************************************************************
5.0 - Header */

/****************************************************************************
6.0 - Body */

  /************************************************************************
  6.1 - Sliders */

  /************************************************************************
  6.2 - Imagery */

/****************************************************************************
7.0 - Footer */
```

Tip: Many code editors will comment a highlighted portion of text by typing `CMD + /` (Mac) or `CTRL + /` (Windows).

The best thing you can do in CSS with comments is the next thing: use Regions. Yes, the regions you use too in C#.
Regions are useful in a long CSS file, when you've got plenty of classes and sections to manage and organize. They are basically commented titles of specific sections. The best part about regions? You can collapse/expand them.

Here's how region works:
``` css
/*#region Header */

.header {
  font-size: 12px;
}

/*#endregion */

/*#region Footer
------------------------------------------- */

.footer {
  height: 20px;
}
/*#endregion */
```

### More Information:

* [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/Comments)
* [CSS Comments by Adam Roberts](https://www.sitepoint.com/css-comments/)
* [CSS Guidelines](https://cssguidelin.es/#commenting)
