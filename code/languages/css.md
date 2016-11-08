# x - code - languages - css

## Basic CSS codings rules

*   **Single Responsibility Principle**
*   **Separation of Concerns**
*   **Immutability**
*   Use the "minimum viable selector"
*   Don’t throw new rules at bugs
*   There’s life beyond px and % (like em, rem, vw, vh...)
*   Use Flexbox
*   Use Grid
*   Use BEM, OOCSS & ITCSS
*   Use SASS (CSS Preprocessor)
*   Strictly no IDs in CSS
*   Avoid unnecessary nesting
*   Keep specificity as low as possible
*   Keep scope limited to thing you’re styling
*   Avoid unnecessary unsetting of styles
*   Lots of comments to explain whats going on to other developers

### Use !important

You should use *!important* for [utility classes](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/#the-namespaces)

### When to use an Utility class

If it’s permanent styling, formalise it and code it right into your CSS. If
it’s short-term or one-off styling, use an utility class.

### Typography

Use this stack for display native font:
```css
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
```

## Resources

*   [StackOverflow CSS Documentation](http://stackoverflow.com/documentation/css)
*   [An ultimate guide to CSS pseudo classes and pseudo elements](https://www.smashingmagazine.com/2016/05/an-ultimate-guide-to-css-pseudo-classes-and-pseudo-elements/)
*   [BEM](https://en.bem.info/)
*   [Sass](http://sass-lang.com/)

### Libraries

*   [Bootstrap](http://getbootstrap.com/)
*   [Foundation for Sites](http://foundation.zurb.com/)

### Parker (Stylesheet analysis tool)

*   [Parker](https://github.com/katiefenn/parker/)
*   [How to read results](http://csswizardry.com/2016/06/improving-your-css-with-parker/)

### Great articles and blogs

*   [OOCSS](http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/)
*   [ITCSS](http://www.creativebloq.com/web-design/manage-large-scale-web-projects-new-css-architecture-itcss-41514731)
*   [CSS Wizardry](http://csswizardry.com/)
*   [The importance of !important](http://csswizardry.com/2016/05/the-importance-of-important/)
*   [More Transparent UI Code With Namespace](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/)
*   [CSS at BBC Sport](https://medium.com/@shaunbent/css-at-bbc-sport-part-1-bab546184e66#.mbtvlw6oq)
