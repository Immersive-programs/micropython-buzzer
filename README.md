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
buzzer.beep([[500,100],[20.50],[1100,100],[20.50],[500,100])))
```

#### if necessary, Zumer can be turned off:
```Python
buzzer.isenabled = False
```

### Notes:
  - development was carried out in the Thonny IDE V4.0.2;
  - performance was checked for: "Micropython v1.19.1 on 2022-06-18";
  - used controller: "Raspberry Pi Pico";

#### Author: Denis
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
#buzzer.beep([[Частота, Длительность]])
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

### Примечания:
 - Разработка велась в Thonny IDE V4.0.2;
 - Работоспособность проверена на: "MicroPython v1.19.1 on 2022-06-18";
 - Использованный контроллер: "Raspberry Pi Pico";

#### Автор кода: Денис
</details>
