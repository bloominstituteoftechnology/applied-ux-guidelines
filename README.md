# Applied User Experience Guidelines

These are some simple guidelines to create better looking websites and apps.  

## General Design Ideas

Don't reinvent the wheel when it comes to building your design.  Find examples to use as guides and then add your own content and design.

* [Awwwards.com](https://www.awwwards.com/websites/) is an awesome place to find inspiration for design.

* [Dribbble](https://dribbble.com/tags/webdesign) is another great place to find design inspiration

* [Html5up](https://html5up.net/) provides amazing free templates under a creative commons license that only requires attribution.

## Content Layout

Content is anything your user will consume beyond navigation or headings.  Forms, paragraphs, instructions all fall into the content category.  

* For large content areas, do not go over 550px width.  Users of your site/app will lose interest quickly.

* Always provide at least 15px of margin between content elements

* If you have a border around your content, provide at least 10px padding between the border and the content area

* Provide `line-height` of at least `1.25` to help your text breathe

* Avoid centering anything longer than 3 to 4 words long

* Never center large portions of content

## Fonts

```Rule: Pick 1 font for headings and 1 font for content```

### Sans-serif fonts

Use a sans-serif font for content elements as it is easier to consume on digital devices.

* [Roboto](https://fonts.google.com/specimen/Roboto)

* [Lato](https://fonts.google.com/specimen/Lato)

### Serif fonts

Use serf fonts for headings to add some flare to your site.  Avoid using serif fonts for content as they are harder to consume on digital devices.

* [Merriweather](https://fonts.google.com/specimen/Merriweather)


## White space matters

* 

## Responsive Units

* Don't use `vw` and `vh` units unless you need some element to go full screen.  Example: using vh and vw for a full screen modal pop up would be good, but that's about it.

* For width values, use a `%` or hard coded pixel in a `flexbox`

## CSS Height

* For height values let the content's box model fill the height instead of hard coding a height in.  Hard coded heights cause so many UI problems.

* Let the browser do the scrolling

## Mobile

* Plan for mobile on day 1.  Set up your media queries to desktop or mobile first as a priority and not a last thought.

* When working with mobile layouts, stack everything vertically and provide at least 15px margin from the edge of your content to the edge of the device.

## Color

* Pick a color scheme with good contrast - http://colorsafe.co/
* Don't use gradients
* Do use solid / flat background colors
