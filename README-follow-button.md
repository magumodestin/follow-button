# Follow Button

A small interactive button built with plain HTML, CSS and JavaScript. Click it to toggle between **Follow** and **Following**, with the button turning red while it's in the "Following" state.

## Demo

Live demo: https://YOUR-USERNAME.github.io/follow-button/

## Features

- Toggles the text between "Follow" and "Following" on click
- Changes the background color to red when following
- Hover effect on the button
- Everything in a single `index.html` file, no libraries or setup

## How it works

- **HTML:** a single `<button class="follow">`
- **CSS:** the `.follow` class styles the button, and `.follow.following` adds the red state
- **JavaScript:** a click listener toggles the `following` class and updates the button text

```javascript
followBtn.classList.toggle("following");
```

## Run it locally

1. Download or clone this repo
2. Open `index.html` in any browser

## What I learned

- Selecting elements with `document.querySelector`
- Handling clicks with `addEventListener`
- Toggling CSS classes with `classList.toggle`
- CSS specificity and rule order

## Possible improvements

- Follower counter that goes up and down
- Smooth color transition
- Remember the state after refresh using `localStorage`
