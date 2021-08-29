# TCP/IP Protocol Suites

TCP / IP Protocol Suites

TCP \(Transmission Control Protocol\)

TCP is one of the mail protocols used in a TCP/IP network.

Connection Oriented protocol which basically means that it must first acknowledge a session between two computers that acknowledge a session between two computers that are communicating and it does this by using a 3 way handshake.

The first step is that the computer will send a message called a SYN.

Then the receiving computer will send back an acknowledgement message telling the sender that it has received the message SYN ACK.

Finally, the sender computer sends another acknowledgement message back to the receiver.

Once this has taken place, data can be delivered.

TCP guarantees the delivery of the data so if a data packet goes missing and doesn’t arrive then TCP will resend it.

UDP \(User Datagram Protocol\) -

UDP is very similar to TCP.

It is also for sending and receiving data but the main difference is that the UDP is connectionless which means it does not establish a session and does not guarantee data delivery.

So, when a computer sends a data, it doesn’t really care if the data is received at the other end and that’s why UDP is known as a Fire and Forget protocol.

Because of the less overhead that is involved of not guaranteeing data delivery, UDP is faster than TCP.

FTP \(File Transfer Protocol\) -

The standard protocol used by web users for file transfer.

Users can download and upload files through the internet.

If the user wanted to make their files available to download to other users they have to upload their files to an FTP server and then a user can simply download them.

There are few ways to transfer files using FTP.

You can use your standard internet browser or you can use special FTP software.

Transfer done by web browser or FTP software.

FTP is a connection oriented protocol that uses TCP for file transfer.

TFTP \(Trivial File Transfer Protocol\)

A simple protocol.

Not used over the internet like FTP.

It is mainly used to transfer files within a same network and it does provide any security during the transfer.

Unlike FTP that uses the TCP protocol for file transfer, TFTP is a connectionless protocol that uses UDP as its transfer protocol.

SFTP \(Secure File Transfer Protocol\)

It is just like FTP except that it adds a layer of security.

A data using secure FTP is actually encrypted using secure shell during data transfer.

So no sensitive data is sent in clear text or plain text.

SMTP \(Simple Mail Transfer Protocol\)

It is a protocol used to send email.

It uses a TCP protocol \(I.e. connection oriented\).

You get an error if the mail is not sent.

POP3 \(Post Office Protocol Version 3\) -

Where SMTP is used for sending emails.

POP3 is a protocol that is used for receiving email.

Whenever an email arrives at your mail server, you can retrieve it using the POP3 protocol and download it to your computer.

The main characteristics about POP3 is that all it does is grab the email from the mail server and downloads the email to your computer.

It does not sync any email or folders from the mail server and your computer like IMAP4 does.

When your email application using POP3 retrieves the email from the mail server, the email is removed from the mail server unless you specify in your email application to keep a copy on the mail server.

POP3 is commonly used with email applications such as microsoft outlook.

IMAP4 \(Internet Message Access Protocol Version 4\) -

IMAP4 is another protocol that is used for receiving email.

It is similar to POP3 because they both are used in retrieving email from a mail server but IMAP4 has better features.

With IMAP4, you can access and manage your email on the server from your local computer.

Copies of the email are remained on the mail server.

Unlike POP3, IMAP4 syncs your email and your email folders from the mail server with your computer.

IMAP4 is also commonly used with microsoft outlook.

HTTP \(Hypertext Transfer Protocol\) -

It is most widely used protocol.

HTTP is the protocol that is used for viewing web pages on the internet.

We use HTTP to retrieve the web page HTTPS \(Hyper Text Transfer Protocol Secure\).

In standard HTTP, all the information is sent in clear text.

It is okay if we browse regular website but if you are at a website where you had to enter sensitive data such as passwords or credit card information then this would be a problem for the security.

HTTPS stands for Secure Hypertext Transmission Protocol.

This is HTTP with security feature.

HTTPS encrypts the data is being retrieved by HTTP.

Ex- Used in banks, email servers or e-commerce websites.

Telnet -

Telnet is a terminal emulation program that is used to access remote servers.

It is simple tool that runs on your computer and will allow you to send commands remotely.

Because it only sends commands and not graphics, it is very fast.

The drawback is that it us not secured as all commands are sent in clear text.

So today, a telnet is mainly used to access devices within a local network and not on the internet.

SSH \(Secure Shell\) -

It is better alternative to telnet.

Secure Shell protects the data from being attacked or stolen as it’s been transferred over a network.

Secure shell acts as a secure tunnel that forms around the data transfer and protects it from potential threat.

ARP \(Address Resolution Protocol\) -

This is the protocol that is used to resolve ip addresses to MAC addresses.

Whenever a computer needs to communicate with another computer on the network, it needs the MAC address for that computer.

If a computer wants to communicate with another one then it will first look at it’s internal list called an ARP cache to see if the targeted computer’s ip address already has a matching MAC address in its table.

Now, if it doesn’t, it will send out a broadcast message out on the network asking which computer has the ip address and the computer that has the matching ip address will respond back informing that it has the ip, it is looking for.

Then the original computer will ask for the MAC address and then once it receives it, the communication will take place between the two.

RARP \(Reverse Address Resolution Protocol\) -

RARP is just the opposite of ARP.

RARP resolves MAC addresses to IP addresses.

NTP \(Network Time Protocol\) -

This is the internet standard that is used to synchronize the clocks of computers with the U.S. Naval Observatory master clock.

This protocol runs on each computer and it sends periodic requests to the server to make sure the time is in sync.

SCP \(Secure Copy Protocol\) -

This uses secure shell to safeguard data as its being transferred over a network.

SNMP \(Simple Network Management Protocol\) -

This is used for network management.

It is used to collect data from various network devices such as : routers, printers and servers.

