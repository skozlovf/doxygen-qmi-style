Qmi is a "**Q**t **Mi**nimal" theme for the Doxygen HTML documentation.
It based on official Qt4 documentation's style.

# How to setup

To use `qmi` style make the following changes in your Doxyfile:

    # Project section
    BRIEF_MEMBER_DESC = NO
    
    # HTML section
    HTML_HEADER = ${path_to_qmi}/header.html
    HTML_FOOTER = ${path_to_qmi}/footer.html
    HTML_STYLESHEET = ${path_to_qmi}/qmi.css


# Examples

If you want to see `qmi` style in action then use the following links with examples:

* [Qwt docs](http://skozlovf.github.com/doxygen-qmi-style/qwt)


Some screenshots:

![](http://skozlovf.github.com/doxygen-qmi-style/qwt_index.png)
![](http://skozlovf.github.com/doxygen-qmi-style/qwt_classes.png)
![](http://skozlovf.github.com/doxygen-qmi-style/qwt_doc.png)
