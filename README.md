# Objective-C ARC Memory Management Bug
This repository demonstrates a subtle bug related to memory management in Objective-C when using Automatic Reference Counting (ARC).  Improper implementation of custom retain, release, and dealloc methods can lead to unexpected crashes or memory leaks. The example shows a class with incorrect implementations, causing memory issues. The solution provides corrected methods to ensure proper memory management with ARC.

## Bug Description
The bug lies in the implementation of the `retain`, `release`, and `dealloc` methods within the `MyCustomObject` class. These methods are incorrectly implemented and can lead to crashes or memory leaks. The solution demonstrates the correct implementation.