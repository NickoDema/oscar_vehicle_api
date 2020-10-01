### OSCAR vehicle API

Репозиторий содержит API низкоуровневой системы управления, разрабатываемой в рамках проекта [OSCAR](https://gitlab.com/starline/oscar), для беспилотных транспортных средств.


#### Установка с PyPI

```
pip install --user oscar_vehicle_api
```


#### Установка из исходников

```
git clone https://gitlab.com/starline/oscar_vehicle_api.git && cd oscar_vehicle_api
pip install --user -e .
```

#### Использование

```
import oscar_vehicle_api
vehicle = oscar_vehicle_api.LexusRX450H(“/dev/ttyACM0”)       # начало работы с автомобилем
vehicle.led_blink()                                           # индикация на панели управления автомобиля
vehicle.emergency_stop()                                      # экстренное торможение автомобиля
vehicle.left_turn_signal()                                    # включить левый сигнал поворота
vehicle.get_steering_wheel_angle_and_velocity()               # получить текущее положение и скорость руля
vehicle.stop_sending_steering_wheel_torque_cmd()              # перестать отправлять сообщения управления рулем
```
