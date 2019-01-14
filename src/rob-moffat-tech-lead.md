# Rob Moffat, Java / Javascript / Full-Stack / Senior Dev or Team Lead

## Qualifications ##

 -	First in B.Sc. (Hons.) Computer Science at Aston University (1997)
 -	MBA (Hons.) at Warwick Business School (2007) 
 -	Certified Java Enterprise Architect
 -	Certified Java Developer 
 -	4 A Levels, 8 A Grade GCSEs

## Summary ##
 - I am a seasoned Senior Developer or Tech Lead with a passion for testing, quality and build systems. 
 - I have recently been working at HSBC delivering two projects in teams-of-one, whilst at Credit Suisse I was leading a testing team within a wider credit-risk back-testing project.
 - I am confident communicating technical ideas.  I write _lots_ of technical documentation,  and I'm happy running workshops or giving presentations if required.
 - I have wide experience of CI tools like Jenkins/Hudson, Team City, Gradle, GIT and Maven.  I'm usually the guy who ends up fixing the builds.
 - I am experienced in writing testable requirements documentation, and negotiating sign-off processes.
 - I've worked in Finance IT for over 10 years, and I'm used to dealing with large, complex, long-running Risk / Regulatory projects with multiple stakeholders and distributed teams.
 - I studied Lean/Kanban principles on my MBA, and try to apply them to projects I work on. 
 - I've done software project management, but I don't love it enough to want to do it for my job.
 - I've coached agile teams and used Scrum, but I believe team process is usually less important than strong automated testing with Continuous Integration/Delivery practices.  
 - I've got experience with current web technologies such as JavaScript, SVG, JSON, Sass, HTML5, React, Redux and Node. 
 - I've built many relational-backed software systems from the ground up using Oracle, MySQL and Sybase, and I've got an in-depth understanding of performance optimisation.

[block]   
   
## Open Source Projects ##

I put a lot of code on GitHub in my spare time:

 - **[Concordion Excel Extension](http://github.com/concordion/concordion-excel-extension)**:   Wherever I work I am a firm advocate for automated testing.   I wrote an extension for Concordion to make it more suitable for unit testing financial calculations with examples created in Excel spreadsheets.

- **[Pure4J](https://github.com/pure4j/pure4j)**:  I’ve been working recently in Clojure (which sports immutable collections) and I'm interested in pure functional programming as a way of improving program correctness.  Pure4J is an experiment in building a Java code analysis tool to check functional purity within a codebase.

- **[Risk-First](https://github.com/risk-first/website/wiki)**:  Mainly a wiki classifying different types of risk found on software projects, but there is also Java code here that integrates with Twitter and GitHub APIs.

[/block]

[block]

## Career ##

### HSBC (May 2015 to Present) ###

#### HSBC Global Research Symphony App ####

Symphony is a secure chat messaging system being developed by a consortium of finance and tech partners including HSBC and other tier 1 banks.  I was hired to build technologies (such as chat-bots) to integrate HSBC systems with Symphony to increase the value of the platform and therefore its internal uptake.

- I build an **Apache Solr** and **Spring Boot** based application for Symphony which indexed HSBC Global Research and made it searchable and shareable from within Symphony.
- It used a **Javascript React and Redux** front-end, with tests written in **Jest** and **Selenium**.
- We adopted a Devops-style approach, eventually automating the process enough to release approximately every 2-weeks.
- HSBC Global Research website that they decided to throw theirs away and start using our search strategically.
- Recently, other teams have come to us asking for *their own* versions of the same app, to fix problems of search and sharing for their teams.  

#### Symphony Applications

### Credit Suisse (Oct 2013 to May 2015) ###

#### REF Team ####

"REF" is a component framework for building risk and finance calculations at Credit Suisse.  After the departure of the first architects, I took on the role of re-architecting REF, to simplify it and improve reliability:  

 - I led a project to re-architect the Data Service Layer: The original design had three separate Java JVMs, code generated from a **Sparx Enterprise Architect** models and was impossible to debug.  We moved to **Spring / JPA / Hibernate**, and made the whole thing a library, which improved performance and maintainability at the same time.
 - I devised the configuration and deployment process for all components, and persuaded all the component teams to adopt these standards.  This enabled **Continuous Deployment** for REF.   
 - REF started out as a set of inter-dependent, individually-versioned micro-services, communicating using **JMS and Apache MQ**.  But coupling between the modules was so high this created problems every time a change was made.  I organised all the teams to move their code into a single build tree.  This meant developers could work on each other's modules and see immediately when their changes had broken other components.
 - I removed our **Oracle Coherence** dependency (millions of CHF in licensing fees).
 - I worked on the architecture for REF2 (which will be more "buffet" style than the original REF).  For this I built out tutorials covering topics such as **Docker, Azure, REST, Security, Jenkins and Spring Boot** for developers of other projects to follow.
 
[/block]

[block]

#### Back Testing Project ####

Back Testing was a project built in CS using the REF architecture.  
 
- I ran a team responsible for building out an Automated Testing Framework for REF, and we also took care of building tests specific to the Back Testing project.
- I ran a weekly workshop for developers and BAs on the Back Testing project to explain methodology and process.  We covered aspects of statistics (**p-Values, Cramer von Mises, Sampling Dots**), testing methodology (mocking, integration testing) and risk methodology (**Monte-Carlo, Historic VaR**) for an audience in multiple regions.

[/block]

[block]

### Aura Software Sept. 2010 - Oct. 2014

I was variously a Tech Lead, Architect and PM in a small, distributed consultancy building mainly **Learning Management System** (LMS) software for various clients.

- Applied various technologies on different projects, including **Javascript, Angular, jQuery, XML, JSON, Git, PHP, Wordpress, Ruby and Java**.  (LMS systems are generally *terrible*, so by using modern tools and techniques we were able to demonstrate clear competitive advantages.)
- Used platforms such as **AWS and Linode** to deploy our applications.
- Built front-end tests using tools like **Geb, Spock, Selenium** and  **PhantomJS**.
- Project Managed delivery of our software solutions using agile and waterfall approaches where appropriate.
- Built Kite9: an online, interactive **UML** editor using **SVG, Spring, XML and JQuery**.

[/block]

[block]

### Royal Bank of Scotland Mar. 2005 – Sept. 2010

Project Manager & Tech Lead in Global Banking and Market’s Risk Team.

#### E-Star

- Architect and Tech Lead on **E-Star**, which was RBS’s investment bank implementation of **Basel II** - a critical project with drop-dead timelines.
- When the project manager left, I assumed this role too and delivered E-Star over it’s 3 releases.
- E-Star used **Java, Spring, Sybase, JMS and Hibernate**, and it was here I started building functional tests using Excel.  This technique  was then adopted across future projects in Risk.  (In fact, this is broadly the approach used in my open-source [Concordion Excel Extension](https://github.com/concordion/concordion-excel-extension).)
- With E-Star, we introduced new software build techniques to Risk:  **Maven, Cruise Control** and **automated functional testing** and **JUnit**
- I was made a member of Royal Bank of Scotland’s talent programme.

[/block]

[block]

#### Gateway 

- PM and Architect on **Gateway**: a limit-checking service for prime brokerage clients, with high-frequency, low-latency requirements.   We ensured these requirements were met with **JMeter** tests and Java profiling.
- As well as using **XStream, RMI, Java, Spring, Servlets**, we used **Coherence**, and it was the first project at RBS to make use of this.  

[/block]

[block]

#### Repo-VaR

- PM and developer on another critical **Basel II** project:  without this, the bank relied on the more capital-intensive haircut approach, but with RepoVaR we got sign-off from the FSA (Financial Services Authority) to use our own internal model which was less capital intensive.

[/block]

- In conjunction with this, I built the **RepoVaR Back Testing** project.  In order to get a model FSA-approved, you have to back-test it.  I built the Back Testing software, which looked back through time to check that for a given historic period, our model’s predictions were correct.
- Over time, we discovered flaws in the methodology of our backtesting, but with a comprehensive understanding of the **repo product family** and how **VaR** was calculated for them, I was able to specify and then engineer a new back testing calculation to avoid these breaks.


[block]

### Deutsche Bank Feb. 2002 – Mar. 2005

#### Tech Lead in the Risk and PnL Reporting Team.

- I developed and delivered a complete global redesign and rollout of Risk’s website in 5 regions using **Java Servlets, JSP and Sybase**, based on the Deutsche Look-And-Feel guidelines.  I built a **JSP tag library** for all of the Deutsche interface elements, so other people could do the same with their websites.
- I was tech lead and architect on the **MIS3 Project**, which was a risk and PnL aggregation and reporting tool that brought together daily valuations and risk together with trade details from a variety of different risk and trade sources for use by downstream groups (margin management, risk controlling, accounts etc).
- MIS3 is notable because it used the *Inversion Of Control* pattern (which was new at the time) in the **Apache Avalon container** (a precursor to **Spring**).  MIS3 was horizontally scalable, distributed and redundant.
- Later on, I helped design an **Oracle data warehouse** for MIS3 data.
- MIS3 continues to be a key strategic system at Deutsche Bank.  Apparently, they’ve barely changed the code I wrote twelve years ago.

[/block]

[block]

## Contact Details

- email: robmoffat@mac.com
- blog: http://robmoff.at
- twitter: @bobm_kite9
- github: https://github.com/robmoffat
- linkedin: https://linkedin.com/in/robmoffat

References available on request.

[/block]