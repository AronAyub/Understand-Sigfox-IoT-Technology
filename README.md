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

# Qualifications 
- Sigfox operator in your country would be the most useful to help you acccess your project's potential using Sigfox Technology.

- ***Exploring IoT potential in an organuzation***

1. IOT PROJECTS CAN DELIVER VALUE IN THREE DIFFERENT WAYS
    - optimizing operations/cost optimization
    - generate new revenues with new products/services
    - enhance customer satisfaction by improving existing products or services
2. THE TECHNOLOGY IS NOT THE STARTING POINT
The value of the IoT is the data that can be derived from a connected device – and, most importantly, how that data can be used by the organization to drive increased profit through customer needs.

Forget about asking how you get the data.  Today, the technology exists to connect almost anything.  Whether this data comes from a standalone connected sensor or an existing product newly endowed with an embedded IoT sensor is less important – certainly at this stage.

Instead, you should be thinking about ‘what data are we missing from our decision making?’; if there were no limits on what we could know (because there aren’t) what would we like to know about our product and our customer and our market? How much better could your sales people sell if they understood more about how your customers are using your product?  What would you need to know to achieve that? How much better a product could your product developers build if they understood more about product performance post-sale?  What do you need to know to understand that? How much more value could your customers derive from your product if they had access to more information?  What do they need to know to gain that?

- Don’t start with the technology.  Start with what piece of information you (or your customers, or your stakeholders) would get value from if you had it want to know. 

3. INVITE THE RIGHT PEOPLE TO YOUR WORKSHOPS
Facilitated workshops can be a great way to explore IoT potential.  Workshops with strategic business leaders identify pain points in business – and reveal opportunities for improvement.

But, to be successful, these workshops need to have the right people in the room.

For real innovation, you don’t need a room full of techies.   If your IoT discovery workshop invite-list consists of technology, network and application managers, you need to stop and think again.  These people will be important on your IoT journey, of course – but not at this stage. The driver for any IoT project has to be business need.

These early workshops are not for getting bogged down in technical detail – they are for thinking freely and creatively about how you operate your organization, how you serve your customers, what you offer your customers and the value your customers get from those products and services.

And, for that, you need the business’s perspective. When you are creating your discovery workshop invite list, forget you are initiating a tech project.  Think: business improvement.

4. THINK ABOUT THE CUSTOMER EXPERIENCE
Organisations are increasingly choosing to compete on the customer experience (CX). To compete on this platform, as you begin to look at opportunities to improve your operations as well as your product and service offering, you will need to incorporate:

    - business process mapping
    - direct customer feedback
    - indirect customer feedback
    - financial services feedback
Understanding how your customers perceive your brand, operations, products and services will expose the improvement opportunities that matter to them.

Not all business leaders can be Steve Jobs – identifying needs in customers that customers don’t even recognise in themselves.  For those of us who aren’t like Jobs, customer feedback mechanisms are the best ways to identify areas of potential.

Incorporating this information also raises the question of what else you’d like to know about your customers that you can’t currently know – another ripe source of IoT potential.

Connected devices open up possibilities for insights that go way beyond traditional business metrics – offering insights into post-sales product performance and lifecycles that we just couldn’t have otherwise.

If you could gain those insights, how much better could your CX be then?

5. STRESS TEST YOUR IDEAS
Once you’ve collected a range of ideas from your workshops, the next step is to stress test those ideas: do they really have business value?

Again, this is a workshop where strategic business leaders will be calling the shots – not the technologists. What you want is an assessment where your own business modelling will come into play, so you can identify and evaluate the potential value proposition brought by the IoT solution – and the commercial implications of these new revenue streams.

6. GET EXPERT HELP TO DEFINE ROUGH COSTINGS
Once you have an idea of the revenue-generating potential of the various ideas your team has identified, you will need to assess this against the cost and complexity of bringing those ideas to life.

Here, you are probably going to need some expert input. The Sigfox IoT agency can talk you through the approximate costs of implementing various ideas. 

You will need to think about:

- The costs of the device, sensor, connectivity and network connectivity
- Who bears those costs?
- Can you leverage exisiting technology to get the data you need?
- How do you need to adapt your product to get the information you need?
- How complex is that product development process?
- How complex are the connectivity issues moving forward?
- What security implications are there? What are the approximate costs for managing those risks?
- These costings will be very approximate at this stage since you are a long way off scoping out a possible solution, but working with a company that has a great deal of experience in bringing IoT projects to life will give you a rough idea of the cost and complexity involved in realising each idea.

7. DECISION: WHICH IDEAS (IOT SOLUTIONS) TO PURSUE
You’ll then need to bring step five together with step six, in order to decide which ideas are worth pursuing.

Evaluate the approximations you have in terms of each idea’s complexity and cost against its potential value.  From this, you will be able to create a short list of ideas you want to take forward to the next phase.



