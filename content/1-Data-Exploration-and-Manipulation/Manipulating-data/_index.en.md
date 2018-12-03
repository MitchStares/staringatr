---
title: Manipulating data
weight: 10
---

As previously mentioned, one of the extremely useful and time saving parts of R is manipulating your data without touching your original spreadsheet. Manipulating your data within the R environment allows us to generate entirely new datasets based off our raw data, without modifying the original document. This means no more multi-sheet excel workbooks, no more opening excel to generate a new column, this can all be done in R. This is really beneficial when collaborating with other researchers, group members or supervisors since all we are required to do is send the raw data sheet and the R document. They can follow the code to see what is happening and run everything directly from the original data.  

Manipulation of data can be done with the base R language (everything we have done so far) or with packages in the **Tidyverse** library, such as **"dplyr"** and **"tidyr"**. `**Tidyverse** simplifies the language of coding and offers powerful tools for data manipulation and graphing.  

{{% notice note %}}
**Make sure you have loaded tidyverse with the `library()` command before attempting any functions.**  
{{% /notice %}}  

For the rest of the course from here on out, there will be many arguments of functions that will be left out. If you want to learn about other customisation options for your code, or are lost at any point, use the **"Help"** tab in R studio or type **"?"** followed by the name of the function.
e.g. ?rename.  

Otherwise, the internet is a awesome resource for R help.  

### Content:
{{%children description="true"   %}}