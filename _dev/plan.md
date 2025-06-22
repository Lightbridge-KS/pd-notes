# Planning

Here is the topics I'd like to cover integrating tidyverse comparisons throughout each chapter rather than having separate sections.

## Outline for `pd-notes`

### Basics

- **Data types in pandas** 
  - Compare with R's types (numeric, character, factor, etc.)
  - Quick conversion reference
- **Series Basics**
  - Series as R vectors
  - Key methods with tidyverse equivalents
- **DataFrame Basics**
  - DataFrame vs tibble
  - Index concept (the main difference from R)
  - Method chaining setup

### Data Manipulation
- **Selecting Columns** 
  - `select()` → various pandas methods
  - Common selection patterns
- **Filtering Rows** 
  - `filter()` → boolean indexing, query()
  - Practical filtering recipes
- **Creating & Transforming Columns** 
  - `mutate()` → assign(), direct assignment
  - Common transformations
- **Grouping & Aggregation** 
  - `group_by() + summarize()` → groupby() + agg()
  - Window functions comparison
- **Arranging & Sorting** 
  - `arrange()` → sort_values()
  - Multi-column sorting patterns
- **Pivoting Data** 
  - `pivot_wider/longer()` → pivot(), melt()
  - Quick reshape recipes
- **Joining DataFrames** 
  - `*_join()` → merge(), join()
  - Join type mapping table

### Advanced Operations
- **String Operations** 
  - `stringr` → .str accessor
  - Common string patterns
- **DateTime Operations** 
  - `lubridate` → .dt accessor
  - Frequent datetime tasks
- **Working with Missing Data** 
  - NA handling differences
  - Common cleaning patterns

This structure is perfect for a quick reference! Each topic can have:

1. The tidyverse equivalent at the top
2. 2-3 most common use cases
3. A simple example
4. Any important differences/gotchas