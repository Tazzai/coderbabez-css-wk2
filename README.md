# CoderBabez

##  Week Three - CSS Layouts

### Objectives
Use flexbox to create a complex site layout with rows and columns.

### Vocab
* Box Model
* Divs
* Parent Elements
* Child Elements
* Flexbox

### Review
1. What tags are used on this page?
2. What styles are used on this page?
3. How does the html page know about the styles?

![alt text](https://github.com/megknoll/coderbabez-css-wk2/raw/master/img/practice.png "Review")

### Intro
Last week we started exploring using CSS to add styles to our pages. This week we're going to continue with CSS to work on layout - or moving elements to specific positions on the page using CSS. 

### Lesson - CSS and Layouts:

1. When you look at HTML, imagine every element having a box drawn around it. BOX MODEL

![alt text](https://github.com/megknoll/coderbabez-css-wk2/raw/master/img/boxmodel.png "Box Model")

2. PARENT vs CHILD ELEMENTS

![alt text](https://github.com/megknoll/coderbabez-css-wk2/raw/master/img/child_parent_element.png "Parent vs. Child Element")

3. USING DIVS TO GROUP ELEMENTS

4. USING FLEXBOX. In flexbox, the parent element tells the child elements how to behave.
```html
<div class=”parent”>
	<div class=”child”>
		<img ...>
	</div>
</div>
```

```css
parent {
	display: flex;
	flex-direction: column;
	align-items: center;
}

```


### FlexBox Cheat Sheet

display: sets the flex container
* flex

flex-direction: sets the main axis for the content
* row
* row-reverse
* column
* column-reverse

justify-content: defines how items are aligned along the main axis. 
* flex-start
* flex-end
* space-around
* space-between
* center

align-items: defines how items are aligned along the secondary or cross axis. 
* flex-start
* flex-end
* center
* stretch

flex-wrap: tells us if the content should wrap, or try to fit on one line
* nowrap
* wrap
* wrap-reverse

### Practice Together
1. Open up the index.html file in the practice folder of this repo
2. Use flexbox to make the boxes centered in a column on the page 
3. Use flexbox to make the boxes in a column on the right side of the page
4. Use flexbox to reverse the order of the boxes in a row in the vertical center of the page. All of the items should have even space around them.

### Practice on Your Own: 
1. Open up the index.html file in the main folder of this repo. 

Use flex box to....
1. Make the nav a row of buttons aligned to the left of the page
2. Center the hero image inside of the red div
3. Make the subsection images align in the center of the page in a row, with space around each element*/

When you're done, [it should look like this.](./hero-supply-solution.png)

### Final Thoughts
Today we learned how we can use CSS to add style and layouts to our pages.
Next week we’ll do our first big review project and make our own portfolio pages. 
