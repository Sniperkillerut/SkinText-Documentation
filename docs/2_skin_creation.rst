====================
Create your own Skin
====================

SkinText has a wide and extensive configuration, here we will go step by step to help you on your way to become a master skinner!

------
Colors
------
All of Skintext's color can be changed to your liking even with transparency (Gradients are planned for a future release)

Overlayed colors will stack/fuse/add if they are semi-transparent

 .. image:: img/Colors.png

The Color config window is organized as a table, here you can see **objects** at the left as rows and the **states** at the top as columns, lets go one by one:

*****************
Window Background
*****************
This is the Configuration and Font Windows background color, transparency is optional but recommended.

*****************
Button Background
*****************
This is the button background Color, has **states** for mouse over and selected.

*************
Button Border
*************
This is the button border color, this does not contain a "Normal" **state** to help on clarity/readability and to better highlight the *mouseover* and *selected* **state**.

***********
Button Text
***********
This is the color of all texts and images that are inside a button.

**********
Text Color
**********
This is the color of the texts, the labels, the  tittles and so on.

*********************
FontPicker Background
*********************
This is the Font picker Background color on the Font config window

*****************
FontPicker Border
*****************
This is the Font picker Border color on the Font config window

***************
FontPicker Text
***************
This is the Font picker Text color on the Font config window

***************
Menu Background
***************
This is the background color of the menu from the Main Window.

****************
MenuItem1 Border
****************
This is the border of the *File*, *Edit* and *Help* buttons from the menu.

***************
MenuItem2 Text
***************
This is the submenu Text highlight Color, the *Normal* Color is changed on `Text Color`_.

****************
MenuItem2 Border
****************
This is the submenu border highlight Color.

*******************
Disabled Item Color
*******************
This is the color of the disabled or unavaliable submenu items.

*****************
Main Window Color
*****************
This is the color of SkinText Main window, depending on the skin, if this uses a `Background Image`_ it is a good idea to use full transparency.

*********************
Text Background Color
*********************
This is the Text Area background color, using slight transparency is recommended.

*****************
Text Border Color
*****************
This is the Text Area Border Color, only visible if enabled in `Text Area`_

---------
Text Area
---------
Here you can change how the Text Area looks like.

**************
Rotation Angle
**************
Set the rotation of the Text Area in degrees (This includes the menu and the toolbars).

:min: 0º
:max: 359º

*********
Flip Text
*********
This consists of two buttons, *flip vertically* and *flip horizontally* (This does **not** include the menu and toolbars).

************
Text Opacity
************
The whole text opacity, it is different from the transparency used in `Text Background Color`_

*********
Read Only
*********
Sets the Text Area to read only mode, you can still select text but can not edit it.

***********
Spell Check
***********
Turns On/Off the Windows' Default SpellCheck (it is configured by your keyboard input language)

*********
Word Wrap
*********
Sets Word Wrap On/Off

Word wrapping is when a line of text automatically "wraps" to the next line when it gets to the end of a page or text field. [#]_

***************
Enable Toolbars
***************
Show/Hide the Text edition ToolBars

:Recommended use:
  Turn On when editing, Turn off when not editing to remove them from view and create a more immersive experience

*********
Auto Save
*********
Sets the interval in minutes between each autosave.

Set to Zero (0) to disable Auto Save feature.

SkinText will only auto save if there are unsaved changes and the file already exists.

******************
Resize / Move Text
******************
This will allow to resize the Text Area (This is separated from the Window Size).

this is different from `Resize Corner`_.

*******************
Resize Border Width
*******************
Sets the Text Area Border Width, set to Zero (0) to disable.

the border color can be changed in `Text Border Color`_

*************
Corner Radius
*************
Set each corner radius.

playing with this some somewhat complex shapes can be made, like teardrops or an eye.

***********
Same Radius
***********
This locks all the corner radius to the same value

***********************
Max Corner Radius Value
***********************
This is for some advanced shapes when radius is set bigger than the actual width of the Text Area, feel free to play with this.

------------------------------
Background Image Configuration
------------------------------
SkinText allows to skin it using images with trasnparency and even GIFs with animation.

*************
GIF Rendering
*************
SkinText can use two methods of rendering/loading Animated GIFs (This does not affect other file formats)

RAM
^^^^
    SkinText will load all the frames of the GIF on RAM, this will reduce the CPU and HDD usage, but will greatly incresease the amount of RAM that SkinText uses, this is recommended only for short/small GIFs or if you don't worry about RAM usage.

CPU
^^^^
    SkinText will load each frame of the GIF from the HDD according to the GIF framerate, this will use both HDD and CPU, these usages are really low but will keep RAM usage far lower than the RAM method, this is recommended for big/long/HD GIFs.

****************
Background Image
****************
Select the Background Image to use on SkinText.

**********************
Clear Background Image
**********************
This button will remove the Background Image.
    :Known Issue:
        If using a GIF with `RAM`_ method, the used memory will not be unloaded until SkinText restart.

*******************
BG Image Blur Value
*******************
Sets the amount of blur to use on the Background Image.

not to be confused with `Window`_ `Blur Background`_

******************
BG Image Blur Type
******************

Box:
^^^^
    A box blur (also known as a box linear filter) is a spatial domain linear filter in which each pixel in the resulting image has a value equal to the average value of its neighboring pixels in the input image. [#]_

Gauss:
^^^^^^
    The visual effect of this blurring technique is a smooth blur resembling that of viewing the image through a translucent screen. [#]_

*************
Image Opacity
*************
Sets the Background Image transparency.

notice that 100% will not disable/unload the image, for that use the `Clear Background Image`_ button

------
Window
------
**************
Window Opacity
**************
Sets the Main Window transparency.

**************
Always on Top
**************
Set SkinText to be above all other windows.

*******************
Tools Always on Top
*******************
Set SkinText Configuration Windows to be above all other windows.

************
TaskBar Icon
************
Show/Hides SkinText and all Config windows from the Windows TaskBar

*****************
Notification Icon
*****************
Show/Hides SkinText icon from the notification area

This is recommended to be enabled since in case of a bad configuration, you can still access the configuration window and can reset to defaults.

*************
Resize Corner
*************
Enables/Disables the grip on the bottom-right corner to resize SkinText Window, this is different from `Resize / Move Text`_ on the `Text Area`_ menu

***************
Blur Background
***************
Aneable/Disable the Blur on all SkinText Windows.

not to be confused with `BG Image Blur Value`_.

******************
Start with Windows
******************
If enabled SkinText will start automatically on Windows logon.

------------
Skin Manager
------------
Here you can Create, modify, Import, and Export your skins

*********
Skin List
*********
Shows a list of the currently installed skins.

******************************
Import and Export Skin Buttons
******************************
Whit these butons importing and exporting of skin is made really easy, for more information please read:

:doc:`importing and exporting skins`

*********
Skin Name
*********
Give a name to your awesome creation!

***********
Skin Author
***********
Promote yourself, be known to the world!

************
Skin Version
************
The version of your skin, 0.1.0 beta or whaterver you want

****************
SkinText Version
****************
The version of SkinText in wich your skin is created/modified

**********
Screenshot
**********
Show a preview of your skin creation for all to see.

*****
Notes
*****
Add any note you want, comunicate with the SkinText Family.

*********
Load Skin
*********
Loads/Sets the currently selected skin.


********************
Create / Modify Skin
********************
Create a new skin or modify te currently selected one.

----------
References
----------

.. [#] https://techterms.com/definition/wordwrap
.. [#] https://en.wikipedia.org/wiki/Box_blur
.. [#] https://en.wikipedia.org/wiki/Gaussian_blur