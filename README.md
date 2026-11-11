# Power BI Course for Beginners

## watch here:
[Watch the Power BI course on Google Drive](https://drive.google.com/drive/folders/1bYwtfWTYwwfH22LRP8U0HZA8Ul-lxwPV)

This is the Power BI module of the **Past Hundred Data Analysis course**. It takes you from importing your first dataset in Power BI Desktop to building a sales report, writing DAX measures, and publishing a report to the Power BI Service.

Start with the [four-page course outline](docs/power-bi-course-outline.pdf). Follow the course in order and pause to reproduce each demonstration in Power BI Desktop. The [practice files](datasets-parts-01-06/README.md) and the two project folders are organized by the stage where you use them.

<!-- Add the public course-video or playlist link here. -->

## 1. Getting started and connecting to data

- Get familiar with Power BI Desktop and the basics of charts and data visualization.
- Review the practice data and the questions you’ll work through.
- Connect to a CSV file and an SQL database.
- Load files from a folder and connect to an XML file.

## 2. Preparing data in Power Query

**Inspect the data.** Get familiar with the Power Query Editor and check your data before transforming it. Use Column Quality, Column Distribution, and Column Profile to understand what’s in each column.

**Combine tables.** Learn when to append rows and when to merge tables using matching columns. Practice both operations in Power Query.

**Reshape and clean the data.** Manage rows and columns, split columns, replace values, and group rows. Work through what pivoting and unpivoting do, then perform both transformations. Use Extract, text formatting, and transformations for numbers, dates, and times.

**Add new columns.** Create a column from examples and build custom, conditional, and index columns.

## 3. Building a data model

- Navigate Model View, the Data pane, and the Properties pane.
- Create and modify relationships between tables.
- Understand cardinality, which describes how rows match across tables, and cross-filter direction, which controls how filters propagate.
- Identify fact and dimension tables and compare star and snowflake schemas.

## 4. Writing DAX formulas

Learn DAX (Data Analysis Expressions) syntax, operators, and functions. Compare **row context** and **filter context**, then create a calculated column and a measure so you can see how each is evaluated.

| Topics | Functions covered |
| --- | --- |
| Dates and calendars | `CALENDAR`, `DATE`, `MONTH`, `WEEKDAY`, `WEEKNUM` |
| Formatting and text | `FORMAT`, `CONCATENATE`, `LEFT`, `RIGHT`, `LEN`, `MID` |
| Aggregations | `SUM`, `MIN`, `MAX`, `AVERAGE`, `COUNT`, `PRODUCT` |
| Iterators | `SUMX`, `MINX`, `MAXX`, `AVERAGEX`, `COUNTX`, `PRODUCTX` |
| Table filtering | `FILTER` |

## 5. Building Power BI visuals

Start with chart basics, create report visuals in Power BI, and progress to the advanced chart demonstration. The capstone uses visuals to answer questions about product performance and sales over time.

## 6. Applying the workflow in the capstone

The [Project Builders capstone](project-01/README.md) starts with business requirements and ends with a report in the Power BI Service.

1. Load the data into Power BI Desktop. Profile the source tables and apply the transformations the report needs.
2. Identify primary and foreign keys, check relationship cardinality, and build a star schema. Review the completed model.
3. Set up the report filters and use DAX where the requirements call for it.
4. Build the top and bottom five product views by **sales, quantity, and profit**. Show how sales change over time.
5. Use **Edit interactions** to control which visuals respond to a selection. Check how a slicer based on a dimension table filters the report.
6. Review the report against the business requirements, then follow the demonstration on publishing to the Power BI Service.

## 7. Practicing with SNEAKERS and Saleswear

Use the [SNEAKERS and Saleswear project](project-02-sneakers-and-saleswear/README.md) to practice with a second dataset. Explore sales by brand, product, country, and payment method, and build a monthly trend from the transaction dates.

## Finding your course files

Follow the recordings in this order. The topic sections above give you the detail within each part.

| Recording or project | Focus |
| --- | --- |
| 01 | Introduction and data import |
| 02–03 | Data preparation in Power Query |
| 04 | Adding columns in Power Query |
| 05 | Data modeling |
| 06 | Data visualization |
| 07 | DAX introduction |
| 08–09 | Optional DAX practice |
| 10 | Project Builders capstone |
| 11 | SNEAKERS and Saleswear |

| Material | Where to start |
| --- | --- |
| Printable syllabus | [Power BI course outline](docs/power-bi-course-outline.pdf) |
| Files for the early lessons | [Datasets for Parts 01–06](datasets-parts-01-06/README.md) |
| Project 1 | [Project Builders capstone guide](project-01/README.md) |
| Project 2 | [SNEAKERS and Saleswear project guide](project-02-sneakers-and-saleswear/README.md) |

If you have access to the original course folder, follow the numbered recordings there. Some exercises require source files provided separately by the instructor.
