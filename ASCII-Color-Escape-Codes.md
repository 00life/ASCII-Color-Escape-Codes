## Standard escape codes are prefixed with Escape:

|:--:|
|Ctrl-Key|
|`^[`|
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

| Color Name | Foreground Color Code | Background Color Code |---| Style Code | Style Description |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Black |	30	| 40 |---| 0 | reset all modes (styles and colors) |
| Red	| 31	| 41 |---|  1 | set bold mode. |
| Green |	32	| 42 |---| 2 | set dim/faint mode. |
| Yellow |	33 |	43 |---| 3 | set italic mode. |
| Blue	| 34	| 44 |---| 4 | set underline mode. |
| Magenta	| 35	| 45 |---| 5 | set blinking mode. |
| Cyan	| 36	| 46 |---| 7 | set inverse/reverse mode. |
| White	| 37 |	47 |---| 8 | set hidden/invisible mode. |
| Default	| 39	| 49 |---| 9 |	set strikethrough mode. |
| Bright Black | 90 |	100 |---|---|---|
| Bright Red | 91	| 101 |---|---|---|
| Bright Green |92 | 102 |---|---|---|
| Bright Yellow |	93 | 103 |---|---|---|
| Bright Blue | 94 | 104 |---|---|---|
| Bright Magenta | 95 | 105 |---|---|---|
| Bright Cyan |	96 | 106 |---|---|---|
| Bright White | 97 |	107 |---|---|---|


