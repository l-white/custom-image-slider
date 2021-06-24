# Custom Image Slider

**This image slider was modified from a code sample from W3 Schools**

View the code for [W3Schools](https://www.w3schools.com/howto/howto_js_slideshow.asp)

Modifications:
1. Refactored JavaScript to ES6 syntax
2. Modified CSS to incorporate styles and branding guidelines for Milwaukee Public Schools
3. Modified CSS for stylistic adjustments, such as adding more contrast, larger caption fonts, and larger borders for accessibility considerations.

**If you are working in a content management system and the slider no longer works, adjust functions so that they are function expressions.**

**Example**

Change:
&nbsp;&nbsp;&nbsp;&nbsp;let plusSlides = n => showSlides(slideIndex += n);\
To:&nbsp;&nbsp;&nbsp;&nbsp;
    function plusSlides(n) {
        showSlides(slideIndex += n);
    }
