# RC Glider
## ℹ️ What is it?
This project aims to convert "Play Live" toy glider from Lidl into a remote controlled UAV.

## 📚 Hardware and Mechanics
### Compoment list
| Component 	| Part 	|  Additional info	|  Link |
|---	|---	|---	|---	|
| Flight Control Unit (FCU) | ESP32S3	| Powered from BEC, should take care of wing servos, maybe camera, gyro and lights | - |
| ESC with 5V 3A BEC (ECU) |  Hobbyocean 40A ESC, 5V/3A BEC |   Best to buy with motor | [ESC + Engine set](https://pl.aliexpress.com/item/1005006107745151.html)|
| Main engine |  Dr Mad Thrust 40mm 	|  Best to buy with motor	| [ESC + Engine set](https://pl.aliexpress.com/item/1005006107745151.html) |
| Wing servo #1 | TBD	| Be careful with symmetry | - |
| Wing servo #2 | TBD | Be careful with symmetry | - |
| Battery | Turnigy Graphene 1300mAh 3S 45C LiPo | - | [Battery](https://hobbyking.com/en_us/graphene-1300mah-3s-45c-w-xt60.html)	|

### Flight Control Unit [FCU]
- The unit is based on custom PCB powered from BEC via LDO.
- Controls wing steering servos and main engine with PWM signal going to the ESC.
- Includes USB port for programming with ESD protection, should also handle BEC coexistence.
- Includes SD card and camera. The minimum is to get the ability to take some photos.

### Electronic Speed Controller [ESC]
- Provides energy for the engine that generates the thrust, making our plane able to fly.
- Provides lower 5V voltage that powers the brain of the plane as well as steering servos, camera and SD card.

## 💻 Software
### PLACEHOLDER

## 💌 Special thanks
### PLACEHOLDER
