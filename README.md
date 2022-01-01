# PyRingD

This is a package which can be used to make some kind of alarm clock.

```python
    pip install PyRingD
```

This version of the package is dependent on the following packages-

* datetime
* pyttsx3(speak)
* winsound/Playsound


# How PyRingD works-

    If you give the input as time then it will play the alarm on the time given as input.
    It has a function named 'alarm' which is used to play the alarm


## Example Code-

```python
from PyRingD import PyRingD

print("Tell the time at which you want to set alarm.")
tt = input()#give input as "10:34 AM" / "4:34 PM"
tt = tt.upper
PyRingD.alarm(tt)
```

### Deo Krishna

For any error occuring in our module, contact us at -
deo2k09@gmail.com
