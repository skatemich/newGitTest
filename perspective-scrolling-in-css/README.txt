A Pen created at CodePen.io. You can find this one at http://codepen.io/Hornebom/pen/zGKVva.

 A 3 dimensional scrolling experience built in CSS only. The trick is to rotate a single element around its x-axis, while its parent provides the perspective environment and a special perspective-origin.

Best viewed in Chrome/Safari on your desktop. Passed my test on Android, but lacks performance. Test failed on IOS7.

//

Update (tested under OSX 10.9.5):

Chrome 42.0.2311.152  --- fine

Opera 26.0.1656.60 --- fine

Firefox 38.0.1 --- works, but animations look horrible and transformed elements flicker while scrolling

Safari 7.1.6 --- scrolling effect works, animations don't run

Vivaldi --- works fine only after window resize

//

Have an idea how to improve this pen or found a bug? Let me know about it in the comments