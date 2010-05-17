Feedback Boxes
==============

Most website today are interactive -- transfer of information is not only one-way but two-way. User are interacting with content: adding, editing and deleting stuff. A common concept these websites (should) have is user feedback for interactive actions. This sort of user feedback is most of the times realized with different colored boxes somewhere near the content that is manipulated. We created some standard XHTML feedback boxes with some custom icons -- if you like them, use them.

In the following image you can see the included icons:

![Feedback Icons Example](http://github.com/designchuchi/dc.feedback_boxes/raw/master/dc-feedback-boxes-icons.jpg)

Usage
=====

What? You need a How To? Okay. It's simple: Just include the CSS file in your HTML document and write the following:

    <div class="feedback info">Some feedback information</div>

This would then display a blue information box. For a validation error box use:

    <div class="feedback validation-error">
        <ul>
            <li>Some error in the form</li>
            <li>And another one</li>
        </ul>
    </div>

You get the idea. The following classes are available for you to use:

- info
- success
- error
- warning
- validation-error

Included in the download is an example XHTML page with all feedback boxes, a CSS file, the icons in PNG format in three different sizes plus the Adobe Fireworks source files of the icons. If you have any questions or wishes or recommendation leave a comment. You can distribute, remix, tweak, and build upon the files.
