# Markdown Features
#### Emphasis: 
- *This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*

#### Images:
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

#### Orders:
1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b

# Useful links

- [https://ledatascifi.github.io/](https://ledatascifi.github.io/) is the main website
- [https://github.com/kjacobellis1/](https://github.com/kjacobellis1/) is my account homepage on GitHub
- [https://www.espn.com/](https://www.espn.com/) has scores
- [https://github.com/LeDataSciFi/Discussion/](https://github.com/LeDataSciFi/Discussion/) This is the discussion and announcement repo
- [https://ledatascifi.github.io/studentresourcevert/resource-landing.html](https://ledatascifi.github.io/studentresourcevert/resource-landing.html) This is a repo for useful resources
- [https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) For more markdown recommendations!

# How to:
- To open my participation repo in Jupyter I run "jupyter notebook --notebook-dir" C:\Users\Kathrynjaco08\Desktop\FIN377\FIN377--Participation".

- Adding a spell checker. Open Terminal/Powershell, and run these 3 lines:
  - pip install jupyter_contrib_nbextensions
  - jupyter contrib nbextension install --user
  - jupyter nbextension enable spellchecker/main
  
# Golden Rules!
| **Category** | **Rule**  
| :--- | :--- |
| 0. **PLAN BEFORE YOU CODE** | A. \"Pseudo code\" is writing out the broad steps in plain language. I often (almost always for complicated tasks) do this on paper, then translate it to code as an outline (in the code's comments). <br> <br> Maybe planning sounds boring and like a waste of time. I get it; I also want to [shoot first](https://youtu.be/la7uuFsCIrg?t=43) like [Han did...](https://youtu.be/93pXrmCdlI0?t=26)  but coders like Han often [end up looking like this guy](https://youtu.be/mLyOj_QD4a4?t=67)... |
| | B. Break the problem into chunks/smaller <br>problems. This dovetails with rule 5.B below nicely. |
| 1. Automation | A. Automate everything that can be automated, don't do point-and-click analysis! |
| | B. Write a single script that executes all code from beginning to end |
| 2. Version control | A. Store code and data under version control. Revisit the [GitHub workflow recipe](01_Motivation_and_Getting_Started.html#***-THE-WORKFLOW-RECIPE--***) as needed! |
| | B. **Before checking the directory back in, clear all outputs and temp files and then run the whole directory!** (Check: Did it work right?) <br>  |
| 3.  Directories | A. Separate directories by function |
| | B. Separate files into inputs and outputs |
| | C. Make directories portable |
| 4. Keys / Units | A. Store cleaned data in tables with unique, non-missing \"keys\" |
| | B. Keep data normalized as far into your code pipeline as you can |
| 5. Abstraction - fncs/classes | A. Abstract to eliminate redundancy |
| | B. Abstract to improve clarity |
| | C. Otherwise, don't abstract |
| | D. **Unit test your functions!** |
| | E. Don't use magic numbers, define once as variables and refer as needed |
| 6. Documentation | A. Is good... to a point |
| | B. Don't write documentation you will not maintain |
| | C. Code is better off when it is self-documenting |
| 7. Randoms | NEVER DRAW RANDOM NUMBERS WITHOUT A SEED |
