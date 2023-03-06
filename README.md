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
- The Sigfox network is global, it is managed by local Sigfox Operators (SO), you need to do a quick prototype, contact your SO, as of 2023, Kenya SO is Liquid 

## Network Overview
- Sigfox's network works with lightweight messages (12 bytes, excluding payload headers).

The life cycle of a Sigfox message is always the same:

            - A device wakes up and emits a message using its radio antenna,
            - Multiple Sigfox base stations in the area receive the message,
            - Base stations send the message to the Sigfox Cloud,
            - The Sigfox Cloud sends the message to a customer's backend platform.
- It's that simple!
<img width="730" alt="communication" src="https://user-images.githubusercontent.com/55284959/223074176-98c02908-6994-4b40-b5a4-0afd92c1d8d3.png">
