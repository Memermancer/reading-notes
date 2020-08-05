**Responsive Web Design
Mobile web access has increased the accessibility of the internet many times over in recent years. This poses challenges as to how we can design web pages to work well no matter what device is being used to view them. Ethan Marcotte coined the name responsive web design. Responsive design reacts quickly and positively to change, while adaptive means the design can be modified easily. They are different but related concepts. Mobile design just means making a whole new site for mobile users. CSS has flexible layout styles that we can use to make responsive sites. The article goes on the discuess media queries which could be exciting to dig into. Try designing for mobile first then build up.

**All About Floats
Float is a positional property in css. We float images so text wraps around them, and this practice comes from print media. Floated elements remain part of the flow of the webpage, as opposed to absolute positioned elements that are removed from the flow of the website. Float isn't normally used for layout anymore due to the effectiveness of display grid and flex. Float can be overwritten with the clear property. Unusually, a float property can affect a parent element, if a parent only contains floated elements it will collapse. There's some fancy tricks in the examples I am a little intimidated by. It goes into some problems that IE6 has with floats, which I don't think we should be too worried about.

**Don't Overthink It Grids
Most sites use a grid. Either implicit or explicit. The methods in this article are outdated because flex and grid displays have overtaken float as a primary means of laying out page but some of the techniques could still prove useful. CLear your parent elements so they don't collapse. Gutters are a tricky part of using this method. The author uses something called SCSS/Compass which might be worth asking about in class.

**CSS Floats Explained By Riding An Escalator
Floats can have a lot of unintended behavior. Floats create alternate flows. Write code that accounts for three flows, normal, left and right. Floats address the relationship between these flows. Use clear to allow elements to specify where they should align in comparison to the floated elements.

**SMACSS Official Documentation
SMACSS is a style guide for front end projects. this looks like a great resource to reference.