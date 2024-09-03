# PicToCode

## Change Log

* 18/02: Added "if applicable" comment to pseudo classes; updated text for task 3 - there is some confusion between the terms "Pro" and "Business" in the enterprise screenshots. You can use those two words interchangably, it won't matter which is used.

## 1. Tasks

### Task 1 - Static, fixed size page

Build a page that looks identical to [task1/page.png](task1/page.png). The window width you should work with is 1555 x 808 pixels. You are only allowed to use HTML and CSS for this task. No external libraries are permitted.

Please build a page in [task1/index.html](task1/index.html). Welcome to create as many CSS files that are needed in the `task1` folder for `index.html` to import.

#### Task 1 - Assets

* The assets are provided in `task1/assets/text.txt` give the text to put on the page.
* For the arrows, use a reasonable emoji (or image of own choice found online) to display that element.
* The font doesn't have to match exactly. Use font-family `Arial` or `Helvetica` for the page.

### 1.2. Task 2 - Static, fixed size page

Build a responsive page that complies with [task2/page_big.png](task2/page_big.png) and [task2/page_small.png](task2/page_small.png). The big page is 1040 x 577 pixels, and the small page is 501 x 592 pixels. The single page (note that must not using two separate HTML files) should like identical to either of these pages depending on the window sized the browser is at.

Assume that all the input fields are `<input />` tags. All non-text inputs do not need any drop down behaviour or dynamic styling when being clicked etc. For text inputs they can be assumed to be static text inputs that have a text of colour `#000000` when text is inputted. None of the text inputs need to deal with text longer than 10 characters.

Please build a page in `task2/index.html`. Welcome to create as many CSS files that are needed in the `task2` folder for `index.html` to import.

#### Task 2 - Assets

* The assets are provided in `task2/assets` and provide you with the background and calendar.
* For the two car images can just use emojis (remember: emojis are text characters too).
* For the right arrow and the magnifying glass, Use a reasonable emoji (or image of your choice found online) to display that element.

### 1.3. Task 3 - Responsive static page

Build a responsive page that complies with [task3/page_big.png](task3/page_big.png) and [task3/page_small.png](task3/page_small.png). The big page is 1595 x 895 pixels, and the small page is 673 x 3034 pixels. Your single page (note that you're not using two separate HTML files) should like identical to either of these pages depending on the window sized the browser is at.

It is expected to have reasonable intermediate states. In other words, if the window size is some combination of widths between 673 and 1595, combined with some combination of heights between 895 and 3034, the page should still reflect the same general structure.

Please build a page in `task3/index.html`. Welcome to create as many CSS files that are needed in the `task3` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

#### Task 3 - Assets

* The asset(s) are provided in `task3/assets`.
* The font doesn't have to match exactly. Use font-family `Arial` for the page.

## 2. Analysing the pages

### 2.1. Analysing the Pages

Two things will want to seek external help for are:

1) Determining the particular colour (RGB or HEX) of various pixels (Recommend the use of [a chrome extension](https://chrome.google.com/webstore/detail/eye-dropper/hmdcmlfkchdmnmnmheododdhjedfccka/), though other alternatives may be appropriate for you)
2) Determining the size of particular elements (Recommend the use of [photopea](https://www.photopea.com/)). An screenshot example of it's usage can be found [here](./help/photopea.png)

### 2.2. Font Sizes

it might be curious to know what the correct font-size and other font properties are for this assessment. Part of this assessment is trying to explore the relationship between how a font looks and the properties that are set for the element.

Generally the best approach is to set a basic font size (e.g. `font-size: 1.1em`), see how it looks, and if it just generally seems too big or too small, then adjust the `em` or `rem` value appropriately until the developer is comfortable with it.

## 3. Constraints & Assumptions

### 3.1. Correct viewing settings

Don't forget to put this code in the head of each webpage you make: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`. It will help on mobile responsive view get the right zoom.

### 3.2. Fair use of methods

It is prohibited from unreasonable use of images and svg to solve your problem - more specifically, do not upload large chunks of the 'page' as just a single SVG image or single JPG.

### 3.3. Browser Compatibility

Ensure that the programs are tested on Google Chrome, ensuring that they are run in the latest version.

### 3.4. External libraries

It is restricted from using any third party CSS libraries during the implementation. Basically, this means try not to import code using the `<script />` and `<link />` tags if it's from a file written  by someone else.
