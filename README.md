# 5G-Device-Identifier

Identifiers are used who uniquely recognize the entity. Send all the connection characteristics are tide to this identity. For example the device identity can be used it will be fine if it is a blacklisted device or not. Subscription identity is used to define if the subscription allows a certain 5G service or not. There are two different identities in 5G system as follows

i) Device Identity

ii) Subscription Identity


### Device Identity

In a 5G system, the device identifier is called PEI or Permanent Equipment Identifier. Every device in 5G network has unique PEI. This is stored in the device whether it is 5G smartphone or self driving car it contains or stores the PEI. It can take two possible formats inside the system

i) IMEI: 

It is a 15 digit number with three different columns. TAC type allocation code is issued by the central body across the globe in global contest and then using this 8 digits, manufacturer can then assign a 6 digit serial number corresponding phones they manufacturers. Then we have one digit code, but tech desert which is used to see if when the people reports the lost device.

ii) IMEISV: 

IMSI is a hardware number if we need a software information then we use the same digit I am EISV this is along with PSN serial number is also have SVN or software version number software version number is used to identify which is what is the software weather in the current device 

**Note:** PEI is transmitted only after the encryption parameter are set, so it's always transmitted securely. So nobody can eavesdrop on the network and identify this network. There is one exception, when a device is trying to make an emergency call then it may not have time to authenticate itself and it may not have necessary encryption parameters in place. So under this scenario PEI is transmitted without interruption and this is the exceptional case.
