# LatinToFrench

Short personal project to see how historical phonetic changes in a language could be modelised. 

## How it works

The user inputs a Latin word, dividing it into syllables and using phonetic symbols, and indicates which of the syllables is stressed. 
The word is then modified according to phonetic changes that are believed to have happened in Vulgar Latin during the 1st century AD.
After each step, an updated phonetic representation of the word is returned. 

If expanded, the project would hopefully end up returning a modern Romance language word (provided the original word chosen did evolve into one). 

## Examples

Here is a list of words that already show certain interesting changes, along with their modern French evolution and, when applicable, derived English word.

| Original word  | Syllable transcription | Stressed syllable | 1st century pronunciation | French evolution | English derived word |
| -------------- | ---------------------- | ----------------- | ------------------------- | ---------------- | -------------------- |
| Vineam         | vi / ne / am           | 1                 | /vinja/                   | Vigne */vinj/*   | A vine               |
| Colapum        | ko / la / pum          | 1                 | /kolpu/                   | Coup */ku/*      |                      |
| Cohortem       | ko / hor / tem         | 2                 | /korte/                   | Cour */kur/*     | A court              |
| Tabulam        | ta / bu / lam          | 1                 | /tabla/                   | Table */tabl/*   | A table              |
| Maledicere     | ma / le / di / ke / re | 3                 | /maldikre/                | Maudire */modir/*|                      |
| Caelum         | kae / lum              | 1                 | /kelu/                    | Ciel */sjel/*    |                      |
| Stabulam       | sta / bu / lam         | 1                 | /istabla/                 | Etable */etabl/* | A stable             |
| Computare      | kom / pu / ta / re     | 3                 | /komptare/                | Compter */kɔ̃te/* | To count, compute    |
| Insulam        | in / su / lam          | 1                 | /isla/                    | Ile */i:l/*      | An isle              |
