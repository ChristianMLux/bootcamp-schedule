# bootcamp-schedule
this respository is to keep track of my journey in the bootcamp 


## Today I've learned: 

* [08.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#08062021 "08.06.2021")
* [09.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#09062021 "09.06.2021")
* [10.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#10062021 "10.06.2021")
* [11.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#11062021 "11.06.2021")
* [14.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#14062021 "14.06.2021")
* [15.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#15062021 "15.06.2021")
* [16.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#16062021 "16.06.2021")
* [17.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#17062021 "17.06.2021")
* [18.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#18062021 "18.06.2021")
* [21.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#21062021 "21.06.2021")



## 08062021
### -> what visual studio code is
  visual studio is an IDE (integrated development environment)
### -> what a powershell is and how to use it 
  input interface 
### -> how to set variables in windows and use them in cmd
  (enter "environment variables" in windows search > "new" > Name the variable > enter the varable value > safe > to use them in cmd %VARIABLENAME%
### -> how to create new files and folders via cmd
  "%code% filename.txt filename.txt dir\filename.txt" will create 2 files in the current folder and also creates a new folder with an filename.txt in it.
### -> getting more in touch with github
  learned how to work with Issues 
  how to add/edit Readme Files
  how to edit the profil 
### -> what markdown is
  Markdown’s syntax is intended for one purpose: to be used as a format for writing for the web.



## 09062021
### -> HTML
brief overview about HTML, tags , format , text , structure (html, head, body, main, footer etc)
heading=use headings for accessibility. don't skip headings
### -> Git Bash
How to use it, for what is it good for. cmd replacement
### -> visual studio code 
emmet shortcut, 

## 10062021
### -> shortcuts/lifehack
alt + arrows = moving lines in code

divx5>{itemsx$} (creates 5 divs with item

## 11062021
### -> CSS 
selector {property: value;}

(Margin(Border(Padding(Content)Padding)Border)Margin)

## 14062021
### WeeklyRecap
#### ->CSS
Ruleset selector{style declaration:value}
tag selector -> name
class selector -> .name
universal selector -> *
id selector -> #name
attribute selector -> [name]

#### -> BoxModel
(Margin (Border (Padding (Content) Padding) Border) Margin)

## 15062021
### -> CSS
Ruleset selector{style declaration:value}
tag selector -> name
class selector -> .name
universal selector -> *
id selector -> #name
attribute selector -> [name]

(Margin(Border(Padding(Content)Padding)Border)Margin)

shorthands 
border.. 
border .. 
border 

= border : 5px solid red

pseudo classes / selectoren 


(git pull/push workthrough)
1. git repository erstellen 
(sowohl in git als auch auf dem desktop) 
2. touch files in desktop folder
3. git init the dekstop repo 
4. (if needed) git branch -m master main (change branche from master to main) 
5. git add . = make the files ready for commit
6. git remote add origin "origin URL"  = connect desk and hub
7. commit changes
8 git push -u origin main 

(if this leads to an error and youre sure you're uploading the 
right thing just git push --force origin main

## 16062021

### Cascade 
> on a simplyfied level the cascade defines which styles should be applied to an element in the following order 

1. Importance 
2. Specificity
3. Source ordner

* Universal selector → *.
* Tag selector → p or div
* Class selector → .nav or .main-content
* Attribute selector → [title] or [href]
* Pseudo-classes → :hover or :focus 
* ID selector → #contact or #skills
* Inline styles → <main style=”color: red”>...</main>

Each selector has a specificity score
* Tag → 1
* Class, pseudo-class and -element, attribute → 10
* ID → 100
)

### Flow Layout / Document FLow / Display types 

https://developer.mozilla.org/en-US/docs/Web/CSS/display
[MDN DOCS](https://developer.mozilla.org/en-US/docs/Web/CSS/display "display property")

#### Position 
>The position property allows taking elements out of the normal document flow to create complex components and layouts.

>!!**position: absolute can be slightly tricky because it depends on the containing block 
and if offset properties are set.**!!


Position | Positioned | Positioned to?
--- | --- | ---
static | No | - 
relative | Yes | Normal flow + offsets
absolute | Yes | Containing block + offsets
fixed | Yes | Viewport + offsets
sticky | Yes | Scrolling ancestor + offsets

### Length Units

* em stands for equalm m
* rem stands for root euqlm m

> Root: 16px -> 1 rem = 16px

*ch = represents the width of the glyph “0” of the current element
*ex = represents the height of the letter “x” of the current element

> **!! Absolute units can cause accessibility issues because they don’t scale when the user agent’s font-size changes!! **


## 17062021

### Media Queries 

> What is a Media Query?
> Media query is a CSS technique introduced in CSS3.

__It uses the @media rule to include a block of CSS properties only if a certain condition is true.__

```
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
```
* @media → queries for a specific device criteria
* @supports → queries for specific CSS feature
* @keyframes → defines a keyframe animation
* @font-face → defines an external font (to be downloaded)

Examples for specific features are:
1. Width and height of the viewport
2. Media type
3. Resolution
4. Display mode
5. Orientation
6. Light level


> MEDIATYPES: all, screen, printer, speech .. etc. 

__Printing dark themed websites only makes printer companies happy__
```
.theme {
  background-color: black;
  color: white;
}

@media print {
  .theme {
    background-color: white;
    color: black;
  }
}

```

## 18062021

### Weekly Recap 
### Lightning talk with atef 

## 21062021







