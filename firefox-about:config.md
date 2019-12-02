
This snippet is originated from `loopy750`'s comment on Reddit: [Fix for choppy scrolling?](
  https://www.reddit.com/r/firefox/comments/7d8xxe/fix_for_choppy_scrolling/)

```
general.smoothScroll;true
general.smoothScroll.currentVelocityWeighting;0.15
general.smoothScroll.mouseWheel.durationMaxMS;250
general.smoothScroll.mouseWheel.durationMinMS;250
general.smoothScroll.msdPhysics.enabled;true
general.smoothScroll.msdPhysics.motionBeginSpringConstant;400
general.smoothScroll.msdPhysics.regularSpringConstant;600
general.smoothScroll.msdPhysics.slowdownMinDeltaMS;120
general.smoothScroll.other.durationMaxMS;500
general.smoothScroll.pages.durationMaxMS;350
general.smoothScroll.stopDecelerationWeighting;0.8
mousewheel.min_line_scroll_amount;22
```
