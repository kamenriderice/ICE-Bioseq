# ICE-Bioseq
Program to integrate the results from multiple epitope prediction and protein analysis tools.

Iván Corona Guerrero (icg.microbiologia@gmail.com)
PhD Student @ Universidad Autónoma de Querétaro

ICE-Bioseq is a tool developed to help researchers and their students to integrate results of multiple epitope prediction tools.
Currently, ICE-Bioseq can analyse the results from Bcepred, Abcpred, Bepipred 3.0, IEDB MHC-I and MHC-II Binding Prediction tools.

# How to use
## Get results
### Sequence
The aminoacid sequence of the protein must be saved in plain text or fasta format in a .fasta or .txt file.
The sequence must be exactly the same in all the tools, otherwise the program will crash.

### Bcepred
On the results page of the tool, right click on the page, select "Save as..." and save the complete page as a .html file.

### Abcpred
On the results page of the tool, right click on the page, select "Save as..." and save the complete page as a .html file.

### Bepipred 3.0
On the results page of the tool, clic the "Download bepipred3 results (zip)" option. Don't extract the files.
ICE-bioseq only works with Bepipred 3.0. Please avoid using results from previous versions of the program.

### IEDB MHC-I binding prediction tools
In the submission page, at the specify output section select Sort Peptides by Predicted Score (Descend) and set the output format as Text File.
On the results page of the tool, right click on the page, select "Save as..." and save the complete page as a .html file.

### IEDB MHC-II binding prediction tools
In the submission page, at the specify output section select Sort Peptides by Percentile Rank and set the output format as Text File.
On the results page of the tool, right click on the page, select "Save as..." and save the complete page as a .html file.


## Running the tool
### Select a work folder
The user must select a work folder for the program. Due to permission management, the folder must not be associated with a cloud sync service such as OneDrive, Google Drive, iCloud, etc.

### Loading the results
Clic on each button to select the appropiate file. The sequence and all the results files must make reference to the same sequence, otherwise the program will crash. The user can change the name of the results file. The results will be saved as a .xlsx file.

## You can help me improve ICE-Bioseq
If you or your colleagues need another tool to be integrated in ICE-Bioseq, send an email to icg.microbiologia@gmail.com


