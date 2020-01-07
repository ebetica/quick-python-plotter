# quick-python-plotter
Bash based tool for plotting things quickly

Examples:

Line plot
```
python -c 'import numpy as np; print("\n".join(str(x) for x in np.random.randn(100)))' | pqp line | display
```
