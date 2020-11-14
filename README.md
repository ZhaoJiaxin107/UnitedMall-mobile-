# UnitedMall-mobile-
United Mall deployed mobile device using HTML/HTML5 &amp; CSS/CSS3

***1.Viewport***

Viewport refers to a virtual window where a page is placed in the browser
of a mobile device, which is the part of the page used to diaplay. It is 
equvalent to the visual area of a PC browser.

****The function of the viewport****

In mobile terminal development, visual port is often abstractly divided into layout visual port, visual port and ideal visual port.

***2.Rem layout adaptation scheme***

****What is rem?****

Rem(font size of the root element) is the unit of font size relative to 
the HTML root element, which is calculated based on the font-size of the 
HTML element.

****The implementation principle of REM layout adaptation****
1) Set the viewport of the page

2) Establish the base value, and use REM unit instead of px.(Suppose the design draft font-size of 100px for easy calculation.)

3) Convert 1rem value under different device sizes, that is, change font-size of HTML under different sizes. CSS media query customization and 
JS dynamic calculation control are commonly used in coversion.
