# hexcon
Convert hex file from lospec to kitty themes

<img src="https://github.com/AmosNimos/hexcon/blob/main/Theme_neofetch.png" alt="preview">

## Usage:
~~~
hexcon -f template.hex -d >> ~/.config/kitty/kitty.conf
~~~
This will print the template.hex into the kitty format and append it at the end of the "~/.config/kitty/kitty.conf"

~~~
hexcon -f template.hex -d -o
~~~
Same as above

~~~
hexcon -h
~~~
For more info use the "-h" flag to print the help.

## What are Hexadecimal color?
RGB colors in hexadecimal notation are represented by two-digit numbers ranging from 00 to FF for each of the primary colors: red, green, and blue. Each pair of digits indicates the intensity of a color component. For instance, #FF0000 represents maximum red intensity, no green, and no blue, resulting in pure red.

You can get more .hex files for free at [lospec.com](https://lospec.com/palette-list/)

