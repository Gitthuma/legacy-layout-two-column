Layout and grid systems before CSS Grid Layout

It may seem surprising to anyone coming from a design background that CSS didn’t have an inbuilt grid system until very recently, and instead we seemed to be using a variety of sub-optimal methods to create grid-like designs. We now refer to these as "legacy" methods.

For new projects, in most cases CSS Grid Layout will be used in combination with one or more other modern layout methods to form the basis for any layout. You will however encounter "grid systems" using these legacy methods from time to time. It is worth understanding how they work, and why they are different to CSS Grid Layout.

This lesson will explain how grid systems and grid frameworks based on floats and flexbox work. Having studied Grid Layout you will probably be surprised how complicated this all seems! This knowledge will be helpful to you if you need to create fallback code for browsers that do not support newer methods, in addition to allowing you to work on existing projects which use these types of systems.

It is worth bearing in mind, as we explore these systems, that none of them actually create a grid in the way that CSS Grid Layout creates a grid. They work by giving items a size, and pushing them around to line them up in a way that looks like a grid.

A two column layout

Let's start with the simplest possible example — a two column layout. You can follow along by creating a new index.html file on your computer, filling it with a simple HTML template, and inserting the below code into it at the appropriate places. At the bottom of the section you can see a live example of what the final code should look like.

Ref: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Legacy_Layout_Methods

Live web: https://gitthuma.github.io/legacy-layout-two-column/
