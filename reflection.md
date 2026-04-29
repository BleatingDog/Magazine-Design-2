## What is position: absolute and why is it useful for a layout like this magazine cover? What would happen if you removed it?

`position: absolute` is a CSS property that allows us to place elements exactly where we want them on the page. A magazine cover is artistic and static, 
so using position: absolute lets us freely arrange elements and position them precisely according to our design. If we removed it, the elements would follow the normal document flow, 
making it much harder to achieve the layered and customized layout typical of a magazine cover.

---

## What does the ::before pseudo-element do, and why is it useful to add decorative elements this way instead of adding extra HTML tags?
The `::before pseudo-element` is commonly used to add decorative content to an element, such as icons, quotation marks, or, in this case, a black rectangle that can be stretched 
and positioned behind the text. The advantage of using this pseudo-element is that it allows us to apply consistent styling patterns in CSS, making it easy to reuse decorations 
across multiple elements without adding extra HTML tags.

---
## What challenges did you face when trying to position elements on the cover? How did you use the browser's DevTools to help?
While positioning the cover elements, I noticed that the contributors’ names were overlapping. By using the browser’s developer tools, 
I was able to inspect the styles and temporarily disable the line-height property. This helped me identify that the `line-height` was causing the text to overlap.
