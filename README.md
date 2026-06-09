# Metagenomik Flores Sea

## Deskripsi
Analisis filogenetik bakteri dominan dari Flores Sea menggunakan gen 16S rRNA.

## Spesies yang Dianalisis
- Pseudoalteromonas lipolytica
- Marinobacter nauticus
- Pseudomonas mendocina
- Halopseudomonas aestusnigri
- Flavobacterium beibuense
- Flavobacterium rakeshii

## Software yang Digunakan
- NCBI GenBank
- MEGA 11
- MUSCLE

## File Repository
- flores_all.fasta → file FASTA gabungan
- flores_aligned.meg → hasil alignment
- Flores_phylogeny.png → pohon filogenetik
- workflow.md → workflow analisis

## Metode
1. Pengambilan data 16S rRNA dari NCBI
2. Penggabungan FASTA
3. Multiple Sequence Alignment (MUSCLE)
4. Analisis filogenetik Neighbor-Joining
5. Bootstrap 1000 replikasi

## Hasil
Flavobacterium beibuense dan Flavobacterium rakeshii membentuk klaster dengan bootstrap 100, menunjukkan hubungan kekerabatan yang sangat dekat.
