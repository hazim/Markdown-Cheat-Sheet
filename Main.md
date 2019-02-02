# Markdown Basics Cheat Sheet 

## Headlines, Paragraphs and Basic Formatting 

### Headlines Level 3
#### Headline Level 4
##### Headline Level 5 
###### Headline Level 6 

### Paragraphs and Line Breaks 

We create paragraphs by typing the way we would in and other program. Just hit return twice to start another pragarph.

Where you see empty space between blocks of text in your Markdown document, you will see empty space sepearting those blocks of text in your formatted HTML document. 

I love you without knowing how, or when, or  
from where  
I love you directly without problems or pride:  
I love you like this because I don't know any  
other way to love

Neruda, Pablo. "Sonnet 17" The Poetry of Pablo Nerida, edited by Ilan Stavans, translated by Mark Eisner, Farrar, Straus and Giroux, 2005, p. 514.

### Emphasis and Bolding

#### Italics 

This *works*, and this _works_ too.

#### Bolding 

This **works**, and this __works__ too. 

#### Italics + Bolding 

This ***works*** and this ____works____ too. 

### Blockquotes

> Markdown is intended to be as easy-to-read and easy-to-write as is feasible. 
> 
> Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions. - [John Gruber](http://daringfireball.com "Creator of Markdown")

### Horizontal Ruke

---
___

***

## Lists

### Numbered Lists 

1. Item 1
1. Item 2
1. Item 3


1. Item 1
    1. Item 1
    1. Item 2

### Bulleted Lists

* Item 
* Item 
* Item 
    * Item 
    * ***Item*** 

---

## Code

to install the latest of NPM you can type, `npm install npm@latest -g`

```js
let exampleFunction = () => {
  Let foo = 'foo';
  Let bar = 'bar';

  return foo + bar;
}
```

---

## Links 

[Treehouse](http://www.teamtreehouse.com)

[Treehouse](http;//www.teamtreehouse.com "Link to Treehouse")

[Treehouse][1]

[1]: http://www.teamtreehouse.com "Reference Lonk to Treehouse"

---

## Images

![Budapest](https://images.unsplash.com/photo-1524615688360-e7614ea326b5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1352&q=80 "Budapest Castle")

[![Castle](https://images.unsplash.com/photo-1484284948449-77aa72231187?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80)](http://www.hazimsami.com)




## Further Useful Markdown Reading 

[CommonMark](https://commonmark.org/)  
[Blog in Markdown](https://mediatemple.net/blog/tips/you-should-probably-blog-in-markdown/)  
[Daring Fireball](https://daringfireball.net/projects/markdown/)  
[Choosing the Right Markdown Parser](https://css-tricks.com/choosing-right-markdown-parser/)  
[GitHub Mastering Markdown](https://guides.github.com/features/mastering-markdown/)  

## Markdown Tools
[StackEdit](https://stackedit.io/)  
[Dillinger](https://dillinger.io/)  
[Babelmark 2](https://johnmacfarlane.net/babelmark2/)  

---
---

# Wes Bos Markdown sessions 


![Colourful Flower][flower]
# About Hazim 

## About the 
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Hello _hello_ __heloo__

Lorem ipsuim dolor. **Hagsanb** odsjl *ksm* uisewmn.

I **love your**. 

I _really_ love you. 

_one_ 
__two__ 
three
~~four~~ 
five
give

![Random][random]



## This is an h2  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Code Blocks w/ language defined

Here is my code:

```js
var x = 100;
const dog = 'snikers';
```

```php
$age = 50;
$name = "hazim";
echo strtoupper($name);
```

## Code Block without language defined
```
    var userCount = Math.random;
```

## Inline Code Block
Het did you try `var x = 100;`?

## Code Block explaining the diference between before and after
```diff
var x = 100;
- var y = 200;
+ var y = 300;
```

<http://www.hazimsami.com>

[Github.com](http://github.com/hazim "back")

[Hackeryou.com][1]

Make sure you check out Hazim's Site. 

If you want to learn React, you can [learn][1] at React for beginners.com - Hazim did a great job on this. 

Hazim also teaches at HackerYou where you can come and learn with him in person. Check out their site for more info. 


## How to tell a story

1. Lorem ipsum dolor sit amet,
1. consectetur adipiscing elit, 
1. sed do eiusmod tempor 
1. incididunt ut labore et 
1. dolore magna aliqua. 
1. Ut enim ad minim 
1. veniam, 
1. nostrud 

## Things you will need for the trip
- shoes
- underpants 
- flash light
- compos
- hat
- extra socks

|Dog's Name| Dog's Age|
|:---------|:---------|
|Snickers|2|
|Prudence|8| 

## Making a Todo List using Markdown
* [ ] Pens
* [ ] Ruller
* [x] Photocopying paper
* [ ] Eraser 
* [ ] 



## Line Breaks 
Hazim is cool. <br>
He really is. 

## Horizontal Rules

---

## Black quotes 

>You miss 100% of the shots you don't take. 
> **Wayne Gretzky** 


## Webiste links:
[1]:http://www.hazimsami.com "Testing title"
[flower]:https://images.unsplash.com/photo-1464820453369-31d2c0b651af?ixlib=rb-1.2.1&auto=format&fit=crop&w=2000&q=80
[random]:https://picsum.photos/800/500/?image=321

