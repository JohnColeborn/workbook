Q1 Identify and explain common and important components and concepts of web development markup languages.


# Some common and important concepts in detail:

## Markup languages use tags to manipulate / alter data
An example of this would be Markdown using an "em" tag to emphasise a word.

This varies somewhat between languages as to the extent of how and how far.

Manipulation of data to create a structured document is another example which can be seen in various markup languages such as the use of elements in HTML where through a start tag, content tag, and an end tag a simple text is converted into a particular format or has a particular use like the "head" element which contains metadata, and other information which will affect the overall document.

## Markup languages are similar to a verbal/written language
As with a language like English, markup languages have a few "grammatical" laws known as syntax. Similar to how we learn to read and write appropriate English following the conventions of sentence structuring, spelling, and word building. So we learn to read and write appropriate syntax for markup languages by following the convention of tag usage, semantics, and element use.

## They create structure in data
To summarise and emphasise this point a little, an example is Markdown using tags and whitespace to create a particular structure.

## They have their own unique Schemas
Again using common written and spoken languages such as English and Chinese it can quickly been shown that not only are the characters of their alphabets completely different, but also their word building, sentence structures and many other aspects are completely unique to that language. Each of these languages has a dictionary unique to themselves that summarises all the appropriate laws such as correct and incorrect spelling. 

This concept applies directly to markup languages, through the use of their dictionaries, which are known as Schemas

----
----

Q2 	Define the features of the following technologies that are essential in terms of the development of the internet:
 - packets
 - IP addresses (IPv4 and IPv6)
 - routers and routing
 - domains and DNS

Explain how each technology has contributed to the development of the internet.

# Packets

## What are packets?
Assuming familiarity with instant noodles we can quickly grasp the concept of packets and how they apply to internet information. (Apologies if this is read while hungry) By opening a packet of instant noodles there will generally be multiple smaller packets inside containing seasoning, sauce, sometimes even vegetables! By sending someone a large packet with multiple smaller packets within, you can give them a meal. 

To translate this and apply it to internet theory we can say that if we have a large block of data (delicious noodle dinner), that we would like to transfer. The large block is broken down into smaller 'packets' (seasoning, sauce) and shipped to be re-assembled at the end user.

The benefits of this include but are not limited to a more balanced loading across platforms used in the transferal, such as using a more constant lower intensity upstream or download. Or also by allowing multiple mirrors to take a packet each and then bring them back together which can avoid congested networks, or issues with equipment.

A network packet will generally consist of three parts:
- Name or packet header
- Content or payload
- Signature or trailer
 
To use the instant noodle analogy, the name or packet header is the packaging and the description of type of noodles, spicy beef ramen. The content or payload is the delicious product, and the signature or trailer is the brand. To reiterate in internet terminology the name or header is the box that holds the data and contains the instructions related to its contents. The content or payload is the data itself. The signature or trailer is exactly that, a signature to identify where it has originated from.

## How have packets contributed to the development of the internet?
A major use that packets have brought to the internet is the ability to manipulate large data through multiple access points. An example of this may be:
- Torrent files. Effectively a large file broken into many smaller files that have a 'tracker' which identifies their parent file, their position on the ladder within the parent file and more. By utilising packets in this manner, the torrent file can be initialised through a 'seed' and can then pull data from various hosts. EG: File part 1/100 from one source, and part 2/100 from another which are then reassembled at the end user to obtain the complete file 100/100. 

# IP Addresses
## What are IP addresses and what is IPv4 and IPv6?
IP is an acronym for Internet Protocol and v4 and v6 are version numbers for this. 
An IP address is similar to the address of the physical house we live in EG: 42 Wallaby Way Lane Cove. This physical address can be looked at in a few ways, such as the physical location of the house, and the physical location from which can be sent mail, or can receive mail sent to it. An IP address also functions in this manner as both the physical 'home' of the device and also the access point to send and receive data via internet. The IP address identifies the network device, which may be local(home) or remote(internet). A good example commonly used is Git where data may be formed and stored on the home device(can be viewed at a local address), or transferred to remote (can be viewed on internet). Regarding IPv4 and IPv6 they are both a means to traverse the paths between devices with some differences in terms of capability. Using the postal service as an analogy we could say that IPv4 is like the postie on his bike delivering mail, and IPv6 is the postie in his van delivering different mail(perhaps bulkier parcels)

## How have IP addresses contributed to the development of the internet?
Internet Protocol is the means by which one address can be accessed and identified by another address. For example using roads to travel between towns is helpful (data streaming via cable or other means), but in order to reach a particular destination we need to first identify the address and then travel the appropriate roads to get there. 
So in order for there to be an 'Internet' it was first necessary to create paths between devices, then a means to identify both the end address and the path choices required to get from one device to the next. Branching further down the same school of thought we arrive at a point where millions of paths with vast and various data types transfer from one all those addresses to other addresses. 

# Routers and routing
## What is a router? What is routing?
Cambridge Dictionary defines Route as "'a particular way or direction between places', 'a method of achieving something', 'a set of regular visits that you make to a number of places or people, especially in order to take products as part of your job', 'to send something somewhere using a particular way or direction'"[[1]](#1)

This is somewhat along the lines of semantic HTML where the names mean what they sound like they mean. 

Routing is an encapsulation of many elements of the pre-defined 'Route'. 
- Identifying of paths between devices
- Optimisation of using the most appropriate path.
- Knowledge of the start and ending points and everything in between. 
- Knowledge of the rules of each path (kind of like how we have speed zones on a street etc.)

A Router is a device which enables all of this and has some key features:
- Sends data packets from a local device to a remote device
- Receives data packets from a remote device to its local device
- Encrypts and decrypts data packets
- Assembles and dissembles data packets
- Directs data packets on where and how to go
- 'Bounces' data from one remote device to another

<a id="1">[1]</a> 
https://dictionary.cambridge.org/dictionary/english/route

## How have Routers and routing contributed to the development of the internet?
 Similar to the postal service having post offices where mail can be sent from one address to another, perhaps by a straight path, perhaps by going to multiple different post offices along the way.

 Routers are access points where data packets are received and sent. Where instructions are enacted in order to enable data to transfer appropriately to an intended destination. 

Routers then can be seen as an ultimate followup tool specialised in handling data packets, enabling internet protocol, and being a dedicated resource to minimise stress on any particular one device along the way.


# Domains and DNS
## What are Domains and the DNS?
Domains are the IP address of a particular nature. For example 198.168.1.60 may be the IP address/domain of a local home device and 127.421.4.12 (these numbers are lorem) might be the specific IP address/domain for an online shop. The Domain Name System (DNS) manages these addresses like a large registry where the information that 127.421.4.12 is known as (online shop), and keeps it unique across its particular internet protocol.
A huge benefit of the DNS is that it enables us to use and remember particular websites in our language such as English (Google), and enables our devices to use and remember particular websites in computer language (127.421.4.12 (not Googles actual number haha))

## How have domains and DNS contributed to the development of the internet?
To liken it to our local town or city. If each address was the same we would not be able to send a letter to anyone else. But also if we want to send a letter to someone on the other side of the city we are able to look up a registry of people or business's and send the mail to the appropriate address.

If there were no unique IP addresses identifying each domain it would be impossible to transfer data appropriately. If there was no DNS, then trying to remember 197.232.2.13 equivalents for every site we wanted to access would be complicated at a minimum. Much easier to be able to look up 'Google' or 'Coolsite.com'

----
----

Q3: Define the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)

Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)
# TCP
## What is TCP?
Transmission Control Protocol is a large part of the governance used to enable data transferal between devices. It does this by:
- Listening for requests
- Providing communication between a program and the IP
- Establishing connections between the sender and receiver
- Policing lost, duplicated, unordered data packets
- Ensuring certifications and credentials are correct prior to allowing traffic (handshakes)
- Ensuring that sent data has been received
- Many more
## How has TCP contributed to the development of client and server communication over the internet?
By complimenting IP in a step commonly referred to as TCP/IP it is used in many large internet apps up to and including the big WWW(World Wide Web) as a means to fulfill the steps listed above.
# HTTP and HTTPS
## What is HTTP AND HTTPS?
Hypertext Transfer Protocol and Hypertext Transfer Protocol Secure (Not to be confused with HTML) are the base of the web and are used to load websites using Hypertext links. They achieve this by sending a query to a server, which then responds

For example an HTTP request contains and shares data such as what version the HTTP is using, a URL, its method which is conveyed to a queried server. The queried server then responds by answering the data with appropriate communication. EG:
(In laymen terms) Can I use HTML on this site? Yes you can. HTTPS is the Secure version of this and uses encryption to enable a secure environment for the communication.
## How has HTTP and HTTPS contributed to the development of client and server communication over the internet?
By enabling a method of "Can I do this on your site? Yes you can" it has allowed a local device to 'talk' to a server and work out if it can be used for a connection and further transfer of data. Essentially asking for what information they need to load a website.
# Web Browsers
## What are web browsers (requests, rendering and developer tools)?
Web browsers are UI apps designed to allow users to browse, find, view, and interact with websites via the internet. There are many browsers that vary somewhat in capabilities and features. Some common elements are the abilities to search around and interact with websites, and some less common elements are high customisation options and stronger security features. 
- Requests. They possess the ability to query websites for things such as certificates and content previews.
- They can render images and translate different languages to allow viewing of data in a way that is more comprehensible to humans.
- Allowing the use of developer tools such as 'Inspect' and the developer console attached.
## How have web browsers contributed to the development of client and server communication over the internet?
By enabling an extremely simple layout, meaningful translations, a means to traverse the web, and many other features web browsers empower users to view, navigate, and interact with the internet. Such a highly demanded tool has been massively beneficial in promoting the use of the internet, and has simplified the use from clients when accessing different servers. What once was a complex path of going from user input to correct destination and accessing desired data can now be as simple as a couple of clicks.

----
----
Q4 Describe the features of interpreters and compilers and how they are different.
# Interpreters and Compilers
## What are Interpreters
An interpreter is a program that directly executes coded instructions or scripted language in a single line. An example of this would be using WSL to set up a Git repo
## What are Compilers
A compiler is a program that takes an entire code block and alters it into machine code and then executes it. An example of this would be using Python to run an app
## How are they different?
- Interpreter is a single line operation, Compiler is a multiple line operation
- Interpreter is an almost instant response, Compiler has a delay during compilation and has to be re-compiled each time it is altered. 
- Interpreted code translates to machine code as it goes, compiler converts it all to machine code and then runs which optimises run time and execution
- Debugging interpreted code is generally a lot simpler than debugging compiled code due to compiled code being machine code and lacking human-readable code while interpreted code remains as written.

----
----
Q5 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.
# Cobol
A common business-oriented language, Cobol was designed to be highly readable and self documenting and achieves that using a prose style approach, quite similar to how we would write pseudocode. It was and is an excellent language for handling large bulk data particularly in number handling. And was designed with that intent as a business oriented programming language to be primarily used in mainframes. 

Some drawbacks that have arisen with Cobol are its excessive syntax, a lack of conforming to modern design needs (such as structured programming), it's need for very large programs that are hard to read and grasp overall understanding of (though the line to line is exceptionally easy), and more.

 ``` Fun Fact: My mum was one of the earliest female programmers in Australia who used Cobol when she was coding for Caterpillar quite some time ago ```

# C#
A language designed to be highly portable (easily run on different platforms), economical for resources, and to be used in developing software components. It is a general purpose programming language and has a broad spectrum of qualities including "static typing, strong typing, lexically scoped, imperative, declarative, functional, generic, and OOP"[[2]](#2) 

Some drawbacks to C# are the greater learning curve that simpler languages such as Cobol exhibit. The failure to be as economical on resources as some of its peers. Greater runtime due to using CLR(Common Language Runtime), and focused mainly on Microsoft and Windows usage through .NET

<a id="1">[2]</a>
Skeet, Jon (2019). C# in Depth (Fourth ed.). Manning. ISBN 978-1617294532

----
----
Q6 A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.

## Email from client
Click for details
<Details>

The client’s email is as follows:

Hello there!

My name is Alex, and I’m the director of the Super Awesome Museum (SAM). We display a variety of interesting artefacts, objects, and paraphernalia about all sorts of things from all over the world.

I’m writing to you because the SAM needs a website. The museum is new in the city, we’re fully funded and don’t sell our items but we just need to encourage people to visit the museum.

We would need a website that showcases some of our interesting exhibits and items, helps people find their way to the museum, and helps people contact the museum.

We don’t know much about this website stuff - does this sound like something that you can do? 

Looking forward to hearing from you,

Alex

Director

Super Awesome Museum 
</Details>
  

## My Response email
    Hello Alex,
    
    Great to hear from you and wonderful to hear about your Super Awesome Museum.

    While my knowledge on artefacts, objects, and paraphernalia about all sorts of things from around the world may be limited, when it comes to websites and all of your internet needs I have aquired an excellent repetoir of knowledge and skills.

    From your email I would like to draw out a few focal points for discussion:
    - The museum requires a website
    - The museum is new in the city
    - You do not sell any items, but would like to encourage visitors
    
    To further clarify on these points:

    The museum requires a website for multiple reasons that you have listed, such as showcasing some of the wonderful exhibits and items, helping people find how to reach you, and helping people contact you either through the website directly or through phone and address details.

    SAM is also new in the city which I would assume indicates that word of mouth advertisment and exposure amongst the populace is low to nil at this point. Am I correct in saying that through the website you hope to create an online presence that assists in exposing people to the awesome features you are offering and encourages them to come in and check it out?

    
