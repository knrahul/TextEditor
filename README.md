## Text editor ##

This project implements a simple text editor with a font family, font weight and italic
selector that instantly changes the font of the entire text. Font selector shows a list
of all google fonts and font weight selector shows the appropriate font weights
supported for the selected font family. Italic toggle is only active if the selected font
family and weight combination supports italic. You also need to implement auto save
which saves the text and font family locally in the browser. On reloading the page,
existing content should load and correct font family and variant should be selected in
the dropdown.

## Features ##

Load fonts from a JSON file and populate the font family dropdown.
Update the font weight dropdown based on the selected font family.
Apply selected font family, weight, and italic style to the content in the text area.
Save the content and font settings locally.
Load saved content and font settings.
Display saved contents.
Clear all saved contents.
Reset the editor content and font settings.
Prevent saving empty text and show an alert message.