---
title: Truncate String
description: Truncates a string to a specified length and adds an ellipsis.
author: axorax
tags: python,string,truncate,utility
---

```py
def truncate_string(s, length):
    return s[:length] + '...' if len(s) > length else s

# Usage:
print(truncate_string('This is a long string', 10))  # Output: 'This is a ...'
```
