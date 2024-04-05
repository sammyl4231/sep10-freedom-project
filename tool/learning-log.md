# Tool Learning Log

Tool: **CSS Flexbox**

---

3/11/24:
* [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp)

CSS Flexbox is used make easier design flexible-responsive structure without using float or positioning. When you begin using it, you must start with a container with 3 flex items.

I learned from CSS Flexbox that the flex container properties are flex-direction, flex-wrap, flex-flow, justify-content, align-items, and align-content. Flex-direction defines the direction the flex items are stacked in the container. Flex-wrap specifies if the items should wrap or not. Flex-flow is shorthanded for setting both flex-direction and flex-wrap. Justify-content is used to align flex items, putting them in the middle of the container.

To create a flex container:

```HTML
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```

3/12/24:
* [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox_responsive.asp)

One more thing I learned in CSS Flexbox is CSS Flex Responsive. For this one, CSS Media Queries are involved to create different layouts for a certain screen or device type. Horizontal for certain computer types, and vertical for phones and tablets. If you want to create 1 or 2 column layouts, you can change the flex-direction from row to column at a specific breakpoint. You can also change the % of theflex property of the flex items to create different layouts depending on the screen size. You must use flex-wrap: wrap; on the flex container in order for the code to work.

Flexbox can also be used for creating image galleries between 2 or 4 images full-width images wide, depending on the device you use. Flexbox can be used for creating responsive websites, with flexible navigations or content.

Media Queries:

```CSS
.flex-container {
  display: flex;
  flex-direction: row;
}

/* Responsive layout - makes a one column layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-container {
    flex-direction: column;
  }
}
```

3/22/24
* [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox_items.asp)

The CSS Flex Items consist of Child Elements, used to automatically make a flex container flexible. The properties are order, flex-grow, flex-shrink, flex-basics, flex, and align-self. Order specifies the arrangement of flex items in a container. Flex-grow specifies how much a flex item grows compared to the rest. Flex-shrink does the opposite, flex items will look smaller compared to the rest. Flex-basis specifies the initial length of an item. Align-self specifies the alignment for the selected item in the container and overrides the alignment set by align-items.

When you've already created your columns, using CSS Flexbox can also adjust the size of them. The flex container can be flexible by using the display: flex; which is known as a parent element. The child element can automatically become flexible.

3/25/24

[CSS Responsive](https://www.w3schools.com/css/css_rwd_intro.asp)

Another CSS tool is CSS Responsive. This CSS tool makes your weboages look clear and viewable on all devices. It only uses HTML and CSS, and it's not considered a program or Javascript. They must never leave out information to fit smaller devices, but it should adaptits content to fit any device type or size [Desktop](https://www.w3schools.com/css/rwd_desktop.png), [Tablet](https://www.w3schools.com/css/rwd_tablet.png), or [Phone](https://www.w3schools.com/css/rwd_phone.png).

This is called responsive because you use CSS and HTML to resize, hide, shrink, enlarge, or adjust and move content to make it clear regardless of the screen type.

4/5/24

[CSS Grid](https://www.w3schools.com/css/css_grid.asp)

A final CSS tool I learned is CSS Grid. With this tool, you can design webpages without floats or positioning. They consist of columns and rows, are supported in all types of browsers, and consist of parent and child elements. It becomes a grid container when you set the display to grid or inline-grid. Child elements of a grid container become grid items and form columns, rows, and gaps. These 3 parts of a grid can be set using the properties column-gap, row-gap, and gap. There can also be grid lines, you use the properties grid-row-start, grid-row-end, grid-column-start, and grid-column-end.

These can also be used to make grid templates. They're the shorthand property for grid template columns, rows, and areas properties.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
