# Energy Resource Control via Privacy Preserving Data
Energy resource control with private purterbed timeseries data 


## Setup and Dependencies

+ Python 3.x/numpy/scipy/[cvxpy](http://www.cvxpy.org/en/latest/)
+ [PyTorch](https://pytorch.org) >= 0.4.1  [recommend version >=1.1.0]
+ pandas >= 23.0
+ matplotlib, seaborn (optional)

if using GPU, setup CUDA (optional).

---

This repo contains the experiments in the following paper "Energy Resource Control via Privacy Preserving Data". [arxiv link](https://arxiv.org/abs/1910.02157) 

```bibtex
@misc{chen2019energy,
    title={Energy Resource Control via Privacy Preserving Data},
    author={Xiao Chen and Thomas Navidi and Ram Rajagopal},
    year={2019},
    eprint={1910.02157},
    archivePrefix={arXiv},
    primaryClass={eess.SY}
}
```


---

To test our parallel batched solver, simply run the 
```python
profiling_runtime.py 
``` 
which is located under **/CaseStudy_Synthetic/** folder. 


![check_priv](debug_priv_vis_out.gif)


![check_ctrl_gap](diagnostic_c_sol_vis_out.gif)


### reference 

```bibtex
@InProceedings{amos2017optnet,
  title = {{O}pt{N}et: Differentiable Optimization as a Layer in Neural Networks},
  author = {Brandon Amos and J. Zico Kolter},
  booktitle = {Proceedings of the 34th International Conference on Machine Learning},
  pages = {136--145},
  year = {2017},
  volume = {70},
  series = {Proceedings of Machine Learning Research},
  publisher ={PMLR},
}

@article{diffcp2019,
    author       = {Agrawal, A. and Barratt, S. and Boyd, S. and Busseti, E. and Moursi, W.},
    title        = {Differentiating through a Cone Program},
    journal      = {Journal of Applied and Numerical Optimization},
    year         = {2019},
    volume       = {1},
    number       = {2},
    pages        = {107--115},
}

```
