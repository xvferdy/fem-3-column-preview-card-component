# 3-column preview card component

> 🔖 This is a solution for the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

## 🌈 ✨ 🎉 Have Fun Building! 🚀 🎊 🎈
> 🖥️ **Welcome** <br>
> Thanks for checking out this front-end coding challenge.
[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.
***To do this challenge, you need a basic understanding of HTML and CSS.*** Press <kbd>Enter</kbd> 🚀 to start the game!!

## 📍Table of Contents
- [Brief](#brief)
- [The challenge](#the-challenge)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned-)
- [Difficult Things](#difficult-things-)
- [Author](#author)

## Brief
This challenge is perfect if you're just getting started. The shift between the layouts will be a nice test if you're new to building responsive projects.

Your challenge is to build out this **3-column preview card component** and get it looking as close to the design as possible. You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go 👍.

**Preview** :eyeglasses:

![Design preview for the 3-column preview card component coding challenge](./design/desktop-preview.jpg)

## The challenge 
Users should be able to:
  
| Challenge | Newbie | Junior | Intermediate | Advanced |
| --- | :---: | :---: | :---: | :---: |
| View the optimal layout depending on their device's screen size | ⭕ |  |  |  |
| See hover states for interactive elements | ⭕ |  |  |  |

[![🐬 Newbie Difficulty List](https://img.shields.io/badge/Difficulty-Newbie-3F54A3?style=for-the-badge&logo=frontendmentor "Newbie Difficulty")](https://www.frontendmentor.io/challenges?difficulties=1)

## Links
- Solution URL: [Frontend Mentor Solution]()
- Live Site URL: [Github Pages]()

## My process
> ⌛ I challenge my self to finish this for ***~3 days*** <br>
> ▐ <br>
> 🧑‍💻 ***Day 1.*** Folder structure & basic [Sass](https://sass-lang.com/) boilerplate <kbd>~2 hours</kbd> <br>
> ▐ <br>
> 🧑‍💻 ***Day 2.*** [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) skeleton <kbd>~2.5 hours</kbd> <br>
> ▐ <sub>Plus starting making a very basic layout using `grid` </sub> <br>
> ▐ <br>
> 😭 ***Day 3.*** [Javascript](https://www.javascript.com/) day<br>
> ▐ <sub>Working with JSON file <kbd>~4 hours</kbd></sub> <br>
> ▐ <br>
> 🌐 ***Day 3.*** Submit to [**Frontend Mentor**](https://www.frontendmentor.io/solutions/femtimetrackingdashboard-ujF6vcWFM "Solution") 🚩 <br>
> ▐ <sub>Add some [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) for coloring <kbd>~3 hours</kbd></sub> <br>
> ▐ <br>
> 🗓️ ***Day 4-5.*** Continuing incomplete design <br>
> ▐ <sub>Try to fix buggy style <kbd>~6.5 hours</kbd></sub> <br>
> ▐ <sub>Responsive design <kbd>~3 hours</kbd></sub> <br>
> ▐ <sub>Tried to figuring out how to add animation <kbd>~1 day</kbd></sub> <br>
> ▐ <br>
> 🗓️ 

## Built with
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML "developer.mozilla")
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html "W3C")
- ❤️

## What I learned 🥳
This is my very first trying _mobile first approach_ for designing a website, TBH I'm not really comfortable and this lead me to writing unnecessary **CSS** code. But I will fix my self and study more.

###### src/stylesheets/helpers/\_breakpoints.scss
```scss
@mixin display($breakpoint) {
  @if ($breakpoint == sm-phone) {
  @media only screen and(max-width: 320px) {
    @content;
    }
  }

  @if ($breakpoint == desktop) {
  @media only screen and(min-width: 900px) {
    @content;
  }
 }
}
```

## Difficult Things 😵‍💫
Things were difficult for me and I finally gave up 🤙
- [ ] Try to use `grid`
- [ ] Clean **CSS** code

## Author
| [<img src="https://avatars.githubusercontent.com/u/47988956?v=4" alt="xvferdy" width="100px"/><br><sub><samp>Berlianto</samp></sub>](https://github.com/xvferdy)  |
|:---:|

<h3 align="right">
      <a href="#time-tracking-dashboard">To Top ✪</a>
</h3>
