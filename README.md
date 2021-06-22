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
* [22.06.2021](https://github.com/ChristianMLux/bootcamp-schedule/blob/main/README.md#22062021 "22.06.2021")

___

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

___

## 09062021
### -> HTML
brief overview about HTML, tags , format , text , structure (html, head, body, main, footer etc)
heading=use headings for accessibility. don't skip headings
### -> Git Bash
How to use it, for what is it good for. cmd replacement
### -> visual studio code 
emmet shortcut, 

___

## 10062021
### -> shortcuts/lifehack
alt + arrows = moving lines in code

divx5>{itemsx$} (creates 5 divs with item

___

## 11062021
### -> CSS 
selector {property: value;}

(Margin(Border(Padding(Content)Padding)Border)Margin)

___

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

___

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

___

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

___

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
___

## 18062021

### Weekly Recap 
### Lightning talk with atef 

___

## 21062021

### GitHub 

> **Git** is the de facto industry standard when it comes to version control and web development
> Git helps developers to track changes and to collaborate changes to software

* Highlevel overview of Git workflow
* How to init a repository
* How to add and commit changes
* How to view the history of a repository 
* How to connect remote repositories 
* How to use VSCode with Git

> git is a timemashine for file changes.

Git is a tool that tracks file changes in a directory. 
+ when was the files changed
+ what was changed
+ was the file deleted

Git trakcs everything that can happen to a files or directory

**Repository**: A repository is a folder on your computer that is managed by Git
* the folder can hold files and subfolders
* often called "Repo"

**Stage/Index**: File changes in a repository are not automatically saved by Git. File changes need to be proposed as permanent changes.

> this is done by adding changes to the stage or index (add .)

**Commit**: A commit is a change to file(s) in a repo. A commit holds information like (When, Who, Why, What)

**HEAD**: is the latest version of a repo. the head is the sum of all commits in a repo. 

**Branch**: Branches are used to develop features or to isolate work. A Repo usually has a default or main branch where other branches are merge once they are ready. 

__Workflow__: 
1. File(s) in a repository change
2. The changes are added to the index / stage
3. The staged changes are committed to the repository
4. The history and HEAD of the repository changes

**git config**
```
git config --help
rm -rf .git (delete initialized git repo) 
```

**Commit Hash** 
> The commit hash is unique historical identifier of the repository 

* reset the current 

___

## 22062021

### Flexbox

> Flexbox is a efficient and modern way of layouting with a chance of overuse

* Flexbox allows you to distribute items among available space
* primarily designed for one-dimensional layouts
* potential chance of overuse

__A flexbox has a main and a cross axis__

row -> 

reversed row <- 

Column |

_the justify-content property defines the distribution of space and flex items accross the main-axis_

__order__ base value= 0 (don't use it) 
__flex-grow__ controls the distribution of remaining space.
__flex-shrink__ The flex-shrink property defines a shrink factor for each flex item.
__flex-basis__ The flex-basis property sets the initial main size of a flex item.
__flex shorthand__ 
```
flex: 5; 
/* flex-grow: 5; flex-shrink: 1; flex-basis: auto; */

flex: 100px; 
/* flex-grow: 0; flex-shrink: 1; flex-basis: 100px; */

flex: 2 0; 
/* flex-grow: 2; flex-shrink: 0; flex-basis: auto; */

flex: 5 100px; 
/* flex-grow: 5; flex-shrink: 1; flex-basis: 100px; */

```

__align-self__ The align-self property allows flex items to be positioned individually on the cross-axis
```
.flexbox {
  display: flex;
  align-items: flex-end;
}

.flex-child {
  align-self: flex-start;
}
```
### CSS Custom Properties

> Custom properties can be changed during runtime / They can be used to create customizable web components

```
html {
  --primary-color: black;
}

p { 
  color: var(--primary-color);
}
```

__Fallback Value__
> What happens if a custom property is undefined?
The var() function takes a second argument which represents a fallback value
var(--custom-property, <fallback-value>)

__Dark&Light Theme__
```
@media (prefers-color-scheme: dark) {
  html {
    --font-color: white;
    --background-color: black;
  }
}
```
> If a none defined custom property is used (without a fallback value) the property is set to initial or inherit
* The property will use initial if the property is not inherited
* The property will use the inherited value if the property is inherited





