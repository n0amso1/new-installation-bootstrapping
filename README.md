# System

## Post-installation problems to address
* Screen tearing
* Issue https://github.com/systemd/systemd/issues/13943 requires early KMS boot
* Add input languages

## Terminal
* Color scheme
* Infinite scrolling
* Preferrably bi-directional support with UTF-8 for apps like ranger
* Install Zsh
### Oh-My-Zsh extensions
* Git integration
* Vim bindings for terminal

## Remapping
* Map `Alt+Shift` to change input language.  
Fix bug where only left `Alt+Shift` works, but changing input language by right `Alt+Shift` works only on English.
* Remap `CAPS LOCK` to `Esc`
* Remap `Fn`/`Right-click` to `Winkey` 
* `Alt+J` to `Down Arrow`, `Alt+K` to `Up Arrow`

# Applications

## Firefox
* Fix tearing by using `force-acceleration`
* SurfingKeys
* AdBlock Plus
* Change Firefox `about:config` to add smooth scrolling support - the required changes are described in a separate file.

## Community IDEs:
* Pycharm
* IntelliJ

## Editors:
* VSCode automatically installed with Python and C extensions.  
Edit VSCode config: don't open files as _"preview"_ (which auto-closes when opening another window)
