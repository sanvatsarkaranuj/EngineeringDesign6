# Lab 5:Paho-MQTT
---
**Description:** This lab utilizes Paho-MQTT, which is a type of protocol that allows publishing/subscribing between modules

**Prelab Tasks:** Before starting this lab, I had to install paho-mqtt and update the respository using `git pull`. These steps are shown below:
1. Paho Installation
2. git pull

pubcpu and subcpu
---
These functions utilize Paho MQTT in order to send / receive messages. `pubcpu` publishes, or sends, information regarding the CPU to the subscriber. `subcpu` is the subscriber, and receives this information. The functions were run in different terminals simultaneously, so the timestamped information sent by the publisher immediately showed up in the subscriber terminal.
1. Publisher
![Image](https://github.com/user-attachments/assets/8124338e-b290-4795-87ea-c411a758ff9f)

2. Subscriber
![Image](https://github.com/user-attachments/assets/93f9fbcf-b48b-4662-b327-99cae7107b36)
