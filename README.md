ERP420_Prac1
============

This is for a university practical.
Omnet++ ring- and star-topology networks simulated. 

Both networks simulate communication delays, as well as dropped/lost messages.

Delays are calculated randomly (or as random as you can get) and is set for each device before the simulation starts.

The ring topology network is simulated with 4 connected devices. 
The devices can only communicate with their neighbour, thus if device 1 wants to communicate with device 4 the message has to be forwarded from 1 to 2, 2 to 3 and finally 3 to 4. 

The star topology network is simulated with 4 devices connected via a hub.
Each device can only coumminicate with the hub. The hub checks the message, and forwards it to the intended recipient.
If a message was lost, the hub notifies all the devices, if the device sees that it's message has been lost, it resends the message.
