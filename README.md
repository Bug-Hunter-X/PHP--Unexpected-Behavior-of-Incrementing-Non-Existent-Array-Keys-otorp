# PHP Array Key Increment Bug
This repository demonstrates a common PHP bug involving the increment of array keys that may not yet exist.  Attempting to directly increment such keys will result in an `Undefined index` notice, potentially leading to unexpected program behavior.

The `bug.php` file illustrates the problematic code. The `bugSolution.php` file provides a corrected version with an added check for key existence.

This is a simple, yet frequently encountered issue, especially for developers new to PHP's array handling nuances.  Understanding this behavior is key for writing more robust and reliable PHP applications.