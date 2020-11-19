# Gateway Device Application (Connected Devices)

## Lab Module 12 - Semester Project Proposal

### Description

<!-- On the following page(s), be sure to address the following four topics: 
- What - The Problem
- Why - Who Cares?
- How - Expected Technical Approach
- Results - Expected Outcomes -->

### What - The Problem 

<!-- NOTE: Write one or two paragraphs to answer EACH of the following questions. -->

**What problem are you trying to solve and why does it matter?**

Nowadays, so many people how to work from home but they do not pay attention to the air quality in their room. Especially for those programmer, they always sit for hours in their own room. The air quality here is not common PM 2.5 but the CO2 level. Because according to some study, it's very common they people stay at a closed
room where the CO2 level will slowly increase as people do not ventilate often, as a result the high C02 level (usually higher than 1000) would could drowsiness therefore affect their work or study.


### Why - Who Cares? 

**Why do you care about this particular problem?**

It's a very common case that every person may meet, and usually little people realise that sometimes why they feel sleepy and tired is because of the CO2 level in their room. And such product that can detect C02 level in any closed env, show and alert info of C02 level can help improve their work or study environment.

### How - Expected Technical Approach

<!-- NOTE: Provide a high level design diagram depicting your planned technical approach. This should be a relatively
simple block diagram - you do NOT need to create a UML diagram for the proposal, although you should provide
specifics on which protocols you plan to use, where they’ll be used, and how you plan to communicate between
your constrained device, gateway device, and cloud services. You may make changes to this for the final
implementation if needed - this should serve merely as a guide.  -->

1. Connect a air quality sensor to my raspberry pi to collect current air quality sensor data in the room.
2. Use CDA to connect to this sensor so as to integrate the sensor to my IoT system.
3. Send sensor data to two places:
   1. The screen on SenseHat
   2. The cloud
   3. The GDA
4. The GDA and cloud will make some response to the CO2 level data or other air quality data.
 
### Results - Expected Outcomes 

<!-- NOTE: Write one or two paragraphs to answer the following question. -->

**If your project is successful, what outcome do you expect (e.g. what will happen if everything works)?**

If all things work well, following features will be available:

1. The screen on SenseHat could show current CO2 Level with number in PPM.
2. The GDA and cloud will send test message or E-mail to me when the CO2 level is too high.
3. The cloud could store and show history CO2 level info. 
