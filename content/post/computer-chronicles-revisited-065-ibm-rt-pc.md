---
title: Computer Chronicles Revisited, Part 65 — The IBM RT PC
description: The Computer Chronicles discusses RISC.
date: 2022-08-06
categories:
- "Computer Chronicles Revisited"
tags:
- "RISC"
draft: False
---

During the run of *Computer Chronicles* thus far, IBM launched a number of products that failed to dominate their respective markets, including the PCjr, *TopView*, and token ring. But that didn't stop Big Blue from trying to recapture its early PC glory days. This [next *Chronicles* episode from October 1986](https://www.youtube.com/watch?v=DIccm7H3OA0) demonstrated yet another stumble in the form of the IBM RT PC, which despite the name was not part of its personal computer line, but rather an experimental minicomputer/microcomputer hybrid based on an architectural approach known as RISC.

Unable to avoid the obvious dad joke, Stewart Cheifet opened the program by showing Gary Kildall a [RISK game board](https://boardgamereviewed.com/reviews/risk-board-game-review/). But the topic of course was RISC, which stood for "reduced instruction set computing." Cheifet noted that major players like IBM and Hewlett-Packard were now involved in RISC. And while some people were saying RISC was the "wave of the future," others said it was "already a passe technology."

What did Kildall think? Kildall noted the current IBM PC line--the PC, the XT, and the AT--were all based on the Intel 8086 microprocessor, which succeeded the earlier 8-bit 8080 CPU. This left the industry with a "messy architecture" that faced some barriers, such as expanding the amount of addressable memory space beyond 640 KB. RISC gave us a new starting point. By using a simpler instruction set that took up less code space, that could make it easier to write compilers and ultimately software programs.

## H-P Bet on Speed Potential of RISC

Wendy Woods presented her first report, narrating some B-roll footage taken at a Hewlett-Packard laboratory. Woods said that in the search for faster and more powerful computers, improved hardware often took center stage while changes in architecture trailed behind. The new architectural design used in RISC relied on simpler instructions requiring fewer machine cycles.

Woods said in the early 1970s, IBM examined the kinds of operations most commonly carried out by a complex instruction set computer (CISC) and found that only about 20 percent of the simplest instructions represented 80 percent of the processing time. RISC architecture relied on those simple computational elements to execute most of its operations in a single cycle.

While RISC had made few inroads in the market thus far, Woods said, at least one major company--Hewlett-Packard--demonstrated its confidence in RISC by introducing a whole line of RISC-based machines as the next generation of its high-end computers. All computations except "load" and "store" took place in the data path. Inline subroutines could be called up for complex functions and assist processors operated when required for floating-point arithmetic and graphics.

Woods said the special nature of RISC design made it well-suited to engineering and scientific applications, where instructions of 4 bytes or less could be executed in one cycle. But while such applications demonstrated the advantages of RISC, some critics contended that the speed gained by reduced instructions could be wiped out by the longer data paths--and by the need to accommodate complex functions.

## RISC Is a Philosophy, Not an Instruction Set

For the first of three round tables, Dr. Joel S. Birnbaum and Dr. David Patterson joined Cheifet and Kildall. Birnbaum was a vice president at Hewlett-Packard. Patterson was a computer science professor at the University of California, Berkeley, and the researcher credited with coining the term RISC.

Kildall asked Patterson for some background on the origins of RISC and what made it different from traditional machine architecture. Patterson said the idea was simplicity, of going back to a "small is beautiful" philosophy. There were several origins to RISC, including work done at IBM during the mid-1970s as well as other research groups in California. But the basic idea was to make computers faster and more cost-effective.

Kildall pressed for a more specific comparison in speed between, say, an IBM PC-AT with an Intel 80286 CPU and a RISC-based machine. Patterson said researchers in the field believed that using the same resources, you could get a 2- to 4-times improvement in cost-performance with RISC compared to a traditional design. So given the same transistors that Intel used on the 286, you could theoretically build a machine like the AT that was 2 or 4 times as fast.

Cheifet asked Birnbaum about the 80/20 ratio--the same one that Wendy Woods mentioned earlier--regarding the percentage of instructions most commonly used by a CPU. Birnbaum said the notion was that computers spent most of their time, roughly 80 percent, doing a few simple things and did not do complex things very often. So if you optimized the machine to do the simplest things as well as possible--and to do the complex things as infrequently as possible--you might come out with a machine that for certain types of jobs would be more effective.

Kildall asked if RISC was a philosophy of machine architecture or a specific set of instructions. Birnbaum said it was the former. RISC was a style that differed depending on what you were trying to do. The main idea was not to add any complexity to the machine unless it "pays for itself" by how frequently that complexity was used. For example, a machine used in a scientific environment that required the heavy use of floating-point calculations might make a different set of trade-offs than another machine where that wasn't important.

Kildall asked Birnbaum where he saw RISC architecture as important to computing right now. Would it be a replacement for a desktop computer? Birnbaum reiterated there was no such thing as "RISC architecture." There was good engineering design of a computer. All computers should be designed by analyzing exactly what they do and the objectives of the person building the machine, and then incorporating that analysis into the specific design. It's turned out that a smaller number of instructions can, in fact, address a very wide range of applications and types of applications. That is the RISC philosophy. But there were other factors that went into a successful design. He noted that at Hewlett-Packard, his team spent about two-thirds of their time on issues that had nothing to do with the instruction set itself.

Kildall asked how users would be convinced to move to a new architecture like RISC given issues like software compatibility. Birnbaum acknowledged that H-P was trying to get its customers--as well as some other companies' customers--to move onto the new machines from at least three previous "families," each with their own instruction sets and compilers. So H-P had to provide a smooth migration path for these customers. For software written in a high-level language (like C), that could often be accomplished simply by recompiling the code, which retained most--but not all--of the features of the native-mode architecture. When people didn't have that capability, H-P offered a range of hardware and software tools that offered a "compatibility mode" to translate instructions from one architecture to another.

Cheifet turned to Patterson and asked him how he saw the evolution of RISC proceeding. Patterson said it was interesting how viable the RISC philosophy had turned out to be in many different fields. The original work was done on artificial intelligence and floating-point computations. Since then, several groups had done experiments that showed RISC designs could work well on various number-crunching applications.

## Defining the Market for RISC

The second round table featured Dr. William Frank King, the general manager of IBM's advanced engineering systems group, and Hugh Martin, a vice president with Ridge Computers. Also on set was the sole product demonstrated in this episode, the IBM RT PC. (RT PC formally stood for "RISC Technology Personal Computer.")

Kildall opened by noting that the RISC philosophy focused on the design of the CPU. But what about related concepts like parallelism, I/O, and things like that? Martin said that at Ridge, they concentrated first on the CPU but the entire machine had to be designed to be efficient. So Ridge spent a lot of time initially on I/O (input/output) performance to match the CPU's performance. And now that they had a simplified processor, they could examine parallel architectures. Kildall noted that DEC minicomputers like the VAX 11/780 were popular because they were good I/O processors. Did Martin see RISC architecture as a competitor for the VAX on that front? Martin said you needed a fast I/O system regardless of the type of computer. But he found that Ridge's machines were performing as well as the VAX in terms of I/O.

Kildall turned to King and asked about the RT PC. Specifically, Kildall pointed out there was actually a co-processor in the RT that could handle standard 80286-based applications. King said the RT ran between 1.6 and 2.1 million instructions per second and the 286 co-processor board ran at about one-third of that speed.

Cheifet asked King what market the RT PC aimed at. Who was actually buying this RISC machine? King said the tabletop version of the machine--the one on the set--was packaged primarily for people who needed speed and capacity above what the IBM PC and similar systems could support. Cheifet pressed who those people were. King said engineers, architects, and people in the insurance industry. Cheifet suggested that meant IBM saw a market for business applications on the RT and not just scientific ones. King said yes, the RT was marketed at "high-end" business applications.

Kildall then asked the inevitable question: How much did the RT cost? King said the machine sitting on the table cost about $10,000 and came with up to 4 MB of RAM and a 70 MB hard drive.

Kildall then decided to demonstrate the RT--relying on the "10 to 15 seconds of instruction" he received from King--specifically the machine's graphical interface. (The RT PC came with AIX, IBM's proprietary version of UNIX, running the X window system.) Kildall pulled up a window containing a document with a "technical illustration." He then selected an object in that illustration and rotated it in real time. Cheifet noted this required a lot of processing power.

Cheifet again brought up the issue of adapting software to the newer RISC-based machines. Did you have to write new software to run on the RT? King said no, most of the software that ran on this machine was written in a high-level language. So you needed compilers that could work with RISC architecture, but the compiler effectively "masked" the current software.

Repeating his earlier question to H-P's Birnbaum, Kildall asked King about IBM's strategy for moving applications over to the RT PC. King reiterated that it started by defining a set of compilers. But the price-performance of the RT still had to justify people moving their software over to it.

Cheifet asked Martin about Ridge's customer base, noting it was a much smaller company that had sold about 400 to 500 RISC computers. Who was Ridge selling those machines to? And what was their niche against giants like IBM and H-P? Martin said Ridge's niche was price-performance in the technical marketplace. For example, one of Ridge's customers was the computer graphics company Pacific Data Images-itself a subject of [multiple prior *Chronicles* episodes](https://smoliva.blog/post/computer-chronicles-revisited-046-kron-tv-usa-today-kcbs-radio-aurora-75-graphics-system/)--which had 12 Ridge computers doing its 3D rendering.

Cheifet asked King what was coming next. There were rumors of IBM releasing an "enhanced" RT PC. What changes could we expect? King said IBM never talked about future products. But invoking Moore's law, he saw a doubling of speed and capacity in the desktop personal computer market continuing every 12 to 14 months. If IBM planned to continue participating in this market--which it did--then they needed to find a way to sustain that improvement.

Kildall pointed out that recent speed gains from the Intel 286 and now 386 CPUs already seemed competitive with RISC. For instance, a 386 running at 24 megahertz was pretty close to the RT PC. King said the 386 processors available today actually ran at 16 megahertz. But he admitted that as the Intel architecture became faster, the RT PC would have to stay faster to justify its price. And that was IBM's goal.

## Using RISC to Design New Computer Chips

Wendy Woods returned for her final report, this time from ESL in Sunnyvale, California. Woods said ESL was designing the world's fastest systolic processor, a chip that could be used in everything from sophisticated listening devices to image processing of pictures from outer space.

ESL's needs required tremendous computing power, Woods noted, for which the company's engineers relied on a RISC-based minicomputer from Pyramid Technologies. Dr. Nickolas Dunckel of ESL told Woods the RISC computer enabled them to have a machine that ran much faster, which was very important because their programs took so long to run. The RISC machine was also very efficient in handling multiple users at the same time. He added that the particular instruction mix ESL got from its integrated circuit design--which relied on fixed-point rather than floating-point numbers--ran particularly fast on the RISC architecture.

Woods said that ESL was designing an integrated circuit with 62,000 transistors. The RISC computer was used to perform a thorough simulation and verification of that design before it was committed to silicon. Woods added, however, that even after two years of using the Pyramid machine, ESL was still not completely sold on RISC technology. Dunckel and his team believed that parallel processing offered similar advantages. But the bottom line was these types of engineering projects never had enough processing power and engineers were not married to any one technology when it came to getting their work done.

## Could a "Watered-Down" RISC Approach Still Win?

Regular contributors Jan Lewis and George Morrow joined Cheifet and Kildall for the final segment. Kildall opened by noting the computer industry had been reluctant to accept new architectures in the past. Would this be a problem for the RISC architecture? Lewis said it would be a problem. Not only would there be reluctance to accept a new architecture, but Lewis said she was personally skeptical about RISC, particularly with respect to its viability in consumer applications. She added that H-P and IBM's machines were effectively "watered-down" versions of RISC. They used some of the RISC principles but were not "true RISC machines." And some of the performance improvements seen in these machines may not be due to RISC but because of other factors like having more on-chip registers.

Morrow said, "Looking at it from a point of view of silicon, the richer register sets and the simplified instruction sets favored the use of silicon," which was a positive thing. On the negative side, he noted that we kept making new instruction sets, which was like inventing a new typeface every time you wanted to say something. What Morrow would really like to see is someone make a computer that could run anybody's binary without recompiling or translations or any of this stuff.

Cheifet followed up on Lewis' remark that the current RISC offerings from IBM and H-P were "watered down." What was the technical problem that prohibited a more complete RISC implementation? Lewis said there were a few issues. The first was that RISC proposed sending one instruction--each containing multiple simple instructions--per CPU clock cycle. But in practice, a machine like the RT required a lot of extensions, which made the actual performance closer to one instruction per 2.7 clock cycles. So we'd evolved from "RISC in the pure sense" to "RISC-like architectures" to "architectures using RISC principles" to "simplified instruction sets with on-chip registers."

Kildall asked about the first potential applications for RISC architecture. Lewis said it would largely be in the scientific community. Those applications didn't require the same amount of I/O, which was still a problem. The engineering and scientific community was also less "standards conscious" and therefore more willing to accept a new architecture.

Cheifet noted that despite the problems discussed by Morrow and Lewis, Hewlett-Packard was reportedly "betting" its entire computer division on RISC technology. Morrow disagreed with that characterization. He noted that part of H-P's investment was in transporting customers from their standard environments to something that was perhaps more flexible. And while he agreed with Lewis about the current drawbacks of RISC, he said better-written compilers would hopefully get us to the point where there were truly portable, high-level languages.

Kildall asked about the impact of other new CPUs coming onto the market such as the Intel 80386 and the Motorola 68030. Morrow noted the speed on the 68030 was especially impressive. So it was possible the traditional approach to computer architecture would continue to get better. Eventually, however, we'd get down to the point where "silicon is important," and on that front RISC beat CISC.

## H-P Delayed Bet on RISC Machines

Stewart Cheifet presented this episode's "Random Access," which was recorded in October 1986.

+ Hewlett-Packard said "software problems" would delay the planned shipment of its RISC-based Spectrum minicomputer until mid-1987.
+ IBM announced "upgrades and improvements" to the RT PC. The new RT Model 15 would feature improved networking capability, memory, and storage. Cheifet added that IBM was also cutting the price of the RT.
+ IBM transferred 2,000 employees into sales as part of a planned increase of its sales force by 5,000 people.
+ Apple reached a deal with Northern Telecom to enable the Macintosh to network over regular telephone lines. Cheifet said this would increase the Mac's networking speed by a factor of 18.
+ Lotus Development Corporation debuted its new AI-based *Hal* add-on for *Lotus 1-2-3* at the Info '86 show in New York.
+ At the recent Software Publishers Association conference in Washington, DC, a spokesman for Educational Systems Technology predicted that computers would "reverse the trend" of smaller classroom sizes. Cheifet said the prediction was that teachers could handle classes of up to 90 students using computer assistance.
+ Paul Schindler reviewed *Tornado Notes* (Micro Logic, $50), a note-taking and management program.
+ Gammalink announced a new $1,000 add-on board that lets a user send copy from a PC directly to a fax machine.
+ Federal Express eliminated its own fax service, *Zapmail*, due to heavy losses.
+ The [Overseas Security Advisory Council](https://www.state.gov/overseas-security-advisory-council/) started a BBS on international terrorism to provide information for American businessmen traveling abroad.
+ A "blind businessman" in Indiana developed *Rapsheet*, a talking spreadsheet that he planned to give away for free to blind users.
+ Researchers at Carnegie Mellon University said they were "making progress" on synthesizing protein molecules that could one day be used to create "molecular computers."

## Corporate Politics Likely Doomed the RT PC

As I alluded to in my introduction, the IBM RT PC was not a great success. While it wasn't a complete disaster like the PCjr, the RT series sputtered along for roughly four years before IBM moved on to a new line of RISC-based machines, the RS/6000, in 1990. And by that point, a number of other companies had successfully entered the nascent RISC market.

So what went wrong? Authors Charles H. Ferguson and Charles R. Morris documented the troubled history of the RT PC in their 1993 book, [*Computer Wars: How the West Can Win in a Post-IBM World*](https://archive.org/details/computerwarshoww0000ferg), which offered a detailed account of IBM's decline in the late 1980s based on numerous interviews with company insiders. What follows is largely summarized from their work.

As David Patterson noted during the broadcast, IBM began work on what he would later describe as RISC during the 1970s. More precisely, Ferguson and Morris credited IBM's early RISC work to John Cocke of IBM's Yorktown Heights (New York) Research Center. IBM kept Cocke's work secret for most of the 1970s. At the same time, Patterson conducted his own research into RISC concepts at Berkeley--aided by some graduate students who previously interned at IBM--while Dr. John Hennessy led a similar effort at Stanford University. Hennessy later co-founded MIPS Computer Systems, while Hennessy's work led to the development of the Sun Microsystems SPARCsystem. MIPS and Sun would effectively dominate the early RISC-based CPU market in the United States. (Patterson and Hennessy later shared the [2017 A.M. Turing Award](https://amturing.acm.org/award_winners/patterson_2316693.cfm) from the Association for Computing Machinery for their work in developing RISC.)

As for IBM, it may have been the first to research RISC ideas, but company politics stymied Cocke's initial attempts to actually bring a product to market. Indeed, Ferguson and Harris said Cocke developed an early prototype called ACS in 1968 that "incorporated early versions of the key RISC concepts." Management quickly killed ACS, however, because it was incompatible with its System/360 mainframe line, which was IBM's main product line at the time.

Sometime around 1974 or 1975, Cocke developed his next idea, the ServiceFree, which he claimed was 50 times faster than IBM's existing mainframe line, which by then was the System/370. But again, Ferguson and Harris said IBM killed Cocke's project so it could dedicate more resources to another (ultimately doomed) project called F/S.

Another guest from the episode, Joel Birnbaum, was Cocke's supervisor during this time. In 1976, Birnbaum gave Cocke the go-ahead to start work on yet another CPU prototype, which was eventually named the IBM 801 after the number of the building where it was developed. Ferguson and Harris noted the creation of the 801 was "usually designated as the invention of RISC."

But the IBM 801 was not yet ready for the market. IBM's mainframe division continued to oppose the very idea of RISC processors. Despite this, the company's Austin division, where W. Frank King was the general manager, decided to take up the 801's development. Using the 801 design the Austin team produced the Research/Office Products MicroProcessor (ROMP) in 1980. Ferguson and Harris noted this took place at least a year before Patterson designed his first RISC processor at Berkeley.

There was at least one senior IBM executive, Bob Evans, who supported the idea of creating a new company-wide architecture based around the ROMP. Ferguson and Harris said that even at the height of the IBM PC's success, Evans was concerned about the “potential danger from clones if Microsoft and Intel controlled the PC architecture." Cocke's team managed to develop a prototype compiler--the Austin Compiler System--which made it theoretically possible to run the same code on either the ROMP or the existing System/370 mainframes. But there was a caveat: The Austin compiler required at least 10 MB of RAM, which was too much for the Series/370 to spare, as the mainframe's design limited it to a maximum of 16 MB of RAM. “[A]lthough RISC’s potential was beyond dispute," Ferguson and Harris said, "no one was prepared to tell the mainframe division to fix the 370’s memory or move on to a better architecture.”

By the end of 1983, IBM's senior management abandoned the idea of a company-wide RISC standard. But they still approved two RISC-related projects. The minicomputer division would handle one project, dubbed "Fort Knox," while Austin would start work on a ROMP-based workstation. Although called "Olympiad" at this point, the latter project would eventually become the IBM RT PC. (Ferguson and Harris said Evans was dissatisfied with this "compromise" and left the company.)

This was not the end of corporate politics, Ferguson and Harris noted. There were several key decisions that ended up seriously crippling the RT. First, IBM decided to manufacture the ROMP CPUs themselves at its Burlington, Vermont, factory. Up to this point, Burlington primarily focused on memory chips and in fact had no prior experience making microprocessors. Ferguson and Harris said the CPU that Burlington finally produced was "deficient," but management never considered outsourcing the production to an established manufacturer like Intel or Motorola.

Second, although the shipped RT PC ran a UNIX-like operating system, it wasn't exactly UNIX. At the time, UNIX was owned by AT&T, which IBM still viewed as a potential competitor in the computer market. Accordingly, Ferguson and Harris said IBM management decreed that its new ROMP machine "would have a custom IBM software layer, called the Virtual Resource Manager, standing between the ROMP and UNIX." This way, IBM could "expand" the virtual layer into a proprietary operating system later if AT&T tried to assert too much control. Unfortunately, this virtual layer also slowed the RT's performance "badly" and delayed the project's development by another year.

Finally, there was another IBM division that had convinced management to adopt a company-wide graphics standard. As you might expect, this new standard was largely dictated by the demands of the mainframe division. This added to the RT's delays. On top of that, the people in charge of the RT had something of an identity crisis. Frank King's Austin division largely focused on office products like typewriters and standalone word processors. This led to repeated flip-flopping over whether to position the RT PC as an office machine or a workstation targeting the scientific and engineering communities. (King's response to Stewart Cheifet's questioning suggests this issue was never quite resolved.)

When IBM finally released the RT PC in April 1986, the public response was underwhelming. IBM's competitors certainly weren't running scared. Compaq President Rod Canion told Wendy Woods' *Newsbytes* that the RT PC would fail because it wasn't "fully compatible" with the existing IBM PC line and that compatibility had "taken on a life of its own, independent of IBM." Robert Wight, an executive with Maynard Electronics, a major developer of IBM add-ons, [told *InfoWorld*](https://books.google.com/books?id=oi8EAAAAMBAJ&pg=PA11) that his company didn't "consider the RT a major machine." Other add-on manufacturers were similarly unimpressed, although several did eventually produce peripherals for the RT.

As Stewart Cheifet reported during "Random Access," by late September 1986 IBM was already rushing to put out a new version of the RT. The Model 15 was priced lower than the original RT--but it still cost $10,050. At the same time, IBM cut the price of its original RT models between 20 and 32 percent. IBM continued to update the line through the end of 1989, but as Ferguson and Harris concluded, the entire RT project "was an embarrassment--years late, with capabilities weirdly mismatched to its proclaimed market, very expensive, and most damningly, slow." They added that IBM's upper management was "shocked" when Sun Microsystems' SPARCstation, released in late 1986 and based on Patterson's work at Berkeley, "decisively outperformed the RT PC, often by several factors, on every count."

## Notes from the Random Access File

+ This episode is available at the [Internet Archive](https://archive.org/details/RISC1986) and has an original broadcast date of October 2, 1986.
+ Dr. Joel S. Birnbaum spent 15 years at IBM where, as previously noted, he oversaw the company's early RISC research. He joined Hewlett-Packard in 1980 as a vice president, where he also served two stints as director of H-P Labs. Birnbaum remained with H-P until his retirement in 1999. In retirement, he also served a number of years on the board of trustees for the [SETI Institute](https://www.seti.org/).
+ [Dr. David Patterson](https://research.google/people/105290/) spent nearly 40 years as a computer science professor at Berkeley, retiring in 2016. Patterson is currently a Distinguished Engineer with Google Research and vice chair of the board of directors at RISC-V International, a Switzerland-based nonprofit that promotes a newer, open RISC standard.
+ Dr. William Frank King left IBM in the late 1980s to join Lotus Development Corporation, where he was a senior vice president. In 1992, King became president and chief executive officer of PSW Technologies, Inc. PSW, which later renamed itself Concero Inc., originally provided software services to large vendors. Indeed, IBM was PSW's biggest client in the mid-1990s, accounting for 52 percent of sales. As Concero, the company pivoted in the late 1990s to "e-business solutions" for Internet and interactive television companies. King left the CEO's role in 1998 but remained on the board until the [company's dissolution in 2003](https://www.sec.gov/Archives/edgar/data/0001030487/000119380503001157/e300799_8k-concero.txt). He's been a private investor since then and served on a number of corporate boards, including the intellectual property investment firm [Inventergy, Inc.](http://www.inventergy.com/)
+ I didn't learn much about Ridge Computers except that it dissolved in April 1990. [Hugh Martin](https://www.linkedin.com/in/hugh-martin-403b939/details/experience/) left Ridge in 1988 to join Apple for three years. In 1991, he became president of the 3DO Company, Electronic Arts founder [Trip Hawkins'](https://smoliva.blog/post/computer-chronicles-revisited-043-trip-hawkins-john-merson-ben-anixter-richard-obrien/) attempt to create a new video game hardware and software manufacturer. When [3DO sold off its hardware business to Samsung in 1997](https://www.wired.com/1997/04/3do-consoles-r-not-us/), Martin left the company. He's served as CEO of a number of tech ventures since then, most recently [Lacuna Technologies](https://www.lacuna.ai/), a developer of mobility software for cities.
+ Hewlett-Packard's Spectrum program later became known as its Precision Architecture or PA-RISC series, which remained in production in various forms until 2008.
+ Bill Grimm was the developer of *Rapsheet*. According to a September 1986 Associated Press report, Grimm lost his sight due to a motorcycle accident in 1974. He started Computer Aids Corporation to develop a number of software programs targeting blind users, including "Small Talk, a five-pound, talking computer that fits in a briefcase."
+ As I mentioned in the recap, the IBM RT PC demo featured the X Window System. The X Window System--also known as X11--continues to be used today in many UNIX-based operating systems, including the Fedora laptop that I use to write this blog. (No, I haven't switched to Wayland!)
+ The most notable omission from this episode was any mention of Acorn Computers Ltd., a United Kingdom company that introduced its own RISC-based microprocessor in 1985. Originally known as the Acorn RISC Machine (or ARM), Acorn's work would eventually set a key standard for RISC-based architecture throughout the tech industry, including most of the smartphones in use today and the recent line of Apple Silicon Macs.




