# emojicon

Bored of the same blue folder icons? Me too.

emojicon turns any emoji, image file or image URL into a macOS file or folder icon, or picks one for you based on the folder's name. One file, no dependencies, nothing to compile.

```sh
emojicon 🧪 ~/Desktop/Research
emojicon 📸 ~/Desktop/Screenshots ~/Pictures
emojicon ~/Downloads/spiderman.png ~/Projects   # any PNG/JPG/ICNS
emojicon https://example.com/logo.png ~/Work
emojicon --auto ~/Desktop/*        # picks an emoji from each name
emojicon --reset ~/Desktop/Research   # back to the default icon
```

## Install

```sh
curl -fsSL https://raw.githubusercontent.com/singhharsh1708/emojicon/main/emojicon -o /usr/local/bin/emojicon
chmod +x /usr/local/bin/emojicon
```

Works on macOS. It uses JavaScript for Automation (JXA), which ships with the OS.

## License

MIT
