# supaspin

***2 or 3 phases synthesised sinewave generator suitable for driving turntable synchronous or BLDC motors, tachometer, OLED or BT/app display.***

![20210212_180454](https://user-images.githubusercontent.com/6553778/150026303-0230ef0f-b120-468e-9ba8-85c3d9d89403.png)

![20210216_172346](https://user-images.githubusercontent.com/6553778/150026721-0050b6f9-6d96-4e7f-ba26-7d41b9e81bbc.png)

This project consists of a PCB and Arduino firmware. The PCB mounts directly on the Arduino Uno, with one required for 2 phases, and 2 for 3 phases.

The sinewave are generated using 31.4kHz PWM + 2-stage low-pass filter, with a nominal 1.2v peak-peak output, and will require amplification to the voltage required by the motor.

The tachometer requires any sensor that generates 5v pulses.

**Features**
* 2 (0° and 90 °) or 3 (0 °, 120 ° and 240 °) phases of sinewave
* electronic speed switching for 33 or 45rpm
* tuneable frequency and relative phase, separate settings for each speed, stored in non-volatile memory
* selectable soft start, sinewaves ramp up over 2s
* selectable reduced amplitude, seperate settings for each speed, after selectable delay
* tachometer has selectable pulses-per-rev and averaging
* button interface for start/stop, 33/45 rpm, frequency and phase adjustments, plus OLED display or Bluetooth + RemoteXY App options

![OLEDa](https://user-images.githubusercontent.com/6553778/150026793-8820291e-2e61-45be-80d3-1654c817a8cc.png)

![ref_3phase](https://user-images.githubusercontent.com/6553778/150026933-96545139-2a2d-4c5d-831c-8ae76d48d536.png)

![ref_ampred_ss](https://user-images.githubusercontent.com/6553778/150027020-66dccd9d-eace-461b-9616-b0d2c2daad9f.png)
