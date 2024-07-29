# This read me is for manually linking the Rmarkdown knit from MacOS local repository to Github
## The next step after uploading the Rmarkdown script is to download the file from Github then manually upload to Overleaf
cd /Volumes/Teatree/Dissert/France/Data/RAW/Regressions/Thesis_Rmarkdown  
git init  
git add Results-draft.tex  
git commit -m "Initial commit of Results-draft.tex"  
git remote add origin https://github.com/treetreh/Thesis-Rcode.git  
git push -u origin master  

## Updating Results
git add Results-draft.tex  
git commit -m "Updated Results"  
git push
