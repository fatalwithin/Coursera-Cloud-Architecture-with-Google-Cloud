- [Intro](#intro)
  - [Understanding the Professional Cloud Architect Certification](#understanding-the-professional-cloud-architect-certification)
  - [Exam Guide Outline](#exam-guide-outline)
- [Case Studies](#case-studies)
  - [Mounkirk Games](#mounkirk-games)
  - [Mountkirk Games Case Study Analysis](#mountkirk-games-case-study-analysis)
  - [Dress4Win](#dress4win)
  - [Dress4Win Case Study Analysis](#dress4win-case-study-analysis)
  - [TerramEarth](#terramearth)
  - [TerramEarth Case Study Analysis](#terramearth-case-study-analysis)
  - [TerramEarth Sample Solution](#terramearth-sample-solution)
  - [Review](#review)
- [Preparing for Business Design](#preparing-for-business-design)
  - [Designing and Implementing](#designing-and-implementing)
  - [Designing a solution infrastructure that meets business requirements](#designing-a-solution-infrastructure-that-meets-business-requirements)
  - [Case Study 1](#case-study-1)
- [Preparing for Technical Design](#preparing-for-technical-design)
  - [Designing a solution infrastructure that meets technical requirements](#designing-a-solution-infrastructure-that-meets-technical-requirements)
  - [Designing Network, Storage, and Compute Resources](#designing-network-storage-and-compute-resources)
  - [Creating a Migration Plan](#creating-a-migration-plan)
  - [Practice Exam Questions 1](#practice-exam-questions-1)
- [Preparing for Managing](#preparing-for-managing)
  - [Case Study 2](#case-study-2)
- [Preparing for Data Processing](#preparing-for-data-processing)
  - [Configuring individual Storage Systems](#configuring-individual-storage-systems)
  - [Data transfer](#data-transfer)
  - [Cloud Storage](#cloud-storage)
  - [Data processing to Machine Learning](#data-processing-to-machine-learning)
- [Preparing for Compute](#preparing-for-compute)
  - [Configuring Compute Systems](#configuring-compute-systems)
  - [Microservices, Containers, Data Processing, and IoT](#microservices-containers-data-processing-and-iot)
  - [Experiment: Containers and GKE video (Like/Dislike)](#experiment-containers-and-gke-video-likedislike)
  - [Practice Exam Questions 2](#practice-exam-questions-2)
- [Challenge Lab](#challenge-lab)
- [Preparing for Optimizing and Operating](#preparing-for-optimizing-and-operating)
  - [Case Study 3](#case-study-3)
- [Preparing for Security and Compliance](#preparing-for-security-and-compliance)
  - [Designing for Security](#designing-for-security)
  - [Designing for Legal Compliance](#designing-for-legal-compliance)
  - [Practice Exam Questions 3](#practice-exam-questions-3)
  - [Case Study 4](#case-study-4)
- [Preparing for Analyzing Processes](#preparing-for-analyzing-processes)
  - [Analyzing and defining business processes](#analyzing-and-defining-business-processes)
  - [Developing procedures to test resilience](#developing-procedures-to-test-resilience)
  - [Practice Exam Questions 4](#practice-exam-questions-4)
  - [Case Study 5](#case-study-5)
- [Preparing for Advising](#preparing-for-advising)
  - [Advising development operation teams](#advising-development-operation-teams)
  - [Practice Exam Questions 5](#practice-exam-questions-5)
- [Preparing for Reliability](#preparing-for-reliability)
  - [Ensuring solution and operations reliability](#ensuring-solution-and-operations-reliability)
  - [Case Study 6](#case-study-6)
  - [Practice Exam Questions 6](#practice-exam-questions-6)
- [Challenge Lab](#challenge-lab-1)
- [Resources and next steps](#resources-and-next-steps)

## Intro

Hi, welcome to this course, Preparing for the Professional Cloud Architect Exam. I'm a technical curriculum developer with Google, my name is Tom Stern.  
The place where certification and training intersect is at the job itself. The certification exam is designed to evaluate whether you have the skills and knowledge expected of someone in a role of a cloud architect.  
Therefore, the best way to prepare for the exam is to be a confident, professional cloud architect. The approach in this course is to review many items that a cloud architect should know because that information could be on the exam.  
So this course focuses on the skills you need to know for the job. Being prepared to be a professional cloud architect is the best way to be prepared for the exam.  
If you go to cloud.google.com/certification, you'll see a list of our professional certifications. And if you click on cloud architect, you'll see several valuable resources.  
The most important one is a certification exam guide. It's a list of all the areas covered in the exam. The tips section of this course are organized around Cloud Architect Exam Guide Outline. The outline divides the exam into sections that focus on specific priorities and information about the job role.  
So this course follows the outline, explaining each section of the course, providing tips, and highlighting information that would be useful to know. Some items in the outline are important to the job of a professional cloud architect, but they're not technical or maybe they're not specific to Google.  
For example, a cloud architect needs to know how to present solution proposals to customers and to communicate with executive staff. That isn't something we currently teach, but you should know it from experience or learn it on your own. I'll identify these items when they appear on the outline.  

These are the sections of the exam.  
The first part of the exam about design and the second part about provisioning are more inclined towards product and feature knowledge and basic design. Where and how to use each product in specific cases.  
The middle two parts on security and optimizing are about getting specific qualities into the solution.  
For example, in the first two parts, you might make something function, in the second two parts, you might make it **secure and cost-effective**.  
The last two parts are about operating the solution and all the procedures and features that can make the solution continue to operate reliably and to adopt and to change overtime. Notice the gradation between products and procedures.  
Have you heard of the the **four P's**? That's **product, people, policy, and process**. The cloud architect exam is not all about product. People sometimes go into the exam expecting only questions about product, like how to do a particular thing or why a capability is useful. You should understand that the questions on the exam can be about the other three P's as well. There's a lot of ground to cover today.  

You'll begin by learning what the certification is about, where it's positioned relative to other certifications, and more specifically, how it's designed relative to your job role and experience in the industry.  
Next, you'll explore the sample case studies, provided to help prepare for the exam. These case studies are also available on the cloud.google.com/certification site. Some of the questions on the exam can key to these case studies.  
If you've read and studied them in advance, you'll already be familiar with them. And that means you'll effectively have more time to answer questions during the exam.  
Most of these case studies focus on business requirements, as well as technical requirements. The business requirements are just as important as the technical requirements to passing the exam. You'll spend most of the day reviewing and getting preparation tips in specific subject areas.  
And at the end, you'll get pointers to resources and next steps to continue your preparation. I think it seems pretty obvious from this list, but it should be called out that you can't learn everything you need to know for the certification exam in one class. So the goal here is to help you prepare, but you won't be able to pass the exam based only on attending this course. By the end of this class, if you've already been preparing for the examination, you'll have a good sense of what else you need to study or do to prepare or whether you're ready to give it a shot.

### Understanding the Professional Cloud Architect Certification

The main thing you need to know about the professional cloud architects certification is that it isn't a theoretical test.  
This certification has been designed to confirm the skills required of a practitioner. Specifically, to test whether you know how to do the job of a cloud architect, it doesn't just test whether you know lots of general information. It ask questions to see if you can think like a cloud architect and solve problems like a cloud architect.  
Look, that means the certification is going to be more challenging than other certifications you may have heard about that only test on information, but it also means that the certification means something and that's one reason it's highly valued in the industry. The practical nature of the exam makes it challenging but it also makes it valuable.  
I just want to caution you that the associate cloud engineer is not a simpler and easier cloud architect exam. All of these certifications are based on real-world practical job skills required and used by practitioners in the industry. A cloud engineer uses the same technology as the cloud architect. However, their job focuses different and so the skills are different.  
For example, a cloud architect might consider how to design a Kubernetes cluster to meet customer requirements. A cloud engineer might run jobs on the cluster and be more focused on monitoring the cluster and measuring and maintaining its performance.  
A cloud architect designs the solution and implements it. A cloud engineer operates a solution, monitors it maintains it, and evolves it as business circumstances change.  

So, which certification or certifications you might want depends on your job role, the job you have or the job you want to have. A main differentiator between the professional level certification and the associate certification is the **focus on designing and on business requirements**.  
If you're involved in designing, planning, proof of concept, and identifying the business needs, then you should be looking at the Professional Certification and if you're going to focus on implementing and operating and on the technical requirements then you should consider the associates certification.  
In addition to the business requirements, there are differences in the technical requirements.  
For example, a cloud engineer might need more practice operating and maintaining a solution whereas a cloud architect might need to know more about how different options will change and how the solution is operated and maintained. They're related technical skills but they serve a different purpose and perspective.  
Here's some direct advice to help you decide where to start. If you're job focuses mainly on business requirements and not on implementation or if your job does not focus on business requirements but only on technical requirements, start with the Associate Cloud Engineer certification, the ACE.  
If your job involves all three, business requirements, technical requirements, and implementation, start with the Professional Cloud Architects certification.  
If your job is not associated with any of these, then start with the Associate Cloud Engineer.  

The exam is about two hours. In the US, as an example, the cost is about $200. You can check local prices and currencies online. The examine is available globally. You have to take it at a Criterion testing center.  
Let's see, what else can I tell you? You're not allowed to have scratch paper, a pen or notes, no drinks are allowed. You can take a bathroom break but the time continues to count down. Many people report that they used the entire two hours.  
Here are some general tips: The certification offers a practice test, use it. There's also a lot of opportunities in this course to practice and develop good test-taking skills. Also, I think it's a good idea to look at each possible answer as if it were the only answer available and evaluate whether it could be true or not do this before choosing from the alternatives and finally pace yourself, avoid getting bogged down on any single question.  
There are two general approaches to preparing for the certification exams.  
The first approach which is the most common is what I call **cram for the exam**. That is you start with basic information, like the information covered in our courses, and you review that information and make sure you've mastered and can recall the majority of it.  
Then you research and practice, practice, practice, in a formal education science, this is called mastery method. When you're proficient, then you can attempt the exam.  
This class uses a different approach. We identify **key points**. Some of them are complex or subtle. If you understand and know those points, you have an indicator that you have knowledge of all the elements that go into that solution.  
If you don't understand a point or sets that you're missing something or it's weak in some aspects, you can note those items and use that as a guide for what to study. **Fill in the gaps** on what you need to know by going back to the training that contains them or by exploring documentation or labs to solidify your understanding.  
**Rehearse the problem-solving skills** of the profession and when you're proficient, you can attempt the exam.  

The benefit of the bottom-up approach is that it doesn't skip anything. On the other hand, a lot of time is spent covering things you already know. The benefit of the top-down approach is that it respects the studying and work you've already done so it helps you focus much more quickly on what you need to learn. There is far less time spent reviewing information that you already know. Should you guess or you better off leaving an item blank? **There's no advantage to leaving a question unanswered**. One of the most important features of this exam, is that you can bookmark questions you're unsure about and you can review those questions later.  
You can actually do iterative rounds if you have the time. So, answer the easiest and most certain questions first then answer the next and the next until what's left are the questions that are hard for you. Use everything you know to sort out exactly what's being asked and surface which information is important.  
The ability to bookmark items and come back to them is really powerful. I suggest that you practice this way like when you're studying practice recognizing when you don't know something or not sure about it and bookmark it for later consideration. Then go back and take a look at your bookmarked answers to see if you still agree with your original response.

### Exam Guide Outline

1. Designing and planning a cloud solution architecture

    1.1 Designing a solution infrastructure that meets business requirements. Considerations include:

- Business use cases and product strategy
- Cost optimization
- Supporting the application design
- Integration with external systems
- Movement of data
- Design decision trade-offs
- Build, buy, modify, or deprecate
- Success measurements (e.g., key performance indicators [KPI], return on investment [ROI], metrics)
- Compliance and observability

  1.2 Designing a solution infrastructure that meets technical requirements. Considerations include:

- High availability and failover design
- Elasticity of cloud resources with respect to quotas and limits
- Scalability to meet growth requirements
- Performance and latency

    1.3 Designing network, storage, and compute resources. Considerations include:

- Integration with on-premises/multi-cloud environments
- Cloud-native networking (VPC, peering, firewalls, container networking)
- Choosing data processing technologies
- Choosing appropriate storage types (e.g., object, file, databases)
- Choosing compute resources (e.g., preemptible, custom machine type, specialized workload)
- Mapping compute needs to platform products

    1.4 Creating a migration plan (i.e., documents and architectural diagrams). Considerations include:

- Integrating solutions with existing systems
- Migrating systems and data to support the solution
- Software license mapping
- Network planning
- Testing and proofs of concept
- Dependency management planning

    1.5 Envisioning future solution improvements. Considerations include:

- Cloud and technology improvements
- Evolution of business needs
- Evangelism and advocacy

2. Managing and provisioning a solution infrastructure

    2.1 Configuring network topologies. Considerations include:

- Extending to on-premises environments (hybrid networking)
- Extending to a multi-cloud environment that may include Google Cloud to Google Cloud communication
- Security protection (e.g. intrusion protection, access control, firewalls)

    2.2 Configuring individual storage systems. Considerations include:

- Data storage allocation
- Data processing/compute provisioning
- Security and access management
- Network configuration for data transfer and latency
- Data retention and data life cycle management
- Data growth planning

    2.3 Configuring compute systems. Considerations include:

- Compute resource provisioning
- Compute volatility configuration (preemptible vs. standard)
- Network configuration for compute resources (Google Compute Engine, Google Kubernetes Engine, serverless networking)
- Infrastructure orchestration, resource configuration, and patch management
- Container orchestration

3. Designing for security and compliance

    3.1 Designing for security. Considerations include:

- Identity and access management (IAM)
- Resource hierarchy (organizations, folders, projects)
- Data security (key management, encryption, secret management)
- Separation of duties (SoD)
- Security controls (e.g., auditing, VPC Service Controls, context aware access, organization policy)
Managing customer-managed encryption keys with Cloud Key Management Service
- Remote access

    3.2 Designing for compliance. Considerations include:

- Legislation (e.g., health record privacy, children’s privacy, data privacy, and ownership)
- Commercial (e.g., sensitive data such as credit card information handling, personally identifiable information [PII])
- Industry certifications (e.g., SOC 2)
- Audits (including logs)

4. Analyzing and optimizing technical and business processes

    4.1 Analyzing and defining technical processes. Considerations include:

- Software development life cycle (SDLC)
- Continuous integration / continuous deployment
- Troubleshooting / root cause analysis best practices
- Testing and validation of software and infrastructure
- Service catalog and provisioning
- Business continuity and disaster recovery

    4.2 Analyzing and defining business processes. Considerations include:

- Stakeholder management (e.g. influencing and facilitation)
- Change management
- Team assessment / skills readiness
- Decision-making processes
- Customer success management
- Cost optimization / resource optimization (capex / opex)

    4.3 Developing procedures to ensure reliability of solutions in production (e.g., chaos engineering, penetration testing)

5. Managing implementation

    5.1 Advising development/operation team(s) to ensure successful deployment of the solution. Considerations include:  

- Application development
- API best practices
- Testing frameworks (load/unit/integration)
- Data and system migration and management tooling

    5.2 Interacting with Google Cloud programmatically. Considerations include:

- Google Cloud Shell
- Google Cloud SDK (gcloud, gsutil and bq)
- Cloud Emulators (e.g. Cloud Bigtable, Datastore, Spanner, Pub/Sub, Firestore)

6. Ensuring solution and operations reliability

    6.1 Monitoring/logging/profiling/alerting solution

    6.2 Deployment and release management

    6.3 Assisting with the support of deployed solutions

    6.4 Evaluating quality control measures

## Case Studies

In this module, we'll look at sample case studies that are published by the certification organization. There are good examples. Questions on the exam could even be drawn from these cases, so it's important to study them. It's recommended that use a worksheet similar to the one provided to analyze cases, especially the sample cases provided for the certification exam. We're going to review each case study. Then, you'll have the opportunity to create your own solution. Finally, we'll provide a sample solution. The sample solution is not authoritative, it's not the correct solution or the only possible solution. The point here isn't to memorize the sample solution, but to practice thinking through defining your own solution, which is the skill you need as a professional Cloud Architect.

### Mounkirk Games

**Sample case study: Mountkirk Games**  
This is a sample case study that may be used on the Professional Cloud Architect exam. It describes a fictitious business and solution concept to provide additional context to exam questions.

Mountkirk Games makes online, session-based, multiplayer games for mobile platforms. They build all of their games using some server-side integration. Historically, they have used cloud providers to lease physical servers.

Due to the unexpected popularity of some of their games, they have had problems scaling their global audience, application servers, MySQL databases, and analytics tools.

Their current model is to write game statistics to files and send them through an ETL tool that loads them into a centralized MySQL database for reporting.

1. Solution concept  

Mountkirk Games is building a new game, which they expect to be very popular. They plan to deploy the game’s backend on Compute Engine so they can capture streaming metrics, run intensive analytics, and take advantage of its autoscaling server environment and integrate with a managed NoSQL database.

2. Business requirements  

- Increase to a global footprint
- Improve uptime—downtime is loss of players
- Increase efficiency of the cloud resources we use
- Reduce latency to all customers

3. Technical requirements  

**Requirements for game backend platform**

- Dynamically scale up or down based on game activity
- Connect to a transactional database service to manage user profiles and game state
- Store game activity in a timeseries database service for future analysis
- As the system scales, ensure that data is not lost due to processing backlogs
- Run hardened Linux distro

**Requirements for game analytics platform**

- Dynamically scale up or down based on game activity
- Process incoming data on the fly directly from the game servers
- Process data that arrives late because of slow mobile networks
- Allow queries to access at least 10 TB of historical data
- Process files that are regularly uploaded by users’ mobile devices

4. Executive statement  

Our last successful game did not scale well with our previous cloud provider, resulting in lower user adoption and affecting the game’s reputation. Our investors want more key performance indicators (KPIs) to evaluate the speed and stability of the game, as well as other metrics that provide deeper insight into usage patterns so we can adapt the game to target users. Additionally, our current technology stack cannot provide the scale we need, so we want to replace MySQL and move to an environment that provides autoscaling and low latency load balancing and frees us up from managing physical servers.

### Mountkirk Games Case Study Analysis

Mountkirk Games builds all of their games with some server-side integration. And has historically used cloud providers to lease physical servers.  
A few of their games were more popular than expected. And they **had problems scaling** their application servers, MySQL databases, and analytics tools.  
Mountkirk's current model is to write games statistics to files. And send them through an ETL tool that loads them into a centralized MySQL database for reporting.  
Mountkirk Games has an unexpected hit. Predictions were that there would be a small surge of interest at the beginning, but that demand would flatten out. When the game debuted, initial players reported the game on social media and the reports went viral. Instead of flattening, demand started growing exponentially.  
The two greatest problems for a game company are if **nobody wants to play your game**, and if **everybody wants to play your game**.  
Success is difficult because the company needs to scale its IT infrastructure fast to maintain the quality of the user's experience. The popularity of the game created problems with the previous vendor when scaling could not keep pace.  

MountKirk Games wants to adjust their infrastructure to solve their scaling problems.  
They have application servers, MySQL database for storing user information and game state.  
And they're interested in using analytics to improve their games.  
They have a design plan in place, but ran into issues with a previous cloud provider.  
Their immediate business goals are to expand into new markets globally.  
They want to track and reduce the amount of time their systems go down and their games are not available.  
They need some kind of metrics or key performance indicators to measure speed, stability, and other qualities. So they can start managing the qualify of the user experience by making intelligent choices in the game infrastructure.  
As is often the case, the planned or presumed solution might not be ideal. You have to be careful when discussing this, right? You don't know who was in involved in defining that great plan.  
It might be a good design. It might have some areas that have to be changed. The important thing is to first **acknowledge the existence of the planned solution**. Then, to define the solution separately, so you can understand the strengths and weaknesses of the proposal.  
That way, you can make reasoned suggestions about what to change to improve the plan. The company has a strong focus on analytics and custom metrics. In other words, it's great to be able to scale instances based on CPU load. But how well does that really indicate resource consumption by users? It could be that some offer factors like the number of users currently playing should be a factor in scaling.  

Finally, you should consider potentially different storage solutions for analytic data and for game data. The data's different, it's accessed differently and at different times.  
So it would make sense that each kind of data and use case should be examined separately to determine the best candidates for inclusion.  
The existing environment consists of application servers and data centers that are working acceptably, and handling the current game load. So there's **no immediate pressure to replace those servers** or migrate them to the cloud.  
On the other hand, any new games ought to be implemented using the new or future solution. The **MySQL database is creating scaling issues and it needs to be replaced**. Analytics works like this, the statistics are written out to files and ETL process, that's Extract, Transfer, and Load, stores the statistical data in MySQL.  
Then reports are generated from the data. Storing the analytics in MySQL doesn't sound ideal. It really isn't the right tool for that job. Here are some technical watch points.  
The solution should have **global load balancing, autoscaling, low latency**. And it should be able to catch up and **not lose customer game information**, due to a backlog if game use spikes and it takes some time to scale up.  
They're concerned about security so they want to use a hardened Linux distribution.  
They need a **transactional** type database for user profiles and game state information.  
They need to use SQL to query **up to 10 terabytes** of historical information. And a managed NoSQL database and time series database for Analytics.  
It would be ideal if the **game server metrics could be ingested directly into the new analytics framework**, and **not written out as files** and ETL ingested.  
Sometimes games are played on mobile phones and tablets. Due to the slow and inconsistent mobile network, game data could arrive late, and statistics data is regularly uploaded from the mobile devices.  
Take a few minutes to define your solution. What elements would you use? How would you satisfy the business needs while minding the technical watch points?

**Here's one sample solution.**

We'll start with a scalable game hosting servers. The servers will be Compute Engine instances.  
We'll create a server template, and use instance groups for auto-scaling.  
We'll use HTTPS load balancing with an autoscaler.  
To complete the picture, we'll create custom metrics on the servers that are directly related to the game engine.  
Pass those through Stackdriver, and use the custom metrics to scale up and down the servers.  
There's a lot more we can do. There are Linux images available that are regularly maintained. So, we need to consider whether those are secure enough for the business requirements, or if we'll need to develop a custom image.  
We could also have considered using App Engine and Cloud Endpoints as an alternative solution, but it wouldn't meet all the requirements for custom metrics.  

Data store is fully managed servers that will be an excellent choice for preserving game state. We can probably also store user profile in Data store.  
Alternatively, we could use a Cloud SQL instance for profiles.  
Finally, there's the analytics workflow.  
We can use BigQuery to accumulate the game statistics. The data set can be loaded with 10 terabytes of historic data.  
We want to use Cloud Pub/Sub to provide a buffer for live data, and late data, removing timing considerations from the ingesting process.  
Then, for mobile devices we can have them upload their data to cloud storage.  
If we need to do batch data processing, or streaming data processing to prepare the data, or clean the data, then Cloud Dataflow would be a good choice, since it's server-less and auto-scaling.

### Dress4Win

**Sample case study: Dress4Win**

This is a sample case study that may be used on the Professional Cloud Architect exam. It describes a fictitious business and solution concept to provide additional context to exam questions.

Dress4Win is a web-based company that helps their users organize and manage their personal wardrobe using a web app and mobile application. The company also cultivates an active social network that connects their users with designers and retailers. They monetize their services through advertising, ecommerce, referrals, and a freemium app model. The application has grown from a few servers in the founder’s garage to several hundred servers and appliances in a colocated data center. However, the capacity of their infrastructure is now insufficient for the application’s rapid growth. Because of this growth and the company’s desire to innovate faster, Dress4Win is committing to a full migration to a public cloud.

**1. Solution concept**

For the first phase of their migration to the cloud, Dress4Win is moving their development and test environments. They are also building a disaster recovery site, because their current infrastructure is at a single location. They are not sure which components of their architecture they can migrate as is and which components they need to change before migrating them.

**2. Existing technical environment**

The Dress4Win application is served out of a single data center location. All servers run Ubuntu LTS v16.04.

**Databases:**

MySQL. One server for user data, inventory, static data,
- MySQL 5.7
- 8 core CPUs
- 128 GB of RAM
- 2x 5 TB HDD (RAID 1)

**Compute:**

40 web application servers providing micro-services based APIs and static content
- Tomcat - Java
- Nginx
- Four core CPUs
- 32 GB of RAM

20 Apache Hadoop/Spark servers:
- Data analysis
- Real-time trending calculations
- Eight core CPUs
- 128 GB of RAM
- 4x 5 TB HDD (RAID 1)

Three RabbitMQ servers for messaging, social notifications, and events:
- Eight core CPUs
- 32GB of RAM

Miscellaneous servers:
- Jenkins, monitoring, bastion hosts, security scanners
- Eight core CPUs
- 32GB of RAM

**Storage appliances:**

iSCSI for VM hosts
- Fibre channel SAN - MySQL databases
- 1 PB total storage; 400 TB available
- NAS - image storage, logs, backups
- 100 TB total storage; 35 TB available

**3. Business requirements**

- Build a reliable and reproducible environment with scaled parity of production
- Improve security by defining and adhering to a set of security and identity and access management (IAM) best practices for cloud
- Improve business agility and speed of innovation through rapid provisioning of new resources
- Analyze and optimize architecture for performance in the cloud  

**4. Technical requirements**

- Easily create non-production environments in the cloud
- Implement an automation framework for provisioning resources in cloud
- Implement a continuous deployment process for deploying applications to the on-premises data center or cloud
- Support failover of the production environment to cloud during an emergency
- Encrypt data on the wire and at rest
- Support multiple private connections between the production data center and cloud environment.  

**5. Executive statement**

Our investors are concerned about our ability to scale and contain costs with our current infrastructure. They are also concerned that a competitor could use a public cloud platform to offset their up-front investment and free them to focus on developing better features. Our traffic patterns are highest in the mornings and weekend evenings; during other times, 80% of our capacity is sitting idle.

Our capital expenditure is now exceeding our quarterly projections. Migrating to the cloud will likely cause an initial increase in spending, but we expect to fully transition before our next hardware refresh cycle. Our total cost of ownership (TCO) analysis over the next five years for a public cloud strategy achieves a cost reduction between 30% and 50% over our current model.  

### Dress4Win Case Study Analysis

Dress4Win is a web-based company that helps their users organize and manage their personal wardrobe using a website and mobile application.  
The company also cultivates an active social network that connects their users with designers and retailers.  
They monetize their services through advertising, eCommerce referrals, and a freemium app model. Dress4Win is going to try Cloud solutions using three tests to provide proof of concept.  
The development processes, testing processes, and disaster recovery are their first three experiments with cloud computing.  

So, each of these are infrastructure and development pieces of their environment. If these solutions work well, they'll have confidence to consider migrating parts of their application to the Cloud.  
Dress4Win provides a wardrobe management service via a web UI and mobile app. They use social networking to identify style trends and adjust their recommendations. For example, if people are sharing images wearing acid washed jeans and there are favorable comments, then acid washed jeans will become more popular in the recommendation engine.  
The application is free to users. The monetization model is to sell ads to directly sell products through the interface and to provide referrals to other sites and services.  
Since inception, the system has grown from 10 servers to 100 servers. The company has actually committed to Cloud adoption. They just want a gradual approach.  
So, phase one is DevTest and DR, and phase two will be the application services and recommendation engine.  

Immediately, they need capacity for growth. They need to fit the cloud migration activity into the current cycle, so they don't have to buy additional hardware for their data center.  
Immediate business goals are lower IT overhead through the use of managed services while meeting growth requirements and managing cost. The company has predicted it will see an immediate expense for moving into Cloud, and then a gradual reduction in cost over five years which will save 30 percent to 50 percent.  
So, the move to Cloud will eventually pay for itself. Dress4Win will migrate in phases.  
**Phase one will be DevTest and disaster recovery**. Future migration will be dependent on phase one. Disaster recovery and high availability will be considerations.  
We will migrate the least critical software components first. The plan is to reduce operation costs by moving towards more of a DevOps model.  
The development and test process should increase the velocity of product and feature releases. They plan to use a CICD approach.  
The existing environment uses **MySQL to keep user data and other application data**.  
The social graph **recommendation engine is using Redis**.  
There are a number of application servers running **TomCat** with a micro-services design, and it uses **NGINX** to serve up static content.  
The Apache Beam is running the batch processing for recommendations. There are a lot of details in the case study covering storage and compute capacity for a range of use cases.  

Here are some technical watch points: They have static or infrequently changing data stored in a relational database.  
They're using high-speed in-memory caching database for some parts of the application.  
So, micro-services architecture, that should start you thinking about what kind of compute services on Google Cloud could support a micro-services design.  
They're already using VMs in the data center, so, lift and shift should be an option. If we lift and shift the compute service directly to VMs and Compute Engine, we'll need a multi-region approach because the customers are global.  
Their application uses multiple kinds of storage in the data center, and some of these will need to be mapped to services in Google Cloud to support all the requirements.  
Data analysis and trending are run on Hadoop and Spark pipelines. That probably means offline batch processing for the social graph, and analytics are run on the same platform, so we're looking mainly at batch processing and not streaming.  
What's a direct managed service solution for Hadoop and Spark? Right, **Cloud Dataproc**.  
They're using some message queue services. This is implemented in the data center as an MQ service running on individual servers. We need to see when it might make sense to migrate this to **Cloud Pub Sub**.  

They have some security concerns. We'll need to have the discussion about the kinds of security and encryption services that are built into the Google Cloud platform. Then we can look at additional security services if those are not sufficient.  
It looks like they might want some auditing capabilities so they can understand and manage security.  
And, for a Continuous Integration and Continuous Delivery, CICD, they can use Jenkins open source software. So, let's be clear about this.  
The disaster recovery objective is really about building an entire solution. It kind of encompasses the whole migration to Cloud, because we want to bring everything back if the data centers go down.  
The development and test environments are going to create and update software and data that works with current production and also with disaster recovery. So, this whole activity is almost like a dress rehearsal for phase two, for full migration to the cloud.  
Take some time to come up with your solution, and then when you've got your solution, you can compare it with the sample solution.

**Dress4Win Sample Solution**

We need to come up with a full migration design in order to define the disaster recovery elements.  
If we're going to change your development workflow, and test workflow, it needs to work with a Phase 2 future cloud solution, not a cloud based support for data center based development workflow.  
A lot of this becomes **direct mappings like Cloud SQL to replace MySQL**.  
**Cloud memory store** is a managed reddest service so that can **replace Redis**.  
**Cloud Data Store** is a natural fit for the mobile backed data service.  
**Compute Engine VMs** for the lift and shift of application servers.  
If they don't want to use **Cloud Storage** for static content, and serve it through **CDN**, then we could use **Cloud Marketplace to get a preconfigured Nginx server**.  
We could use **Kubernetes** for the micro services, that starts to play into changes to development and test, and since it will now be a containerized workflow.  
**Load balancing for traffic routing and availability, App Engine for applications** possibly also using containers.  
**Local SSD and SSD persistent disks** for VM host, and if they initially lift and shift MySQL, instead of using CloudSQL.  
**Cloud storage for backups**, multi regional buckets, as part of disaster recovery.  
**Cloud Data Proc** instead of Hadoop.  
**Big Query** could be used for the real time trending and analytics. We don't know how data is currently stored on their Hadoop cluster if the data is in HDFS, it can be moved to cloud storage, and if it's an HBase it can be moved to **Cloud Bigtable**.  
**Cloud VPN** for connectivity to the current environment. **Firewall rules** for security.  
See sec if additional encryption control is needed, and finally we can use **Cloud Marketplace to rapidly deploy a Jenkins service** for container development.  
The whole infrastructure could be templated into **Deployment Manager** or perhaps **Terraform**, so that we can spin up entire development and test environments with their own clusters and so forth.  
This will create the scaling and isolation they want, and meet the needs of phase one, development test and disaster recovery.

### TerramEarth

**Sample case study: TerramEarth**

This is a sample case study that may be used on the Professional Cloud Architect exam. It describes a fictitious business and solution concept to provide additional context to exam questions.

TerramEarth manufactures heavy equipment for the mining and agricultural industries. About 80% of their business is from mining and 20% from agriculture. They currently have over 500 dealers and service centers in 100 countries. Their mission is to build products that make their customers more productive.

**1. Solution concept**

There are 20 million TerramEarth vehicles in operation that collect 120 fields of data per second. Data is stored locally on the vehicle and can be accessed for analysis when a vehicle is serviced. The data is downloaded via a maintenance port. This same port can be used to adjust operational parameters, allowing the vehicles to be upgraded in the field with new computing modules.

Approximately 200,000 vehicles are connected to a cellular network, allowing TerramEarth to collect data directly. At a rate of 120 fields of data per second, with 22 hours of operation per day, TerramEarth collects a total of about 9 TB/day from these connected vehicles.

**2. Existing technical environment**

TerramEarth’s existing architecture is composed of Linux and Windows-based systems that reside in a single U.S. west-coast-based data center. These systems gzip CSV files from the field and upload via FTP and place the data in their data warehouse. Because this process takes time, aggregated reports are based on data that is three weeks old.

With this data, TerramEarth has been able to preemptively stock replacement parts and reduce unplanned downtime of their vehicles by 60%. However, because the data is stale, some customers are without their vehicles for up to four weeks while they wait for replacement parts.

**3. Business requirements**

- Decrease unplanned vehicle downtime to less than one week
- Support the dealer network with more data on how their customers use their equipment to better position new products and services
- Have the ability to partner with different companies—especially with seed and fertilizer suppliers in the fast-growing agricultural business—to create compelling joint offerings for their customers

**4. Technical requirements**

- Expand beyond a single data center to decrease latency to the American Midwest and East Coast
- Create a backup strategy
- Increase security of data transfer from equipment to the data center
- Improve data in the data warehouse
- Use customer and equipment data to anticipate customer needs

**5. Application 1: Data ingest**

A custom Python application reads uploaded data files from a single server, writes to the data warehouse

**Compute:**
- Windows Server 2008 R2
- 16 CPUs
- 128 GB of RAM
- 10 TB local HDD storage

**6. Application 2: Reporting**

An off-the-shelf application that business analysts use to run a daily report to see what equipment needs repair. Only two analysts of a team of 10 (five West Coast, five East Coast) can connect to the reporting application at a time.

**Compute**  
Off-the-shelf application. License tied to number of physical CPUs
- Windows Server 2008 R2
- 16 CPUs
- 32 GB of RAM
- 500 GB HDD

**Data warehouse**  
A single PostgreSQL server
- RedHat Linux
- 64 CPUs
- 128 GB of RAM
- 4x 6TB HDD in RAID 0

**7. Executive statement**

Our competitive advantage has always been in our manufacturing process, with our ability to build better vehicles for lower cost than our competitors. However, new products with different approaches are constantly being developed, and I’m concerned that we lack the skills to undergo the next wave of transformations in our industry. My goals are to build our skills while addressing immediate market needs through incremental innovations.

### TerramEarth Case Study Analysis

TerramEarth manufacturers heavy equipment for the mining and agricultural industries.  
About 80 percent of their businesses are for mining and 20 percent from agriculture.  
They currently have over 500 dealers and service centers in 100 countries. Their mission is to build products that make their customers more productive.  
The workload is divided between nine terabytes per day delivered streaming over cell service.  
That's the IoT part, and 900 terabytes per day delivered via Gzip CSV file.  
Currently, the Gzip CSV data from the field takes about three weeks to make it into the data warehouse.  
That means some customers have vehicles out of service for four weeks waiting for parts. The company knows that IoT is coming and is preparing to meet the changes as traffic shifts from the file transfer model to the cell IoT model.  
However, the data warehouse is behind technically and also is not meeting customer business needs. They need a data warehouse upgrade that will handle both problems.  

The company provides heavy equipment through 500 dealers in 100 countries. One of the company goals is future-proofing, being prepared with skills and infrastructure to keep pace with changes in the industry.  
Immediate business goals are to **decrease downtime**. Downtime can currently run beyond four weeks. They would prefer to get this down to about one week with an average being between one week and four weeks.  
They want to give those 500 dealers greater access to customer data. For example, if the dealer knew that a particular machine was out of service often, they might want to approach a customer with an upgrade offer.  

The 20 percent of the business in agriculture vertical is a potential growth area. The company wants to be able to partner with others net industry to expand their market.  
One way to do this is to be in the lead technologically. So, when there are inflection points in the market, TerramEarth can take advantage and enter new niches. This says it's about vehicles, but we can look at it as a way to understand the data demands it will be placed on the IT infrastructure.  
They have 200 thousand vehicles connected to cell networks that stream data at the rate of a 120 fields per second.  
They're on for 22 hours a day resulting in nine terabytes of data per day.  
They also have another 20 million vehicles that are not cell connected. The data is stored on the vehicle and downloaded when the vehicle is serviced.  
It takes quite a bit of time for the data to be uploaded and transformed.  
Currently, that process causes about a three week delay. To cover any parts that might be needed over a three week period, TerramEarth is forced to keep additional parts in stock.  
If the feedback were faster, their spare parts could more closely match the real demand and they could liberate some of the money that's currently invested in stock and sitting on shelves.  

A few key points. The first one is that this is not an ERP project. ERP is electronic resource planning. If you instrument your parts demand through your business and map it back to the supply chain, you can do things like order parts automatically when they're needed or even look at suppliers inventory and preorder parts if they are not enough in stock.  
In any case, TerramEarth has decided that ERP should be an upgrade for another day. They'll stick with current surplus supply levels and maintain the same supply chain as today.  
They're happy just to provide visibility to supply partners. Change is already occurring in the management team through retraining management about emerging opportunities. TerramEarth realizes that the technical staff will need to be trained on the new systems and solutions. Moving the data warehouse to BigQuery will handle a lot of the main customer and business issues having to do with parts delay.  
It will need a **front end** that can handle today's IoT demands and will grow and adapt to the changing categories of demand as more streaming solutions are employed and fewer file-based solutions.  
Keep in mind that **Cloud IoT core** doesn't suffice to get your data to cloud storage. Cloud IoT core b**rokers between IoT devices and Cloud Pub Sub**.  
You'll almost certainly want Cloud Dataflow to get the data to the next place. For vehicles that store and upload their data, the service will need to handle 900 terabytes of batch data transfer each day.  
Go ahead and define your solution. Consider how you would design this solution for a real customer. What are the questions you want to ask to help clarify your design? When you're ready, we'll look at one sample solution

### TerramEarth Sample Solution

Moving the data warehouse to BigQuery will handle a lot of the main customer and business issues having to do with parts delay.  
It will need a front end that can handle today's IoT demands, and will grow and adapt to the changing categories of demand as more streaming solutions are employed, and fewer file-based solutions.  
Keep in mind that Cloud IoT Core doesn't suffice to get your data to Cloud Storage. Cloud IoT Core brokers between IoT devices and Cloud Pub/Sub.  
You'll almost certainly want a Dataflow job to get the data to the next place.  
The 900 terabytes of data can be uploaded directly to BigQuery, or could be staged in Cloud Storage. We don't know what kind of processing might be required to make the data useful, so it could be ETL using Dataflow.  
However, **Cloud Storage has the ability to store gzip files as objects**, and then decompress them when requested by a client. So, the gzip files could be uploaded and decompressed during transfer through Dataflow to BigQuery.

### Review

**Product and technology knowledge**  
You need to know the basic information about each product that might be covered on the exam.  

You need to know:

- What it does, why it exists.
- What is special about its design, for what purpose or purposes was it optimized?
- When do you use it, and what are the limits or bounds when it is time to consider an alternative?
- What are the key features of this product or technology?
- Is there an Open Source alternative? If so, what are the key benefits of the cloud-based service over the Open Source software?

**Which products and technologies**  
Training and Certification meet at the JTA -- the Job Task Analysis -- the skills required of the job.

The scope of the exam matches the learning track and specialization in training. So a great place to derive a list of the technologies and products that might be on the exam is to look at all the products and technologies that are covered in the related training. The training might not cover everything. But it is a good place to start.

**Study methods**  
Training is great. Digging into the online documentation can be very instructive and covers more detail than can be covered in a class, so documentation tends to have more equal coverage of features, whereas training has to prioritize its time. Getting hands on experience can help you understand a product or technology much better than reading and is the kind of experience a professional in the job would have. So labs can be a great way to prepare.

## Preparing for Business Design

**Touchstone concepts**  
A touchstone concept is a complex or key idea -- something that you would learn in a class AFTER you have learned all the basic dependent concepts. They are used in this course because they are a very efficient way for you to learn where you have confidence and where more preparation might be needed.  

This approach is based on the Deeper Learning method of adult learning.  

**Example**  
People seem to be able to relate well to this example.  

**Touchstone**: "Unlike other vendor clouds, a subnet spans zones, enabling VMs with adjacent IPs to exist in separate zones, making design for availability easier to accomplish since the VMs can share tagged firewall rules."  

To understand the above statement, the basic dependent knowledge that must already be understood includes, Regions, Zones, Subnets, IP Addresses, and Firewall Rules.  

These basic concepts are not taught or reviewed in this course. They are taught in the training courses in this specialization and in the corresponding learning track in instructor led training.  

**Advice: Evaluate the dependent basic concepts**  
Assess your confidence with each touchstone concept as it is presented. Don't expect to be taught the basic concept. If you don't understand the touchstone at all, or if you don't feel confident in your knowledge of it, or if you feel there are specific elements of it that you don't understand or are not confident about -- take note!  

This is an area where more preparation can be of benefit for you.  

Also -- note where you are confident, know the material, and the dependent concepts on which the touchstone is based. These areas require less preparation for you. So noting what you know well can help make your preparation activities more efficient.

### Designing and Implementing

This module covers designing and implementing infrastructure solutions. Design can get complicated.  
Do you have an approach to design? It's easy to confuse elements if you don't use an organized method.  
Do you have favorite design elements? For example, do you find most of your designs start with VMs? You'll want to overcome these biases by understanding the infrastructure services available and when to select them.  
Today you'll be learning about and preparing for the Professional Cloud Architect exam. A lot of that has to do with design.  

Before you can design a solution, you need to understand the building blocks, the underlying services, and technologies that make up solutions in Google Cloud.  
Here's a tip, use a layered model like this one. It'll help you organize your thinking about each exam question, so that you'll more easily recognize and focus on what's important.  
Professional Cloud Architects often use layered models to organize or separate solution designs. It makes it much easier to deal with the complexity and to make sure there are no dropouts in the design. This model comes from our design and process class.  
Sometimes people ask if the order of the layers is significant in this diagram - well, the order is significant.  
You start with service definition at the bottom and move up the layers until you're planning the rollout and maintenance of the solution. So, each layer has dependencies on the one beneath it.  

**Layers from top to bottom:**
- Deploying and Monitoring
- Capacity and Cost
- Security
- Scalability and Recovery
- Network and Presentation Layer
- Data Layer
- Business Layer
- Service Definition

Sometimes people also ask if the size of the layers in this diagram is meaningful. For example, a security more important than costs because the layer is bigger in the diagram and the answer to that is **no**.  
Each of the layers is equally important to your design. During the exam consider which layers are required as part of the answer.  
Next consider which layers are involved in the background. This can be a very useful way to surface exactly what skills are required by the exam question and help focus your time and attention during the exam.  
If you can rule out a layer there will be more time to focus on what is important in the question. Experienced Cloud Architects have assemblies that are familiar to them.  
A good analogy is a chess expert who sees the board and combinations of pieces rather than individual moves. When they change out one element, they may already know the consequences to security throughput reliability and so forth.  
This familiarity takes time and practice to develop.  
Until you develop your own familiar assemblies it's recommended that you use the model to consider changes in design from each layer and iterate to make sure you've covered everything. It's better to be careful with design and followed a structure approach than to accidentally introduce a design flaw in your thinking and maybe get an exam question wrong.

### Designing a solution infrastructure that meets business requirements

This class follows the exam guide. So whenever you see a slide like this, a blue column contains items directly from the exam guide and the white column contains tips and advice directly relevant to each outlined item.  
You can read through these yourself. I'm going to highlight and discuss one or two of these per slide.  
When we speak about business requirements, we're asking the question, "**What are the customer's needs and expectations?**"  
Questions on the exam are realistic, so on a job, these discussions would likely be with a business stakeholder, and you'd need to be prepared to answer these questions and their concerns.  
You'll notice that the first and last items in the list have to do with determining the criteria for success and deciding how to measure that. It's very important to be explicit about exactly what you're trying to achieve.  
These items are often stated qualitatively at the beginning and are measurable and quantitative at the end. It's extremely difficult to optimize for success criteria and minimize cost at the same time. For this reason, it's recommended that you divide the activity into function first and cost optimization second.  
Another suggestion is to keep existing systems working in parallel for a period of time and verify that the new system is behaving as expected. Be on the lookout for these slides, with a blue column and a white column.  
They're intended to explicate for you what you see on the exam guide and how to prepare.  

Identify the context in which the solution is being employed, think about what the business is trying to accomplish. That will help distinguish between solutions that might seem equally correct.  
There are no universal remedies for all situations. Different design patterns have their best uses and their limitations.  
In every design, there will always be issues that need to be considered. For the exam, you need to know not only design patterns but their context of use and especially what circumstances to apply one design instead of another.  
What's the priority or the blend of priorities? Good, fast, inexpensive?  
How will these priorities be measured? What are the measures of time, budget or qualities?  
How will you know if your design meets requirement if you can describe them and measure them in some way?  
One way to think about these decisions is to consider whether to build a solution from scratch yourself, purchase solution off the self or from a vendor, or customize existing products and services or trade off speed of implementation for perhaps fewer or more general features.  

If you build it yourself, you get absolute control over what the solution does and how it works.  
If you go to the experts who already have handled similar problems and have experienced creating and implementing similar solutions, it's often the fastest way to get the matter resolved.  
Adapting what you already have, which might be partially depreciated or already paid for is often fast, but you'll probably compromise on features.  
A great example of this is with our machine learning products.  
We have pre-trained models, like Cloud Vision API and Natural Language API, which are fast, because you can just grab them and use them.  
We have Cloud ML Engine and TensorFlow, which allow you to take complete control, and we have Cloud Auto ML, which allows you to customize and add to a pre-trained model.

### Case Study 1

This is a very common situation, where it isn't actually an application and a solution, but rather earlier in the business lifecycle moving to cloud. Where the customer's interested in establishing standards and systems whereby their organization can design and develop their own solutions as needed.  
The problem the customer came to us with was that their project teams were provisioning hardware, which was slow and arduous.  
A side effect of the slowness was that it stifled experimentation and innovation. Nobody wants to ask for hardware unless they know exactly what they need it for. That was a business requirement the customer expressed to us.  

A customer had this interesting business requirement.  
Provisioning VMs within their own data center took weeks. They wanted to empower their IT teams to develop new applications in the Cloud, with greater autonomy and more quickly using a hybrid Cloud strategy.  
We need a solution where the customer can provision projects, including runtime environments at scale, and it needs to work very quickly. There's a review process, so this is not a free for all.  
There's a human being or a group that will review certain parameters, a review gate. And basically once a request has passed the review gate, it should only take a couple of minutes for the resources to be deployed.  

We map this to technical requirements like this, a turn-key GCP project for any developer team that requested it. Manually provisioned within 24 hours, following a brief review of the request.  
From a practical implementation perspective, that meant **setting up the organization node**. And folders for each organization for different kinds of organizations and different kinds of projects.  
We implemented **VPN tunnels to GCP**, so the company could reach the cloud resources without having to go through the public Internet space unprotected.  
We also went through a process of identifying the proper **IAM roles** to assign to various environments.  
And we needed to establish processes for project owners to be able to log into the environment. We needed to **synchronize these roles and identities with the Active Directory service** in the datacenter.  

And this is how we implemented that technical requirement.  
User identity via **Google Cloud Directory Sync**, that's **GCDS**, from on-prem.  
Network connectivity between colo and GCP via **two VPN tunnels**.  
**Organization node**, folders by department and use case, project by environment.  
IAM roles, commonly **Project Owner, not Project Creator**.  
We needed to set up processes for establishing new project creation, and who would be assigned specific roles. So there was a kind of process and logic around this that needed to be established.  
What kind of data is going to be stored in each project, is it confidential?  
We need to go through some basic classification, and who's going to pay for it. In this case, there were multiple billing accounts and that needed to be decided.

**Case Study 1**

Case Study 01: Design and Plan

This is a very common situation, where it isn't actually an application and a solution, but rather earlier in the business lifecycle moving to cloud, where the customer is interested in establishing standards and systems whereby their organizations can design and develop their own solutions as needed. The problem the customer came to us with was that their project teams were provisioning hardware, which was slow and arduous. A side effect of the slowness was that it stifled experimentation and innovation. Nobody wants to ask for hardware unless they know exactly what they need it for. That was the business requirement the customer expressed to us.

A customer had this interesting business requirement...
- Provisioning VMs within their own data center took weeks 
- They wanted to empower their IT teams to develop new applications in the Cloud with greater autonomy and more quickly, using a hybrid Cloud strategy

We need a solution where the customer can provision projects, including run-time environments, at scale. And it needs to work very quickly. There is a review process. So this is not a "free-for-all". There is a human being or a group that will review certain parameters - a review gate. And basically, once a request has passed the review gate, it should only take a couple of minutes for the resources to be deployed.

We mapped that to technical requirements like this…
- A turn-key GCP project for any developer team that requested it
- Manually provisioned within 24 hours, following a brief review of the request.

From a practical implementation perspective, that meant setting up the Organization node, and Folders for each organization, for different kinds of organizations and different kinds of projects. We implemented VPN tunnels to GCP so the company could reach the cloud resources without having to go through the public internet space unprotected. We also went through a process of identifying the proper IAM roles to assign to the various environments. And we needed to establish processes for Project Owners to be able to log into the environment. We needed to synchronize these roles and identities with the Active Directory service in the data center.

And this is how we implemented that technical requirement.
- User identity via Google Cloud Directory Sync (GCDS) from on-premise
- Network connectivity between colo and GCP via two VPN tunnels
- Organization node, folders by department and use case, project by environment
- IAM roles commonly Project Owner, not Project Creator.

We needed to set up processes for establishing new project creation and who would be assigned specific roles. So there was a kind of process and logic around this that needed to be established. What kind of data is going to be stored in each project? Is it confidential? We need to go through some basic classification. And who is going to pay for it? In this case there were multiple billing accounts and that needed to be decided.

## Preparing for Technical Design

### Designing a solution infrastructure that meets technical requirements

If a requirement is not described fully, perhaps it's not important to the question being asked.  
Notice that the exam guide highlights fail-over right next to elasticity. Why would that be the case? Well, consider this example.  
A client comes to you and says, "We're happy with our data center solution. We want to use the cloud, but only for fail-over and disaster recovery. Can you help?"  
So, you provide an IT solution in the cloud that gives them a disaster recovery scenario and fail-over capabilities. So, if elements of their existing solution go down, the cloud can provide an alternative.  
Some time goes by and the client comes back to you with an additional request. "The fail-over solution is working great, but we have another problem.  
Sometimes we get demand above our capacity and we don't want to invest in more data center capacity. Can you help us burst into the cloud so when we have extra demand, we can use the cloud for temporary extra capacity?" You modify some of the elements that you built for fail-over and you give them cloud bursting capability. So, there is the elasticity.  

Some more time goes by and the client isn't happy with their colo. They're paying for racks and they don't want to pay more and the equipment needs a refresh and they ask you for some help, "Can you help us migrate our application fully to the cloud so we can scale more dynamically to meet growth?"  
Of course you help them. Now, this is a very common adoption pattern. This is a natural and orderly progression of events. Now, you see why they're located together in the exam guide.  
For the exam, you need to think about what you would measure in the situation. You might not need to calculate anything, but knowing what you need to be measured will help you focus on what information is important in this question.  

Architectural principles. Compose simple services and evolve them, plan to avoid conditions that would lead to failure such as bottlenecks, consider the hardware or service limitations in the cloud, but also plan for resiliency and fast recovery when failure occurs. Consider the time value of the result of the solution.  
Here's an **example**. If a data processing job takes 3,000 years to run, the proposed method might not fit the business requirements and an alternate solution might be better. An old business saying, in business, all values are real-time values. Meaning that you might want to determine when a metric might change or how this will affect the value to the business.  
So, time value, what happens if the solution is delivered sooner or later? In a design class, we often say that all values are real time. In this case, constant value might not have any additional value if it's delivered earlier or later.  
Here's **example two**. This is a solution that has additional value if delivered sooner. So, the sooner it's delivered, the more value it provides.  
In **example three**, it's a solution that has diminishing value if it's delivered late.  
An **example four** has a solution that has no value if it's not delivered on time.  
One example would be an online ordering system tied to an event. If it's ready early, it provides no value because the customers are not ready to take orders and if it comes in a day late, then the customers will no longer be interested. Always take note of state information and consider the impact of storing and retrieving state information on scalability.  

All work in all systems **can be divided up into job shops and assembly lines**.  
In a **job shop**, a single server, service, or unit performs **multiple steps**.  
In an **assembly line**, each server, service, or unit performs **one well-defined step** and hands the work off to another worker for the subsequent steps. Food preparation can help illustrate these principles.  
Here's an assembly line kitchen. Each person is responsible for a specific action. One person places one kind of food on the plate, another puts on the sauce, a third places the garnish. On the one hand, there's not much to remember because each person individually just does one discrete thing over and over again. So, there isn't much state information. But what this model requires is coordination.  
If something happens and one person changes what they're doing, the line has to adjust. If a person in the middle takes a break, everyone further down the line stops working and the work queues up from the workers earlier in the line.  
However, this approach can really be worthwhile because each individual can focus on being really fast and efficient at their task. So, this model scales very well.  
In this instance, there is a single chef who's doing all of the steps, placing the food, adding the sauce, garnishing, so forth. The chef needs to remember what step was just performed and what step needs to happen next. They may need to change tools or fetch different resources.  

All of that information needs to be remembered for the work to proceed is called state information. Just exactly how much state information is required and where the state information is stored has a huge influence on scalability. just to recap, a job shop has to keep track of where it is in the process and that's the state information.  
The assembly line doesn't need to keep track of state. However, the units or microservices have to coordinate with each other.  
So, **queuing and messaging** becomes important as an alternative to keeping state. You can't get away from state in all cases.  
In those cases, you have to try to make state **scalable** and **reliable** and that leads to another common design pattern you'll want to know. Familiarize yourself with common design patterns, not just what they are, but how they work. It can come in handy to imagine the question in the context of a solution.  
For example, dividing the problem solution into front-end and back-end, stateless and stateful can be very helpful in surfacing the key design issues. There are resources, for example, architectures in our online documentation. The design shown is a general solution. It doesn't fit all cases, but is very common.  
First there's a scalable front-end with fail-over.  
Second are many small stateless servers for back-end scalability.  
Third, is the state information isolated and separated from the front and back-end.

### Designing Network, Storage, and Compute Resources

There's usually more than one way to accomplish the same function in a system using different cloud technologies. However, the technologies make a difference in the overall system and its qualities.  
It helps to narrow down your options first based on what could work, and then decide which service is best in a circumstance.  
**Identifying bottlenecks is especially useful** for questions involving building out from existing solutions.  
For example, the current system can support X number of users, and the goal is to support Y number of users.  
What's the bottleneck in the current design? Is it bandwidths, gigabytes, queries per second? Where will the application hit its limits? This is often the factor that determines which solution is best in the circumstance.  

You need to be able to **read data flow diagrams** and to clearly think about the progression of data through a system. Don't assume that data-flow symmetrically, or that the capacities are symmetrical. Acid versus base is essential data knowledge that you'll want to be very familiar with, so that you can easily determine whether a particular data solution is compatible with requirements identified in the case.  
For example, for a financial transaction, **a service that provides only eventual consistently might be incompatible**. Did you know that **in some cases and eventually consistent solution can be made strongly consistent for a specific limited use case**?  
In Cloud Datastore, there are only two APIs that provide a strongly consistent view for reading entity values and indexes.  
First, **the lookup by key method** and second, **the ancestor query**. Database services provide a model of consistency. Consistency makes certain guarantees with respect to data transactions.  
Whatever guarantees are not made by the data service becomes a responsibility of the application code. You should know the definition and significance of atomicity, consistency, isolation, and durability.

### Creating a Migration Plan

In migration to cloud, you're always starting with data and processing in a data center. So, obviously that's the source of truth, and the cloud version is just a copy. But as you go through the migration plan, what happens to the truth?  
Eventually, you want the cloud version to be either equal and related to the data center version or more likely to replace it and allow the data center resources to be repurposed. Where is the source of truth? And when does that change? Often and ambiguous technical situation like which data storage service to select or which compute platform to choose is easily resolved if you think about it in practical terms and go beyond theory.  
**Look for practical clues** in the case question not just technical clues. We often talk about implementing complete solutions in the cloud. That certainly simplifies the design, but realistically there often elements that cannot be migrated from the data center.  

What resources will remain on-prem? What processes are necessary to integrate with existing systems in the cloud in GCP or in other clouds and in the data center? How do you prove to yourself that the solution will work and isn't just a good theory? Do you need to run a proof of concept?  
If you're moving something from a design for efficiency, for cost reduction, **consider the consequences at all the layers**. For example, if you reduce capacity of a solution because there are fewer users, would also reduce or remove the availability or disaster recovery features.  
After a solution is designed and implemented, it goes through a **period of stabilization** prior to the completion of delivery and hand-off.  
What do you need to include in the design to stabilize the solutions?  
What could change or what might need to be measured and adjusted? In some cases, there may be multiple stakeholders. **The best solution will solve for all interests** or for the common interest.  

For example, a CEO wants to improve data analytics, the CTO wants lower cost. At first the two interests might seem in conflict, however, moving to a different more efficient solution may solve both requirements. There's an old saying in IT, "**Every 10 X in growth, something breaks.**"  
This is because the assumptions that went into the original design are no longer true. Quite often scaling up changes the nature of the problem and requires revisiting assumptions.  
So, in exam questions **if you notice rapid growth or other indicators of large-scale change**, start thinking about **what might have broken or what might be ready to break**.  
What processes will you need to define, to keep the solution operating? Monitoring, logging, metrics, to manage too.  
Often the design isn't done at hand-off. In practice, most cloud architects are required to stay on a project for a period after delivery to ensure that the solution continues to work and is maintainable.

### Practice Exam Questions 1

Application parts developed by separate project teams will communicate over RfC 1918 addresses. 
Single project, same VPC.  
Shared VPC each project a service of the shared VPC project.  
Parts communicate using HTTPS.  
Communicate over Global Load balancers, one per project.  

The answer is B. Shared VPC, each project a service of the shared VPC project. Each team has their own project but communicates securely over a single RFC 1918 address space. The specific configuration is called shared VPC. VPC network peering, and it's described in the documentation on VPC peering.  

Which solutions should dress for wins real-time trend analysis using the Cloud?  
Cloud Dataflow, BigQuery, a Hadoop cluster and Compute Engine, or Cloud Dataproc?  
The answer is D. Cloud Dataproc. D, a managed service that can run Hadoop application. Real-time trend analysis, refer to the case study to learn this is Hadoop and Spark.

## Preparing for Managing

Managing and provisioning solution infrastructure. If you think about it, **managing and provisioning are both about capacity and demand and choosing the right infrastructure components** to support and adapt to the demand.  
External connections, know your options. Internet, VPN, Cloud Router and the various flavors of direct interconnects.  
Google Cloud Networking is not like other vendor networks. Not like traditional IP networks and not like other SDN networks.  
That's networking in the cloud and you need to know how you might handle migrating an existing data center network into a GCP network.  
Most confusing for cloud experts from other vendors clouds and yet it makes so much sense.  

A number of features of Google Cloud Networks eliminate the extra work where methods from traditional IP have been inherited out of habit.  
Subnetworks can extend across zones in the same region.  
One VM and an alternate VM can be on the same subnet but in different zones.  
A single firewall rule can apply to both VM's even though they're in different zones. This makes it much easier to design and implement resilient or high-availability solutions. Know your options. When would you choose which method?  
Have you considered backup connections?  
What happens if an interconnect goes down?  
How will you perform maintenance?  
Does the application need to stay up?  

You can create multiple VPNs for higher bandwidth or for alternate paths as backups. But, if the Internet goes down and you have one Internet provider, there's no alternative. Security in the field is practical.  
The goal is to **raise the cost of violating the security above the value of the data**.  
A good model of this is a castle. The bigger and higher the castle walls, the greater the treasure inside or conversely, if you have great treasure inside, you want to raise the castle walls just beyond where it would be worthwhile for someone to store in the castle.  
In the exam, think practical security. What's needed? Unless the requirement is compliance with the standard. Even if you comply with the standard, that might not be sufficient to meet business security requirements.  
Sometimes, standards are floors, the minimum allowable rather than ceilings, the maximum possible.

### Case Study 2

Case study two. One thing I see with every large customer is that they have business requirements. They want a document resources. If I'm paying the bill, I want to know who's consuming resources, spinning up VMs for example, and I want to know that this is going through some sort of review process.  
This customer want me to minimize the impact to the developer productivity. So, as soon as you start to add any sort of process, you slow things down.  
They were very concerned that I **would not hurt their productivity**.  
That was both a technical requirement and a business requirement. So, a customer had this interesting business requirement.  
Cloud infrastructure resource provisioning must be **documented and auditable**.  
Changes to the cloud infrastructure must go through a review process, and a specific requirement must minimize impact to developer velocity.  
We immediately knew that part of the solution was **infrastructure as code.** There are a lot of reasons to implement infrastructure as code, but forcing a solution into this implementation means you get the benefits of auditing, code review, and all those things that help satisfy their business requirement.  
The customer has dozens of development teams, but only one cloud engineer. So, the solution needed to be distributed. Each team is actually responsible for their own process. We map that to technical requirements like this, provisioning infrastructure should be done as infrastructure as code.  
Specifically, decentralize approval code review process. Teams should own the process. This is how we implemented that technical requirement.  
We use terraform and Deployment Manager, and IAM strategy based on least privilege, service accounts, and specifically, we utilized source control options such as GitHub Enterprise.  
They use GitHub Enterprise with a code owners file and the file is a text file that limits who can actually perform actions in the repository.

**Case Study 02: Provision and Manage**

One thing I see with every large customer is that they have business requirements; they want to document resources. If I'm paying the bill, I want to know who is consuming resources, spinning up VMs for example. And I want to know that this is going through some sort of review process.

This customer wanted me to minimize the impact to the developer productivity. As soon as you start to add any sort of process, you slow things down. And they were very concerned that I not hurt their productivity. That was both a technical requirement and a business requirement.

A customer had this interesting business requirement...

- Cloud infrastructure resource provisioning must be documented and auditable
- Changes to the cloud infrastructure must go through a review process
- Specific: Must minimize impact to developer velocity

We immediately knew that part of the solution was "infrastructure as code". There are a lot of reasons to implement infrastructure as code. But forcing a solution into this implementation means you get the benefits of auditing, code review, and all those things that help satisfy the business requirement.

The customer has dozens of development teams but only one Cloud Engineer. So the solution needed to be distributed. Each team is actually responsible for owning their own process.

We mapped that to technical requirements like this…

- Provisioning infrastructure should be done as Infrastructure as Code
- Specific: Decentralize approval/code review process. Teams should own process.

And this is how we implemented that technical requirement.

- Terraform/Deployment Manager
- IAM Strategy - Least Privilege
- Service Accounts
- Specific: Utilize source control options, such as Github Enterprise

They use Github Enterprise with a code owners file. The file is a text file that limits who can actually perform actions in the repository.

## Preparing for Data Processing

### Configuring individual Storage Systems

Dig into the details in each storage or data option.  
Learning the difference between BigQuery and Cloud Bigtable and which one is a managed service and which one is serverless is not something you want to be doing during the exam.  
**BigQuery is an inexpensive datastore for tabular data**. It's cost comparable with cloud storage, so it makes sense to ingest into BigQuery and leaves the data there.  
Ingesting the data depends on where it's coming from.  
**Cloud logs, gap, can directly be ingested into BQ**. From pub sub, you have an API. In the most general case, you can use Dataflow and write code to ingest data in batch or stream.  
You could also use open source tools like Spark or Hadoop to do the processing in which case you'd use Cloud Dataproc.  
The analysis itself is done by BigQuery.  
Results can be visualized in iPython notebook like in datalab or CoLab or in third-party tools.  
So, BigQuery's role is in both storage and in analysis. In other words, it's a **data warehousing solution**.  
Cloud Bigtable is not a relational database. It does not support SQL queries or joins nor does it support multi-row transactions. Also, it's **not a good solution for small amounts of data like less than one terabyte**.  

If you need full SQL support for an online transaction processing system, that's OLTP, consider Cloud SQL and Cloud Spanner. Cloud Spanner is particularly suited for databases larger than about two terabytes and databases that will be written to by global clients.  
If you need to store immutable blobs larger than 10 megabytes such as large integers or movies, consider Cloud Ctorage.  
If you need to store highly structured objects or if you require support for ACID transactions and SQL-like queries, consider Cloud Datastore.  
If you need interactive querying in an online analytical processing or OLAP system, consider BigQuery. You should probably commit this table to memory and be able to use it backwards.  
For example, **if the exam question contains data warehouse, you should be thinking BigQuery is a candidate**.  

GoogleCloud Platform delivers various storage service offerings which remove much of the burden of building and managing storage and infrastructure.  
Like Google's other cloud services, storage services free you to focus on doing what you do best and differentiating at the application or a services layer. Google's storage offerings range across the spectrum. You can use different types of storage in the same project.  
Cloud SQL gives you fully managed MySQL so you have relational DB and a more traditional approach to queries, cloud Datastore provides a nearly infinitely scalable schema-less solution. If you want a disk, you can mount persistent disk as a block store that can be used by a Compute Engine or just pure data and blobs, use cloud storage when that will deliver what you need.  
Cloud Bigtable offers companies a fast fully managed infinitely scalable NoSQL database service, ideal for web mobile and IOT applications. BigQuery is recommended as a data warehouse. BigQuery is the default storage solution for tabular data.  
Use CloudSQL if you need transactions, and use Cloud Bigtable if you want low latency and high throughput.  
Firebase differs from Cloud Datastore in many significant ways. **Firebase is a mobile platform** that provides features beyond storage including authentication, notifications, and real-time synchronization of clients.  
Cloud Datastore is a NoSQL database.  
Cloud Bigtable can scale to massive amounts of data, Cloud Bigtable queries can be more sophisticated than Firebase queries. The top one is a scalable web app with mobile support. Cloud Functions drive a Cloud Bigtable back-end and the bottom one is a mobile client app.  
**Mobile clients interact with Firebase**, and App Engine provides back-end processing.

### Data transfer

Global Google Cloud Network Integration with Google Cloud Storage, enables high bandwidth upload from anywhere.  
App Engine provides authentication and ingest coordination, and management between the network and storage. Upload is exposed to browsers through a web UI implemented on App Engine. Upload is provided for client applications via RESTful APIs exposed by Cloud Endpoints.  
This is an example of a lazy deletion design. There are a number of layers of soft deletion, and delay between steps that should be tuned to the application and its business requirements. Data integrity is the quality of the data remaining accurate and accessible.  
If the **data loses accessibility or accuracy, it's no longer reliable to the system**, and the users, and therefore has lost integrity. Many kinds of failure including human error can lead to data loss. Strategy is defense in depth.  
How long does it take to transfer data online? The left side of the table are closer to physical speeds, and the right side of the table is closer to online speeds. Therefore, it's much faster to accumulate data online and work with it and transfer it online, than to collect the data physically and then transfer it.

### Cloud Storage

Cloud Storage backup is often the easiest and first cloud application for many businesses. Archive is a natural step. And once the utility and value are understood, a common follow-on step is to reduce the cost and overhead of maintaining offline archive storage such as tape libraries by directly loading them into archival storage.
Cloud Storage offers four storage classes. Customers can associate each of their buckets with the storage class most appropriate for its use case. **All of the storage classes are accessed in analogous ways using the Cloud Storage API**, and all offer millisecond access times.  
**All storage classes incur a cost per gigabyte of data storage per month**, and **egress and data transfer charges may apply**.  
In addition to those charges, nearline storage also incurs an access fee per gigabyte of data read, and coldline storage incurs a higher fee per gigabyte of data read. See the Cloud Storage pricing page for more information.  
First, temporary data, maybe you want to use a local disk. Standard and regional HDDs and SSDs are now supported. Regional versions have zonal redundancy.

### Data processing to Machine Learning

Data Center Migration. BigQuery provides a front-end for analysis and a back-end that can read from several sources including BigQuery tables, but also CSV files in Cloud Storage.  
Cloud Dataproc is a managed service for Hadoop clusters, useful for processing data and returning it to Cloud Storage or BigQuery.  
The first step is migration from Data Center processing to Cloud Data processing. BigQuery replaces many tools and custom applications in data center, while **Cloud Dataproc replaces Hadoop**.  
Cloud Bigtable is a drop in replacement for Hbase. Machine learning is available from Cloud Dataproc using APIs, such as natural language processing or NLP. When ready, the business can move from cluster-based managed service to a serverless service, and access the full benefits of machine learning.  
Machine learning provides value through tagging of unstructured data, which makes it useful for specific purposes. Machine learning can also be used to recognize items and for prediction.  
Machine learning is more of a focus of the data engineering track rather than the cloud architect track. But it's still part of the infrastructure of a cloud architect, and it might be used for finding solutions. So, you should be familiar with the services and what they do.

## Preparing for Compute

### Configuring Compute Systems

We've already covered many of these items. One thing to consider in the design is whether you can create an application that's tolerant of some amount of lost data or state and part of the system can simply drop some data or can store data externally and recover from drops.  
Then if that part is isolated, you can consider using **Preemptible VMs for lower cost**. By the way, do you remember what the maximum time is that you would have control of a Preemptible VM? **It's 24 hours**. If a VM hasn't been requested by then, it'll be pulled from service anyway.  
Development environments and disaster recovery are often good applications for creating infrastructure through automation technologies such as Deployment Manager or Terraform. In the development environment case, you can generate a clone of the production infrastructure solution or use by the development team.  

So the test team needs an environment, deploy another copy.  
Quality control needs and environment, another copy.  
Auditing and compliance test backup and recovery, create more deployments on demand. There's no perfect solution for all circumstances.  
But there are usually several options that can work and one that is optimal for a specific situation. In general, if your use case is application focused, App Engine is the fastest way to get something up and running with the least infrastructure overhead. Kubernetes is more complicated and places more responsibilities on the developer and the support staff. Fewer items in Kubernetes are automated when compared with App Engine. On the other hand, it offers controls over automation and Kubernetes can make the application platform independent which is easier for development and migration of support for different environments.  
Compute Engine is a VM. The software installation and maintenance gives far greater control and performance efficiency at the expense of IT overhead. Finally, Cloud functions provide a micro-services approach which means creating small stateless elements, very fast and scalable. But you have to be diligent about isolating state and there's additional programming overhead involved. You can also implement micro-services solutions on Kubernetes. This is another one of those tables that you should know backwards and forwards. For example, if a solution involves Node.js, which compute service should immediately become a candidate for part of the solution? App Engine Flex and Cloud Functions both support Node.js.  

First of all, **there's no such thing as a load balancer in Google Cloud**. Allow me to explain. In Google Cloud, there is no load balancer because the function of distributing traffic is handled by the software defined network.  
So there are several kinds of load balancing. But these are **just features that are part of the network**, not physical devices.  
Load balancing services are distinguished by the kind of traffic they direct. By whether they're intended to balance traffic from one server to another inside the Google Cloud or if they're intended to direct data arriving from the Internet.  
Also load balancing can be global or applied to a specific region. Make sure you understand the basics of how geo-distributed and load balancing works. How can everyone go to the homepage for google.com and get great response time as if from a local server?  
Unmanaged instance groups collect different kinds of instances. Usually, this is done for management of lift and shift existing designs and it's not recommended because it does not make the best use of the features available in cloud.  
**Managed instance groups** are all the same kinds of instances meaning that the type can be defined by an instance template and auto-scaling is available. **Zonal managed instance groups keep all the instances in the same zone** which is useful to provide consistent network location when the instances must communicate with similar latency and avoid zone to zone transfer.  
Regional managed instance groups distribute the instance and multiple zones within the region increasing reliability. Instance groups should be managed instance groups to make effective use of the cloud.

### Microservices, Containers, Data Processing, and IoT

Microservices is not a panacea, it doesn't fit all cases. You can implement a microservices solution in App Engine cloud functions and using Node.js and Kubernetes.  
The platforms have overlapping coverage. Do you know when you might choose one platform over another for microservices solution? Coordinating a transaction across stateless microservices is tricky. You have to store the state externally and retrieve and use it in each function.  
Microservices architectures are commonly used and implemented in Cloud Functions or in App Engine. Containers bundle application code and dependencies into a single unit, abstracting the application from the infrastructure.  

Make sure you know the difference between containers and VMs. Make sure you know the basics of Kubernetes. When might you use a different pod? How does code maintenance and migration to a new version work? Understand AB testing and deployment.  
A pod is Kubernetes engine abstraction to represent an application. It holds one or more containers. The containers in the pod share a single IP address and a single namespace.  
A pod can share other items such as access to storage. Any data access mattered on a pod called a volume is available to all containers in the pod. Containers that are part of the same pod are guaranteed to be scheduled together on the same VM and can share state via local volumes.  
Persistent volumes using persistent disks in Compute Engine survive instance and container restarts. How do you balance resiliency, scalability, and cost?  

Well, small stateless servers are more scalable and reliable closer to a microservices designed. Of course, you have to coordinate all the messaging and state storage and retrieval.  
So the **cost is increased complexity**.  
Large stateful servers reduce application complexity. They allow you to combine activities and organize them making the application more manageable. However, this comes at a cost of decreased scalability and a greater chance that if something goes wrong it will take down the service.  
What you want to do is **blend the approaches where it makes sense to the business**. This is another case where what the client wants is what's most important to the design and on an exam it means being sensitive to and looking out for those trade-offs. Services, managed services, and serverless services, knowing the differences between them will help distinguish solutions that meet all the requirements.  

A managed service gives you visibility to servers but limited control. You give up control for automation. It's great for popular use cases and eliminating overhead.  
Serverless services **completely hide all servers**. Generally, it's more fast scalable and efficient than you could create on your own. The key trade off their proprietary. To be fair, all services are sometimes called managed services even if they're really serverless services.  
I mentioned previously that there are common assemblies of services that work together. If you review solutions and diagrams, you'll start to recognize some. There's a great resource for becoming familiar with a variety of solution architectures online.  

Look for it at cloud.google.com/solutions. The core assembly here is IoT Core, Cloud Functions, Cloud Pub Sub, and Cloud Dataflow. The IoT core device manager. Google Cloud IoT Core provides a fully managed service for device registration, authentication, authorization, metadata and configuration.  
**Cloud Pub Sub**. Google Cloud Pub Sub provides a globally durable message ingestion service.  
Cloud Pub Sub **can act like a shock absorber** and rate level or for incoming data. Cloud Pub Sub scales to handle data spikes that can occur when swarms of devices respond to events in the physical world. It buffers these spikes to help isolate them from applications monitoring their data.  
**Cloud Dataflow**. Google Cloud Dataflow provides the open Apache Beam programming model as a managed service for processing data in multiple ways including batch, extract transform load ETL patterns, and continuous streaming patterns. Cloud Dataflow performs well with high volume data processing.  
**Cloud Functions**. IoT events and data can be sent to the cloud at a high rate and need to be processed quickly. Cloud functions allow you to write custom logic that can be applied to each event as it arrives. This can be used to trigger alerts, filter invalid data, or invoke other APIs. Cloud Functions can operate on each published event individually.

### Experiment: Containers and GKE video (Like/Dislike)

Between 2017 and 2018, the number of organizations using containers for software development had to deploy their services doubled.  
The trend shows no signs of slowing. For this reason, container knowledge and skill with Kubernetes is increasing the importance for the job of a Cloud architect.  
Of course, if you need more of these skills for the job, you will also need them to prepare for the exam. Docker is software that builds containers. User apply application code and instructions called a Docker file, and Docker follows the instructions and assembles the code and dependencies into the container. Containers can be run much as an application can run. However, it is a self-contained environment that can run on many platforms.  
Google Cloud offers a service called **Cloud Build** which functions similarly to Docker. It accepts code and configuration and builds containers. Cloud Build offers many features and services that are geared towards professional development.  

It is designed to fit into a continuous development, continuous deployment workflow. It is designed to scale and to handle many application developers working on, and continuously updating a live global service. If you had 100 developers sharing source files, you would need a system for managing them, for tracking them, versioning them, and enforcing a checking review and approval process.  
**Cloud Source Repositories** is a cloud-based solution. If you were deploying hundreds of containers, you would not be in keeping it to yourself. One of the reasons to use containers is to share them with others. So you need a way to manage and share them. This is the purpose of container registry.  
Container registry has various integrations with continuous integration, continuous deployment services. A Docker container is an image built-in layers. Each layer is created by an instruction in the Docker file. All the layers except for the top one are air locked. The thin read-write layer at the top is where you can make changes to a running container. For example, if you needed to change a file, those changes would be written here. The layer designed inside of a container isolates functions. This is what makes the container stable and portable.  
Here are a few of the common Docker commands.  
The docker build command creates the container image.  
The docker run command runs the container.  
There are other Docker commands that can help you list images, check the status of a running container, work with logs or stop a running container. You can run a container in Docker itself, as you saw with the docker run command. You can also run containers using Compute Engine.  

**Compute Engine** gives you the alternative to start up a virtual machine from a container, rather than from an OS Image Boot Disk. You also have this option when creating an instance template, which means you can create managed instance groups from containers.  
**App Engine** supports containers as custom runtimes. The main difference between the App Engine standard environment and the App Engine flexible environment is that flexible hosts applications in Docker containers. It creates Docker containers and persists them in Container Registry.  
A Container Orchestrator is a full service for managing, running and monitoring containers. Both App Engine flexible environment and Google Kubernetes engine are container orchestrators. Kubernetes is an open standard software.  
So you can run a Kubernetes cluster in your data center. Google Kubernetes engine provides Kubernetes as a managed service. A Kubernetes cluster is composed of nodes, which are a unit of hardware resources. Nodes in GKA are implemented as VMs in Compute Engine. Each node has pods. Pods are resource management units. A pod is how Kubernetes controls and manages resources needed by applications and how it executes code.  
Pods also give the system fine grain control over scaling. Each pod host, manages, and runs one or more containers. The containers in a pod share networking and storage.  
So typically, there is one container per pod, unless the containers hold closely related applications. For example, a second container might contain a logging system for the application in the first container.  
A pod can be moved from one node to another without reconfiguring or rebuilding anything. This design enables advanced controls and operations that gives systems built on Kubernetes unique qualities.  
Each cluster has a master node that determines what happens on the cluster. There are usually at least three of them for availability, and they can be located across zones. A Kubernetes job makes changes to the cluster. For example, a pod YAML file provides the information to start up and run a pod on a node. If for some reason a pod stops running or a node is lost, the pod will not automatically be replaced.  
The deployment YAML tells Kubernetes how many pods you want running. So the Kubernetes deployment is what keeps a number of pods running.  
The deployment YAML also defines a replica set, which has how many copies of a container you want running. The Kubernetes scheduler determines on which node and in which pod the replica containers are to be run.  
One of the advanced things that Kubernetes deployments allow you to do is roll out software to some pods and not others. So you can actually keep version in production on most of the pods and try out version B with a sample group and other pods.  
This is called A/B testing, and it is great because you can test the new software in a real production environment without risking the integrity of the entire service.  
Another thing you can do with deployments is a rolling update. Basically, you load up the new software in a replacement pod, switch the load to the new pod, and turn down the old one. This allows you to perform a controlled and gradual roll out of the new software across the service. If something goes wrong, you can detect the problem and roll back to the previous software.  
Really, if you are going to run an enterprise production service you will need these kinds of operations. That is one major reason to adopt Kubernetes. There are a number of subjects that were not covered in this brief overview.  
For example, how containers running in the same pod can share resources, how containers running in different pods can communicate, and how networking is handled between a node's IP and the applications. These subjects and more are covered in the course, getting started with Google Kubernetes engine or you can find more information in the online documentation.

### Practice Exam Questions 2

Which network feature could help a company meet its goals to expand service to Asia while reducing latency?  
- HTTP/TCP load balancing,  
- network TCP/UDP,  
- Cloud Router,  
- or Cloud Content Delivery Network (CDN).  

The answer is D, Cloud Content Delivery Network (CDN).  
CDN will enable a company to expand its online presence with a single IP address and global reach, leveraging Google's global network. While global load balancing is part of CDN, it won't help reduce latency to customers in Asia, whereas the cache service in CDN will do that.  
Network load balancing is designed to load balance from one GCP service to another to scale back end services, which is called east-west communications. North-south communications, where one part is in the GCP network and the other part is external, requires a different kind of load balancing.  
Cloud Router uses BGP to discover changes in network topology in a remote network, so it doesn't address latency.  

How can you minimize the cost of storing security video files that are processed repeatedly for 30 days?  
- First, Regional class, then move to Coldline after 30 days;  
- next, Nearline class, then move to Coldline after 30 days;  
- Regional class, then move to Nearline after 30 days;  
- or Multi-Regional class, and then move to Coldline after 30 days?  

The answer is A, Regional class, then move to Coldline after 30 days. The question here is answered by understanding the purpose of each of the storage classes and, in general, how they're priced. One thing to remember is that **Coldline is really not intended to be read more than once a year**.  
It's cheap to write data to it, but much more to read it back, compared to the other classes of storage. So the correct answer is A, local usage in a regional bucket for initial use during the month, then Coldline because it's unlikely to be read after that. This is often the case when data is used during the month and archived for compliance and record keeping after. The other options will not be cost effective.

## Challenge Lab

Problem solving is the key skill of the job.
During the exam you will be reading a question or a case and the problem it is describing should start to inform and define a solution in your mind.  
The faster and more clearly you can **understand the requirements and identify elements that might be part of the solution**, the better the chances are that you will understand the question correctly and be able to identify the correct answer. This is what we mean by the best preparation for the exam is to be prepared for the job.

**Practice problem solving**  
There are sample/practice exam-type questions throughout this course and a simulated exam quiz at the end. Don't just read through these or watch these for information.  
It is not there to teach you the right answer to a particular question. It is there to give you the opportunity to practice using your problem-solving skills, which you will need on the job and for the exam.

Practice evaluating your own confidence about information, an answer, or a solution.  
Another skill that will help you on the job and on the exam is being able to evaluate your own confidence about your knowledge.  
People often assume that they either know something or they don't know it, they either recall it or they don't. But in fact, recall is much less binary than that. What we don't often get the chance to practice is evaluating how well we know something or how certain we are of answers or solutions.

This is really important. Because if you know that you are not certain of something, then you can use that as a guide to help you decide what to study, how to prioritize your study time, and how much effort to apply.

This means that you learn more from missing a question and answering it incorrectly in this course than from answering it correctly.  
When you miss a question, it is an indicator to take note that this is something you might want to study to better prepare for the exam.

How much confidence do you want?  I will often dig into the documentation and not only prove to myself exactly why the correct answer is correct.  
But I will also continue studying until I know with absolute certainty exactly why each incorrect answer is wrong. I want to be able to state the reason it is not correct. Because that is how I know that I have studied enough.

## Preparing for Optimizing and Operating

This module covered the sections of the exams outline on optimizing and operating. You can optimize a solution **for many things such as reliability, efficiency, low cost, high performance, or security**.  
Let's begin with security and compliance. Security is a broad term. It includes **privacy, authentication and authorization, and identity and access management**. It could include intrusion detection, attack mitigation, resilience and recovery. So security really appears across the documentation and not in just one place. Compliance is about meeting some external guideline or standard

### Case Study 3

The following is a case study that involves a financial services company. This vertical often involves private information and transactions, so the security requirements are high. Also these kinds of companies often need a plan for audits to meet compliance requirements for certifications.  
This customer had a common FinServ requirement. The customer **did not want any data to traverse the public Internet**, for obvious reasons.  
So they had a security strategy that included a technical requirement to use private APIs to access Google Cloud resources. They saw this is a fundamental need to their security strategy.  
Additionally, they wanted to know how the cloud provider's security standard certifications, and what they did to stay current. So they were concerned that the provider might lose the certification that they were relying on for business. A large company wanted to improve their security posture, a common FinServ requirement.

**Security, business requirement**, data cannot traverse the public Internet.  
**Technical requirement**, must have private API access to GCP services as a good security practice and to minimize data exfiltration.  
**Compliance, business requirement,** cloud provider must earn the trust of the business.  
How does Google Cloud maintain the latest standards around security, availability, process integrity, privacy, and confidentiality?  
The first thing we did was make sure all access to GCP was through secure methods including **SSL, VPN, Interconnect and private API**. We decided to use a new feature that was in alpha called **VPC service control**.  

This enables the security perimeter. For example BigQuery could placed inside a security perimeter, and then could only be accessed at a private endpoint. And then there were standards and compliance such as ISO and SOC.  
We provided these to the customer and they needed to sign agreements to be covered by Google's guarantees about these standards.
We mapped that technical requirement in Google's clouds, products and services.  
**Security**, ensure all traffic to GCP is through secure methods, such as SSL, TLS, VPN, Interconnect, private APIs and endpoints.  
**Compliance**, Google Cloud has standards, regulations, and certifications that would meet their compliance requirements and help earn their trust in our platform.

And this is how we implemented that technical requirement.  
**VPC service controls, secure GCP API**.
We restricted access to user GCP resources based on the Google Cloud Virtual Network or IP range. We restricted the set of Google APIs and GCP resources accessible from user's Google Cloud Virtual Network.
Standards, regulations, and certifications. Products regularly undergo independent verification of security, privacy, compliance controls, certifications.  
And so ISO 27001, 27017, and 27018 and SOC 1, 2, and 3 certifications. An interesting point about both security and compliance is that it's a shared responsibility model. So although we provided secure access and layered protection, the customer needed to **use IAM to manage access to its employees**.  
And implement secure practices in its procedures. Also, the standard compliance covers the cloud resources, but not the customer's application. So they may need to take extra steps to ensure that the overall solution is compliant.

**Case 03: Security and Compliance**

This customer had a common FinServ requirement. The customer did not want any data to traverse the public internet, for obvious reasons. So they had a security strategy that included a technical requirement to use private APIs to access Google Cloud resources.  
They saw this as fundamental to their security strategy. Additionally, they wanted to know how the Cloud Provider secured Standards Certifications, and what they did to stay current. They were concerned that the provider might lose a certification that they were relying on for business.

A large financial company wanted to improve their security posture, a common FinServ requirement...

**Security**  

- Business Requirement: Data cannot traverse the public Internet.  
- Technical Requirement: Must have private API access to GCP services as a good security practice and to minimize data exfiltration.

**Compliance**

- Business Requirement: Cloud provider must earn the trust of the business. How does Google Cloud maintain the latest standards around security, availability, process integrity, privacy, and confidentiality?  

The first thing we did was made sure all access to GCP was through secure methods, including SSL, VPN, Interconnect, and private API.  

We decided to use a new feature that was in alpha, called VPC Service control. https://cloud.google.com/vpc-service-controls/ This enables a security perimeter. For example, BigQuery could be placed inside a security perimeter, and then could only be accessed at a private endpoint. And then there were standards and compliance such as ISO and SOC. We provided these to the customer - and they needed to sign agreements to be covered by Google's guarantees about these standards.

We mapped that to technical requirements and Google Cloud’s products and services…

**Security**

- Ensure all traffic to GCP is through secure methods, such as SSL/TLS, VPN, Interconnect, and private APIs / private endpoints.  

**Compliance**

- Google Cloud has Standards, Regulations & Certifications that would meet their compliance requirements and help earn their trust in our platform.  

And this is how we implemented that technical requirement.

VPC Service Controls / Secure GCP API

- Restrict access to user’s GCP resources based on the Google Cloud Virtual Network or IP range.  
- Restrict the set of Google APIs and GCP resources accessible from user’s Google Cloud Virtual Network.  

Standards, Regulations & Certifications

- Products regularly undergo independent verification of:  
  - Security / Privacy / Compliance Controls
  - Certifications  
  - ISO 27001, 27017, and 27018 and SOC 1, 2, and 3 certifications.  
- An interesting point about both security and compliance, is that it is a "shared responsibility" model. So although we provided secure access and layered protection, the customer needed to use IAM to manage access to its employees and implement secure practices in its procedures. Also, the standards compliance covers the cloud resources, but not the customer's application. So they may need to take extra steps to ensure that the overall solution is compliant.

## Preparing for Security and Compliance

### Designing for Security

One key to securing access is to request and established **groups** that represent **roles**. Then apply the **permissions** to the groups, and allow the people in the organization who manage identity to assign membership to the groups.  
This creates a clean interface between permission management on the cloud side, and group membership on the personnel IT side.  
Another key to security, is to craft security permissions. **The standard roles are defined for the most common use cases**, but you might want to derive more granular and restricted roles by customizing them.  
**Service accounts** are a great way to separate system components, and established secure communications between components.  
**A bastion host is a way to leverage a service account**. For risky and uncommon actions, make the user admin startup and log into bastion host.  
From there they can borrow the service account assigned to the host to perform restricted functions.  

One benefit is that the login process generates logs for accountability. A policy is set on a resorts, and each policy contains a set of rules enroll members. Resources inherit policies from parents.  
So, a policy can be set on a resource for example, a service, and another policy can be set on a parents such as a project that contains that service.  
**The final policy is the union of the parent policy and the resource policy**.  
What happens when these two policies are in conflict? What if the policy on the resource only gives access to a single cloud storage bucket, and restricts access to all other buckets? However, at the project level, a rule exists that grants access to all buckets in the project.  
Which rule wins? The more restrictive rule on the resource or the moral general role on the project? **If the parent policy is less restrictive, it overrides a more restrictive resource policy**.  
So, in this case, the project policy wins. Folders map well to organization structure. It's a way to isolate organizations or users or products while still having them share billing and corporate resources. Commit a security checklist to memory. Sometimes just running down a list will rapidly identify a solution.

### Designing for Legal Compliance

What are the two most common compliance areas?  
Privacy regulations such as HIPAA and GPDR, and commercial and live business standards such as PCI DSS.  
Google Network has layers of protection. Each layer protects and compliments the next internal layer. The main thing to know is that Google handles security up to a point, after that, the security is up to you. So, you need to know where your responsibilities begin.  
**Secure VPC**; identify optimal VPC topology, deploy distributed firewalls, control access with IAM permissions, avoid adding public IPs to instances.  

Access Google services internally.  
**Cloud Interconnect**, connect securely to on-prem or other cloud deployments, Private Interconnect, Carrier Interconnect, Direct Peering, VPN.  
Third-Party Virtual Appliances, enhance VPC security with third party appliances, Next-gen firewalls, IDS slash IPS, that's intrusion detection.  
Logging, monitoring, scale third-party appliances using internal load balancing so you don't create choke points in your VPC.  
**Global Cloud Load Balancing** provides edge protection and global infrastructure protection for IPv4 and IPv6. Layer three and layer four, denial of service protections.  

**Anycast IP even if backends are in multiple regions** to absorb a tax for resiliency, auto-scaling, cross-region, overflow, and cross-region failover.  
**Google network**; high-capacity, high-performance, software defined network, virtualization global networks with subnets, organizations, folders, cross-project networking, peering.  
**Third-Party DDoS**, you can complement the infrastructure with additional security from third-party providers.  
Here's some key concepts: Cloud Armor, Cloud Load Balancing, Cloud Firewall Rules, Service Accounts, separation into front-end and back-end, isolation of resources using separate service accounts between devices.  
Because of pervasive availability of firewall rules, you don't have to install a router in the network at a particular location to get firewall protection. That means you can layer the firewalls as shown in this example, because of pervasive support for Service Accounts you can lock down connections between components.  

When faced with a security question on an exam or in practice, **determine which of the specific technologies or services is being discussed**: Authentication, encryption for example, then determine exactly what the goals are for sufficient security.  
Is it deterrence? Is it meeting a standard for compliance? Is the goal to eliminate a particular risk or vulnerability?  
This will help you define a scope of a solution whether it's on an exam or in a real-world application. GCP provides several encryption options. Customer Managed encryption keys CMEK, using Cloud KMS.  
When you use Cloud Dataproc, cluster and job data is stored on persistent disks associated with the Compute Engine VMs in your cluster, and in a Cloud Storage bucket. The persistent disk and bucket data is encrypted using a Google-generated data encryption key called a DEK and a key encryption key called a KEK.  
**The CMEK feature** allows you to create use and revoke the key encryption key, the KEK. Google still controls the data encryption key or the DEK. Default encryption, encryption at rest uses the key management system KMS to generate KEKs and DEKs. The Key Management Service KMS allows you to generate AES-256 keys. You can use these values off Cloud. The service also handles key rotation and when a file is destroyed there is a 24-hour delay before final deletion.

### Practice Exam Questions 3

Which Cloud IAM roles for security auditors requiring visibility across all projects?  
- A, Org viewer, project owner.  
- B, Org viewer, project viewer.  
- C, Org admin, project browser.  
- D, Project owner, network admin.

And the answer is B, Org viewer, project viewer. This solution gives read-only access across the entire company. The other options allow changes that should not be permitted.  

Dress4Win security has decided to standardize on AES256 for storage device encryption. Which strategy should be used with Compute Engine instances?  
- So like SSDs rather than HDDs to ensure AES256 encryption.  
- Use the linux dm-crypt tool for whole-disk encryption.  
- Use the Customer Supplied Encryption Keys, CSEK.
- Use open SSL for AES256 file encryption.  

The answer is A, Select SSDs rather than HDD to ensure AES256 encryption.  
Selection of disk type determines the default method for whole-disk encryption. HDDs use AES128 and SDDs use AES256. In addition to the storage system level encryption described above, in most cases, data is also encrypted at the storage device level. With at least AES128 for hard disks HDD and AES256 for new solid state drives SSD. Using a separate device level key which is different than the key used to encrypt the data at the storage level. As older devices are replaced solely AES256 will be used for device level encryption.

### Case Study 4

This section covers analyzing and optimizing technical and business processes in the exam guide outline. Let's start with a case that will illustrate business requirements.  
You may have seen this situation before, the customer experiences that pushing to production is scary because you'll never know when things might break.  
This customer could only push to production once a month. There was significant risk of downtime and when there was downtime the application breaks and that impacts revenue.  

So the summary is **we need to be able to develop and deploy features needed to present to production without it being an event**.  
A customer had this interesting business requirement.  
- Pushing to prod is a big event and happens once a month.  
- Significant risk of downtime due to unforeseen issues.  
- Downtime exceeds SLAs that have revenue impact.  
- Need to develop and deploy features without burning the house down.  
- Pushing to production should be a non-event.  

There are two passes through the problem in the architectural process. First, there's the business pass which includes both the business challenge and the people processes understanding what roles there are and what actions that people need to be able to take.  
And then there's the technical pass which is mapping all of these needs and procedures to a technical solution.  

We mapped that to technical requirements like this.  

Establish a CI/CD pipeline:  
- Single source repo per product, git-flow as branching model.  
- Automate build, self-testing, rapid.  
- Automate deployment.  
- Setup robust monitoring, logging and alerting for visibility.  

Promote team culture:  
- Test Driven Development.  
- Push often, address broken builds immediately.  
- Transparency.  
- Change management, and release process.  

To push to production on demand, we needed to analyze the development process. We figured out that a single source repo made the most sense for the whole team. We decided to go with git-flow as a branching model instead of other kinds of development.  
We automated the build process, but also we made sure that the builds were self testing using salt test coverage.  
And we measure the build process to make sure that it was rapid.  
We also automated the deployment of the solution software, couple of these automation with monitoring login and alerting. And you get a nice build and deploy system that can be headed off to a team. But that doesn't solve the entire problem.  
The system has to be used and this team was not going to be accustomed to using the development paradigm we've implemented. So we also needed to do was to enhance their processes.  
This primarily had to do with how test and development work together. In the new paradigm, they would start writing the testing along with development. The new way was to push reproduction off and then push early, and as soon as something would break, fix it.  
This meant a new team culture, one of accountability and transparency where all the stakeholders could participate in identifying and resolving a problem. And that meant change management and leadership buy-end was necessary for the technical solution to be successful  

And this is how we implemented that technical requirement.  
Cloud Source Repositories for hosting of repositories.  
Container Builder that builds the Docker container images.  
Container Registry that hosts these container images.  
Google Kubernetes Engine, +Helm for running and managing.  
And Spinnaker for CDP for continuous delivery.  
Cloud Load Balancing, Stackdriver, Cloud IAM, and Service Accounts and manageability constructs for proper visibility.

**Case 04: Technical and Business Processes**

You may have seen this situation before. The customer experience is that pushing to production is scary, because you never know when things might break. This customer could only push to production once a month. There was significant risk of downtime. And when there was downtime, the application breaks, and that impacts revenue. So the summary is… we need to be able to develop and deploy features, need to present to production, without it being an event.

A customer had this interesting business requirement...

- Pushing to Prod is a big event and happens once a month.
- Significant risk of downtime due to unforeseen issues.
- Downtimes exceeding SLA have revenue impact.
- Need to develop and deploy features without burning the house down. Pushing to Prod should be a non-event.

There are two passes through the problem in the architectural process. First, there is the business pass, which includes both the business challenge and the people processes - understanding what roles there are and what actions the people need to be able to take. And then there is the technical pass which is mapping all these needs and procedures to a technical solution.

We mapped that to technical requirements like this…

Establish CI/CD pipeline:

- Single source repo per product; git-flow as branching model.
- Automate build, self-testing, rapid. 
- Automate deployment.
- Setup robust monitoring, logging and alerting for visibility.

Promote team culture:

- Test Driven Development.
- Push often, address broken builds immediately.
- Transparency.
- Change management / Release process.

To push to production on demand, we needed to analyze the development process. We figured out that a single source repo made the most sense for the whole team. We decided to go with git-flow as a branching model instead of other kinds of development. We automated the build process. But also we made sure that the builds were self-testing using SALT test coverage. And we measured the build process and made sure that it was rapid. We also automated the deployment of the solution software. Couple this automation with monitoring, logging, and alerting, and you get a nice build-and-deploy system that can be handed off to a team.

But that doesn't solve the entire problem. The system has to be used. And this team was not going to be accustomed to using the development paradigm we had implemented. So we also needed to do was enhance their processes. This primarily had to do with how test and development worked together. In the new paradigm they would start writing the testing along with development. The new way was to push to production often and push early, and as soon as something break -- fix it. This meant a new team culture, one of accountability and transparency. Where all the stakeholders could participate in identifying and resolving a problem. And that meant change management and leadership buy-in was necessary for the technical solution to be successful.

And this is how we implemented that technical requirement.

- Cloud Source Repositories - for hosting their repositories
- Container Builder - that builds the docker container images
- Container Registry - that hosts those container images
- Google Kubernetes Engine + Helm - for running and managing
- Spinnaker - for CDP - continuous deliver
- Cloud Load Balancing, Stackdriver, Cloud IAM + Service Accounts - management constructs for proper visibility

## Preparing for Analyzing Processes

There are a number of items to review on this slide. Two of them are related and important for you to know. The first is the concept of an error budget. Some companies arbitrarily make a goal of 100 percent like 100 percent up-time but that isn't realistic. We exist in a quantum mechanical universe where random events happen. So, 100 percent isn't really physically possible most of the time. So, at Google, we understand that some amount of time will be spent in error. What we do is identify and manage that time. So, if you have 99 percent up-time, then you have an error budget of one percent. If you find that you've not used all one percent of the error budget during that period, then it's time to do some things that are potentially disruptive. That leads me to a second point and that is about backup and disaster recovery. We often say people don't care about backup, they care about restore. But how do you know that the restore processes are working if you don't try them? If you did a backup last year and you've been consistently generating backups since that time, what are the chances the restore process will work? That's a good thing to do with that extra error budget. It's handy to have a testing checklist in mind to help you consider all options. Consider the questions you're trying to answer with testing. Will the solution support the number of users? Will it handle peak traffic? Is latency acceptable? And so forth. The test environment should resemble production as closely as possible. If you can, test on a part of the production service during a low-use time such as at night. That's called a Dark Launch. If you can't do that, test in pre-production using a synthetic workload that closely resembles a real workload. The results could be misleading if the workload is not designed well. The pricing calculator is very handy for comparing different configurations and identifying cost-effective alternatives. The pricing calculator can be used with BigQuery to estimate the cost of a query before you submit it. The basic advice for optimizing VM cost is use the right size VM and the right resources, customize if necessary. You can use what-if scenarios to see how changing the design can influence cost. For example, which is more cost effective, four machines with eight CPUs or eight machines with four CPUs or 32 machines with one CPU? The GCP console gives you price estimates in the interface when you're configuring the instance. Preemptible VMs can be a great way to scale out. The important thing to remember is that the application has to be designed to handle the loss of any of the preemptible workers at any time. There are committed use discounts and sustained use discounts. Sustained use is when you use the same kind of instances in the same location, and an automatic discount kicks in. Committed use discounts is where you reserve resources and commit to using them in advance at a discounted rate. Discounting algorithms are subject to change. Please see current discounting details in the online documentation. Optimizing disk cost has to do with two factors, size and performance. If you over-allocate disk, you'll be paying for storage capacity that you're not using. It's a much better idea to offload data to cloud storage so you're paying for what you use, rather than holding disk capacity that might not be used. Disk performance can be complicated but there are four factors to consider. The frequency of reads, the size of reads, the frequency of rights, and the size of rights. Generally, smaller more frequent reads and writes are less performance than longer and less frequent ones. Remember that read and write performance are usually not symmetric. Also, consider using a cash if the usage pattern involves a lot of repeated reads. Egress is free, networking cost are similar per GCP product but are build per product. So, you need to view the pricing documentation per product for the details. Example, cloud storage has standard egress cost but there are also separate charges for data migration and for cloud storage operations. Here's an example, egress between regions might be one cent per gigabyte, egress to the internet. The first terabyte to the world destinations might be 12 cents per gigabyte. For the example, I wouldn't expect to know the exact cost of egress from zone to zone or zone to Internet. But I would anticipate the need to know what activities are charged and generally, which actions are more or less expensive than other actions. For example, in a disaster recovery scenario, you'd want to recognize that the improved isolation of storing data in a separate region will be more expensive than just storing the data in a different zone in the same region.

### Analyzing and defining business processes

Analyzing and defining business processes is covered in our design and process courses. Let's expand on a couple of these issues. In the change management outline item, there's a tip that says, quality is a process not a product. As a working cloud architect, you'll almost never have a job where you design and implement the technical solution and then you're done. Instead, you'll be required to stay on the project for a period after implementation and launch, to make sure that solution continues to run and stabilizes. Anticipating that, you'll want to develop process checks, and operational knobs to ensure that the solution can be monitored and adjusted during the stabilization period. So, the business processes might look like generating reports, and it might include weekly or monthly meetings to analyze the reports. It might include procedures that explains to administrators how to take action. Another item is customer success management. Only in the past few years has customer success been broken out from support. The difference is that support is there to make sure a solution continues to operate as it was designed and built. But what if the business circumstances change, or the technology changes, and the current solution is starting to drift off from the actual business needs? Customer success is about making sure that the solution continues to evolve, and remains effective and efficient for the current requirements, and uses the latest and most efficient technologies and methods. If you can exchange a server oriented architecture for a serverless service, you no longer have to be concerned about instance overhead, just the SLAs of the service. There are different hardware, CPU architecture supported in different zones. For example Sandy Bridge Aswell, Broad Well, Ivy Bridge, Skylight and so forth. There are a lot of benchmark comparisons online, and there open source CPU measurement tools that you can use. It suggested that you test your application and workload in different zones to see what differences the hardware in the zone might make. There are new persistent disk features and options released periodically. So, check the documentation online for the latest figures and details. People often assume that a persistent disk is just a hard disk, when it has different features and capabilities. Consider potential I/O burst, if you've planned on I/O based on an average, and the actual disk usage is bursty, the disk could be under provision for dealing with the bursts. Persistent disk performance scales with the size of the disk. So, if you trade up to a larger disk in your design, revisit the performance to avoid overcapacity. If you trade disk size down, check for under capacity. Potential I/Os may be constrained by CPU. An n1-standard-4 can drive a PD-SSD at capacity, and an n1-standard-16 can drive a local SSD at capacity. There are open source disk measurement tools available, and it's recommended that you run tests on your application at various sizes of data and loads, to understand not just capacity, but how the solution handle stress and overload conditions. In general, internal IPs are faster than external IPs. Even VM to VM in the same zone over external IPs can be about one gigabit per second versus 8.5 gigabits per second for internal IPs. Here's another tip. Does a default instance in Google Compute Engine know the difference between an internal and an external IP? No, it doesn't. Standard instances have one interface, and all traffic arrives on that interface. So, that means that external IP isn't added to the hardware interface to the local IP. For sizing network capacity, consider potential I/O burst. If you've planned on I/Os based on an average, and the actual traffic is bursty, it could be underprovision. Network capacity scales with the number of cores. So, if you change out the number of cores and the VM's in your design, revisit the network capacity to make sure the design does not over or under provision. What are some of the factors you should consider when estimating workload? Most common of course are the characteristics of communication and messaging, how often a request or transactions or operations performed, and how big is the payload of the request. Other factors include state changes and methods that divide work into parts, such as sharding, distributing work to multiple workers, such as pipelines, or aggregate work for efficiency, such as batching.

### Developing procedures to test resilience

In this section, we'll discuss developing testing procedures. You can't test everything, so you need to consider what items can act as indicators. How do you prove that the solution is working properly? How do you know if the solution is highly available or scalable? This design illustrates that in some cases, technical design is not sufficient, but must be followed up with human procedures. The original design was intended to handle a maximum of 1000 queries per second. It was originally a functional design. However, over time, the load has grown. While the system is still operational, if one of the front end servers were to fail and the combined traffic was taken up by the other front end, the total would be 1,200 queries per second, and would be above capacity. For this reason, resiliency requires identifying key metrics, in this case total load, and periodically adjusting capacity to stay ahead of growth. On the other side, if load were diminishing consistently over time, there could be cost savings in downsizing the front end servers. A common misunderstanding is forgetting that auto-scaling follows the law of diminishing returns. Imagine that you're considering the target CPU utilization for the entire group of VMs, the percentage utilization that an additional VM contributes depends on the size of the group. The fourth VM added to a group offers 25 percent increase in capacity to the group. The tenth VM attitude group only offers 10 percent more capacity, even though the VMs are the same size. In this example, removing one VM doesn't get close enough to the target of 75 percent. Removing a second VM would exceed the target. The auto-scaler behaves conservatively, so it will shut down one VM rather than two VMs. It would prefer under utilization over running out of resource when it's needed. Now, here's a tip. Consider using Stackdriver custom metrics for auto-scaling. The reason is that CPU utilization is rarely a good measure of customer experience. A custom metric can enable auto-scaling on a more meaningful value. For example, a game service might scale with the number of players, which might be more directly related to application performance than something like CPU utilization.

### Practice Exam Questions 4

Which of Dress4Win's requirements will Stackdriver dashboards, metrics, and reporting satisfy? Improve security by defining and adhering to a set of security and identity and access management IAM best practices for cloud. Encrypt data on the wire and at rest. Analyze and optimize architecture for performance in the cloud, or support multiple VPN connections between the production data center and cloud environment. C is the correct answer. Analyze and optimize architecture for performance in the cloud. Stackdriver metrics will help to analyze and optimize performance for the cloud, because it can be used to gather metrics and custom metrics if needed, to get to specific behavior the applications being migrated. Stackdriver does not necessarily improve security. How can a company connect cloud applications to an Oracle database in its datacenter to meet its business requirement of up to 10 gigabytes of transactions with an SLA? Implement a high-throughput cloud VPN connection. Cloud Router with VPN. Dedicated interconnect. Or partner interconnect. The correct answer is D, partner interconnect. Partner interconnect is good up to 10 gigabits per second and provides an SLA. To differentiate the options, consider their support for speed and volume of data. Cloud VPN is useful for low volume connections. Partner interconnect is useful for data up to 10 gigabits per second. Direct Interconnect is useful for data from 10 gigabits per second to 80 gigabits per second. The Cloud VPN SLA covers the availability of the VPN service not the availability of the public internet. Business Internet Service Level Agreements, SLAs from ISPs are commonly between 99 percent and 99.5 percent for a dedicated line. Therefore even though the Cloud VPN services available at 99.9 percent of the time, the communication it relies on will be down between one half percent, and one percent of the time. That doesn't meet availability requirements.

### Case Study 5

This case involves Finserv, which is how people in the industry refer to financial services. There are two industries where security comes up as a priority in nearly every transaction. Can you guess them? Financial services is one because the transactions involved are both private and involve the exchange of value. The other is the healthcare industry, where a lot of the information is what they call PII or personally identifiable information. Let's see how security is handled in this financial services example. A lot of customers we see are in the enterprise space, so their needs are very similar. This example comes from a financial services company. We often see similar requirements among Finserv companies. So, a Finserv customer had this interesting business requirement. Encryption in transit and at rest for all developer operations. Follow Google Best Practices. All keys must be managed by the company. They wanted to own the keys. The real trick here is that the structure and solution had to be put into production at one time. It couldn't be built-in parts into production, it had to be all working when it went into production. That caused us to think about what parts were inherent and what parts we could automate. So, we ended up using a Jenkins Pipeline and Deployment Manager Templates for parts of this automation. We mapped that to technical requirements like this. Use Google authentication. No public IP access unless through a bastion host. No Operations team access to production environment, that means NoOps. Everything is automated. Minimize downloaded keys. Keys accounted for via business logic application. All the Google APIs are encrypted in transit and authenticated. So, that requirement was inherited and automatic. The production team needed operations access but without handing them the keys. So, what we did is implemented all operations in deployment pipelines using Jenkins and Deployment Manager. The business logic was implemented using Python in the Deployment Manager Templates. This is how we implemented that technical requirement. All Google APIs are encrypted in transit and authenticated. Production has Operations team access. All deployment pipelines via Jenkins and Deployment Manager business logic and Python templates and Deployment Manager. CloudSDK was not installed in local machines. Cloud Shell ensures that no keys are downloaded. Service Account Keys when needed for off-GCP clients are managed via deployment pipelines. There are two kinds of operations actions: on-GCP actions and off-GCP actions. For on-GCP actions, we didn't install CloudSDK on local machines. Instead, we set them up to use Cloud Shell, that ensured that no keys were downloaded. For off-GCP actions, the Service Account Keys were managed via the deployment pipelines. Anytime there was a need for off-GCP access, the clients are managed via the deployment pipeline. So, that means there's a full audit control and records of those keys, and who had access to them, and when and where they were used.

Case Study 5
Case 05: Managing Implementation

A lot of the customers we see are in the Enterprise space, so their needs are very similar. This example came from a Financial Services company. We often see similar requirements among FinServ companies.

A Finserv customer had this interesting business requirement...

Encryption in transit and at rest for all developer operations
Follows Google Best Practices
All Keys must be managed by Company - they wanted to own the keys
The real trick here is that the structure and solution had to be put into production at one time. It couldn't be built in parts into production. It had to be all working when it went into production. That caused us to think about what parts were inherent, and what parts we could automate. So we ended up using a Jenkins pipeline and Deployment Manager templates for parts of this automation.

We mapped that to technical requirements like this…

Use Google Authentication.
No Public IP access unless through bastion host.
No Operations team access to production environment. That means "no ops" - everything is automated.
Minimize downloaded keys.
Keys accounted for via business logic application.
All of the Google APIs are encrypted in transit, and authenticated. So that requirement was inherited and automatic. The production team needed operations access but without handing them keys. So what we did is implemented all operations in deployment pipelines using Jenkins and Deployment Manager. The business logic was implemented using python in the Deployment Manager templates. 

And this is how we implemented that technical requirement.

All Google APIs are encrypted in transit, and authenticated.
Production has operations team access - all deployment pipelines via Jenkins and Deployment Manager.  Business Logic in python templates in Deployment Manager.
CloudSDK was not installed in local machines - Cloud Shell ensures no keys are downloaded.
Service Account keys when needed for off-GCP clients are managed via deployment pipelines.
There are two kinds of operations actions; on-GCP actions and off-GCP actions. For on-GCP actions, we didn't install Cloud SDK on local machines. Instead, we set them up to use Cloud Shell. That ensured that no keys were downloaded. For off-GCP actions,the Service Account keys were managed via the deployment pipelines. Any time there was a need for off-GCP access, the clients are managed via the deployment pipelines. So that means there is full audit, control, and records of those keys, who had access to them, and when and where they were used.

## Preparing for Advising

### Advising development operation teams

Most of the items in the exam outline have been covered already in another context.
The first rule of testing is that you can't test everything so you need to make some decisions. Unit testing focuses on individual functional units, for example, exercising an API. In some development environments, it's common for the original software developer to provide a testing application that exercises the API and validates that it's working as expected. Integration testing has to do with putting parts together and testing them as an assembly. Sometimes the individual parts can pass unit test because each is working as designed, but when the units are assembled they may not be compatible. You can also discover timing issues called race conditions during integration testing. One good piece of advice is to create a launch checklist. In this example, there are dependencies, capacities, single points of failure, security and access, and a phased roll out plan. With all those items to be checked and some of them being very complex, it's easy to see the value of using an organized approach to ensuring that everything's ready. General advice about release management? Well, automate everything you can. Also, instead of creating a process with a resource bottleneck which can slow down release, consider implementing a self-service approach. Let the lead developers or the product managers perform the release using the tools. Reliability and consistency are the keys to making release work well. Also, implement access control over critical release features and processes. For example, a team lead or a tech lead might be a member of the release group, and have special access.
When we think about capacity planning for launch, it's common to create a moon shot event where everything has to come together perfectly at a single moment for the launch to succeed. Consider instead using a phased approach, by launching first to a smaller market. The service can generate feedback and even warn of issues that might not scale in subsequent phases.
A classic example of this was when the first Pokemon Go game was launched. It was launched first in Japan. The game was so popular that it had scaling issues because the demand was much greater than the anticipated demand for which the service was designed. Fortunately, launches in Europe, the US and other locations were separated by a few days. Staging the launch gave the team the time needed to understand the scaling issue and redesign and reimplement the service before its second launch. I'm pretty sure you know this already. There are three ways to interact with Google Cloud, first is GCP Console. Second is the tiny virtual machine that's started up inside Console called Cloud Shell. One thing that makes Cloud Shell useful is it's authorized in the project, and it has the Cloud SDK tools including gcloud, gsutil and bq installed. You can also install the Cloud SDK outside of Google Cloud on a local computer or VM.

### Practice Exam Questions 5

Implement back-out/rollback for website with hundreds of VMs. Site has frequent critical updates. Create a nearline copy of static data in Cloud Storage. Create a snapshot of each VM prior to update in case of failure. Use managed instance groups with the "rolling-action start update" command when starting a rolling update. Only deploy changes using Deployment Manager templates. The correct answer is C. Use managed instance groups with the "rolling-action start update" command when starting a rolling update. Allows compute engine to handle updates, easy management of VMs. Website with hundreds of VMs, load-balanced likely already using a managed instance group. Now here's a tip. Did you know about this command? This is an example of the level of detail you should be familiar with. If you had studied managed instance groups features, you would have at least seen the "rolling-action start update" option and recognized it in the question. Nearline copy would have been unreliable because once the copy has overwritten, you can't roll it back. Creating VM snapshots could work but it's not an efficient way to backup big data. Also the bigger the data the longer the backup takes which could impact production. Using Deployment Manager templates runs the risk of version conflicts. So, managed instance group features are most efficient for this situation. A car reservation system has long-running transactions, which one of the following deployment methods should be avoided? Execute canary releases, perform AB testing prior to release, introduce a blue-green deployment model, introduce a pipeline deployment model. The answer is introduce a blue-green deployment model. Switching the load balancer from pointing at the green, good environment to the blue new environment is a fast way to roll back if there's a problem during a release. However, long-running transactions would be disrupted by that switch. This question requires you to know a little about AB testing and a little about blue-green deployments and a little about canary releases. They're covered lightly in our courses but it would be advisable to study these separately since they are not Google specific methods. The second link discusses long-running connections and how to support them.

## Preparing for Reliability

### Ensuring solution and operations reliability

Ensuring solution and operations reliability. How do you ensure that a solution is reliable? Part of it occurs in the design. Making sure that common changes like increased traffic are handled in elastic ways. However, part of it is also in planning to monitor the service and to notice and respond to unplanned events. Some of those activities require human intelligence. For this reason, operations reliability spans both the technical and the procedural domains. Site reliability or SRE, is Google's approach to DevOps. It's a very comprehensive system that involves changing the culture about how maintenance occurs. One central idea is the division of aspects of operations into separate layers for clarity. Here's a tip, you ought to know something about each of these layers and most importantly, you should be able to distinguish between the layers. For example, monitoring is not incident response. They're related. Do you know what features relates them? It's alerts. A Stackdriver alert is triggered by monitoring and begins incident response, which is composed mainly of procedures. Qualities are often where our goals start, but figuring out how to measure them quantitatively enables data-driven operations. It can be difficult to figure out exactly what to measure because sometimes what's easily measured is not a good indicator of customer interests. Speaking of alerts, at Google, we have the concept of alerting for the right reason. Often, alerts are designed to signify some metric passing some limit. But the question is whether that metric or trigger is something the customer cares about or not. We need to alert on some technical measures. But if there's something that is directly causing the customer frustration and upset, that should also be an alert or perhaps replace a more technical alert. Make sure you know the difference between blackbox monitoring and whitebox monitoring. Blackbox monitoring and whitebox monitoring are frequently misunderstood. In the cloud architect contexts, the difference has to do with the assumptions you can make when designing your monitoring framework. In blackbox monitoring, you're not supposed to know or think about the inner workings of the application. All you can see is the user interface or the API interface. So, the only assumptions you're allowed to make have to do with these interactions. Blackbox monitoring is very good for validating user experience. You end up monitoring things like latency between request and response. In whitebox monitoring, the application is assumed to be known to you. The inner workings of the application are transparent. So, you can use that special knowledge when defining the test. A good example would be if you knew that under certain conditions a critical resource will get oversubscribed and you've designed the system from resiliency. In this case, you might flood the interface to trigger the state as if the service was under attack to see if the resiliency worked as expected. That's whitebox monitoring, where the tests can be focused on inner workings and not just the UI. In practice of course, you need both kinds. Here's an example, CPU utilization may or may not indicate user satisfaction. Round-trip delay or frequency of request errors might be a better measure of the user's experience. What metrics are you using? Can you define metrics that relate directly to user experience and service objectives? What are the watermarks or alert levels at which human processes are engaged? How are you setting those values? When do they need to be revisited and updated? How do you know they're related to important events? Know how to use trace and debug. Examples of other tools that Stackdriver replaces. Note that it's not just a collection of alternate tools that's the issue, but how you use them together. The individual tools are not integrated or designed to work together. So, a lot of manual procedures and translation massaging of data are required to use them together. With Stackdriver, the integration is by design. So, that work disappears. Stackdriver is also multi-cloud, able to manage projects across GCP and AWS. Another useful idea is that people don't plan to fail, they fail to plan. Another way of saying this is, the only time we have to prepare for emergencies is before they happen. Once the emergency is occurring, it's too late to prepare. You can design a great technical solution, but if it doesn't include human processes, then it might not be adaptive and resilient. Easy buttons are tools and processes that automate common actions. A playbook is a list of what to do when. So, here's a general rule; for every alert you should have a play in the playbook. What are the differences between a dashboard, an alert, and incident response? A dashboard is a display for monitoring a system. It's commonly tailored to the application. An alert occurs when a condition is met such as a metric crossing above a particular value for a given duration. The alert is the notification and alert could just be a warning or it could be a notification of an incident that needs to be handled immediately. Incident response consists of the steps you would take when a problem occurs. This might be written up in a playbook. Find a lab such as Quick Labs lab that uses logging and trace and debug to identify and solve an application problem. This will give you a sense of the value and how these components work together. There's a lab like this in the architect in GCP infrastructure class. Google's approach focuses on transparency, on involving the customer in the solution and blamelessness. Assigning blame establishes root cause with a person or an organization instead of getting to the real technical or procedural issue so that it can be fixed. If blame has been assigned, there's a high likelihood that the process has been prematurely suspended without really addressing the problem. What are the people supposed to do? What decisions or actions are they supposed to make or take? Are these documented? As mentioned, the metrics are not sufficient without the meeting to review the metrics, to evaluate them and make decisions and take actions. In those cases where timing is critical, you'll want to playbook and easy buttons supporting automation to increase the speed and consistency of incident response. Here's another tip, when something goes wrong with the cloud resource, give yourself or your team a limited period of time to solve it. For example, if a VM starts behaving incorrectly, see if it's something that's easily fixed. Then spare the VM to the side and replace it. Perform your diagnostics and debugging after the instance is replaced.

### Case Study 6

A customer had this interesting business requirement. The back office system needs to support frequent updates. The back office system needs to be available especially between 6:00 AM and 06:00 PM. A failure in one part of the back office system shouldn't bring down the entire system, and the customer wants to re-architect the system. They don't want to bring down the entire system when doing an update. So, we map that to technical requirements like this. Microservices, break apart the back office system into independent services, create a standard way for teams to publish logs and metrics for their services, and create a standard way for services to be rolled out. This use case was a natural fit for microservices. They knew that when they told development groups that they would be developing their own microservices, that they needed standards for reliability and scalability, and that they want common ways to monitor the applications. This is how we implemented that technical requirement. Google Kubernetes Engine, microservices deployed into a shared cluster. Surging rolling deployments with Kubernetes deployment resource, and Stackdriver, custom metrics, a wrapper library around Stackdriver client libraries and that enabled us to expose common metrics, and expose custom metrics. So, the solution was to use Stackdriver exposing the metrics that could be done through dashboards, exposed metrics through Prometheus standards scraped from API's and sent to Stackdriver, where it could be exposed through the dashboards. They use custom metrics and Stackdriver, so they were able to monitor and scale their microservices based on those metrics.

Case Study 6
Case: 06 Solution and Operations Reliability

A customer had this interesting business requirement...

The back-office system needs to support frequent updates
The back-office system needs to be available - especially between 06:00 CEST and 18:00 CEST
A failure in one part of the back-office system shouldn’t bring down the entire system
Customer wants to re-architect system. Does not want to bring down the entire system when doing an update.
We mapped that to technical requirements like this…

Microservices!

Break apart the back-office system into independent services
Create a standard way for teams to publish logs and metrics for their services
Create a standard way for services to be rolled out
This was a natural fit for microservices. They knew that when they told development groups that they would be developing their own microservices, that they needed standards for reliability and scalability, and they want common ways to monitor the applications.

And this is how we implemented that technical requirement.

Google Kubernetes Engine

Microservices deployed into a shared cluster
Surging Rolling Deployments with K8s deployment resource
Stackdriver

Custom Metrics - a wrapper library around the Stackdriver client libraries to: 
Expose “common” metrics
Expose custom metrics
Solution was to use Stackdriver. Exposing the metrics could be done through dashboards. Exposed metrics through prometheus standard, scraped from APIs, and sent to Stackdriver where it could be exposed through dashboards. 

They used custom metrics in Stackdriver, so they were able to monitor and scale their microservices based on those metrics.

### Practice Exam Questions 6

 microservice has intermittent problems that bursts logs. How can you trap it for live debugging?
Log into machine with microservice and wait for the log messages. Look for error in Stackdriver Error Reporting dashboard. Configure microservice to send traces to Stackdriver Trace. Set a log metric in Stackdriver logging, alert on it past a threshold. D is the correct answer. Set a log metric in Stackdriver logging, and alert on it past a threshold. A Stackdriver metric can identify a burst of log lines. You can set an alert, then connect to the machine while the problem is happening. What's your tip from this? You should be familiar with basic Stackdriver features and operations. With distributed and scalable services, you need to debug from logs and centralized monitoring services. Error reporting is an instance whereas the a log is a history so you can see issues in context of time. Likewise, trace is a sampling system, so it might miss intermittent issues like this. Again, the tip here is to understand the differences and appropriate uses for the tools in Stack Driver. Last week a region had a 1% failure rate in web tier VMs. How should you respond?
Monitor the application for a 5% failure rate. Duplicate the application on prem to compensate for failures in the cloud.
Perform a root cause analysis, reviewing cloud provider and deployment details to prevent similar future failures. Halt all development until the application issue can be found and fixed. C is the correct answer.

## Challenge Lab

This is not a technical training course
Don't expect to be taught the touchstone concepts here. The purpose of them in this course is to help you evaluate your preparedness. Seek training in the technical training courses, documentation, labs, and so forth.

Practice the case evaluation method on cases and on sample questions
Business Requirements
Technical Requirements
Technical Watchpoints (requirements or facts that indicate elements of a solution)
Proposed Solution
This is not just a test-taking skill. This is a skill used in practice by consultants on the job. It is how they think about their customer engagements and talk about it with other professionals.

What questions would you want to ask a client?
You can make reasonable assumptions about a case. But if you seem to be missing information, especially technical information, that may be useful. It may help constrain the degree of freedom and limit the number of potentially correct answers. It might indicate that an answer is incorrect. In other words, use what you don't know or what is missing in the case to help you evaluate the intent of the question. 

Make sure you know what is being asked.
If you find yourself speculating and trying to add information to the case beyond reasonable assumptions, then you might be drifting off of the intent of the question. 

Hands-on
It is a good idea to review and run through basic labs so that the hands-on details are fresh in mind. You might want to review steps of labs you performed before. Or you might want to do some of them again.

## Resources and next steps

In this module, we'll discuss next steps. This course exposed you to a lot of information. There were many elements designed to help you approach preparing for the exam in different ways. First, we described the certification and the exam itself. You were encouraged to adopt an iterative strategy of answering the questions you're most confident about first, and bookmarking the others and revisiting them. You also learn that the exam is designed to test practitioners who do the job. It isn't about only knowing certain information or details, it's about being able to reason through cases and make reasoned decisions. The majority of this course followed the exam guide outline, and we explored each of the parts of the exam, the concepts behind them, and map these two important information to know about the technology that's taught in the architecting infrastructure courses. Every section of the exam guide was summarized with the blue table that identify the outline subjects and gave you helpful tips to consider. This wasn't a cram session. We're not trying to cover every detail or to build your knowledge from the ground up. In fact, the goal was to remind you of higher-level important concepts that you ought to know and understand, knowledge you probably gained from attending other courses or from your experience. The idea is, if you understand these touchstone concepts, you'll also need to know all the dependent basic information that they depend on and the reasoning behind them. You can still use a bottom-up mastery approach to help prepare for the exam if you like, the two approaches are not mutually exclusive. You got to practice answering sample exam questions, and we shared some actual case studies with you that were from real cloud architects explaining how they use the skills on the job. You now have a pretty good sense of the exam and how to prepare for it. You've been exposed to information that will help you decide what to study and how to prepare. Next, you'll be given an opportunity to practice answering sample exam questions and finally, a list of resources for further study and preparation.

Review of tips
TIP 1: Create your own custom preparation plan using the resources in this course.

TIP 2: Use the Exam Guide outline to help identify what to study.

TIP 3: Product and technology knowledge.

TIP 4: This course has touchstone concepts for self-evaluation, not technical training. Seek training if needed.

TIP 5: Problem solving is the key skill.

TIP 6: Practice evaluating your confidence in your answers.

TIP 7: Practice case evaluation and creating proposed solutions.

Tip 8: Use what you know and what you don't know to identify correct and incorrect answers.

Tip 9: Review or rehearse labs to refresh your experience

Tip 10: Prepare!