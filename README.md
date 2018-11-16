# Applied User Experience Guidelines

These are some simple guidelines to create better looking websites and apps. [Click here for a video walk through of these concepts](https://youtu.be/Ir58R46Owy4).

## General Design Ideas

Don't reinvent the wheel when it comes to building your design.  Find examples to use as guides and then add your own content and design.

* [Awwwards.com](https://www.awwwards.com/websites/) is an awesome place to find inspiration for design.

* [Dribbble](https://dribbble.com/tags/webdesign) is another great place to find design inspiration

* [Html5up](https://html5up.net/) provides amazing free templates under a creative commons license that only requires attribution.

## Content Layout Guides

Content is anything your user will consume beyond navigation or headings.  Forms, paragraphs, instructions all fall into the content category.  

* For large content areas, do not go over 550px width.  Users of your site/app will lose interest quickly.

* Always provide at least 15px of margin between content elements

* If you have a border around your content, provide at least 10px padding between the border and the content area

* Provide `line-height` of at least `1.25` to help your text breathe

* Avoid center-aligning any text more than 3 to 4 words long

* Never center-align large portions of text — stick to left-justified alignment.

* Avoid using drop shadows to frame content or text, if you do use one, make it extremely small

## Fonts

General Rule: Pick 1 font for headings and 1 font for content.  Keep it simple so the user can focus on your content.

### Sans-serif fonts

Use a sans-serif font for content elements as it is easier to read on digital devices.

* [Roboto](https://fonts.google.com/specimen/Roboto)

* [Lato](https://fonts.google.com/specimen/Lato)

### Serif fonts

Use serif fonts for headings to add some flare to your site.  Avoid using serif fonts for longer blocks of content as they are not as easy to read on digital devices.

* [Merriweather](https://fonts.google.com/specimen/Merriweather)

## Responsive Units

Responsive units are a lot of fun to use, but some should be avoided unless you have extensive experience using them.  

* Don't use `vw` and `vh` units unless you need some element to go full screen.  Example: using vh and vw for a full screen modal pop up would be good, but that's about it.

* For width values, use a `%` or hard coded pixel in a `flexbox`

## CSS Height

For CSS height values, let the content's box model control your height instead of hard coding anything.  Hard coded heights can create nested vertical scroll bars instantly hurting your user experience.

* Let the browser do the scrolling, don't use `overflow: hidden` to make up for CSS mistakes

## Mobile

Plan for mobile on day one.  Set up your media queries to desktop or mobile first as a priority and not a last thought.  **You don't need mobile design to think about mobile code structure!**

* When working with mobile layouts: stack everything vertically

* Provide at least 15px margin from the edge of your content to the edge of the device.

## Color

Color trends come and go. Currently we are in a flat and simple color trend across the internet.  Choose 2-3 colors and stick to them.

* Pick a color scheme with good contrast, use [http://colorsafe.co](http://colorsafe.co/)

* Don't use gradients

* Do use solid / flat background colors
