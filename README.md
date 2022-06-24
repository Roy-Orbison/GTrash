# <img width="24" height="24" src="icon.svg"> GTrash

Provides a button and keyboard shortcut (<kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd> by default) to move selected messages to the Trash folder regardless of the mail account's _When I delete a message_ setting.
It was developed to improve the experience of using GMail via IMAP.

The [recommended option for that setting][0] is _Just mark it as deleted_, which preserves the concept of Thunderbird folders acting as GMail labels.
Deleting from a folder should only remove that label, and leave the message archived under _All mail_.
Moving a message from any folder to Trash (or Junk) will result in permanent deletion (after the grace period), also removing all other labels.

Regular <kbd>Shift</kbd> + <kbd>Del</kbd> is unhelpful with GMail because it works similarly to normal delete, only removing a label without the desired permanent removal.

It is not recommended to use _Move it to this folder: Trash_ as the general delete setting because it breaks the folders-as-labels convention.
With that, the only way to remove a label would be to move a message to the _All mail_ folder, where it already exists, which is very unintuitive.

You can edit the default shortcut under _Add-ons and Themes > Extensions > :gear: > Manage Extension Shortcuts > GTrash_.

[0]: https://support.google.com/mail/answer/78892?hl=en#zippy=%2Cthunderbird
