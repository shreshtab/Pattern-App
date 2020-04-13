# Pattern App
*   Intro
    - Pattern app is next with cards
    - Font Awesome has updated too so will be doing some stuff with it
    - Only 1 line of CSS! Rest is Bootstrap classes
*   Nav
    - Nav - with class navbar with pattern + logo inside a container (use bg-dark, navbar-dark)
    - Try nav.navbar.bg-dark... and hit tab. Works wow!
    - a.navbar-brand with Pattern inside the text. Note: Add container first and a inside
    - Font-Awesome: Some free and others are not. Look for the free ones, maybe binocs
    - Copy the i tag before the word Pattern, and then add the CDN to the head after the Bootstrap link
    - Add mr-2 to the i tag
*   Jumbotron
    - Section vs div is pretty similar
    - section#header.jumbotron.text-center
    - h1.display-3 inside this, then p.lead with junk text
    - a.btn.btn-primary and then btn-successs with labels - Do Something, Another Thing
    - Procure header.jpeg from file and instead of a separate stylesheet, in the head, add a style tag, select the header ID
    - background: url("img/header.jpeg") center center / cover no-repeat (maybe keep this remaining stuff as a comment)
*   Cards
    - Lots of stuff that we can do per the docs!
    - section#gallery > div.container > div.card > img.card-img-top with src from the uploaded ones
    - In the card, after img > div.card-body > h5.card-title ("First"), p.card-text ("LI Text"), a.btn.btn-outline-success.btn-small ("Download")
    - Duplicate, then btn-outline-danger and instead of download, use a FA icon for the heart
*   Card sizing
    - After lg, goes to 3 across
    - Add a div.row > div.col-lg-4 and then add the card div. Then duplicate the col-lg-4 twice and change the pics and descriptions
    - For the margin, after the col, mb-3 or mb-4