<div align="center">
	<div>
		<img width="300" src="/awesome-logo.png" alt="Awesome Bigtable">
	</div>
    <br />
	<p>
		:zap: Delightful list of <a href="https://cloud.google.com/bigtable/">Google Bigtable</a> resources, packages and interesting finds.
	</p>
	<br>
	<img src="https://awesome.re/badge.svg" alt="Awesome List">
</div>

---

# Awesome Bigtable

[Bigtable](https://cloud.google.com/bigtable) is a fully managed, scalable NoSQL database service for large analytical and operational workloads, built and managed by Google.

## Contents

- [Tools](#tools)
  - [Client-Libraries](#client-libraries)
  - [Command-line](#command-line)
  - [Emulators](#emulators)
  - [Databases](#databases)
- [Resources](#resources)
  - [Articles & Blogs](#articles--blogs)
  - [Tutorials](#tutorials)
- [Cool Stuff](#cool-stuff)
  - [Inspired by Bigtable](#inspired-by-bigtable)
  - [Interesting Projects](#interesting-projects)

---

If you are new to Bigtable I'd recommend checking out the [Bigtable Documentation](https://cloud.google.com/bigtable/docs/). The docs are a great place to start, as you can view a full list of integrations, tutorials and other treats. This list is meant to be a curated list of awesome Bigtable "things" to supplement any official documentation.

## Tools
A curated list of tools that will help you when working with or building on-top of Bigtable.

### Client-Libraries
- [C++](https://github.com/GoogleCloudPlatform/google-cloud-cpp/tree/master/google/cloud/bigtable) - Official implementation of the Google Cloud Bigtable C++ client.
- [C#](https://github.com/googleapis/google-cloud-dotnet) - Official implementation of the Google Cloud Bigtable .NET client.
- [Node.js](https://github.com/googleapis/nodejs-bigtable) - Official implementation of the Google Cloud Bigtable Node.js client.
- [Python](https://github.com/googleapis/python-bigtable) - Official implementation of the Google Cloud Bigtable python client.
- [HappyBase](https://github.com/googleapis/google-cloud-python-happybase) - Official client which uses a HappyBase emulation layer which uses Bigtable as the underlying storage layer.
- [Java](https://github.com/googleapis/java-bigtable) - Official implementation of the Google Cloud Bigtable Java client.
- [HBase Java](https://github.com/GoogleCloudPlatform/cloud-bigtable-client) - Official Java libraries and HBase client extensions for accessing Google Cloud Bigtable.
- [Go](https://github.com/googleapis/google-cloud-go/tree/master/bigtable) - Official implementation of the Google Cloud Bigtable Go client.
- [PHP](https://github.com/googleapis/google-cloud-php-bigtable) - Official implementation of the Google Cloud Bigtable PHP client.
- [Simple Bigtable](https://github.com/spotify/simple-bigtable) - Java based client built and maintained by Spotify.
- [Rust Bigtable](https://github.com/durch/rust-bigtable) - Rust library for working with Google Bigtable Data API.
- [AsyncBigtable](https://github.com/OpenTSDB/asyncbigtable) - Implementation of AsyncHBase but on top of Google's Cloud Bigtable service.

### Command-line
- [cbt](https://cloud.google.com/bigtable/docs/cbt-overview) - Official command-line interface for performing several different operations on Cloud Bigtable. 
- [btcli](https://github.com/takashabe/btcli) - CLI client for the Bigtable with auto-completion.

### Emulators
- [Google Emulator](https://cloud.google.com/bigtable/docs/emulator) - Official in-memory emulator for Cloud Bigtable, included with the Google Cloud SDK.
- [Spotify Docker Bigtable](https://github.com/spotify/docker-bigtable) - Docker container with an in memory implementation of Google Cloud Bigtable.
- [Shopify Bigtable Emulator](https://github.com/Shopify/bigtable-emulator) - In memory Go implementation of Bigtable.
- [LittleTable](https://github.com/steveniemitz/littletable) - In-memory JVM-based emulator for Bigtable.

### Databases
- [Heroic](https://github.com/spotify/heroic) - Scalable time series database based on Bigtable, Cassandra, and Elasticsearch.
- [Janusgraph](https://github.com/JanusGraph/janusgraph) - Open-source, distributed graph database that can use Bigtable as its storage layer.
- [GeoMesa](https://github.com/locationtech/geomesa) - Suite of tools for working with big geo-spatial data in a distributed fashion, that can leverage Bigtable as its backend.
- [GeoWave](https://github.com/locationtech/geowave) - Tool that provides geospatial and temporal indexing on top of Accumulo, HBase, Bigtable, Cassandra, and DynamoDB.
- [HGraphDB](https://github.com/rayokota/hgraphdb) - Client layer for using HBase (Bigtable) as a graph database.
- [OpenTSDB](https://github.com/GoogleCloudPlatform/opentsdb-bigtable) - An Open Source Time Series Data Base that can levearge Bigtable as its storage layer.
- [Cattle DB](https://github.com/wuttem/cattledb) - Timeseries store built on top of Bigtable.
- [YildizDB](https://github.com/yildizdb/yildiz) - Graph database layer on top of Bigtable.

## Resources
A curated list of resources to help you get off the ground with Bigtable.

### Articles & Blogs
- [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) - Published on 2006.
- [A NoSQL massively parallel table](https://www.cs.rutgers.edu/~pxk/417/notes/content/bigtable.html) - Published on 2011-11.
- [How we moved our Historical Stats from MySQL to Bigtable with zero downtime](https://www.fastly.com/blog/how-we-moved-our-historical-stats-from-mysql-bigtable-zero-downtime) - Published on 2017-07.
- [Medium @duhroach](https://medium.com/@duhroach) - Bigtable centric posts by Colt McAnlis, DA @ Google.
  - [Cloud Bigtable Performance 101](https://medium.com/@duhroach/cloud-bigtable-performance-101-8bf884bc1d1c) - Published on 2018-11.
  - [The right Cloud Bigtable index makes all the difference.](https://medium.com/@duhroach/the-right-cloud-bigtable-index-makes-all-the-difference-3bcabe9bd65a) - Published on 2019-1.
  - [Cloud Bigtable : Getting the geography right](https://medium.com/@duhroach/cloud-bigtable-getting-the-geography-right-645577216516) - Published on 2019-1.
  - [Using Cloud Bigtable Monitoring UI](https://medium.com/@duhroach/using-cloud-bigtable-monitoring-ui-40d3f4c726d6) - Published on 2019-1.
- [Bigtable: storing Protobuf bytes in one column vs splitting the content into column families/qualifiers](https://tech.travelaudience.com/bigtable-storing-protobuf-bytes-in-one-column-vs-splitting-the-content-into-column-families-c231bdff8db7) - Published on 2018-1.
- [Using Google Cloud Emulators in Integration Tests](https://medium.com/google-cloud/using-google-cloud-emulators-for-integration-tests-7812890ebe0d) - Published on 2017-6.
- [The Joy and Pain of using Google Bigtable](https://syslog.ravelin.com/the-joy-and-pain-of-using-google-bigtable-4210604c75be) - Published on 2019-1.

### Tutorials
- [Google Tutorials for Bigtable](https://cloud.google.com/bigtable/docs/tutorials) - List of official tutorials related to Bigtable. 
- [Cloud Bigtable Examples](https://github.com/GoogleCloudPlatform/cloud-bigtable-examples) - Repo containing official examples of using Bigtable.
- [Introduction to Google Cloud Bigtable](https://cloudacademy.com/course/introduction-to-google-cloud-bigtable/) - CloudAcademy provided intro tutorial to Bigtable (membership required).

## Cool Stuff
A list of cool things related to Bigtable.

### Inspired by Bigtable
- [Apache Cassandra](http://cassandra.apache.org/) - Highly-scalable partitioned row store.
- [Apache HBase](https://hbase.apache.org/) - The Hadoop database, a distributed, scalable, big data store.
- [Apache Accumulo](https://github.com/apache/accumulo) - Sorted, distributed key/value store that provides robust, scalable data storage and retrieval.
- [Tera](https://github.com/baidu/tera) - High performance distributed NoSQL database.
- [obigstore](https://github.com/mfp/obigstore) - Database with Bigtable-like data model atop LevelDB.

### Interesting Projects
- [YildizDB Bigtable](https://github.com/yildizdb/bigtable) - TypeScript Bigtable Client with 🔋🔋included.
- [Bigtable Autoscaler](https://github.com/spotify/bigtable-autoscaler) - Service that autoscales Bigtable clusters based on CPU load.

<!--lint ignore no-emphasis-as-heading-->
**Awesome mentioned badge**

If your package or repository is mentioned in this list feel free to add the Awesome mentioned badge to your README.md.

```md
[![Mentioned in Awesome Bigtable](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/zrosenbauer/awesome-bigtable)
```

---

**Logo Source:** https://logomakr.com/4gLK5l
