Here is a README file for your code repository:

---

# README

## Overview

Welcome to the repository for the code associated with our anonymous under-review paper submitted to *Geophysics*. This code is designed to verify the effectiveness of our proposed method through synthetic examples. 

## Purpose

The primary objective of this code is to demonstrate the capability and performance of our method in separating ground roll from seismic data. Our approach, which leverages advanced signal processing techniques, is unsupervised and does not require external training datasets.

## Features

- **Unsupervised Method**: No need for external training datasets, making it easy to apply in various scenarios.
- **Synthetic Examples**: Included to validate the performance of our method.
- **Reproducible Research**: Code is provided to ensure that the results presented in the paper can be replicated and verified by other researchers.

## Requirements

To run the code, you'll need the following software and libraries installed:

- Python 3.x
- NumPy
- SciPy
- Matplotlib
- Pytorch

You can install the required packages using `pip`:

```bash
pip install numpy scipy matplotlib Pytorch
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-repo/your-repo.git
   cd your-repo
   ```

2. **Run the Example**:

   Execute the Unsupervised_GR_attenuation.ipynb script to run the synthetic example and verify the method:

   ```
   jupyter notebook Unsupervised_GR_attenuation.ipynb
   ```

   This will generate plots and results demonstrating the effectiveness of the proposed method.

## Directory Structure

- `data.mat`: Directory containing synthetic data files.

## Contributing

We welcome contributions to enhance the functionality of this code. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

For any questions or further information, please contact us.

---

Thank you for using our code. We hope it proves valuable in your research and applications.
