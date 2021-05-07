# Simple rEFInd Theme

[rEFInd][refind] is an easy to use boot manager for UEFI based systems. This is a simple theme for it.
It comes in a light and dark variant and is based on the rEFInd-minimal theme from [Evan Purkhiser][refind-minimal] and rEFInd-minimal-dark
theme from [Carlos Pinto][refind-minimal-dark].

The function icons are based on those of the rEFInd-regular theme from [Alberto Bursi][refind-regular].

[refind]: http://www.rodsbooks.com/refind/
[refind-minimal]: https://github.com/EvanPurkhiser/rEFInd-minimal
[refind-minimal-dark]: https://github.com/PillTime/rEFInd-minimal-dark
[refind-regular]: https://github.com/bobafetthotmail/refind-theme-regular

## Installation

Simply download or clone this repository and move it to the directory where rEFInd has been installed (typically `/boot/EFI/refind`) or a subdirectory therein (e.g. `themes/`).
Then all you have to do is add a line similar to one of the following to the end of your `refind.conf`.
Either use:
> include themes/refind-simple/dark/theme.conf  # loads the dark theme variant

if you want the dark theme variant, or

> include themes/refind-simple/light/theme.conf  # loads the light theme variant

if you want the light theme.
