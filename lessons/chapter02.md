# User-Facing Backend
## Cursor Methods and Aggregation Equivalents
The way that we limit the number of results that are returned by a cursor is with this dot.limit method.
And we specify an integer value for the number of documents that we want back in the cursor so that when we do iterate through the cursor, we can be sure that there are no more than two documents in it.

## Basic Aggregation

## Basic Writes
The two idiomatic methods for inserting documents are insertOne and insertMany.

Trying to insert a duplicate _id will fail.

And as an alternative to inserting a document, an upsert in an update method can be used instead.

## Write Concerns

OVER