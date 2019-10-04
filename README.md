# DER_ControlPrivateTimeSeries
Energy resource control with private purterbed timeseries data 

## Setup and Dependencies

+ Python 3.x/numpy/scipy/[cvxpy](http://www.cvxpy.org/en/latest/)
+ [PyTorch](https://pytorch.org) >= 0.4.1  [recommend version >=1.1.0]
+ pandas >= 23.0
+ matplotlib, seaborn (optional)

if using GPU, setup CUDA (optional).

---

To test our parallel batched solver, simply run the 
```python
profiling_runtime.py 
``` 
which is located under **/CaseStudy_Synthetic/** folder. 


![check_priv](debug_priv_vis_out.gif)


![check_ctrl_gap](diagnostic_c_sol_vis_out.gif)
