# What is CSS Structure and Lesson Plan Template

## Description

In this lesson you will learn what is CSS (Cascading Style Sheets) and how it interacts with with the HTML elements of your website and Javascript. Learn how to use CSS to style those HTML elements and the 'cascading effect'.

## Objectives

After completing this lesson, participants will be able to:

* Define what is CSS and the role it plays on a website (the fundamental the role of HTML, CSS and Javascript)
* Define the anatomy of a CSS block and illustrate how it can be applied to HTML
* Illustrate how to use basic CSS to modify the HTML elements of your site (text, backgrounds)
* Define what is a CSS class and id and show how it can be applied to the HTML elements of your site
* Explain the 'cascading' effect and how you can arrange your CSS to reflect this

## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Put an "x" in the brackets for all that apply.

* [ ] Users / Content Writers
* [X] Designers
* [X] Developers
* [ ] Speakers
* [ ] Organizers
* [ ] Kids

## Experience Level

How much experience would a participant need to get the most from this lesson? Put an "x" in the brackets for all that apply.

* [X] Beginner
* [ ] Intermediate
* [ ] Advanced

## Type of Instruction

Which strategies will be used for this lesson plan? Put an "x" in the brackets for all that apply.

* [X] Demonstration
* [ ] Discussion
* [X] Exercises
* [ ] Feedback
* [ ] Lecture (Presentation)
* [ ] Slides
* [ ] Show & Tell
* [X] Tutorial

## Time Estimate (Duration)

How long will it take to present this lesson? Put an "x" in the brackets for the one that applies.

* [X] 1 hour or less
* [ ] 2-4 hours (half-day)
* [ ] 5-8 hours (full-day)
* [ ] 2 days
* [ ] 3 days or more

## Prerequisite Skills

Participants will get the most from this lesson if they have familiarity with:

* Basic computer literacy
* Basic understanding of HTML
* Basic knowledge of how to use a Text Editor

## Readiness Questions

* Do you have a basic knowledge of HTML?
* Have you got access to and do you know how to use a Text Editor?

## Slides

> Change the `/repo-name/` in the link to match the URL name of this repo.

*   [Slides](https://wptrainingteam.github.io/lesson-plans/reo-name/slides/) (files included in this repo)

## Materials Needed

* Web Browser
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator.html.en)
* [W3 HTML Color Picker](https://www.w3schools.com/colors/colors_picker.asp)
* [W3 HTML Color Names](https://www.w3schools.com/colors/colors_names.asp)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator.html.en)

## Notes for the Presenter

* The lesson plan is meant to to be an introductory to CSS through demonstrations, exercises and tutorials. It is not a detailed course on CSS but an introduction to the topic for users who have a basic understanding of HTML and want to use CSS to style basic HTML elements.
* Users must be able to answer ‘Yes’ to the first readiness question. If they answer ‘No’ to the second question then they can be directed to use the W3C CSS validator.

## Lesson Outline

* First go through the description, objectives, the target audience this is aimed at the skills required and how the lesson will be delivered.
* Then start with 'Hands-on Walkthrough' and try to understand it.
* After Finishing that go with Exercises, and then get them to try to complete the Assessment.
* Finish with additional resources/reading material.

## Exercises

**Exercise 1 - Modifying Fonts **

For this exercise, we will be making changes to the h1 elements on index.html and we have prewritten some CSS code under styles.css

index.html
<h1>Everything Cupcake</h1>
<h2>First Cupcake</h2>
<p>Gummies muffin donut. Sweet marshmallow halvah dessert I love lemon drops lollipop brownie bonbon. I love pudding cake icing liquorice.
</p>
<h2>Second Cupcake</h2>
<p>Donut bear claw cake pie I love halvah. Cake cotton candy donut sweet cheesecake I love wafer liquorice tiramisu. Pie oat cake halvah cake candy. Chocolate tiramisu tiramisu tiramisu jelly-o bear claw sugar plum oat cake soufflé.</p>
<h2>Third Cupcake</h2>
<p>Dragée I love chocolate bear claw marzipan cheesecake danish. Oat cake candy oat cake pudding gummies. Halvah gingerbread I love cotton candy apple pie sweet roll cheesecake. Tiramisu jelly beans danish soufflé pie sweet marzipan candy.</p>

style.css
h1 {
font-family: arial;
color: black;
text-align: right;
font-weight: italic;
}
h2{
font-family: arial;
color: black;
text-align: center;
font-size: 24px;
}
p {
color: red;
font-size: 22px;
font-family: georgia;
text-align: justify;
}

Make the following changes
1. Change the h1 font to Georgia
2. Align the h1 text to align to the center
3. Change font to be bold
4. Add a font size property to h1 and set it 36px
5. Change the color of the h2 font to dark grey
6. Change the h2 text to align to the left
7. Change the paragraph font size to 18 pixels
8. Change the paragraph font color to black

**Exercise 2 - Backgrounds, Colors and Padding **

For this exercise, we will be adding color to the background of some HTML elements and assigning some padding to these elements. See index.html and we have prewritten some CSS code under styles.css

index.html
set the background of each #color-div
<header></header>
<nav></nav>
<section></section>
<article></article>
<aside></aside>
<footer></footer>

Set the background of header to x
Assign x to footer
Assign x to aside

ID vs. Class You may notice in the above example, some selectors have a "#" in front of them, and some have a "." in front of them. This is used to denote if there is an ID or a class associated with this HTML element. Each ID is used only once. Groups can be used for more than one HTML element.

**Exercise 3 - Adding a Background Image **

Short description of what the exercise does and what skills or knowledge it reinforces.

*   Change the colour of of the 'H2' elements using an 'id'


> These are short or specific activities that help participants practice certain components of the lesson. They should not be fully scripted exercises, but rather something that participants could do on their own. For example, you can create an exercise based on one step of the Example Lesson.

## Assessment

There should be one assement item (or more) for each objective listed above. Each assessment item should support an objective; there should be none that don't.

**CSS:**

1.  Specifices how documents are presented to a user
2.  Changes the colour and size of a HTML element
3.  Defines the position of a HTML element on a page
4.  All of the above

**Answer:** 4\. Correct answer

**The anatomy of CSS consists of:**

1.  Selector, color, value
2.  Value, selector, property
3.  Selector, property, value
4.  Color, value, selector

**Answer:** 3\. Correct answer

**You can use the font-size property to:**

1.  Control the size of a font
2.  Set the font to small, medium or large
3.  Control the weight of a font
4.  Set a font to italics

**Answer:** 3\. Correct answer

**You can use the background property to:**

1.  Set the set the background color of an element
2.  Control the position of text in a background
3.  Control the repitition of an font in the background
4.  All of the above

**Answer:** 1\. Correct answer

**Which option is True:**

1.  A CSS class applies changes to a specific element and an ID applies changes to a group of elements
2.  A CSS class applies changes to a group of elements and an ID applies changes to a specific element

**Answer:** 1\. Correct answer

**The cascading effect is:**

1.  Option
2.  Option
3.  Option
4.  Option

**Answer:** 3\. Correct answer


> A few questions to ask participants to evaluate their retention of the material presented. They should be a measure of whether the objectives were reached. Consider having a question for each objective.

## Additional Resources

* Mozilla Developer Network - https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics
* WordPress - https://codex.wordpress.org/CSS
* CSS Tricks - https://css-tricks.com
* Codrops CSS Reference - https://tympanus.net/codrops/css_reference/


> An optional section which can contain a list of resources that the presenter can use to get more information on the topic.
>
> _For example:_
>
> * Link to information on the Codex
> * Theme Review Team's Handbook

## Hands-on Walkthrough

> An example of how the lesson plan can be implemented. Written in script form as one possible way an presenter might use this lesson plan at an event, with screenshots and instructions if necessary.


### What is CSS? What does it do?

Welcome to What is CSS! Today you are going to learn about CSS and how you can use it to alter the “look and feel” of a HTML element by modifying its existing Cascading Style Sheet (CSS) file , as well as write a few new styles of your own. We are going to watch a short video that explains what is CSS and how it fits in with HTML and Javascript. Play the video https://www.youtube.com/watch?v=gT0Lh1eYk78&t=9s In practical terms, the code found in a site's CSS file determines the appearance of your site by applying style rules to HTML content, which has no style of its own. Another way to visualize this is to think of your site as an HTML "mannequin" and CSS as the "clothing" you put on it. Just like a mannequin's clothing, you can change the CSS of your site any time you like, without altering its underlying HTML structure.

### Learning the Lingo: Selectors, Properties, and Values

Like any foreign language, CSS can be made easier to understand by breaking down each "sentence" into its individual components. Because our plan is to find and modify the existing CSS of HTML elements, this will help you to better understand what is going on.
* Selector - The HTML element that you want to change.
* Property - What you are changing about it.
* Value - What you are changing it to.

### CSS Properties
Here are some CSS properites that you can use

1. For Text
font-family assigns the font of the text. For example, Arial, Georgia, Helvetica, Times
font-size assigns the size of the text. For example pixels (16px) or ems (2ems)
font-color assigns the color of the text. For example web safe colors like red, blue and green; or Hexidecimal codes like #000, #fff
text-align aligns the text to a position on the page. For example, left, right, center
font-weight sets the font to bold, bolder or light

2. For Backgrounds

Like any foreign language, CSS can be made easier to understand by breaking down each "sentence" into its individual components. Because our plan is to find and modify the existing CSS of HTML elements, this will help you to better understand what is going on.
* Selector - The HTML element that you want to change.
* Property - What you are changing about it.
* Value - What you are changing it to.

### How to target a specific element in CSS?

There are different ways to target a specific element in CSS depending upon the element itself. Below are the most common ways to target an element.

1.Using its element name.
Targeting element with its name is the most common way. we will use its name to target it and give it new properties and values. Let's see how it works.
If you want to target a 'p' tag and assign its font-size property to 16px you will do that as below:
p {
font-size: 16px;
}
Note: Here all 'p' tags in your document will be targeted.

2.Using its class.
A single class can be used multiple times and for different elements in a single document. If the element to be targeted has class, you can target it using that class. For targeting a class in CSS you will use a dot '.' before its class name. Let's see how it works.
Assume you have a 'p' tag with class 'text-small' which will look something like this <p class="text-small">Hello World!</p> and you want its 'font-size' to be '12px'. You will write it as below:
p.text-small {
    font-size: 12px;
}
Note: Here only 'p' tags with class 'text-small' will be targeted. If you want all the elements, no matter which they are, to be targeted you will simply remove 'p' and will just use .text-small. This will target all the element with class 'text-small'.

3.Using its ID.
Unlike class, id should be always unique in your HTML document. To target an element with id you will have to just replace that dot '.' which you used for class with hash '#'. For example, if you have a 'p' tag with id 'name' which will look something like this: <p id="name">John Doe</p> and you want it to be bold you will target it as follow:
#name {
    font-weight: bold;
}
Note: While targeting id you can also mention tag name before id name. It will look like this 'p#name'.

### The Cascading Effect

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with the [Exercises](#Exercises) and [Assessment](#Assessment) outlined above.


### Lesson Wrap Up

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Now that we've gone through what a CSS block looks like and how you can target specific elements in CSS, we are going to practice modifying CSS to see how it changes a HTML element. Follow with the [Exercises](#Exercises) and [Assessment](#Assessment) outlined above.
