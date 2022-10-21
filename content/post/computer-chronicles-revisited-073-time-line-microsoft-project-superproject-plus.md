---
title: Computer Chronicles Revisited, Part 73 — Time Line, Microsoft Project, and SuperProject Plus
description: The Computer Chronicles discusses project management software.
date: 2022-10-21
categories:
- "Computer Chronicles Revisited"
tags:
- "Project Management Software"
draft: False
---

Project management software was in the midst of a boom in the late 1980s. According to a May 1987 report from Wendy Woods' *Newsbytes*, one company claimed that sales of project management software had increased an astounding 315 percent from February 1986 to February 1987. This likely reflected the growing adoption of minicomputers in offices and large organizations, and the fact such PCs were now powerful enough to handle complex software that had once been the exclusive province of larger mainframes and minicomputers.

This next *Computer Chronicles* episode from November 1986 was all about project management software. Stewart Cheifet opened the program by showing George Morrow, this week's co-host, *MacProject*, which as you can probably guess was a project management program for the Macintosh. Cheifet described *MacProject* as a "series of spreadsheets." So why did someone need specialized project management software as opposed to just using multiple spreadsheets? Morrow retorted that years earlier, people said the same thing about spreadsheets, i.e., they were just specialized databases. And while you could do project management with multiple separate spreadsheets, that would involve a lot of programming just to get the spreadsheets to talk to one another. Using project management software meant you didn't need to be a programmer. Cheifet agreed and quipped, "Nobody wants to be a programmer, we know that's a lot of headaches."

## Keeping the Space Telescope (Sort of) On Time

Wendy Woods presented her first remote segment from Lockheed Corporation in Mountain View, California. Lockheed was overseeing construction of what Woods said was "one of NASA's most ambitious projects," the Space Telescope, which began in 1978. (Woods is referring here to the [Hubble Space Telescope](https://hubblesite.org/), although she never used that name.) Once anchored in orbit, the mammoth telescope would detect objects 50 times fainter than those observable from Earth, expanding the "visible universe" by 350 times.

To plan and manage a project of this complexity, Woods explained, Lockheed used a high-level project management system called *Metier Artemis*. The system was based on CPM, or *critical path method* (not to be confused with Digital Research's CP/M operating system). CPM established the proper order and relationship of each individual task.

Woods said that CPM itself was an extension of the PERT chart, i.e. the *program evaluation review technique*. On a computer screen, this translated to a network of boxed events interconnected according to their priority and scheduled completion. The "critical path" was the main route to completion of the project, from which lesser tasks branched off.

Lockheed originally planned 10,000 activities for the Space Telescope, Woods said, but that quickly expanded to over 30,000, each of which might have to be changed due to time and resource constraints. Before *Artemis*, scheduled changes could take 4 to 5 months. Now they could be done in a few days.

Sadly, Woods noted, the Space Telescope's original launch date in early 1985 was postponed due to the budget shift from peacetime space exploration to developing new space weapons. Today, the telescope sat idle waiting for the next Space Shuttle mission--and perhaps a new era of humanitarian space research.

## Battle of the Gantt Charts

David Bryan and Jim Dunningan joined Cheifet and Morrow for the first studio round table segment. Bryan was vice president of product marketing with Breakthrough Software, which published *Time Line*. Jim Dunnigan was Microsoft's project manager for its, uh, project management software, *Microsoft Project*.

Following up on the introductory discussion, Morrow asked Bryan to explain project management software to someone who was already familiar with spreadsheets. Bryan said a spreadsheet could just be a column of numbers that you added up. Similarly, a project manager had the same kind of components in it, except instead of numbers they worked with tasks. The tasks related to one another in the same way as numbers in a spreadsheet. As you adjusted the time for one task, the software automatically adjusted the times for all the other tasks, which in turn changed the project's completion date.

Cheifet asked Bryan to demonstrate *Time Line*. Bryan showed a sample project--a kickoff for an advertising campaign--where the software displayed a sample chart of the various tasks involved, such as market research and client presentation. The software also displayed a list of the people who would be working on each of those tasks. There was also a bar chart (known as a Gantt chart) on the right indicating when those tasks were scheduled to take place.

Cheifet asked how these charts actually helped someone handle a project. Bryan said one thing you could see was that there were three gaps in the schedule, where the estimated tasks were expected to be two days late in their completion, as indicated by two right-facing arrows on the chart. He explained that this was a real common problem in project management. One way to address this would be to stack multiple tasks to overlap--as opposed to finishing them back-to-back--to open up two additional days for the task that required more time. Bryan then showed how to do this using *Time Line*. The software could also produce "before" and "after" charts.

*Time Line* could also flag "resource problems," Bryan said. He pulled up a histogram showing the schedules for an account executive and their assistant. The chart indicated the executive was "overbooked." Morrow clarified that this was triggered by the previous change to overlap tasks. To resolve this new problem, Bryan went back to the Gantt chart and selected the executive in question. He could then add the executive's assistant as an additional "resource" and reallocate the executive's time to eliminate the resource conflict.

Cheifet then turned to Dunnigan and asked him how *Microsoft Project* differed from *Time Line*. Dunningan said *Project* was different in a couple of ways. One difference was that *Project* had individual resource calendars. So if a particular employee was going to be on vacation for two weeks, or a piece of machinery was unavailable for several weeks, you could go into the software and block that time out on the resource's individual calendar. The program would then take that unavailability into account when creating the project schedule.

Cheifet then asked Dunnigan for a demonstration of *Project*. Dunnigan pulled up a sample project file, which like *Time Line* displayed a Gantt chart. He noted that *Project* used a command-line interface on the bottom of the screen, which was similar to other Microsoft products. He then showed how to edit items in the Gantt chart itself.

Morrow asked Dunnigan about the types of problems Microsoft had providing telephone support to customers for *Project*. Was it more difficult than, say, word processors? Dunnigan said they got a lot of questions from people who were new to project management. They may have previously scheduled projects using a database or spreadsheet and they had questions about concepts like CPM.

Cheifet asked Dunnigan how you would go about solving a hypothetical problem in *Project*. Dunnigan pulled up a list of resources. The system would beep if he tried to overschedule a particular resource. Dunnigan then showed how to resolve that problem, which was similar to Bryan's earlier method for handling the same issue in *Time Line*. Cheifet pointed out that *Project* also showed the costs associated with each resource. Dunnigan said this made it possible to cost out the entire project. Morrow clarified those cost projections would automatically update as resources were added to the project.

Cheifet asked about the prices for these project management packages. Dunnigan said the suggested retail price of *Project* was $395. Bryan said *Time Line* sold for $495. Morrow noted a few years ago, this type of software cost $100,000 and ran on mainframes. Did customers believe you could get the same performance on a microcomputer? Bryan said initially many customers had their doubts but they were resolved after trying the software. Morrow interjected--and Bryan concurred--this should make the vendors of the $100,000 software nervous.

Cheifet asked who was actually using project management software. Bryan said that *Time Line* was most commonly used at the "bottom level," i.e., the spot where a user was responsible for a sub-project or sub-assembly to manage that particular area. *Time Line* also linked to another product called *OpenPlan*, which could handle much larger projects with hundreds of thousands of tasks.

## Using Project Management Software to Design Software

Wendy Woods returned with her second remote segment, this time from The Droid Works, a company started by filmmaker George Lucas to develop a commercial videodisc-based editing system known as the EditDroid. Woods explained that the EditDroid's software could handle up to eight separate sources of videos at once. This in turn required the use of project management software.

Woods said that Michael O'Brien, a senior software engineer at The Droid Works, and his team designed the EditDroid's software using *Micro Planner*, a Macintosh project management program. O'Brien said that before using *Micro Planner*, much of his team's planning was done *ad hoc*, i.e., writing things on the backs of envelopes. The planning software had turned around this whole process for the better, he said.

*Micro Planner* required a person to sit down and think about a project in advance. In turn, the software provided a clear path to achievement of results. It may seem strange that software was being used to manage a software project, Woods quipped, but as O'Brien told her, the business of creating software had traditionally been one of the least well-planned activities in the world.

## Could "Hip Shooters" Benefit from Project Management Software?

Nancy Ann Twomey and Glenn Katz joined Cheifet and Morrow for the final segment. Twomey was a product marketing manager with Computer Associates, which published *SuperProject Plus*. Katz was director of the construction executive program at Stanford University.

Morrow asked Katz for some background on project management software. Katz said it arose out of the U.S. Department of Defense in the 1950s. The Navy needed to develop software to manage some of their projects like the Polaris missile. Since then, project management had expanded into other areas, notably the construction industry. Now it was continuing to work its way into a number of new markets.

Cheifet asked Twomey about those new markets. Twomey said project management was used in a variety of applications ranging from the production of a television show like *Computer Chronicles* to developing large charity drives. She said that project management software was now widely used in the banking industry as well. Morrow added that many software companies were using such programs themselves.

Cheifet asked Twomey for a demonstration of *SuperProject Plus* and how it differed from the two programs seen in the previous studio segment. Twomey said the goal of *SuperProject* was bringing in new users, so the software included an extensive on-line help system and glossary of key terms. For her demonstration, she pulled up a sample sales promotion program. She explained the program worked off a pull-down menu structure and offered nine different views of the project information.

Twomey displayed a PERT chart view of the sequences of tasks for the sample project. She explained how you could create a new project and layout individual tasks using boxes connected by arrows. Morrow noted there were different colors indicating different functions. Twomey said red diamonds indicated critical tasks and blue diamonds were for non-critical tasks. Cheifet then asked Twomey to demonstrate some of the software's other views. Twomey highlighted one feature of the program called "resource leveling," which basically went through all of the available resources and came up with a schedule to finish a specified task.

Cheifet asked Katz how big a project needed to be before using this type of software. Katz said size wasn't the critical consideration as much as whether or not you could use the information that the product provided. The type of manager who could use project management software was one who could, given some knowledge of how to manage projects, make a good decision about whether to change the order of the projects, allocate additional resources, have people work overtime, et cetera. But in terms of size, you could have a project with just two people that would benefit from the software, all the way up to multi-million dollar construction projects.

Morrow noted there was a lot of "emotion" associated with project management software that you didn't see with something like spreadsheets. Why did Katz think that was? Katz said it was because these types of programs got at the heart of how you managed people, and managers took that very personally. A lot of the products wanted you to become very rigid or precise in following certain rules to plan a project. Yet some of the best project managers were people who "shoot from the hip."

Morrow followed up, asking Katz how he would teach someone like that--i.e, a hip-shooter--and help them use project management software to be a "better hip-shooter." Katz said the important thing was how they tried to model their project. Rather than breaking everything down into microscopic detail, model the level of detail based on how that manager was used to thinking about things. The goal was to make the tool compatible with their management style. Morrow asked if you could actually break things down in even greater detail. Katz said yes, many programs now supported "sub-networking," where you could take a more detailed schedule and roll it up for the higher levels of management so they didn't get bogged down in details.

Cheifet observed that many people complained that project management software was difficult to use. How did Twomey respond to that concern? Twomey said there was a general misnomer that if you bought project management software, that automatically made you a project manager. That wasn't an absolute association. But you needed to look at the products in terms of how intuitive they were, how accessible the interface was, and the user's level of project management. She said the learning curve averaged from a day to a week in most cases.

## FCC Found Most PC Clones Not FCC Compliant

Stewart Cheifet presented this week's "Random Access," which was recorded in November 1986.

+ The Electronic Industry Association reported that computer sales for the first nine months of 1986 were down more than 9 percent from last year--but overall sales of electronic devices were up by about 8 percent.
+ A *Trenton Star-Ledger* survey found that 41 percent of respondents planned to buy a personal computer within the next few years.
+ *Fortune* named the Compaq DeskPro 386 as one of its top 10 "Products of the Year" for 1986. Cheifet said other products honored included the Lasertag toy gun and the new Bruce Springsteen five-record set (*Live 1975–85*).
+ Compaq said it had already shipped more than 10,000 of the DeskPro 386 computers. Cheifet said the company also announced an update to the DeskPro 286, which featured a 40 MB hard disk drive and seven expansion slots.
+ John Maxfield, a "computer security consultant," claimed that nearly 40 percent of existing computer bulletin boards provided information to criminals.
+ The Federal Communications Commission found that only about 15 percent of PC clones displayed at the recent COMDEX show met the agency's signal emissions standards.
+ Paul Schindler reviewed *Time Bandit* (MichTron, $40), a collection of 16 maze-type games for the Atari ST.
+ Novell and 3Com were no-shows at the recent LocalNet '86 trade show in San Francisco.
+ The American Bar Association introduced the first online continuing legal education program for lawyers.
+ The online service NewsNet added the Xinhua news wire from China.
+ *Hoops*, a new $50 basketball simulator for the IBM PC and compatibles, included data form the top 200 college teams of the past 35 years.

## Former Kildall Associate the Brains Behind Computer Associates' Project Management Software

Perhaps the most interesting story from this episode is that two of the products demonstrated--*Time Line* and *SuperProject Plus*--nearly ended up under the same owner, namely Computer Associates.

But let's back up a bit. Computer Associates (CA) did not originally develop either program. Charles Wang started CA in 1976 as a joint venture with a Switzerland-based company also known as Computer Associates. The New York-based CA initially focused on marketing software by telephone. After some early success licensing a data-sorting program called CA-SORT to enterprise customers, CA basically built its business by aggressively acquiring small software companies.

Among CA's early acquisitions were Information Unlimited Software (IUS) in 1983 and Sorcim in 1984. CA merged the two companies together into a new division called Sorcim/IUS, which focused on software for personal computers. Sorcim/IUS subsequently acquired a project management program called "Plan*It" from its original developer, Alan Cooper.

Cooper himself had a long association with *Computer Chronicles* co-host Gary Kildall. Cooper was one of Kildall's students at the Naval Postgraduate School in Monterey, California. Later, Cooper joined Digital Research as one of its first research and development employees. After leaving DRI in the late 1970s, Cooper started writing his own business software applications. In a [2020 *Medium* article](https://onezero.medium.com/in-1983-i-created-secret-weapons-for-interactive-design-d154eb8cfd58), Cooper recalled that "it wasn’t until 1983 and about 15 major business and personal software products later that I began to develop a more effective approach" to making software more user-friendly. It was around that time he started writing "Plan*It" as a critical-path project management program.

CA renamed "Plan*It" *SuperProject Plus* and later versions *CA-SuperProject*. At some point in the 1990s, CA changed the product's name to *AllFusion Project Planner*. It's hard to nail down exact dates since CA licensed the software to enterprise customers--as opposed to selling it in retail boxes--but as best I can tell, support stopped sometime before 2002.

As for *Time Line*, it was developed by the previously mentioned Breakthrough Software Corporation. This company had a very short lifespan. It was incorporated in California in April 1984. The two principals were a married couple, William and Victoria Lohse, and from what I can tell *Time Line* was their sole product.

*Time Line* enjoyed some success in the market, and by October 1986, the Lohses were ready to cash out. They initially agreed to sell Breakthrough Software to Integrated Software Systems Corporation (ISSCO), a company that specialized in computer graphics. But while that deal was pending, CA's Sorcim/IUS division agreed to acquire ISSCO. A [December 1986 *InfoWorld* report](https://books.google.com/books?id=ejwEAAAAMBAJ) suggested that Breakthrough had now decided to scuttle the ISSCO deal, largely due to concerns that CA would phase out *TimeLine* in favor of its competing *SuperProject* product. A few months later, in February 1987, the Lohses sold Breakthrough to Symantec, which continued to revise and update *Time Line* until a final 6.0 release for Windows in 1994.

## Notes from the Random Access File

+ This episode is available at the [Internet Archive](https://archive.org/details/ProjectM1986) and has an original broadcast date of November 24, 1986.
+ [Jim Dunnigan](https://www.linkedin.com/in/jimdunnigan/details/experience/) remained with Microsoft until 1993. He then shifted careers into education, working as an elementary and high school teacher for most of the next two decades. In 2012, he moved into higher education, first as an adjunct professor at Seattle University and most recently as a faculty member at Arizona State University's teachers college.
+ [Nancy Twomey](https://www.linkedin.com/in/ntwomey/details/experience/) remained with Computer Associates until early 1987, when she moved to a product marketing position with Tandem Computers, and later held marketing positions with Compaq, Hewlett-Packard, Adobe, and WebEx, among other companies. Her last known position was with the cloud services company VMware, from where she retired in 2018.
+ [Glenn Katz](https://www.linkedin.com/in/glkatz/) is still affiliated with Stanford University, where he's been a lecturer in the school's civil engineering department since 2004. He also owns his own architectural design firm, [Bearington Studios](https://bearington.com/).
+ [Debra Wilrett](https://www.linkedin.com/in/debrawillrett/details/experience/) developed *MacProject*, which Stewart Cheifet demonstrated during the studio introduction. Wilrett continues to work in software development today.
+ The Hubble Space Telescope was not deployed until April 1990, more than three years after this episode aired. Wendy Woods did not mention this in her report, but a planned 1986 launch date was scrapped due to the loss of the Space Shuttle *Challenger* in January 1986 and the subsequent grounding of the remaining shuttle fleet. When the Space Shuttle *Discovery* finally carried the Hubble into orbit, the price tag for the project had climbed to $1.5 billion, according to a United Press International report, "making the instrument the single most expensive civilian science payload ever launched."
+ As for *Metier Artemis*, Houston-based Metier Management--which was actually a subsidiary of Lockheed Corporation--would port its mainframe project management software to the PC in June 1987.
+ *Time Bandit* didn't start out as an Atari ST program. The original game was released for the Tandy TRS-80 in 1983. Harry Lafnear, who co-designed *Time Bandit* with Bill Dunlevy, said in a [2003 interview with *Atari Legend*](https://www.atarilegend.com/interviews/4) that he believed the game sold about 75,000 copies across all platforms, with most of those on the ST. He said there had also been work done on a sequel, but that was abandoned after both he and Dunlevy left the publisher, MichTron.
+ Stewart Cheifet described John Maxfield as a "computer security consultant" and expert. The real story behind Maxfield was quite a bit more complicated. According to a 2016 report by [Matt Novak for *Gizmodo*](https://www.gizmodo.com.au/2016/04/the-untold-story-of-the-teen-hackers-who-transformed-the-early-internet/), Maxfield was a "former phone phreak who fancies himself the proto-internet's sheriff," and who "gained the trust of teen hacker communities on bulletin board systems (BBSs) in the early 1980s and fed the information to the FBI." Maxfild subsequently became known as the "most loathed man on the internet" after his information led to a series of FBI raids in 1983. Maxfield himself has apparently not been publicly seen or interviewed since the early 1990s.
+ George Lucas' EditDroid proved to be a commercial flop and The Droid Works company itself closed up shop in 1987. Tom van Klingeren directed a short documentary in 2005, [*EditDroid: Rise and Fall*](https://www.youtube.com/watch?v=z99wO2utddo&list=PLt_f-NUXUN7McEZR7btAYWuCgj7sftJFq), which provides an overview of the product's history.
