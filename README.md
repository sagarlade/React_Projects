# React Portfolio, multiple pages with dark mode

## a portfolio for developers



## features

🌑 Dark Mode Toggler

📖 Multiple Pages (React Router)

📱 Fully Responsive

🎨 Modern Design

💡 Perfect Lighthouse Score

![screenshot of perfect lighthouse score](https://user-images.githubusercontent.com/18350557/179609620-847374a6-23e6-4432-b7a8-181d7d9bf026.png)


---

## getting started

### prerequisites

- have [Git](https://git-scm.com/) installed on your machine
- have [Node.js](https://nodejs.org/en/download/) installed on your machine
- basic familiarity with your machine's command line
- basic understanding of JSON data outline (arrays of objects basically)

## how to use

- fork the repository and clone locally
- cd into the project and run `npm install` to install dependencies
- once installation is complete, run `npm run start` to get your local copy running in the browser.

## template instructions

### 1. replace the images

- open the project in your file explorer, and navigate to `src/img`. there, you will see a bunch of images. these need
  to be replaced with your own images.

#### self.png

- add an image of yourself with the background removed, and cropped into a square. i know this seems picky, but the
  template is set up in a way that this is how it will look best :) I recommend using https://remove.bg to remove the
  background from your image. If this website wants to charge you for some reason, try searching "Remove Background AI"
  on Google, there are some free ones there :)
- Once you add it to this img folder, rename it to `self.png` (delete the old self.png so
  yours replaces it)
- if background removal is not an option for you, any image you use will automatically be made into a circle. for this
  reason, square images without too tall of an aspect-ratio work best.
- example with background removed:



#### mockups

- add to the `img` folder up to 5 screenshots of projects you have completed to be added to your portfolio page. this
  can either be a regular screenshot, or you can create mockups like what are on the default template. I created these
  in Canva -- At the bottom of this readme is instructions to create them yourself! 


- to make life easier later, name these files `mock1.png`, `mock2.png`, etc.

---

### 2. edit `Info.js`

Next, open the project in your code editor. Navigate to `src/info/Info.js`. There are some instructions written in the
comments there, but I will go over it all here as well:

#### Color Scheme

near the top of the file, you will find a line that looks like this:

```
export let colors = ["rgb(0,255,164)", "rgb(166,104,255)"];
```

There are the colors being used to determine the "accents" throughout the site - the circle behind your self portrait,
the color of your name, the labels on the about page, and the underline for the navigation.

You can pick any colors you like for this, just play around with it and make sure to check the colors against both light
mode and dark mode to make sure it looks good on both :)

