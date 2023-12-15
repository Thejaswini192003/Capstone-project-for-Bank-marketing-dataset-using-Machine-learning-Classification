**Data Description:**

 The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact with the same client was required, to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 
             
**VARIABLES:**

1 - age (numeric)

2 - job: type of job (categorical: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "Services") 

3 - marital: marital status (categorical: "married", "divorced", "single"; note: "divorced" means divorced or widowed) 

4 - education (categorical: "unknown", "secondary", "primary", "tertiary") 

5 - default: has credit in default? (binary: "yes", "no") 

6 - balance: average yearly balance, in euros (numeric) 

7 - housing: has a housing loan? (binary: "yes", "no") 

8 - loan: has a personal loan? (binary: "yes", "no")

9 - contact: contact communication type (categorical: "unknown", "telephone", "cellular") 

10 - day: last contact day of the month (numeric) 

11 - month: last contact month of the year (categorical: "Jan", "Feb", "mar", ..., "Nov", "Dec") 

12 - duration: last contact duration, in seconds (numeric)

13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes the last contact) 

14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means the client was not previously contacted) 

15 - previous: number of contacts performed before this campaign and for this client (numeric)

16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")

OUTPUT VARIABLE:

 17 -y: has the client subscribed to a term deposit? (binary: "yes", "no")
