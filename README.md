# Move Boxes With Angular

An app to generate new boxes in your app. And move those boxes using your keyboard keys.

### Installation and Running Code

1. Install Angular CLI by running `npm i -g @angular/cli`
2. Open terminal into project folder
3. Install required dependencies by running `npm i`
4. Run `ng serve` to run app on in your browser
5. Open `localhost:4200` in browser to see app

### Working

-   User gets to see a button to add a new box in the window. On clicking the button, a box
    is created with a unique number ID. Boxes are of fixed width and height.
-   Higher id boxes will have a higher z-index.
-   Users can add multiple boxes.
-   To select a box, click on it. Highlight the selected box.
-   Use W-A-S-D or arrow keys on the keyboard to move the selected box.
-   Use the "delete" key on the keyboard to remove the selected box.
