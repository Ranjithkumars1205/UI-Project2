shortcut for html structure - ! and hit enter

<!-- just write an exclamation mark and you can hit the tab on your keyboard, then you will get very basic HTML structure -->

<h1>Lorem</h1> - Lorem10 and hit enter - it will give 10 words for you or just type Lorem - it will give you some sentence for you

# Flex Box:

basically, we want to line up left to right, we have to use float. but we can use flex box instead of this.
flex box is the next advance method of this.

if you use flex box, use justify-content: center otherwise use text-align: center

if you need space between up and down, first of all don't use margin.. instead of this, increase the min-height if you want

align-items for one row; align-content for more the one row

if you want to make center vertically without flex, use line-height or adjust all side of padding for button/inline-block elements instead of align-item/centre.

\*remove height/min-height if you apply height basically.. if you want height, apply it otherwise not needed if we have padding

min-height - it will make responsive

By default, H1 tag has 16px

google font we are using are roboto, playfair.

playfair - regular 400

google it - "google fonts pairing 2023" - you will get some of this website for reference - https://inkbotdesign.com/google-font-combinations-mixing-typefaces/

this website looks nice with our gradient and our fonts.

# why you can't use pixels for font sizes anymore

- px is absolute fonts. they're the same on all the computers. we can't changed.
  we cant mess around with them.

we need relative fonts, that's where em and rem are come in.

3 rems is bigger than 30 pixels.

i didn't style it
i haven't done anything to it.

by default, font size for google browser is 16 pixels.
`rem is 3 times bigger than pixels`
16 pixels \* 3 = 48 px = 1 rem

1 rem = 16 pixels;

rem will be usefull when we trying to customize font-size by using chrome brower settings -> appearance, it will be change as per your selection.
but pixels not like that.

1. if you use it, your site better
2. google will base your site on how accessible it is.

# Rem vs Em

Rem ignores the wrapper tags size.

R is root, so root em.
all right, the default's still 16.
so, i'm 3 times of 16

i wanted to be 20 pixels

0.0625 \* 20 = 1.25 em

it means 20 pixels is (0.0625 \* 20px) rem/em = 1.25 rem/em;

if you want what px it is when you have rem/em size,
here you go,

1.25 rem/ 0.0625 = 20 px;

# Line-height:

we can look at doing the space between paragraphs.

line-height mainly useful for make space between paragraph or any text of the more the a row contents.

# When would you use an svg image instead of jpg or png in web design

Why don't we just use those?

jpg has good quality and file size is very, very small as well as it has loads of colors

then, where do JPEGs stop?
`Big trouble with JOEG is that there's no transparency.`... for examples, logo and bikre repair service img in the website, when you drag the logo around, you can see its transparency and see through.. but not with bikre repair service in the herobox2.

ya, okay, png is awesome, they have loads of colors as well. you can use millions of colors in a PNG but it alsp has transparency.

you might be saying,
`Why don't we just use those?`
becaus the file sizes are huge for PNGs in comparion to a JPEG.
so, you got to do a trade-off
do i need transparency..

if you do, then you have to leave JPEG behind.

if you don't, definitely a JPEG. there is no transparency and low file size with all the goodness of the colors.

Now the third option the SVG, is quite new
SVG stands for Scalable Vector Graphics.

But the benefit of it, as long as it's a really simple shape like an icon or a logo..

an SVG would be terrible for this, even if you wanted transparency..
but for simple shapes SVGs are brilliant.

So, logos here, we're going to switch this out for an SVG and look at the perks.

a PNG uses pixels to make its graphic, and while it was really small it was fine...
PNG has a slightly blurry edge but vector is fine.
if you make them bigger
you can scale it as big as you like, it would be really good.

GIFs, the only reason you use GIFs these days, if you need to animate them.

photoshop XD for png, jpg, svg

photoship cc for a photo editing program, here you can get different size of image like 1x, 2x, 3x.

always make layout with flex and background color

rem, we are using so far for font-size and margin-bottom

why we are putting h2 tag for cards, there are couple of things,
that text are smaller and
h1 is the most important, that's why we are adding in the herobox2.

h2, there aren't as important to the kind of overall importance of the website.

if you end up having like 10 h1 on your home page, it becomes hard for the search engines to know what your site is all about. so, keep it one or two.

Make sure we have to check text-align: center; could be suitable in the wrapper for all the items of that.

Why am i using pixels and not rems, that's a good question.
because sometimes people can- you can use rems for sizes like this as well

but i find, like i can't see the reason to hvae rems for h2..
So, it is, one rem is relative to whatever the default size is set to the browser

# How to add icons to your website using font awesome VS Code

there's just lots of cool - you know, you don't have to design them yourself.. they're all in nice little groups, they're free...
There's all sorts of good reasons to use fonts.

font awesome is just fonts. but material is a lot of things.

for font icon, you want to make some space then use padding instead of margin.. i don't know why it is like that. this couser, he is telling like that.

# Box-sizing: border-box;

it removes it off the width now

padding added and box will get bigger

start minusing the margin or padding of the overall width(100%) of the box.

by default, width will be 100%, so, content goes out if we dont apply box-sizing: border-box;

Here, the full width is 300px(should be have), no matter what! Ref: https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing
box-sizing: content-box; - If you apply padding/margin to the child element which has content-box. it goes out from the parent element..
in case you want to avoid that child element goes out from parent element box model, apply box-sizing: border-box; in the child instead of box-sizing: content-box or remove box-sizing: content-box;.

The boxes just get it's original 30% + padding.

if we apply border-box, it could minus the padding

/_ this two are combo
color: #fa4083;
font-family: "Playfair Display", serif;
_/

# inline elements"

a tag,
img tag

display: inline-block; - we are using scenarios like if we want to create customize button using a tag. we are using this. otherwise we use flex box for common layout.

# Border radius:

border-radius: 12px 0px 6px 100px;
Border-radius: LeftTop RightTop RightBottom LeftBottom;
most important features, we are using in cards, button and
layout as well.

tricks:
border-radius: 0px 100px 100px 0px;
border-radius: 1000px;

# Box-shadow and text-shadow

box-shadow: 5px(x-axis-towards right) 5px(y-axis-towards down) rgba(0, 0, 0, 0.228);
/_ box-shadow: 5px 5px `10px` black - here, 10px is blur_/

/_ box-shadow: 10px 10px 5px lightblue inset; - The inset parameter changes the shadow from an outer shadow (outset) to an inner shadow._/

text-shadow: 5px 5px rgba(0, 0, 0, 0.228); for text

# Hr tag

we're not using this anymore as a rulte by HTML documentation..
we're using it as like a content break
we're going to hide it
you should make it so it's styled so you can't see it
`it's used to break up content`
use border botton instead of this

`border-bottom: 1px solid lightgray;`

box-sizing: border-box; /_it is very important for child to make responsive for all font-size (check with chrome font size setting)_/

https://niva.io/tools/testimonial-generator - used to generate testimonials

div img:first-of-type – Selects the first element of this type within any parent. So if you have two divs, each had within it a paragraph, image, paragraph, image. Then div img:first-of-type would select `the first image` inside the first div and the `first image`(`not second image`) inside the second div.
