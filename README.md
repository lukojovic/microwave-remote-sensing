#  UE Microwave Remote Sensing (120.030)

These are the hand-outs and exercises of the Master course Microwave Remote Sensing (120.030) at the TU Wien.

# Generate Jupyter Conda environment and Jupyter Kernel from `yml`

To re-create the environment as a Jupyter kernel for execution of the notebooks, do the following:

- Open a Terminal from the same level as this Markdown README file.
- Type the following into the terminal.

```
make kernel
```

Select the kernel with the equivalent name as the `.ipynb` notebook to execute the notebook. For example, `01_lecture.ipynb` requires the kernel `01_lecture` for execution of the code blocks.

# Clean-up

To remove Jupyter checkpoints run:

```
make clean
```

In order to remove the Conda environments and Jupyter kernels runL

```
make teardown
```