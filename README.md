# Objective-C Memory Management Issues

This repository demonstrates two common but easily overlooked issues in Objective-C memory management:

1. **Memory Leaks:**  The `bug.m` file showcases a potential memory leak caused by improper handling of string object lifecycle.
2. **Dangling Pointers:** The `bug.m` file also shows how improper use of `performSelector:withObject:afterDelay:` can lead to a dangling pointer and potential crashes.