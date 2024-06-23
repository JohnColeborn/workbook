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


---
---


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


---
---

Q3 Define the features of the following technologies that are essential in terms of the development of the internet:
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


---
---

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


---
---

Q5 Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.


# Cobol
A common business-oriented language, Cobol was designed to be highly readable and self documenting and achieves that using a prose style approach, quite similar to how we would write pseudocode. It was and is an excellent language for handling large bulk data particularly in number handling. And was designed with that intent as a business oriented programming language to be primarily used in mainframes. 

Some drawbacks that have arisen with Cobol are its excessive syntax, a lack of conforming to modern design needs (such as structured programming), it's need for very large programs that are hard to read and grasp overall understanding of (though the line to line is exceptionally easy), and more.

 ``` Fun Fact: My mum was one of the earliest female programmers in Australia who used Cobol when she was coding for Caterpillar quite some time ago ```

# C#
A language designed to be highly portable (easily run on different platforms), economical for resources, and to be used in developing software components. It is a general purpose programming language and has a broad spectrum of qualities including "static typing, strong typing, lexically scoped, imperative, declarative, functional, generic, and OOP"[[2]](#2) 

Some drawbacks to C# are the greater learning curve that simpler languages such as Cobol exhibit. The failure to be as economical on resources as some of its peers. Greater runtime due to using CLR(Common Language Runtime), and focused mainly on Microsoft and Windows usage through .NET

<a id="2">[2]</a>
Skeet, Jon (2019). C# in Depth (Fourth ed.). Manning. ISBN 978-1617294532


---
---

Q6 A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.


## Email from client

``` 
  Hello there!

  My name is Alex, and I’m the director of the Super Awesome Museum (SAM). We display a variety of interesting artifacts, objects, and paraphernalia about all sorts of things from all over the world.

  I’m writing to you because the SAM needs a website. The museum is new in the city, we’re fully funded and don’t sell our items but we just need to encourage people to visit the museum.

  We would need a website that showcases some of our interesting exhibits and items, helps people find their way to the museum, and helps people contact the museum.

  We don’t know much about this website stuff - does this sound like something that you can do? 

  Looking forward to hearing from you,

  Alex

  Director

  Super Awesome Museum 
```




## My Response email
Hello Alex,
    
Great to hear from you and wonderful to hear about your Super Awesome Museum, I would love to come and check it out myself!

While my knowledge on your specialty is limited, when it comes to websites and all of your internet needs I have acquired an excellent repertoire of knowledge and skills to meet your needs such as:
- In regard to not selling any items but wanting to encourage visitors, you would not need any E-Commerce, but would most likely need a highly optimised image gallery.

- Being new to the city we would include SEO (Search Engine Optimisation), which would allow for greater exposure.

- People would be able to contact you via a dedicated contact page which would include options such as a form to contact through the website, phone details, physical address, and any links to social media platforms you would like attached. It would be likely that we would embed Google Maps for people to find where you are situated and how to get there.

- We always ensure that our sites are responsive and accessible to all ages and demographics across multiple devices which makes online access easier to the broad variety of people interested in your museum.

- UX (User Experience) is a large part of our priorities when building a website, we like to ensure a clean, responsive, and overall pleasing experience.

- We would use the appropriate CMS(Content Management System) such as WordPress and assist you and your team in learning how to use and update it.

- We also offer hosting solutions and a maintenance retainer if you are interested in that.

Rest assured that we go as far as needed to make sure that everything makes sense for you, and are happy to answer any and all questions that may arise.

The basic way we would achieve this is by having a meeting at a time of convenience to discuss details in depth. 

If you are interested in arranging a time when we can also provide more info such as pricing, strategies, and overall plans we would love to hear from you.

Regards

John
___
Managing Director
CoolGuy Websites

[coolwebsiteguy@websites.com](mailto:coolwebsiteguy@websites.com?subject=Test)

[Call Us](tel:1223334444)

[LinkedIn](linkedincoolguy)
[Facebook](facebookcoolguy)
[Twitter](coolguytwitter)


---
---

Q7 Think back to a scenario or situation in your own software development projects or work.

Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.


# My scenario
I spent a few months building a 2d RPG to learn C# and Unity, and absolutely loved the entire experience. I did however spend the vast majority of my time making it look pretty as opposed to coding. Which kind of defeated my main purpose for attempting it.

A few things that I learnt from doing this, and or have learnt since, include:
- I had no prior planning or overall plan
- I had zero exposure, so everything was shiny and distracting
- I can't do everything all at once and definitely won't be a master at anything I have spent a day learning

To spell out the opportunities for growth and improvement from these lessons, I both had and continue to have the following epiphanies:

- Planning in advance is your friend. From many years in cooking this is something I know very well, but when it came to more scholastic pursuits it all went out the window. I have learnt and continue to learn more about how to plan appropriately, how to include both overall and in depth planning. It has been reassuring to see this approach taught in my current course. Which still doesn't stop me from skipping it at times haha. Using tools such as Figma, DrawIO, Trello, Pseudocode to create a layout and palpable steps, clearly defined goals and checkpoints is something that I am hoping to become far more fluent and natural in.

- Having had limited to nil exposure to either coding or Unity prior to my attempt I was getting constantly distracted by all the new information, new content, new everything! What retrospect and a bit of time taught me through this is to fully utilise and more appropriately absorb new content it is best to keep it to small blocks at a time, focus on the block at hand and repeat it as many times as possible. I was constantly trying to jump ahead or try something different and was not retaining much. So my plan regarding this is to put my actions where my mouth is. Break my learning content into chunks I can focus on. Practice it till I can do it with my eyes close (figuratively). Absorb appropriately.

- In a similar vein, recognizing that I can't do everything at once. By having more meaningful smaller chunks of learning with high repetition, I can not only improve retention, but also alleviate stress and distraction caused by information overload.
I won't be a master in a day, but if I practice every day, I will become a master.


---
---

Q8  	

A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops. 

Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.


# Action Plan!
To be a man of action!

Currently living in a rather remote area of Australia, there is extremely limited access to networking, events, or workshops in-person. Which means that almost 100% of my potential networking has to occur online in some form. 

Having been an avid gamer for many years I have quite a few friends in the gaming industry who have worked in various areas of the game design field. While this is somewhat alien to web dev, the foundations of coding are the same across languages and their exposure to both in-house dynamics and IT related experience is a huge source of knowledge and networking opportunities. 

My hope is to reach out and network on a higher level with those in the interest of not only gaining insight, but also potentially employment, learning opportunities, and possibly even friends of friends to get to network with. 

Another thing that I would like to implement is tracking down online opportunities, such as the ones posted in the course discord on occasion. From which I would like to grow my knowledge on as many general fields as possible to increase my base understanding, and also to potentially gain networking opportunities.

I am also doing my best to read documentation around the content I am currently learning, which is complimented by the lessons, and my peers in course. My hope is to fully use the opportunities that arise from this to not only grow my personal network, but also to grow my knowledge.

---
---



<a id="9">[Q9]</a>
 Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.

# Pros
There are many benefits to the usage of language-learning model technologies in the same way that there are many benefits to a calculator, to a dictionary, or to a thesaurus.
To be able to suggest a topic or to specify instructions, and query it from a knowledge base outside our own is an amazing way to learn.
EG:
Calculator: 1+1 = 2
  - Or does it? [[3]](#3)
  - Dictionary is true surely? [[4]](#4)
  - A Thesaurus... as above really, just with a bit more to say about it

So to iterate how these tools can impact written and technical works, (refers to thesaurus), verbosity! It teaches that taking a mellifluous peregrination approximates equitably conspicuous conclusions.

To refer to the dictionary for some of these was a path that had to be taken for myself, which only served to prove its purpose and worth

For calculations, mentally computing 1 + 947 + a + pi / .5 is going to take a long time, and using a calculator will expediate the process.

However, to lead into Cons below, the accuracy is pre-defined by the programming(as in AI) and while 1 + 1 might equal 2, but does it count to the x<sup>99</sup>? An excellent example is a float only having 6-7 decimal digits of precision

# Cons
But. Buuuut. Not entirely sure how to drag out a phonetic 'u' appropriately, let me ask ChatGPT for the first time for this, so I can verbatim an appropriate response.

ChatGPT is given the prompt "But. Buuuut. Not entirely sure how to drag out a phonetic 'u' appropriately"

Response: "To drag out the phonetic 'u' in writing, you can use repeated 'u' characters. For example, you could write "But. Buuuut." This effectively elongates the sound and conveys the extended pronunciation you're aiming for. The number of 'u' characters can vary depending on how long you want to stretch the sound, so feel free to adjust it to fit your needs." [[5]](#5)

So this particular case study was not excellent in terms of result, apologies for the potential head bopping. There is a very literal response, without a grasp of context or completion.

But to a degree the point is conveyed, this is a tool entirely devoted to answering, and using itself to grow, so it can answer more, but more is != True. EG: Bunnings Snags through an AI filter just doesn't add up as demonstrated recently on some viral Reddit threads [[6]](#6)



<a id="3">[3]</a>
[H, John (2019). Terrific Math & Science Tutoring and More!.](https://www.wyzant.com/resources/answers/638898/when-does-1-1-not-equals-2)


<a id="4">[4]</a>
[Oxford University Press ELT](https://learningenglishwithoxford.com/2024/02/29/15-modern-english-words-with-different-meanings-in-the-past/)


<a id="5">[5]</a>
[ChatGPT 2024.06.23](https://www.youtube.com/watch?v=dQw4w9WgXcQ)


<a id="6">[6]</a>
[Reddit Bunnings AI Example 2024.06.19 AbleCalligrapher5323](https://www.reddit.com/r/AusMemes/comments/1dj7y98/facebook_suggested_i_try_their_ai_so_i_told_it_to/)


---
---

Q10 Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.


# An exponentiation of explanation
I would like to preface this segment with a clarification, this is a purely academic study, the following is an attempt to understand and iterate the query and response.

This truly is a fascinating query, and an instantaneous example that springs to mind is a somewhat eccentric study by a music theorist called Adam Neely who interviews Damien Riehl and Noah Rubin, and it explains that as a technicality all music can be claimed as copyrighted provided it is "copied to a physical medium" [[7]](#7)

From this we infer that there is a vast majority of 'Intellectual Property' that is based around dictionaries, libraries, lists, databases. In essence what words are said or how words are constructed into sentences are all "claimed by &copy;" 

Another suggestion outside original obvious (Dictionaries have the words correct?) the Bible mentions a theory that there are no new theories [[8]](#8)

In a particular interpretation of this data, it could be surmised that all data exists in a theoretical format, that all data once written, could not be unwritten, and hence duplication of the 'physical medium' would then be subject to claims of plagiarism or breach of &copy;. 

When a language model such as ChatGPT is then used via prompt to complete a task or answer a question, we refer to question nine [[9]](#9). 
- Can it answer a question in a meaningful way? (True)
- Will it always be true and be able to be used as testimony or fact? (False)
- Can it greatly speed up the general creative process? (True)



<a id="7">[7]</a>
[Neely, Adam 2020.2.11](https://www.youtube.com/watch?v=sfXn_ecH5Rw)


<a id="8">[8]</a>
[Bible KJV Ecclesiastes 1:9](https://www.bible.com/bible/1/ECC.1.9.KJV)


---
---

Q11 Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.
  -  Soft skills
  -  Hard skills


# Soft Skills
Calm
- Increases sense of clarity and control from an outside and inside perspective
  - This helps keep a workplace smooth and positive, allowing for greater productivity and appropriate responses throughout all processes particularly in times of stress or elevated emotion

Friendly
- Increases chances of positive interactions
  - Being more approachable is an incredibly proactive way to ensure that elements such as constructive criticism, general interactions, and professional discussion are carried out in a manner that is both comfortable and of a higher likelihood to be absorbed and reflected appropriately

Focused
- Improves productivity
  - Ensures that tasks are adhered to appropriately, that timelines are met, that final products are polished. The benefits of being focused are almost an endless list, possibly excluding only sleeping and / or resting

# Hard Skills
Design
- Ability to create conceptual views, flows, and overall concepts used in the development and execution of software creation

Programming
- Knowledge and usage of programming languages, syntax, and use, applied to create functional code, programs, games, and more 

Research
- Includes reading documentation, exploring new data and theories, establishing own use-cases and facilitating the general knowledge requirements for each and every aspect of software development


---
---

Q12 Explain multiple roles or job positions that would be found in a medium-sized software development company.


# Positions and Descriptions

### Scrum Master
Agile coaching, someone who facilitates the training and use in Agile software development projects

### Project Manager
Someone who manages budgets, people, and timelines for projects

### Technical Lead
Developer accountable at a higher level for the quality of the software, overseeing and training developers at a lower level

### Front End Dev
Develops the client facing elements of software such as CSS on websites

### Back End Dev
Develops and maintains databases, functional code, and integrates behind the scene mechanics with the client facing elements

### UX Designer
Responsible for the user experience of the software, can include graphical elements, responsiveness, audio cues, and more

### Product Manager/ Owner
Responsible for prioritizing the development backlog according to the overall business strategy

All the above [[10]](#10)


<a id="10">[10]</a>
My Wife (Project Manager - A large multinational tech company)



---
---