
## Honeyfund responsive web design

Due to a config error in webpack, this file's .scss file was unable to be compiled. CSS changes are instead appended to the top of the document in a \<style\> tag.

While a great exercise, a static PNG image can't tell the developer how the design, *changes* under varying conditions (especially the layout). In this particular case, the developer is given no information as to how the document should flow with increasing width; e.g: whether the size of content should grow, or the size of spacing. 

Responsiveness accomplished with media queries at widths of 620px (large tablet-like object) and 1120px (small laptop-type screen)

 To gain truly fluid control over a layout, it seems best to use a combination flexbox, grid, and truly responsive spacing with clamp(), min(), max(), and calc() specifications.

Certain "magic number" media query widths had to be overwritten for a more uniform flow between screen sizes


Representative mobile model: Samsung Galaxy S8+ (360 x 740)
Representative tablet model: iPad Air (820 x 1180)

I'd love to talk more about frontend design and development - especially CSS - if you have the time

Thanks!

