# PyMemory
Happy using PyMemory to read and write to computer memory.

```python
from PyMemory import PyMemory

Process = PyMemory("QQ", "QQ.exe")
print(Process.ReadProcessMemory(0x218ED5D4))
```

