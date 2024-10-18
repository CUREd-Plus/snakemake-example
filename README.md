# NHS data workflow example
An example workflow using NHS synthetic data implemented using [Snakemake](https://snakemake.readthedocs.io/en/stable/) to process [NHS artificial data](https://digital.nhs.uk/services/artificial-data).

The contents of this repository are organised following [Snakemake reproducibility guidelines](https://snakemake.readthedocs.io/en/stable/snakefiles/deployment.html).

# Installation

Create a virtual environment

```bash
python -m venv venv
```

Activate that environment

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

# Usage

Run the workflow

```bash
snakemake
```

