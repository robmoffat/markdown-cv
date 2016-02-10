# Rob Moffat, Java Architect

## Qualifications ##

 -	First in B.Sc. (Hons.) Computer Science at Aston University (1997)
 -	MBA (Hons.) at Warwick Business School (2007) 
 -	Certified Java Enterprise Architect
 -	Certified Java Developer 
 -	4 A Levels, 8 A Grade GCSEs

## Summary of Skills ##
 - I am a seasoned Java Software Architect and Tech Lead with a passion for testing, quality and build systems.
 - I'm a strong proponent of the Agile Principles.  I've coached **XP** teams and used **Scrum**, but I believe team task process is usually less important than strong Continuous Integration/Delivery practices.  I studied Lean/Kanban principles on my MBA, and try to apply them to projects I work on. 
 - I am confident communicating technical ideas, whether writing technical documentation, producing **UML** or other diagrams, running workshops or giving presentations.
 - I've worked in Finance IT for over 10 years, and I'm used to dealing with large, complex, long-running **Risk / Regulatory** projects with multiple stakeholders and distributed teams.
 - I am a keen advocate of automated testing and continuous deployment (CI/CD).  
 - I have wide experience of tools like **Jenkins/Hudson, Team City, Gradle** and **Maven**.
 - Experience with current web technologies such as **JavaScript, jQuery, SVG, JSONP, CSS3, HTML5, WordPress, Drupal, PHP, React.js and Node.js**. 
 - I've architected many relational-backed software systems from the ground up using **Oracle, MySQL and  Sybase**, and I've got an in-depth understanding of performance optimisation.

[block]   
   
## Open Source Projects ##

Two projects I am involved in, which both aim to help developers build good code:

### [Concordion](http://github.com/concordion/concordion-excel-extension)

Wherever I work I am a strong advocate of automated testing.   **Concordion** is a functional testing framework for Java.  I wrote an extension for Concordion to make it more suitable for testing financial calculations:  Business Analysts in banks understand **Excel**.   Therefore, why not get them to write test cases in Excel?  These can be parsed as functional test examples by my extension, so you can ensure that the Java code under test is getting the answers the same as the Excel spreadsheet example.

[/block]

[block]

### [Pure4J](https://github.com/pure4j/pure4j)

I’ve been working recently in **Clojure**, and interested in **pure functional programming** as ways of improving throughput and program correctness.  But asking developers in finance to learn Haskell, say, would be crazy: everyone already knows Java, it’s our *lingua franca*.   Pure4J is a Java code analysis tool for ensuring functional purity within a codebase, giving you the advantages of this style of programming without having to learn a new language.  Pure4J comes with the immutable, persistent collections from **Clojure**, adapted to use generics and normal Java idioms.

[/block]

[block]

## Career ##

### Credit Suisse (Oct 2013 to Present) ###

#### REF Team ####

"REF" is a component framework for building risk and finance calculations at Credit Suisse.  After the departure of the first architects, I took on the role of re-architecting REF, to simplify it and improve reliability:  

 - I led a project to re-architect the Data Service Layer: The original design had three separate Java JVMs, code generated from a **Sparx Enterprise Architect** models and was impossible to debug.  We moved to **Spring / JPA / Hibernate**, and made the whole thing a library, which improved performance and maintainability at the same time.
 - I devised the configuration and deployment process for all components, and persuaded all the component teams to adopt these standards.  This enabled **Continuous Deployment** for REF.   
 - REF started out as a set of inter-dependent, individually-versioned modules.  But coupling between the modules was so high this created problems every time a change was made.  I organised all the teams to move their code into a single build tree.  This meant developers could work on each other's modules and see immediately when their changes had broken other components.
 - I removed our Oracle Coherence dependency (saving millions of CHF in licensing fees).
 - Currently I am designing the reference architecture for REF2, which will be more "buffet" style than the original REF.  For this I am building out tutorials covering topics such as **Docker, REST, Security, Jenkins and Spring Boot** for developers of other projects to follow.
 
[/block]

[block]

#### Back Testing Project ####

Back Testing was a project built in CS using the REF architecture.  
 
- I ran a team responsible for building out an Automated Testing Framework for REF, and we also took care of building tests specific to the Back Testing Project.
- I ran a weekly workshop for developers and BAs on the Back Testing project to explain methodology and process.  We covered aspects of statistics (p-Values, Cramer von Mises, Sampling Dots), testing methodology (mocking, integration testing) and risk methodology (Monte-Carlo, Historic VaR) for an audience in multiple regions.

[/block]

[block]

### Aura Software Sept. 2010 - Oct. 2014

I was variously a Tech Lead, Architect and PM in a distributed consultancy building mainly **Learning Management System** (LMS) software for various clients.

- Applied various technologies on different projects, including **Javascript, Angular, jQuery, XML, JSON, Git, PHP, Wordpress, Ruby and Java**.  (LMS systems are generally *terrible*, so by using modern tools and techniques we were able to demonstrate clear competitive advantages.)
- Used platforms such as **AWS and Linode** to deploy our applications.
- Built front-end tests using tools like **Geb, Spock, Selenium** and  **PhantomJS**.
- Project Managed delivery of our software solutions using agile and waterfall approaches where appropriate.
- Built Kite9, an online, interactive **UML** editor using **SVG, Spring, XML and JQuery**.

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
- In conjunction with this, I built the **RepoVaR Back Testing** project.  In order to get a model FSA-approved, you have to back-test it.  I built the Back Testing software, which looked back through time to check that for a given historic period, our model’s predictions were correct.
- Over time, we discovered flaws in the methodology of our backtesting, but with a comprehensive understanding of the **repo product family** and how **VaR** was calculated for them, I was able to specify and then engineer a new back testing calculation to avoid these breaks.

[/block]

[block]

### Deutsche Bank Feb. 2002 – Mar. 2005

#### Tech Lead in the Risk and PnL Reporting Team.

- I introduced improved development practices to the team by bringing all source code under source control in **VSS** (later moved to **CVS**), with a single build process using **Ant**.
- I Introduced **Eclipse IDE**, which was a new thing back then.  
- I developed and delivered a complete global redesign and rollout of Risk’s website in 5 regions using **Java Servlets, JSP and Sybase**, based on the Deutsche Look-And-Feel guidelines.  I built a **JSP tag library** for all of the Deutsche interface elements, so other people could do the same with their websites.
- I was tech lead and architect on the **MIS3 Project**, which was a risk and PnL aggregation and reporting tool that brought together daily valuations and risk together with trade details from a variety of different risk and trade sources for use by downstream groups (margin management, risk controlling, accounts etc).
- MIS3 is notable because it used the *Inversion Of Control* pattern (which was new at the time) in the **Apache Avalon container** (a precursor to **Spring**).  MIS3 was horizontally scalable, distributed and redundant.
- Later on, I helped design an **Oracle data warehouse** for MIS3 data.
- MIS3 continues to be a key strategic system at Deutsche Bank.  Apparently, they’ve barely changed the code I wrote twelve years ago.
- Finally,  I provided mentoring and project leadership for offshore staff in Spain, and was made a member of Deutsche Bank’s talent programme.

[/block]

References available on request.

## Contact Details

- email: robmoffat@mac.com
- blog: http://robmoff.at
- twitter: @bobm_kite9
- github: https://github.com/robmoffat
- linkedin: https://linkedin.com/in/robmoffat
