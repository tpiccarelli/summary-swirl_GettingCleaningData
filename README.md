# summary-swirl_GettingCleaningData

1-) Manipulating Data with dplyr
    - Main functions:
        select(): focus on select a subset of COLUMNS
        filter(): focus on select a subset of ROWS
                    when conditions are separated by ",", it means AND; if separated by "|", it means OR
        arrange(): puts data in ascending or descendig order
        mutate(): adds column(s) based on previous existing column data
        summarize(): collapses the dataset to a single row and gives the requested value FOR EACH dataset group

2-) Grouping and Chaining with dplyr
    - Secondary functions:
        group_by()
        n()
        n_distinct()
        mean()
    - chaining operator: %>%
      
3-) Tidying Data with tidyr

        Tidy data must satisfy three conditions:
            1- Each variable forms a column;
            2- Each observation forms a row;
            3- Each type of observational unit forms a table.
    
    - tidyr functions:
        gather(): used when column headers are values or columns are not variables
        separate(): separates data from one column into multiple columns
        spread()
        extract_numeric()
        mutate(extract_numeric())
        select () unique
        bind_rows()

4-) Dates and Times with lubridate
