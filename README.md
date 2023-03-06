# Understand Sigfox IoT Technology
 ## Introduction 
- Sigfox is an inexpensive, reliable, low-power solution to connect sensors and devices. 
- With our dedicated radio-based network, we are committed to giving a voice to the physical world, and make the Internet of Things truly happen. 

### The Sigfox protocol focuses on: 

- **Autonomy.** Extremely low energy consumption, allowing years of battery life.
- **Simplicity.** No configuration, connection request or signaling. Your device is up and running within minutes!
- **Cost efficiency.**  From the hardware used in the devices to our network, we optimize every step to be as cost-effective as possible.
- **Small messages.** No large assets or media allowed on the network, only small notifications: up to 12 bytes.
- **Complementarity.** Thanks to its low cost and ease of configuration, you can also use Sigfox as a secondary solution to any other type of network, e.g GSM

## Accessing the Sigfox service
Getting your device to communicate with Sigfox is very easy: everything you need is included! Our subscription service is based on the number of devices you want to connect to the network.
- The Sigfox network is global, it is managed by local Sigfox Operators (SO), you need to do a quick prototype, contact your SO, as of 2023, Kenya SO is [Liquid Intelligent Technologies](https://www.liquid.tech/)

## Network Overview
- Sigfox's network works with lightweight messages (12 bytes, excluding payload headers).

The life cycle of a Sigfox message is always the same:

            - A device wakes up and emits a message using its radio antenna,
            - Multiple Sigfox base stations in the area receive the message,
            - Base stations send the message to the Sigfox Cloud,
            - The Sigfox Cloud sends the message to a customer's backend platform.
- It's that simple!
<img width="949" alt="communication" src="https://user-images.githubusercontent.com/55284959/223074469-ed069526-ee62-4134-95d6-228294f7c7da.png">

### What is a Sigfox "base station"? 
Base stations are local Sigfox antennas, which receive messages from emitting devices and forward them to the Sigfox Cloud. They are deployed in the field by our local Sigfox Operators. 

#### They are composed of three major elements:

- **An antenna,** to receive messages over the air, usually deployed on high points or towers,
- **A LNA or LNAC** (low-noise amplifier), to amplify the signal and filter noise,
- **An access point,** which understands the Sigfox messages and sends them to the Sigfox Cloud.
Once connected, they become part of our public network. They then start listening for all Sigfox messages sent by devices in the vicinity. 
![sigfox-iot-1030x687-1030x687](https://user-images.githubusercontent.com/55284959/223075829-20cd2454-e24b-4e80-a745-eae7b5467ae1.jpg)
### Coverage
- Sigfox is a public network, which means that devices rely on the infrastructure deployed through cities and countries by the local Sigfox Operator to communicate. Our full public coverage map is available here:[Coverage map](https://www.sigfox.com/en/coverage.) 
## Building your product.
- We rely on an ecosystem as below:
![jhbrwoo0-build_ecosystem-cropped](https://user-images.githubusercontent.com/55284959/223080932-57c24485-6d5b-477b-ad94-5e204764dbf5.jpg)