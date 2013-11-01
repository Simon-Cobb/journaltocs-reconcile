An OpenRefine reconciliation service that queries the API provided by the [JournalTOCs](http://www.journaltocs.ac.uk/api_help.php?subAction=journals) project.

You will need to register for the api at http://www.journaltocs.ac.uk/api_help.php?subAction=journals.

Run as:
~~~~
$ python reconcile.py --debug -u your_api_email@none.com
~~~~

Michael Stephens wrote a [demo reconcilliation service](https://github.com/mikejs/reconcile-demo) that this code is based on.
