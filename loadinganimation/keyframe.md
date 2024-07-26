## keyframe
CSS keyframes are used to create animations that change an element's style over time. 
By defining keyframes, you can specify the starting and ending points of an animation as well as intermediate points along the way.

## basic syntax
```
@keyframes animation-name {
  0% { /* starting styles */ }
  50% { /* middle styles */ }
  100% { /* ending styles */ }
}
```
## Tips for Using Keyframes in CSS
1.Easing Functions: Use easing functions (like ease, linear, ease-in-out) to make animations more natural.

2. Performance: Avoid animating properties that trigger layout changes, such as width, height, left, and top. 
Prefer transform and opacity for smoother animations.

3.Prefixes: Use vendor prefixes for better cross-browser compatibility (-webkit-, -moz-, etc.).

4.Chaining Animations: Combine multiple animations for more complex effects by using animation properties with multiple keyframes.
