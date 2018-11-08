# Applied User Experience Guidelines

These are some simple guidelines to create better looking websites and apps.  

## General Layout

* For content areas, do not go over 550px width.  
* Try to create visual lines

## Fonts

```Rule: Pick 1 font for headings and 1 font for content```

### Sans-serif fonts

Use a sans-serif font for content elements as it is easier to consume on digital devices.

* [Roboto](https://fonts.google.com/specimen/Roboto)

* [Lato](https://fonts.google.com/specimen/Lato)

### Serif fonts

Use serf fonts for headings to add some flare to your site.  Avoid using serif fonts for content as they are harder to consume on digital devices.

* [Merriweather](https://fonts.google.com/specimen/Merriweather)

## Text Alignment

Avoid centering content, english speaking people don't consume centered content compared to the top down left to right.  Always think "Wait, should I be centering this?"  The answer is usually “Nope"

* Paragraph level text should never be centered
* Anything longer than 3 or 4 word headline

## White space matters

```Rule: provide at least 10px worth of padding and margin in any element that has content or a border```

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
