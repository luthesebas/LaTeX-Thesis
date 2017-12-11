## LaTeXTemplates

TODO

## Install MiKTeX and TeXstudio

1. Install **MiKTeX**: https://miktex.org/

2. Install **TeXstudio**: https://www.texstudio.org/ 

3. Run **TeXstudio** and open _Options_ to configure **TeXstudio**

   - Make sure to check _Show Advanced Options_
   
   - Go to _Commands_ and modify the following entries:
   
     - **pdflatex**: ```pdflatex.exe -synctex=1 -interaction=nonstopmode -aux-directory=metadata %.tex```
     
     - **bibtex**: ```bibtex.exe metadata/%```
     
     - **biber**: ```biber.exe -output-directory=metadata -input-directory=metadata %```
     
   - Go to _Build_ and modify the following entries:
   
     - **Build & View**
     
       - ```txs:///pdflatex | txs:///biber | txs:///pdflatex | txs:///pdflatex | txs:///compile | txs:///view```
       
       - or: ```txs:///pdflatex | txs:///biber | txs:///pdflatex | txs:///pdflatex | txs:///view```
       
     - **Log File**: ```\\metadata```
     
     - **PDF File**: ```\\metadata```
