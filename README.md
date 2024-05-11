# RC Glider
## ℹ️ What is it?
This project aims to convert "Play Live" toy glider from Lidl into remote controlled UAV.

## 📚 Design [DRAFT]

### Part list
| Component 	| Part 	|  Additional info	|  Link |
|---	|---	|---	|---	|
| Flight Control Unit (FCU) | ESP32S3	| Powered from BEC, should take care of wing servos, maybe camera, gyro and lights | - |
| ESC with 5V 3A BEC (ECU) |  Hobbyocean 40A ESC, 5V/3A BEC |   Best to buy with motor | [ESC + Engine set](https://pl.aliexpress.com/item/1005006107745151.html)|
| Main engine |  Dr Mad Thrust 40mm 	|  Best to buy with motor	| [ESC + Engine set](https://pl.aliexpress.com/item/1005006107745151.html) |
| Wing servo #1 | TBD	|  	|  	|
| Wing servo #2 | TBD |  	|  	|
| Battery | Turnigy Graphene 1300mAh 3S 45C LiPo |  	| [Battery](https://hobbyking.com/en_us/graphene-1300mah-3s-45c-w-xt60.html)	|

### Flight Control Unit
- Based on custom PCB powered from BEC via LDO.
- Controls wing steering servos and main engine with PWM signal going to the ESC.
- Includes USB port for programming with ESD protection, should also handle BEC coexistence.
- Includes SD card and camera. The minimum is to get the ability to take some photos.
