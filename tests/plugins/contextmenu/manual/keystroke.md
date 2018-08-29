@bender-tags: bug, 4.10.1, 1451
@bender-ui: collapsed
@bender-ckeditor-plugins: wysiwygarea,toolbar,contextmenu,clipboard,table,tableselection

## For each editor:
1. Scroll page so editor as at the top.
1. Select some editor context with mouse or keyboard.
1. Press `Shift + F10` to open context menu from keyboard.

### Expected

#### Left to right editors:
- The panel shows itself on the right side of selection.

#### Right to left editors:
- The panel shows itself on the left side of selection.


### Note:

IE8: There is known bug [#549](https://github.com/ckeditor/ckeditor-dev/issues/549) with wrong context menu position in inline editors.
