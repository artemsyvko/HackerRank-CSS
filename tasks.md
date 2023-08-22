## 1. CSS Animation

Which of the following would create the below animation? Moving the mouse over the div should double its size, and the animation should happen over 500ms.

```
<style>
    div {
        height: 50px; width: 50px;
        background: #3ba59b;
        border-radius: 50%;
    }
</style>
<div class="greyBall"></div>
```

**Pick ONE OR MORE options**

- .greyBall:hover {transform:scale(2); animate: 500ms; }
- .greyBall:hover {transform:scale(2); transition: 500ms transform; }
- .greyBall:hover {transform:scale(2); transition: 0.5s; }
- .greyBall:focus { transform:scale(2); animate: 0.5s; }


## 2. CSS object-fit

Which of the following are true about the CSS property 'object-fit'?

**Pick ONE OR MORE options**

- 'object-fit: contain;' does not preserve the aspect ratio of the image; it stretches the image to cover the entire width and height of the container.
- 'object-fit: contain;' preserves the aspect ratio of the image and makes sure no clipping happens to the whole image.
- 'object-fit: cover;' avoids the image getting squeezed, but it could end up clipping the image.
- 'object-fit: cover;' avoids clipping the image by sacrificing the aspect ratio.


## 3. CSS Ellipsis

If an element extends beyond the allocated width, how do you truncate the sentence with an ellipsis (...) using CSS?
For example, "Hello! I am an element, and my width is larger than the container..."

**Pick ONE OR MORE options**

- {white-space: pre-wrap; overflow: ellipsis; }
- { text-overflow: ellipsis; white-space: wrap; visibility: hidden; }
- {white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
- None of the above


## 4. CSS Text Coloring

Which of the following renders the text red?

```
<p id="tagld">Please color me red</p>
```

**Pick ONE OR MORE options**

- :root {--text-color: red; } p { color: --text-color; }
- :root { --text-color: red; } p { color: var(--text-color); }
- #tagld { color: red; } p { color: blue; }
- p { color: red !important; } #tagld { color: blue; }


## 5. CSS Selection
How do you prevent the user from selecting the text rendered inside the following element?

```
<p>I should not be selectable</p>
```

**Pick ONE OR MORE options**

- p { cursor-event: none; }
- p { pointer-events: none; }
- p { user-select: none; }
- None of the above


## 6. CSS Input Placeholder

How do you hide the "placeholder" text of an <input> field?

**Pick ONE OR MORE options**

- input::placeholder { visibility: clip; }
- input::placeholder { color: transparent; }
- input::placeholder { display: none; }
- input::placeholder { visibility: hidden; }

## 7. CSS Centering

Which of the following options can position the div with the class name "child" exactly at the center of the page?

```
<div class="parent" style="width: 100vw; height: 100vh;">
    <div class="child" style="height: 100px; width: 100px; background: black"></div>
</div>
```

**Pick ONE OR MORE options**

- .parent { display: flex; justify-content: center; align-items: center; }
- .parent { display: flex; justify-content: center; align-self: center; }
- .parent{position: relative;}.child {position: absolute; top: 50%; left: 50%; }
- .parent{position: relative;}.child {position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); }


## 8. CSS vertical-align

Which of the following are true about the CSS property 'vertical-align'?

```
<p>
    Let's
    <span class="heroWord">Hack</span>
    <img src="""/>
</p>
```

**Pick ONE OR MORE options**
- .heroWord { vertical-align: 25px; } moves the word "Hack" to the bottom, 25px lower than the <p> tag.
- .heroWord { vertical-align: 25px; } moves the word "Hack" to the top, 25px higher than the <p> tag.
- p img { vertical-align: text-bottom; } moves the image to the bottom with respect to the <p> tag.
- p img { vertical-align: text-bottom; } has no effect on the <img> tag.