# E-coli-str-K-12
DNA Sequence Analysis of E. coli (K-12)



📌 Overview
This project performs a basic bioinformatics analysis of a DNA sequence from E. coli (K-12 strain) using Python. It reads a sequence file, analyzes nucleotide composition, and visualizes the results.
The goal is to demonstrate how biological data can be processed and analyzed using simple Python tools.


🎯 Objectives
Read DNA sequence data from a FASTA file
Extract key sequence information
Count nucleotide frequencies (A, T, G, C)
Visualize nucleotide distribution using a bar chart


🛠️ Technologies Used
Python
Biopython
Pandas
Matplotlib


📂 Project Workflow
1. Data Input
Upload a DNA sequence file (.fasta) using Google Colab or local environment.

2. Sequence Reading
Use Biopython (SeqIO) to:
Read the sequence file
Extract sequence ID
Determine sequence length
Preview initial bases

3. Data Processing
Count occurrences of:
Adenine (A)
Thymine (T)
Guanine (G)
Cytosine (C)


4. Data Storage
Store nucleotide counts in a structured table using Pandas DataFrame.


6. Data Visualization
Generate a bar chart using Matplotlib to display nucleotide composition.
