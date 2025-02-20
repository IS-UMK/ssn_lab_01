# SSN. Lab. 1. Wprowadzanie do python i notatnika jupyter

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

Notatnik: [01_Wprowadzenie.ipynb](https://github.com/IS-UMK/ssn_lab_01/blob/master/01_Wprowadzenie.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_lab_01/blob/master/01_Wprowadzenie.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_lab_01/master?filepath=01_Wprowadzenie.ipynb) 

---

## Zad. 1. Bramki logiczne

Korzystając z modelu neuronu McCulloch-Pittsa zaimplementuj funkcje realizujące bramki logiczne:
* AND
* OR
* NOT
* NAND <BR> ``a NAND b = NOT(a AND b)``
* XOR <BR> ``a XOR b = (a NAND (a NAND b)) NAND (b NAND (a NAND b))`` <BR> ``a XOR b = ( a AND NOT b )  OR  ( NOT a AND b ) `` <BR> ``a XOR b = (a OR b) AND NOT (a AND b)``

Przetestuj działanie bramek prezentując wyniki dla wszystkich możliwych wartości wejściowych. 

Rozwiązanie w postaci notatnika Jupyter (``.ipynb``) lub skrypt w języku Python (``.py``) umieść w Moodle lub prześlij do repozytorium GitHub.

---
## Materiały:

* [The McCulloch-Pitts Artificial Neuron Model](https://pabloinsente.github.io/the-mcculloch-pitts-artificial-neuron-model) by Pablo Caceres
* [Bramka NAND](https://en.wikipedia.org/wiki/NAND_logic) Wikipedia
* [Bramka XOR](https://en.wikipedia.org/wiki/XOR_gate) Wikipedia
