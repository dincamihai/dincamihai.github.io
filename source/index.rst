Mihai Dincă - Resume
====================

**Nürnberg, Germany**


Contact
-------

- **Online Resume**: https://dincamihai.github.io
- **Email**: dincamihai@gmail.com
- **Github**: https://github.com/dincamihai
- **Linkedin**: https://linkedin.com/in/mdinca


Summary
-------

I am a **Lead/Staff Backend Engineer** and **Architect** specializing in high-performance, data-intensive SaaS platforms. I apply structured frameworks like **SPAR** to align technical implementation with business requirements.

My core focus:

*   **Distributed Systems Design:** Architecting scalable, event-driven systems on AWS (Serverless, SQS/SNS, Step Functions).
*   **Technical Leadership:** **Servant Manager** driving architectural decisions, mentoring engineers, and fostering a "manage work, not people" culture.
*   **System Resilience:** Evolving monolithic architectures into decoupled systems to reduce blast radius and eliminate release friction.
*   **Process & Security:** Contributing to **ISO 27001 / ISMS** frameworks to align engineering with compliance goals, focusing on risk assessment and asset management.

**Core Tech Stack:** Python, Golang, AWS (Step Functions, SQS/SNS, Lambda), Terraform, SQL/NoSQL.

`[See the courses section] <http://dincamihai.github.io/#courses>`_


Experience - Software Engineering
---------------------------------

Technical Engineering Manager & Staff Engineer - Exasol GmbH
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Apr 2021 - NOW

*   **Situation:** Exasol provided its high-performance database as a SaaS offering, initially built on a monolithic control plane.
*   **Problem:** Operations relied on a fragile polling mechanism, requiring downtime for releases. The design lacked customer isolation (large blast radius), and the billing system couldn't support new instance families (r6id) needed for global growth.
*   **Action:** Led a 7-person team to implement a decoupled, **event-driven architecture** (AWS Step Functions, SQS, SNS) in parallel. Managed a **phased rollout strategy** to migrate operations incrementally and extended the billing engine to support new hardware and regions.
*   **Result:** Achieved release reliability by decoupling services, improved system resilience by reducing the blast radius, and enabled business growth by launching new global regions and instance families.

*   **Situation:** The SaaS platform required ISO 27001 certification to meet enterprise security standards.
*   **Problem:** The platform lacked documented policies, procedures, and a comprehensive asset inventory. Without this visibility, we could not identify missing controls, assess risks, or align with the corporate ISMS.
*   **Action:** Attended specialized ISO 27001 training to support the technical integration into the corporate ISMS. I established the asset inventory, implemented a risk assessment framework, and authored policies covering Confidentiality, Integrity, and Availability (CIA). I also collaborated with the AWS TAM on security evaluations.
*   **Result:** Established a verifiable security posture for the SaaS platform and aligned technical operations with the corporate ISMS, facilitating the certification process.

*   **Situation:** The platform relied on a legacy monitoring system to track service health.
*   **Problem:** The system generated frequent false positives (alert fatigue) and was a "black box," making it difficult to debug why alerts fired or failed to trigger.
*   **Action:** Designed and implemented an **AWS-native, event-driven alerting engine**. I utilized **DynamoDB** to manage alerting parameters dynamically, allowing for granular control without code deployments.
*   **Result:** Effectively eliminated false alerts, provided full auditability of alert evaluations through logging, and enabled support teams to troubleshoot issues independently.

*   **Situation:** The SaaS development team needed to scale from a single backend engineer to a full cross-functional team (7 members) to meet product goals.
*   **Problem:** Initially, the team lacked UI expertise and lacked structured hiring or onboarding processes for the new multi-disciplinary roles.
*   **Action:** Designed the technical interview process and conducted evaluations to hire two UI, two backend, and two cloud engineers. I established an onboarding framework and a bi-weekly 1-on-1 structure focused on collaboration and roadmap delivery.
*   **Result:** Successfully scaled the team to 7 members, established a collaborative culture, and delivered all planned roadmap items for 2025.

**Key Responsibilities:**
*   **Architecture & Development:** Hands-on development of core SaaS components using Python, Golang, and AWS Serverless.
*   **Technical Leadership & Servant Management:** Driving cross-functional technical initiatives, conducting architectural design reviews, and mentoring senior/mid-level engineers. I manage operational overhead (support, releases, rollout strategies) and perform background refactoring to enable the team to focus on feature implementation. I conducted bi-weekly 1-on-1s, managed performance reviews, and established frameworks for goal setting and evaluation.
*   **Roadmap & Planning:** Contributing to roadmap definition by identifying and sequencing work item dependencies. Defining rollout strategies and coordinating task distribution to align with delivery timelines.
*   **Business & Hardware Expansion:** Extended the billing engine to support new instance families (r6id) and managed the technical expansion into multiple global AWS regions.
*   **Stack:** Python, Golang, AWS, Terraform, SQL, Serverless.
*   **Release Reliability:** Decoupled core services, moving away from heavy monolithic releases and reducing deployment-related downtime.
*   **Enhanced Isolation:** Improved system resilience by ensuring better isolation between customer environments, reducing the potential blast radius.
*   **Business Enablement:** Integrated new instance families (e.g., r6id) into the billing system and expanded platform operations into new global regions.

**Key Responsibilities:**
*   **Architecture & Development:** Hands-on development of core SaaS components using Python, Golang, and AWS Serverless.
*   **Technical Leadership & Servant Management:** Driving cross-functional technical initiatives, conducting architectural design reviews, and mentoring senior/mid-level engineers. I manage operational overhead (support, releases, rollout strategies) and perform background refactoring to enable the team to focus on feature implementation. I conducted bi-weekly 1-on-1s, managed performance reviews, and established frameworks for goal setting and evaluation.
*   **Roadmap & Planning:** Contributing to roadmap definition by identifying and sequencing work item dependencies. Defining rollout strategies and coordinating task distribution to align with delivery timelines.
*   **Business & Hardware Expansion:** Extended the billing engine to support new instance families (r6id) and managed the technical expansion into multiple global AWS regions.
*   **Stack:** Python, Golang, AWS, Terraform, SQL, Serverless.

Various Projecs
^^^^^^^^^^^^^^^
January 2020 - May 2021

* Various service providers API integrations:

    + Google Maps venue availability and reservation
    + Payments integration with Stripe
    + Apple Login

* Web scraping
* Test performance - data collection, measurement and improvement
* Data storage and SQL queries optimisation
* Visualisations in Graphana
* Code reviews

Python Developer - SUSE Linux GmbH
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
April 2016 - December 2019

* Work on integrating Salt with SUSE Manager
* Develop, package and maintain the Salt package for SUSE and OpenSUSE
* Test the Salt package on SUSE Manager supported OSs using Docker
* Fix bugs and implement features in SUSE Manager - Java component
* Help improving scalability and performance
* Debug complex setups consisting of multiple running services and distributed systems

Web Developer - Freelance
^^^^^^^^^^^^^^^^^^^^^^^^^
October 2013 – April 2016

* Build a REST Hyperlinked API with nested resources to be used for integrating an online service with partners
* Entirely responsible for implementing the authentication, permissions and structure of the API
* Optimize DB queries where required
* Document the API behaviour for developers and non-technical persons with BDD tests (Cucumber style)
* Build REST APIs to support the front-end
* Identify and refactor the key aspects of the application before they would become a blocking issue for extending the service
* Participate in improving the development workflow to better organize the tasks and allow Continuous Integration
* Implement front-end features with MVC structure for preparing and displaying the data obtained from the API
* Write BDD tests for front-end

Projects
""""""""

`iMedicare <https://imedicare.com/>`_
*************************************

* stack: Flask, Peewee, PostgreSQL
* my contribution:

    + Help building the APIs used by the front-end
    + Improve the search performance by using Postgresql fulltext search scoring feature
    + Perform DB queries performance comparisons for optimisation purposes

`Video Interviewing Platform <http://viasto.com>`_
**************************************************
* stack: Django, MySQL, Celery
* my contribution:

    + build the API using Django Rest Framework
    + improve the permission system
    + refactor and fix large parts of the code
    + improve the development workflow
    + fix bugs
    + implement new functionality
    + add BDD style tests for permissions to serve as documentation and better organisation of the tests

`Hotel Maintenance Platform <http://roomchecking.com>`_
*******************************************************
* stack:
    + frontend: backbone.js, marionette.js, coffeescript
* my contribution:

    + build a calendar application to show the hotel rooms and their state
    + implement filtering and sorting capabilities
    + create a state machine wizard to allow json configuration of the states

`AgriPlace <http://www.agriplace.org>`_
***************************************
* stack: Django, Angular.js, MySQL, coffescript
* my contribution:

    + add various features based on the client's specifications
    + build the API
    + add functional tests
    + small frontend contribution (Angular.js)


Web Developer - `Eau de Web <http://www.eaudeweb.ro/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
April 2012 – October 2013 (1 year 7 months)

Projects
""""""""

`Digital Agenda <http://digital-agenda-data.eu/>`_
**************************************************
* sources: https://github.com/eaudeweb/scoreboard.visualization
* stack:
    + frontend: backbone   + highcharts
    + backend: Plone (python framework) and Virtuoso(RDF database)
* my contribution:

    + develop chart customization wizard features (frontend)
    + develop json configurable chart types (frontend)
    + process and prepare data before passing it to charts (frontend)
    + add required API backends (backend)
    + write SPARQL queries to retrieve data from DB using Jinja templates (backend)

`Central Data Repository <http://cdr.eionet.europa.eu/>`_
*********************************************************
* sources: https://github.com/eea/Products.Reportek
* stack: Zope (python framework)
* my contribution:

    + develop new features based on the customer's specifications
    + refactoring old code
    + convert DTML templates to ZPT
    + customer support and bug fixing

Central Data Repository Converters
**********************************
* description: internal API service for convertion of files between various formats
* sources: https://github.com/eea/reportek-converters
* stack: Flask (python microframework)
* my contribution:

    + create the API
    + support JSON configuration
    + integrate with [Central Data Repository]
    + migrate the existing conversion tools and scripts to the service
    + tweak and create new converters (eg: convert map files to jpg)


Experience - Aircraft Maintenance
---------------------------------

Base Maintenance A320 - Meridiana Maintenance
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
October 2011 – December 2011 (3 months)

Responsibilities

* "C" Check tasks

Aircraft Engineer - Jetran Air
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
October 2011 – December 2011 (3 years 5 months)

Responsibilities

* Reliability Reports - I've built a Java web app to generate the reports
* Network and System Administrator
* Training Manager
* Boeing Primary Focal

Engineering Referent - Jetran Asset Management
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
November 2006 - June 2008 (1 year 8 months)

Responsibilities

* Network and System Administrator
* Boeing Primary Focal


Education
---------

Courses
^^^^^^^
* `ISO 27001 - Information Security Management System (ISMS)`
* `Architecting with Google Kubernetes Engine <https://www.coursera.org/account/accomplishments/specialization/WVZF64YJJJ3B>`_:

    - Google Cloud Platform Fundamentals: Core Infrastructure
    - Architecting with Google Kubernetes Engine: Foundations
    - Architecting with Google Kubernetes Engine: Workloads
    - Architecting with Google Kubernetes Engine: Production
    
* `Functional Programming in Scala Specialization <https://www.coursera.org/account/accomplishments/specialization/Z5UYPKG4EF7K>`_
* `Big Data Analysis with Scala and Spark <https://www.coursera.org/account/accomplishments/verify/8HY38CR7PNYH>`_
* `Parallel programming in Scala <https://www.coursera.org/account/accomplishments/certificate/M82E6AVGYLGZ>`_
* `Functional Program Design in Scala <https://www.coursera.org/account/accomplishments/certificate/3S5LD6QEER6S>`_
* `Functional Programming Principles in Scala <https://www.coursera.org/account/accomplishments/certificate/EV6WJ5T3XCX4>`_
* `Programming with Google Go Specialization <https://www.coursera.org/account/accomplishments/specialization/certificate/F6QTTASXTQBY>`_
* `IBM - Applied Data Science Specialist <https://www.youracclaim.com/profile/badges/d8161db4-e51d-4914-8f0c-895481fba561>`_
* `Coursera - IBM - Advanced Machine Learning and Signal Processing <https://www.coursera.org/account/accomplishments/verify/9BEMXNW7YM8D>`_
* `Coursera - IBM - Fundamentals of Scalable Data Science <https://www.coursera.org/account/accomplishments/verify/P6ECMC9KJMQX>`_
* `Coursera - IBM - Applied Data Science Capstone <https://www.coursera.org/account/accomplishments/verify/2NSFRX6K8GDJ>`_
* `Coursera - IBM - Data Visualization with Python <https://www.coursera.org/account/accomplishments/verify/CR3DJYXKARLJ>`_
* `Coursera - IBM - Data Analysis with Python <https://www.coursera.org/account/accomplishments/verify/JHVJ4DYQHSUZ>`_
* `Coursera - IBM - Python for Applied Data Science <https://www.coursera.org/account/accomplishments/verify/DC2V8ERPZ7ZK>`_
* Udacity - Self-Driving Car Engineer (Term1 completed)
* `Coursera - Sequence Models <https://www.coursera.org/account/accomplishments/verify/SFVSAU7DWRP5>`_
* `Coursera - Convolutional Neural Networks <https://www.coursera.org/account/accomplishments/verify/6G3R45CEH3NP>`_
* `Coursera - Structuring Machine Learning Projects <https://www.coursera.org/account/accomplishments/verify/W3VLWUVCTTG5>`_
* `Coursera - Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization <https://www.coursera.org/account/accomplishments/verify/Z4VXQ6SED9PM>`_
* `Coursera - Neural Networks and Deep Learning <https://www.coursera.org/account/accomplishments/verify/F6BHNA4DES46>`_
* Coursera - Machine Learning - Andrew Ng
* C++ for programmers - Udacity
* C++ - sololearn
* Statistics and Probability - KhanAcademy
* Scrum Training - SUSE
* Airbus A320 - B2 Course
* B2 Part-66 License
* Trainee OJT A318/319/320/321 CFM-56 - TAROM


Degrees
^^^^^^^


Information Engineering Degree
""""""""""""""""""""""""""""""
Electrical, Electronics and Communications Engineering - "Politehnica" University of Bucharest
2002 – 2008


Relevant Courses
****************

* Java
* C
* Parallel programming with POSIX C
* Matlab
* Operating Systems
* Computer Architecture
* Computer Networks
* PHP
* Statistics and Probability


Aid Programmer - Level 2
""""""""""""""""""""""""
"I.L. Caragiale" College of Bucharest
1998 - 2002


Relevant Courses
****************

* Pascal
* FoxPro
* Data Structures and Algorithms
* Mathematics
* Physics


Languages
---------

    - English - Advanced
    - German - Intermediary
    - Italian - Intermediary
