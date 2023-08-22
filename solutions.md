## Solutions

- Task 1: (2)
    ```
    .greyBall:hover {
        transform: scale(2);
        transition: 500ms transform;
    }
    ```

- Task 2: (2, 4)
    - 'object-fit: contain;' preserves the aspect ratio of the image and makes sure no clipping happens to the whole image.
    - 'object-fit: cover;' avoids clipping the image by sacrificing the aspect ratio.

- Task 3: (3)
    ```
    {white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
    ```

- Task 4: (2)
    ```
    :root { --text-color: red; } p { color: var(--text-color); }
    ```

- Task 5: (3)
    ```
    p { user-select: none; }
    ```
- Task 6: (2, 3, 4)
    ```
    input::placeholder { color: transparent; }
    /* OR */
    input::placeholder { display: none; }
    /* OR */
    input::placeholder { visibility: hidden; }
    ```

- Task 7: (1, 4)
    ```
    .parent { display: flex; justify-content: center; align-items: center; }
    ```
    ```
    .parent{position: relative;}.child {position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); }
    ```

- Task 8: (1, 3)
    - .heroWord { vertical-align: 25px; } moves the word "Hack" to the bottom, 25px lower than the <p> tag.
    - p img { vertical-align: text-bottom; } moves the image to the bottom with respect to the <p> tag.
