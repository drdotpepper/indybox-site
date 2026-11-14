Retired design pieces kept for later.

burger-icon.svg - the pixel hamburger menu icon (orange buns, green lettuce, brown patty). Currently live on the site.
arcade-cabinet-icon.svg - pixel mini arcade cabinet menu icon (orange marquee, green screen, red/yellow/blue controls).

To swap one in: paste its <svg> into the #burger button in index.html and give it class='burger-ico' (that class carries the jiggle animation) and a width/height.
The 'Menu' text label was a <span class="burger-label">Menu</span> placed before the svg inside the button.

indybox-logo-px.png: the original pixel logo (white pixel letters, orange i-dot). Replaced in the header by images/indybox-logo-bold.png on 14 Nov 2026. A copy also stays in images/. To go back, point the header <img> at images/indybox-logo-px.png, set .mark img back to image-rendering: pixelated and .mark width to min(212px,70vw) (150px on phones).
