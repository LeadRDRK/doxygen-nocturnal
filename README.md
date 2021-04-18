# Doxygen Nocturnal theme
Simple dark theme for Doxygen that tries to keep it similar to the original theme and be OLED friendly.
# Demo
A demo for this theme can be found at https://leadrdrk.eu.org/zpack
# Usage
Put customdoxygen.css in the same directory as your Doxyfile. Modify the HTML_EXTRA_STYLESHEET field to include it.
```
HTML_EXTRA_STYLESHEET  = customdoxygen.css
```
Also modify the colorstyle's gamma to match the theme.
```
HTML_COLORSTYLE_GAMMA  = 180
```
Additionally, you may want to use a custom DoxygenLayout.xml and change the Main Page's tab title to your project name.
