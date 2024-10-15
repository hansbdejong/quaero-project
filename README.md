# quaero-project

For the course Internet and Web Systems (CIS 555), we implemented a Google-style distributed cloud-based search engine that interacts with users via a frontend and returns relevant search results for the users’ queries. This search engine is built using a web server, key-value store, distributed analytics engine, web crawler, indexer, and a page ranker. All components were built from **scratch** using standard Java.

We individually built the web server, key-value store, distributed analytics engine, crawler, and indexer. We then joined forces in a team of four to build our search engine. We deployed our implementations of the web server, key-value store, and distributed analytics engine on multiple Amazon Web Service EC2 instances in order to crawl and index hundreds of thousands of web pages. We then built a ranker in Java that took into account page rank, term frequency inverse document frequency, and phrase match, which we also hosted on EC2 instances. The frontend was built in React.

Our search results are strong. We received full marks for this project as well as the most extra credit points.

**Skills**: Distributed Systems, Web Server, Key-Value Store, Distributed Analytics Engine, AWS, EC2, Web Crawler, Indexer, Page Rank, TF-IDF, DNS, React, HTML, CSS, JavaScript, Multithreading


### Figure 1:
Search results for "President of the United States". Phrase matching helped improve our results.

<br>

<p align="center">
  <img src="https://github.com/hansbdejong/quaero-project/blob/main/quaero-gifs/president.gif" 
        width="70%" height="70%">
</p>

<br>

### Figure 2:
Search results for "climate change", again demonstrating high quality search results and fast search speeds.

<br>
<p align="center">
  <img src="https://github.com/hansbdejong/quaero-project/blob/main/quaero-gifs/climate-change.gif" 
        width="70%" height="70%">
</p>
<br>

### Figure 3:
Search results for "Tamil Nadu" The great search results for a more obscure query demonstrates that we have a strong corpus of indexed pages.

<br>
<p align="center">
  <img src="https://github.com/hansbdejong/quaero-project/blob/main/quaero-gifs/tamil-nadu.gif" 
        width="70%" height="70%">
</p>
<br>

### Figure 4:

Search results for "asdf asdf". Our search engine handles situations when there are no matching pages.

<br>
<p align="center">
  <img src="https://github.com/hansbdejong/quaero-project/blob/main/quaero-gifs/asdf.gif" 
        width="70%" height="70%">
</p>
<br>

### Figure 5:
Search results for "weather 94110". As an additional feature, we used a weather API (visualcrossing) to show the weather forecast.

<br>
<p align="center">
  <img src="https://github.com/hansbdejong/quaero-project/blob/main/quaero-gifs/weather.gif" 
        width="70%" height="70%">
</p>
<br>

### Figure 6:
Phrase search in action.

<br>
<p align="center">
  <img src="https://github.com/hansbdejong/quaero-project/blob/main/quaero-gifs/phrase-search.gif" 
        width="70%" height="70%">
</p>
<br>




