# Recommendar explanability

This is just an example on how to try to explain the results from a recommendation.


## Basic install on Windows

Install the python modules needed.

```
# install environment
python -m venv venv
python -m pip install --upgrade pip
.\venv\Scripts\Activate.ps1

# basic modules
pip install -r .\requirements.txt

# torch-geometric
pip install torch_geometric

# extra torch-geometric dependencies:
pip install torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.0.0+cpu.html

pip install jupyter
```



## References

* Explainer
    - https://pytorch-geometric.readthedocs.io/en/latest/index.html
    - https://github.com/pyg-team/pytorch_geometric/blob/master/examples/explain/gnn_explainer.py
    
* Recommending Amazon Products using Graph Neural Networks in PyTorch Geometric 
    - https://wandb.ai/manan-goel/gnn-recommender/reports/Recommending-Amazon-Products-using-Graph-Neural-Networks-in-PyTorch-Geometric--VmlldzozMTA3MzYw