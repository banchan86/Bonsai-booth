# Reaction Time Task Example

An example of a reaction time task in [Bonsai](https://bonsai-rx.org/). 

This example demonstrates how to use the [Harp Hobgoblin](https://harp-tech.org/tutorials/hobgoblin-setup.html) to implement a simple task that can be adapted to model a wide range of neuroscience experiments. For a detailed walkthrough on the task logic, refer to this [tutorial](https://harp-tech.org/tutorials/hobgoblin-reaction.html).

## How to use

1) Connect a LED wired up with a 100 Ω resistor to `GP15` and a push button to `GP2` on the `Hobgoblin`.
2) Adjust the task parameters to specify the response window/timeout as well as number of trials.
3) Hit the `Start` button to start the reaction time task.

## How to analyze data

This example includes a simple Jupyter notebook for data analysis. To setup the virtual environment for data analysis:

1) Install [`uv`](https://docs.astral.sh/uv/getting-started/).
2) Run `uv sync` to restore the virtual environment.
3) Run `uv run jupyter lab` and open the `harp_data_analysis.ipynb` Jupyter notebook.