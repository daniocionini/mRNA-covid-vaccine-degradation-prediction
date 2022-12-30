# Covid-19 mRNA Vaccine Degradation Prediction
Model development to predict likely degradation rates at each base of an RNA molecule

*As part of a competition on <a href="https://www.kaggle.com/">Kaggle.</a>*<br>

<img height="500" src="https://github.com/daniocionini/mRNA-covid-vaccine-degradation-prediction/blob/main/coronavirus-curevac-rna-cepi.jpg"/>

## Project Overview
**mRNA vaccines** have taken the lead as the fastest vaccine candidates for COVID-19, but currently, they face key potential limitations. One of the biggest challenges right now is how to design super stable messenger RNA molecules (mRNA). Conventional vaccines (like your seasonal flu shots) are packaged in disposable syringes and shipped under refrigeration around the world, but that is not currently possible for mRNA vaccines.

Researchers have observed that RNA molecules have the tendency to spontaneously degrade. This is a serious limitation--a single cut can render the mRNA vaccine useless. Currently, little is known on the details of where in the backbone of a given RNA is most prone to being affected. Without this knowledge, current mRNA vaccines against COVID-19 must be prepared and shipped under intense refrigeration, and are unlikely to reach more than a tiny fraction of human beings on the planet unless they can be stabilized.

## Project Objective
Develop a model to predict likely degradation rates at each base of an RNA molecule, trained on a subset of an Eterna dataset comprising over 3000 RNA molecules (which span a panoply of sequences and structures) and their degradation rates at each position.

## References
### Data Used
The data comes from the **National 2009 H1N1 Flu Survey (NHFS)**.

>The National 2009 H1N1 Flu Survey (NHFS) was sponsored by the National Center for Immunization and Respiratory Diseases (NCIRD) and conducted jointly by NCIRD and the National Center for Health Statistics (NCHS), Centers for Disease Control and Prevention (CDC). The NHFS was a list-assisted random-digit-dialing telephone survey of households, designed to monitor influenza immunization coverage in the 2009-10 season.<br>
<br>The target population for the NHFS was all persons 6 months or older living in the United States at the time of the interview. Data from the NHFS were used to produce timely estimates of vaccination coverage rates for both the monovalent pH1N1 and trivalent seasonal influenza vaccines.
<a href="https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Datasets/nis/nhfs/nhfspuf_readme.txt">National 2009 H1N1 Flu Survey Public-Use Data File Readme</a>

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Scikit-learn

## Getting Started
### Cloning the repository
Use the <a href="https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository">tutorial</a> provided.<br>

### Raw Data
The datasets can be found <a href="https://www.drivendata.org/competitions/66/flu-shot-learning/page/210/">here</a>


![alt text](https://media0.giphy.com/media/LaVp0AyqR5bGsC5Cbm/giphy.gif?cid=790b761127b602110641413a4158b121329f65abb5979c7b&rid=giphy.gif&ct=g)
