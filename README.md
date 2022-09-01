# A.M.-and-F.M-Transceivers
### Implementation of A.M. and F.M. Transceivers on a SDR (software defined  radio)

#### NOTE: The grc and python files are to be opened with GNU radio (software defined radio or SDR). [Download Here](https://www.gnuradio.org/)

### A.M. TRANSCEIVER

A transceiver is a combination transmitter/receiver in a single package. The main functionality of this electronic device is to transmit, as well as receive, different signals. In radio communications, the transceiver can work in half-duplex or full-duplex mode:
•	Half-duplex transceivers: It can either transmit or receive but not both at the same time. This is because both the transmitter and receiver are connected to the same antenna using an electronic switch. This mode is found in ham radios, walkie-talkies and other single-frequency
•	Full-duplex transceivers: The radio transmitter and receiver can work in parallel. Transmission and reception take place on different radio frequencies. This mode is observed in handheld and mobile two-way radios.
AM transmitter takes the audio signal as an input and delivers amplitude modulated wave to the antenna as an output to be transmitted.

![image](https://user-images.githubusercontent.com/92263062/187825730-b07ece48-985f-4b57-883f-55643d250bc2.png)

I have implemented a basic half-duplex AM transceiver in GNU radio. The flowgraphs of transmitter and receiver sections are shown in the following images.

![image](https://user-images.githubusercontent.com/92263062/187825762-c6995815-d737-409c-81d2-d05837c12a34.png)

![image](https://user-images.githubusercontent.com/92263062/187825789-6448eff9-8f1c-40ea-83dd-0591fa13a537.png)

The resulting interface after executing the above flowgraph is attached below. We can switch between transmitter and receiver modes. The amplitude of transmitted and received signal can also be adjusted. 

![image](https://user-images.githubusercontent.com/92263062/187825819-4e00ae27-7da0-48b2-b21c-4fc667518ac9.png)

![image](https://user-images.githubusercontent.com/92263062/187825847-b4a3dc34-39e5-44a5-b757-13d6a61dd77c.png)

### F.M. TRANSCEIVER

Frequency modulation (FM) is the encoding of information in a carrier wave by varying the instantaneous frequency of the wave.

![image](https://user-images.githubusercontent.com/92263062/187825978-cff0a796-f42b-4034-9cb0-031399712896.png)

I have implemented a basic full-duplex FM transceiver in GNU radio. The flowgraphs of transmitter and receiver sections are shown in the following images.

![image](https://user-images.githubusercontent.com/92263062/187826013-1e09e7fa-16af-42f4-9a51-9690c8ceb4cb.png)

![image](https://user-images.githubusercontent.com/92263062/187826026-0dfa592a-78c4-4a63-97c3-1abac0de99ac.png)

The resulting interface after executing the above flowgraph is attached below. The amplitude of transmitted and received signal can be adjusted. Squelch level can also be adjusted.

![image](https://user-images.githubusercontent.com/92263062/187826071-e8e9fa6a-71c9-42ea-8f16-eaeadf6205d2.png)
