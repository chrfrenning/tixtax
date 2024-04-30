# tixtax

Just a utility to calculate some currency rates and gains.

1. Export transactions from Fidelity into transactions.csv
2. Run the notebook, e.g. using GitHub Codespaces, to download the USD-NOK exchange rate for purchase and sale dates
3. Doublecheck stuff, then do tax calculations and reporting
4. Don't push your changes to GitHub unless you want your tax report public (forks are public unless you perform some magic)

## Where to find the data

Export data from this place in Fidelity, then copy the year's transactions into transactions.csv.

![Fidelity Export](fidelity_export.png)

You can use the Export button and read the entire file, a cell lets you filter last years transactions

## Remember

* Remember Norwegian tax law requires first-in-first-out when reporting. 
* And that I'm not a tax lawyer. 
* And that this may have bugs.