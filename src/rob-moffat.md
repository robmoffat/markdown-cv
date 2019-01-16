# Rob Moffat

# Java / Javascript / Full-Stack / Senior Dev or Tech Lead

## Qualifications ##

 -	First in B.Sc. (Hons.) Computer Science at Aston University
 -	MBA (Hons.) at Warwick Business School
 -	Certified Java Enterprise Architect
 -	Certified Java Developer 
 -	4 A Levels, 8 A Grade GCSEs

## Summary ##
 - I am a seasoned Senior Developer or Tech Lead with a passion for testing, quality and build systems. 
 - I'm happy working in **any team configuration**:  at HSBC I delivered two projects in teams-of-one, whilst at Credit Suisse I lead a testing team and worked as a developer within a team co-located across Poland, India and the UK.
 - I am confident communicating technical ideas.  I write _lots_ of technical documentation and I'm happy running workshops or giving presentations if required.
 - I have wide experience of **CI tools** like Jenkins/Hudson, Team City, Gradle, Git and Maven.  I'm usually the guy who ends up fixing the builds.
 - I've coached agile teams and used Scrum, but I believe team process is usually less important than strong automated testing with Continuous Integration/Delivery practices.  
 - I've worked in Finance IT for over 15 years and I'm used to dealing with large, complex, long-running **Risk / Regulatory** projects with multiple stakeholders and distributed teams.
 - I am experienced in writing testable requirements documentation and negotiating sign-off processes.
 - I've got experience with current web technologies such as **JavaScript, SVG, JSON, SCSS, HTML5, React, Redux and Node**. 
 - I've built many relational-backed software systems from the ground up using **Oracle, MySQL and Sybase, JPA and Hibernate**, and I've got an in-depth understanding of performance optimisation.

[block]

## Contact Details

- email: robmoffat@mac.com
- github: https://github.com/robmoffat
- linkedin: https://linkedin.com/in/robmoffat

References available on request.

[/block]

[block]   
   
## Open Source Projects ##

- **[Concordion Excel Extension](http://github.com/concordion/concordion-excel-extension)**:   Wherever I work I am a firm advocate for automated testing.   I wrote an extension for Concordion to make it more suitable for unit testing financial calculations with examples created in Excel spreadsheets.

- **[Pure4J](https://github.com/pure4j/pure4j)**:  I’ve been working recently in Clojure (with its immutable collections) and I'm interested in pure functional programming as a way of improving program correctness.  Pure4J is an experiment in building a Java code analysis tool to check functional purity within a codebase.

- **[Risk-First](https://github.com/risk-first/website/wiki)**:  Mainly a wiki classifying different types of risk found on software projects, but there is also Java code here that integrates with Twitter and GitHub APIs.

[/block]

[block]

## Career ##

### HSBC (May 2015 to Dec 2018) ###

_Senior Dev / Project Lead in Symphony Team then Global Research Team_

Symphony is a secure chat messaging system used at HSBC.  I was hired to build technologies (such as chat-bots) to integrate HSBC systems with Symphony to increase the value of the platform.

#### HSBC Global Research Symphony App ####

- I build an **Apache Solr** and **Spring Boot**-based application for Symphony which indexed HSBC Global Research publications, making them searchable and shareable from Symphony chats.
- It used a **Javascript React and Redux** front-end, with tests written in **Jest** and **Selenium**.
- Search results from the app were qualitatively better than those from the existing Global Research search engine, so at the time I left, the plan was to switch the website to use the same search engine.
- Although built for internal use, the Global Research team tasked me with rolling this out to Symphony users at external clients too.  [Here is a promotional video HSBC made for the app launch.](https://players.brightcove.net/1311491902001/default_default/index.html?videoId=5759030978001)  

[/block]

[block]

#### Other Symphony Applications

- As well as building the app, we built a Symphony bot to respond to user's requests for research articles.  
- In order to troubleshoot outages and performance problems with Symphony, I built a monitoring dashboard using **Spring Boot, Grafana and InfluxDB**.

#### Responsive Content Project

- I moved from the Symphony team to the Global Research team after the success of the Symphony app.  They tasked me with building a tool to convert Global Research publications (Microsoft Word documents) into responsive HTML5.
- As well as converting the Word documents, I also built a converter for Word's images, turning them into SVG graphics.   Research had expected to pay a third party provider to do this, so this saved a lot of money and trouble.
- Although this was working well in December 2018, the project is now on hold due to budgetary problems.  

[/block]

[block]

### Credit Suisse (Oct 2013 to May 2015) ###

_Senior Dev / Team Lead roles in Credit Risk._

#### REF ####

"REF" is a component framework for building risk and finance calculations at Credit Suisse.  After the departure of the first architects, I took on the role of re-architecting REF to simplify it and improve reliability:  

 - I led a project to re-write the Data Service Layer: The original design had three separate Java JVMs, code generated from a **Sparx Enterprise Architect** model and was impossible to debug.  We moved to **Spring / JPA / Hibernate** and made the whole thing a library.  This improved performance and maintainability at the same time.  
 - I devised the configuration and deployment process for all components and persuaded all the component teams to adopt these standards.  This enabled Continuous Deployment (CD) for REF.   
 - I removed our **Oracle Coherence** dependency (saving millions of CHF in licensing fees).
 - I worked on the architecture for REF v2.  For this I built out tutorials covering topics such as **Docker, Azure, REST, Security, Jenkins and Spring Boot** for developers of other projects to follow.
 
[/block]

[block]

#### Back-Testing ####

Back-Testing was a project built in CS using the REF architecture.  
 
- I ran a team responsible for building an Automated Testing Framework for REF and we also took care of building tests specific to the Back-Testing project.
- I ran a weekly workshop for developers and BAs on the Back-Testing project to explain methodology and process.  We covered aspects of statistics such as **p-Values, Cramer von Mises, Sampling Dots**, testing methodology (mocking, integration testing) and risk methodologies like **Monte-Carlo or Historic VaR** for an audience in multiple regions.

[/block]

[block]

### Aura Software (Sep 2010 to Oct 2014)

_I was variously a Tech Lead, Architect and PM in a small, distributed consultancy building mainly Learning Management System (LMS) software for various clients._

- Applied various technologies on different projects, including **Javascript, Angular, jQuery, XML, JSON, Git, PHP, Wordpress, Ruby and Java**.  (LMS systems are generally *terrible*, so by using modern tools and techniques we were able to demonstrate clear competitive advantages.)
- Used platforms such as **AWS and Linode** to deploy our applications.
- Built front-end tests using tools like **Geb, Spock, Selenium** and  **PhantomJS**.
- Project Managed delivery of our software solutions using agile and waterfall approaches where appropriate.
- Built Kite9: an online, interactive **UML** editor using **SVG, Spring, XML and JQuery**.

[/block]

[block]

### Royal Bank of Scotland (Mar 2005 to Sep 2010)

_Project Manager & Tech Lead in Global Banking and Market’s Risk Team._

#### E-Star

- Architect and Tech Lead on E-Star, which was RBS’s investment bank implementation of Basel II - a critical project with drop-dead timelines.
- When the project manager left, I assumed this role too and delivered E-Star over it’s 3 releases.
- E-Star used **Java, Spring, Sybase, JMS and Hibernate** and it was here I started building functional tests using Excel.  This technique  was then adopted across further projects in Risk.  
- With E-Star, we introduced new software build techniques to Risk:  **Maven, Cruise Control** and automated functional testing and **JUnit**.
- I was made a member of Royal Bank of Scotland’s talent programme.

[/block]

[block]

#### Gateway 

- PM and Architect on Gateway, a limit-checking service for prime brokerage clients, with high-frequency, low-latency requirements.   We ensured these requirements were met with **JMeter** tests and Java profiling.
- As well as using **XStream, RMI, Java and Spring**, we used **Coherence** and it was the first project at RBS to make use of this.  

[/block]

[block]

#### Repo-VaR

- I was PM and developer on Repo-VaR, another critical Basel II project.  Without this, the bank relied on the more capital-intensive haircut approach, but with RepoVaR we got sign-off from the FSA (Financial Services Authority) to use our own internal model which was less capital intensive.
- In conjunction with this, I built the RepoVaR Back-Testing project.  In order to get a model FSA-approved, you have to back-test it.  I built the Back-Testing software, which looked back through time to check that for a given historic period, our model’s predictions were correct.

[/block]

[block]

### Deutsche Bank (Feb 2002 to Mar 2005)

_Tech Lead in the Risk and PnL Reporting Team._

#### MIS3

- I was tech lead and architect on the MIS3 Project, a risk and PnL aggregation and reporting tool.
- MIS3 continues to be a key strategic system at Deutsche Bank.  (Apparently, they’ve barely changed the code I wrote in 2004.)
- Later on, I helped design an **Oracle data warehouse** for MIS3 data.

[/block]

