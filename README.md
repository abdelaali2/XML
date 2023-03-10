# XML

Day 1 Exercise:
    
    • Design a configuration file for a library:
        - Info of library consists of a location, a description of the library, a librarian and a lot of books.
        - Each book has title, ISBN, and Author The book contains also a preface and many of parts.
        - Each part has title and contains many of chapters.
        - Each chapter has title and contains a summary and many of sections.
        - Sections contain the content of the book as paragraphs.

    • Design a DTD of the configuration file for the library that you made.
        - External DTD
        - In DTD:
            • Define elements with occurrence indicators.
            • Define attribute with different types (CDATA, enumerated, ...) & with different behavior (required, optional).
            • Define external entity.

Day 2 Exercise:

    • Create XML Schema to the following XML doc:
        <WeekDay>valid-values</WeekDay>
        where its valid values are:
            - Integer range "from 1 to 7".
            - a string "Saturday | Sunday | …….. | Thursday".
    
    • Design a schema of the configuration file for the library that you made.
        Note:
            - In schema:
                • Use Simple type.
                • Use complex type (Simple content, Complex content).
                • Group (attribute).

    • Consider the case where we need to Convert the following BookStore.dtd file to the XML Schema syntax:
        i.
            <!ELEMENT BookStore (Book)+>
            <!ELEMENT Book (Title, Author, Date, ISBN, Publisher)>
            <!ELEMENT Title (#PCDATA)>
            <!ELEMENT Author (#PCDATA)>
            <!ELEMENT Date (#PCDATA)>
            <!ELEMENT ISBN (#PCDATA)>
            <!ELEMENT Publisher (#PCDATA)>

        ii.
            <!ELEMENT BookStore (Book+)>
            <!ELEMENT Book (Title, Author)>
            <!ATTLIST Book Category (science | fiction) "fiction" InStock (true | false) "false">
            <!ELEMENT Title (#PCDATA)>
            <!ELEMENT Author (#PCDATA)>
            
Day 3 Exercise:

    • Using: cd catalog.xml, Write a suitable XPath Expression for following use cases:
        - Select all the CD's titles with price more than 10$
        - Select all the CDs that came before 1990
        - Select the titles and prices of all the CDs from "UK"
        - Select the artists names in the CDs that came before "Dolly Parton" 's CD
        - Select the titles of all the CDs after the "Private Dancer" CD

    • Design a configuration file for a library:
        - Info. of library consists of a location, a description of the library, a librarian and a lot of books.
        - Each book has title, ISBN, and Author.
        - The book contains also a preface and many of parts.
        - Each part has title and contains many of chapters.
        - Each chapter has title and contains a summary and many of sections.
        - Sections contain the content of the book as paragraphs.