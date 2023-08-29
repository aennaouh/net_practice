# net_practice
https://www.youtube.com/watch?v=BWZ-MHIhqjM&list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE&pp=iAQB
https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi&pp=iAQB
<img width="642" alt="Screen Shot 2023-08-29 at 2 35 30 PM (1)" src="https://github.com/aennaouh/net_practice/assets/116731966/d857b19f-8554-4eb6-a20c-90d4e9517f68">

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
    <img width="1267" alt="Screen Shot 2023-08-16 at 11 37 08 AM" src="https://github.com/aennaouh/net_practice/assets/116731966/5c939f66-a841-45dd-87a2-3229dc802c89">
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
    
    <img width="217" alt="Screen Shot 2023-08-16 at 3 27 46 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/5ee85c5f-a134-4b16-94c9-140b4fffe884">

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
        

<img width="742" alt="Screen Shot 2023-08-17 at 6 27 38 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/455d0617-66ac-4e19-b659-b57d1888d7a4">
<img width="719" alt="Screen Shot 2023-08-17 at 8 18 04 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/d7ea87b9-fc65-4b95-86ec-a491f0ee2fbd">
<img width="861" alt="Screen Shot 2023-08-17 at 8 25 23 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/5d4d56b3-fb6e-45f3-b89c-4d84d7628b83">
<img width="799" alt="Screen Shot 2023-08-17 at 8 30 12 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/a22a9aea-5555-47ec-bd73-6b655d7a6371">

****What is Subnetting?****

<img width="976" alt="Screen Shot 2023-08-17 at 8 51 47 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/a6a2d982-72a3-427b-b2df-55ec66054873">

240

****Drawing the Cheat Sheet -****

<img width="481" alt="Screen Shot 2023-08-18 at 6 05 55 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/e03492a1-58e5-46ac-bc82-490d9621ef26">
<img width="871" alt="Screen Shot 2023-08-17 at 9 59 46 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/4249c937-8509-4fb0-a9e9-7ab8b6a7b255">

****Practice Examples****

<img width="761" alt="Screen Shot 2023-08-17 at 10 44 55 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/98424acf-da00-4740-8ce2-3ecbfe983b31">
<img width="774" alt="Screen Shot 2023-08-17 at 11 24 55 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/d6179e45-259d-4f80-b11a-af1ed5f8241b">


****OSI Model: A Practical Perspective :****

- ***network***
- ***data link***
- ***physical***

<img width="1001" alt="Screen Shot 2023-08-18 at 3 28 33 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/dd063fa4-3929-40b9-a5f7-016e74b5e986">


****OSI Model: A Practical Perspective :****

- **transport**

<img width="915" alt="Screen Shot 2023-08-18 at 3 50 36 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/fc7d7f0d-b1b0-4601-821f-5eaccd6de9bb">


**that layer header will indicate which particular programe should be receiving that data and that’s what layer four is going to use to make sure the right program the right once and zeros**

***SENDING - ENCAPSULATION***

each layer of this lesson is to understanding that each layer of the OSI model has a specific that contributes the overall goal of allowing to hosts to share data with one anther

<img width="899" alt="Screen Shot 2023-08-18 at 4 08 36 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/df40b695-2b91-4452-9476-4f40a65238db">


**IP Addresses PUBLIC & PRIVTE**

<img width="892" alt="Screen Shot 2023-08-19 at 6 51 10 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/f88375d3-4833-4cb5-abdc-154756d5cad4">

routing table

<img width="1040" alt="Screen Shot 2023-08-25 at 6 34 36 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/88f5ab62-5669-4a10-a3c7-d91354c86468">

```c
her how u can get the CIDR subnet and also the groupe of ech size
```
<img width="584" alt="Screen Shot 2023-08-27 at 5 03 34 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/1ea2742b-4c71-4f06-b9e4-129bb330cb71">

<img width="569" alt="Screen Shot 2023-08-27 at 4 57 27 PM" src="https://github.com/aennaouh/net_practice/assets/116731966/1d79712e-1021-4332-9a0e-84cada4460f6">

