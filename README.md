# 🔖 Advanced Bookmarklets! 🔖

🎉 Welcome to the ultimate bookmarklets repository! 🎉

Here you'll find a collection of super useful bookmarklets 🔥 that you can use on all your devices to enhance your browsing experience to the max 💪.

### What is a bookmarklet?

A bookmarklet is a small piece of Javascript code 🔰 that is saved as a bookmark in your web browser. When clicked, the bookmarklet runs the code, which can perform a variety of actions 🌟 on the current page. This can include things like modifying the page's content, adding new functionality, or making it easier to interact with the page.

## Table of Contents

- [🔍 Overview](#overview)
- [📜 Changelog](#changelog)
- [🎮 Usage](#usage)
  - [💻 Desktop](#desktop)
  - [🤖 Android](#android)
  - [📱 iPhone](#iphone)
- [🧰 Support](#support)
- [🤝 Contributing](#contributing)
- [🏗 Create your own bookmarklet!](#create-your-own-bookmarklet)

## Overview

Check out the 🔥 bookmarklets we have available in this repository:

| Name            | Description                                                  |
| --------------- | ------------------------------------------------------------ |
| Bookmarklet 1   | This bookmarklet allows you to do X.                        |
| Bookmarklet 2   | This bookmarklet allows you to do Y.                        |
| Bookmarklet 3   | This bookmarklet allows you to do Z.                        |

Each bookmarklet has its own set of features that make it unique and useful.

## Changelog

- Added this 🚀
- Fixed a bug 🐛
- Removed this ❌

## Usage

To use a bookmarklet, follow these steps
A bookmarklet looks like this
```javascript
javascript: (function(){
 // code here ;)
});()
```

### 💻 Desktop
1. Locate the desired bookmarklet
2. Copy the bookmarklet code to your clipboard
3. Click the ★ icon in the top right corner
4. Click 'More'
5. Replace the URL with the bookmarklet code
6. Press save
7. Locate where you saved the bookmarklet
8. Click!!

### 🤖 Android

1. Locate the desired bookmarklet
2. Long press on the link and select "Bookmark this link" from the menu that appears.
3. Give the bookmarklet a name and select the folder where you want to save it. Tap "Add" to create the bookmark.
4. Open your web browser and navigate to the page that you want to use the bookmarklet on.
5. Tap the bookmarklet in your bookmarks.

### 📱 iPhone

1. Locate the desired bookmarklet.
2. Tap and hold on the link until the menu appears.
3. Tap "Add to Home Screen" from the menu.
4. Give the bookmarklet a name and tap "Add" to create the bookmark.
5. Open your web browser and navigate to the page that you want to use the bookmarklet on.
6. Tap the bookmarklet on your home screen.

## 🧰 Support

### ❓ FAQ

**How do you use the bookmarklets?**

See [Usage](#usage)

**Bookmarklet is not working, how do I fix it**

- Make sure you have properly pasted the code and didn't forget some code
- Some websites prevent the execution of JavaScript code, we try to bypass this, but it might not always work
- Make sure your web browser supports this feature, if you're using an old web browser, such as internet explorer, this may not work

## 🤝 Contributing
We welcome contributions to this repository! If you have an idea for a new bookmarklet or want to improve an existing one, please open a pull request. Make sure to follow the repository's contribution guide! See 
TODO: ADD CONTRIBUTING.md

## 🏗 Create your own bookmarklet!

To create your own bookmarklet, you need to be quite knowledgeable in JavaScript and be VERY familiar with DOM Manipulation (crazy right).

A you can learn how to create your own bookmarklet [here](add bookmark url)

I also have a repo that has utility functions to make it easier, stuff like:
```javascript
addElement('div')
parentElem('div', 'coolClassName')

// and more
```

Not only that, I have another repo that contains a HTML to DOM converter, that takes HTML, and converts it to JavaScript, i.e:

```html
<div class="cool">
<span>Hello, world!</span>
<span class="thisIsCrazy">Hello, world!</span>
</div>
```
==> 
```javascript
const div1 = document.createElement('div');
div1.className = 'cool';
document.appendChild(div1)

const span1 = document.createElement('span');
span1.parentElement = div1
document.appendChild(span1)

const span2 = document.createElement('span');
span2.parentElement = div1
span2.className = 'thisIsCrazy';
document.appendChild(span2)
```
