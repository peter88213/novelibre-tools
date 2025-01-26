# novelibre-tools

OpenOffice/LibreOffice extension with tools for processing text documents in connection with 
[novelibre](https://github.com/peter88213/novelibre).


This extension adds menu entries to the **Format** and **Insert** menus of OpenOffice/LibreOffice *Writer*.

- The macro associated with the "Format" menu entry helps to change the look of your final document.
- The macro associated with the "Insert" menu entry is useful for setting up a "work in progress" 
  written with *Writer* to create a new *novelibre* project.


**Note:** The macros coming with this extension are meant to be used with text documents 
in connection with the novelibre application, where the paragraph style 
"Heading 4" is reserved for section dividers.
The use of the macros with other text documents may have undesirable side effects.

---

## Command reference


### Format > Replace section dividers with blank lines


![Screenshot](docs/Screenshots/format_menu01.png)

This will replace the three-line "* * *" section dividers
with single blank lines. The style of the scene-dividing
lines will be changed from  _Heading 4_  to  _Text body indent_.

![Screenshot](docs/Screenshots/section_divider01.jpg)

Optional command: **Tools > Add-Ons > novelibre-tools > Replace section dividers with blank lines**


### Insert > \* \* \* Section divider

![Screenshot](docs/Screenshots/insert_menu01.png)

This will insert a "\* \* \*" section divider, and 
apply the _Heading 4_ paragraph style. 

**Note:** Before calling this command, 
make sure the cursor is on a blank line.


Optional command: **Tools > Add-Ons > novelibre-tools > \* \* \* Insert section divider**

---

## Download and install

[Download extension](https://raw.githubusercontent.com/peter88213/novelibre-tools/main/dist/novelibre-tools-0.4.0.oxt)

* Installation right at download, by double-clicking on the downloaded file, or via the OpenOffice/LibreOffice Extension Manager.


## Get updates

This extension supports the update mechanism of OpenOffice/LibreOffice. You can let the Extension Manager check for updates from time to time to get the latest release.

---

## Credits

- [OpenOffice Extension Compiler](https://wiki.openoffice.org/wiki/Extensions_Packager#Extension_Compiler) by Bernard Marcelly.

## License

This extension is distributed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
