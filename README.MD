# Recommendar explanability

This is just an example on how to try to explain the results from a recommendation.


## Basic install on Windows

Install the python modules needed (for CPU environment).

```
# install environment
python -m venv venv
.\venv\Scripts\Activate.ps1
python -m pip install --upgrade pip

# install python modules
pip install -r .\requirements.txt

```



## References

* Explainer
    - https://pytorch-geometric.readthedocs.io/en/latest/index.html
    - https://github.com/pyg-team/pytorch_geometric/blob/master/examples/explain/gnn_explainer.py
    
* Recommending Amazon Products using Graph Neural Networks in PyTorch Geometric 
    - https://wandb.ai/manan-goel/gnn-recommender/reports/Recommending-Amazon-Products-using-Graph-Neural-Networks-in-PyTorch-Geometric--VmlldzozMTA3MzYw