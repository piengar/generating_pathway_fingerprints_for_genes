# Generating pathway fingerprints for genes
Scripts developed to carry out the work described in, “Using the Reactome Graph Database to generate pathway fingerprints for cancer-related genes, and using the fingerprints to gain insights into cancer, comorbidity, and cancer gene networks”. 

P.I. may be contacted for help with implementing the set of bespoke computer scripts. 

The scripts may be used to reproduce the work in the following way:
1) Text file __masterfiles.txt__:  This file contains a listing of 15 MASTERFILES (searching for the string “MASTERFILE” will enable the user to identify the 15 files), and 5 PERL PROGRAMS (search string “PERL PROGRAMS”).  Each MASTERFILE carries out a piece of work presented in the manuscript; comments _at the beginning of the MASTERFILE_ describe the piece of work carried out in the MASTERFILE.  To carry out the piece of work, the scripts used, the order in which the scripts must be run, and the input files to- and output files from- each script are all given.  _In each MASTERFILE_, there are also numerous comments describing what is being attempted and what each script does.  Following these MASTERFILES will provide insight into how the work has been done, and will make it possible to reproduce the work.  Five PERL PROGRAMS developed for the work have also been included. 

2) WinRAR archive file __allscripts.rar__: From this archive file, the text file, allscripts.txt, has first to be extracted.  The text file contains a listing of all scripts developed for the work.  AWK SCRIPTS appear towards the end of the file (search string “AWK SCRIPTS”).  Scripts are separated by a line of hashes (“########”).  The name of each script is given in the first line of the script, along with the path to the script (in P.I.’s work area).

3) To reproduce a piece of work, consider the relevant MASTERFILE.  If the MASTERFILE requires a script with a particular name to be run, search for the script name in the allscripts.txt file.  Use the script as specified in the MASTERFILE. Similarly, go through the entire MASTERFILE, executing specified scripts, and reproduce the piece of work.


(Note: In the supplementary file, Supplementary_Methods_SuppFigs_1to9_12to15.docx, two key scripts are given on pages 19 and 20, and two key Perl programs are given from the end of page 24 to page 30; these scripts are also included in the above files). 
