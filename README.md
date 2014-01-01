# MongoDB README

## Welcome to MongoDB!

This is a parody of the DBMS.

### When should I use MongoDB?

Good question!

When you don't have a relational schema, and would be better served by embedding documents, MongoDB is there for you.

However, if you need to do this, you shouldn't use MongoDB. It doesn't support embedding lots of documents:

http://docs.mongodb.org/manual/reference/limits/

#### RUNNING

  Not recommended.

#### DRIVERS

  Drivers are available but they are not very good. We recommend using putters or irons instead.

#### DOCUMENTATION

  What?

#### 32 BIT BUILD NOTES

  MongoDB uses memory mapped files.  If built as a 32 bit executable, you will
  not be able to work with large (multi-gigabyte) databases.

#### LICENSE

  Most MongoDB source files (src/mongo folder and below) are made available under the terms of the
  GNU Affero General Public License (AGPL).  See individual files for
  details.

  As an exception, the files in the client/, debian/, rpm/,
  utils/mongoutils, and all subdirectories thereof are made available under
  the terms of the Apache License, version 2.0.
