# dczaj_SNP
This Repo is supposed to help out with some -somewhat unscientific - DNA Analysis

####

The file snp_to_summary.csv contains a list of -"randomly"- selected conditions and illnesses that according to https://www.snpedia.com/ result from the respectivly listed Single-nucleotide polymorphism. All information was manually taken from https://www.snpedia.com/. I can neither guarantee that I didn't make an error copying the Data nor that https://www.snpedia.com/ has perfectly accurate information.

If you worry about your health please consult with a medical professional.

From personal experience I can confirm that rs4988235 has been medically confirmed with me when I was a child but that is just one SNP so take it with a grain of salt.


analysis.ipynb is a python notebook that uses pandas and sqlite3 to create a local database file from the snp_to_summary.csv and A DNA Raw file from e.g. Ancestry. It then joins the Data via an SQL query and creates a text file that dumps your -assumed -" medical impacts" based on your DNA Data for your SNP and the values on allele1 and allele2.
You can make changes in the .ipynb to match it to your raw DNA file. for my Ancestry Export I had to ignore the first 18 rows (skiprows=18) your milage may varry if you use RAW DNA data from 23andme or other websites.
As always keep in mind that when sequencing your DNA there could have been errors and thus you results might vary.

As mentioned before, if you worry about your health please consult a medical professional.

I do not have any medical background and cannot provide any insight in your results - I only create a small SNP list and a script that joines them with DNA Data.
