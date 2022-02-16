# <img width="24" height="24" src="icon.svg"> GTrash

Provides a keyboard shortcut (<kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd> by default) to move selected messages to the Trash folder regardless of the mail account's _When I delete a message_ setting.

It was developed to improve the experience of using GMail over IMAP, where [it is recommended][0] to have the aforementioned setting on _Just mark it as deleted_.
This is so that deleting a message from a folder in Thunderbird is equivalent to removing a single label and leaving it archived under _All mail_,
and only moving to Trash (or Junk) will result in permanent deletion (after the 30-day grace period).
Using <kbd>Shift</kbd> + <kbd>Del</kbd>  to force deletion is not helpful because it works similarly to removing a label, and may not result in the desired permanent removal.
Using _Move it to this folder: Trash_ as the delete setting is unintuitive,
as then the only way to remove a single label is to move the message to the _All mail_ folder, where it already exists.

You can edit the default shortcut under _Add-ons and Themes > Extensions > :gear: > Manage Extension Shortcuts > GTrash_.

[0]: https://support.google.com/mail/answer/78892?hl=en#zippy=%2Cthunderbird