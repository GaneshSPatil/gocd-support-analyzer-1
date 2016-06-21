======

#GoCD Thread Information Analysis Tool

    Gocd-support-analyzer is a support-log analysis tool.

  It analyzes the api/support JSON information to figure out:
  * the groups of threads with same stack trace.
  * the synchronizers information about locked, waiting and held-by threads.

**Usage**
  * Open [gocd-support-analyzer/index.html](https://github.com/gocd/gocd-support-analyzer/blob/master/index.html) file in browser.
  * Paste the JSON content available at api/support endpoint in the provided textarea.
  * Hit Analyze.
