# Div Spacing

This project will test your knowledge of spacing and positioning. And if you use a table, I will come up there and personally strangle you! :)

## CSS Reset

Some browsers act differently from others, so you should always use a CSS Reset at the very top of your first css file. This will make sure all browsers start in the same configuration. This is very simple reset that you can use for this project
```css
/* css reset */
html, body { margin:0; padding:0; height:100%; }
```

## Properties Used

These are the properties that I used to create this example.

- background-color
- height
- margin
- padding
- width

## Steps

### 0 - Background Color

First off, set the background color to something that isn't white. Nobody likes looking at a pure white page. How about #D3D9DF.

### 1 - Single Column

Start by making a single column all the way down the page that is 500 pixels wide. And give it a background color of #989898 so you can see it.

![step 1](Step1.png)

### 2 - Center that Column!

Take the existing column that you have and center it on the page. Keep in mind, that no matter how wide your browser is, that column should be in the middle. So if I make the browser smaller to take up half of my screen, that column should still be in the center of my screen.
![step 2](Step2.png)

### 3 - Add a Couple of Boxes

I want two boxes, each 200 pixels tall, stacked on top of each other in the column that we made. The blue one can have a background color of #004489 and the dark gray one should have a background color of #565656.

![step 3](Step3.png)

### 4 - Space Around Boxes

Put 20 pixels of space around the boxes using the `padding` property.

![step 4](Step4.png)

### 5 - Boxception!

Put a new gray box inside your blue box and a new blue box inside your gray box. Make sure there is 20 pixels of space around the inner boxes so I can see the background of the outer boxes. This is a big step, but what do you expect from the grand finale?

![step 5](Step5.png)