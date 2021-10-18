# User-Facing Backend
## Cursor Methods and Aggregation Equivalents
The way that we limit the number of results that are returned by a cursor is with this dot.limit method.
And we specify an integer value for the number of documents that we want back in the cursor so that when we do iterate through the cursor, we can be sure that there are no more than two documents in it.