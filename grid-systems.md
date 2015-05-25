# Grid System Guideline


In its most basic terms, a grid system is a structure comprising a series of horizontal and vertical lines which intersect and are then used to arrange content.

Using a grid system in your designs is one way to achieve a level of consistency that would be otherwise extremely difficult to master and to portray in your designs. Again, uniformity and consistency are key to creating a website that your users will find easy to navigate, read and understand.

**Some popular pre-made grid systems:**

- [960][960]
- [Responsive Grid System][responsive]
- [Golden Grid System][golden]


## When to NOT use a grid system:

- UI Uses irregular column sizes
- Has irregular margins or gutters
- Has width indivisible by sane number

## Advantages:

- Structure
- Alignment Horizontal and vertical
- Simplify visualization of proportions
- Stability

## Disadvantages:

- Stifle creativity.
- Too contained.
- For new sites increases velocity, for organized ones it could not be needed.

## Types of grid systems:

We should choose ONE from the beginning (even before any design/mockup)

### Fixed

**Features:** [Fixed layout][fixed-layout]

- “What the designer sees, the user sees”.
- Content won’t change over the max width of the page (e.g. 960px).
- Media queries will designate the MINIMUM width for particular style.
- Will trigger change when changing minimum BREAKPOINT.

**Pros:**

- Easier to use and easier to customize.
- Less hassle with images, forms, video and other content that are fixed-width as every browser has the same width.
- No need for min-width or max-width

**Cons:**

- Excessive White space for larger screen resolutions.
- Could cause horizontal scrollbars on smaller resolutions.
- Textures, patterns and image continuations needs accommodation on larger resolutions.
- Fixed-width layouts generally have a lower overall score when it comes to usability.

**Examples:**

- [Bootstrap][bootstrap-fixed]
- [Fixed Non-responsive][fixed-non-responsive]
- [Fixed responsive][fixed-responsive]

### Fluid

**Features:** [Fluid layout][fluid-layout]

- Will always stretch to fit browser window.
- Media queries indicates the change but containers are always a percentage of the browser window.
- Better to use simple design to easily fix any overlooked scenario.
- Use of min-width and max-width properties.
- This will help to create pseudo-fixed content for handling different users’ resolutions.
- No compatible with IE, as IE 7 - doesn't support max-width property.

**Pros:**

- User friendlier as the content adjust to their setup.
- Less extra space between all browsers and resolutions.
- Can eliminate scrollbars in smaller screen resolutions.

**Cons:**

- Designers has less control over what the user sees and may overlook problems as it looks fine on their setup (designer).
- Images, videos and other content type would need multiple width to accommodate different resolutions.
- With incredibly large screens, lack of content could create excess of white space that diminish aesthetic appeal.

**Examples:**

- [Bootstrap][bootstrap-fluid]
- [Fluid Non-responsive][fluid-non-responsive]
- [Fluid responsive][fluid-responsive]

### Elastic

This is basically a mix of fixed and fluid; this works by sizing all elements by [Em’s][em-vs-rem-vs-px].
These designs adjust to the text size that users set for their browser.

**Pros:**

- If implemented correctly, could be the user friendliest as basically grow larger or smaller in proportion with user's preference.
- Pros of fixed and fluid.

**Cons:**

- Takes a lot of savvy and testing to get the layout right for all users.
- It's harder to implement, and the benefit not always worth it.
- Depending on specifics, it could required supplementary styles for IE6.

**Examples:**

- [Clearleft][clearleft-elastic]


## Grid Systems Tools:

- [Grid System Generator][grid-system-generator]
- [Fluid Grids][fluid-grids]
- [Gridpak][gridpak]
- [Gridset][gridset]

## Common Breakpoints:

Although I consider to be [Content First][content-first] the best approach on designing a website as it will immediately reflect your domain, I know it's not always possible and we require to define common breakpoints where we'll change our design.

Also, we have to take into account that defining a "common" breakpoint list it's always a titanic task as the quantity of devices and its variations are growing up faster and faster, [CSS-Tricks][css-tricks-media-queries] or [CSS Media Queries][css-media-queries] helps us to dig deeper.

**Small Lisf ot common breakpoints:**

- 320px (mobile portrait)
- 480px (mobile landscape)
- 600px (small tablet)
- 768px (tablet portrait)
- 1024px (tablet landscape / netbook)
- 1280px (desktop)

Remember, these breakpoints are not bulletproof, in fact, they could've old.
[fixed-layout]:http://www.smashingmagazine.com/images/fixed-fluid-elastic/fixed.jpg
[fluid-layout]:http://www.smashingmagazine.com/images/fixed-fluid-elastic/fluid.jpg

[bootstrap-fluid]:http://getbootstrap.com/2.3.2/examples/fluid.html
[bootstrap-fixed]:http://getbootstrap.com/2.3.2/examples/hero.html

[fluid-non-responsive]:http://jsfiddle.net/5JECu/
[fluid-responsive]:http://jsfiddle.net/ZnEEa/

[fixed-non-responsive]:http://jsfiddle.net/eterpstra/ZR4zz/3/
[fixed-responsive]:http://jsfiddle.net/eterpstra/rdvaG/12/

[clearleft-elastic]:http://clearleft.com/
[em-vs-rem-vs-px]:https://www.futurehosting.com/blog/web-design-basics-rem-vs-em-vs-px-sizing-elements-in-css/
[content-first]:https://blog.gathercontent.com/designing-content-first-for-a-better-ux

[css-tricks-media-queries]:https://css-tricks.com/snippets/css/media-queries-for-standard-devices/
[css-media-queries]:http://cssmediaqueries.com

[grid-system-generator]:http://www.gridsystemgenerator.com/
[gridset]:http://gridsetapp.com
[gridpak]:http://gridpak.com
[fluid-grids]:https://github.com/csswizardry/fluid-grids


[960]:http://960.gs
[golden]:http://goldengridsystem.com
[responsive]:http://www.responsivegridsystem.com
