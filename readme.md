### Json Parser Project
---
이것이 마크다운입니다.
# 큰 제목
## 중간 제목
### 작은 제목
![image](https://github.com/user-attachments/assets/eedf9bd9-a919-4c77-a565-1efab229c061)
```python

from random import randrange
from abc import ABC, abstractmethod

class IGame(ABC):
    def __init__(self):
        pass
    def quiz(self):
        pass
    def start_play(self):
        pass
    def next_player(self):
        pass
    @abstractmethod
    def is_playable(self):
        pass

    @abstractmethod
    def add(self, player_name):
        pass

    @abstractmethod
    def rolling(self):
        pass
    @abstractmethod
    def was_correctly_answered(self):
        pass
    @abstractmethod
    def wrong_answer(self):
        pass
```
|   |   |   |
|---|---|---|
|A|B|C|
|1|2|3|
|4|5|6|


