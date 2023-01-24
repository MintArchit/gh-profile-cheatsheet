# Cheatsheet for Github profiles README.md

***Disclaimer: Notice this is Work in Progress and might contain errors!***

**What you can Integrate:**
- Markdown
- Badges
- Collapsible Content
- Html(limited)
- Images
- SVG
- Gifs
- Define Terminal Cmds
- Preview sytax highlighted Code
- Latex
 
# Rescources

- [Official GH Wiki about Writing&Format](https://docs.github.com/en/get-started/writing-on-github)
- [MarkDown Docs](https://www.markdownguide.org/)
- [Awesome Github Profiles](https://zzetao.github.io/awesome-github-profile/) \([projects github repo](https://github.com/abhisheknaiidu/awesome-github-profile-readme)\)

# Contents

# Collapse

## How to
````md
<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Code
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>
````

## Example
<details>
    <summary>Click me</summary>

  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux
     
  ### Some Code
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>

## Rules
1. Have an **empty line** after the `</summary>` tag or markdown/code blocks will not render.
1. Have an **empty line** after each `</details>` tag if you have multiple collapsible sections.

[Author](https://gist.github.com/pierrejoubert73/902cc94d79424356a8d20be2b382e1ab)

# Links

Via MarkDown

\[Description\]\(URL/Link\)

e.g.

\[Youtube\]\(https://youtube.com\) rendered: [Youtube](https://youtube.com)

Via HTML
<a href="https://youtube.com">Youtube</a>

# Html

tags that work
```html
<a>
<img>
<h1>
<img>
```


tags that don't work
```html
	
```

attributes that don't work
```html
target="_blank"
```

# Badges
 
Badges are via html integrated adjustable Image Links(URLs) to an Online Third-Party Image Generator

URL Syntax/Structure:

https: //img.shields.io/badge/ leftText - rightText - rightBG 
?style       = btnDesign
&
logo        = logoName
&
logoColor   = HexColor
&
labelColor  = HexColor

e.g.

https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white&color=white

https://img.shields.io/static/v1?message=html&logo=css3&labelColor=5c5c5c&color=1182c3&logoColor=white&label=%20&style=plastic

https://img.shields.io/badge/Medium-black?style=for-the-badge&logo=medium&logoColor=red

<img src="https://img.shields.io/badge/Bootstrap-informational?style=flat-square&logo=bootstrap&color=003B57" />

**! Dont stretch badges by setting width & height (doesnt look right) !**

# Colors

- [Discussion StackExchange](https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file#answer-73613791)
- [Latex Colors](https://en.wikibooks.org/wiki/LaTeX/Colors)
