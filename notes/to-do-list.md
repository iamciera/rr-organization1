##01-file-organization
- **DONE:** Add learning objectives to `01-file-organization.md`

### Activity 1
- Forensic Science - Give the students collection of files: cryptic, similar file names to different files, poorly named, "superFINAL3.doc", spreadsheet format from really old excel or numbers, some graph images. Have them figure out whats going on. What's the raw data file, what's the script for the analysis. (Courtney, Kristina)
- **TODO:** Make instructor guidelines on how to run activity and add to `instructors.md`
- **TODO:** Figure out how to disseminate files. 
- **DONE:** Make folder full of disorganized files from gapminder dataset

### Lecture (Jenny - @jennybc)

- algorithmic thinking (input vs. output, intermediate or derived = output AND input, something that converts input to output)
- file naming (self-documentation, pay attention to implications for sorting)
- data is raw (neither overwrite nor duplicate)
- minimal input and output
- file formats (text non proprietary, file extensions)
- Concluding Discussion: is A better than B? why? here's C ... how could you improve it?
- **TODO:** Create lecture.  

##02-programatic-modification

- **DONE:** Make instructor guidelines on how to run activity and add to `instructors.md`
- **DONE:** Add learning objectives to `02-programatic-modification.md'*

### Activity 2 (Naupaka - @naupaka)

- Broken excel data sheet: Show typical spreadsheet (`oceania_broken.xlsx`) and have students document changes they see as necessary before having it ready for analysis (writing each step in a text file) . Then go through all fixes needed and discuss why each is important.
- Take away: If you can design away deficiences in data collection, DO! If too late for that, consider if this is a "one-time" cleaning or a potentially repeated task. Protip: it's probably the latter. Best practice is to clean with a script, not point and click.
- **DONE:** Make small subset of gapminder data (Oceania)
- **DONE:** Break spreadsheet in excel and document problems (for instructors)
- Hands-on (Activity 2). Fix the broken excel data sheet. Everyone take notes on how to document
- Demonstrate export to .csv
- [Link to Excel data carpentry lesson]()

## 03-literate-programming - R via RStudio 

- **NEED:** Find out if they've seen this IDE earlier and to what extent
- **TODO:** Jenny re: lecture; rest will wait to see concrete details on what group 1 produces re: an Rmd file)
    - [Link to work in progress](https://github.com/Reproducible-Science-Curriculum/rr-organization1/blob/master/lecture02_literate-programming-via-rmarkdown.md).
- **TODO:** Make slides on literature programming and knitr, working through Rmd file they used in the first session
- **DONE:** Make interactive knitr document
- **TODO:** Make instructor guidelines on how to run activity and add to `instructors.md`
- Slides on what is literate program
- simple `.R` script, e.g. import data, filter to one country, make a plot and write it to file
- commenting that script (Why selecting sweden, not what the subset function is doing)
- same actions but embedded in `.Rmd`
- run both using interactive run, whole file source, Preview/Knit HTML
- note what sorts of outputs are left behind
- Wrap-up activity: which files can we delete and reproduce? Which files are inputs, outputs, converters of inputs to outputs?

## Links relevant to items above

#### UBC Library Research Data Management has good resources

- File Naming Conventions & Best Practices <http://researchdata.library.ubc.ca/organize/>
- File Format Considerations <http://researchdata.library.ubc.ca/format/>Links from Jenny relevant to our outline

#### Naming practices

- ISO 8601 standard for dates <http://en.wikipedia.org/wiki/ISO_8601>
- File naming guides and suggestions
    - http://www.exadox.com/en/articles/file-naming-convention-ten-rules-best-practice
    - http://www.mnhs.org/preserve/records/electronicrecords/erfnaming.php
    - http://www.recordsmanagement.ed.ac.uk/InfoStaff/RMstaff/RMprojects/PP/FileNameRules/FileNameRules.htm
    - http://www.recordsmanagement.ed.ac.uk/InfoStaff/RMstaff/RMprojects/PP/FileNameRules/Rules.htm
- Filename extension conventions <http://en.wikipedia.org/wiki/List_of_file_formats>

#### Spreadsheet advice

- Spreadsheet advice from UK's Government Statistical Service Good Practice Team [PDF](https://gss.civilservice.gov.uk/wp-content/uploads/2012/12/Releasing-statistics-in-spreadsheets-Good-practice-guidance.pdf)

#### Paper with lots of good tips

- Nine simple ways to make it easier to (re)use your data by EP White, E Baldridge, ZT Brym, KJ Locey, DJ McGlinn, SR Supp. Ideas in Ecology and Evolution 6(2): 1–10, 2013. [doi:10.4033/iee.2013.6b.6.f] (http://library.queensu.ca/ojs/index.php/IEE/article/view/4608). See the section "Use standard table formats".

## LICENSE and ATTRIBUTION  

- Gapminder data [available here](http://www.gapminder.org/data/). [Gapminder data is licensed CC-BY 3.0](https://docs.google.com/document/pub?id=1POd-pBMc5vDXAmxrpGjPLaCSDSWuxX6FLQgq5DhlUhM#h.ul2gu2-uwathz).
- Processed data via [@jennybc](https://github.com/jennybc), [R package available here](https://github.com/jennybc/gapminder). The [data-raw](https://github.com/jennybc/gapminder/tree/master/data-raw) sub-directory reveals the journey from Gapminder.org's Excel workbooks to increasingly clean and tidy data.
    - cleanest data is in [07_gap-every-five-years.tsv](https://github.com/jennybc/gapminder/blob/master/data-raw/07_gap-every-five-years.tsv)
    - this gives rise to the data.frame provided by the R package

