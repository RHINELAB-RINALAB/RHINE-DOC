Repository for Lab's Documents and some **templates**. Most small documents will be found on here sometimes. Currently, its purpose is to hold **source codes on documents typesetting**. It is originally a part of the wider regime to establish a form of *template documents system*, however, since such role has been transferred, or rather rebuilt into a different form, the repository has now taken the role for coordinating sources, if one wish to do so on this playground as itself. 

In the `V1` folder for the old organization up to present, there is:

1. `R0` is for document template and details. There is one local from *RevTeX 4.2* of The American Physical Society for local compilation. There, if you use Overleaf, just take [this already available template on Overleaf](https://www.overleaf.com/latex/templates/revtex-4-dot-2-template-and-sample/yydsrzvrqrzs). 
2. `R1` is for organization documents and bureaucratic - non-research and non-pedagogy materials. 
3. `R2` is for conceptual notes and miscellaneous, research/work-adjacent notes. 
4. `R3` is for source code of Research Topics, its template and also subsequent topic analysis. 
5. `R4` is for a new form, notably **Dialog** discussions. 
6. `R5` is for miscellaneous documents and filing. 

Such is the current operation. Since we decided to house large files, `Git LFS` has been patched, so if you are to push onto this repository, please do the same. The pipeline is simple as followed. 

1. Install Git LFS. 
2. In the git initialization of the repository, use `git lfs track "*.png" "*.jpg" "*.jpeg" "*.pdf" "*.gif"` to track for large produced files artifact. 
3. Add `git add .gitattributes` as the produced file. 
4. Continue with the usual `git` pipeline (don't break the version control, please).

## Update

- 2026/04/06 - Updated another template. 
- 2026/05/11 - Fixing `readme` and changing purpose. 
- 2026/06/30 - Updated to `V1` and `V2` repository in provision. We will be testing a variety of things up there. 
- 2026/07/02 - Moved a version of it to `github`. This will be the **public repository** of all works here. 
