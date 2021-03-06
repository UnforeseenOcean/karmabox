# karmabox
Re-creation of Mark Rober's bait package

## Introduction
Let me shatter your dreams to begin with; Unfortunately, I'm not a NASA scientist nor a professional thing-maker, former or present. So, this project cannot recreate 100% of his work.

However, I can at least try. So, here it is. I'm trying my best to recreate the ever-famous bait package that celebrates the thief's first foray into the world of thievery with butt-ton of glitters and a healthy dose of fart spray.

My version will substitute some or many parts of the package with cheaper, easier and more accessible parts and things that are much easier to tweak.

## Concept
This device will be a lot more modular (hopefully) than Mark & Co.'s design, which is designed precisely to fit inside an Apple product box.

### How it works
1. Surprise Deployment Mechanism:tm: sits dormant while thief steals the bait package
2. The Surprise Deployment Mechanism:tm: gets ready when certain criteria are met
3. The thief opens the package
4. Surprise Deployment Mechanism:tm: deploys surprise in a timely manner or with a delay
5. Optionally the Surprise Deployment Mechanism:tm: records its position and audio/video data
6. The thief either destroys or abandons the Surprise Deployment Mechanism:tm:
7. Optionally the deployer recovers the equipment

## List of desired technologies
- AVR/Arduino
- Gyroscope/Accelerometer sensor
- Brushed or brushless DC motor
- N-channel MOSFET
- Lithium Ion/Polymer battery 
- GPS
- Tons of blinkenlights
- (If using BLDC motor) Electronic Speed Controller (PicoESC etc.)
- Power saving mode
- LED 7-segment display
- Frequency-matched oscillator and accompanying control circuitry (i.e. personal alarm, car siren, etc.)
- Piezoelectric sensor and/or tilt sensor
- Bluetooth Low Energy (optional: Either detect loss of connection to the main base or use it to trigger camera)
- ESP32/ESP8266 (optional: Use instead of the Arduino brain)
- Passive Infrared sensors or microwave movement sensors (to detect if someone is approaching the package or the place where the package is stored at)
- Plenty of GPIO ports to expand the device if required
