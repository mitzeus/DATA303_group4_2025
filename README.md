# 2025 DATA303 Project - Group 4

## Paper Selected:

B. Pang. _Learning Latent Space Energy-Based Prior Model_. 2020. https://arxiv.org/pdf/2006.08205

### Description

#### Paper Abstract

We propose to learn energy-based model (EBM) in the latent space of a generator
model, so that the EBM serves as a prior model that stands on the top-down
network of the generator model. Both the latent space EBM and the top-down
network can be learned jointly by maximum likelihood, which involves short-run
MCMC sampling from both the prior and posterior distributions of the latent vector.
Due to the low dimensionality of the latent space and the expressiveness of the
top-down network, a simple EBM in latent space can capture regularities in the
data effectively, and MCMC sampling in latent space is efficient and mixes well.
We show that the learned model exhibits strong performances in terms of image
and text generation and anomaly detection. The one-page code can be found in
supplementary materials.

## How to run

### 1. (Optional) Setup Virtual Environment

It is recommended to run this code in a virtual environment such as conda. For this project Miniconda was used. See instructions [here](https://www.anaconda.com/docs/getting-started/miniconda/install).

### 2. Install Required Packages

In your environment, run `pip install -r requirements.txt` to install necessary packages.

### 3. Code Execution

To execute the code, run `full_code.ipynb` file.

## <span style="color: rgb(255 100 0)">2025.06.22 Results Inconsistency</span>

As of 2025.06.22 the runtime will not produce consistent results becuase of a bug, therefore refer to `Results/` for current best generated results from current code.

## Credits

Korea University 2025 Spring Semester

Course: DATA303-00: Advanced Machine Learning

### Instructor

Professor 김성웅

### Group Members

- 국회영
- 오예준
- MITZEUS DENNIS MIKAEL
