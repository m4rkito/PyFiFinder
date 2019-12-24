# PyFinder

<p>PyFinder is a basic tool to search for archives passing their formats</p>

## How to use?

create PyFinder object by passing path to directorie and passing one list that containg all formats to search

```python
from pyfinder import pyfinder

finder = PyFinder('path/to/search', ['mp3', 'mp4', 'mkv'])
print(finder.data)
```

Author: M4rk
License: MIT
