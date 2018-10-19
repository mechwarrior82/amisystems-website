---
# The Hugo Grayscale theme is a one page theme designed to be the front page to your site.  Its content is populated via the front-matter in content/_index.md.  The page consists of, in order:
# * a navbar at top linking to the other sections, and other arbitrary links
# * an intro section presenting a header title and into text with background image
# * an about section presenting a header and text with black background
# * a download section presenting header and text with background image
# * a contact section presenting header and text with black background
# 
# The section names show up as the links in the navbar, so you may wish to rename them if, for example, you're not using it for the purpose suggested by the default section name.
# 
# The background images are selected by filename - the intro section image must be named "intro-bg.jpg" and placed in the "static/img/" directory for your site.  Similarly, the downloads section image must be named "downloads-bg.jpg" and placed in the "static/img/" directory for your site.  See the default images in the theme's static directory for file size reference.

title: "Advanced Microcontrols, Inc."
date: 2018-09-09T00:00:00-00:00
copyright: "Advanced Microcontrols, Inc."
#mapsapikey: xxx

socialhandles:
    # twitter: ""
    # github: ""
    # googplus: "goog_addr_here"

menu:
    -
        url: ""
        name: ""

intro:
    header: "header here?"
    text: "sub text here?"

about:
    header: "About Advanced Microcontrols, Inc."
    text: '<p>AMI (Advanced Microcontrols, Inc.) specializes in the design and manufacturing of quality controls and other innovative electronic devices for the elevator contractor. we constantly see ways to incorporate the latest technology into all of our products to make them more durable and/or easier to use. Because of our dedication to quality and innovation, we at AMI can be depended on to supply reliable products at competitive prices.</p>'

download:
    rename: "Links"
    header: "Download manuals"
    text: '<p>You can download product manuals for free from the Github page.</p>
    <a href="..\manuals\satellite_C75D-C7232.pdf" class="btn btn-default btn-lg">Download Manual 1</a>
    <a href="..\manuals\satellite_C75D-C7232.pdf" class="btn btn-default btn-lg">Download Manual 2</a>
    '

contact:
    header: "Contact Information"
    text: '<p>Please feel free to contact us with questions, information request, or quote request.
    <br>Telephone: 817-589-0416 | Fax: 817-595-0070</p>
    <p>Postal Address 
    <br>7710 Trinity Blvd. Fort Worth, Texas 76118</p>
    <p>Email:
    <br>General Information and Sales: mike@amisystems.com
    <br>Customer Support: greg@amisystems.com</p>'
---