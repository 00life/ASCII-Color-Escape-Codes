## Standard escape codes are prefixed with Escape:

- Ctrl-Key: ^[
- Octal: \033
- Unicode: \u001b
- Hexadecimal: \x1B
- Decimal: 27
- Followed by the command, somtimes delimited by opening square bracket ([), known as a Control Sequence Introducer (CSI), optionally followed by arguments and the command itself.

Arguments are delimeted by semi colon (;).

### For example:

- \x1b[1;31m  # Set style to bold, red foreground.
