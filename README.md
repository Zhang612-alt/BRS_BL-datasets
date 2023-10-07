# BRS_BL-datasets
Our dataset is constructed based on traditional datasets, where each project consists of four tables that record prefix comments, predefined fields, the main body, and content related to bug localization.

In the comments table, the primary information includes bug_id, comments, author(commenters), and date.

The "predefined fields" correspond to the predefined information found on the original Bugzilla web page.

The "main body" primarily contains information related to titles and description.

The last table is similar to the classic dataset, with the only difference being that "buggy_paths" is determined based on the removal of files marked as "add" in the articles, while "old_buggy_paths" contains the content from the original dataset.



We have publicly released four datasets mentioned in the paper, each of which represents a subset of bug reports.

| Project | Number of Bug Reports |
| ------- | --------------------- |
| Tomcat  | 355                   |
| SWT     | 1986                  |
| Eclipse | 3287                  |
| JDT     | 2592                  |



The dataset is stored in SQL format, and you can use **Navicat** to execute the SQL file.
