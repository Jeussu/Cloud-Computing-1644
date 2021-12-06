# Cloud-Computing-1644
I. 	Introduction: 
as a developer of a toy company in Vietnam called ATN. In this report, I will introduce to the board director about a method that can solve the problem of data collection and storage from stores for the company and that is cloud computing. cloud, then I present and introduce deployment models and service models, and talk through virtual computing, virtualization and the properties of cloud computing. 
	II. 	Fundamentals of cloud computing 
1. Definition 
Cloud computing is an IT delivery model based on virtualization, where one or more service providers manage resources in terms of infrastructure, software, and data via the Internet as a distributed service. Such programs are on-demand elastic and are printable on a payper-use basis.  (Armbrust et al, 2009) 
2. Cloud computing in the Evolution of computing Paradigm 
a. Server/client networking Paradigm 
The Client-server model is a distributed application system that divides task or workload between resource or service providers, called servers, and service requestors called clients. Client-server model examples include email, the World Wide Web, etc.  (David Reilly, Michael Reilly, 2019) 
![image](https://user-images.githubusercontent.com/94780400/144860192-bc5a6e97-5c11-40c8-ab12-710fd001c099.png)
Fig 1: The Client-Server Computing Paradigm 
b. High-performance computing (HPC) 
High-performance computing (HPC) is the ability to process data at high speeds and to perform complex calculations. 
![image](https://user-images.githubusercontent.com/94780400/144860217-036443a7-b081-459a-bee7-6147a06aa172.png)
Figure 2: HPC 
Cluster computing paradigm 
A cluster computing system consists of a collection of processor machines of the same or similar type, linked through the dedicated network infrastructure. It is also more of a type of HPC. The individual nodes can work together to solve a problem that is bigger than any machine can solve easily 
![image](https://user-images.githubusercontent.com/94780400/144860262-e3ab6b62-e1b6-4554-ab83-49cc6c6ee190.png)
Figure 3: What is cluster computing? 
Peer-to-Peer Computing paradigm: 
Stands for "peer to peer." The "peers" are computer systems in a P2P network that are connected to each other via the Internet. Files can be shared directly between networked systems without the need for a central server. To put it another way, each computer on a P2P network becomes both a file server and a client.  
![image](https://user-images.githubusercontent.com/94780400/144860289-f8161832-99e2-4be5-967e-848f661fb487.png)
•	Benefits of P2P: 
-	No need for dedicated application and database servers  - 	Improved scalability and reliability (no single point of failure)  
•	Shortcomings of P2P:  
-	Poor security  
-	Lack of centralized control 
-	Computers with shared resources may suffer from sluggish performance  
P2P networking allows easily to share and download copyrighted files  
•	Parallel computing: Parallel computing is a facet of HPC, too. It is run using multiple (multiple CPU) processors. A problem is divided into discrete parts that can be overcome at the same time. Further, each element is broken down into a series of instructions. Instructions for each part are executed on different processors simultaneously. An overall mechanism of control / coordination is used 
•	Distributed computing: Distributed computing is also a computer system consisting of multiple computers or processor machines connected via a network that can be homogeneous or heterogeneous, but function as a single system 
•	Grid Computing: Grid computing is a network of computing machines or processors operated with software like middleware to remotely access and use the resources. 
 
 
 
 
 
Cloud computing  
Cloud computing in the simplest terms involves storing and accessing data and programs over the Internet from a remote location or device, rather than the hard drive of our computer. The cloud is essentially a Web metaphor. Cloud computing can be done anywhere, anytime, and from any device with an online connection.  
Principal characteristics: 
For most cloud environments, the following five basic characteristics are common: 
•	On-demand self-service 
•	Broad network access 
•	Elastic resource pooling 
•	Rapid elasticity 
•	Measured service 
-	On-demand self-service: A consumer can automatically provide computing capabilities unilaterally, such as server time and network storage, as required without requiring human interaction with the provider of each service. 
for example, the consumer’s request is then automatically processed by the cloud infrastructure, without human intervention on the provider’s side. 
-	Broad network access: Wide network access refers to services housed in a private cloud network (operated within a company's firewall) that can be accessed from a wide variety of devices, such as laptops, PCs, Macs and smartphones. Elastic resource pooling 
-	Rapid elasticity: Capabilities can be easily and elastically given, in some cases automatically, to be rapidly scale-up and quickly released in 
For example: Let's say we're stores for eCommerce. At Christmas time, we will probably be getting higher seasonal demand. If we use cloud computing we can spin up new servers automatically as our demand increases. 
-	Elastic resource pooling: The computing resources of the company are pooled using a multitenant model to serve multiple consumers 
Example: It's similar to people living in an apartment building, sharing the same building infrastructure, but within that infrastructure, they also have their own apartments and privacy. 
-	Measured service: Cloud systems control and optimize the use of resources automatically by leveraging a metering capability at some level of abstraction appropriate to the type of service  
(Thomas Erl, Zaigham Mahmood, and Ricardo Puttini, 2006) 
(for example, Save, process, bandwidth, and active user accounts,). 
c. Deployment Models 
A cloud deployment model reflects a particular kind of cloud environment, characterized primarily by ownership, scale, and access. 
There are four common cloud deployment models:  
•	Public cloud 
•	Community cloud 
•	Private cloud  
•	Hybrid cloud the following sections describe each. 
- Public cloud: The cloud technology is provided to the general public for open use. It may be owned, managed, and operated by, or some combination of, a corporation, academic, or government agency. It occurs at cloud provider premises 
![image](https://user-images.githubusercontent.com/94780400/144860323-823db716-43df-40cb-afa4-771d4565f7f7.png)
Figure 1.3: Organizations act as cloud consumers when accessing cloud services and IT resources made available by different cloud providers. Microsoft Azure is an example of a public cloud.  
Advantages  
•	Lower costs – no need to purchase hardware or software, and you only pay for the service you use. 
•	No maintenance – your service provider provides the maintenance. 
•	Near-unlimited scalability – on-demand resources are available to meet your business needs. 
•	High reliability – a vast network of servers ensures against failure. 
Disadvantages: 
•	Lacks proper controls 
•	Performance: The performance of the network depends on the speed of internet connectivity. 
•	Weak on Security 
•	Customization: Customization of resources or services is not possible. 
-	Community cloud: Community Cloud: Many entities share the cloud infrastructure and support a particular community that has shared concerns. It can be operated by companies or third parties and can operate on-site or off-site  
Example: The program, which is available on one set of cloud servers, is needed by organizations. Thus, the company that allows multiple servers will not provide a specific server in the cloud. But they will allow multiple customers to link and segment their sessions into the cloud. It simply means that servers use the same application which makes it a community cloud. 
Advantages: 
•	Flexibility and Scalability 
•	Available and Reliable 
•	Secure and Compliance 
•	Improved Services 
Disadvantages: 
•	Not the right choice for every organization 
•	Slow adoption to date 
Like the private cloud solution, the community cloud has areas where it can greatly benefit agencies, but it’s also not the right solution in all circumstances. 
-	Private cloud: A single organization comprising multiple consumers provides the cloud infrastructure for exclusive use. It may be owned, managed and operated by, or some combination of, the organization, a third party, and may exist on or off-premises 
-	Examples of private cloud deployment can be found easily in fields such as banking and financial services, large corporate organizations, government organizations, etc. where only registered users can access the network. 
Advantages: 
•	Increased isolated Network security.  
•	Improved efficiency due to the mere commitment of resources to one organization.  
•	Enhanced customization capability. 
Disadvantages: 
•	Higher cost 
•	Maintenance - Set up and support for private cloud is more expensive and time-consuming than deploying on a public cloud service. 
-	Hybrid Clouds: The cloud infrastructure is a composition of two or more different cloud infrastructures (private, group or public) that remain unique entities but are connected by standardized or proprietary technology that allows portability of data and applications  
-	For instance, you can use the public cloud for high-volume, lower-security needs such as webbased email, and the private cloud (or other on-premises infrastructure) for sensitive, businesscritical operations like financial reporting. 
Advantages: 
•	Scalability (both up and down). Almost unlimited due to on-demand cloud resources. 
•	Lower capital expenditure (capex). You don’t need to purchase all your own data center equipment. 
•	Reliability. Due to services distributed across multiple data centers. 
Disadvantages: 
•	Less control over data security. You never know where—and under what geographic or other restrictions—your data is operating. 
•	Higher operational expenditure (opex). As you scale performance, your cost-per-hour fees rise. 
c. Service Models 
-	Infrastructure-as-a-Service (IaaS): The IaaS delivery model describes a self-contained IT ecosystem consisting of IT services focused on infrastructure that can be accessed and managed through cloud service-based interfaces and tools. Hardware, network, networking, operating systems, and other "real" IT tools can be part of this process. Usually, IT services are virtualized with IaaS, and bundled into packages that simplify up-front runtime scaling and network configuration.  
-	IaaS Examples: Amazon Web Services (AWS), Cisco Metapod, Microsoft Azure, Google Compute 
Engine (GCE), Joyent 
![image](https://user-images.githubusercontent.com/94780400/144860389-f0d85aae-db20-46e6-ba01-0afefa05ea4e.png)
Figure 1.4: Within an IaaS system a cloud user uses a virtual server. The cloud provider provides cloud customers with a variety of contractual commitments, relating to features such as power, performance, and availability. 
-	Platform-as-a-Service (PaaS): Platform as a Service (PaaS) is a way to build and have cloud provider hosting applications. It allows you to deploy software without having to spend the money purchasing the servers to house them on. 
-	Software as a Service: The consumer's ability is to use cloud-based applications, including network, servers, operating systems, storage, and even individual application capabilities, with the possible exception of limited user-specific configuration settings. 
-	SaaS Examples: Google Apps, Salesforce, Workday, Concur, Citrix GoToMeeting, Cisco WebEx 
Infrastructure 
Virtualization: Virtualization is a technology that allows a single physical infrastructure to act as a multiple logical infrastructure or resources 
-	Virtualization is not only hardware-limited but can also take many forms such as memory, processor, I / O, network, OS, data, and application 
-	It helps to improve scalability and resource utilization of the underlying infrastructure.  
-	It also enables the IT personnel to perform the administration task easier 
Network Virtualization: Cloud computing network virtualization is a method of combining the available resources in a network by dividing the available bandwidth into different channels, each being separate and distinguishable. Such as your segmented hard drive, you can handle files more effectively. 
-	Virtual LAN (VLAN), is one example of network virtualization. A VLAN is a subsection of a local area network (LAN) created with software that, irrespective of physical location, combines network devices into one community. 
-	Application Virtualization: Application virtualization helps the user get remote access from a server to an application. The server stores all of the application's personal information and other features, but can still run through the internet on a local workstation. 
-	Example: A user who needs to run two different versions of the same program would be an example of that. Hosted applications and bundled applications are technologies that use application virtualization. 
Network Virtualization: Cloud computing network virtualization is a method of integrating the available resources in a network by separating the available bandwidth into different channels, each being distinct and distinguishable. They can either be allocated to a particular server or computer or remain completely unassigned— all in real-time. The hope is that the system disguises the network's true complexity by splitting it into easy-to-manage bits, much like your segmented hard drive makes file management simpler. 
-	Example: virtual private Network(VPN) 
-	Processor virtualization: Computer virtualization is known as CPU Virtualization. This is where practically any hardware device which can be operated over a virtual machine on a computer by the user or a guest program. This is not just about guest applications but several operating systems as well. The software works with some limitations as though it is the local machine itself. 
-	Example: A computer running Microsoft Windows, for example, may host a virtual machine that looks like a computer running the Ubuntu Linux operating system; Ubuntu-based software can run on the virtual machine; 
-	Memory Virtualization: Virtual memory virtualization parallels the virtual memory support that current operating systems offer. The operating system performs mappings of virtual memory to machine memory in a typical execution environment, using page tables, which is a one-stage mapping from virtual memory to machine memory. 
-	Storage virtualization: When the physical storage is pooled from multiple network devices into a single storage device in appearance to manage the functions centrally, it is called storage virtualization. 
-	Data virtualization: This kind of virtualization methodology for cloud computing abstracts the technical details commonly used in data management, such as venue, output or format, in favor of wider access and more flexibility that are directly related to business needs. 
Proposed solution: 
the reason why ATN should choose cloud computing for the project 
In fact, using cloud computing technology for storage is the most essential solution for ATN company's websites when developing beyond the resources of hosting providers that can share them. 
-	Cost-efficiency: Virtualized resources eliminate the capital expense of procurement and maintenance of equipment, as well as the cost of maintaining a data center on-site: cooling, physical security, janitorial services, etc. 
-	Scalability: Estimating the requirements of data center capacity is one of the most difficult tasks faced by a leading IT toy company. Underestimate your ability to meet business opportunities and you end up crippling them. Cloud computing resources (computing, cloud storage, and network bandwidth) may be scaled up, down, or off to meet ATN company's current needs. Public clouds such as AWS and Azure even offer elastic computing, automatically expanding storage and calculations to meet unpredictable storage requirements. 
-	cloud computing technology that stores data helps ATN company's websites make good use of the server's virtual resources to hold entire private databases to store transactions. for shop 
-	In that case, with common data, overloading resources and being provided from a shared server, we need to use other solutions to store data, store transactions, at this time, cloud computing technology is the perfect storage solution, bringing many advantages to data storage without any challenges. 
-	therefore, cloud computing is applied to ATN toy company to manage and store data to ensure that the company can operate efficiently and stably at any time. 
- Architectural design 
![image](https://user-images.githubusercontent.com/94780400/144860424-8f9f195f-7cd5-4fe7-9519-f93143387cfe.png)
to solve the problem of the toy company ATN asked me and I proposed a more advanced solution, which is to apply cloud computing architecture to the project to store data of each store for company and below is a schematic image of cloud computing architecture describes the user sends a request to the cloud service and thereby optimize the data storage: 
B. Detailed design 
1. Deployment model 
ATN toy company is a big enterprise in Vietnam but because of its new development, the staff and infrastructure are limited, to solve this problem I choose cloud computing in the public model. The benefits of the public model I discussed above, especially this model is very suitable for the project because of its features. 
2.Service model  
This is the toy-selling website I created based on cloud computing, and Paas is the model we choose to manage the website as well as product data, purchase and transaction data of each store. We won't need to worry about other pieces like 0S, Runtime, Database, Space, ... And other Hardware and Engineering related matters. We will be creating this Web Application as a Developer so in this case, the PaaS model is very suitable. 
3. The necessary things: 
- Program Language:  
JavaScript is the most powerful and stable language among the languages, with the popularity of JavaScript it is the right language for the project. The advantages include: We can compile a program through HTML using a web browser without installing the compiler. Simple to understand and easy to read for beginners Can add events on the website and thus benefit the user Get a better experience with the app. It is simpler and lighter than other languages used for programming. 
➢ NodeJS is a JavaScript platform to create web apps. The advantage of using NodeJS for the site is that we can synchronize both the Front-end (JavaScript) and Back-end (NodeJS), the communication between Back-end and Front-end is easily accomplished through moduledeveloped API (Application Programming Interface). Additionally, the NodeJS support community is huge, so it's easy to support fixing bugs or software problems. 
- Web server: Heroku 
Heroku is a cloud platform that allows developers to build, deploy, manage, and extend (PaaS Platform as a service) applications. It is very versatile and user-friendly, offering the best way for users to get goods. It allows developers to concentrate on product development without having to worry about running the server or hardware 
- Database server 
The toy product data is quite versatile and often changes (expanding narrowly) so we'll use a NoSQL database, in this case, we'll use GitHub. The benefits of NOSQL, as well as GitHub, Code Studio include: we don't have the definition of the data relationship in this database so it's quite easy to expand the database. Mapping, assembly, and restrictions between data fields are not necessary the layout of a set is simple and easy to understand, the ability to query deeply, the data is stored as JSON files, so that it can be read easily in many different devices 
	• 	Conclusion 
So, we have understood the basic concepts of cloud computing (5 essential characteristics, 4 deployment models, 3 service models), concepts and forms of virtualization through the report, the first thing based on the current popular computing paradigms. The design of a cloud computing architecture and the selection of specific methods for deploying into the ATN toy company project 
References 
Armbrust et al, 2009. Understanding the concept of cloud computing. Anon ed. Anon: Anon. 
David Reilly, Michael Reilly, 2019. Java Network Programming and Distributed Computing. Anon ed. Anon: 
Anon. 
Thomas Erl, Zaigham Mahmood, and Ricardo Puttini, 2006. Cloud Computing Concepts, Technology & Architecture. Anon ed. Anon: Anon. 
