# ISO-OSI Model

## Computer Networks

Two or more computers interconnected to each other via wired or wireless media forms a computer network.

### Why computers form a network

Computers form a network so that they can share information and data ie they can communicate with each other.

Interconnection between computers is not the only thing required for communication.

If one system is using Windows and other systems Using Linux, systems can not understand data send to each other.

### Protocols

To computers in the network to communicate with each other, there should be some set rules followed by all computers while transferring data, these rules are called **protocols**

### OSI model

OSI stands for Open System Interconnection, a seven-layer model introduced by ISO to enable communication between computers.

Each layer provides some services and a bunch of protocols.

### OSI model layers

1. Application Layer

    * This layer provides protocols such as HTTP/S, FTP, SMTP.

    * These protocols are used by computer applications that use and provide internet services, for example, Chrom, Firefox, etc.

    * This layer provides services for file transfer, mail transfer, and internet surfing

2. Session Layer

    * This layer receives information from the application layer and performs authorization and authentication.

    * It helps in maintaining sessions for each client which gets terminated after a specified duration or when the client closes the browser.

3. Presentation Layer

    * This layer converts the data into machine representable form.

    * encryption, decryption, and compression are performed at this layer.

4. Transport Layer

    * This layer performs segmentation, flow control, and error control.

    * This layer provides two protocols

        1. TCP stands for transmission control protocol

        2. UDP stands for user datagram protocol

    * Transport layer is responsible for dividing data into segments which then received by the next layers.

5. Network Layer

    * Network layer segments data from the Transport layer and divide it into packets.

    * This layer is also responsible for routing, logical addressing, and path determination.

    * Logical address is an IP address which is unique for each computer and helps in finding networks and hosts within the networks.

6. Datalink Layer

    * This layer further divides data into frames.

    * This layer is also responsible for physical addressing.

    * This layer allows other layers to user media for data transfer through media access control

7. Physical Layer

    * At this layer data which is in form of binary bits gets converted to signals and transmitted over a network
