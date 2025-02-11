# aws-developer-associate-notes

<main>

        <p>This is a collection of cheat sheets for the AWS Developer Associate.<br>
                Click on the links below to browse the detailed cheat sheets by AWS service:</p>
        <ul>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-analytics-dva/">AWS
                                Analytics</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-application-integration-dva/">AWS
                                Application Integration</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-compute-dva/">AWS
                                Compute&nbsp;</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-database-dva/">AWS
                                Database</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-developer-tools-dva/">AWS
                                Developer Tools</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-management-tools-dva/">AWS
                                Management Tools</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-networking-content-delivery-dva/">AWS
                                Networking &amp; Content Delivery</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-security-identity-compliance-dva/">AWS
                                Security Identity &amp; Compliance</a></li>
                <li><a href="https://digitalcloud.training/category/aws-cheat-sheets/aws-developer-associate/aws-storage-dva/">AWS
                                Storage</a></li>
        </ul>

        <h1>
                Amazon Kinesis
        </h1>
        <div class="entry-content single">

                <div class="wp-block-image">
                        <figure class="alignright is-resized"><img loading="lazy" decoding="async"
                                        src="https://digitalcloud.training/wp-content/uploads/2022/01/Amazon-Kinesis-.jpg"
                                        alt="Amazon Kinesis Services" class="wp-image-316399" width="375" height="188"
                                        srcset="https://digitalcloud.training/wp-content/uploads/2022/01/Amazon-Kinesis-.jpg 750w, https://digitalcloud.training/wp-content/uploads/2022/01/Amazon-Kinesis--300x150.jpg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/Amazon-Kinesis--400x200.jpg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/Amazon-Kinesis--624x312.jpg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/Amazon-Kinesis--600x300.jpg 600w"
                                        sizes="(max-width: 375px) 100vw, 375px"></figure>
                </div>

                <p>Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can
                        get timely insights and react quickly to new information.</p>

                <p>Kinesis is a collection of services for processing streams of various data.</p>

                <p>Data is processed in “shards” – with each shard able to ingest 1000 records per second.</p>

                <p>There is a default limit of 500 shards, but you can request an increase to unlimited shards.</p>

                <p>A record consists of a partition key, sequence number, and data blob (up to 1 MB).</p>

                <p>Transient data store – default retention of 24 hours but can be configured for up to 7 days.</p>

                <p>There are four types of Kinesis service, and these are detailed below.</p>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="1024" height="255"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2.png" alt=""
                                class="wp-image-296578"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2.png 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2-300x75.png 300w, https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2-768x191.png 768w, https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2-400x100.png 400w, https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2-624x155.png 624w, https://digitalcloud.training/wp-content/uploads/2022/01/word-image-2-600x149.png 600w"
                                sizes="(max-width: 1024px) 100vw, 1024px"></figure>

                <h2 class="wp-block-heading"><span id="kinesis-video-streams"><a
                                        id="post-296569-_andk006dgseq"></a>Kinesis Video Streams</span></h2>

                <p>Kinesis Video Streams makes it easy to securely stream video from connected devices to AWS for
                        analytics, machine learning (ML), and other processing.</p>

                <p>Durably stores, encrypts, and indexes video data streams, and allows access to data through
                        easy-to-use APIs.</p>

                <p>Producers provide data streams.</p>

                <p>Stores data for 24 hours by default, up to 7 days.</p>

                <p>Stores data in shards – 5 transaction per second for reads, up to a max read rate of 2MB per second
                        and 1000 records per second for writes up to a max of 1MB per second.</p>

                <p>Consumers receive and process data.</p>

                <p>Can have multiple shards in a stream.</p>

                <p>Supports encryption at rest with server-side encryption (KMS) with a customer master key.</p>

                <p>Kinesis Video Streams does not appear much on AWS exams.</p>

                <div class="adplugg-tag" data-adplugg-zone="all_access_membership_body" data-adplugg-regid="0"
                        data-adplugg-processed="true">
                        <!-- Powered by AdPlugg <www.adplugg.com> Copyright (c) 2025 AdPlugg -->
                        <div id="adplugg-placement-0-8399" class="adplugg-placement" data-adplugg-refresh-count="0">
                                <div class="adplugg-ad adplugg-image-ad" id="adplugg-ad-b99cai8g6oou0"
                                        data-adplugg-ad="80907">
                                        <div class="adplugg-image-wrapper"> <a
                                                        href="https://www.adplugg.com/track/click/A48221584/80907/click?toi=21584&amp;hn=digitalcloud.training&amp;bu=%2Famazon-kinesis%2F&amp;rf=https%3A%2F%2Fdigitalcloud.training%2Fcategory%2Faws-cheat-sheets%2Faws-developer-associate%2Faws-analytics-dva%2F&amp;zn=16423&amp;pm=8399&amp;ct=&amp;next="
                                                        target="_blank" rel="nofollow"> <img
                                                                src="https://cdn4.adplugg.io/apusers/serve/A48221584/file/120110/PLANS_300x250_3.png"
                                                                width="300" height="250"> </a> </div>
                                </div>
                        </div><!-- AdPlugg End -->
                </div>

                <h2 class="wp-block-heading"><span id="kinesis-data-streams"><a
                                        id="post-296569-_s4wugea8kpo"></a>Kinesis Data Streams</span></h2>

                <p>Kinesis Data Streams enables you to build custom applications that process or analyze streaming data
                        for specialized needs.</p>

                <p>Kinesis Data Streams enables real-time processing of streaming big data.</p>

                <p>Kinesis Data Streams is useful for rapidly moving data off data producers and then continuously
                        processing the data.</p>

                <p>Kinesis Data Streams <strong>stores data</strong> for later processing by applications (key
                        difference with Firehose which delivers data directly to AWS services).</p>

                <p>Common use cases include:</p>

                <ul class="wp-block-list">
                        <li>Accelerated log and data feed intake.</li>
                        <li>Real-time metrics and reporting.</li>
                        <li>Real-time data analytics.</li>
                        <li>Complex stream processing.</li>
                </ul>

                <p>The diagram below illustrates the high-level architecture of Kinesis Data Streams.</p>

                <ul class="wp-block-list">
                        <li>Producers continually push data to Kinesis Data Streams.</li>
                        <li>Consumers process the data in real time.</li>
                        <li>Consumers can store their results using an AWS service such as Amazon DynamoDB, Amazon
                                Redshift, or Amazon S3.</li>
                        <li>Kinesis Streams applications are consumers that run on EC2 instances.</li>
                        <li>Shards are uniquely identified groups or data records in a stream.</li>
                        <li>Records are the data units stored in a Kinesis Stream.</li>
                </ul>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="881" height="258"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1.jpg" alt=""
                                class="wp-image-297409"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1.jpg 881w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1-300x88.jpg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1-768x225.jpg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1-400x117.jpg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1-624x183.jpg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-1-600x176.jpg 600w"
                                sizes="(max-width: 881px) 100vw, 881px"></figure>

                <p>A producer creates the data that makes up the stream.</p>

                <p>Producers can be used through the following:</p>

                <ul class="wp-block-list">
                        <li>Kinesis Streams API.</li>
                        <li>Kinesis Producer Library (KPL).</li>
                        <li>Kinesis Agent.</li>
                </ul>

                <p>A record is the unit of data stored in a Amazon Kinesis data stream.</p>

                <p>A record is composed of a sequence number, partition key, and data blob.</p>

                <p>By default, records of a stream are accessible for up to 24 hours from the time they are added to the
                        stream (can be raised to 7 days by enabling extended data retention).</p>

                <p>A data blob is the data of interest your data producer adds to a data stream.</p>

                <p>The maximum size of a data blob (the data payload before Base64-encoding) within one record is 1
                        megabyte (MB).</p>

                <p>A shard is the base throughput unit of an Amazon Kinesis data stream.</p>

                <p>One shard provides a capacity of 1MB/sec data input and 2MB/sec data output.</p>

                <p>Each shard can support up to 1000 PUT records per second.</p>

                <p>A stream is composed of one or more shards.</p>

                <p>The total capacity of the stream is the sum of the capacities of its shards.</p>

                <p>Kinesis Data Streams supports resharding, which lets you adjust the number of shards in your stream
                        to adapt to changes in the rate of data flow through the stream.</p>

                <p>There are two types of resharding operations: shard split and shard merge.</p>

                <ul class="wp-block-list">
                        <li>In a shard split, you divide a single shard into two shards.</li>
                        <li>In a shard merge, you combine two shards into a single shard.</li>
                </ul>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="1024" height="211"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards.jpeg"
                                alt="Amazon Kinesis Splitting and Merging Shards" class="wp-image-296584"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards.jpeg 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards-300x62.jpeg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards-768x158.jpeg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards-400x82.jpeg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards-624x129.jpeg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-splitting-and-merging-shards-600x124.jpeg 600w"
                                sizes="(max-width: 1024px) 100vw, 1024px"></figure>

                <p>Splitting increases the number of shards in your stream and therefore increases the data capacity of
                        the stream.</p>

                <p>Splitting increases the cost of your stream (you pay per-shard).</p>

                <p>Merging reduces the number of shards in your stream and therefore decreases the data capacity—and
                        cost—of the stream.</p>

                <p>Consumers are the EC2 instances that analyze the data received from a stream.</p>

                <p>Consumers are known as Amazon Kinesis Streams Applications.</p>

                <p>When the data rate increases, add more shards to increase the size of the stream.</p>

                <p>Remove shards when the data rate decreases.</p>

                <p>Partition keys are used to group data by shard within a stream.</p>

                <p>Kinesis Streams uses KMS master keys for encryption.</p>

                <p>To read from or write to an encrypted stream the producer and consumer applications must have
                        permission to access the master key.</p>

                <p>Kinesis Data Streams replicates synchronously across three AZs.</p>

                <h2 class="wp-block-heading"><span id="kinesis-data-firehose">Kinesis Data Firehose</span></h2>

                <p>Kinesis Data Firehose is the easiest way to load streaming data into data stores and analytics tools.
                </p>

                <p>Captures, transforms, and loads streaming data.</p>

                <p>Enables near real-time analytics with existing business intelligence tools and dashboards.</p>

                <p>Kinesis Data Streams can be used as the source(s) to Kinesis Data Firehose.</p>

                <p>You can configure Kinesis Data Firehose to transform your data before delivering it.</p>

                <p>With Kinesis Data Firehose you don’t need to write an application or manage resources.</p>

                <p>Firehose can batch, compress, and encrypt data before loading it.</p>

                <p>Firehose synchronously replicates data across three AZs as it is transported to destinations.</p>

                <p>Each delivery stream stores data records for up to 24 hours.</p>

                <p>A source is where your streaming data is continuously generated and captured.</p>

                <p>A delivery stream is the underlying entity of Amazon Kinesis Data Firehose.</p>

                <p>A record is the data of interest your data producer sends to a delivery stream.</p>

                <p>The maximum size of a record (before Base64-encoding) is 1000 KB.</p>

                <p>A destination is the data store where your data will be delivered.</p>

                <p>Firehose Destinations include:</p>

                <ul class="wp-block-list">
                        <li>Amazon S3.</li>
                        <li>Amazon Redshift.</li>
                        <li>Amazon Elasticsearch Service.</li>
                        <li>Splunk.</li>
                </ul>

                <p>Producers provide data streams.</p>

                <p>No shards, totally automated.</p>

                <p>Can encrypt data with an existing AWS Key Management Service (KMS) key.</p>

                <p>Server-side-encryption can be used if Kinesis Streams is used as the data source.</p>

                <p>Firehose can invoke an AWS Lambda function to transform incoming data before delivering it to a
                        destination.</p>

                <p>For Amazon S3 destinations, streaming data is delivered to your S3 bucket. If data transformation is
                        enabled, you can optionally back up source data to another Amazon S3 bucket:</p>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="862" height="234"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2.jpg" alt=""
                                class="wp-image-297415"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2.jpg 862w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2-300x81.jpg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2-768x208.jpg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2-400x109.jpg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2-624x169.jpg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/Kinesis-2-600x163.jpg 600w"
                                sizes="(max-width: 862px) 100vw, 862px"></figure>

                <p>For Amazon Redshift destinations, streaming data is delivered to your S3 bucket first. Kinesis Data
                        Firehose then issues an Amazon Redshift <strong>COPY</strong> command to load data from your S3
                        bucket to your Amazon Redshift cluster. If data transformation is enabled, you can optionally
                        back up source data to another Amazon S3 bucket:</p>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="1024" height="332"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination.jpeg"
                                alt="Amazon Kinesis Data Firehose RedShift Destination" class="wp-image-296590"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination.jpeg 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination-300x97.jpeg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination-768x249.jpeg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination-400x130.jpeg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination-624x202.jpeg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-redshift-destination-600x195.jpeg 600w"
                                sizes="(max-width: 1024px) 100vw, 1024px"></figure>

                <p>For Amazon Elasticsearch destinations, streaming data is delivered to your Amazon ES cluster, and it
                        can optionally be backed up to your S3 bucket concurrently:</p>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="1024" height="436"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina.jpeg"
                                alt="Amazon Kinesis Data Firehose Elasticsearch Destination" class="wp-image-296593"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina.jpeg 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina-300x128.jpeg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina-768x327.jpeg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina-400x170.jpeg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina-624x266.jpeg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-elasticsearch-destina-600x255.jpeg 600w"
                                sizes="(max-width: 1024px) 100vw, 1024px"></figure>

                <p>For Splunk destinations, streaming data is delivered to Splunk, and it can optionally be backed up to
                        your S3 bucket concurrently:</p>

                <h2 class="wp-block-heading"><img loading="lazy" decoding="async" class="alignnone wp-image-296596"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination.jpeg"
                                alt="Amazon Kinesis Data Firehose Splunk Destination" width="750" height="294"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination.jpeg 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination-300x118.jpeg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination-768x302.jpeg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination-400x157.jpeg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination-624x245.jpeg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-data-firehose-splunk-destination-600x236.jpeg 600w"
                                sizes="(max-width: 750px) 100vw, 750px"><a id="post-296569-_qu934ipo7jrm"></a></h2>

                <h2 class="wp-block-heading"><span id="kinesis-data-analytics">Kinesis Data Analytics</span></h2>

                <p>Amazon Kinesis Data Analytics is the easiest way to process and analyze real-time, streaming data.
                </p>

                <p>Can use standard SQL queries to process Kinesis data streams.</p>

                <p>Provides real-time analysis.</p>

                <p>Use cases:</p>

                <ul class="wp-block-list">
                        <li>Generate time-series analytics.</li>
                        <li>Feed real-time dashboards.</li>
                        <li>Create real-time alerts and notifications.</li>
                </ul>

                <p>Quickly author and run powerful SQL code against streaming sources.</p>

                <p>Can ingest data from Kinesis Streams and Kinesis Firehose.</p>

                <p>Output to S3, RedShift, Elasticsearch and Kinesis Data Streams.</p>

                <p>Sits over Kinesis Data Streams and Kinesis Data Firehose.</p>

                <p>A Kinesis Data Analytics application consists of three components:</p>

                <ul class="wp-block-list">
                        <li>Input – the streaming source for your application.</li>
                        <li>Application code – a series of SQL statements that process input and produce output.</li>
                        <li>Output – one or more in-application streams to hold intermediate results.</li>
                </ul>

                <p>Kinesis Data Analytics supports two types of inputs: streaming data sources and reference data
                        sources:</p>

                <ul class="wp-block-list">
                        <li>A streaming data source is continuously generated data that is read into your application
                                for processing.</li>
                        <li>A reference data source is static data that your application uses to enrich data coming in
                                from streaming sources.</li>
                </ul>

                <p>Can configure destinations to persist the results.</p>

                <p>Supports Kinesis Streams and Kinesis Firehose (S3, RedShift, Elasticsearch) as destinations.</p>

                <p>IAM can be used to provide Kinesis Analytics with permissions to read records from sources and write
                        to destinations.</p>

                <h2 class="wp-block-heading"><span id="kinesis-client-library"><a
                                        id="post-296569-_2ho0qa20krxz"></a>Kinesis client library</span></h2>

                <p>Kinesis Client Library is a Java library that helps read records from a Kinesis Stream with
                        distributed applications sharing the read workload.</p>

                <p>The KCL is different from the Kinesis Data Streams API that is available in the AWS SDKs.</p>

                <ul class="wp-block-list">
                        <li>The Kinesis Data Streams API helps you manage many aspects of Kinesis Data Streams
                                (including creating streams, resharding, and putting and getting records).</li>
                        <li>The KCL provides a layer of abstraction specifically for processing data in a consumer role.
                        </li>
                </ul>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="1024" height="358"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library.jpeg"
                                alt="Amazon Kinesis Client Library" class="wp-image-296599"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library.jpeg 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-300x105.jpeg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-768x269.jpeg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-400x140.jpeg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-624x218.jpeg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-600x210.jpeg 600w"
                                sizes="(max-width: 1024px) 100vw, 1024px"></figure>

                <p>The KCL acts as an intermediary between your record processing logic and Kinesis Data Streams.</p>

                <p>When you start a KCL application, it calls the KCL to instantiate a worker. The KCL performs the
                        following tasks:</p>

                <ul class="wp-block-list">
                        <li>Connects to the stream.</li>
                        <li>Enumerates the shards.</li>
                        <li>Coordinates shard associations with other workers (if any).</li>
                        <li>Instantiates a record processor for every shard it manages.</li>
                        <li>Pulls data records from the stream.</li>
                        <li>Pushes the records to the corresponding record processor.</li>
                        <li>Checkpoints processed records.</li>
                        <li>Balances shard-worker associations when the worker instance count changes.</li>
                        <li>Balances shard-worker associations when shards are split or merged.</li>
                </ul>

                <p>The KCL ensures that for every shard there is a record processor.</p>

                <p>Manages the number of record processors relative to the number of shards &amp; consumers.</p>

                <p>If you have only one consumer, the KCL will create all the record processors on a single consumer.
                </p>

                <p>Each shard is processed by exactly one KCL worker and has exactly one corresponding record processor,
                        so you never need multiple instances to process one shard.</p>

                <p>However, one worker can process any number of shards, so it’s fine if the number of shards exceeds
                        the number of instances.</p>

                <figure class="wp-block-image"><img loading="lazy" decoding="async" width="1024" height="381"
                                src="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors.jpeg"
                                alt="Amazon Kinesis Client Library Record Processors" class="wp-image-296602"
                                srcset="https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors.jpeg 1024w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors-300x112.jpeg 300w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors-768x286.jpeg 768w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors-400x149.jpeg 400w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors-624x232.jpeg 624w, https://digitalcloud.training/wp-content/uploads/2022/01/amazon-kinesis-client-library-record-processors-600x223.jpeg 600w"
                                sizes="(max-width: 1024px) 100vw, 1024px"></figure>

                <p>If you have two consumers it will load balance and create half the processors on one instance and
                        half on another.</p>

                <p>Scaling out consumers:</p>

                <ul class="wp-block-list">
                        <li>With KCL, generally you should ensure that the number of instances does not exceed the
                                number of shards (except for failure or standby purposes).</li>
                        <li>Each shard can be read by only one KCL instance.</li>
                        <li>You never need multiple instances to handle the processing of one shard.</li>
                </ul>

                <p>However, one worker can process multiple shards.</p>

                <p>Example:</p>

                <ul class="wp-block-list">
                        <li>4 shards = max 4 KCL instances.</li>
                        <li>6 shards = max 6 KCL instances.</li>
                </ul>

                <p>Progress is checkpointed into DynamoDB (IAM access required).</p>

                <p>KCL can run on EC2, Elastic Beanstalk, and on-premises servers.</p>

                <p>Records are read in order at the shard level.</p>

                <h2 class="wp-block-heading"><span id="security"><a id="post-296569-_1p1z92rabdsq"></a>Security</span>
                </h2>

                <p>Control access / authorization using IAM policies.</p>

                <p>Encryption in flight using HTTPS endpoints.</p>

                <p>Encryption at rest using KMS.</p>

                <p>Possible to encrypt / decrypt data on the client side.</p>

                <p>VPC endpoints available for Kinesis to access within a VPC.</p>

                <h2 class="wp-block-heading"><span id="sqs-vs-sns-vs-kinesis"><a id="post-296569-_prynwec0i4pt"></a>SQS
                                vs SNS vs Kinesis</span></h2>

                <p>SQS:</p>

                <ul class="wp-block-list">
                        <li>Consumers pull data.</li>
                        <li>Data is deleted after being consumed.</li>
                        <li>Can have as many workers (consumers) as you need.</li>
                        <li>No need to provision throughput.</li>
                        <li>No ordering guarantee (except with FIFO queues).</li>
                        <li>Individual message delay.</li>
                </ul>

                <p>SNS:</p>

                <ul class="wp-block-list">
                        <li>Push data to many subscribers.</li>
                        <li>Up to 10,000,000 subscribers.</li>
                        <li>Data is not persisted (lost if not deleted).</li>
                        <li>Pub/sub.</li>
                        <li>Up to 10,000,000 topics.</li>
                        <li>No need to provision throughput.</li>
                        <li>Integrates with SQS for fan-out architecture pattern.</li>
                </ul>

                <div class="adplugg-tag" data-adplugg-zone="all_access_membership_end_of_the_article_desk_"
                        data-adplugg-regid="1" data-adplugg-processed="true">
                        <!-- Powered by AdPlugg <www.adplugg.com> Copyright (c) 2025 AdPlugg -->
                        <div id="adplugg-placement-1-8400" class="adplugg-placement" data-adplugg-refresh-count="0">
                                <div class="adplugg-ad adplugg-image-ad" id="adplugg-ad-tekuodbr3qjqj"
                                        data-adplugg-ad="60494">
                                        <div class="adplugg-image-wrapper"> <a
                                                        href="https://www.adplugg.com/track/click/A48221584/60494/click?toi=21584&amp;hn=digitalcloud.training&amp;bu=%2Famazon-kinesis%2F&amp;rf=https%3A%2F%2Fdigitalcloud.training%2Fcategory%2Faws-cheat-sheets%2Faws-developer-associate%2Faws-analytics-dva%2F&amp;zn=16425&amp;pm=8400&amp;ct=&amp;next="
                                                        target="_blank" rel="nofollow"> <img
                                                                src="https://cdn4.adplugg.io/apusers/serve/A48221584/file/120113/PLANS_A.png"
                                                                width="728" height="90"> </a> </div>
                                </div>
                        </div><!-- AdPlugg End -->
                </div>
                <div class="adplugg-tag" data-adplugg-zone="all_access_membership_end_of_the_article_mob_"
                        data-adplugg-regid="2" data-adplugg-processed="true">
                        <!-- Powered by AdPlugg <www.adplugg.com> Copyright (c) 2025 AdPlugg -->
                        <div id="adplugg-placement-2-8399" class="adplugg-placement" data-adplugg-refresh-count="0">
                                <div class="adplugg-ad adplugg-image-ad" id="adplugg-ad-r7kcc2tamd8nm"
                                        data-adplugg-ad="60492">
                                        <div class="adplugg-image-wrapper"> <a
                                                        href="https://www.adplugg.com/track/click/A48221584/60492/click?toi=21584&amp;hn=digitalcloud.training&amp;bu=%2Famazon-kinesis%2F&amp;rf=https%3A%2F%2Fdigitalcloud.training%2Fcategory%2Faws-cheat-sheets%2Faws-developer-associate%2Faws-analytics-dva%2F&amp;zn=16424&amp;pm=8399&amp;ct=&amp;next="
                                                        target="_blank" rel="nofollow"> <img
                                                                src="https://cdn4.adplugg.io/apusers/serve/A48221584/file/120105/PLANS_300x250_1.png"
                                                                width="300" height="250"> </a> </div>
                                </div>
                        </div><!-- AdPlugg End -->
                </div>

                <p>Kinesis:</p>

                <ul class="wp-block-list">
                        <li>Consumers pull data.</li>
                        <li>As many consumers as you need.</li>
                        <li>Possible to replay data.</li>
                        <li>Meant for real-time big data, analytics, and ETL.</li>
                        <li>Ordering at the shard level.</li>
                        <li>Data expires after X days.</li>
                        <li>Must provision throughput.</li>
                </ul>
                <!-- relpost-thumb-wrapper -->
                <div class="relpost-thumb-wrapper">
                        <!-- filter-class -->
                        <div class="relpost-thumb-container">
                                <h3>Related posts:</h3><!-- related_posts_thumbnails -->
                                <ul id="related_posts_thumbnails">
                                        <li><a href="https://digitalcloud.training/aws-iam/"><img loading="lazy"
                                                                decoding="async" class="relpost-post-image"
                                                                alt="Amazon AWS IAM Services"
                                                                src="https://digitalcloud.training/wp-content/uploads/2022/01/AWS-IAM-300x150.jpg"
                                                                width="300" height="300"></a><a
                                                        href="https://digitalcloud.training/aws-iam/"
                                                        class="relpost_content"><span
                                                                class="rpth_list_content"></span></a></li>
                                        <li><a href="https://digitalcloud.training/aws-systems-manager/"><img
                                                                loading="lazy" decoding="async"
                                                                class="relpost-post-image"
                                                                alt="Amazon AWS Systems Manager Services"
                                                                src="https://digitalcloud.training/wp-content/uploads/2022/01/AWS-Systems-Manager-300x150.jpg"
                                                                width="300" height="300"></a><a
                                                        href="https://digitalcloud.training/aws-systems-manager/"
                                                        class="relpost_content"><span
                                                                class="rpth_list_content"></span></a></li>
                                        <li><a href="https://digitalcloud.training/aws-elastic-beanstalk/"><img
                                                                loading="lazy" decoding="async"
                                                                class="relpost-post-image"
                                                                alt="Amazon AWS Elastic Beanstalk Services"
                                                                src="https://digitalcloud.training/wp-content/uploads/2022/01/AWS-Elastic-Beanstalk-300x150.jpg"
                                                                width="300" height="300"></a><a
                                                        href="https://digitalcloud.training/aws-elastic-beanstalk/"
                                                        class="relpost_content"><span
                                                                class="rpth_list_content"></span></a></li>
                                </ul><!-- close related_posts_thumbnails -->
                                <div style="clear: both"></div>
                        </div><!-- close filter class -->
                </div><!-- close relpost-thumb-wrapper -->
        </div>
</main>