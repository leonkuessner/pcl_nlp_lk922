## NLP CW

This task aims to follow a typical NLP research lifecycle, with the aim of improving baseline classification on PCL dataset.
I fine-tuned the baseline RoBERTa model using seed ensembling, various eda-driven ablations including task2 warm start, 

### Dependencies
> python -m pip install -r requirements.txt

### Important Files
- model: <./BestModel/BEST_MODEL.ipynb>
  - This also contains the error analysis
- eda in PCL_analysis
- test.txt, dev.txt in root