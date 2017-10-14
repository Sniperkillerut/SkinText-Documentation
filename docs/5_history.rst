============
Change Log
============

Planned Features:
-----------------

    - [ ] Text Area: place a button to exit Text Area Selection /Resize mode.
    - [ ] Add checkbox: not possible, lost on save.
    - [ ] Change shortcut (ctrl+shift+n) or remove.
    - [ ] when click on notify icon: focus then hide/show.
    - [ ] Config tab -> windows settings, Register file association
    - [ ] Make 3 main colors more noticeable.
    - [ ] Change Configs to JSON format.
    - [ ] Change Colorpickers to Gradient Pickers. (requires JSON)
    - [ ] ARGs for skin.
    - [ ] Args for portable.
    - [ ] Move skin Mgr to main window and main windows to separate windows.
        - [ ] allow for multiple text windows at the same time.
        - [ ] this allows to create windows with rtb, checkboxes, paint, etc.
    - [ ] Make run only once.
    - [ ] Alarm / Timer?
    - [ ] Web Updater.
    - [ ] Turn all texts into resources for translation.

    - [x] Border binding to window actual-width.
    - [x] Check dragdrop to not accept .exe .ppt or anything weird.
    - [x] Make export ignore notes file.
    - [x] Config tab -> windows settings, Start with windows
    - [x] Fix text background (issues with RTF Fixed)
    - [x] Add "do you want to save?" dialog
    - [x] Open character map.
    - [x] Add undo /redo.
    - [x] Alt opens menu.
    - [x] Right click notification icon for menu.
    - [x] Menu tooltips.
    - [x] Icon by EdeFex.
    - [x] Hide Resize Corner.
    - [x] File Save confirmation shows filepath.
    - [x] Save/Open xaml, xamlp, rtf, txt.
    - [x] Super and Under script.
    - [x] All the other text position scripts.
    - [x] Changed closing behaviour.
    - [x] Add menu Commands (ctrl+s=save).
    - [x] Add FlipH FlipV.
    - [x] Changed gifMethod to Gif_uses_ram (string to bool).
    - [x] Allow to skin menu (advanced config).
    - [x] ToolBar Working.
    - [x] Add Blur.
    - [x] All icons in svg.
        Thanks to:

        `http://modernuiicons.com/ <http://modernuiicons.com/>`_

        `https://materialdesignicons.com/ <https://materialdesignicons.com/>`_

    - [x] Custom Control Styles.
    - [x] Changed font config window layout.
    - [x] AutoSave.
    - [x] Autosave custom timer.
    - [x] Change Config window.
    - [x] Add links.
    - [x] Register file association.
    - [x] Open registered files on double click.
    - [x] Fix startup intall/update behaviour.
    - [x] Fix Blur on windows 10 fall update.
    - [x] Skin install config.
    - [x] Skin package file.
    - [x] Import skin.
    - [x] Export skin.
    - [x] Tutorial.
    - [x] Baseline alignments.
    - [x] Rtb background transparency.

Changes:
--------

0.5.12
*******

    ApplyPropertyValueToSelectedText now working when there is no selection.

    Removed debug messageboxes.

    Fixed help.

    Added explore skins button.

    ApplyPropertyValueToSelectedText changed, now shorter.

    Screenshot file now retains name.

0.5.11
******

    A lot of relative imagepath fixes.

    BGImg now retains name.

    Creating a skin will now copy the img to the new folder.

    Relative imagepath are prefered.

0.5.10
******

    Added hyperlinks to files on dragdrop.

    Auto-hyperlink cheker fixes

    Export skin now with skinName and skinFolder.

    Changed Filepath from skintext.ini to config.ini

    Enabled relative filepath for bgimg

0.5.5
*****

    Fixing Visual Studio bugs.

    Added auto hyperlink check on space and enter

    Fixed all resizes.

0.5.4
*****

    Added Tooltips to Hyperlinks.

    Added ColorCanvasStyle1.

    Added hyperlink check.

    Changed style colorpicker2 to colorpicker.

    Added dynamic hyperlink tooltip.

    Changed colorpicker style to style2.

    Added check for not ovewriting config.ini when updating.

    Moved startwith windows to custommethods.

    Removed debug spam.

0.5.3
*****

    If manually saving while DelayedSaveAsync was waiting, stop DelayedSaveAsync.

    Added start with windows.

    Some more debuging msgbox (temporal).

    Edefex Link.

    Gradient Brush preparations.

    Portable changes.

    Added portable option.

    Added gradient brush picker (lib).

0.5.2
*****

    New document now displays "no title" instead of empty.

    Align right document Name on Menu bar.

    Refactoring.

0.5.1
*****

    Enabled updates again. (Testing for portable version)

    Messagebox to notice update.

    Removed msgbox with args and appdatacheck. (removed debuging messageboxes)

    Added padding to config window.

   Fixed typo on config window.

   Fixed transparency on Help.

    Show in taskbar for config window.

    Focus opened windows.

    Show in taskbar for tool windows. (popups)

    Minor changes.

0.5.0
*****

    Better order for bitmapimage imports.

    Added creative commons image.

    Completed Help

    Added About.

    Text background transparency changes.

    Minor changes to about menu click.

0.2.0
*****
    Added some transparency to Tools background Color.

    Major change to app flow now:

        -Start

        -Check for parameters

        -Get appdatapath

        -Check if runing from appdata

        -if yes run acording to parameters

        -if not then check if appdata exists

          -Create-copy-update-register-shortcut

          -if error run as admin the above function

        -close current

        -open appdata exe

        -close, delete current exe

    Added Skin Management.

    First pass of tutorial.

    Re*order custommethods.

    Corrected lineheight tooltip.

    Mouseover changes.

    Window:load changes.

    BGblur fixes.

    Variuos minor changes.

0.1.96
******

    Dragdrop now takes images too!

    Fixes to dragdrop.

    Changed LoadImage a little.

    Changed copy to appdata behavior.


0.1.95
*******

    Warning fixes.

    Added DragDrop.

    Fixed 2 color config errors.

0.1.93
*******

    Refactored, reordered, organized, simplified.

    CodeMaid.


0.1.92
******

    Added hyperlink window.

    Changed flip from panel to border.

0.1.9
*****

    Error catching fixes.

    More warnings solved.

    Major and complete Refactoring.

    Deleted GifMethod Global variable.

    Some code formating.

    First step for skin support.

    Added new code analyzers.

    Warning suppressing.

    More warning killing.

    CodeMaid fixes.

    Code alignment fixes.

    Turned most static color to resources.

    Turned all StaticResources to DynamicResources.

    CodeMaid reordering.

    Moved test folders to new folder.

    Changed base colors.

    Added advanced config.

    Finished toolbar buttons.

    Changed all images to canvas.

    Added Blur.

    Font Family combobox working.

    Added combobox style.

    Window Test movement working.

    Changed grid to dockpanel

    Fixed size issues on dockpanel.

    Remake config window.

    Some refactoring of customMethods.

0.1.65
******

    Moved imagesource1X to Globals

    Changed all dynamic resource to static.

    Changed textbox to decimalupdown.

    Added flipimages.

    Solving Visual Studio Warnings

0.1.50
******

    Font Config window added fonsize textbox

    Font Config window added super/sub*script.

    Some refactoring.

    Added button icons.

    Moved Styles to glbal.

    Modified text flow direction.

    Added all the baseline alignments.

    Added Render Flip to Rich Text Box.

    Minor formating.

    Changed closing behaviour.

    Added render flip to config.ini Save/load

    Refactored an if on rtb_selectionchange()for ``DependencyProperty.UnsetValue``

    Added custom commands to Menu.

    Mayor refactor.

0.1.38
******

    More Refactoring.

    changed file type selector for Open and Save.

    File name now visible on menubar

0.1.35
******

    Lots of refactoring.

0.1.33
******

    save confirmation popup now displays the filepath

    Hyperlinks are now more visible.

0.1.32
******

    Minor fixes to tooltips

    Menu show with ALT more responsively

    Resize Corners can be hidden

0.1.31
******

    Added Tooltips to Configuration Window

0.1.30
******

    Now With GIT!