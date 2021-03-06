## Optimize for speed

The PxWeb alternative style has only a 1/10 the size footprint of the regulars CSS. The number of request has been reduced from 25-28 to a meager 4-8.

If bandwidth and speed is a concern you can reduce the number of requests even further making your pages even faster.

1. Minimize font load
2. Inline SVG images
3. Load the optimised CSS

This will take reduce the number of CSS, font and media related request down to **2**!!

### 1. Minimize font load

In the config.scss file found in root, set ´optimize_fonts: true´ instead of default ´false´

### 2. Inline SVG images

In the config.scss file found in root, set ´optimize_images: true´ instead of default ´false´

### 3. Load optimised CSS

The CSS directory will output a minimized version of the CSS files ```css/style.min.css```. 