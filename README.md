# P-LCommentary

Currently an inprogress projection. I am working on a way to automate our P&L commetaries for our MTD, QTD and YTD finacial data. The goal of this project is we take our finacial data and create the commentary on the slide deck for those who have to create this deck monthly for our VP of FP&A, all the way up to our CFO. This uses a set of variables we create in this notebook to write out our commentary in a specific specific format. 

An example line from the commentary slide deck shows how this will look: 

Comments vs. Projection
Sales +$XM favorable to PIIIa on a CC basis
MSNT: +$XM favorable to Projection on a CC basis, driven by Division1 +$XM, Division2 +$XM, Division3 +$XM, Division4 +$XM. Slightly offset by Division5 ($XM) and Division6 ($XM) 


We do most of the formating to output this via email in Azure logic apps, but the rest of the Pyspark code in databricks gets us to a point where we can do that.


Note: Some data is taken out/replaced for privacy reasons
