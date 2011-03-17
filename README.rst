UIView+position
===============

This is UIView category that adds properties that make frame geometry-related stuff less tedious.

For example, you can write::

    someView.rx += 100;

instead of::

    someView.frame = CGRectMake(someView.frame.origin.x+100, someView.frame.origin.y,
                                someView.frame.size.width, someView.frame.size.height);

This category is based on (Apache licensed) code from http://bynomial.com/blog/?p=24.
Properties changed to even more concise (e.g. frameOrigin -> origin, frameX -> rx)
