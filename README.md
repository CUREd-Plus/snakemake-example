# NHS data workflow example
An example workflow using NHS synthetic data implemented using [Snakemake](https://snakemake.readthedocs.io/en/stable/) to process [NHS artificial data](https://digital.nhs.uk/services/artificial-data).

The contents of this repository are organised following [Snakemake reproducibility guidelines](https://snakemake.readthedocs.io/en/stable/snakefiles/deployment.html).

# Installation

Create a [virtual environment](https://docs.python.org/3/library/venv.html)

```bash
python -m venv .venv
```

Activate that environment (the specific command depends upon operating system)

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

# Usage

Run the workflow using the [command line interface](https://snakemake.readthedocs.io/en/stable/executing/cli.html)

```bash
snakemake <target_output_file>
```

