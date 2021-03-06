# Biotools

This module contains many methods related to biology and sequence manipulation,
either used in the core DNA Chisel classes, or very helpful when writing
DNA Chisel scripts.


- **biotables.py** provides tables (=dictionaries) of biological data, such as genetic code, IUPAC nucleotide definitions, etc.
- **blast_sequence** contains a practical BLAST method (using NCBI+). It is used in AvoidBlastMatches but could be used anywhere else.
- **enzymes_operations** is for enzyme-related methods. Currently only "list_common_enzymes", which can be practical.
- **formatting_operations** contains methods to format strings and numericals, used throughout the library.
- **gc_content.py** contains a method implementing (windowed) GC content and is notably used by EnforceGCContent.
- **genbank_operations** contains many Genbank and Biopython record related methods, used intensively in the librairy and examples.
- **indices_operations.py** contains methods to group or ungroup segments and sets of indices, which are used to handle breach *Locations* in the core code.
- **sequences_differences.py** contains methods for comparing sequences and pointing at locations that differ.
- **sequences_operations.py** contains methods for manipulating "ATGC" strings representing sequences (methods include reverse_complement, reverse_translate, etc.)
- **data/** contains data files used by the code in this folder (genetic code, iupac definitions, etc.)