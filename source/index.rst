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

I am a **Lead/Staff Backend Engineer** and **Architect** specializing in high-performance, data-intensive SaaS platforms.

My core focus:

*   **Distributed Systems Design:** Architecting scalable, event-driven systems on AWS (Serverless, SQS/SNS, Step Functions).
*   **Technical Leadership:** **Servant Manager** driving architectural decisions, mentoring engineers, and fostering a "manage work, not people" culture.
*   **System Resilience:** Evolving monolithic architectures into decoupled systems to reduce blast radius and eliminate release friction.
*   **Process & Security:** Contributing to **ISO 27001 / ISMS** frameworks to align engineering with compliance goals, focusing on risk assessment and asset management.

**Core Tech Stack:** Python, Golang, AWS (Step Functions, SQS/SNS, Lambda), Terraform, SQL/NoSQL.

`[See the courses section] <http://dincamihai.github.io/#courses>`_


Strategic Impact & Key Achievements
-----------------------------------

**Architecture: Monolith to Event-Driven Migration**

*   **Situation:** A high-performance database SaaS product relied on a monolithic control plane with a fragile polling mechanism and a centralized management node for orchestration.
*   **Problem:** The architecture required downtime for releases, lacked customer isolation, and used a management node that acted as a scaling bottleneck and a single point of failure.
*   **Action:** Led a 7-person team to implement a decoupled, **event-driven architecture** (AWS Step Functions, SQS, SNS). I re-engineered the orchestration layer to use the database API directly within **Step Functions**, eliminating the centralized management node. Managed a **phased rollout** strategy to migrate operations incrementally.
*   **Result:** Achieved release reliability (zero-downtime deployments), removed a major scaling bottleneck, and increased the system's capacity for concurrent platform operations.

**Security: ISO 27001 Compliance & ISMS Integration**

*   **Situation:** The SaaS platform required ISO 27001 certification to meet enterprise security standards.
*   **Problem:** The platform lacked documented policies, procedures, and a verifiable asset inventory, making risk assessment and audit readiness impossible.
    **Action:** Attended specialized ISO 27001 training and led the technical integration into the corporate ISMS. I established the asset inventory, applying a **criticality framework** to assign risk scores and prioritize controls. I implemented a risk assessment framework and authored CIA policies, while collaborating with the AWS TAM on security evaluations.
*   **Result:** Established a verifiable security posture, aligned operations with the corporate ISMS, and facilitated a successful certification process.

**Observability: Reliable Event-Driven Alerting**

*   **Situation:** The platform relied on a legacy monitoring system for service health.
*   **Problem:** High rates of false positives (alert fatigue) and a "black box" design made debugging difficult and configuration rigid.
*   **Action:** Designed and implemented an **AWS-native, event-driven alerting engine** using DynamoDB for dynamic configuration.
*   **Result:** Effectively eliminated false alerts, provided full auditability of alert evaluations, and empowered support teams to troubleshoot issues independently.

**Leadership: Scaling High-Performance Teams**

*   **Situation:** The SaaS development team needed to scale from a single backend engineer to a full cross-functional unit (7 members).
*   **Problem:** The team lacked UI/Cloud expertise and had no structured hiring or onboarding processes.
*   **Action:** Designed technical interviews (culture-fit & system design) and hired 5 engineers (UI, Backend, Cloud). Established an onboarding framework and a collaborative 1-on-1 structure.
*   **Result:** Successfully scaled the team, established a culture of delivery and continuous improvement, and delivered all planned roadmap items for 2025.


Employment History
------------------

**Technical Engineering Manager & Staff Engineer** - Exasol GmbH (Apr 2021 - NOW)
    *Focus: SaaS Architecture, Team Leadership, Security Compliance, AWS Serverless.*

**Python Developer** - SUSE Linux GmbH (Apr 2016 - Dec 2019)
    *Focus: SUSE Manager, Salt Integration, Scalability, Packaging.*

**Web Developer (Freelance)** - Various Clients (Oct 2013 - Apr 2016)
    *Focus: REST APIs, Flask/Django, Frontend Integration, Optimization.*

**Web Developer** - Eau de Web (Apr 2012 - Oct 2013)
    *Focus: Data Visualization, Plone, Zope, SPARQL.*

**Aircraft Maintenance Engineer & Referent** - Jetran Air / Meridiana (2006 - 2011)
    *Focus: Safety-Critical Systems, Highly Regulated Environments, Reliability Reporting.*


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
""""""""""""""""""""""""""""
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
"""""""""""""""""""""""
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
