# simple-DNA-Tm-calculator

This is a small summer project that calculates the **CG content** of a DNA sequence and estimates its **melting temperature (Tm)** using the **Wallace rule**.

My goal is to practice basic bioinformatics and Python skills before starting a dual-degree program in **Life Sciences and Computer Science**.
I previously did PASS, the selective first-year medical program in France, but decided to change direction. During that year, I learned about the Wallace rule and chose to apply it here.


## Features

- Counts the number of **C** and **G** bases in a DNA sequence.
- Calculates the **CG content** as a percentage.
- Estimates the **melting temperature (Tm)** using the **Wallace formula**:
  

## About the Tm calculation

This project uses the **simplified Wallace formula** to estimate the DNA melting temperature (Tm):

Tm = 2°C × (A + T) + 4°C × (G + C)

This is a quick and easy estimation method suitable for short DNA sequences and standard conditions. It does not account for factors like salt concentration or sequence length beyond 20 bases.
