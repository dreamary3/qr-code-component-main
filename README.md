# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#Overview)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Author](#author)


## Overview
In my recent learning journey, I delved into the world of CSS units and their role in creating responsive web designs. This exploration led me to discover the significance of units like "rem," "px," and "vh" in shaping layouts and optimizing user experiences across various devices.


### Links
box-shadow : https://box-shadow.dev/

### Built with
- HTML5
- CSS custom properties

### What I learned
I learned The 100vh property in CSS is used to set an element's height to 100% of the viewport's height, ensuring it takes up the entire visible area of the screen. This is useful for: creating 1.full-height sections, 2.Vertical Centering: When combined with other CSS properties, such as Flexbox or Grid, 100vh can be used to vertically center elements within their parent containers.3.responsive designs. 4. Single-screen scrolling experiences. 5. Avoiding Overflow. By using 'height: calc(100vh - 1px)', we account for the fact that smartphones might not consistently interpret the 'vh' (viewport height) unit accurately.  subtracting a tiny amount of pixels (1px) from the 100vh value causes the height to be evaluated in pixels, thereby providing robust height support across various mobile screens.

I learned about the concepts of "rem" and "px" and when to apply them. Rem values are relative to the root HTML element. For instance, if the root element's font-size is set to 16px, then 1rem will correspond to 16px for all elements. If the font-size isn't explicitly defined in the root element, 1rem will assume the default font-size provided by the browser."Px" (pixel) represents an absolute unit that remains fixed in size, unaffected by screen dimensions or user preferences. This quality makes it suitable for small, unchanging elements such as borders or shadows. When aiming for scalable typography and responsive layouts that need to adapt relative to the root element, "rem" units are the recommended choice. By using "rem," you can create typography and layouts that gracefully adjust based on the user's preferred font size or changes in the root element's font-size. This approach helps achieve a consistent and adaptable design across various devices and screen sizes.


## Author

- Website - [Meryem Ketishvili](https://www.twitter.com/dreamary37)
- Frontend Mentor - [@ydreamary3](https://www.frontendmentor.io/profile/dreamary3)
- Twitter - [@dreamary37](https://www.twitter.com/dreamary37)