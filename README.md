=======

**Thread Dump Analysis Tool**

Gocd-support-analyzer is a gocd server's support-log anlysis tool.

It analyzes the api/support-json information to figure out:
  * the groups of threads with same Stack Trace
  * the Synchronizers information about locked, waiting and held-by threads

##Usage
  * Open [gocd-support-analyzer/index.html](https://github.com/gocd/gocd-support-analyzer/blob/master/index.html) page in browser.
  * Paste the JSON response of api/support endpoint.
  * Hit Analyze.