# net_practice
https://www.notion.so/Net_practice-825ad116f408448ba3539ddfe86a5778?pvs=4#fdbb276ec46740ab824ac04d8f17b135

every device in the network has a unique ip adderss ech address can access different ports for exchanging data with other ip addresses 

- you can think of adresses as phone numbers and
- ports as the calls between them

withe the TCP/IP protocol , each port is a private channel for two-way communication, and hardware and software are responsible for routing data in and out 

the connections are also like phone calls where someone has to initiate the connection by dialing a number at one end , someone has to be listening and pick up the line when a call comes in.

- the server is  the device thats listening for calls and
- the client is the dials the server

port numbers are like a particular phone extension once the call is answered 

- A client needs to know the IP address of whatever server wants to connect to , and also needs to know the port number through which to send or receive data , after the call established
- the server only need to listen to connections, then chose to accept or reject
- TCP/IP also perform error checking to guarantee that there will be no error in the transmission
    
    ![Screen Shot 2023-08-16 at 11.37.08 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bb6df4c4-784a-4f64-b57d-7561ad2d5dca/Screen_Shot_2023-08-16_at_11.37.08_AM.png)
    
    **Subnet Mask (often just referred to as the 'Mask')**:
    
    A subnet mask is used to divide an IP address into two parts: the network address and the host address. It's like determining which part of your home address refers to your city and which part refers to your specific street.
    
    **P Address**:
    
    An IP (Internet Protocol) address is a unique string of numbers separated by periods that identifies each computer or device connected to the Internet or a local network. In your example, "104.97.23.12" is an IP address for "Interface A1."
    
    Think of it as your home address: Just like how the post office needs your home address to deliver mail, computers need an IP address to communicate with one another.
    
    the first communication between internet was in 1969 they called this arpanet
    
    the tale 2 network m0e use :
    
    TCP/IP its the rule and guidelines standards on how computers can communicate how we design those systems and there’s a lot goes into that to make think simple we divid all those functions into layers 
    
    1- Application : for example wen i open up my web browser and i go to netfilx  what protocol i m going to use do we all agree to use the same protocol 
    
    2-transport : tsp , udp , port numbers
    
    3-network: all the ip adresses and routers 
    
    4- physical : that’s going to involve the ethernet cables 
    
    N.B
    
    this is the traditional view of the tcp model the layers we see here 
    
    ![Screen Shot 2023-08-16 at 3.27.46 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/186c1a87-7d53-4264-a237-08e95508b94c/Screen_Shot_2023-08-16_at_3.27.46_PM.png)
    
    - 0 : network id
    - 128: brodcast ip
    - IP adresses are 32 bits
        - Bit = 1 or 0
        - each octets can be 0 - 255
        - Represented as 4 Octets :
        
        1000 1000 . 0001 0110 . 0001 0001 . 0110 0010
        
            136        .       22          .          17     .           98
        
          [0 - 255].        [0 - 255].       [0 - 255].        [0 - 255]
        
        ***loopback ip***
        
        The IP address **1**  is called a loopback address. Packets sent to this address never reach the network but are looped through the network interface card only. This can be used for diagnostic purposes to verify that the internal path through the TCP/IP protocols is working.
        

![Screen Shot 2023-08-17 at 6.27.38 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1a68b924-5ba6-4b08-b1cb-8c5e8cfe0e3f/Screen_Shot_2023-08-17_at_6.27.38_PM.png)

![Screen Shot 2023-08-17 at 8.18.04 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/26fc4e2c-da9b-426e-bf0e-a0dde8bf98b1/Screen_Shot_2023-08-17_at_8.18.04_PM.png)

![Screen Shot 2023-08-17 at 8.25.23 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/eb4ed1d4-984d-4f66-a30d-742ee1cc9c96/Screen_Shot_2023-08-17_at_8.25.23_PM.png)

![Screen Shot 2023-08-17 at 8.30.12 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e161ebb4-d13a-4934-a331-faf03b3b9691/Screen_Shot_2023-08-17_at_8.30.12_PM.png)

****What is Subnetting?****

![Screen Shot 2023-08-17 at 8.51.47 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/40aa713c-9044-4eac-be98-516adaa94c3f/Screen_Shot_2023-08-17_at_8.51.47_PM.png)

240

****Drawing the Cheat Sheet -****

![Screen Shot 2023-08-18 at 6.05.55 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f86548c-011c-4abe-9139-9e5b98f12295/Screen_Shot_2023-08-18_at_6.05.55_PM.png)

![Screen Shot 2023-08-17 at 9.59.46 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1b72b9eb-5ea9-41ff-abed-feb5e6c7f0d4/Screen_Shot_2023-08-17_at_9.59.46_PM.png)

****Practice Examples****

![Screen Shot 2023-08-17 at 10.44.55 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cb7f7f3c-4501-4db2-a8e6-9cb73201f79f/Screen_Shot_2023-08-17_at_10.44.55_PM.png)

![Screen Shot 2023-08-17 at 11.24.55 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1e71242c-9c56-4e15-9ef6-e0b1f859c9ea/Screen_Shot_2023-08-17_at_11.24.55_PM.png)

****OSI Model: A Practical Perspective :****

- ***network***
- ***data link***
- ***physical***

![Screen Shot 2023-08-18 at 3.28.33 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/250fb46d-895b-4b6f-9753-98a503601120/Screen_Shot_2023-08-18_at_3.28.33_PM.png)

****OSI Model: A Practical Perspective :****

- **transport**

![Screen Shot 2023-08-18 at 3.50.36 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e0890d64-93a5-4d38-b426-aed61a704240/Screen_Shot_2023-08-18_at_3.50.36_PM.png)

**that layer header will indicate which particular programe should be receiving that data and that’s what layer four is going to use to make sure the right program the right once and zeros**

***SENDING - ENCAPSULATION***

each layer of this lesson is to understanding that each layer of the OSI model has a specific that contributes the overall goal of allowing to hosts to share data with one anther

![Screen Shot 2023-08-18 at 4.08.36 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/35362c4b-a444-4645-a6f9-1438d8f98379/Screen_Shot_2023-08-18_at_4.08.36_PM.png)

**IP Addresses PUBLIC & PRIVTE**

![Screen Shot 2023-08-19 at 6.51.10 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7a151a7e-ffff-478f-a67f-aa2ded0f793c/Screen_Shot_2023-08-19_at_6.51.10_PM.png)

routing table

![Screen Shot 2023-08-25 at 6.34.36 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c137d4b3-d87e-4b13-aed3-a0a8ec4d4643/Screen_Shot_2023-08-25_at_6.34.36_PM.png)

```c
her how u can get the CIDR subnet and also the groupe of ech size
```

![Screen Shot 2023-08-27 at 5.03.34 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/395c4b07-c6e8-47d8-85b5-1e57a1fafe76/Screen_Shot_2023-08-27_at_5.03.34_PM.png)

![Screen Shot 2023-08-27 at 4.57.27 PM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f9060c93-376c-4a26-a7af-2ca746f78dfc/Screen_Shot_2023-08-27_at_4.57.27_PM.png)
