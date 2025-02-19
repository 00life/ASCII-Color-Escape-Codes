## Standard escape codes are prefixed with Escape:

- Ctrl-Key: `^[`
- Octal: `\033`
- Unicode: `\u001b`
- Hexadecimal: `\x1B`
- Decimal: `27`

Followed by the command, somtimes delimited by opening square bracket ([), known as a Control Sequence Introducer (CSI), optionally followed by arguments and the command itself.

Arguments are delimeted by semi colon (;).


### For example:

- `\x1b[1;31m`  # Set style to **bold**, *red foreground*.
- `\x1b[2;37;41m`  # Set style to **dimmed white foreground** with *red background*.


## Color codes

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
