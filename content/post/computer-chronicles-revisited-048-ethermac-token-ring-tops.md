---
title: Computer Chronicles Revisited, Part 48 — EtherMac, Token Ring, and TOPS
description: The Computer Chronicles discusses computer networks.
date: 2022-03-27
categories:
  - "Computer Chronicles Revisited"
tags:
  - "Computer-Networks"
draft: False
---

IBM was not having the best year in 1985. In October, Big Blue reported its third consecutive drop in quarterly profits. *TopView*, IBM's attempt to introduce multi-tasking into DOS, had not taken the business market by storm. And then there was the ever-increasing competition from various PC clone makers.

But we're still in the period where many industry observers kept their faith in IBM's ability to brute-force its will upon the market. That leads into our [next *Computer Chronicles* episode from October 1985](https://www.youtube.com/watch?v=illGtdeI6uo), which focused on computer networks. As Stewart Cheifet mentioned during the [last episode's "Random Access"](https://smoliva.blog/post/computer-chronicles-revisited-047-the-well/) segment, IBM had recently launched its new token ring system, which was the company's challenge to 3Com's Ethernet standard in local area networking. 

## Would Token Ring Become the New Standard in LANs?

Cheifet did his cold open standing outside IBM's headquarters in Endicott, New York. He quipped that when most people thought of three-letter abbreviations for "networking" it was usually "NBC", "CBS", or "PBS," but when it came to computer networks the more relevant abbreviation was "IBM." Cheifet said IBM's new token ring system could finally put computer networking on the high-tech map. 

Gary Kildall was back in the co-host's chair this week. On the desk, Cheifet showed off a random assortment of computer cables. He said these were part of a computer networking system or local-area network (LAN). He noted that people in the computer industry had been talking about networking for years, but from the user's point of view nothing ever seemed to happened. Would IBM's token ring system finally make things happen in networking? Kildall said that LANs let personal computers share huge data files--and when it came to personal computers used in offices, IBM sets standards. And if there was a new standard, he saw some exciting possibilities for networking and network-aware software.

## Using Existing Telephone Lines for PBX Networks

Wendy Woods presented her first report. Narrating over some B-roll footage of an unidentified office, Woods said that as PC workstations became more common--and their standalone functions more elaborate--they became increasingly attractive as alternatives to mainframe-based networks. But so far, there had been limited acceptance of LANs due to the usual incompatibility of operating systems and the expense of installing miles of coaxial cable.

But Woods said that the logic of a PC-to-PC network was powerful and there were some new solutions on the market. For businesses already equipped with a telephone PBX system, a practical network could be installed over existing phone lines. One of the first of these was Northern Telecom's Meridian system, which worked in conjunction with a local PBX to handle both data and voice over standard twisted-pair telephone wiring. 

Equipped with its logical counterpart--an integrated voice and data terminal--Woods said the Meridian system combined computer and communication functions, such as an online directory and automatic dialing. Messages could be transmitted in text or voice mode, or a combination of both. Terminals tied into the network could automatically log on to outside databases. Two users could share multimedia information simultaneously. The star-shaped network also allowed for the shared use of printers and hard disks, and the internal BUS operated at 40 MB/second. 

Memory-enhanced telephones were nothing new, Woods noted, and any PC could store a directory of numbers, but the computers using the Meridian system had a practical route to travel--along the telephone wires already found in every office wall.

## Ethernet on the Macintosh

Bob Metcalfe and Sherry Geddes joined Cheifet and Kildall for the first of two studio round tables and demonstrations. Metcalfe, the founder and chairman of 3Com, [previously appeared on *Chronicles* back in March 1985](https://smoliva.blog/post/computer-chronicles-revisited-037-equalizer-computer-colorworks-digital-paintbrush-system-att-unix-pc-grid-compass-1101/). Kildall opened by recalling [another prior *Chronicles* episode from September 1983 on LANs](https://smoliva.blog/post/computer-chronicles-revisited-010-sytek-localnet/). He asked Metcalfe about the progress that had been made over the two years since that show aired. Metcalfe said that LANs had been a long time in coming--indeed, people like him had been working on the technology for the past 10 to 15 years. He estimated there were currently about 100,000 LANs in operation. 

Kildall wondered how that figure related to the number of people who actually needed a LAN. (He quipped that the average person in the home didn't really need a LAN.) So 100,000 LANs should be considered a success. Metcalfe said it was a relative success but there was still a much bigger potential. He saw LANs as part of the next generation of computing. So in his view, 100,000 LANs seemed like a small number. There were about 7 to 8 million PCs currently used in businesses, so he thought the number of LANs could get quite a bit larger. 

Kildall noted the advantage of the personal computer is that it was a standalone unit. But the disadvantage was that it didn't have access to a big database. The PC wasn't really built for I/O (input/output) processing, so is that where an LAN could help out in an office? Metcalfe said absolutely, the standalone PC was in his view a "transient" in the development of computers. That is, they were useful up to a point. So a LAN provided access to data that the PC could not store by itself, as well as data that needed to be frequently updated by many other people.

Turning to Geddes, a computer networking consultant with Strategic, Inc., Kildall asked about PBX networking, which she worked with. Could you get high data-transfer rates with a PBX system, which was basically a telephone network? Geddes said you could get high data rates on specialized PBX systems called *data PBX*. On traditional integrated voice-data PBX systems (presumably like the one Wendy Woods described in the prior segment) the data rates were still relatively low, but the throughput was very good, and that was a critical distinction. Many users didn't need a high data rate; they needed a high throughput rate because lots of users required simultaneous access to the network. 

Cheifet asked Metcalfe to demonstrate EtherMac, an Ethernet adapter for the Macintosh. Metcalfe explained the Macintosh was connected to an AppleTalk server located at the other end of the studio. (A man named "Derek" monitored this machine.) Metcalfe used a floppy boot disk to login to the network and access the network server. 

Kildall asked about the comparison between the data-transfer rates of the network as compared to, say, accessing a file locally from a floppy disk. Metcalfe said the network was actually two-to-three times faster than the floppy disk. 

Continuing the demo, Metcalfe showed how he could open the same document that Derek was looking at on his machine at the other end of the studio. Kildall asked how users could then protect their files on the network. Metcalfe said the user could assign a password. What about simultaneous access, Kildall asked? Could two users write to the same file at the same time? Metcalfe said that 99 percent of the software designed for personal computers were meant to run on only one PC. If two PCs tried to manipulate the same data on a disk, the data itself could be damaged. So you had to take that into account when designing a network so that people did not simultaneously manipulate the same files. 

Cheifet clarified that although Metcalfe's demo involved networking two Macintosh computers, it could also be done with two IBM PCs or other computers as well. Metcalfe said yes, this particular system could network hundreds of IBM PCs or Compaqs or other machines. 

Cheifet asked Geddes why people were making a big deal about the new IBM token ring standard when Ethernet already seemed to be working well. Geddes said IBM had taken a different approach. The EtherMac system was a collision-based system, which provided good access for users in an office environment. One advantage of the token ring approach was that every device knew it would get the "token" at a predetermined time. This could be very important in something like a factory, where you knew every device had to be polled every so-many nanoseconds or microseconds. In an office environment, this was useful in a bisynchronous situation or an office with a very large population where you didn't have any type of prioritization scheme. Otherwise, you might have users who never gain access to the network. Ultimately, Geddes said token ring's main benefit was to IBM customers and those shops that relied on primarily on IBM equipment.

Cheifet turned back to Metcalfe and asked if EtherMac could be used to share peripherals as well as files. Metcalfe said yes, and in fact one of the strong advantages of this particular system was that you could connect multiple computers--PC and Macintosh--to an Apple Laserwriter. 

Kildall asked Metcalfe about the EtherMac's system cost. Metcalfe said it cost about $10,000, not including the computers. 

## Multi-User Systems vs. PC-Based LANs

Wendy Woods returned with her second remote segment, this time focused on Viasyn, a company based in Hayward, California. Woods opened by noting that the difference between a multi-user system and a network was that the former was designed to be networked--unlike an office full of PCs. Viasyn was one of the players in the multi-user system market. It produced the Compupro line of CPUs and terminals. 

Viasyn founder Bill Godbout--who previously appeared in [another *Chronicles* remote segment reported by Robin Garthwait](https://smoliva.blog/post/computer-chronicles-revisited-036-top-view-concurrent-pc-dos/)--told Woods there were two advantages to working with a multi-user system as opposed to a LAN composed of separate PCs. The first was speed of operation. The second was cost-performance ratio. A multi-user system like the Compupro was generally 20 to 50 percent less expensive than a network of PCs. 

Woods said Compupro terminals used [Datapoint Corporation's ARCNET](https://networkencyclopedia.com/arcnet/), the networking architecture with the largest installed base in the world. This system could link up to 14 users--and even more if the CPUs were connected at central points called *nodes*. Woods noted that Viasyn's own departments were interconnected in this manner. 

Unfortunately, Woods said, the biggest drawback to networking, whether through multi-user systems or a room full of PCs, was cabling. Cabling had to go through a building to every terminal hooked up to the network. There wasn't much that people in the industry could do about that. But one thing was certain, Woods said: Even IBM was planning multi-user systems that could be linked to a LAN. Meanwhile, Viasyn's multi-user business continued to grow by "several million percent," according to Godbout. 

## IBM Promised to Maintain "Open Architecture" with Token Ring

Stewart Cheifet presented the next remote segment, this time from IBM's offices in New York. Cheifet interviewed Richard H. Goldberg, IBM's director of marketing for the telecommunications division. Cheifet asked how token ring differed from IBM's existing PC Network technology. (That system was based on Sytek's broadband technology, as I discussed in [my post on the 1983 *Chronicles* LAN episode](https://smoliva.blog/post/computer-chronicles-revisited-010-sytek-localnet/).) Goldberg said PC Network was ideal for small departments and establishments that required a lower-cost implementation. But for businesses with an expanded set of requirements, token ring was a probably a better solution--and a little more expensive. 

Cheifet said that one nice feature of the token ring system was that it didn't require IBM's own expensive cabling system but could work over regular telephone lines. He asked Goldberg about the trade-offs. Goldberg said both telephone lines and the cabling system performed at 4 MB/second. But in order to achieve that performance, there were certain distance limitations, such as from the wall outlet to the wiring closet. For a twisted-pair (telephone) line it was 100 meters, while for the cabling system it was 300 meters. Goldberg added that the number of devices that could be hooked up to the network also differed. Instead of 260 devices, it was 72 devices using twisted-pair lines. 

Cheifet said that IBM was following the same "open architecture" approach with the token ring network that it did with the PC. Goldberg explained that in the "real world" a network had to support a wide variety of device types--not only those that exist now but also those produced in the future. That was the value of the open architecture. It also had to foster application development. 

Indeed, Cheifet noted the next challenge was to find software written to take advantage of networking. Goldberg noted that most software up to this point had been developed as a single-user activity. It didn't allow for distributed file sharing or recognizing a distributed architecture. But now they were starting to see more and more software packages, specifically databases, coming out with a true LAN implementation. In the long run, Goldberg believed that network-based software would change work habits.

## Using Any PC as a File Server for Any Other PC (or Mac)

Back in the studio, Nat Goldhaber joined Cheifet, Kildall, and Sherry Geddes. Goldhaber was president of Centram Systems West, which produced *TOPS*, a LAN-based file sharing system. Kildall opened by noting that unlike the prior EtherMac demonstration--where a Mac was connected to a Mac--Goldhaber set up a demo with a Mac connected to an IBM PC-AT. (Holly Murray, a *Chronicles* producer, worked at the AT on the other side of the studio, while Goldhaber operated the Macintosh from the desk.) Goldhaber noted *TOPS* could network Macs, PCs, or any combination of the two. 

Goldhaber described *TOPS* as a "distributed file-server environment." It was also inter-operating system, meaning that any device or computer on the network--regardless of its microprocessor or operating system--could act as a file server on the network. Goldhaber demonstrated this by mounting volumes from Murray's AT to the Macintosh's operating system as if it were a native file. 

Kildall clarified that you were sharing files but not applications, as the Macintosh was based on a Motorola 68000 CPU and the AT was based on an Intel 80286 CPU, which were not compatible. Goldhaber said that was correct, the server allowed for the free exchange of data only. 

Goldhaber then used *TOPS* to open a *Lotus 1-2-3* spreadsheet stored on the PC-AT using the recently released *Microsoft Excel* for the Macintosh. Goldhaber noted that *Excel* was capable of both reading and writing to the *1-2-3* file format.

Recalling his earlier question to Bob Metcalfe, Kildall asked Goldhaber to compare the data transfer rate of *TOPS* to simply moving files around on a floppy disk. Goldhaber said *TOPS* was slightly faster in retrieving a file stored on a PC-AT hard disk drive. 

Kildall then asked about the cost. Goldhaber said *TOPS* was a software-only product for the Macintosh, which already had a built-in networking system. The IBM PC required a separate, *TOPS*-specific card. The Macintosh software cost $100, while the PC software and card bundled together cost $300. 

Kildall--worried as always about potential software piracy--then asked Goldhaber about the problem of licensing software that could potentially run across thousands of networked machines. Goldhaber said he certainly did not recommend that anyone violate the licensing agreements for their software. Indeed, many software licenses explicitly stated that a copy of a program could only be used locally on a single computer. But Goldhaber expected that all software companies would soon address the issue of so-called "site licenses," which would legally permit multiple computers to use one copy of a program.

Finally, Cheifet asked Geddes if users should sit back and wait until the market for networking standards settled itself out before actually buying something. Geddes said no. She said the issue was so complex that if you waited, all you'd end up doing was feeling more confused later. She advised businesses to "get their feet wet" now by setting up a small-scale network and hooking up a few machines. This would let you find out if networking actually benefited your organization, and in the long run would help you make a more informed decision.

## Was IBM Simply Protecting Its Mainframe Dominance?

Starting with this episode, George Morrow assumed the end-of-episode commentator role from Paul Schindler. Morrow was critical of IBM's role in creating market confusion over networking. He noted the company had embraced "not one but three different standards" that were all incompatible with one another. And the most recent standard, token ring, was in his view the "least efficient and least reliable" of them all. He added that IBM was also largely motivated by fears that increased demand for LANs might hurt its traditional mainframe business.

## The Rise of the Intelligent Factory, Intelligent Office Building, and Intelligent Home

Stewart Cheifet presented this week's "Random Access," featuring news headlines from late October 1985.

+ Several deals were announced to develop the so-called intelligent factory where robots and computers ran the whole plant. Hewlett-Packard signed a deal with Bechtel to design and develop a fully automated electronics plant. Ford Motor Company also announced its own deal with Measurex to develop a computer-controlled system for running the automaker's assembly plants. And General Motors said it would soon reveal its model for the "factory of the future" using its Manufacturing Automation Protocol (MAP) standard. 
+ The Real Estate Research Corporation said there were now 200 "smart office buildings" around the world, including the CitiCorp building in San Francisco and Hong Kong's Exchange Square. Cheifet noted that tenants of these smart buildings received not only centralized heat, air, and phone service, but also centralized computer applications and electronic mail. The demand for such buildings was still slow, however.
+ Ryan Homes of Pittsburgh claimed to be the first homebuilder in the nation offering homes that came standard with computerized controls for electrical outlets and security systems.
+ Speaking of "intelligent homes," Cheifet said the largest such structure was now in Dallas. The "FutureHome" featured $500,000 worth of automation equipment, including 13 computers, 26 monitors, and 14 telephone terminals. 
+ Keeping with the main episode's theme, Cheifet said more than a dozen companies had already jumped on the IBM token ring bandwagon and would offer bridges to the new system.
+ Paul Schindler reviewed *Concepts Computerized Atlas*, which is exactly what it sounds like. Schindler noted the software's publisher, Software Concepts, had a "clever" marketing method to generate sales. A customer could pay $5 and use the package three times. The software then froze until you paid another $50 to unlock it again. (Even then, the program was still copy protected.)
+ Borland International planned to release [*Turbo Lightning*](https://winworldpc.com/product/turbo-lightning/1x), a $99 RAM-resident program that provided an AI-based spelling checker, thesaurus, and encyclopedia. 
+ A court clerk in Sonoma County, California, was arrested after breaking into the court's computer system and deleting records of his arrest for drunk driving. 
+ Some "New Coke" machines featured two built-in computer games, including "Catch-a-Coke." Cheifet noted you didn't actually get a free Coke if you won, as that would be "Classic or New Gambling." (If you want to learn more about this game, [*The Video Game Soda Machine Project*](https://vgsmproject.com/2017/07/25/catch-a-coke/) by Dr. Jess Morrisette published an in-depth retrospective in 2017.)

## Price and Speed Helped Ethernet Triumph Over Token Ring

Few people today have used a token ring network. That's not to say the standard was a failure. In fact, the token ring standard was competitive with Ethernet through the mid-1990s. But Ethernet ultimately prevailed.

In a [2008 article for *TechRepublic*](https://www.techrepublic.com/article/does-anyone-actually-still-use-token-ring/), John Sheesley delved into the reasons that token ring lost. He explained that strictly in terms of specs, token ring was better than Ethernet: It used bandwidth more efficiently, allowed for larger packet sizes, and performed better overall, even if Ethernet technically transmitted data at a higher rate. 

Despite these advantages, Sheesley said that Ethernet speeds eventually grew so great that token ring's greater efficiency ceased to matter. Vendors also "started introducing switches which eliminated" the problems that caused Ethernet's inefficiencies to begin with. 

On top of that, Sheesley said that IBM "charged too much for royalties to vendors that wanted to produce" the token ring equipment. IBM's Richard Goldberg conceded to Stewart Cheifet that token ring would be more expensive than Ethernet. But he probably undersold the cost difference. Sheesly said that at its height, a token ring networking card "could cost 5 and 6 times as much as an Ethernet card"--and that was before you factored in the cost of the cabling and switches. 

Another loser in the LAN standards battle was ARCNET, which was championed by Bill Godbout's Viasyn. ARCNET was first developed by Datapoint in 1977 and was considered the preeminent networking standard in the early 1980s, but its popularity was quickly eclipsed by Ethernet and token ring. Datapoint continued developing ARCNET into the 1990s, but Viasyn, which made its mark as a provider of niche computing equipment, fizzled out. According to a [November 2018 article by Iain Thomson for *The Register*](https://www.theregister.com/2018/11/18/bill_godbout_obituary/), "the increasing standardization of the industry squeezed Godbout out into semi-retirement." As I noted in an earlier blog, Godbout and his family died when their town burned to the ground during the November 2018 Camp Fire in California. 

## Goldhaber Went from Three Mile Island to Third-Party VP Run, While TOPS Was Eventually Sherlocked

Although the Macintosh debuted with a proprietary networking standard called *AppleTalk*, it was initially designed to connect a Mac to a Laserwriter printer rather than another computer or file server. A number of third-party vendors thus stepped into fill the gap, including Centram Systems West with *TOPS*. Apple would not release its own Mac-based file server, *AppleShare*, until January 1987.

*TOPS* was formally released in 1986 and sold about 45,000 units during its first year on the market, according to a [June 1987 *InfoWorld* report by Laurie Flynn](https://books.google.com/books?id=xjAEAAAAMBAJ&pg=PA23). By that time, Centram founder Nat Goldhaber had sold the company to Sun Microsystems--which had outbid Bob Metcalfe's 3Com at the last minute, according to Flynn. 

Prior to founding Centram, Goldhaber worked in politics, serving as a senior aide to Pennsylvania's Republican lieutenant governor, William Scranton III, from 1979 to 1984. At the time, Scranton was responsible for overseeing the Governor's Energy Council, and he named Goldhaber as interim director--essentially the state's energy secretary--in January 1979. Goldhaber [later told Peter Delevett of the *San Jose Mercury News*](https://www.mercurynews.com/2011/06/08/qa-with-nat-goldhaber-on-the-three-mile-island-crisis/) that he was "unqualified" for the job beyond reading the *Whole Earth Catalog* and knowing something about windmills. 

Just weeks into the job, however, Goldhaber faced two major crises: A sudden drop in oil production caused by the 1979 Iranian Revolution and the partial meltdown of a nuclear reactor at the Three Mile Island Nuclear Generating Station near Harrisburg, Pennsylvania. Goldhaber later told Delevett that he'd organized a press conference with Scranton regarding the oil crisis when he received a phone call about the Three Mile Island accident. Goldberg said it wasn't until the third day following the initial reports that the state government contemplated taking any serious action in response:

>So I was sent down to the Emergency Management Agency’s bunker, three floors underground, and there I sat with a bunch of ex-military guys, mostly brass from Vietnam, and tried to figure out what an evacuation of the area would look like. About 125,000 people voluntarily evacuated, most from close to the site.
>
>It was seven or eight days before we decided things were sufficiently back to normal. There was constant talk on the national news about the situation that were grossly exaggerated, but it was the first time anybody had ever had a nuclear accident, so we really didn’t know.

Having Homer Simpsoned his way out of that situation, Goldhaber left Scranton's office in 1984 and moved to California where he founded Centram Systems West. Goldhaber initially pitched the idea of networking Macs and IBM PCs directly to Apple. According to Laurie Flynn's *InfoWorld* story, Goldhaber said Steve Jobs "thought [*TOPS*] was a product that maybe should go out with every Mac sold, maybe even as part of the ROM." But Jobs was gone from Apple by late 1985, so Goldhaber decided to market *TOPS* on his own.

After selling Centram to Sun Microsystems, Goldhaber stayed with the latter as a vice president until 1989. In 1991, Apple and IBM tapped Goldhaber to run their new joint venture, Kaleida Labs, which produced one of the earliest cross-platform multimedia players--also named Kaleida--and an associated programming language called ScriptX. Goldhaber didn't last long in the job, however, and was ousted after about a year.

In 2000, Goldhaber returned to politics, this time as the vice presidential nominee of the U.S. Natural Law Party (NLP). This is actually where Goldhaber and I likely crossed paths, as I covered the Natural Law Party (NLP) convention that year for an early political blog. The NLP was the political arm of the Transcendental Meditation (TM) movement founded by Maharishi Mahesh Yogi, an Indian-born yoga guru. Goldhaber studied with the Maharishi and helped him establish the Maharishi University of Management (MUM) in 1973 to promote TM as part of a "consciousness-based" educational program. 

Dr. John Hagelin, a physicist, joined MUM--now called [Maharishi International University](https://www.miu.edu/)--in 1984 and currently serves as its president. Hagelin co-founded the NLP in 1992 to promote governance based on TM principles. He was also the party's presidential nominee in 1992, 1996, and 2000. Mike Tompkins, another physicist, was Hagelin's running mate in the first two elections. Goldhaber took over the number-two slot in 2000. As I noted in [my blog post at the time](https://web.archive.org/web/20010225073353/http://www.generationvote.com/focus_08-16-00_2.html), "Goldhaber has promised to provide Hagelin with financial support and the use of two planes."

The Hagelin-Goldhaber ticket only appeared on 38 state ballots, winning a total of 83,714 votes nationally. This proved to be the NLP's last stand. The party dissolved in April 2004. Goldhaber hasn't been a political candidate since and instead is [living the venture capitalist lifestyle](https://claremontcreek.com/team/nat-goldhaber/) in San Antonio.

As for Centram Systems West, Sun renamed the company TOPS shortly after the acquisition. *TOPS* the product continued to do well up until Apple released Macintosh System 7 in 1991, which finally included its own built-in file server. This effectively eliminated the market for *TOPS*. (The common practice of Apple assimilating third-party features into its core OS would [later be called "Sherlocking"](https://www.howtogeek.com/297651/what-does-it-mean-when-a-company-sherlocks-an-app/).) Sun tried to cut its losses by spinning off TOPS into a separate company, Sitka Corporation, but when it couldn't find a buyer, Sun shut down the former TOPS entirely in 1993.

## Notes from the Random Access File

+ This episode is [available at the Internet Archive](https://archive.org/details/Computer1985_3) and has an original broadcast date of October 24, 1985. 
+ [Sherry Geddes](https://www.linkedin.com/in/sherry-geddes-4bb52/) had a long career in marketing within the tech industry. In the early 1980s, she worked at Sytek, a company featured in the 1983 *Chronicles* episode on local area networks. In 1989, Geddes joined First Pacific Networks as its vice president for marketing. She took a similar role with [Tezzaron Semiconductor](https://tezzaron.com/) in 1999. Geddes is currently retired and living in California. 
+ Viasyn's Bill Godbout had a long professional association with George Morrow, which [Herb Johnson detailed in a 2018 post](http://www.retrotechnology.com/herbs_stuff//godbout_obit.html) following Godbout's death. 
+ This wasn't made clear in the episode, but EtherMac was not made by Bob Metcalfe's 3Com. Rather, EtherMac was the first in a long line of Macintosh networking products made by Farallon Computing, Inc., during the 1980s and 1990s. In 1997, Farallon changed its name to Netopia, Inc.. A year later, [Netopia spun-off its Macintosh products business into a separate company](https://www.gores.com/wp-content/uploads/2018/01/Press-Release-Farallon-Capitalizes-on-Apple%E2%80%99s-Momentum-with-Managment-Led-Spin-Off-from-Netopia.pdf), this time called Farallon Communications. Proxim Corporation--now known as Proxim Wireless--[acquired Farallon Communications in 2000 and then bought Netopia in 2001](https://tidbits.com/2001/01/29/proxim-reunites-farallon-and-netopia-2/).
+ The Dallas FutureHome was the brainchild of [Portia Isaacson Bass](http://bassbasement.org/About/Portia.aspx), a computer scientist. The [*Los Angeles Times* noted in a September 1985 profile](https://www.latimes.com/archives/la-xpm-1985-09-22-re-18471-story.html) that Isaacson and her husband financed their computerized dream home with the $8 million sale of her company, Future Computing, Inc., to McGraw-Hill in 1984. The FutureHome was briefly featured in the 1987 movie *RoboCop* (which was filmed in Dallas). The house has been sold several times since 1985, with the most recent sale occurring sometime around 2019 for around $1.6 million. 
