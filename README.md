🧬 FASTA File Analysis using Shell Scripting

📘 Project Description

This repository contains a comprehensive set of shell scripts for performing essential FASTA file operations in bioinformatics.
It demonstrates how command-line tools and Bash scripting can automate sequence analysis — from calculating GC content to motif detection, filtering, and classification.

🧪 Key Sections
1️⃣ What is FASTA File Analysis?

FASTA files store biological sequence data (DNA, RNA, or protein).
This project shows how to extract useful biological insights from these sequences using Unix/Linux shell scripting — without relying on heavy bioinformatics software.

2️⃣ Objectives of the Project

Automate reading and analysis of FASTA sequences

Use loops, conditionals, and case statements for decision-based outputs

Implement common genomic calculations (GC%, length, motifs, complements)

Separate, classify, and filter sequences efficiently

3️⃣ Part A – Basic FASTA Operations
Script	Description
count_sequences.sh -	Counts total number of sequences
sequence_lengths.sh -	Calculates and prints each sequence length
longest_shortest.sh -	Finds longest and shortest sequences
gc.sh -	Computes GC percentage for each sequence
extract_seq.sh -Extracts sequences longer than 30 bp
count_motif.sh - Searches motifs (ATG, TATA, CGC) in sequences


4️⃣ Part B – Loops & Conditionals in FASTA Analysis
Script	Description
seq_length_classification.sh - Classifies sequences as Short, Medium, or Long
search1.sh -	Loops through motifs and checks their presence
rev_comp_gc.sh -	Prints reverse complement if GC% > 50
save_seq.sh -	Saves long and short sequences separately
seq_filtering.sh -	Filters sequences by user-defined minimum length
poly_a.sh -	Detects poly(A) tails (AAA...) at sequence ends
count_nucleotides.sh	Counts A, T, G, C nucleotides
palindromic.sh -	Detects palindromic sequences
selected_genes.sh -	Extracts specific Gene IDs (e.g., Gene1, Gene4)
gc_case.sh -	Categorizes GC% using case statements (Low, Medium, High)


5️⃣ Input Files Used
File	Description
all_sequences.fasta -	Combined FASTA file containing multiple gene sequences
motifs.txt -	Contains motifs to be searched (e.g., ATG, TATA, CGC)

⚙️ Usage Example
# Make scripts executable
chmod +x *.sh

# Run any script
./count_sequences.sh all_sequences.fasta

# Example : search for motifs
./count_motif.sh 

🧰 Tools & Commands Used
Category	Commands / Concepts

Sequence processing	grep, awk, wc, tr, rev
Looping & conditions	for, if, elif, case
File handling	Redirection (>, >>), conditional writes
GC and motif analysis	String pattern matching and arithmetic operations


📊 Learning Outcomes

Understand FASTA format and its biological relevance

Automate repetitive bioinformatics tasks using Bash

Gain hands-on experience in scripting logic and text parsing

Perform genomic feature analysis without external software

📄 Project Report
You can view the complete project report here: https://github.com/DEBOPRIYA2320/FASTA-File-Analysis-using-Shell-Scripting/blob/747e866754b494d7bd6c3dacde0cecdd781178fa/Bash%20Scripting(GITHUB).pdf

🧠 Author
**Debopriya**  
📧 [debopriya0920@gmail.com](mailto:debopriya0920@gmail.com)  
🔗 [GitHub](https://github.com/DEBOPRIYA2320)  
🔗 [LinkedIn](https://www.linkedin.com/in/debopriya2320)


🪪 License
This work is licensed under the [MIT License](LICENSE).


⭐ If you find this project helpful, consider giving it a star on GitHub!

