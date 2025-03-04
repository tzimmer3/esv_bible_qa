# Data Preparation
This document describes the approach to collecting an ESV version of the bible.


## Acquisition

### Bible Text

Scraped from biblegateway.com.


### Subsections inside of books

Scraped from biblestudystart.com.









-----



This describes the extraction and processing steps to go from .pdf to structured text.


## Extraction

Used .pdfplumber to extract text from the document.

Assumptions
- First 36 pages are discarded
    - Page 37 is the start of Genesis

- Each Book begins with a data dictionary with hyperlinks for each chapter.

- Section heads are included and are accompanied with a <b>page break</b>.
    - Naturally seem to correspond to the beginning of chapters


## Possible Approach

Might use the KJV bible that is already structured to reference verse numbers, chapters, etc. to ensure accuracy.