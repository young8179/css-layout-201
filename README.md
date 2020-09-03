# CSS Layouts 201

## Table of Contents

- [CSS Layouts 201](#css-layouts-201)
  - [1.0 Chessboard](#10-chessboard)
    - [1.1 Bonus - Tile Identifiers](#11-bonus---tile-identifiers)
    - [1.2 Bonus Bonus - Chess pieces](#12-bonus-bonus---chess-pieces)
  - [2.0 Mondrian](#20-mondrian)
  - [3.0 Make a Modal Dialog](#30-make-a-modal-dialog)
    - [3.1 Bonus - Fullscreen Overlay](#31-bonus---fullscreen-overlay)

## 1.0 Chessboard

Inside the file called `chessboard.html`, create a chessboard using HTML and flexbox. The board should work at any width for the outermost container.

![chessboard-02](https://user-images.githubusercontent.com/1687902/79484248-5c3b9800-7fe1-11ea-9fc0-3ac658312d4e.png)

### 1.1 Bonus - Tile Identifiers

See if you can add a border with the row letters and column numbers for the board.

![chessboard-01](https://user-images.githubusercontent.com/1687902/79484247-5ba30180-7fe1-11ea-962e-944d5e16f510.png)

### 1.2 Bonus Bonus - Chess pieces

For an extra challenge, add some chess pieces on their starting positions. How can you do this semantically? There are images you can use in the `images` folder.

## 2.0 Mondrian

Inside the file called `mondrian.html`, create the painting below using HTML and flexbox.

![modrian](https://user-images.githubusercontent.com/1687902/79473031-8e91c900-7fd2-11ea-8c3e-097824183679.jpg)

If you're having trouble creating the whole thing, pick a "chunk" of the painting and work on just that. Then pick another "chunk" and do that, etc. How can you combine your chunks into a single image? (think: HTML tree structure)

## 3.0 Make a Modal Dialog

Using fixed positioning and absolute positioning, you can create a modal dialog that sits in the middle of the page and appears on top of the rest of the page content.

You have a page with some place holder content in it. Also, there's the following markup for a pop-up modal dialog:

```html
<div class="modal-dialog">
  <div class="modal-header">
    <label class="modal-title">Hello</label>
  </div>
  <div class="modal-content">
    <p>Would you like to subscribe to our email newsletter?</p>
  </div>
  <div class="modal-buttons">
    <button>Ok</button>
    <button>Cancel</button>
  </div>
</div>
```

Use the `modal-dialog.html` file to use as a template. Apply CSS rules to make this modal be centered on the page as it appears in the screenshot below.

> **\*N.B**. You will have to add your own css file and use the `<link>` tag load it into your HTML file.\*

![Modal](https://user-images.githubusercontent.com/1687902/79469289-fc87c180-7fcd-11ea-8eda-0d1bd47d7eff.png)

### 3.1 Bonus - Fullscreen Overlay

Semi-gray out the rest of the content on the page, and add a drop shadow to the modal dialog, as is shown in the bonus challenge screenshot. And while we are at it might as well add a little rounded corner to the dialog. You may need to add additional HTML element(s) to the page to achieve this effect.

> **\*Hint:** research the CSS properties opacity and box-shadow.\*

![Modal Bonus](https://user-images.githubusercontent.com/1687902/79469293-fd205800-7fcd-11ea-8a46-ac515a136143.png)
