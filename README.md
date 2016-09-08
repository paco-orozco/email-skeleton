#Skeleton Email Template

Use this .html setup to create cross browser/client email templates. Stand alone file that is coded using best practices including the proper document setup using XHTML 1.0 Transitional Type document decleration. Also uses the proper tags for viewport and content declaration. Media Query for responsive styles is also initiated for responsive design.


###Best Practices: Design

* Emails should be 600-800 pixels maximum width. This will make them behave better within the preview-pane size provided by many clients.
* Assume images will be initially blocked by email clients, or that certain images—background images, for example—will completely fail to load.
* Avoid elements that require Flash or JavaScript. If you need motion in an email, a .gif is your best bet.

###Best Practices: Development

* Code all structure using the table element. For more complicated layouts, you should nest tables to build complex structures.
* Use element attributes (such as cellpadding, valign, and width) to set table dimensions. This forces a box-model structure.
* Inline all CSS before sending.
* Use only absolute links for images, and host those images on a reliable server.
* Don’t bother with JavaScript or Flash—those technologies are largely unsupported by email clients.
