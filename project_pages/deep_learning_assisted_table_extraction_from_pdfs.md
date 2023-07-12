<h2>Deep-learning-assisted table extraction from PDFs</h2>

### Summary

I worked as a Civic Digital Fellow for the U.S. Census Bureau in the summer of 2023.  I contributed to their Frames Program, an effort begun in 2019 to link data across a gamut of contexts to better inform policymaking and research, enhance data discoverability, and reduce false matches.

<i>Franchise Disclosure Documents</i> are one of the many sources that feed into Census Bureau databases.  These are a rich source of franchisee rosters (eg a table containing all McDonald's establishments in the world).  However, these documents are PDF files and have significant variation in formatting and stylization.  As a result, the Census Bureau had previously been extracting franchise roster information by hand, which can take hours for a single brand.

I'm currently building an end-to-end pipeline to transform these PDF files into tables that are exactly formatted for the Census Bureau's purposes.  Because the files are so varied and lack internal structure, I've used a combination of natural language processing and more basic approaches to extract and format the information we need.

So far, the largest hurdle of the project has been inferring column names when they can't be recovered from a table.  To meet this challenge, I've been training a large language model to infer column names using the data found in the cells that belong to that column.  Because it's important that neural networks in government be made to a high standard of care and bias testing, I'm taking steps to minimize bias, such as running rigorous bias tests and ensuring that US Island Areas are represented in the dataset.

![Before and after](/images/projects/deep_learning_assisted_table_extraction_from_pdfs/before_and_after.png)

### Skills gained

Through this fellowship, I've gained experience working in a large organization such as a government agency, and proactively reach beyond existing silos to access information in other groups of employees with whom I might not otherwise have contact.  I've also learned best practices for contending with the lack of structure in PDF files.
