# Shoestring

## Run demos

#### Run code with parameters to reproduce the results in our paper

```bash
# Cora
python train.py --pset config_citation.one_label_set --dataset cora --method l1 l2 cos
python train.py --pset config_citation.two_label_set --dataset cora --method l1 l2 cos
python train.py --pset config_citation.five_label_set --dataset cora --method l1 l2 cos
# Citeseer
python train.py --pset config_citation.one_label_set --dataset citeseer --method l1 l2 cos
python train.py --pset config_citation.two_label_set --dataset citeseer --method l1 l2 cos
python train.py --pset config_citation.five_label_set --dataset citeseer --method l1 l2 cos
# Pubmed
python train.py --pset config_citation.one_label_set --dataset pubmed --method l1 l2 cos
python train.py --pset config_citation.two_label_set --dataset pubmed --method l1 l2 cos
python train.py --pset config_citation.five_label_set --dataset pubmed --method l1 l2 cos
# Large Cora
python train.py --pset config_citation.one_label_set --dataset large_cora --method l1 l2 cos
python train.py --pset config_citation.two_label_set --dataset large_cora --method l1 l2 cos
python train.py --pset config_citation.five_label_set --dataset large_cora --method l1 l2 cos
```
