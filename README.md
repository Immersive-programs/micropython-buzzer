# micropython-buzzer

# English:

<details>
<summary> <b><i></i></b> (<i>click to expand</i>)</summary>

## Small Library to Manage Buzzer

### Examples of using:
#### Playback:
```Python
from machine import Pin
from buzzer import Buzzer

buzzer = Buzzer(Pin(0))
#buzzer.beep([[frequency, duration]])
buzzer.beep([[900,500]))
```

#### Reproduction of the sequence:
```Python
#At a frequency of 20 zuroma turns off
buzzer.Beep([[500,100],[20.50],[1100,100],[20.50],[500,100])))
```

#### if necessary, Zumer can be turned off:
```Python
buzzer.isenabled = False
```
</details>

# Русский:

<details>
<summary> <b></b> (<i>нажмите, чтобы развернуть</i>)</summary>


## Небольшая библиотека для управления зуммером

### Примеры использования:
#### Воспроизведение:
```Python
from machine import Pin
from buzzer import Buzzer

buzzer = Buzzer(Pin(0))
#buzzer.beep([[частота, Длительность]])
buzzer.beep([[900,500]])
```

#### Воспроизведение последовательности:
```Python
#При частоте 20 зуммер отключается
buzzer.beep([[500,100],[20,50],[1100,100],[20,50],[500,100]])
```

#### При необходимости зуммер можно отключить:
```Python
buzzer.isenabled = False
```
</details>
