# KUET_Crescendo-Code-Library
Code Library For KUET_Crescendo (2019-2020)

## Usage:

 > Requires: [Python 2/3](https://www.python.org/), [latexmk](https://www.ctan.org/pkg/latexmk/)
 
 > Use **generate_pdf.py** to create PDF file 
 
 > All Code is in `\code` directory
 
 > **contents (2).txt** is used for Indexing
   `contents (2).txt` has the following format :
   ```
   [Section name]
   subfolder/file.cpp  Description of the file      # Optional end-of-line comment
   ```
 > **notebook.tex** is generating and Formatting the PDF file
  - Edit Line 26: basicstyle ... for changing font size/family
  - Edit Line 28,36,44,52: syntax coloring 
     The generator script can add text highlighting for the following file formats : `.h, .c, .cc, .cpp, .java, .py`
  
  - Edit 74.. : You can edit the row adding  `\begin{multicols}{2} ... \end{multicols}`
                You can edit the orientation adding `\begin{landscape} ... \end{landscape}`
                
   
## Release:
  [Latest Release](https://github.com/sabertooth9/KUET_Crescendo-Code-Library/releases/latest)
  
  [History](https://github.com/sabertooth9/KUET_Crescendo-Code-Library/releases)
