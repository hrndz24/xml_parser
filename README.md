**XML Parser**

The application is made to parse an xml-file that stores information about objects of specific subject field.
For validation there is a corresponding xsd-schema.
The document can be parsed with DOM, SAX and StAX parsers.
   
The file is to be loaded via a web-browser through a web-page with the parser choice.
Parsing results are displayed on the web-page as a table. 

Task requirements:
* usage of *required* & *optional* for attributes;
* enumerations;
* patterns;
* usage of ID type;
* default attribute values;
* usage of date-time;
* xml-file should not contain less than 16 entities;
* parsers should be organised with *Builder* pattern;
* for logging use Log4J2;
* the code should be covered with tests.

The field: ***Post cards***

Attributes:
* theme;
* type (congratulatory, promotional, casual);
* country (of production);
* year (of production);
* author (if known);
* sending date;
* value (historical, collectible, thematic).

The root element is called *oldCards*
