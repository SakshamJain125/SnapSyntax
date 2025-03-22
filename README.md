# SnapSyntax
✅ HTML (Structure)
1. Header / Navbar
You’ve got the website heading "Pam" hanging out on the left side.
Next to it, you'll find:
Info (styled lightly bold with CSS).
Project with a superscript number 44 (just for show, not a link).
In the middle of the navbar:
The brand name "E c o m m e r c e" with those nice spaced-out letters.
This navbar is sticky, so it stays at the top while you scroll.
2. Description Section
There’s a right-aligned paragraph that lays out what the e-commerce site is all about.
3. Product Boxes Section
You’ll see 6 sections for products (
blocks), each containing:
A product name (displayed above each box on the right).
A content box that holds:
One image.
One video (it’s muted, autoplaying, and looping).
Each product box has a unique background color (white, green, pink, yellow, red) that shifts as you scroll down.
Even though videos don’t actually start on hover (thanks to browser security), they do fade in and zoom a bit for a cool effect.
4. Big Display Image
Right after the product boxes, there’s a big, full-width image (like a hero banner).
5. Contact Section
At the very bottom, you’ll find a contact form featuring:
A spot for your name
A field for your email
A textarea for your message
A big, bold submit button that looks inviting and ready to click.
✅ CSS (Styling & Layout)
1. Body and Header
background-color: #fdf5e6; gives the whole site a creamy background vibe.
The header uses flexbox: left for the heading and info, center for the brand name.
Sticky navbar: position: sticky; top: 0; keeps it in view when you scroll.
2. Typography
The Info text is a bit lighter (font-weight 300).
Project text sports a red superscript (styled to look smaller and a different color).
3. Description Styling
The description paragraph is right-aligned, with some nice margins and a bigger font size.
4. Box Section Styling
Each .box-section has generous padding and vertical spacing.
The product name (h3) is right-aligned.
.content-box makes sure the image and video sit side by side with some room in between.
5. Video & Image Hover Effect
The videos and images have smooth transitions (transition: change 0.6s ease, opacity 0.6s ease;).
When you hover, the video/image slightly grows (change: scale(1.08)) while the video fades in from a bit dim (0.5) to bright (1).
6. Background Colors on Scroll
Every product section (.box-section) has its unique background color (white, green, pink, yellow, red).
These colors change smoothly as you scroll through the sections.
7. Big Image Styling
The large display image spans the full width, with rounded corners and some space above it.
8. Contact Form Styling
The form is centered, featuring a white background, large fields, and a red button that turns darker on hover.
✅ Key Visual/UX Features:
FeatureHow it worksSticky headerThe navbar sticks around at the top when you scrollSection color changesEach product section has its own background color to keep things interestingVideo hover effectThe video pops up a bit (opacity and scaling) when hoveredResponsive layoutFlexbox keeps things neat with boxes wrapping and centeredContact formA straightforward, clean form with an engaging button

