# Frequenze relative nel dramma tedesco: Sturm und Drang e Klassik a confronto

Progetto di Rebecca Zani, Master in Digital Humanities, Università degli Studi di Milano (2026-2027).

L'analisi confronta il lessico di 54 drammi tedeschi: 32 dello **Sturm und Drang** (SD) e 22 della **Klassik**. Per ogni lemma calcola la frequenza relativa nelle due classi e individua le parole distintive di ciascuna con tre misure: il rapporto P(w|c)/P(w), il log-likelihood di Dunning (G²) e il log₂ ratio. Il notebook misura anche due tratti formali, la quota di versi e l'uso delle elisioni.

La relazione completa, con metodo, risultati e limiti, è in [docs/Frequenze_relative_SD_Klassik.pdf](docs/analisi_notebook_output.pdf).

## Struttura del repository

<pre>
├── frequenza_relativa_SD_Klassizismus_lessico.ipynb
├── GerDraCor SD Klassik/
│   ├── SD/          
│   └── Klassik/    
├── risultati_frequenza/   
├── docs/analisi_notebook_output.pdf
├── README.md
  
</pre>

## Corpus

I testi provengono da [GerDraCor](https://github.com/dracor-org/gerdracor), il German Drama Corpus del progetto DraCor, in open access. I file TEI sono riportati senza modifiche e divisi in due sottocartelle, una per corrente.



