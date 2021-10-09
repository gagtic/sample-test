## Getting started

Create a [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) of this [repository](https://github.com/nabeel-raresense/sample-test), and [clone](https://docs.github.com/en/get-started/quickstart/fork-a-repo#cloning-your-forked-repository) your private forked repository.


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for all interactive elements on the page
- See a live countdown timer that ticks down every second (start the count at 14 days)
- **Bonus**: When a number changes, make the card flip from the middle

### Built with (Recommended)

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles
- **Bonus** [Storybook](https://storybook.js.org/) - For Component Driven Development

### Development Timeline (NEWLY ADDED)

I started working on 10/8/2021 (mm/dd/yyyy) on 04:00PM. As I haven't worked on Next .js before, I watched the fireship.io video (link in reference) to familiarize myself with the workflow. From my very limited understanding, I believe the reason for Next .js is to pre-render and pre-compute stuff on server side, so that the loading of web element is faster. 

As I have done most of my development in react native expo. I checked expo documentation on how to make an expo-next app (link in the reference). I also watched a video on youtube for making the counter but rest assured, I haven't copied everything off it, as that code was in react next .js

The problem came when I tried to add font to the app. For some reason, I have scraped the whole web (even second page of google search result) to investigate how to implement font, but for some reason, I wasn't able to implement font for expo app. My initial thoughts were that it was some fault with expo library. Hence, I created the same app again in react-native (I could expo eject, but it ejects way more build-in libraries than actually needed), and much to my surpise. The font is still not updated. Now the code is present in both project, but for some reason, react just don't access those files and apply the font when I use fontFamily.

### Continued development

Continue investigating how to implement fonts, for sure. Because as embarassing as it is, I already had done that using expo hooks but wasn't able to do so for some reason, this time.

Also exploring more about next .js in react js, from the video I've seen, routing & even selection of data is very easy when it comes to next .js. Might take care of much of the boilerplate code form node .js 


### Useful resources

- [FireShip.io video link](https://www.youtube.com/watch?v=Sklc_fQBmcs) - This helped me for introduction to next.js framework. I am really impressed by how easy it can make optimization and routing of my website.
- [Using Next.js with Expo for Web](https://docs.expo.dev/guides/using-nextjs/) - This article shows how to create a nextjs app with expo
- [Counter App video link](https://www.youtube.com/watch?v=VNTom2Gtn8s) - I got basic idea about the coutner application from this video, I only checked the coutner logic from the video
- [How to import SVG inside react native](https://ozorku.hashnode.dev/how-to-use-svg-images-in-react-native-expo-app-ckahw4soq01dumks1zffuv4ey) - This is a good article on how to import an svg inside react native project and use it


## Acknowledgments

I would like to thank fireship.io for giving me a speedy introduction to nextjs. Whenever I try to learn new language, I first see fireship.io video on Youtube, so that I have some idea about what I'm about to learn.
