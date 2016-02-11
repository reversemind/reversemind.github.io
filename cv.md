
Eugene V. Kalinin

### Senior Java Developer, Architect


>
> [Linkedin](https://www.linkedin.com/in/kalynin) / [GitHub](http://www.github.com/reversemind) / [Twitter](http://www.twitter.com/konilovsky)




SUMMARY
------------------------

Experienced and motivated software developer/architect with extensive knowledge in performance critical large-scale web applications.
Excellent attention to details, balanced with the ability to make near-optimal decisions.

Passionate to working with cutting-edge technologies, to utilize them as crafted tools to form developed software solutions for resiliency, performance and scaling.
Wide knowledge in the development, engineering, operations and business fields.

Particularly experienced in resolving stability and performance issues in production systems.
Strong interpersonal, problem-solving and teamwork skills.


TECHNICAL SKILLS
------------------------------

Back-end(server-side) `Java`, HTTP&REST, `microservices` approach, performance, `resiliency`, stability, scalability, `continuous delivery` approach, auto configuration and deployment.

| | |
|:------------- |:-------------|
| `Languages` |  `Java`, Groovy, Scala, Clojure, C/C++, R, Python |
| `Java(J2SE)` | core, Swing, annotations, collections, multithreading, reflection, network, JDBC, JVM tuning & profiling, JMX|
| `Java Enterprise (J2EE)` | Servlet/JSP, JSF, CDI, JNDI, EJB, JTA, JAAP, JSTL, JMS, JPA |
| `Spring Framework` | IoC, MVC, Data, Boot, Security, Aspects(AOP), Batch, AMQP, Test, Cloud|
| `ORM` | Hibernate, EclipseLink, OpenJPA |
| `Messaging` |  ActiveMQ(JMS), RabbitMQ(AMQP) |
| `RESTful / Web Services` | SOAP, XML(DTD/XSD, XSLT, XPath), WSDL, JAX-WS, JAX-RS, Apache CXF, JSON, Jackson |
| `Frontend` |  HTML/CSS/`Java`Script/AJAX, jQuery, JSON, JSP|
| `Testing` | JUnit, TestNG, Mockito, Spock, Apache JMeter, Selenium, Docker|
| `Databases SQL` | Oracle, PostgreSQL, MySQL, HSQLDB |
| `Databases NoSQL` | Redis, MongoDB, HBase, Cassandra, CouchBase |
| `Distributed` | REST, HTTP, SSL, SOAP/WS, RMI |
| `Patterns` | GoF, Patterns of Enterprise Application Architecture(EAA), Enterprise Integration Patterns (EIP), Refactoring patterns |
| `Web/App Servers` | Jetty, Tomcat, JBoss, GlassFish, WebLogic, NGINX, Apache
| `High Availability/Failover` | Clustering, Replication, Heartbeat, HAProxy|
| `Cloud` | Amazon AWS EC2, S3, Beanstalk; Google App Engine & Compute Engine, Docker|
| `Scripting` |  Bash, Python, Groovy|
| `OS` | Linux, MAX, Windows |
| `Development Tools` |   |
| `Version control systems` | CVS, Subversion, Git |
| `Build tools` |  Ant, Maven, Gradle, Jenkins, Team City, Atlassian Bamboo|
| `IDE` |  IntelliJ IDEA, Eclipse, NetBeans |
| `Collaboration/bug tracking` | JIRA, Redmine, GitHub, GitLab, Atlassian Stash |
| `Other` | (tools, libs, approaches, paradigms): Apache Lucene/SOLr, Apache HADOOP, EhCache, Terracota, OSGI, Hazelcast, OpenGL, CUDA, Matlab, UML, OOP, TDD, IDEF0, IDEF3, ARIS, PMBOK, RUP, XP, Agile(Scrum, Kanban) |


EMPLOYMENT
------------------------

##### Java Lead Developer / Software Architector
>JSC "Company TransTeleCom" (trademark - TTK)
>
>2012 – 2015 Moscow

I worked as an architect and lead developer on CRM platform (millions of users) for telecommunication company.

I designed a high performance asynchronous shared middleware framework for JVM-based solutions available on GitHub (based on `Java`, `Spring`, `Netty`, `Kryo`, `Zookeeper`) with service auto-discovery, metrics sharing, load-balancing. Integrated legacy products with new systems and that fit to microservices approach.

Developed a CRM architecture as a distributed, extendable and scalable solution with `microservices` approach. Each business module inside a CRM platform is loosely coupled with shared activity metrics (via `Zookeeper`) and is load-balanced via multiple instances approach. It speeded up a development process for new services, resolved a scaling and resilience issues.

Developed key CRM modules: Organization structure (groups, roles, LDAP integration & etc.), Addresses(Locations), Billing, Call-center, Trouble-ticket. Address module of CRM is based on Google maps plus implemented fast intellectual search (`Lucene/SOLr`) with precision till a separate house.

Localized and fixed some performance issues on production system - via a sequence of steps from system/application/module logs analysis, profiling (custom metrics, jconsole, jprofiler & etc.), to targeted load(stress) testing.

Evangelization of new approaches for designing distributed systems (loosely coupled, reactive, microservices and etc.) across distributed team.

Successfully built for distributed team an infrastructured stack for software development based on Continuous Integration / Continuous Delivery model. Utilized an Atlassian products (JIRA, Confluence, Bamboo, Stash) which also included a repository and artifact management tool Nexus of Sonatype.

`Technologies`: `Java`, Servlet/JSP, `Spring`, JPA (Hibernate/EclipseLink), Oracle, PostgreSQL, Apache Cassandra, JBoss, Tomcat, Apache Lucene/SOLr, `Linux`, Apache `Zookeeper`, Netty, `NGINX`, Groovy, HTML, CSS, jQuery, Maven, Git


##### Founder / Software Architector / Lead developer
> Social Analytics Platform / Startup for social data analytics
>
> 2010 – 2012 Moscow

Designed services and tools for intelligent marketing decisions of different businesses size in order to help business understand it impact on social networks;

Calculated params like: user experience and attitude to a company; Key persons identification (influencers) in social graph, user profile metrics, user addictions, user classifications and clasterization, bot detection in social networks.

Real-time processing of `more than 400 requests/second`, more than `15 terabytes` of data for analysis. Multi-threaded сrawlers with orchestration and scheduling, social network API utilization, stemming, words normalization, semantic extraction.

`Technologies`: `Java`, Spring, Amazon `AWS` EC2/S3, Apache `Hadoop`, HBase, Apache Mahout, Apache Lucene/SOLr, RabbitMQ


##### Senior Java Developer / Java Developer
> JSC "MPO Electromontazh" - Largest Moscow retailer of electrotechnical products
>
> 2006 – 2012 Moscow

Played a key role as an architect and senior developer on various valuable projects for the retail company’s on-line store (more than 40thousand items). Back-end data processing and collection, asynchronous distributed integration solutions, performance and stability analysis with further system turning. Maintained direct interaction with business and company’s departments to gather requirements and facilitate successful integrations of custom software, that was basically based on opensourse projects.

Successfully developed an innovative smart-reactive, multi-level caching framework for on-line company store. Increased stability for high-load traffic from 7 `up to 500 HTTP requests/seconds`. Throughput value was measured with custom designed technique on production and virtual (test) environment.

Developed and facilitates company on-line store analytic system (KPI system for on-line store; clustering of website clients; automatic reports generating) for marketing department. Analytic system is based on a NOSQL solution (Hadoop cluster with Map/Reduce tasks) and MongoDB/PostgreSQL. Technologies: `Java`/Spring, Apache `HADOOP`(Map/Reduce), Groovy, GWT/SmartGWT, PostgreSQL, MongoDB

Designed and implemented a geographically distributed asynchronous integration solution for back-office, on-line store and warehouses (price, order status, stock resources, discounts per item). Facilitates integration with heterogeneous environment of the company’s software and current business-processes. Increased fault-tolerance of the retailer, guaranteed time delivery of orders. Technologies: `Java`/Spring, RabbitMQ, JMX, Spring, Tomcat, GlassFish, Enterprise Integration Patterns.

`Technologies`: `Java`(J2SE/J2EE), Servlet/JSP/JSTL, RabbitMQ, JMX, Spring, JPA (Hibernate/OpenJPA/EclipseLink), Oracle, PostgreSQL, MongoDB, HSQLDB, SWT, Swing, Terracotta, OSGI, Apache Lucene/SOLr, EhCache, Linux, Apache Tomcat, GlassFish, NGINX, Groovy, HTML, CSS, jQuery, Maven, Ant


##### Java Developer
> JSC "Sukhoi Civil Aircraft"
>
> 2004 – 2006 Moscow

Work on team resposible for designing, implementing and supporting a company corporate website (OpenCMS). Optimized Tomcat for web-traffic (JVM-optimization).

Have developed an automated system for visualization of max reachable airplane distance (on Earth) and rendering it into hi-resolution image.

Successfully developed custom front-end and back-end solution for marketing and sales departments according to gathered requirements. It facilitates online calculations (a tens of parameters), comparisons and visualizations of key features of new airplane vs to competitors.

Organized pipeline for data transfer from CAD systems to Maya system for further visualization; tuning net rendering, shaders programming. It simplifies getting a photorealistic images of airplane and different aircraft details to support sales and patenting.

`Technologies`: `Java`(J2SE/J2EE), Serlvet/JSP, Tomcat, OpenCMS, JDBC, Oracle DB, `Java`(Swing), Maya, MEL, TCL, Pixar RenderMan


#### Java Developer
> 3D Wireless Games Company (Superscape partner)
>
> 2003 – 2004 Moscow

Worked on team responsible for development, optimization and testing of mobile 3D `Java` games for J2ME platform (full cycle). Games porting to J2ME platform (`Java`). Developed several 3D games (final releases).
Games performance optimization (team work).
Designed and implemented in the company a data flow blueprint between 3D-graphic designers and programmers. Improved implementation code of standard (JSR-184/M3G) Swerve Engine (fixed some bugs in 3D matrix projections)

`Technologies`: `Java`(J2ME) 3D, JSR-184/M3G(Swerve engine)


SUMMARY OF SKILLS
------------------------------
Senior Java Developer with 8+ years of experience in requirements analysis, design, development, implementation, production support of `Java`/J2EE web and enterprise applications.

* Analysis of functional and system requirements;
* Analysis and optimization of a system performance, scalability and stability;
* Solid skils in OOP, TDD and UML;
* Design and development of complex, integration, distributed, scalable solutions.
* Experience in client-server application and multi-tier environment, clusters building and load balancing, developing of asynchronous and event-driven systems;
* Experience in multi-threaded applications building;
* Software testing (load-testing, functional, regression)
* Relational database designing;
* Experience in a company business processes description;
* Experience in design and refactoring patterns (GoF, Patterns of Enterprise Application Architecture (EAA), Enterprise Integration Patterns, Refactoring patterns);
* Experienced in Map/Reduce, distributed file systems (HDFS/Hadoop);
* Standards W3C (HTML, CSS, XML, XSLT etc.)
* Protocols  TCP, HTTP, SSL;
* Experience in application of control systems of versions  CVS, SVN, Git and  bug-tracking instruments (Redmine, JIRA, TeamCity);
* Familiar with methodologies  PMBOK, RUP, XP, Agile(Scrum, Kanban)


EDUCATION
------
##### Bauman Moscow State Technical University
> Master's degree, graduated with honors
>
> 1993 – 1999
>
> Biomedical Engineering

##### Higher School of Economics
> Master of Business Informatics (MBI)
>
> 2008 – 2009


INTERESTS
------
Running, Artificial Intelligence, Machine Learning, Computer Vision
