# Entry 5
##### 4/8/24

## What I learned about my tool

The tool I learned about these past weeks is [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp). This tool taught me so many different methods of creating and managing containers and grids. I learned from CSS Flexbox that the flex container properties are flex-direction, flex-wrap, flex-flow, justify-content, align-items, and align-content. Flex-direction defines the direction the flex items are stacked in the container. Flex-wrap specifies if the items should wrap or not. Flex-flow is shorthanded for setting both flex-direction and flex-wrap. Justify-content is used to align flex items, putting them in the middle of the container.

To create a flex container:

```HTML
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```

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

## How I learned my tool

I learned my tool by using the provided properties depending on the purpose of the CSS, and testing them out.

[CSS Flex Items](https://www.w3schools.com/css/css3_flexbox_items.asp)

The CSS Flex Items consist of Child Elements, used to automatically make a flex container flexible. The properties are order, flex-grow, flex-shrink, flex-basics, flex, and align-self. Order specifies the arrangement of flex items in a container. Flex-grow specifies how much a flex item grows compared to the rest. Flex-shrink does the opposite, flex items will look smaller compared to the rest. Flex-basis specifies the initial length of an item. Align-self specifies the alignment for the selected item in the container and overrides the alignment set by align-items. When you've already created your columns, using CSS Flexbox can also adjust the size of them. The flex container can be flexible by using the display: flex; which is known as a parent element. The child element can automatically become flexible.

Child Elements:
```CSS
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
  <div>4</div>
</div>
```

[CSS Responsive](https://www.w3schools.com/css/css3_flexbox_responsive.asp)

Another CSS tool is CSS Responsive. This CSS tool makes your weboages look clear and viewable on all devices. It only uses HTML and CSS, and it's not considered a program or Javascript. They must never leave out information to fit smaller devices, but it should adaptits content to fit any device type or size [Desktop](https://www.w3schools.com/css/rwd_desktop.png), [Tablet](https://www.w3schools.com/css/rwd_tablet.png), or [Phone](https://www.w3schools.com/css/rwd_phone.png).

This is called responsive because you use CSS and HTML to resize, hide, shrink, enlarge, or adjust and move content to make it clear regardless of the screen type.

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

[CSS Grid](https://www.w3schools.com/css/css_grid.asp)

A final CSS tool I learned is CSS Grid. With this tool, you can design webpages without floats or positioning. They consist of columns and rows, are supported in all types of browsers, and consist of parent and child elements. It becomes a grid container when you set the display to grid or inline-grid. Child elements of a grid container become grid items and form columns, rows, and gaps. These 3 parts of a grid can be set using the properties column-gap, row-gap, and gap. There can also be grid lines, you use the properties grid-row-start, grid-row-end, grid-column-start, and grid-column-end.

These can also be used to make grid templates. They're the shorthand property for grid template columns, rows, and areas properties.

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

```CSS
.flex-container {
  display: flex;
  flex-wrap: wrap;
}

.flex-item-left {
  flex: 50%;
}

.flex-item-right {
  flex: 50%;
}

/* Responsive layout - makes a one column layout instead of a two-column layout */
@media (max-width: 800px) {
  .flex-item-right, .flex-item-left {
    flex: 100%;
  }
}
```

## Skills and Professionalism

Some skills I used during learning log are attention to detail, creativity, debugging, etc.

### Attention to detail

As always, I want to make sure everything is spelled correctly and if I made any grammar mistakes. I always make sure my text is readable and makes sense in terms of how I word my responses.

### Creativity

When I started my Learning Log, I first pictured it to have a title in bold, depending on what day I work on it and what I learn that day, and have at least 1 paragraph about what learned.

### Debugging

When I was tinkering with my learning log tool, I tested out the "Try it Yourself" options of the CSS Flexbox features to try to fix any issues or try the properties myself to see how they really work.
