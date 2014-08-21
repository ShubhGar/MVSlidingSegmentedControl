MVSlidingSegmentedControl
=========================
Instagram-style sliding segmented control

![MVSlidingSegmentedControl preview](https://github.com/bizz84/MVSlidingSegmentedControl/raw/master/animated.gif "MVSlidingSegmentedControl preview")

![MVSlidingSegmentedControl preview](https://github.com/bizz84/MVSlidingSegmentedControl/raw/master/screenshot.png "MVSlidingSegmentedControl preview")

Features
-------------------------------------------------------

- Conforms with UIControl's event handling interface via UIControlEventValueChanged
- Auto-layout support
- Can be configured both with Interface Builder or programmatically
- Supports 2, 3 or 4 segments

Usage
-------------------------------------------------------

A sample application demonstrating the usage MVSlidingSegmentedControl is included.

Notes
-------------------------------------------------------
MVTextInputsScroller is designed to work with UIScrollViews whose subviews are laid out using Auto-Layout. Specifically, all the subviews constraints need to be defined top to bottom so that the UIScrollView can infer its contentSize.<br/>
MVTextInputsScroller won't work if this is not the case as it uses the contentSize to determine the correct contentOffset.

Installation
-------------------------------------------------------
To include MVSlidingSegmentedControl in your own project, simply drag the MVSlidingSegmentedControl folder in XCode and you're ready to go.<br/>
The demo app included in this project uses [Masonry](https://github.com/cloudkite/Masonry) for auto-layout.

Before running the demo app, please run:
<pre>
pod install
</pre>

License
-------------------------------------------------------
Copyright (c) 2014 Andrea Bizzotto bizz84@gmail.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
