[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py


## Task 2.5

## Dataset: Simple

### Parameter:
- Number of points: 50
- hidden: 2
- Learning rate: 0.1
- Number of epochs: 500

### Time per epoch:
- 0.040s

### Result:
<img src="simple_result.png">
<img src="simple_logs.png">



## Dataset: Diag

### Parameter:
- Number of points: 80
- hidden: 3
- Learning rate: 0.1
- Number of epochs: 500

### Time per epoch:
- 0.096s

### Result:
<img src="diag_result.png">
<img src="diag_logs.png">



## Dataset: Split

### Parameter:
- Number of points: 50
- hidden: 5
- Learning rate: 0.1
- Number of epochs: 800

### Time per epoch:
- 0.102s

### Result:
<img src="split_result.png">
<img src="split_logs.png">



## Dataset: Xor

### Parameter:
- Number of points: 50
- hidden: 8
- Learning rate: 0.1
- Number of epochs: 800

### Time per epoch:
- 0.205s

### Result:
<img src="xor_result.png">
<img src="xor_logs.png">
