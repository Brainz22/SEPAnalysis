# SEP Analysis:
Framework and ongoing efforts of the Statistical Study of the Correlation between Solar Energetic Particles and Properties of Active Regions. Paper found here: https://arxiv.org/pdf/2303.06100.pdf.

# Datasets:

1. `ARDatabase.json` is produced by `ARDatabase.ipynb` and has the Active regions and their information starting from the 1981 until 2021.
2. `DatabaseBest.json` is produced by `BestARdata.ipynb`. Although it the same dataset as (1), it has separate McIntosh Components and a column where the Hale class is specifiec by a Latex-formatted string. This will be helpful when plotting.
3. `SEPlist_full19762022.json` contains information about 267 SEP events. 36 have invalid dates, and 11 have no Active Region number. Thus, we are left with 220 SEP events to work with.

# Run it:
1. Install environment:
<pre>
 conda env create -f Environment.yml 
</pre>
