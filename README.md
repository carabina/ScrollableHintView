# ScrollableHintView
Easy to use.
Long press on UIView to show hint with scrolling. Double tapp on hint view to remove.

<img src="https://github.com/DhruvinThumar/ScrollableHintView/blob/master/ScrollHint.gif" width="300" height="600"/>

# Requires Xcode 8 and Swift 3.
Just add 'ScrollableHintView.swift' file to your Xcode project.

# Usage

Initialize 'ScrollableHintView' in viewDidAppear.

let stepperView = ScrollableHintView.init(viewForLabelToShow: steperView, withWidth: 150, setDownToView:false)

stepperView.hintText = "This is a Hint View, easy to use."

self.view.addSubview(stepperView)


# License
Apache License 2.0

