# No Hesi's FAQ Backups

This is a backup of all No Hesi's FAQ's from the Discord server. It is here in case of a nuke and for general safekeeping. A big credit to the original FAQ keeper: @grevious1

## How To Use
* `currentFAQs` - This will host all current FAQ's.
* `oldFAQs` - This will host all deleted FAQ's.
* `upcomingFAQs` - This will host any upcoming or experimental FAQ's.

## Note:
Currently this is not fully up to date. I will be fully completing it over the next week when I get time.

## How To Request An Edit

To make an edit, please do the following:

1. **Fork this repository** - Click the "Fork" button at the top right of this page to create your own copy.
2. **Make your changes** - Please refer to the section below on how to make proper edits.
3. **Open a Pull Request** - Go back to this repository and click "New Pull Request". Select your fork and branch as the source, then submit it with a short description of what you changed and why.
4. **Wait for review** - I will review your suggestion, leave feedback if needed, and either approve and merge it or request changes.

If you are not comfortable with Git, please open an [Issue](../../issues) instead, describe the change you would like, and I or someone else can make the edit on your behalf.

## FAQ Formatting

Each FAQ should follow this folder structure:

```
└── faqName/
    ├── content.txt
    ├── imageOne.png
    └── imageTwo.png
```

- **`faqName/`** - camelCase, no spaces or special characters (e.g. `howToJoin`, `rankRoles`)
- **`content.txt`** - contains the FAQ title, the message body, and references any images used (e.g. `[attachment: imageOne.png]`). Please separate all messages with `---` and blank lines surrounding it.
- **`attachments`** - upload all images/ video's with file names used in the content.txt