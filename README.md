### customise-terminal-notifier
Script to setup terminal-notifier with a custom icon

```
usage: ${program} -i <file> -b <bundle_id>

options:
  -i <file>, --icon <file>               Set the icon (can be either an 'icns' or an image format, like 'png')
  -b <bundle_id>, --bundle <bundle_id>   Set the bundle id
  -h, --help                             Show this message
```

example usage
```
~/desktop/customise-terminal-notifier.sh -i ~/Desktop/steem.icns -b com.steem.steem-notifier
```

### originally found in small scripts - [Tiny Scrips - vitorgalvao/tiny-scripts](https://github.com/vitorgalvao/tiny-scripts/)

This script was part of tiny script but was [removed at this commit](https://github.com/vitorgalvao/tiny-scripts/commit/37044c535189b767f601cddb8df3a716ea1d490f) I found references to this script and found it useful so I brought it back to life to make it easier to find.

I used this in my repo [steem-notifier](https://github.com/code-with-sam/steem-notifier) to create a custom icon for native OSX notifications. ✌️

#### License
The Unlicense (Public Domain, essentially)
