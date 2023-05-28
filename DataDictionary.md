# Data Engineering Capstone - US Immigration Data

# **Data Dictionary Dimension Tables**
## codes (Country ISO Code Data)
 * id: integer (nullable = true) - Country unique ISO code consisting of 3 digits
 * name : string (nullable = true) - Country name
 
## df_demo (U.S. Demographic by State)
 * State: string (nullable = true)-Full state name
 * state_code: string (nullable = true)- State code

## full_code (georef-united-states-of-america-zc-point@public.csv)
 * Official USPS State Code: string (nullable = true) - State code
 * Official State Name: string (nullable = true) - State full name

# Fact Table german (US i94 Immigration Dataset)
 * cic_id: integer (nullable = true) - A unique identifier assigned to each individual record in the dataset.
 * i94mon: integer (nullable = true) - The numeric month of the visitor's arrival in the United States.
 * i94res: integer (nullable = true) - The visitor's country of residence in ISO code format.
 * i94addr: string (nullable = true) - The state where the visitor intends to reside in the United States (State Code).
 * visatype: string (nullable = true) - The type of visa that a non-immigrant visitor used to enter the United States.

