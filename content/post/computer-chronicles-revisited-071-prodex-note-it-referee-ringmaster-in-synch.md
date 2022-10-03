---
title: Computer Chronicles Revisited, Part 71 — Prodex, Note-It, Referee, Ringmaster, and In-Synch
description: The Computer Chronicles discusses RAM-resident software.
date: 2022-10-01
categories:
- "Computer Chronicles Revisited"
tags:
- "RAM Resident Software"
draft: False
---

Operating systems like the original MS-DOS were not capable of multitasking--they could only run one program at a time. But you could fake multitasking by taking advantage of the "terminate and stay resident" (TSR) system call in DOS. Essentially, a program that used this call was not cleared from RAM when a new program loaded and remained available to the system until the next reboot.

Such "RAM resident software" was the subject of this [next *Computer Chronicles* episode from November 1986](https://www.youtube.com/watch?v=xV2rxImyGYE). Stewart Cheifet opened the program by telling Gary Kildall that when Borland first released *Sidekick*, it was a big deal that you could pop-up a simple calculator on your screen using a RAM resident program. Cheifet then showed a physical calculator--an HP-12C financial calculator--and noted there was now a computer version of the device, which was also available as a TSR program.

Cheifet said the problem with these types of programs was that they kept "bumping into each other" in memory. Why did that happen? Kildall explained that "terminate and stay resident" was an internal programming function within DOS. When it was first invented, he didn't think anyone knew what it would actually be used for. But a program like *Sidekick* basically intercepted information coming in from the keyboard. If it was for *Sidekick*, that program would process it. Otherwise, *Sidekick* threw the information "over its shoulder" to DOS or another program. The problem was that when multiple programs tried to use the same keyboard information they could end up conflicting or overwriting one another.

## Juggling RAM Manually to Mimic Multi-Tasking

Wendy Woods presented her first remote segment, which profiled author Bob Cowart, who wrote articles and books about using computers, such as *The ABC’s of dBase III Plus*. Woods said that in order to meet his deadlines and keep up to date with the latest information, Cowart found a way to keep several programs loaded simultaneously in his computer's RAM.

Cowart explained that he basically divided up the system RAM into three partitions, which all ran DOS independently. It wasn't a multitasking system as only one program was active at any one time. Woods said that for his latest *dBase III* book, Cowart wanted access to *WordStar*, *dBase III*, and a screen capture program all at once. He managed to juggle all three, but it wasn't easy. Cowart said it was like cooking--if you didn't do the recipe in the right order, things wouldn't work out. And he only found a workable order of loading the programs through experimentation. The first step was deciding which keys you wanted to control each program and if you could redefine them in a way that was workable and convenient.

Woods said this process required the user to have a good memory and some sense of organization. Programs must be loaded in a certain order--and assigning the same keys to different functions could lead to disaster. But if you were careful, manipulating your computer's live memory could lead to some impressive, tangible results.

## Adding Notes to Lotus 1-2-3

Dale Leatherman and David Whitney joined Cheifet and Kildall for the first studio round table. Leatherman was president of Prodex Development, which produced a TSR program also called *Prodex*. David Whitney was a developer with Access Learning Technology Corporation, which developed *Note-It* for Symantec's Turner Hall subsidiary.

Kildall reiterated that the idea behind a TSR program was that it "stayed behind the scenes" and could be called back up by the user as needed. For example, *Note-It* worked in the background as a utility for *Lotus 1-2-3*. Whitney provided a demonstration. He started by entering a command at the DOS prompt to start *Note-It* before *1-2-3*. (Cheifet pointed out this meant that *1-2-3* was actually running resident inside of *Note-It*.) Whitney emphasized this approach was practical when dealing with a TSR program that only needed to run with one particular application, as *Note-It* wouldn't take up memory when running a different program, such as a word processor.

Whitney loaded a sample *1-2-3* worksheet, a financial statement for a fictional lemonade stand. He explained the purpose of *Note-It* was to attach little notes to individual cell locations within the worksheet. He pressed a series of three keys to highlight the cells on the sample worksheet that currently had attached notes. He then pulled up a note on one of the cells. This "woke up" *Note-It* and suspended *1-2-3* within the computer's memory. The *Note-It* interface itself worked just like any other word processor. You could also press a key to "lift" the note off the screen for a moment to look at the underlying worksheet as you typed.

Whitney added that one of the special features of *Note-It* was that if you moved a cell attached to a note, that note would follow to the cell's new location. He also demonstrated a command to search for a particular text string (up to 32 characters) within all of the notes in a document. This enabled the user to create a "text dimension" for documenting the spreadsheet.

Cheifet then asked Leatherman about his company's product, *Prodex*, which Leatherman had characterized as a "second-generation" TSR program. What did he mean by that? Leatherman said the first generation included "pop up" tools like calculators and simple calendars. He felt that wasn't good enough for business professionals. They needed tools that matched the way they worked. This was the target market for *Prodex*.

Leatherman provided a demonstration. Leatherman set up a hypothetical scenario where Kildall had just called him on the phone. Leatherman then pulled up a record of his notes of previous calls with Kildall. He hit a key in *Prodex* to bring up a telephone directory. Hitting ``K`` pulled up a list of names that started with that letter, including Kildall. Leatherman then hit ``F10`` to bring up a command menu with a series of choices (similar to *1-2-3*) that led him to a folder with various notes of his prior conversations.

Kildall asked if you could actually dial a phone from *Prodex*. Leatherman said you could. Leatherman did a mock demo of that function, which was called up by pressing ``F9``. He then showed another list of notes involving a different contact. Leatherman emphasized this would help a business person "clear their desk" of paper and provide instant access to information. Leatherman said you could also log a call by pressing ``F8`` at the beginning or ending of the call.

## AST Surged on Sales of Multi-Function RAM Boards

Wendy Woods presented her second remote segment, this time focusing on AST Research, Inc., in Irvine, California. Woods said that to run more TSR programs, you needed more memory. And over one million users now used AST's Six Pack Plus expansion cards, which provided extra RAM combined with a clock, calendar, extra ports, and enhanced graphics for the PC. Woods said that AST was doing so well that it not only weathered the computer industry's recent slump but had actually doubled its income over the past year.

AST's Tony Paradiso told Woods that a lot of it came down to market timing. He noted that even now, IBM still did not provide a multi-function card like the Six Pack Plus. Indeed, AST was one of the first companies to provide that level of multiple functionality in a card that only took up a single expansion slot.

Woods said the recent appeal of AST's RAM boards had to do with multitasking, i.e., the ability to run several programs at once, such as a word processor with a spelling checker. AST bundled *DESQview*, an operating environment that acted like a "traffic cop," with its cards. This made it easier for a computer to switch between programs. And even as AST diversified into other types of products, the RAM cards still accounted for 40 percent of its business.

## The Problem of TSR Conflicts

Robert Luhn, an associate editor at *PC World* magazine, joined Cheifet and Kildall for the next studio segment. Cheifet said Luhn was there to demonstrate the problems that can arise when different TSR programs started "bumping into" one another. Luhn said there were a number of symptoms that could arise with TSR programs. Some of them were minor. One of the first things that could happen was that a program simply stopped dead and waited for some sort of keyboard input, which he demonstrated.

Luhn pulled up *WordStar* on the demo computer. He said there were actually three or four programs now loaded into memory. This was common, he noted, as most users couldn't solve all of their problems with just one TSR program. Kildall asked if the order in which a user loaded the programs mattered. Luhn said it certainly could make a difference. One of the first pieces of advice he gave to someone running several programs was that changing the loading order could sometimes change the results.

Luhn then called two TSR programs on top of *WordStar*, causing the system to freeze. He then tried to pull up a third program and received an error beep. He then tried calling the programs up in a different order, but that didn't work either. The programs simply couldn't agree on how to do things, especially since they each wanted to capture the same keystrokes. Kildall asked if this problem came down to a lack of standards. Luhn said the issue was that software developers had to follow too many standards. There were multiple types of hardware to support and DOS itself changed every couple of years.

Another typical problem for users, Luhn said, was programs like *WordStar* and *dBase* had a "run" utility to execute programs within those applications. But you couldn't run TSR programs with these utilities. For example, he tried to execute *Sidekick* using the *1-2-3* run command and nothing happened. (Well, the machine froze.)

Kildall asked if the move towards graphical user interfaces would help resolve these problems. Luhn said that most of the TSR programs were designed for character-based interfaces. So if you tried to pull up these programs inside a GUI it would still lead to system conflicts. This would be an especially big problem for people who wanted to use TSR programs like *Sidekick* inside of something like *Microsoft Windows*. But as adoption of GUIs became more common, that would likely make TSR programs redundant and unnecessary.

## How Could You Resolve TSR Conflicts?

For the final segment, Richard Kraus and Chip Rabinowitz joined Cheifet and Kildall. Kraus was director of product development with Persoft, Inc., which developed *Referee*. Rabinowitz was the director of engineering for New York-based American Video Teleconferencing Corporation (AVTC).

Kildall asked Kraus about *Referee* and how it could reduce conflict between TSR programs. Kraus set up a demonstration involving a TSR program and a word processing application called *XyWrite*. He said there was a particular conflict with a prior version of *XyWrite*, which that program's developers resolved by coming out with their own utility called *XyKeybaord*. That program was supposed to make it easier to run TSR programs with *XyWrite*. But it turned out that *XyKeyboard* didn't work with a specific TSR program from Borland called *Superkey*. The result was that every keystroke the user made appeared twice on the screen.

Kraus explained that *Referee* allowed the user to control TSR programs. The user could see the order in which each program loaded and how much memory it used. It even allowed you to unload a particular TSR program and free up its memory. He rebooted the computer and loaded a portion of *Referee* that watched him load the same programs as before. This time, loading both *XyWrite* and *Superkey* did not produce the double-keystroke problem. He explained that *Referee* resolved the issue by temporarily disabling or deactivating loaded TSR programs. This prevented the disabled program from interfering with the other programs in memory. While *Referee* did this in the background without any user input, Kraus showed there was a menu that allowed the user to control the software directly and see what programs were loaded and active.

Cheifet then turned to Rabinowitz and asked how his project, *Ringmaster*, proposed to address this same TSR conflict problem. Rabinowitz said that *Ringmaster* was a series of standards for TSR developers to follow. It wasn't so much a different solution than *Referee* but actually worked hand-in-hand with it. (He noted that several *Referee* developers also contributed to the *Ringmaster* project.)

Cheifet asked how *Ringmaster* specifically addressed the problem. Rabinowitz said the main reason for the problem is that every program loaded was watching the keyboard at the same time. With the *Ringmaster* standard, that program would watch the keyboard alone, and when another program wanted the input, *Ringmaster* would pass it on. The developers of TSR programs would obviously have to make their software work with this protocol.

Cheifet noted that Rabinowitz was one of the first developers to put together a product using the *Ringmaster* standard. He asked for a demonstration of that product, *In-Synch*. Rabinowitz said *In-Synch* was "desktop teleconferencing" software. It was a TSR program that allowed multiple users to work on the same *Lotus 1-2-3* spreadsheet at the same time remotely. In a demonstration, Rabinowitz and a colleague in New York both edited the same *1-2-3* worksheet at the same time.

## Everything's Coming Up 386 at COMDEX

Stewart Cheifet presented this week's "Random Access," which was recorded in November 1986.

+ IBM reported that it sold more PCs in September 1986 than in any previous month in its history.
+ One investment firm upped its projections for the growth of annual PC sales from 20 to 25 percent.
+ The fall COMDEX show recently ended in Las Vegas. Cheifet said the highlight of the was the Intel 80386, with six vendors showing off new machines that took advantage of the microprocessor.
+ In other COMDEX news, IBM reported "healthy" sales of its PC Convertible laptop, saying it could not keep up with demand. Cheifet said Toshiba reported similar demand for its portables.
+ NEC announced its own new portable, the MultiSpeed, which the company claimed was the fastest laptop on the market, capable of running at 9.5 Mhz.
+ China unveiled its own PC-AT compatible at COMDEX, the Great Wall PC, and an XT compatible retailing for $686.
+ Epson announced a printer-scanner hybrid that allowed the user to put a scanner cartridge in place of the traditional printer ink ribbon.
+ Paul Schindler reviewed *IQ Test* (Rational Designs, $40), a not-exactly-scientific intelligence test.
+ Xerox announced PC Typewrite, a hardware-based spell checker that beeped at users when they misspelled a word. (This product was featured in a later *Chronicles* episode.)
+ MasterSoft announced *Word for Word*, a program that converted text and formatting commands between different word processing programs.
+ Xerox announced a $5 million grant to create a new center for learning methods in Palo Alto, California, which would focus on creating AI-based systems for adult literacy and job training.
+ NASA's Marshall Space Flight Center unveiled a new astronaut module for future space flights, featuring 18 talking on-board computers known as "George," which would help diagnose repairs. (The Marshall Center is named for Gen. George C. Marshall.)

## An Early Precursor of Google Docs?

I don't have much to say about the programs that appeared in this episode. The need for RAM resident software largely disappeared after the release of Windows 95. Indeed, preemptive multitasking was already well on its way to mass adoption in later 1980s releases of MS-DOS and competitors like Digital Research's Concurrent DOS.

But in 1986, TSR programs--and programs to manage TSR programs--were still in high demand. John Walkenbach, [reviewing *Referee* for *InfoWorld* in August 1986](https://archive.org/details/bub_gb_Xi8EAAAAMBAJ/page/n39), gave that $70 program top marks, noting that it was "well worth the price" if you had to run two or more TSR programs at once, as he didn't experienced a single system crash. He added, however, that *Referee* was incompatible with existing multitasking environments like *Windows*, *GEM*, and *DESQview*.

*Prodex* also received qualified praise from reviewer Michael J. Miller in an [August 1987 *InfoWorld* column](https://books.google.com/books?id=0DsEAAAAMBAJ&pg=PA63). Miller described the $90 *Prodex* as "rather single-minded" but "actually very sophisticated" when it came to managing a telephone directory and logging calls.

But perhaps the most intriguing demo from this episode was *In-Synch*, a program that seemed to offer an early form of simultaneous multi-user file editing that is now commonplace with services like Google Docs. As M. David Stone [explained in a March 1987 review for *PC Magazine*](https://books.google.com/books?id=_Bg1jlRSiQMC&pg=PA253), while there were other programs on the market that let one user send information from their application to a user on a second computer, *In-Synch* actually made it possible to run "the same program on both computers simultaneously, sending the keystrokes in both directions." Stone said the software worked remarkably fast--there was no "noticeable delay" when connecting two using a 2400-baud modem--but he did run into problems with the machines frequently falling out of sync due to overrunning the keyboard buffer. That said, he praised *In-Synch* for its primary intended use of assembling and performing slide-show presentations remotely. (American Video Teleconferencing Corporation, which published the program, was as the name suggested a business that designed and installed video conferencing facilities.)

## Notes from the Random Access File

+ This episode is available at the [Internet Archive](https://archive.org/details/RAMResid1986) and has an original broadcast date of November 18, 1986.
+ Bob Cowart's first job in the tech industry was as a service technician with North Star Computers, an early manufacturer of CP/M microcomputers. He parlayed that experience into writing a column for [Stan Politi's *Computer Currents*](https://smoliva.blog/post/computer-chronicles-revisited-067-boston-computer-exchange/) and working as a consultant specializing in *dBase*. This in turn led to him writing his first computer book about *dBase*. Cowart went on to write more than 40 computer books. In recent years, Cowart has maintained a [personal blog](https://bobcowart.blogspot.com) detailing his diagnoses with Lyme Disease and Parkinson's Disease.
+ David Whitney co-founded Access Learning Technology Corporation in 1983. The company had a short lifespan and was no longer in business by early 1988.
+ [Robert Luhn](http://www.robertluhn.com/) had a long career as an editor and writer. He served as editor in chief at the aforementioned *Computer Currents* from 1994 to 2000. During the 2000s he was executive editor for O'Reilly Media's consumer book group and later spent a decade as director of communications for the [National Center for Science Education](https://ncse.ngo/).
+ [Richard Kraus](https://www.linkedin.com/in/rick-kraus-9901a24/details/experience/) remained with Persoft until 1991. Since then he's worked primarily in management consulting.
+ Former AST Research executive [Tony Paradiso](https://www.linkedin.com/in/tony-paradiso-06950/) currently serves as CEO of [E3 Go Green](https://www.e3gogreen.com/), a solar energy startup based in Maine.
+ Chip Rabinowitz led a committee of programmers that developed *Ringmaster* as what was described at the time as a "public domain" standard for resolving conflicts among TSR programs. (Today this would likely be an open source project.) Although early reports in the tech press suggested that *Ringmaster* would soon emerge as a "de facto standard," I couldn't find any information about the protocol's ultimate fate.
+ Surprisingly, Hewlett-Packard still sells the [HP-12C calculator](https://www.hp.com/us-en/shop/pdp/hp-12c-english-calculator) that Stewart Cheifet demonstrated during the studio introduction. The calculator, first produced in 1981, is HP's longest-selling product.
