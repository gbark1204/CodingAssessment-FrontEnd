#Wolfe, LLC Front End Developers Coding Assessment

##Coding Assessment

This assessment covers some skills that the Front End Developer will perform
on a daily basis, and it will test the candidates on those skills and their
individual coding style. There isn't really any right or wrong answers. 
Avoid copy/paste from other websites, but feel free to look to the web for ideas.

##How to Submit Assessment

Clone GitHub repository onto local development machine. Complete the coding assessment 
and commit to your GitHub account. Email a link to your repository containing the
completed assessment. 


##Coding Tasks
###Task F1:
Convert the following CSS into one SASS or LESS file named F1.scss or F1.less:
```
.current
{
    display: block;
    color: red;
    background-image: url(//s.wlfcdn.com/giftcards/cms_proper/CMS-376/v1/dashboard-sprite.png);
    background-position: -385px 0;
    width: 166px !important;
    height: 38px !important;
    padding: 0 !important;
    margin: 18px 3px 0 0 !important;
    cursor: pointer
}


.current ul
{
    margin: 0 0 0 9px;
    padding: 0;
    border: 1px solid #9eb5c4;
    width: 152px;
    background-color: #2c8bb7;
}


.current ul li
{
    padding: 0;
    margin: 0;
    font-size: 11px;
    width: 152px;
    height: 25px;
    border-bottom: 1px solid #88cff0;
    background-color: #2c8bb7;
}


.current ul li a
{
    padding: 0;
    margin: 0;
    display: block;
    width: 152px;
    height: 25px;
    line-height: 25px;
    color: #FFF;
    text-decoration: none;
    text-indent: 13px
}


.current ul li a:hover
{
    color: #d3f0fe;
    display: block;
    width: 152px;
    background-color: #3ba4d5;
    padding: 0;
    margin: 0
}
```

###Task F2:
Write a responsive web page, F2.html, that matches the following parameters:
1. Header bar with a logo on the left, and 4 menu items on the right. 
- use any image or https://d1e5fyppsl97wz.cloudfront.net/v11-16-1-rc-2/images/SaveYa-Logo.png
- 4 menu items: 'Buy Gift Cards', 'Sell Gift Cards', 'Partners', 'Contact' 
(don't bother creating those pages)
2. The menu should collapse to a rectangle with the word 'Menu' inside at smaller sized 
view. The 4 menu items should slide-down-reveal when the button is clicked.
3. There should be a hero section under the header bar that contains an image background 
that covers the whole hero section, but does not skew at any size view.
- use any image or https://d3ox5oa3lgo0ps.cloudfront.net/main-banner-blue.jpg
4. Centered header text inside hero that reads, "Hello World!".
5. Centered sub header text inside hero underneath header text that reads, 
"A test webpage.".
6. Add a paragraph of Lorem Ipsum text under the hero
7. Add a footer section that's a grey background with white centered text that reads 
"Goodbye, World!"

You may use a frontend framework(s).