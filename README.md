# system76_keyboard_fn_fix
Fix for FN key-combos on System76 Gazelle 12 keyboards

On Gazelle 12 (gaze12) and possibly other System76 computers, the keyboard doesn't send a
release event when an FN keycombo is done.

This fixes the issue by always doing a force release on the keys from FN combos, so this
patch applies to the __play/pause__, __mute__, __volume down__, __volume up__,
__scroll lock__, __pause__ and __break buttons__.

__Note that this is more of a simple hack than anything else, and it applies to all generic
AT tranlated keyboards, so it applies even if you don't need the patch. Use it at your own
risk.__
