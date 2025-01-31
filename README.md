# Network Traffic Classification using FFT and Statistical Analysis

This project involves analyzing the ISCXVPN2016 dataset to classify network traffic as malicious or benign. The approach taken includes transforming data packets using a Fast Fourier Transform (FFT) to analyze them in the frequency domain and gaining statistical insights into the dataset. The combination of traditional signal processing techniques with statistical analysis provides a deeper understanding of network traffic patterns.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

Steps to install and set up your project:

```sh
# Clone the repository
git clone https://github.com/AdityaBhatt6249/INTERNSHIP_KGP.git

# Navigate to the project directory
cd INTERNSHIP_KGP

# Install dependencies
pip install -r requirements.txt  # If applicable
```

## Usage

This repository contains multiple Jupyter Notebook (`.ipynb`) files, each addressing different aspects of the analysis. The dataset required for the project has also been included.

To run the notebooks:
```sh
# Example command to start Jupyter Notebook
jupyter notebook
```

### Key Steps in the Notebook
1. Load the ISCXVPN2016 dataset.
2. Extract and preprocess network traffic data packets.
3. Apply Fast Fourier Transform (FFT) to convert time-domain signals into frequency-domain representations.
4. Perform statistical analysis to understand traffic behavior and identify patterns.
5. Classify network traffic as malicious or benign based on extracted features.

## Features

- Utilizes the ISCXVPN2016 dataset for network traffic analysis.
- Applies Fast Fourier Transform (FFT) to analyze data packets.
- Extracts statistical features for a comprehensive understanding of network patterns.
- Assists in classifying network traffic into malicious and benign categories.

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the [MIT License](LICENSE).

