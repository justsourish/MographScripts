```
s = effect("Slider Control")("Slider").value.toFixed(1);
(s.length < 4 ? "0" : "") + s
```

Change the value inside `toFixed(1)` to `toFixed(0)` to convert this number to a integer.
