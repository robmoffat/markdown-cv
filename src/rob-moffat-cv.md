# Rob Moffat

*Reading time - 10 mins*

## About Me

Looking back while writing this CV makes me realise that in most of my jobs I’ve commonly taken on two tasks:  fixing broken build systems and introducing automated testing.   You could take it to mean that this is my speciality, but in actual fact I’m always relieved to work in a team that had already figured this stuff out.   Despite Agile methodologies having been with us for over 15 years, it seems like lots of teams still struggle to realise the benefits of these techniques. 

[aside]

#### Contact Details

- email: robmoffat@mac.com
- blog: http://robmoff.at
- twitter: @bobm_kite9
- github: https://github.com/robmoffat
- linkedin: https://linkedin.com/in/robmoffat

[/aside]

Truth is, I I like to help teams to work better.  I’m happiest taking on the dev lead role, as this gets me closest to the hardest problems the Dev team is facing.  I’ve also done Project Management when needed over the years too, but I don’t think this is where I add the greatest value:  Although I have an MBA, it’s just not leveraging my technical skills.

Most of my recent work has been within Risk teams in banks (I live near London), though I’ve worked in various consultancies too.

I am still just as obsessed with computers now as I was aged 10.  Lately I’ve been into Recurrent Neural Networks and Pure Functional Programming on the JVM.

## Qualifications

- First in B.Sc. (Hons.) Computer Science at Aston University (1997).
- MBA (Hons.) at Warwick Business School (2007).
- 4 A Levels, 8 A Grade GCSEs.
- Certified Java Developer
- Certified Java Enterprise Architect

## My Own Projects

### [Concordion](http://github.com/concordion/concordion-excel-extension)

**Concordion** is a functional testing framework for Java (like a streamlined **Fitnesse**, if you’ve used that).  I wrote an extension for Concordion to make it more suitable for testing financial calculations.  

Business Analysts in banks understand **Excel**.   Therefore, why not get them to write test cases in Excel?  These can be parsed as functional test examples by my extension, so you can ensure that the Java code under test is getting the answers the same as the Excel spreadsheet example.

[block]

### [Pure4J](https://github.com/pure4j/pure4j)

I’ve been interested recently in **Clojure** (a Lisp on Java's JVM) and **Frege** (a Haskell on the JVM) as ways of improving productivity and program correctness.  Frege especially espouses a pure functional approach to programming, a style which eradicates state within your application, making  testing easier and reducing the places where bugs can hide.

Asking developers in finance to learn Haskell would be crazy: everyone already knows Java, it’s our *lingua franca*.   Pure4J is a Java code analysis tool for ensuring functional purity within a codebase, giving you the advantages of this style of programming without having to learn a new language.  Pure4J comes with the immutable, persistent collections from Clojure, adapted to use generics and normal Java idioms.

[/block]

### [Risk-First](https://github.com/risk-first/website/wiki)

Risk-First is an Open-Source Wiki in Github cataloging software risks.  It is also [a book which you can buy](https://www.amazon.co.uk/dp/B07MK9LTHN/ref=cm_sw_em_r_mt_dp_U_.2mpCb7F1N9E9) on Amazon.

The conception behind Risk-First is that _everything we do on a software project is about managing risk_.  It takes that simple idea, and sees where it goes.  Originally, I thought it wouldn't go further than a single blog post, but once I got thinking about this, the idea just grew and grew.

At the time of writing, this has been selling fairly well as a book, even though it's just on Kindle pre-order right now, and everything in the book is available to read on the website anyway.  

We'll see where it goes.

[block]

### [Kite9](http://kite9.com)

[aside]

“With Kite9 Rob's pulled off a rare double of having an ambitious technical vision and the focus and tenacity to get that vision built and launched. I love the tool too; Kite9 is crazy good.”

*Bret Weinraub, partner at Aura Software (from LinkedIn)*

[/aside]

Kite9 is a online software diagramming tool that (unlike say **Visio**) organises the layout of the diagrams for you.

Kite9 uses some interesting technologies like **Grails, Bootstrap, SVG** and **jQuery**.  But the most interesting part is the graph layout.  Graph layout is a well-researched problem, but none of the algorithms in the literature had the functionality I wanted to see.  Kite9 uses a bespoke graph layout algorithm based on published approaches, but taken in new directions to give the user more control over the orientation of the elements.

You can try it at [Kite9.com](http://kite9.com).  It’s pretty fun to use, but still in development.

[/block]

[block]

## Professional Experience

[aside]

*Note:*  

This is in chronological order-  it just makes more sense that way.  

But feel free to skip a page or so to get to the recent stuff.

[/aside]

### Early Career Sept. 1997 - Oct 2001

#### Datix

After graduating, I started work at a firm called **Datix** in London.  They built software for legal firms, and I worked on building two internal **Lotus Notes** databases.  One for tracking marketing information and the other for storing legal news, articles, precedents and so on.  Although I was new to all this, they just let me get on with it, and I learnt a lot.   Eventually, they began to market these tools to other law firms, but by then it was time to move on for me.

[/block]

[block]

#### Agora

I worked for a Lotus Notes consultancy called **Agora** next in Kingston (London, not Jamaica).  We were building a database for tracking patient records for the NHS.  In retrospect (and even at the time, really), this was a dreadful misuse of Lotus Notes, and the project was obviously going to fail.  Nevertheless, this was an excellent environment for learning new ideas, and I started using **Java, XML and relational databases** here.

[/block]

[block]

#### PriceWaterhouseCoopers

I worked briefly at **PriceWaterhouseCoopers**, on their global website.  I mainly helped by automating the process of scooping out content from their existing web pages (using **XSLT, XML and Java**), so that it could be ported into the new design.   Sadly, this project got cancelled pretty quickly.

[/block]

[block]

#### Wide Learning

Next, I worked for **Wide Learning**, a purveyor of online software courses.  Theirs was the typical story of .com excess, where they received huge amounts of funding one day, and then had to sell up when the market turned against them.

I worked on the implementation of Wide’s e-learning Content Delivery System, the purpose of which was to render courseware that tailors learning content to the requirements of the student.  We used **Java, J2EE and WebLogic**.  And **Enterprise Java Beans (EJBs)**, which seemed like a good idea at the time.

[/block]

[block]

#### RI3K

Finally I worked for **RI3K** (now part of Qatar Insurance Services), who were creating an application for trading reinsurance contracts.  They had chosen **Java, WebLogic, EJB, Oracle**  and extensively used **XSLT** for rendering user interfaces.

I put in place a build process managing all the deployment platforms, (on NT, Linux and HPUX using **Apache**, **Tomcat** and **CapeClear**) for UK and Singapore versions and rolled out periodically to these sites.  Also, I developed several areas of the system, including Contracts and Negotiation workflows, working closely with in-house experts.

[/block]

[block]

### Deutsche Bank Feb. 2002 – Mar. 2005

#### Tech Lead in the Risk and PnL Reporting Team.

[aside]

"Rob was an enthusiastic and knowledgeable member of the team who was always keen to investigate new technology when providing solutions. 

He has an affable nature and is an excellent communicator of ideas. It would be great to work with Rob again in the future.”

*Laurence May (from LinkedIn)*

[/aside]

Shortly after starting, I introduced improved development practices to the team by bringing all source code under source control in **VSS** (later moved to **CVS**), with a single build process using **Ant**, as well as introducing **Eclipse IDE**, which was a new thing back then.  Later, we would move builds to **Maven**, too.

I developed and delivered a complete global redesign and rollout of Risk’s website in 5 regions using **Java Servlets, JSP and Sybase**, based on the Deutsche Look-And-Feel guidelines.  I built a **JSP tag library** for all of the Deutsche interface elements, so other people could do the same with their websites.

[/block]

I was tech lead and architect on the **MIS3 Project**, which was a risk and PnL aggregation and reporting tool that brought together daily valuations and risk together with trade details from a variety of different risk and trade sources for use by downstream groups (margin management, risk controlling, accounts etc).

MIS3 is notable because it used the *Inversion Of Control* pattern (which was new at the time) in the **Apache Avalon container** (a precursor to **Spring**).  MIS3 was horizontally scalable, distributed and redundant.

Later on, I helped design an **Oracle data warehouse** for MIS3 data.

MIS3 continues to be a key strategic system at Deutsche Bank.  Apparently, they’ve barely changed the code I wrote nearly *twenty years ago*.  Just lazy. :)

Finally,  I provided mentoring and project leadership for offshore staff in Spain, and was made a member of Deutsche Bank’s talent programme.

[block]

### Royal Bank of Scotland Mar. 2005 – Sept. 2010

#### Tech Lead in Global Banking and Market’s Risk Team.

[aside]

“I reported to Rob whilst working at RBOS on a greenfield Basel II reporting project. 

The first thing that struck me was Robs energy and drive, he quickly shaped a new team into delivering quality code on tight schedules.”

*Dave Brimley (from LinkedIn)*

[/aside]

When I started, **Basel II** was beginning to be rolled out worldwide for banks, and there was a hard deadline of compliance by the end of 2005.  I joined as tech lead on **E-Star**, which was RBS’s investment bank implementation of Basel II - so a very critical project.   When the project manager left, I assumed this role too and delivered E-Star over it’s 3 releases.

E-Star used **Java, Spring, Sybase, JMS and Hibernate**, and it was here I started building functional tests using Excel.  This technique  was then adopted across future projects in Risk.  (In fact, this is broadly the approach used in my open-source [Concordion Excel Extension](https://github.com/concordion/concordion-excel-extension).)

[/block]

My second role was PM and Tech Lead on **Gateway**: a limit-checking service for prime brokerage clients, with high-frequency, low-latency requirements.  As well as using **XStream, RMI, Java, Spring, Servlets**, we used **Coherence**, and it was the first project at RBS to make use of this.  Back in 2006, the idea of eventually-consistent caching and distributed systems were fairly novel, but now they are broadly accepted and there are much better options than Coherence today.

The third project I worked on was **Repo VaR**, an imaginatively titled project for calculating exposure on Repo-style products using a **VaR (Value at Risk) methodology**.  Again, this was another critical Basel II project:  without this, the bank relied on the more capital-intensive haircut approach, but with RepoVaR we got sign-off from the FSA (Financial Services Agency) to use our own internal model which was less capital intensive.

In conjunction with this, I managed the **RepoVaR Back-Testing** project.  In order to get a model FSA-approved, you have to back-test it.  I built the back-testing software, which looked back through time to check that for a given historic period, our model’s predictions were correct.

Once in production, we discovered flaws in the methodology of our backtesting, but with a comprehensive understanding of the repo product family and how VaR was calculated for them, I was able to specify and then engineer a new back-testing calculation to avoid these breaks by manipulating the portfolio cash flows to reflect how the portfolio changed after the VaR was originally calculated.

I led the introduction of new software build techniques to Risk:  **Maven, Cruise Control** and automated regression testing and unit testing and was made a member of Royal Bank of Scotland’s talent programme.

[block]

### Aura Software Sept. 2010 - Oct. 2014

#### Partner

Once I started a family, I wanted to spend less time commuting into London, so during this period I worked at home as a consultant and partner in Aura Software, who built learning software portals mainly in the medical equipment industry.

I was tech lead in a distributed team building a custom **Learning Management System** (LMS) for **Medtronic**, a Fortune 500 medical equipment manufacturer.   We used various technologies including **Javascript, jQuery, XML, JSON, Git, PHP, Wordpress, Ruby and Java**.  LMS systems are generally *terrible*, so by using modern tools and techniques we were able to knock this out of the park.

[/block]

Since this was a small operation, I had to wear multiple hats.   As well as development, I organised testing strategy & test plans, performed releases, wrote documentation and handled requirements capture.  This last one was pretty important as there were multiple stakeholders, and little understanding of good project management practice before I got involved.

We rolled out various successful web-based projects for clients within the medical / online learning sectors.  One to facilitate neurosurgeon training, another a portal for management of sales team training.  A big part of our success was leveraging existing software within the **Wordpress** eco-system, and only building the *novel* LMS parts.

[block]

### Credit Suisse Oct. 2014 -  May 2016

#### Consultant

[aside]

“Rob joined us on the DSL team and was instrumental in the successful redesign/rewrite in under three months…”

*Rob Hutton (from LinkedIn)*

[/aside]

Initially, I was hired to Credit Suisse to work on a project called **DSL** (Data Service Layer).  The aim of this project was to provide a unified Java API to access domain objects from various golden-source databases within the Credit Risk department.   The project was in full swing when I arrived, but had broken build scripts and no automated testing, so I fixed these first, implementing a single build in **Gradle** and building out a test framework to check each API method against each database.

Confusingly, the DSL project then became part of the **REF** project (a common infrastructure for calculations in credit risk).  I built out REF configuration and automated deployment and worked to set architectural standards for the components built using this.

Off the back of this, I was given a team of ten or so summer students from UCL to build a proof-of-concept of a testing framework for the **Scenarios** system.  (Scenarios are where we run the risk calculations under extreme conditions, to see what the effect would be on the bank’s capital.)   Despite the fact that this was a new area to pretty much all of us, we were able to demonstrate functional tests of scenarios VaR calculations.

I then ran a team tasked to build out functional testing for the **Strategic Back-Testing** project.  Although I’d done back-testing before at RBS, the methodology had advanced *a lot*, and used some interesting new statistical tests (such as Cramer-von-Mises and P-Values).  We built Excel-based example tests using the Concordion Excel Extension, and ran them against the Backtesting code to assert the calculations were correct in the production system.

After completing this, I moved back into the **DSL** team. There had been a series of owners and some extreme deadlines and the integrity of the original system had been lost.  With a colleague, we rewrote the whole thing in about 3 months using **JPA** and **Spring**.  We reversed some of the original architectural errors too, making it leaner, simpler and more performant.

[/block]

[block]

### HSBC May 2016 -  Dec 2018

#### Symphony Application Developer (Consultant)

[Symphony](https://symphony.com/en-US) is an encrypted chat platform used by several banks and other finance firms.  At the point I was hired, HSBC were just getting started on deploying Symphony internally, and it was something new:  Software-as-a-Service running inside AWS.  How well would this integrate with the banks' existing systems?  

Turns out, it was a lot of work.  I ended up building applications and dashboards to monitor connectivity to  Symphony, building good relationships with the staff that work there.  At the same time, I learnt a _huge amount_ about **encryption, SSL, certificates, proxies, public/private keys** and so on.  

But the big piece of work I did was to build the **HSBC Global Research App**.  This was software that used the Symphony APIs and the Symphony App-Store to provide an app to users of Symphony so they could search for, and share articles published by HSBC's Research team. 

I used a bunch of new technologies here:  **Spring Boot, React, Redux, npm, TypeScript** and **Apache Solr** (for the search index). 

You can check out the [teaser video here](https://players.brightcove.net/1311491902001/default_default/index.html?videoId=5759030978001).

#### Global Research Team: Responsive Content (Consultant)

While I had been building the HSBC Global Research App for the Symphony team, it was never really at home there because the _content_ for the application belonged to Global Research.  So, I moved within the bank and joined the Global Research team to complete the project.

Following that, I began a project to make the Global Research content _responsive_.  Previously, most research had been published as PDF files, which were great when printed, but almost impossible to read on a mobile device.  

I was tasked with providing a solution to get the PDFs to display using responsive HTML.  The approach I chose was to convert them from their original Microsoft Word format to a (very basic) HTML format using **docx4j**.   For the images in the documents, Word uses **EMF** and **WMF** formats, and I was able to convert these to **SVG** using **Apache Batik** and a modified **FreeHEP**.  From there, I devised a pipeline for "cleaning up" the resulting HTML so that it was tight semantic mark-up.  

This sounds easy, but the problem was one of scale: _thousands_ of documents written by _hundreds_ of authors, each using different features of Microsoft Word.  It was never going to be perfect, but after 3 months I had demonstrated the feasibility:  something like 95% of documents were converting correctly.

Sadly at this point, I had worked at HSBC for 2.5 years, and due to IR35 rules had to leave.  

*Online version: https://github.com/robmoffat/markdown-cv/blob/master/src/rob-moffat-cv.md*


[/block]
