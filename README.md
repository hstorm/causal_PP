# Causal Probabilistic Programming in NumPyro

*Hugo Storm, September 2024, hugo.storm@ilr.uni-bonn.de*

Implementing typical causal regression approaches in Probabilistic Programming using NumPyro

# Available Notebooks

- [```notebooks/CallawaySantAnna_in_PP.ipynb```](https://github.com/hstorm/causal_PP/blob/main/notebooks/CallawaySantAnna_in_PP.ipynb): Implements the Callaway and Sant'Anna (2021) approach for estimating treatment effects in staggered adoption settings using NumPyro.

- [```notebooks/IV_in_pp.ipynb```](https://github.com/hstorm/causal_PP/blob/main/notebooks/IV_in_pp.ipynb): Implements a simple instrumental variable regression model in NumPyro

- [```notebooks/joint_causal_models.ipynb```](https://github.com/hstorm/causal_PP/blob/main/notebooks/joint_causal_models.ipynb): Implements a joint model combining a staggered adoption DiD model with IV regression in NumPyro.


# Prerequisites

The repository is set up to run in a Docker container. You should have Docker installed and running on your machine. If you don't have it, please install it from [Docker's official website](https://www.docker.com/get-started).

To use the repository,pull the repository and open it in VS Code with the Remote-Containers extension.
This requires that you have the VS Dev-Containers extension installed (Extension identifier: `ms-vscode-remote.remote-containers`)

Follow the instructions to do this:

1. Clone the repository: `git clone https://github.com/hstorm/causal_PP.git`
2. Open the clone folder in VS Code and hit `Ctrl+Shift+P` and select `Remote-Containers: Reopen in Container`. 

*Note: Ideally, you should have a Nvidia GPU installed on your machine to run the code. However, it is not strictly necessary. Depeding on you machine you might need to adjust the .devcontainer/devcontainer.json file for example in terms of the memory limite or GPU usage.*

All the necessary dependencies are then automatically installed in the Docker container. 

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.