# Week 1

## Objectives
- I can explore how HTML and CSS interact to create websites.
- I can use html tag elements to structure a static page.
- I can use basic css to add style.

## Do Now
- Open Slack (Browser or App!)
- In our class channel "f16-w-html" slack your response to this question. What do you hope to accomplish in this class? 

## Housekeeping and Introductions
### Syllabus
- expectations
- long term goals
- contacting me
- contacting each other
- canvas

### Circle up! 2 whip arounds.
1. Name, Class, Major, Hometown, a movie you've seen 5+ times. 
2. Why web design? Why Now?

### Building Background Knowledge
**Round 1**
- Close your computers. Find a partner or group of 3. 
- On one sheet of paper write HTML inside a small circle. Immediately outside the circle list everything that you know about HTML.
- On a second sheet of paper, write CSS inside a small circle. Immediately outside the circle list everything that you know about CSS.

**Round 2**
- Draw a circle around the outside of Round 1
- As a class let's watch http://www.dontfeartheinternet.com/01-not-tubes/
- See some slides, no css, table layouts, front end vs backend
- Add any new information to your charts

**Round 3**
- Visit some some sites
	1. http://www.w3schools.com/html/html_intro.asp
	2. http://www.w3schools.com/css/css_intro.asp
	3. http://blog.froont.com/brief-history-of-web-design-for-designers/
- Do some googling
- Add any new information to your charts

Why HTML? What does HTML do for us?
Why CSS? What does CSS do for us?

### Mini-lesson 1 - Basic HTML
- anatomy of a tag. Opening and closing, attributes.
- html sandwich analogy.
- Focus that all content needs to be inside tags.
- focus on common tags (head, h1, title, body, paragraph, img, lists)

- HTML Tag Sorting Game

- show how to write html head tag, add a title
- show how to make the body.
- show how to do an img
- show how to do a link
```html
<img src="url">
```
```html
<a href="url">link text</a>
```

####Exercise 1 
*Build a "hello world" meme site. Show example*
https://thimbleprojects.org/awdriggs/194496
- Add a heading to the page, this should be your opening meme line. 
- insert your favorite meme image
- Add another heading, this should be your ending meme line.
- Bonus, add a link to another page.

### Mini-Lesson 2
- Anatomy of a CSS Rule
```
   selector {
      property: value;
   }
```
- There can be multiple properties inside a single rule.

-Show how to add style to the meme
-[example](https://thimbleprojects.org/awdriggs/194501)
```
   body {
       font-family: "Open Sans", sans-serif;
   }

#first, #second {
 font-family: impact, sans-serif;
   color: white;
}

#first {
/*absolute position takes something out of the page flow
it is positioned based off the parent element, in this case the page itself.*/
  position:absolute;
    left: 50px;
}

#second {
  position: absolute;
    top: 280px;
      left: 300px;
}
```
####Exercise 2
*Add some style to your meme with css*
-Change the font
-Change the color
-position the text
-Bonus, add some background color

### Mini-Lesson 3
- Using the inspect from chrome 
- right click
- inspect 

