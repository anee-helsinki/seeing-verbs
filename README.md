# seeing-verbs
Verbs of seeing in Akkadian

This repository contains scripts and data for the paper "Language Technology Approach to Seeing in Akkadian".

**/data**  
+ aug18-nolex.txt  
   Lemmatized dataset from Oracc  
+ results-pmi2-top50.log  
   Script parameters for pmizer (see https://github.com/asahala/Pmizer)
+ results-pmi2-top50.tsv  
   Results in .tsv format. Fields in the file:  
   1. keyword  
   2. translation from Oracc
   3. collocate
   4. translation from Oracc  
   5. period distribution
   6. genre distribution
   7. period and genre distribution
   8. keyword freq
   9. collocate freq
   10. co-occurrence freq
   11. PMI2 score
   12. average distance between keyword and collocate (in words)
   13. url to Korp (all links may not return results, as Korp Oracc had a major update in 2019: see https://www.kielipankki.fi/corpora/oracc/ for more info and user guide). Note that the co-occurrence of words (a, b) is symmetric, meaning that (a, b) == (b, a). Thus, if you search results from Korp using the links and do not get any results, you may have to switch the search boxes in reversed order.
+ period/genre-distribution-matrix.tsv  
   Distribution of seeing verbs in different genres and periods as a matrix representation
