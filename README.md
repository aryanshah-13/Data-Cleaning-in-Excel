# Data-Cleaning-in-Excel

The following analysis draws from a comprehensive dataset sourced from the Nova Scotia Open Data Catalogue. The dataset contains multiple variables capturing municipal solid waste curbside collection costs across Nova Scotia. A brief overview of the key columns is provided below:

1.	Identifiers:
  a.	Year – Fiscal year of the data
  b.	Municipality – The municipal unit reporting the data
  c.	Region – The regional grouping the municipality belongs to 
2.	Cost breakdown:
  a.	Garbage/ Recyclables/ Organics – Program costs for each waste stream
  b.	Total cost – Combined cost across all three streams
3.	Service & Population
  a.	Service units – Number of households/ units receiving curbside pickups
  b.	Population – Total population served
4.	Stream metrics 
  a.	Garbage mt – Total garbage collected in metric tonnes
  b.	Recyclables mt – Total recyclables collected in metric tonnes
  c.	Organics mt – Total organics collected in metric tonnes

The data cleaning process aimed to resolve several quality issues present in the raw dataset, including inconsistent municipality naming conventions across reporting years, missing and ambiguous values, placeholder rows containing no meaningful data, and formatting inconsistencies in numeric fields.
Beyond cleaning, the dataset was also processed to derive standardized stream-level metrics for each of the three waste streams: Garbage, Recyclables, and Organics. The four calculated metrics produced for each stream are:

1. Collection volume per service unit (mt/unit)
2. Collection volume per capita (mt/capita)
3. Collection cost per service unit ($/unit)
4. Collection cost per capita ($/capita)

These metrics enable consistent comparison of waste collection efficiency and cost across municipalities and over time
