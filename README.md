**WORK IN PROGRESS**

<h1>Welcome to zenyx.css!</h1>
<p>This README will teach you the basics of zenyx.css, how to use it, what it's for, and why you should use it</p>

<h1>What is it?</h1>
<p>zenyx.css is a CSS framework which uses classes to style the element</p>
<p>zenyx.css is currently in development, and shouldn't be used standalone, while possible, it's not reccomended</p>

<h1>How do I use it?</h1>
<p>Using the framework is extremely easy. Simply head over <a href="https://zenyxis.com/zenyx">here</a> and follow the steps as instructed in the "How do I use this?" section<p>

<h1>Standard documentation</h1>
<table>
  <tr>
    <th>Classname</th>
    <th>Changeable</th>
    <th>Function</th>
    <th>Type</th>
    <th>Example</th>
    <th>Desc.</th>
    <th>Tags Supported</th>
  </tr>
  <tr>
    <td>zx-margin</td>
    <td>zx-margin(l,r,t,b)-(1 through 10)</td>
    <td>Sets the margin in the respective direction</td>
    <td>Margin</td>
    <td>zx-marginl-4</td>
    <td>For those who don't know, L=Left, R=Right, T=Top, B=Bottom. Measurements are made in EM</td>
    <td>Anything</td>
  </tr>
  <tr>
    <td>zx-padding-</td>
    <td>zx-margin(l,r,t,b)-(1 through 10)</td>
    <td>Sets the padding in the respective direction</td>
    <td>Margin</td>
    <td>zx-paddingr-6</td>
    <td>For those who don't know, L=Left, R=Right, T=Top, B=Bottom. Measurements are made in EM</td>
    <td>Anything</td>
  </tr>
  <tr>
    <td>zx-negmargin</td>
    <td>zx-negmargin(l,r,t,b)-(1 through 10)</td>
    <td>Opposite of zx-margin</td>
    <td>Margin</td>
    <td>zx-negmarginl-4</td>
    <td>For those who don't know, L=Left, R=Right, T=Top, B=Bottom. Measurements are made in EM</td>
    <td>Anything</td>
  </tr>
  <tr>
    <td>zx-text-(property)</td>
    <td>zx-text-(color, alignment, style, responsive)</td>
    <td>Changes the text style</td>
    <td>Text</td>
    <td>zx-text-blue</td>
    <td>Can be any basic color, and can be any alighnment. use zx-text-responsive to align center on mobile screens. You may also use zx-text-simple to change the font to RALEWAY</td>
    <td>Any text tag</td>
  </tr>
  <tr>
    <td>zx-header</td>
    <td>NONE</td>
    <td>Increases the text size</td>
    <td>Text</td>
    <td>zx-header</td>
    <td>Literally just increases the text size. That's it.</td>
    <td>Any text tag</td>
  </tr>
  <tr>
    <td>zx-size-color</td>
    <td>zx-(50,75,100)-color</td>
    <td>Makes a div have the certain height, have padding (unless -nopad is added), and sets the appropriate color for the respective bg-color.</td>
    <td>Sections</td>
    <td>zx-100-black-nopad</td>
    <td>Creates a section with the chosen height (in Viewport Height) and in the chosen color (white, gray, black). Automatically sets padding. -nopad may be added to remove padding</td>
    <td>DIV tags</td>
  </tr>
<tr>
  <td>zx-respdel</td>
  <td>NONE</td>
  <td>Deletes the element on mobile devices</td>
  <td>Responsiveness</td>
  <td>zx-respdel</td>
  <td>Again, deletes the element on mobile devices</td>
  <td>Anything</td>
</tr>
<tr>
  <td>zx-hover-color</td>
  <td>zx-hover-(any standard color)</td>
  <td>Sets the color upon mouse hover</td>
  <td>Text</td>
  <td>zx-hover-black</td>
  <td>Can be used to set hovers for ANCHOR tags</td>
  <td>Any text tag</td>
</tr>
<tr>
  <td>zx-transition-property</td>
  <td>zx-transition-(color, border-color, all, header)
  <td>Adds a transition</td>
  <td>Misc.</td>
  <td>zx-transition-all</td>
  <td>Header is a font-size transition, all sets a transition for everything</td>
  <td>Anything</td>
</tr>
<tr>
  <td>zx-button-color</td>
  <td>zx-button-(only black at the moment, will add more)</td>
  <td>Creates a rounded, pill shaped button</td> 
  <td>Misc.</td>
  <td>zx-button-black</td>
  <td>Pill shaped button. Lol.</td>
  <td>Any text tags</td>
</tr>
</table>

<h1>Install</h1>
<a href="https://zenyxis.com/downloads">zenyxis.com</a>
Make sure to place the link tag in the head tag if chosen, place @import in the stylesheet, whether internal or external.
If you directly install it, it will never be updated unless you reinstall the new version from <a href="https://zenyxis.com/downloads">zenyxis.com</a>
It's really not reccomended.

<h1>Status & Updates</h1>
Current Status: <b>WORK-IN-PROGRESS, NOT EVEN CLOSE TO BEING FINISHED</b>
<h2>Update v1</h2>
Initial Release

