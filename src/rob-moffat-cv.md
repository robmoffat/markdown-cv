# Rob Moffat 

## Profile

[aside]
#### Contacts
- robmoffat@mac.com
- Blog: http://robmoff.at
- Twitter: @bobm_kite9
- Github: https://github.com/robmoffat

[/aside]

I am a full stack developer, based in London or Essex.  I Specialize in build automation, automated functional testing and financial calculations.
I have done project management in the past when required, but I best fit as the development lead of a team, a job which I’ve now done in various
banking roles and elsewhere.

## Qualifications

-	First in B.Sc. (Hons.) Computer Science at Aston University (1997).
-	MBA (Hons.) at Warwick Business School (2007) 
-	Certified Java Enterprise Architect
- 	Certified Java Developer 
- 	4 A Levels, 8 A Grade GCSEs.

## Summary of Skills

- 11 years experience as senior developer on Java projects in investment banks.
- 18 years experience in analysis, design and development of software applications.
- Experience developing Java solutions continuously since 2000.
- In-depth understanding and experience of database architecture and optimisation techniques (Oracle, MySQL,  Sybase).
- Experienced tech-lead and mentor over many java projects, employing agile methods (like XP) with a variety of team sizes and ability levels.
- Experience with all manner of Java technologies such as: Hibernate, JPA, Ant, Maven, Gradle, Tomcat, Data Synapse, Oracle Coherence, Spring, Amazon EC2.
- Front end technologies:  Grails, WebSockets, React, Bootstrap, Spring Web, REST (HATEOAS) via Spring, 
- Experience building and debugging applications using JavaScript, jQuery, SVG, JSONP, CSS3, HTML5, WordPress, Drupal, PHP.
- Used to dealing with large, complex, long-running Risk / Regulatory projects with multiple stakeholders and distributed teams.
- Lots of experience as the technical lead on complex multi-client projects.

## My Open-Source Projects

(see github for further details)

### Concordion

I wrote an extension for Concordion (A Java Functional Testing Framework) to make it more suitable for testing financial calculations.   Calculations
are demonstrated on Excel spreadsheets (owned by Business Analysts) and are used to form the functional test cases of the project. 

### Pure4J

A Java code analysis tool for ensuring functional purity within a codebase.  Functionally pure software is less error-prone and orders of magnitude
easier to test, but usually you have to learn a new language such as Haskell to do it.  This tool allows you to use Java instead, limiting what you 
can do.

### Kite9 (in development)

Kite9 is a online software diagramming tool that (unlike say Visio) organises the layout of the diagrams for you.   You can try it at [Kite9.com](http://kite9.com).
Server side was Java, SpringMVC, IBATIS, MySQL running on Amazon EC2/Linode.  Client side written with jQuery, Grails, SVG, Bootstrap.

•	Made technical decisions regarding choices of technologies in-browser. Used Javascript, jQuery, RaphaelJS, HTML5, SVG.  Communicating via XML protocol (XStream, XMLSchema, AJAX, JSONP).
•	Set up Hudson (Jenkins), Maven build process with large suite of functional/JUnit tests. 

## Professional Experience

### Credit Suisse Oct. 2014 / Present

#### 





### Aura Software Sept. 2010 - Oct. 2014

#### Partner

Over the last 3 years I have spent time away from the finance industry bringing up my young family.  However, I continued to work on various projects as a part-time consultant (and partner) in Aura Software, who built learning software portals mainly in the medical equipment industry.
 
- I was tech lead on a project involving a distributed team to build a custom Learning Management System for Medtronic, a Fortune 500 medical equipment manufacturer (including: Javascript, jQuery, XML, JSON, Git, PHP, Wordpress).  LMS systems are generally *terrible*, so by using modern tools and techniques we were able to knock this out of the park.
- Organised testing strategy & test plans, performed releases, wrote documentation and handled requirements capture.  This was pretty important as there were multiple stakeholders, and little understanding of good project management practice before I got involved.   
- Architected and rolled out various successful web-based projects for clients within the medical / online learning sectors.  One to facilitate neurosurgeon training, another a portal for management of sales team training.  
### Royal Bank of Scotland Mar. 2005 – Sept. 2010

#### Java Tech Lead in Global Banking and Market’s Risk Team.

- Tech Lead on *E**: a Basel II Exposure At Default application using Java, Spring, Sybase, JMS, Hibernate - for 3 successful releases.  Guided developers’ choices in the architectural decisions and technologies used on this project.  This project was *critical* to RBS meeting the Basel II standards.  
- Introduced new functional testing techniques to ensure code was consistent with specifications by integrating Excel and JUnit tests using Apache POI.  This allowed better separation of the business analyst and developer roles within the E* project.  This approach was then adopted across future projects in Risk.  (In fact, this is broadly the approach used in the now open-source [Concordion Excel Extension](https://github.com/concordion/concordion-excel-extension)
- I introduced inversion-of-control (using Spring) to the Risk Department, adopted thereafter on several new projects.   This was kind of new back in 2005, but it’s pretty much the de-facto pattern now.
- Led the introduction of new software build techniques to Risk:  Maven, Cruise Control and automated regression testing and unit testing. 
- Introduced Oracle Coherence to Risk by architecting and delivering Gateway, a limit-checking service for prime brokerage clients, with high-frequency, low-latency requirements (XStream, RMI, Java, Spring, Servlets).  Again, back in 2006, the idea of eventually-consistent caching and distributed systems were fairly novel.  They are now broadly accepted and there are much better options than Coherence today.
- Project-Managed and delivered the long-running Basel II RepoVaR project over several releases, defining GBM’s internal model approach using VaR for Repo-style products (inc. DataSynapse).  Again, this was another critical Basel II project:  without this, the bank relied on the more capital-intensive haircut approach, but with RepoVaR we got sign-off from the FSA to use our own internal model which was less capital intensive.
- RepoVaR Back-Testing:  In order to get a model approved, you have to back-test it.  I was tech lead building the back-testing software, which looked back through time to check that for historic periods, our model’s predictions were correct.
- Specified and developed an approach to close large breaks in RepoVaR back-testing.  This involved a comprehensive understanding of the repo product family and how VaR was calculated for them, and then engineering a new back-testing calculation to avoid these breaks by manipulating the portfolio cash flows to reflect how the portfolio changed after the VaR was originally calculated.
- Made a member of Royal Bank of Scotland’s talent programme.

### Deutsche Bank Feb. 2002 – Mar. 2005

#### Tech Lead in the Risk and PnL Reporting Team.

- Tech lead on the *MIS3 Project*: This was a risk and PnL aggregation and reporting tool that brought together daily valuations and risk together with trade economics from a variety of different risk and trade sources for use by downstream groups (around 10 groups, including margin management, risk controlling, accounts etc).
- Architected MIS3 in a scalable, distributed, redundant way using the Inversion of Control pattern using Apache Avalon (a precursor to Spring) and J2EE.
- MIS3 continues to be a key strategic system at Deutsche Bank.  Apparently, they’ve barely changed the code I wrote *twenty years ago*.  Just lazy.
- Developed and delivered a complete global redesign and rollout of risk’s website in 5 regions (Java Servlets, JSP, Sybase).
- Helped design and procure and architect the Oracle data warehouse for MIS3.  
- In 2002, I introduced improved development practices to Risk: bringing all source code under source control in VSS (later moved to CVS), with a single build process using Ant, as well as introducing the Eclipse IDE to the Risk IT team.
- Provided mentoring, and project leadership for offshore staff in Spain.
- Made a member of Deutsche Bank’s talent programme.

### Contractor at RI3K as J2EE Developer July 01 - Oct. 01

#### Consultant

RI3K created a cutting-edge B2B application for trading reinsurance contracts.  My contract spanned the final stages of development and launch.  Now part of Qatar Insurance Services.

- Put in place a build process managing all the deployment platforms, (on NT, Linux and HPUX using Apache, Tomcat and CapeClear) for UK and Singapore versions and rolled out periodically to these sites.
- Developed several areas of the system (using Java, WebLogic, EJB, Oracle and extensive XSLT), including Contracts and negotiation workflows, working closely with in-house experts.  


### Contractor at Wide Learning May 99 – June 01

Purveyor of online software courses.  Sold after the .com crash.

- I upgraded the company’s intranet software using servlets, XML and XSLT.  
- As developer, helped design and implement Wide’s e-learning Content Delivery System, allowing Wide to real-time render courseware that tailors learning content to 
the requirements of the student (Java, EJB, J2EE, WebLogic).

[aside]
#### References
##### Matthew Harris (matt.r.harris@gmail.com)
- Consultant Programme Manager and Architect, Barclays Capital 
- (Manager whilst in Risk Reporting Team, Deutsche Bank)
##### Andrew Spruce (andrew.spruce@gmail.com)
- Global Head of Rates Trade Capture and Clearing at Barclays Capital
- (Colleague on E* project whilst at RBS) 
##### Tim Hedger (tim.hedger@rbs.com)
- Head of Control & Assurance at Royal Bank of Scotland
- (Head of Risk IT while on E* project at RBS)
[/aside]