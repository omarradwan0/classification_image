# ml-lab0: Practice google colab and github classroom

1. Go to https://colab.research.google.com
2. Open from github and select private repositories
3. In the pop-up allow colab to access your github
4. Search for ensf411-winter-2021, select your dl-lab0 repository and open Jupyter notebook `dl-lab0.ipynb`
5. Change author name to your name. 
6. Save to github. (this will be your first commit)
7. Run the first cell, this will install fastbook, fastai, and dependencies.
8. Copy the code below and run in a code cell in Jupyter notebook.
9. Save to github. (this will be your second commit)


```Python
  import sys
  print("Python version:", sys.version)

  import torch
  print("PyTorch version:", torch.__version__)
    
  import fastai
  print("Fastai version:", fastai.__version__)

  import fastbook
  print("Fastbook version:", fastbook.__version__)

  
```
