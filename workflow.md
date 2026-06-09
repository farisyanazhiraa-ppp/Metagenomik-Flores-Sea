# Workflow Analisis Metagenomik Flores Sea

## 1. Data Acquisition
Spesies dominan diperoleh dari penelitian mikrobioma Flores Sea.

## 2. Sequence Retrieval
Sekuens gen 16S rRNA dari masing-masing spesies diunduh dari NCBI GenBank dalam format FASTA.

Spesies:
- Pseudoalteromonas lipolytica
- Marinobacter nauticus
- Pseudomonas mendocina
- Halopseudomonas aestusnigri
- Flavobacterium beibuense
- Flavobacterium rakeshii

## 3. Quality Control
Sekuens diperiksa untuk memastikan berasal dari gen 16S rRNA dan memiliki panjang sekitar 1400–1500 bp.

## 4. FASTA Merging
Seluruh sekuens digabung menjadi satu file FASTA.

## 5. Multiple Sequence Alignment
Alignment dilakukan menggunakan algoritma MUSCLE pada software MEGA 11 (software sejenis Clustal Omega).

## 6. Phylogenetic Analysis
Pohon filogenetik dibangun menggunakan metode Neighbor-Joining dengan bootstrap 1000 replikasi.

## 7. Interpretation
Hubungan kekerabatan antar bakteri dianalisis berdasarkan topologi pohon filogenetik dan nilai bootstrap.
