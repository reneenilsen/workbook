# Q1 - Describe the architecture of a typical Rails application

Rails applications are a popular web development framework and follows the MVC (model, view, and controller) pattern of architecture. Rails also follows the rule of convention over configuration meaning rails has made decisions and you need not worry about these if you follow the Ruby on Rails conventions.

There are 6 basic Ruby on Rails architecture components – Models, Rails server, Routes, Controllers with actions, Views and Assets. 

Models form the core of the business or representation of the business domain. In Ruby on Rails, models offer the methods to transfer the memory-resident state of a model instance into the database. The models don’t form the web app but many things can be achieved in the models. It gives access to the database and can manipulate data through the rails console. 

A rails server is an executable that instantiates a web server. It listens on a port and IP and is used to accept the requests from the browser. The rails server takes requests then delegates the processes to the various components.  

The routes consist of a way to tell what URL path the app understands and then which code should handle the request. Routes are configured inside a routes.rb file. For each of the paths we need to specify the controller and the action to handle the corresponding request. 

Controllers are responsible for handling a request with one of its actions. Each of the controllers are similar to ruby class and the actions are public methods. With the help of the model can get data from the data base or complete calculations. Controllers’ instantiate objects that used in the views. 

Views are responsible for telling rails what content of the HTML is sent to the browser requested. Views rely on the data prepared by the controller. The view also needs a layout, a piece of HTML that the view reads. The layout often has many views. 

Assets are usually JavaScript, CSS or media such as images. 

# Q2 - Identify a database commonly used in web applications (including Rails) and discuss the pros and cons of this database

PostgreSQL is an open source object relational database system. 

## Pros

PostgreSQL database provides transactions. It includes insert, update, delete as well as creating table, drop table and auto tables reducing the client-side library and reducing code written for error handling.

Code comments are a useful feature of PostgreSQL, they help to see what code does or does not do before locking it in for the app. This allows you to understand the design and follow the open engineering process therefore giving security and quality. 

## Cons

As PostgreSQL is mostly used as a relational database it works some assumptions or works in a particular way. These databases works with tables like a data bin therefore the way to query data has a strict requirement to store the data in the database table. The schema is clear in what data can go into a table and what fields. 

PostgreSQL is open source and not owned by an organization, while being feature rich the software does not include any warranty or no liability/indemnity protection while other proprietary software owned by an organizations do. 

# Q3 - Discuss the implementation of Agile project management methodology

The Agile project management methodology is an incremental approach to delivering the requirements through the projects life cycle. This method breaks a project into smaller parts that are prioritized by the teams in order of importance. This method allows the team to be empowered in their approach, leading them to build accountability, encourage the diversity of ideas, creating achievement at each break and alibility of improvement throughout the project. At its core, the Agile approach should follow central values of trust, flexibility and collaboration. 

Benefits of this approach promotes the collaborative working between the project and the client. The client is provided with small parts of the projects at regular intervals. The changes are incremental rather than revolutionary. The client is able to give feedback more regularly and allows the project to reflect and adjust if needed. This tight feedback loop is highly beneficial to the teams as well as the client.

Agile incorporates planning with execution, this allows an organization to foster a working mindset that helps a team respond to changing requirements. This focuses on delivering maximum value against the businesses priorities in the time and budget allowed. 

# Q4 - Provide an overview and description of a standard source control process

A version control system are a software tool that allows software team manage changes to code over time. This tool keeps track of each modification to the code in a database. If an error occurs, a team member can revert to a previous earlier version of the code to rectify the error while minimizing the disruption to other members of the team. The usual process for a source control software is to ensure you are working from the latest error free version, stage the changes on your local then while working on the code, commit to a branch often. When a commit is done you need to ensure the commit message is meaningful. Review the code then make a request to merge to the master or main code.

# Q5 - Provide an overview and description of a standard software testing process

Test Driven Development also known as TDD is the process of writing code in order to make a test pass, this ensures coders avoid writing unnecessary code and keeping their code DRY. A goal of using this process is to make the code simple, clean and bug free. TDD starts by designing the tests for the functionality of an app. These tests states and verifies what the code will do. When the test fails, usually because the code has not yet been developed, the coder develops the code by writing the minimum amount and refactors it in order to pass the test. The code is being changed without affecting the behaviours. 

# Q6 - Discuss and analyse requirements related to information system security

Information system security is protecting information or data and their information systems from unauthorized access, use, disclosure, disruption, modification, or destruction. A requirement of the business could be the implementation of awareness training for all levels and employees of the business to ensure they know their responsibilities and role in information system security. The team should understand the risk management practices in place and follow them. They should also be able when necessary to follow contingency plans to their fullest capacity. The business responsible to assess new risks in relation to information system security as they arise and as the business changes.

# Q7 - Discuss common methods of protecting information and data

Protecting data and information is highly important for anyone, whether your own individual or a company. Methods can range and there are no guarantees that you will be protected.  One of the simplest methods is to password protect your devices and passwords should not be simple words or linier number sequences. It is also important to not use the same password for every login. Another simple method to protect your data and information is to keep back-ups of your computer and phone in the case they are lost or stolen. It is important to keep your software up to date to keep out malware, viruses and system fails that can wipe out all your data. 

# Q8 - Research what your legal obligations are in relation to handling user data

Legal obligations for user data is making the user aware of what user data is being collected and how it will be used. A home page of a site could potentially collect are the users IP address, when the site was accessed, type of browser used or what site the user came from. This can all be collected before entering anything or clicking anything. The user needs to be made aware that their data will be collected then how it will be used including if sharing with 3rd party. A method used widely for letting users know about this is including a privacy policy outlining the legal obligations however this can be overlooked and is not enough to be bound by. The next step up from this the click wrap where users need to actively click an “I agree” button or checkbox.

# Q9 - Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

A relational database is a collection of table each with a unique name. The rows of these tables represents a relationship among the set of values therefore a collection of relationships, there is a close correspondence between tables and the math concept of relation. The rational data model from this. A tuple is a list of values. A relationship between n values is represented as n-tuple.  In a table the columns list the headers or attributes and the rows store the information of those headers. 

# Q10 - Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

Integrity aspects in relational databases include validation to ensure the data is not null, too long or too short, using associations including the ‘dependent: :destroy’ to avoid orphan records and restricting data types to the needed value such as only allowing positive numbers for prices for a product. 
This also includes entity integrity of the concept of primary keys. Each table must have a PK and should be unique and not null. In the same way a referential is a concept of a foreign key. Its usual state is the FK refers to a PK in another table in the database.

# Q11 - Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

The relational database models can be manipulated through the use of the CRUD method. The CRUD method are 4 basic functions. C = Create, R = Read, U = Update and D = Delete. The create function is to add new entries. Read function is to retrieve, search or view the existing entries. Update is to edit existing entries and delete is to remove an existing entry. These 4 functions are fundamental in the manipulation of data in a relational database model. 

# Q12 - Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency (i.e. Big O)

## Quick Sort
Quick sort is a divide and conquer algorithm that picks an element from the array as pivot and partitions the given array around that picked pivot point.

In Big O notation a quick sort is considered an O(n2) process and is known as quadratic. Quick sort is a simple algorithm, worse case can be slower then merge or heap sort, but because of its inner loop can be more efficiently implemented. It can be faster by changing the point of the pivot but merge sort would be considered better when the data is large.

There are a few ways in which the pivot element is chosen; first element, last element, random element or median. The key process in quick sort is partition. Target of partitions is given the array, then chosen element, is put at its correct position and put all smaller elements then the chosen element below and greater elements after. 

## Bubble Sort
A bubble sort is a simple sorting algorithm that repeatedly steps through the list until the entire list is sorted. 

In Big O notation a binary sort is an O(n2) process and is known as quadratic. Although the algorithm is simple it is often to slow and impractical when compared to other sorting methods. It could be used were the input is mostly in order. 

Bubble sort repeatedly steps through the list, compares adjacent elements then swaps them if they are in the wrong order. It goes through the list repeatedly until the entire list is sorted. This requires many passes when the list is very out of order and is impractical in the case of large lists or reversed ordered lists.

# Q13 - Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency (i.e. Big O)

## Linear Search
A linear search is going through each element until the value is found.

In Big O notation is O(n) and is known as linear. Linear search is not often used as the binary search is significantly faster in comparison. 

Linear search starts from the leftmost element of the array and compare the value with each element of the array. If the first element matches the value, return the index, if the element doesn’t match, return -1. 

## Jump Search
Jump search method is designed to check fewer elements then what linear search does. 

In Big O notation is O(√n) and is logarithmic and should only be used on sorted arrays. 

Jump search is a searching algorithm is for searching sorted arrays. The jump search searches less elements then linear search by jumping ahead by a fixed amount of steps. The optimal skip block should be (√n), this makes up the time complexity of jump search. This skipping of some elements rather searching every element (like linear search) is more efficient in some cases.

# Q14 - Conduct research into a marketplace website (app) and answer the following parts:  
## a. What software is used by the app?
## b. What hardware is used by the app?
## c. Describe the interaction of technologies within the app
## d. Describe the way data is structured within the app

### Shopify

* Shopify uses for their application and data are:
* Nginx - A high performance free open source web server powering busiest sites on the Internet.
* MySQL - The world's most popular open source database
* Redis - An in-memory database that persists on disk
* Ruby - A dynamic, interpreted, open source programming language with a focus on simplicity and productivity
* Rails – Web development framework
* Go - An open source programming language that makes it easy to build simple, reliable, and efficient software
* Kafka - Distributed, fault tolerant, high throughput pub-sub messaging system
* Memcached - High-performance, distributed memory object caching system
* Open Resty - Turning Nginx into a Full-fledged Web App Server
* Hadoop - Open-source software for reliable, scalable, distributed computing
* Apache Spark - Fast and general engine for large-scale data processing
* Google Kubernetes Engine - Deploy, manage, and scale containerized applications on Kubernetes, powered by Google Cloud
* Lua - Powerful, fast, lightweight, embeddable scripting language
* Unicorn - Rack HTTP server for fast clients and Unix
 
Utilities include: 
* ElasticSearch - Open Source, Distributed, RESTful Search Engine
* Bootsnap - Boot large ruby/rails apps faster, by Shopify

DevOp includes: 
* GitHub - Powerful collaboration, review, and code management for open source and private development projects
* Git - Fast, scalable, distributed revision control system
* Docker - Enterprise Container Platform for High-Velocity Innovation.
* New Relic - SaaS Application Performance Management for Ruby, PHP, .Net, Java, Python, and Node.js Apps.
* Kubernetes - Manage a cluster of Linux containers as a single system to accelerate Dev and simplify Ops
* Vagrant - A tool for building and distributing development environments
* Pingdom - Uptime and performance monitoring made easy
* Datadog - Unify logs, metrics, and traces from across your distributed infrastructure.
* Chef - Build, destroy and rebuild servers on any public or private cloud
* Zookeeper - Coordinating distributed systems
* StatusPage.io - Real-time status and incident communication.
* StatsD - Simple daemon for easy stats aggregation
* Buildkite - Fast, secure and scalable CI/CD for all your software projects
* Percy - Add visual reviews to your GitHub pull requests, helping your team spot UI bugs quickly and review visual changes easily

Business tools include: 
* Slack - Bring all your communication together in one place
* Zendesk - The leading cloud-based customer service software solution.

Ruby is a dynamic, interpreted, open source programming language with a focus on simplicity and productivity that uses rails as a gem. Rails needs to be set up within the app in order to work properly. Ruby on Rails default database is SQLite, Shopify configures their system to use MySQL. The pods in which Shopify is currently using (A pod is a fully isolated instance of Shopify with its own data stores). These data stores use MySQL as well as Redis and Memcached. 

Shopify in their growth have hundreds of pods they needed a solution to coordinate the deployments. They use Docker, Kubernetes, and Google Kubernetes Engine to manage resources for the new Shopify Pods. 

Shopify uses Unicorn as a rack HTTP server and nginx through OpenResty, to turn nginx into a full-fledged web app server.   

Shopify data is structured under MySQL which is a relational database management system. This database system that stores data in a structured format using rows and columns. It is called relational because values in each of the table are related to each other and tables can also be related to other tables. Multiple queries can run across multiple tables. A relational database is a software that runs queries on data, including adding, updating and value searches. 

## e. Identify entities which must be tracked by the app
User 
-	User_id
-	Profile_img
-	Account_name
-	Password
-	Shop_id (if they own a shop)
-	Email
-	Address

Shop
-	User_id
-	Shop_name
-	Shop_id

Category
-	Category_name
-	Category_id

Product
-	Product_id
-	Title
-	Description
-	Price
-	Quantity
-	Image

Cart_item
-	Cart_item_id
-	Product_id
-	User_id
-	Quantity
-	Shopping_cart_id
-	Shop_id

Shopping cart
-	Shopping_cart_id
-	User_id
-	Shipping
-	Message

## f. Identify the relationships and associations between the entities you have identified in part (e)

User model 

has_one :shop
-	A user can only have one shop but can exist as a buyer without a shop.

has_many :products, dependent: :destroy
-	A user is able to have many products but is able to exist without having any products. A user can just buy and never sell if wanted. If the user is destroyed all of their products will also be destroyed.

has_one :cart, dependent: :destroy
-	A user can only have one cart. This cart references the current users id, when a user is destroyed so is their cart.

Shop model

belongs_to :user
-	The shop can only have one owner

Has_many :category
-	The shop can have many categories

Category model

Has_many :products
-	The category has many products

Product model

Belongs_to :shop
-	The products listed in the shop can only belong to one shop.

Belongs_to :category
-	The products belong to a particular category

Belongs_to :user
-	Makes sure a product has a user, a product cannot be user identity-less. Payment would be processed on the app and a user-less product would cause many issues.

has_one_attached :image
-	Informs the model to expect an image 

has_many :cart_item, dependent: :destroy
-	A product can appear in many user’s carts through the cart_item model. When a product is destroyed, all of that products in other user’s carts are destroyed.

Cart_item Model

belongs_to :cart
-	The cart_item can only belong to the user’s cart it is assigned to.

belongs_to :product
-	The cart_item can only belong to the product it is assigned to.

Cart Model

belongs_to :user
-	A cart can only belong to one user with the user id associated with it.

has_many :cart_items, dependent: :destroy
-	A cart can have many cart_items. The cart when destroyed, destroy the cart_items.

has_many :products
-	The cart has many products using the cart_items join table. 

## g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)

![ERD](https://github.com/reneenilsen/workbook/blob/master/Database%20ER%20Diagram%20(Crow's%20Foot)%20(2).png "ERD")