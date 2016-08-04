# webmenu-shortcut
It is used when you want to operate menu bar using keyboard.
It is basically developed in javascript.
###How to use ?
 - Add menu_bind_functionality.js in your page.
There are two ways to use :
1) Directly assiging shortcuts to menu li.
 - Just call placeShortcut function with no perameters.
    You need to declare attribut shortcut,display_shortcut and hilight_shortcut value on your main ul
    Also you have to give your attribut to your li as shortcut_key="you shortcut key"
2) Making list of shortcut sequencely.
 - Use placeShortcut funcation with perameter (list of shortcuts which you have to assign), {shortcut: true,
                    display_shortcut: true,
                    hilight_shortcut: true
                }
    Here if you want to apply shortcut then make that opetion true as shown above.
    Display shortcut is used dispaly shortcut on side of menu name
    Hilight shortcut will highligt a letter in name of menu if it exesist in name.
    Ex:menu name is sale and  want to give shortcut ctrl+alt+s.
        Here s will be highlighted as underline.
