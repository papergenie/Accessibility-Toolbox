

Story Mode Website= HTML + ARIA:  



Open Discussion on Best HTML ARIA Workflow practices
Input for tools



Awesome Accessibility
- Pay for User Testing
- Docs
- Tools
  - Checklists
  - Desktop, Bookmarklets, Website Checker
- 100% Matrix

Terms


HTML Semantic Quiz - Decision Tree, Good Web Habits


HTML+ARIA

---

## Accessibility Toolbox:  

One git repo box for all user accessibility needs for the Web Developer of 2020.

Design Accessible First Websites!

Toolbox includes references for ...

- Terms

- Font Selection.
- Font Scaling.

- Color Selection
- Color Contrast

- Website readability: Color, Font style guidelines. 
  - Design light, dark, high and low contrast themes be readable to all users.


- Code for screen reader usability.
- How to write image alt text for screen readers.
- Semantic HTML Tags <nav> <header> <aside> <main> <section> <article> <footer>
- ARIA Tags
- Website Content Flow for different text alignments and directions.
  - Accessible friendly Grid-boxes


- Javascript accessibility guidelines.
  - Page Loads

- ADA & WCAG Links.


- Web Markdown Accessibility

Attend the meetup to hear and see how upgrade your workflow for accessible first websites. 



---

News:  

- https://stripe.com/blog/accessible-color-systems


- 7 Alternatives to the <div> HTML Tag - https://medium.com/@zac_heisey/7-alternatives-to-the-div-html-tag-7c888c7b5036


- https://www.slideshare.net/anm8tr/accessibility-for-fun-and-profit

---


## Devbox 2020 - Accessibility Toolbox Edition:

HTML + ARIA Edition

---

## Why HTML + ARIA?:  

To create a user experience and gain [SEO](https://yoast.com/what-is-googlebot/) exposure!


---

## Is my website accessible?:  


- HTML5 + ARIA tags allow screen readers and SEO bots to navigate the webpage.


Semantic HTML tags
```html
<nav> 
<main>
<section>
<article>
<aside> # as a sidenote
<footer>

<a>
<button> # Replace all <div> buttons with the <button> element.
<details>
<input>
<select>
<textarea>
```


ARIA tags


```html
aria-label
aria-hidden
aria-live
aria alert

tabindex
role="menu" # For main menus and sidebars use <nav> elements over using role="menu" aria tag
```


___


### An Accessible Website ...

- Supports Font Size Override layouts.

- Uses the [Flexbox Grid](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) or a [CSS Grid Framework](https://foundation.zurb.com/sites/docs/xy-grid.html) for content layouts.

- Avoids CSS floats which could break the content layout either by screen size, font-size, or web browser. 

- Orders the Webpage content with HTML. Screenreaders and SEO bots read by HTML DOM order.

- Uses tabindexes for webpage widgets.

- Has accessible HTML + ARIA code for a DatePicker, Payment Process, Drop down menu, and other UI elements

---

## 100% Accessibility:  Accessibility Matrix

`Platforms = Language * Currency * Accessibility * (Browsers + Screenreaders + Apps) * (Phone + Tablets + Desktop)`

---

### I18N - Language and Currency:  

- About 300 Languages actively exist online.
  -  Wikipedia articles have been created in 304 languages, with 294 active and 10 closed - https://en.wikipedia.org/wiki/List_of_Wikipedias#Detailed_list

- 180 currencies recognized as legal tender in United Nations (UN) - [Currency](https://en.wikipedia.org/wiki/List_of_circulating_currencies) 

---

### Accessibilities:  

___

#### Vison 5

- High contrast
- Low contrasts
- Light Theme
- Dark Theme
- Font Size Override

<hr>

Scenarios

- dyslexic High contrast requirement 
- dyslexic Low contrast requirement 
- Night time - Dark background, Warm colors
- Sunlight, Office Light - Light background

<hr>

- 6 Surprising Bad Practices That Hurt Dyslexic Users - https://uxmovement.com/content/6-surprising-bad-practices-that-hurt-dyslexic-users/
  - Bad character and word Spacing 
    - Use OS supported fonts to fix font space. Avoid justified text and double space after period, use normal word spacing.
  - Poor font weight
  - Long blocks of unbroken paragraphs
  - Washout Effect - Example, transparent wallpaper backgrounds color colliding into the font
  - Serif fonts - avoid cursive fonts and Times New Roman.
  - Italicized text


- The effect of contrast on reading speed in dyslexia. - https://www.ncbi.nlm.nih.gov/pubmed/10837835


<hr>

Dyslexia Products

- Colored Overlays - https://www.amazon.com/Colored-Overlays-Reading-Tinted-Dyslexia/dp/B00NEYYRLW/
- Colored Paper - https://www.amazon.com/School-Smart-Exhibit-Inches-Assorted/dp/B003U6QDJI/

___
#### Sound 2

- With sound
- Without sound use Closed captions

<hr>

Scenarios

- Loud Room, Bartender
- Thicc Accents

___
#### Dexterity 3

- Drag and Drop 
- Pinch to Zoom
- Shake to undo

<hr>

Scenarios to avoid dexterous controls

- Cognitive Imparement 
- Driving
- Drunk
- Tired
- One Hand - avoid Pinch to zoom


- Text Selection - Hard press??
- Drag and drop alternative, Select and Move



___
### Browsers 6

<br>

- Browsers - Chrome, Firefox, Safari, Opera, Screen Reader, and IE

- Viewports - Mobile, Desktop, Tablet, Small Printer Screen

___

### Architectures 4

```
x86-32bit
x86-64bit
ARM
MIPS
```

___

```
UI - HTML XML, verb LUA, 
App API
Web Browser
DB - Database
FS - Filesystem
OS - Operating System
Kernel - System Runtime, Driver Runtime
GPU
CPU
MicroController
Radio
Device 
```
---

## Demographics:  

- Refer to "Accessibility for Fun and Profit" by Mike Wilcox - https://www.slideshare.net/anm8tr/accessibility-for-fun-and-profit

---

## Terms:  

- HTML - Hypertext Markup Language. Screenreaders read by the HTML DOM order `Content Order` of the Webpage for the screen reader.

- ARIA - Accessible Rich Internet Applications. HTML tags helping the text adventure of the website.

- Semantic - relating to meaning in language or logic.

- i18n - Internationalization. Accessible Language and Currency.

- a11y - Accessibility. Accessible to Screenreaders and [SEO bots] ([GoogleBot](https://yoast.com/what-is-googlebot/), [BingBot](https://en.wikipedia.org/wiki/Bingbot), [DuckDuckGoBot](https://en.wikipedia.org/wiki/Googlebot))
- DOM - Document Object Model - https://en.wikipedia.org/wiki/Document_Object_Model

___

- [WAI-ARIA](https://en.wikipedia.org/wiki/WAI-ARIA) - Web Accessibility Initiative - Accessible Rich Internet Applications

- WCAG - Web Content Accessibility Guidelines
  - Provides a single shared standard for web content accessibility

- ADA - American Disability Act - Section 503 - https://www.ada.gov/2010ADAstandards_index.htm

- ADA Section 503 - https://adata.org/factsheet/section-503, https://www.dol.gov/ofccp/regs/compliance/section503.htm


- ARIA Mission - The way to provide proper semantics for custom widgets to make them accessible with assistive technologies


- [Kerning](https://en.wikipedia.org/wiki/Kerning) - Character spacing

- [Keming](https://old.reddit.com/r/keming/) - Bad character spacing

---

## Accessibility Law:  

- Demand Letter - compliance complaint not allowing accessibility access - https://www.boia.org/demand-letter#demandletter


- Gov Requirements, School Requirements - Web Content Accessibility Guidelines (WCAG) 2.1 Level A/AA

- Business Requirements, Payment Requirements - https://w3c.github.io/apa/payment-accessibility-reqs/


___
### Compliance:  

```
ADA Section 508
WCAG 2.0
WCAG 2.1 A, AA, AAA
```

- Checklist Outline of Web Content Accessibility Guidelines 2.1 - http://romeo.elsevier.com/accessibility_checklist/

- WCAG 2.0 checklists - Level A, AA, AAA https://www.wuhcag.com/wcag-checklist/

- Examples of WCAG Level AAA websites - https://www.wuhcag.com/wcag-level-aaa-websites/


---

___
Business
- ADA Domino's Suit

- WCAG 2.1 A/AA Has 50 Checkpoints, Categorized by 4 Principles - https://www.boia.org/wcag-2.1-a/aa-principles-and-checkpoints


---

## User Testing:  

`
“Recruiting internal staff to test a user interface should be a last resort” – Nielsen Norman Group
`
___

### Hire User Testers

- Accessibility User Testing - https://access-works.com/getstarted.php
- https://www.usertesting.com/be-a-user-tester
- Hiring Accessibility User Testers - https://www.peatworks.org/staff-training/hiring-consultants-testers

- WANTED! Accessibility testing participants - https://www.system-concepts.com/insights/wanted_accessibility_testing_participants/

___

### Conduct User Testing

- How to conduct User Testing - https://www.invisionapp.com/inside-design/accessibility-user-testing/

- Accessibility user testing: a cautionary tale - https://uxdesign.cc/disabled-user-testing-a-cautionary-tale-b6cf64425adb


- Accessibility Testing Tutorial: Which Disabilities to Support? - https://www.guru99.com/accessibility-testing.html

___


### Hire A11y

- https://www.a11yjobs.com/
- A11y Jobs https://www.accessibilityassociation.org/content.asp?contentid=295


---


# HTML Bootcamp

---

## Font Selection:  

Recommended Fonts

Currently, Section 508 of the Rehabilitation Act of 1973 does not specify the requirements for choosing an accessible website typeface. However, the US Department of Health & Human Services unofficially recommends the following fonts for PDF files: Times New Roman, Verdana, Arial, Tahoma, Helvetica, and Calibri.

- https://www.boia.org/blog/best-fonts-to-use-for-website-accessibility

- Use Verdana or Google-Noto i18n

- Verdana is easier to read for smaller fonts than Arial. Better kerning

___

### Dyslexia :  

- OpenDyslexic Download - https://opendyslexic.org/

---


### Other fonts:  

- Humanist fonts http://www.graphic-design.com/Type/bergsland/humanist.html

---



Replace Arial with Verdana
- Arial VS. Verdana - http://www.ahfx.net/weblog/44

- Ikea - Futura to Verdana to Google Noto - https://hypebeast.com/2019/8/ikea-typeface-noto-google-monotype

- Google NOTO - i18n font with no TOFU (missing characters)

TOFO - missing character represented by an empty box `□`



___


### Font Spacing

WCAG 2.1 Line Height

```
body { 
  line-height:1.5:
}
```

- Standard HTML `line-height:1.2`



---

## Type Scaling:  


- For marketing, use larger font ratios around 1.618 
- For Documentation, use a font ratio around 1.333


# Header 1
## Header 2
### Header 3  
#### Header 4
##### Header 5

___

- Marketing https://www.android.com/what-is-android/

```
# Marketing 1.618
# Sales 
# Shop
# Email
# Wiki Documentation 1.333
```

___

- Font Scaling Ratio Calculator - https://type-scale.com/
- Golden Ratio Font Scaling- https://grtcalculator.com/

- Major Third 5/4, 1.250 - https://en.wikipedia.org/wiki/Major_third
- Perfect Fourth 4/3, 1.333- https://en.wikipedia.org/wiki/Perfect_fourth

- Exploring Responsive Type Scales - https://medium.com/sketch-app-sources/exploring-responsive-type-scales-cf1da541be54




Perfect fourths 4/3

```css
h1 {font-size: 2.369rem;}
h2 {font-size: 1.777rem;} - 28.4px
h3 {font-size: 1.333rem;} - 21.3px
h4 {font-size: 1rem;} - 16px
h5 {font-size: 1rem;}
h6 {font-size: 1rem;}
```

```css
html {font-size: 16px;}

body {
  background-color: white;
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  line-height: 1.45;
  color: #333;
}

p {margin-bottom: 1.25em;}

h1, h2, h3, h4, h5 {
  margin: 2.75rem 0 1rem;
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  line-height: 1.15;
}


h2 {font-size: 3.157em;}

h3 {font-size: 2.369em;}

h4 {font-size: 1.777em;}

h5 {font-size: 1.333em;}

small, .text_small {font-size: 0.75em;}

```

___


Bootstrap

```css
h1 {font-size: 36px;}
h2 {font-size: 30px;}
h3 {font-size: 20px;}
h4 {font-size: 1rem;}
h5 {font-size: 1rem;}
h6 {font-size: 1rem;}



h1 { font-size: 2.2rem; }
h2 { font-size: 1.8rem; }
h3 { font-size: 1.2rem; }
h4 { font-size: 1rem; }
h5 { font-size: 1rem; }


h1 { font-size: 2.2rem; }
h2 { font-size: 1.8rem; }
h3 { font-size: 1.4rem; }
h4 { font-size: 1rem; }
h5 { font-size: 1rem; }
```

___


```css
# Wikipedia
h1 { font-size: 1.8em; }
h2 { font-size: 1.5em; } 
h3 { font-size: 1.2em; font-weight: bold; }
```


___

```
1 36px
2 30px
3 20px
4 14px


h1 2.57rem
h2 2.14rem
h3 1.4rem
h4 1rem
h5 1rem


36/30 = 1.2
30/20 = 1.5
20/14 = 1.43

2.57/2.14 = 1.2
2.14/1.4  = 1.5

acc 
.8 jerk
```

font-size: 36px;
font-size: 1.4em;

---

## Font-Size:  1rem

- `rem` values are relative to the root html element. <br> For general content use.
- `em` is equal to the computed font-size of that element’s parent. For HTML widgets

- Default html element font size is `16px`

___

- Font Size, Font Alignment Issue - https://www.netdata.cloud/

- https://medium.com/code-better/css-units-for-font-size-px-em-rem-79f7e592bb97

---

## Color Blindness:  

- Elder Color Blindness is blind to Blue and Yellow

- Inherited Color Blindness is blind to Red and Green

- Web Aim Color-blindness Guide - https://webaim.org/articles/visual/colorblind

___


### Elder Color Blindness:  

- Elder Color Blindness - https://www.sciencedaily.com/releases/2014/02/140220102614.htm


Nearly 80 percent of the abnormalities involved confusion of the lighter (pastel) shades of blue versus purple and yellow versus green and yellow-green. These "blue-yellow" errors are distinct from the "red-green" errors observed in people with inherited color blindness, which affects about eight percent of males and 0.5 percent of females


---

### Inherited Color Blindness:  

- Men - 8%
- Women - 0.5%

- How to Use Color Blind Friendly Palettes to Make Your Charts Accessible - https://venngage.com/blog/color-blind-friendly-palette/

---

### Tetrachromic:  

- 4 Color Cones - https://en.wikipedia.org/wiki/Tetrachromacy

- One study suggested that 15% of the world's women might have the type of fourth cone whose sensitivity peak is between the standard red and green cones, giving, theoretically, a significant increase in color differentiation

- Tetrachromacy may also enhance vision in dim lighting, or when looking at a screen.

---

---


## Color Selection:  

<br>

Are Web Safe Colors Safe?


___

### ![](image/no-Bugs-Bunny.jpg)

<br>

216 web safe colors were for 256 color PCs - https://websafecolors.info/learn

- Web safe colors are not safe from color contrast collisions

- Consistent Colors For Your Site - All You Need To Know About Web Safe Colors - https://www.htmlgoodies.com/tutorials/web_graphics/consistent-colors-for-your-site-all-you-need-to-know-about-web-safe-colors.html

___




## ![](/image/HSV-color-colors-wheel-names-degrees-rgb-hsb-hsv-hue.jpg)
###### Pick a safe color contrast with HSL Color Steps

- Colors Need Space. 
- Safe Space
- Color Themes - Hue 30°
- Foreground Background - Value 80%
- Value - 20%

___

- Pick a safe contrast between colors and values using HSV
#### Pick Semantic Colors using HSV





---

### HSL Color Steps:  

- Pick a 20% contrast for reading elements

- Pick a 10% contrast for UI coloring hinting - `<hr>` 

<hr>

- HSL full step 20% - 1/5  - `hsl(0,0%,80%);`

- HSL half step 10% - 1/10 - for background element color hinting

- HEX triple code Color Deltas are 6.5% 1/15

![](/image/HSV-color-colors-wheel-names-degrees-rgb-hsb-hsv-hue.jpg)

![](/image/web_safe_colors_by_hue.gif)



___




## HSV Safe Contrast Distances

- 30° Color Distance
- 2 Color Distance


Section

- Apple Contrast
- Wiki Contrast
- Android - Contrast
- Amazon - 


___

#### HEX Color Deltas:  


```
color: hsl(360,0%,80%);
```

```css

20% Delta

#FFF, 100%
#CCC, 80%
#999, 60%
#666, 40%
#333, 20%
#000, 0%


6.5% 1/15 Delta

#FFF, 100%
#EEE, 93%
#DDD, 87%
#CCC, 80%
#BBB, 73%
#AAA, 67%
#999, 60%
#888, 53%
#777, 47%
#666, 40%
#555, 33%
#444, 27%
#333, 20%
#222, 13%
#111, 7%
#000, 0%
```

___

```
:colorhighlight
```

---
 

---

## Color Wheel:  

- Wiki Color wheel - https://en.wikipedia.org/wiki/Color_wheel
- Blue: The Most Important Color In UI Design - https://uxplanet.org/the-most-important-color-in-ui-design-d4f23aefffdf

___

## ![RGB Color Wheel](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/RBG_color_wheel.svg/576px-RBG_color_wheel.svg.png)
```
red orange yellow chartreuse green springgreen cyan azure blue violet magenta rose
```

___

### RGB: Additive primary colors

- RBG Color Wheel - https://en.wikipedia.org/wiki/Color_wheel#/media/File:RBG_color_wheel.svg

## ![RGB Color Wheel](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/RBG_color_wheel.svg/576px-RBG_color_wheel.svg.png)

- Spring Green - https://en.wikipedia.org/wiki/Spring_green
- Chartreuse Green, Lawn Green - https://en.wikipedia.org/wiki/Chartreuse_(color)

___

### RYB: Legacy Primary Colors

## ![RYB Color Wheel](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/Color_star-en_%28tertiary_names%29.svg/480px-Color_star-en_%28tertiary_names%29.svg.png)

- https://en.wikipedia.org/wiki/Primary_color

___

### CYM: Substractive primary colors 

- Ink Colors - https://en.wikipedia.org/wiki/Subtractive_color

___

Color Wheel Division: 

```
rbg 1/3
cym 1/3
rygcbm 1/6
```


___

Bug: Multi Monitor Grey is horrible. Hard to calibrate color tempurature to multiple monitors.

- Colour Mixing: The Mystery of Magenta - https://youtu.be/iPPYGJjKVco?t=296

---

## Color Wheel Quiz:  

- New Android Color Scheme - https://www.android.com/android-10/
- https://www.android.com/versions/pie-9-0/
___

Add Personality by shifting the hue Left or Right on the color wheel

---




## Screenreader Experience:  

- Screenreaders convert websites into Text Adventures Games.


![](/image/lampcomp.png)

```
get lamp
```

- Jump to main content
- Read Article
- Pause, Play
- Read nav bar, Read sidebar
- Tab to widget

___


### Text Adventures:  

- GetLamp Doc http://www.getlamp.com/techsupport/
- GetLamp Trailer - https://www.youtube.com/watch?v=UwZxUGmqSOo


### iPhone Text Adventure Game - In a Door Room:  

- Best selling game 2013 - https://www.newyorker.com/tech/annals-of-technology/a-dark-room-the-best-selling-game-that-no-one-can-explain

- iOS Download https://apps.apple.com/us/app/a-dark-room/id736683061



---





---
---



# Semantic HTML + ARIA:  

- HTML Semantics affect the reading order.

- ARIA semantics only exposes extra information to a browser's accessibility API, and does not affect a page's DOM.


---


## Semantic HTML:  

#### Save the DIV ride the reader elements

HTML Reader Elements

```
<nav> 
<main>
<section>
<article>
<aside>
<footer>

<a>
<button>
<details>
<input>
<select>
<textarea>
```

---



`<aside>`:  As a sidenote

- `<aside>` should be side note information that is related to the article in context.

- http://html5doctor.com/understanding-aside/

___

- aside is not a sidebar! - this website is incorrect on aside - https://codeburst.io/seven-ways-to-make-your-web-app-more-accessible-411a8c716fcb



---

`<button>`:  Submit Button

- https://www.w3schools.com/html/html_accessibility.asp


---

alt="Text":  

Screenreader reads alt texts like any other text in DOM order. 


Markdown or HTML

```
![Story of the Image]()
```
- Hugo Static Site Generator - https://gohugo.io/showcase/
- GatsbyJS - https://www.gatsbyjs.org/docs/adding-markdown-pages/


HTML

```

```

___


Boring

```
![Women feeding a horse.]()
```
___



Wow horses need B3 for healthy hair

```
- Good
![Veterians nursing horse with oats supplemented with B-complex vitamins to maintain their healthy mane.]()
```


---

lang="fr":  

Language tags are designed to signal screen readers pronunciation engines to switch to another language.

- https://accessibility.psu.edu/foreignlanguages/langtaghtml/

___

- lang attribute specifies the language of the element's content. - https://www.w3schools.com/tags/att_global_lang.asp

---


ARIA:  

- ARIA Docs: Roles, states, and properties - https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques


```
tabindex
role="menu"
aria-label
aria-hidden
aria-live
aria alert
```


---

tabindex="-1":  

- https://www.w3.org/TR/wai-aria-practices/#kbd_roving_tabindex

Tabindex works as follows:


-  A negative value, tabindex="-1", -- J means the element should be focusable, but not reachable through sequential keyboard navigation.
-  A value of zero, tabindex="0", means the element should be focusable through sequential keyboard navigation, but the order in which it becomes focusable is denoted by the document’s element order.
-  A positive value means that the element should be focusable in sequential keyboard navigation, but its tab order will be determined by the value of the number. For elements who share the same tabindex value, they are focused in the order in which they appear in the DOM.


- https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex

```
Avoid using tabindex values greater than 0. Doing so makes it difficult for people who rely on assistive technology to navigate and operate page content. Instead, write the document with the elements in a logical sequence.
```

---

`role="menu"`:  for `<nav> and class="sidebar"`

- Aria Menu Specs - https://www.w3.org/TR/wai-aria-practices/#menu
- Navigation Menubar Example - https://www.w3.org/TR/wai-aria-practices/examples/menubar/menubar-1/menubar-1.html

- https://www.w3.org/TR/wai-aria-practices/examples/menu-button/menu-button-links.html

```html
<div class="menu_button">
  <button id="menubutton" aria-haspopup="true" aria-controls="menu2">
    WAI-ARIA Quick Links
  </button>
  <ul id="menu2" role="menu" aria-labelledby="menubutton">
    <li role="none">
      <a role="menuitem" href="https://www.w3.org/">
        W3C Home Page
      </a>
    </li>
    <li role="none">
      <a role="menuitem" href="https://www.w3.org/standards/webdesign/accessibility">
        W3C Web Accessibility Initiative
      </a>
    </li>
    <li role="none">
      <a role="menuitem" href="https://www.w3.org/TR/wai-aria/">
        Accessible Rich Internet Application Specification
      </a>
    </li>
    <li role="none">
      <a role="menuitem" href="https://www.w3.org/TR/wai-aria-practices/">
        WAI-ARIA Authoring Practices
      </a>
    </li>
    <li role="none">
      <a role="menuitem" href="https://www.w3.org/TR/wai-aria-implementation/">
        WAI-ARIA Implementation Guide
      </a>
    </li>
    <li role="none">
      <a role="menuitem" href="https://www.w3.org/TR/accname-aam-1.1/">
        Accessible Name and Description
      </a>
    </li>
  </ul>
  <script type="text/javascript">
    window.onload=function() {
      var menubutton = new Menubutton(document.getElementById('menubutton'));
      menubutton.init();
  </script>
</div>
```


---

aria-label="Sidebar":  

`
role="complementary" with an of aria-label="Sidebar" may be announced redundantly as, "complementary sidebar".
`

- https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/Complementary_role

---

aria-hidden="true":  

	
```html
<p aria-hidden="true">
  This content is not announced to screen readers.
</p>
```

- aria-hidden - https://www.scottohara.me/blog/2018/05/05/hidden-vs-none.html

- HTML5 Accessibility Chops: hidden and aria-hidden - https://developer.paciellogroup.com/blog/2012/05/html5-accessibility-chops-hidden-and-aria-hidden/

---


ARIA Dropdown Menu:  

### Custom Dropdown menu
- Collapsible Dropdown Listbox Example - https://www.w3.org/TR/wai-aria-practices/examples/listbox/listbox-collapsible.html


### Simple Dropdown menu
- https://a11y-guidelines.orange.com/web_EN/exemples/simple-menu/simple-menu.html

```html
<div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown">
    My account
    <span class="caret"></span>
  </button>
  <ul class="dropdown-menu">
    <li><a class="dropdown-item" href="#">My cart</a></li>
    <li><a class="dropdown-item" href="#">My orders</a></li>
    <li><a class="dropdown-item" href="#">My details</a></li>
    <li role="separator" class="dropdown-divider"></li>
    <li><a class="dropdown-item" href="#">Log out</a></li>
  </ul>
</div>
```



---

ARIA Datepicker:  
- https://www.w3.org/TR/wai-aria-practices/examples/dialog-modal/datepicker-dialog.html


---


# Javascript Guidelines

ARIA aria-live="polite":  

- ARIA live regions - https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Live_Regions

- CSS and JavaScript accessibility best practices - https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript


```
aria-live="polite" # The screen reader will speak changes whenever the user is idle.
aria-live="off" # silence updates
aria-live="assertive" # 

```
---

ARIA role="alert":  

- https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Live_Regions#Preferring_specialized_live_region_roles

Double Speak iOS

To maximize compatibility, some people recommend adding a redundant aria-live="assertive" when using this role. However, adding both aria-live and role="alert" causes double speaking issues in VoiceOver on iOS.

---




## CSS Layout, Flexbox:  

- Screen readers should read the webpage by DOM Order then use tabindex for widgets added to the page


Reorder visual order from reader order with `flex-direction:`

- CSS flex-direction -  https://css-tricks.com/snippets/css/a-guide-to-flexbox/
```
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
```

___

- stop floating


---



## Hello World:  

```html
<html>
<head>
</head>
<body>

<ux> 	 User Experience Menu
</ux>

<nav> 	Main menu
</nav>

<nav> 	Sidebar menu
</nav>

<main tabindex="-1"> "jump to main content" point

<section> 	Alerts, Pinned Posts
</section>

<article> 	Reader View Content
</article>

</main>
<footer> 	 SiteMap, Contact Us
</footer>
</body>
</html>
```


---

# Awesome Accessibility



## Tools:

## Screenreaders:  

### Be my Eyes
- https://www.bemyeyes.com/

### Seeing AI
- https://www.microsoft.com/en-us/ai/seeing-ai
- Seeing AI Demo - https://www.youtube.com/watch?v=EGBB-4TW__k




### Jaws
- Using JAWS to Evaluate Web Accessibility - https://webaim.org/articles/jaws/

### NVDA
- Using NVDA to Evaluate Web Accessibility - https://webaim.org/articles/nvda/


### VoiceOver iOS
- Using VoiceOver to Evaluate Web Accessibility - https://webaim.org/articles/voiceover/

### Orca - Linux OS Screen Reader
- Orca - Extensible screen reader that provides access to the desktop
https://www.linuxlinks.com/orcascreenreader/


Browser Screenreaders

### ChromeVox
- ChromeVox Extension - https://chrome.google.com/webstore/detail/chromevox-classic-extensi/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en


### Pericles
- Pericles - Text to Speech Screen Reader - https://addons.mozilla.org/en-US/firefox/addon/pericles/

___


- Is there an online emulating screen reader tool to test against a custom web page? - https://stackoverflow.com/questions/43340690/is-there-an-online-emulating-screen-reader-tool-to-test-against-a-custom-web-pag

---

## Checklist Tools:  

A11y Checklist, Compliance Check, Linter Tools, Web Accessibility Evaluation Tool

<aside>

- Note: Use User testing for a reliable validation of the webpage

</aside>



### Wave:  

- WAVE Web Accessibility Evaluation Tool - http://wave.webaim.org/
- Demo - http://wave.webaim.org/report#/radiantnuclear.com
- Wave Web Extension - http://wave.webaim.org/extension/

![Wave displays a list of errors based from the complance of WCAG or Section 503]()


---

### Tota11y:  
- Tota11y, an accessibility visualization toolkit - https://khan.github.io/tota11y/
- Tota11y Source Code - https://github.com/Khan/tota11y


import `tota11y.min.js` right before `</body>`

```html
<script src="tota11y.min.js"></script>
</body>
```

```sh
npm install @khanacademy/tota11y
```
---


### Accessibility Simulator:  

- No Coffee - Accessibility simulator - https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl

- Let's get color blind - Simulates information a color blind person receives and/or adds a daltonization filter. - https://addons.mozilla.org/en-US/firefox/addon/let-s-get-color-blind/

---

### Bookmarklets:  

- JavaScript Bookmarklets for Accessibility Testing - http://pauljadam.com/bookmarklets/


---

### Web Extensions:  


- Wave Web Extension - http://wave.webaim.org/extension/

- Axe - Web Accessibility auditing 
  - Chrome Axe - https://chrome.google.com/webstore/detail/axe-web-accessibility-tes/lhdoppojpmngadmnindnejefpokejbdd
  - Firefox Axe - https://addons.mozilla.org/en-US/firefox/addon/axe-devtools/


- Safari a11yTools Extension for Safari macOS - http://pauljadam.com/extension.html

---

### Automated Accessibility Testing Tool Server:  

- Automated Accessibility Testing Tool - AATT - https://github.com/paypal/AATT

---

### Pa11y:  
- https://pa11y.org/
- https://bitsofco.de/pa11y/
- Koa11y is a desktop app that allows you to automatically detect accessibility (a11y) issues on webpages. - https://open-indy.github.io/Koa11y/
---

### Web URL Checklist:  

Paste in URL or HTML to check website accessibility

- http://wave.webaim.org/
- Accessibility Compliance - Section 508, WCAG A AA AAA - http://www.cynthiasays.com/


___

- https://www.deque.com/tools/
- Checks HTML source code and detects violations of a defined coding standard - https://squizlabs.github.io/HTML_CodeSniffer/



---

### Human Checklist:  

- Outline of Web Content Accessibility Guidelines 2.1 - http://romeo.elsevier.com/accessibility_checklist/

- WCAG 2.1 A/AA Has 50 Checkpoints, Categorized by 4 Principles - https://www.boia.org/wcag-2.1-a/aa-principles-and-checkpoints


- Offical WCAG guidelines 2.1 - https://w3c.github.io/wcag/guidelines/


---


### Accessibility Compliance Products:  

- https://www.boia.org/

- Check Your Content Against Compliance Standards - https://www.compliancesheriff.com/

- DynoMapper - Website Accessibility Evaluation - Test the accessibility of any public or private website or online application. Free Trial - https://dynomapper.com/features/website-accessibility-testing


---



- https://developers.google.com/web/tools/lighthouse

- https://www.nvaccess.org/

- https://www.sitespeed.io/


---



## Docs, Reference, Discover:  

### Docs
- What are the Web Content Accessibility Guidelines? - https://www.wuhcag.com/web-content-accessibility-guidelines/
- https://fontawesome.com/how-to-use/on-the-web/other-topics/accessibility


### References
- awesome-a11y - A curated list of awesome accessibility tools, articles, and resources. - https://github.com/brunopulis/awesome-a11y



### Discover Web Accessibility
- https://github.com/collections/web-accessibility
- https://github.com/search?q=web+accessibility&type=Wikis



---


## Quizzes
- Quiz - https://www.a11yportal.com/advanced/quiz/code.html


## Good A11y Website Style References:  



Top 5 Websites

apple.com
youtube
Wikipedia
image gram
reddit
cnn.com, msnbc.,



- https://www.awwwards.com/


---

## Bad A11y - Website Style Fixes:  

- Font Size, Font Alignment Issue - https://www.netdata.cloud/

- Avoid blurry backgrounds - https://steamcommunity.com/games/342560/announcements/detail/469905196798266489

- HSL Font - http://www.andrespagella.com/introduction-particle-systems-html5-canvas

- Type-Scaling - https://www.w3.org/International/questions/qa-scripts.en






---





## Style Guidelines Linter:  

Design an accessible website using guidelines


## Cognitive Accessibility:  

abbr a11y accessibility


Client is 
sober - neurotypical
driving
drunk
Spectrum



Avoid Drag and drop


---

### Line of Sight:  

---

## UI Style Code:  

Design website themes

Style Code Cookie to import user style/accessibility preferences

---


---




# Thank You
