A lightweight library that applies a class to an element only when it is focused by tabbing.

**[Try the demo](maxmaeder.github.io/keyboard-focus)**

## Use cases
Perfect for showing users who use keyboard navigation what element they've focused, while not altering the experience for other users.

## Usage
### 1. Add the script to your page
```html
      ...
    <script src="/keyboard-focus.js"></script>
  </body>
</html>
```
### 2. Update your CSS
Create a css rule-set with the `.keyboardFocus` selector and whatever styles you want to be applied when to an element when it is focused by tabbing.
```css
.keyboardFocus {
  outline: 1px solid black;
}
```
3. Sit back, you're done!
