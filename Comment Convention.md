
# Comment Conventions

## Overview

This document outlines the comment conventions for our project. Following these guidelines will help ensure that our code is clean, maintainable, and easy to understand.

## General Rules

- **Be Descriptive**: Comments should describe what the code is doing and why it is doing it.
- **Keep Comments Updated**: Ensure comments are updated when the code changes.
- **Use Tags**: Use specific tags like TODO, FIXME, OPTIMIZE, DEBUG, REVIEW, NOTE, CHEAT, DEPRECATED, and IMPORTANT to indicate specific actions or statuses.

## Comment Tags

### TODO
Use this tag to indicate tasks that need to be completed.
```
// TODO: Refactor this method to improve performance
```

### FIXME
Use this tag to mark code that has bugs and needs to be fixed.
```
// FIXME: This function does not handle edge cases correctly
```

### OPTIMIZE
Use this tag to indicate areas of code that need optimization to improve performance.
```
// OPTIMIZE: Improve the algorithm to reduce complexity
```

### DEBUG
Use this tag for comments that assist in debugging. These comments should be removed or disabled in the production code.
```
// DEBUG: Log output for debugging purposes
// Debug.Log("Value of x: " + x);
```

### REVIEW
Use this tag to mark code that needs to be reviewed or checked by peers.
```
// REVIEW: Check the implementation of this method
```

### NOTE
Use this tag for important notes that need attention but are not directly related to fixing bugs or optimizing code.
```
// NOTE: This method is only used for testing
```

### CHEAT
Use this tag to indicate temporary or non-standard solutions that need to be revisited and improved.
```
// CHEAT: Temporary fix for issue #123, needs a permanent solution
```

### DEPRECATED
Use this tag to mark code that is no longer in use or will be removed in the future.
```
// DEPRECATED: This method will be removed in the next release
```

### IMPORTANT
Use this tag to highlight particularly important sections of code that require special attention.
```
// IMPORTANT: This block of code handles user authentication
```
