# StrideBot: Advanced Biped Robot with Human Gait Mimicking Algorithm

Welcome to StrideBot, a cutting-edge biped robot that harnesses a sophisticated human gait algorithm through a 6-stage process for locomotion.

StrideBot leverages "Adafruit_PWMServoDriver.h" and "Wire.h" libraries for seamless servo motor control via a servo motor driver, facilitated by I2C communication.

With precise calibration in mind, StrideBot dynamically defines the minimum and maximum tick values to guide its servo motors and perform an incredible range of movements from 0 to 180 degrees. By adeptly mapping angles from 0 to 180 to their corresponding tick values, this function commands the servo motors with absolute accuracy.


The ankle servo motors for both legs transition from 90 degrees to 45 degrees for the left leg and 70 degrees for the right leg. Each step is punctuated with a 200-millisecond delay. This simulates liftoff from the ground. The knee servo motors then extend the legs forward, progressing from 90 degrees to 150 degrees for the left leg and 120 degrees for the right leg. Then, StrideBot retraces its steps, gently lowering the ankle servo motors back to their initial 90-degree position. The knee servo motors gracefully return to their default position of 90 degrees, preparing for the next stride. The sequence is repeated to ensure fluid motion.
![image](https://github.com/Riptiva-Roy/StrideBot/assets/141496773/f3d10458-7cb4-480f-80bb-cd0cdf4b643e)


<img width="900" alt="Screenshot 2023-08-05 at 18 03 59" src="https://github.com/Riptiva-Roy/StrideBot/assets/141496773/2df4ae13-ab5b-4138-a32c-ec99eb80e8c0">

