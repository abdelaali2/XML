# XML

Day 1 Exercise:
    
    • Design a configuration file for a library:
        – Info of library consists of a location, a description of the library, a librarian and a lot of books.
        – Each book has title, ISBN, and Author The book contains also a preface and many of parts.
        – Each part has title and contains many of chapters.
        – Each chapter has title and contains a summary and many of sections.
        – Sections contain the content of the book as paragraphs.

    • Design a DTD of the configuration file for the library that you made.
        – External DTD
        – In DTD:
            • Define elements with occurrence indicators.
            • Define attribute with different types (CDATA, enumerated, ...) & with different behavior (required, optional).
            • Define external entity.

Day 2 Exercise:

    • Create XML Schema to the following XML doc:
        <WeekDay>valid-values</WeekDay>
        where its valid values are:
            – Integer range "from 1 to 7".
            – a string "Saturday | Sunday | …….. | Thursday".