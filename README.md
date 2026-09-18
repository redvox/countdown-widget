# Countdown Widget

This project hosts a widget that shows a countdown to a given date.

## Parameter

`date` specify the date you want to count down to, example: `2026-12-24`

`showDate` specify with boolean whenever you want to show the date you are counting down to.

## Countdown colors

In code, there can be threshols defined that changes the day text color; the optional date keeps its existing color.
The first matching threshold is used.

Examples:

- 14 days or fewer: red `#FF0000` (including today and past dates)
- 28 days or fewer: orange `#FFA500`
- 90 days or fewer: blue `#0000FF`
- 180 days or fewer: green `#008000`
- Otherwise: black `#000000`

The thresholds and colors can be adjusted in `colorThresholds` in `widget.html`.

## iframe example

```html
<iframe
  src="https://redvox.github.io/countdown-widget/widget.html?date=2026-12-24&showDate=true"
  width="100%"
  height="500"
>
</iframe>
```
