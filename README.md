MetaSchema
==========


MetaSchema is a Data Definition Language specification.

Design goals
------------

Schemata must

- Be language/platform agnostic
- Allow re-use and composition


Key elements/concepts
---------------------

- Physical Datatype
- Logical Datatype
- Storage Engine
- Presentation Widget
- Validator
- Entity
- Attribute
- Scenario

Physical Datatype
-----------------

Physical Datatypes are **primitive** datatypes supported by:

- Programming Languages, eg. Java, PHP, Javascript, etc.
- Database Systems (relational, object oriented, NoSQL, etc)
- Serialization Data Formats, eg. JSON, XML, etc.

List of Physical Datatypes:

- Char
- String
- Integer
- Double
- Boolean
- Date
- Datetime
- Time

Datatypes in database systems:
- MySQL Datatypes - http://dev.mysql.com/doc/refman/5.0/en/data-types.html
- Sql Server Data Types - http://msdn.microsoft.com/en-us/library/ms187752.aspx

Datatypes in programming languages:
- Java Primitive Datatypes - http://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html
- PHP Types - http://www.php.net/manual/en/language.types.php
- Javascript Datatypes - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures

Datatypes in data formats:
- JSON Datatypes - http://en.wikipedia.org/wiki/JSON#Data_types.2C_syntax_and_example

References
----------

- Entity–attribute–value model - http://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model
- Generic data model - http://en.wikipedia.org/wiki/Generic_data_model
- Three schema approach - http://en.wikipedia.org/wiki/Three_schema_approach
- Putting Semi-structured Data to Practice - homes.cs.washington.edu/~alon/cikm98.ppt‎
- The GMAP: a versatile tool for physical data independence - http://www.vldb.org/journal/VLDBJ5/60050101.pdf
