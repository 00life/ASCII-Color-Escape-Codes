## Standard escape codes are prefixed with Escape:

- Ctrl-Key: `^[`
- Octal: `\033`
- Unicode: `\u001b`
- Hexadecimal: `\x1B`
- Decimal: `27`

Followed by the command, somtimes delimited by opening square bracket ([), known as a Control Sequence Introducer (CSI), optionally followed by arguments and the command itself.

Arguments are delimeted by semi colon (;).


### Example:

- `\x1b[1;31m`  # Set style to **bold**, *red foreground*.
- `\x1b[2;37;41m`  # Set style to **dimmed white foreground** with *red background*.


## Color Codes

| Color Name | Foreground Color Code | Background Color Code |
|:---:|:---:|:---:|
| Black |	30	| 40 |
| Red	| 31	| 41 |
| Green |	32	| 42 |
| Yellow |	33 |	43 |
| Blue	| 34	| 44 |
| Magenta	| 35	| 45 |
| Cyan	| 36	| 46 |
| White	| 37 |	47 |
| Default	| 39	| 49 |

## Style Codes

| Style Name | Style Description |
|:---:|:---:|
| 0 | reset all modes (styles and colors) |
| 1 | set bold mode. |
| 2 | set dim/faint mode. |
| 3 | set italic mode. |
| 4 | set underline mode. |
| 5 | set blinking mode. |
| 7 | set inverse/reverse mode. |
| 8 | set hidden/invisible mode. |
| 9 |	set strikethrough mode. |

