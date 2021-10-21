# Bible Cross Reference Database

A collection of *many* cross references in the Bible.

## Why: Motivation

*What motivated me to start the Bible Cross Reference Database?*

## Why: Goal

*What is the goal of the Bible Cross Reference Database?*

## How: Structure

*How is the content in the Bible Cross Reference Database structured?*

### Schema

Content in this database is kept in a CSV file with the headings:

1. "a": The first passage in the cross-reference (the order between "a" and "b" is unimportant)
1. "b": The second passage in the cross-reference (the order between "a" and "b" is unimportant)
1. "description": Description of the nature and significance of the cross-reference
1. "sources": Sources that mention this connection
1. "date-added": [Epoch time](https://en.wikipedia.org/wiki/Unix_time) when we added the cross-reference to the bible-cross-reference-service

### Example

```csv
a,b,description,sources,date-added
Gen.1.1,Isa.65.17,Isa.65.17 describes God's creation of a New Heavens and Earth (after which the first creation (described in Gen.1.1) will not be remembered),"www.openbible.info,foo",1634813255
```

## How: Use and Context

*How is Bible Cross Reference Database designed to be used?*

## Licensing

*How is Bible Cross Reference Database licensed?*
