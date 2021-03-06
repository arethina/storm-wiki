Want to be added to this page? Send an email [here](mailto:nathan.marz@gmail.com).

<table>

<tr>
<td>
<a href="http://groupon.com">Groupon</a>
</td>
<td>
<p>
At Groupon we use Storm to build real-time data integration systems. Storm helps us analyze, clean, normalize, and resolve large amounts of non-unique data points with low latency and high throughput.
</p>
</td>
</tr>

<tr>
<td><a href="http://www.weather.com/">The Weather Channel</a></td>
<td>
<p>At Weather Channel we use several Storm topologies to ingest and persist weather data. Each topology is responsible for fetching one dataset from an internal or external network (the Internet), reshaping the records for use by our company, and persisting the records to relational databases. It is particularly useful to have an automatic mechanism for repeating attempts to download and manipulate the data when there is a hiccup.</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.fullcontact.com/">FullContact</a>
</td>
<td>
<p>
At FullContact we currently use Storm as the backbone of the system which synchronizes our Cloud Address Book with third party services such as Google Contacts and Salesforce. We also use it to provide real-time support for our contact graph analysis and federated contact search systems.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://twitter.com">Twitter</a>
</td>
<td>
<p>
Storm powers a wide variety of Twitter systems, ranging in applications from discovery, realtime analytics, personalization, search, revenue optimization, and many more. Storm integrates with the rest of Twitter's infrastructure, including database systems (Cassandra, Memcached, etc), the messaging infrastructure, Mesos, and the monitoring/alerting systems. Storm's isolation scheduler makes it easy to use the same cluster both for production applications and in-development applications, and it provides a sane way to do capacity planning.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.yahoo.com">Yahoo!</a>
</td>
<td>
<p>
Yahoo! is developing a next generation platform that enables the convergence of big-data and low-latency processing. While Hadoop is our primary technology for batch processing, Storm empowers stream/micro-batch processing of user events, content feeds, and application logs. 
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.infochimps.com">Infochimps</a>
</td>
<td>
<p>
Infochimps uses Storm as part of its Big Data Enterprise Cloud. Specifically, it uses Storm as the basis for one of three of its cloud data services - namely, Data Delivery Services (DDS), which uses Storm to provide a fault-tolerant and linearly scalable enterprise data collection, transport, and complex in-stream processing cloud service. 
</p>

<p>
In much the same way that Hadoop provides batch ETL and large-scale batch analytical processing, the Data Delivery Service provides real-time ETL and large-scale real-time analytical processing — the perfect complement to Hadoop (or in some cases, what you needed instead of Hadoop).
</p>

<p>
DDS uses both Storm and Kafka along with a host of additional technologies to provide an enterprise-class real-time stream processing solution with features including:
</p>

<ul>
<li>
Integration connections to any variety of data sources in a way that is robust yet as non-invasive
</li>
<li>
Optimizations for highly scalable, reliable data import and distributed ETL (extract, transform, load), fulfilling data transport needs
</li>
<li>
Developer tools for rapid development of decorators, which perform the real-time stream processing
</li>
<li>
Guaranteed delivery framework and data failover snapshots to send processed data to analytics systems, databases, file systems, and applications with extreme reliability
</li>
<li>
Rapid solution development and deployment, along with our expert Big Data methodology and best practices
</li>
</ul>

<p>Infochimps has extensive experience in deploying its DDS to power large-scale clickstream web data flows, massive Twitter stream processes, Foursquare event processing, customer purchase data, product pricing data, and more.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://cerner.com/">Cerner</a>
</td>
<td>
<p>
Cerner is a leader in health care information technology. We have been using Storm since its release to process massive amounts of clinical data in real-time. Storm integrates well in our architecture, allowing us to quickly provide clinicians with the data they need to make medical decisions.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.aeris.com/">Aeris Communications</a>
</td>
<td>
<p>
Aeris Communications has the only cellular network that was designed and built exclusively for machines. Our ability to provide scalable, reliable real-time analytics - powered by Storm - for machine to machine (M2M) communication offers immense value to our customers. We are using Storm in production since Q1 of 2013.
</p>
</td>
</tr>



<tr>
<td>
<a href="http://flipboard.com/">Flipboard</a>
</td>
<td>
<p>
Flipboard is the worldʼs ﬁrst social magazine, a single place to keep up with everything  you care about and collect it in ways that let reﬂect you. Inspired by the beauty and  ease of print media, Flipboard is designed so you can easily ﬂip through news from around the world or stories from right at home, helping people ﬁnd the one thing that  can inform, entertain or even inspire them every day.
</p>
<p>
We are using Storm across a wide range of our services from content search, to realtime analytics, to generating custom magazine feeds. We then integrate Storm across our infrastructure within systems like ElasticSearch, HBase, Hadoop and HDFS to create a highly scalable data platform.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.rubiconproject.com/">Rubicon Project</a>
</td>
<td>
<p>
Storm is being used in production mode at the Rubicon Project to analyze the results of auctions of ad impressions on its RTB exchange as they occur.  It is currently processing around 650 million auction results in three data centers daily (with 3 separate Storm clusters). One simple application is identifying new creatives (ads) in real time for ad quality purposes.  A more sophisticated application is an "Inventory Valuation Service" that uses DRPC to return appraisals of new impressions before the auction takes place.  The appraisals are used for various optimization problems, such as deciding whether to auction an impression or skip it when close to maximum capacity.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.ooyala.com/">Ooyala</a>
</td>
<td>
<p>
Ooyala powers personalized multi-screen video experiences for some of the world's largest networks, brands and media companies. We provide all the technology and tools our customers need to manage, distribute and monetize digital video content at a global scale.
</p>

<p>
At the core of our technology is an analytics engine that processes over two billion analytics events each day, derived from nearly 200 million viewers worldwide who watch video on an Ooyala-powered player.
</p>

<p>
Ooyala will be deploying Storm in production to give our customers real-time streaming analytics on consumer viewing behavior and digital content trends. Storm enables us to rapidly mine one of the world's largest online video data sets to deliver up-to-the-minute business intelligence ranging from real-time viewing patterns to personalized content recommendations to dynamic programming guides and dozens of other insights for maximizing revenue with online video.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.taobao.com/index_global.php">Taobao</a>
</td>
<td>
<p>
We make statistics of logs and extract useful information from the statistics in almost real-time with Storm.  Logs are read from Kafka-like persistent message queues into spouts, then processed and emitted over the topologies to compute desired results, which are then stored into distributed databases to be used elsewhere. Input log count varies from 2 millions to 1.5 billion every day, whose size is up to 2 terabytes among the projects.  The main challenge here is not only real-time processing of big data set; storing and persisting result is also a challenge and needs careful design and implementation.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.alibaba.com/">Alibaba</a>
</td>
<td>
<p>
Alibaba is the leading B2B e-commerce website in the world. We use storm to process the application log and the data change in database to supply realtime stats for data apps.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.baidu.com/">Baidu</a>
</td>
<td>
<p>
Baidu offers top searching technology services for websites, audio files and images, my group using Storm to process the searching logs to supply realtime stats for accounting pv, ar-time and so on.
This project helps Ops to determine and monitor services status and can do great things in the future.
</p>
</td>
</tr>


<tr>
<td>
<a href="http://www.klout.com/">Klout</a>
</td>
<td>
<p>
Klout helps everyone discover and be recognized for their influence by analyzing engagement with their content across social networks. Our analysis powers a daily Klout Score on a scale from 1-100 that shows how much influence social media users have and on what topics. We are using Storm to develop a realtime scoring and moments generation pipeline. Leveraging Storm's intuitive Trident abstraction we are able to create complex topologies which stream data from our network collectors via Kafka, processed and written out to HDFS.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.loggly.com">Loggly</a>
</td>
<td>
<p>
Loggly is the world's most popular cloud-based log management. Our cloud-based log management service helps DevOps and technical teams make sense of the the massive quantity of logs that are being produced by a growing number of cloud-centric applications – in order to solve operational problems faster. Storm is the heart of our ingestion pipeline where it filters, parses and analyses billions of log events all-day, every day and in real-time.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://premise.is/">premise.is</a>
</td>
<td>
<p>
We're building a platform for alternative, bottom-up, high-granularity econometric data capture, particularly targeting opaque developing economies (i.e., Argentina might lie about their inflation statistics, but their black market certainly doesn't). Basically we get to funnel hedge fund money into improving global economic transparency. 
</p>
<p>
We've been using Storm in production since January 2012 as a streaming, time-indexed web crawl + extraction + machine learning-based semantic markup flow (about 60 physical nodes comparable to m1.large; generating a modest 25GB/hr incremental). We wanted to have an end-to-end push-based system where new inputs get percolated through the topology in realtime and appear on the website, with no batch jobs required in between steps. Storm has been really integral to realizing this goal.
</p>
</td>
</tr>



<tr>
<td>
<a href="http://www.wego.com/">Wego</a>
</td>
<td>
<p>About Wego, we are one of the world’s most comprehensive travel metasearch engines, operating in 42 markets worldwide and used by millions of travelers to save time, pay less and travel more. We compare and display real-time flights, hotel pricing and availability from hundreds of leading travel sites from all around the world on one simple screen.</p>

<p>At the heart of our products, Storm helps us to stream real-time meta-search data from our partners to end-users. Since data comes from many sources and with different timing, Storm topology concept naturally solves concurrency issues while helping us to continuously merge, slice and clean all the data. Additionally with a few tricks and tools provided in Storm we can easily apply incremental update to improve the flow our data (1-5GB/minute).</p>
 
<p>With its simplicity, scalability, and flexibility, Storm does not only improve our current products but more importantly changes the way we work with data. Instead of keeping data static and crunching it once a while, we constantly move data all around, making use of different technologies, evaluating new ideas and building new products. We stream critical data to memory for fast access while continuously crunching and directing huge amount of data into various engines so that we can evaluate and make use of data instantly. Previously, this kind of system requires to setup and maintain quite a few things but with Storm all we need is half day of coding and a few seconds to deploy. In this sense we never think Storm is to serve our products but rather to evolve our products.</p>
</td>
</tr>

<tr>
<td>
<a href="http://rocketfuel.com/">RocketFuel</a>
</td>
<td>
<p>
At Rocket Fuel (an ad network) we are building a real time platform on top of Storm which imitates the time critical workflows of existing Hadoop based ETL pipeline. This platform tracks impressions, clicks, conversions, bid requests etc. in real time. We are using Kafka as message queue. To start with we are pushing per minute aggregations directly to MySQL, but we plan to go finer than one minute and may bring HBase in to the picture to handle increased write load. 
</p>
</td>
</tr>

<tr>
<td>
<a href="http://quicklizard.com/">QuickLizard</a>
</td>
<td>
<p>
QuickLizard builds solution for automated pricing for companies that have many products in their lists. Prices are influenced by multiple factors internal and external to company.
</p>

<p>
Currently we use Storm to choose products that need to be priced. We get real time stream of events from client site and filters them to get much more light stream of products that need to be processed by our procedures to get price recommendation.
</p>

<p>
In plans: use Storm also for real time data mining model calculation that should match products described on competitor sites to client products.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://spider.io/">spider.io</a>
</td>
<td>
<p>
At spider.io we've been using Storm as a core part of our classification engine since October 2011. We run Storm topologies to combine, analyse and classify real-time streams of internet traffic, to identify suspicious or undesirable website activity. Over the past 7 months we've expanded our use of Storm, so it now manages most of our real-time processing. Our classifications are displayed in a custom analytics dashboard, where Storm's distributed remote procedure call interface is used to gather data from our database and metadata services. DRPC allows us to increase the responsiveness of our user interface by distributing processing across a cluster of Amazon EC2 instances.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://8digits.com/">8digits</a>
</td>
<td>
<p>
At 8digits, we are using Storm in our analytics engine, which is one of the most crucial parts of our infrastructure. We are utilizing several cloud servers with multiple cores each for the purpose of running a real-time system making several complex calculations. Storm is a proven, solid and a powerful framework for most of the big-data problems.
</p>
</td>
</tr>



<tr>
<td>
<a href="https://www.alipay.com/">Alipay</a>
</td>
<td>
<p>
Alipay is China's leading third-party online payment platform. We are using Storm in many scenarios:
</p>

<ol>
<li>
Calculate realtime trade quantity, trade amount, the TOP N seller trading information, user register count. More than 100 million messages per day.
</li>
<li>
Log processing, more than 6T data per day.
</li>
</ol>
</td>
</tr>

<tr>
<td>
<a href="http://navisite.com/">NaviSite</a>
</td>
<td>
<p>
We are using Storm as part of our server event log monitoring/auditing system.  We send log messages from thousands of servers into a RabbitMQ cluster and then use Storm to check each message against a set of regular expressions.  If there is a match (&lt; 1% of messages), then the message is sent to a bolt that stores data in a Mongo database.  Right now we are handling a load of somewhere around 5-10k messages per second, however we tested our existing RabbitMQ + Storm clusters up to about 50k per second.  We have plans to do real time intrusion detection as an enhancement to the current log message reporting system. 
</p>

<p>
We have Storm deployed on the NaviSite Cloud platform.  We have a ZK cluster of 3 small VMs, 1 Nimbus VM and 16 dual core/4GB VMs as supervisors.
</p>
</td>
</tr>


<tr>
<td>
<a href="http://www.paywithglyph.com">Glyph</a>
</td>
<td>
<p>
Glyph is in the business of providing credit card rewards intelligence to consumers. At a given point of sale Glyph suggest its users what are the best cards to be used at a given merchant location that will provide maximum rewards. Glyph also provide suggestion on the cards the user should carry to earn maximum rewards based on his personal spending habits. Glyph provides this information to the user by retrieving and analyzing credit card transactions from banks. Storm is used in Glyph to perform this retrieval and analysis in realtime. We are using Memcached in conjuction with Storm for handling sessions. We are impressed by how Storm makes high availability and reliability of Glyph services possible. We are now using Storm and Clojure in building Glyph data analytics and insights services. We have open-sourced node-drpc wrapper module for easy Storm DRPC integration with NodeJS.
</p>
</td>
</tr>
<tr>
<td>
<a href="http://heartbyte.com/">Heartbyte</a>
</td>
<td>
<p>
At Heartbyte, Storm is a central piece of our realtime audience participation platform.  We are often required to process a 'vote' per second from hundreds of thousands of mobile devices simultaneously and process / aggregate all of the data within a second.  Further, we are finding that Storm is a great alternative to other ingest tools for Hadoop/HBase, which we use for batch processing after our events conclude.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://2lemetry.com/">2lemetry</a>
</td>
<td>
<p>
2lemetry uses Storm to power it's real time analytics on top of the m2m.io offering. 2lemetry is partnered with Sprint, Verizon, AT&T, and Arrow Electronics to power IoT applications world wide. Some of 2lemetry's larger projects include RTX, Kontron, and Intel. 2lemetry also works with many professional sporting teams to parse data in real time. 2lemetry receives events for every touch of the ball in every MLS soccer match. Storm is used to look for trends like passing tendencies as they develop during the game. 
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.nodeable.com/">Nodeable</a>
</td>
<td>
<p>
Nodeable uses Storm to deliver real-time continuous computation of the data we consume. Storm has made it significantly easier for us to scale our service more efficiently while ensuring the data we deliver is timely and accurate.
</p>
</td>
</tr>

<tr>
<td>
<a href="https://twitsprout.com/">TwitSprout</a>
</td>
<td>
<p>
At TwitSprout, we use Storm to analyze activity on Twitter to monitor mentions of keywords (mostly client product and brand names) and trigger alerts when activity around a certain keyword spikes above normal levels. We also use Storm to back the data behind the live-infographics we produce for events sponsored by our clients. The infographics are usually in the form of a live dashboard that helps measure the audience buzz across social media as it relates to the event in realtime.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.happyelements.com/">HappyElements</a>
</td>
<td>
<p>
<a href="http://www.happyelements.com">HappyElements</a> is a leading social game developer on Facebook and other SNS platforms. We developed a real time data analysis program based on storm to analyze user activity in real time.  Storm is very easy to use, stable, scalable and maintainable.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.idexx.com/view/xhtml/en_us/corporate/home.jsf">IDEXX Laboratories</a>
</td>
<td>
<p>
IDEXX Laboratories is the leading maker of software and diagnostic instruments for the veterinary market. We collect and analyze veterinary medical data from thousands of veterinary clinics across the US. We recently embarked on a project to upgrade our aging data processing infrastructure that was unable to keep up with the rapid increase in the volume, velocity and variety of data that we were processing.
</p>

<p>
We are utilizing the Storm system to take in the data that is extracted from the medical records in a number of different schemas, transform it into a standard schema that we created and store it in an Oracle RDBMS database. It is basically a souped up distributed ETL system. Storm takes on the plumbing necessary for a distributed system and is very easy to write code for. The ability to create small pieces of functionality and connect them together gives us the ultimate flexibility to parallelize each of the pieces differently.
</p>

<p>
Our current cluster consists of four supervisor machines running 110 tasks inside 32 worker processes. We run two different topologies which receive messages and communicate with each other via RabbitMQ. The whole thing is deployed on Amazon Web Services and utilizes S3 for some intermediate storage, Redis as a key/value store and Oracle RDS for RDBMS storage. The bolts are all written in Java using the Spring framework with Hibernate as an ORM.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.umeng.com/">Umeng</a>
</td>
<td>
Umeng is the leading and largest provider of mobile app analytics and developer services platform in China. Storm powers Umeng's realtime analytics platform, processing billions of data points per day and growing. We also use Storm in other products which requires realtime processing and it has become the core infrastructure in our company. 
</td>
</tr>

<tr>
<td>
<a href="http://www.admaster.com.cn/">Admaster</a>
</td>
<td>
<p>
We provide monitoring and precise delivery for Internet advertising. We use Storm to do the following:
</p>

<ol>
<li>Calculate PV, UV of every advertisement.</li>
<li>Simple data cleaning: filter out data which format error, filter out cheating data (the pv more than certain value)</li>
</ol>
Our cluster has 8 nodes, process several billions messages per day, about 200GB.
</td>
</tr>

<tr>
<td>
<a href="http://socialmetrix.com/en/">SocialMetrix</a>
</td>
<td>
<p>
Since its release, Storm was a perfect fit to our needs of real time monitoring. Its powerful API, easy administration and deploy, enabled us to rapidly build solutions to monitor presidential elections, several major events and currently it is the processing core of our new product "Socialmetrix Eventia".
</p>
</td>
</tr>


<tr>
<td>
<a href="http://needium.com/">Needium</a>
</td>
<td>
<p>
At Needium we love Ruby and JRuby. The Storm platform offers the right balance between simplicity, flexibility and scalability. We created RedStorm, a Ruby DSL for Storm, to keep on using Ruby on top of the power of Storm by leveraging Storm's JVM foundation with JRuby. We currently use Storm as our Twitter realtime data processing pipeline. We have Storm topologies for content filtering, geolocalisation and classification. Storm allows us to architecture our pipeline for the Twitter full firehose scale.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://parse.ly/">Parse.ly</a>
</td>
<td>
<p>
Parse.ly is using Storm for its web/content analytics system. We have a home-grown data processing and storage system built with Python and Celery, with backend stores in Redis and MongoDB. We are now using Storm for real-time unique visitor counting and are exploring options for using it for some of our richer data sources such as social share data and semantic content metadata.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.parc.com/">PARC</a>
</td>
<td>
<p>
High Performance Graph Analytics & Real-time Insights Research team at PARC uses Storm as one of the building blocks of their PARC Analytics Cloud infrastructure which comprises of Nebula based Openstack, Hadoop, SAP HANA, Storm, PARC Graph Analytics, and machine learning toolbox to enable researchers to process real-time data feeds from Sensors, web, network, social media, and security traces and easily ingest any other real-time data feeds of interest for PARC researchers.
</p>
<p>
PARC researchers are working with number of industry collaborators developing new tools, algorithms, and models to analyze massive amounts of e-commerce, web clickstreams, 3rd party syndicated data, cohort data, social media data streams, and structured data from RDBMS, NOSQL, and NEWSQL systems in near real-time. PARC  team is developing a reference architecture and benchmarks for their near real-time automated insight discovery platform combining the power of all above tools and PARC’s applied research in machine learning, graph analytics, reasoning, clustering, and contextual recommendations. The High Performance Graph Analytics & Real-time Insights research at PARC is headed by Surendra Reddy<http://www.linkedin.com/in/skreddy>.  If you are interested to learn more about our use/experience of using Storm or to know more about our research or to collaborate with PARC in this area, please feel free to contact sureddy@parc.com.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://gumgum.com/">GumGum</a>
</td>
<td>
<p>
GumGum, the leading in-image advertising platform for publishers and brands, uses Storm to produce real-time data. Storm and Trident-based topologies consume various ad-related events from Kafka and persist the aggregations in MySQL and HBase. This architecture will eventually replace most existing daily Hadoop map reduce jobs. There are also plans for Kafka + Storm to replace existing distributed queue processing infrastructure built with Amazon SQS.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.crowdflower.com/">CrowdFlower</a>
</td>
<td>
<p>
CrowdFlower is using Storm with Kafka to generalize our data stream
aggregation and realtime computation infrastructure. We replaced our
homegrown aggregation solutions with Storm because it simplified the
creation of fault tolerant systems. We were already using Zookeeper
and Kafka, so Storm allowed us to build more generic abstractions for
our analytics using tools that we had already deployed and
battle-tested in production.
</p>

<p>
We are currently writing to DynamoDB from Storm, so we are able to
scale our capacity quickly by bringing up additional supervisors and
tweaking the throughput on our Dynamo tables. We look forward to
exploring other uses for Storm in our system, especially with the
recent release of Trident.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.dsbox.com">Digital Sandbox</a>
</td>
<td>
<p>
At Digital Sandbox we use Storm to enable our open source information feed monitoring system.  The system uses Storm to constantly monitor and pull data from structured and unstructured information sources across the internet.  For each found item, our topology applies natural language processing based concept analysis, temporal analysis, geospatial analytics and a prioritization algorithm to enable users to monitor large special events, public safety operations, and topics of interest to a multitude of individual users and teams.
</p>
 
<p>
Our system is built using Storm for feed retrieval and annotation, Python with Flask and jQuery for business logic and web interfaces, and MongoDB for data persistence. We use NTLK for natural language processing and the WordNet, GeoNames, and OpenStreetMap databases to enable feed item concept extraction and geolocation.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://hallo.me/">Hallo</a>
</td>
<td>
With several mainstream celebrities and very popular YouTubers using Hallo to communicate with their fans, we needed a good solution to notify users via push notifications and make sure that the celebrity messages were delivered to follower timelines in near realtime. Our initial approach for broadcast push notifications would take anywhere from 2-3 hours. After re-engineering our solution on top of Storm, that time has been cut down to 5 minutes on a very small cluster. With the user base growing and user need for realtime communication, we are very happy knowing that we can easily scale Storm by adding nodes to maintain a baseline QoS for our users.
</td>
</tr>

<tr>
<td>
<a href="http://keepcon.com/">Keepcon</a>
</td>
<td>
We provide moderation services for classifieds, kids communities, newspapers, chat rooms, facebook fan pages, youtube channels, reviews, and all kind of UGC. We use storm for the integration with our clients, find evidences within each text, persisting on cassandra and elastic search and sending results back to our clients.
</td>
</tr>

<tr>
<td>
<a href="http://www.visiblemeasures.com/">Visible Measures</a>
</td>
<td>
<p>
Visible Measures powers video campaigns and analytics for publishers and
advertisers, tracking data for hundreds of million of videos, and billions
of views. We are using Storm to process viewing behavior data in real time and make
the information immediately available to our customers. We read events from
various push and pull sources, including a Kestrel queue, filter and
enrich the events in Storm topologies, and persist the events to Redis,
HDFS and Vertica for real-time analytics and archiving. We are currently
experimenting with Trident topologies, and figuring out how to move more
of our Hadoop-based batch processing into Storm.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.o2mc.eu/en/">O2mc</a>
</td>
<td>
<p>
One of the core products of O2mc is called O2mc Community. O2mc Community performs multilingual, realtime sentiment analysis with very low latency and distributes the analyzed results to numerous clients. The input is extracted from source systems like Twitter, Facebook, e-mail and many more. After the analysis has taken place on Storm, the results are streamed to any output system ranging from HTTP streaming to clients to direct database insertion to an external business process engine to kickstart a process.</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.theladders.com">The Ladders</a>
</td>
<td>
<p>
TheLadders has been committed to finding the right person for the right job since 2003. We're using Storm in a variety of ways and are happy with its versatility, robustness, and ease of development. We use Storm in conjunction with RabbitMQ for such things as sending hiring alerts: when a recruiter submits a job to our site, Storm processes that event and will aggregate jobseekers whose profiles match the position. That list is subsequently batch-processed to send an email to the list of jobseekers. We also use Storm to persist events for Business Intelligence and internal event tracking. We're continuing to find uses for Storm where fast, asynchronous, real-time event processing is a must.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://semlab.nl">SemLab</a>
</td>
<td>
<p>
SemLab develops software for knowledge discovery and information support. Our ViewerPro platform uses information extraction, natural language processing and semantic web technologies to extract structured data from unstructured sources, in domains such as financial news feeds and legal documents. We have succesfully adapted ViewerPro's processing framework to run on top of Storm. The transition to Storm has made ViewerPro a much more scalable product, allowing us to process more in less time.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://visualrevenue.com/">Visual Revenue</a>
</td>
<td>
<p>
Here at Visual Revenue, we built a decision support system to help online editors to make choices on what, when, and where to promote their content in real-time. Storm is the backbone our real-time data processing and aggregation pipelines.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.peerindex.com/">PeerIndex</a>
</td>
<td>
<p>
PeerIndex is working to deliver influence at scale. PeerIndex does this by exposing services built on top of our Influence Graph; a directed graph of who is influencing whom on the web. PeerIndex gathers data from a number of social networks to create the Influence Graph. We use Storm to process our social data, to provide real-time aggregations, and to crawl the web, before storing our data in a manner most suitable for our Hadoop based systems to batch process. Storm provided us with an intuitive API and has slotted in well with the rest of our architecture. PeerIndex looks forward to further investing resources into our Storm based real-time analytics.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://eclick.vn/">eClick</a>
</td>
<td>
<p>
At eClick (an ad-network for most popular websites and publishers in Vietnam) we are building a real time platform on top of Storm which does parsing raw logs, crawling websites for social analytics, analyzing big data. This platform tracks impressions, clicks, conversions, user-behaviour, .. etc. in real time. We are using Kafka as message queue, and deploy in customized Storm Cluster.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.wayfair.com">Wayfair</a>
</td>
<td>
<p>
At Wayfair, we use storm as a platform to drive our core order processing pipeline as an event driven system. Storm allows us to reliably process tens of thousands of orders daily while providing us the assurance of seamless process scalability as our order load increases. Given the project’s ease of use and the immense support of the community, we’ve managed to implement our bolts in php, construct a simple puppet module for configuration management, and quickly solve arising issues. We can now focus most of our development efforts in the business layer, check out more information on how we use storm <a href="http://engineering.wayfair.com/stormin-oms/">in our engineering blog</a>. </p>
</td>
</tr>

<tr>
<td>
<a href="http://innoquant.com/">InnoQuant</a>
</td>
<td>
<p>
At InnoQuant, we use Storm as a backbone of our real-time big data analytics engine in MOCA platform. MOCA is a next generation, mobile-backend-as-a-service platform (MBaaS). It provides brands and app developers with real-time in-app tracking, context-aware push messaging, user micro-segmentation based on profile, time and geo-context as well as big data analytics. Storm-based pipeline is fed with events captured by native mobile SDKs (iOS, Android), scales nicely with connected mobile app users, delivers stream-based metrics and aggregations, and finally integrates with the rest of MOCA infrastructure, including columnar storage (Cassandra) and graph storage (Titan).
</p>
</td>
</tr>


<tr>
<td>
<a href="http://www.fliptop.com/">Fliptop</a>
</td>
<td>
<p>
Fliptop is a customer intelligence platform which allows customers to integrating their contacts, and campaign data, to enhance their prospect with social identities, and to find their best leads, and most influential customers. We have been using Storm for various tasks which requires scalability and reliability, including integrating with sales/marketing platform, data appending for contacts/leads, and computing scoring of contacts/leads. It's one of our most robust and scalable infrastructure.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.trovit.com/">Trovit</a>
</td>
<td>
<p>
Trovit is a search engine for classified ads present in 39 countries and different business categories (Real Estate, Cars, Jobs, Rentals, Products and Deals). Currently we use Storm to process and index ads in a distributed and low latency fashion. Combined with other technologies like Hadoop, Hbase and Solr has allowed us to build a scalable and low latency platform to serve search results to the end user.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.openx.com/">OpenX</a>
</td>
<td>
<p>
OpenX is a unique platform combines ad serving, a real-time bidding (RTB) exchange, yield optimization, and content valuation to deliver the highest revenue across every desktop, tablet, and mobile screen
At OpenX we use Storm to process large amounts of data to provide real time Analytics. Storm provides us to process data real time to improve our Ad quality.
</p>
</td>
</tr>


<tr>
<td>
<a href="http://keen.io/">Keen IO</a>
</td>
<td>
<p>
"Keen IO is an analytics backend-as-a-service. The Keen IO API makes it easy for customers to do internal analytics or expose analytics features to their customers. Keen IO uses Storm (DRPC) to query billion-event data sets at very low latencies. We also use Storm to control our ingestion pipeline, sourcing data from Kafka and storing it in Cassandra.
</p>
</td>
</tr>

<tr>
<td>
<a href="http://www.mercadolibre.com/">MercadoLibre</a>
</td>
<td>
</td>
</tr>


</table>