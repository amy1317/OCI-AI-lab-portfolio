# 0-01 Create an OCI Compute Instance

## Overview
This lab provides steps and scripts for creating an Oracle Cloud Infrastructure (OCI) compute instance. You will use OCI CLI and Python SDK.

## Prerequisites
- Oracle Cloud account
- OCI CLI installed
- Python 3.8 or higher
- Required Python packages listed in requirements.txt

## Setup
1. Edit `config/config.yaml` with your OCI account details.
2. Install requirements: `pip install -r requirements.txt`
3. Open `code/setup_instance.ipynb` and follow the steps, or run `python code/setup_instance.py`.

## Data
Sample configuration (`data/sample_config.yaml`) demonstrates required fields.

## Usage
- Run the notebook or script.
- Monitor progress and output in `results/setup_log.txt`.

## Outputs
- Detailed instance info: `results/instance_details.json`
- Any errors: `results/error_log.txt`

## Notes
- Never commit real credentials.
- See Oracle docs for authentication tips: [link to docs]

