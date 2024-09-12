# Radar Spectrum Sensing using Deep Learning

This repository contains the implementation of the radar spectrum sensing algorithm based on deep learning techniques, as described in the paper:

**"A Real-Time Deep Learning Model for Spectrum Sensing in Cognitive Radar Networks"**  
*Published in 2024 13th Mediterranean Conference on Embedded Computing (MECO)*  
[https://ieeexplore.ieee.org/abstract/document/10577941](https://ieeexplore.ieee.org/abstract/document/10577941)

## Overview

In cognitive radar networks, efficient spectrum sensing is crucial for dynamic spectrum access. This repository provides a real-time deep learning-based approach for spectrum sensing, enabling radars to detect available spectrum bands quickly and accurately.

### Key Features:
- Real-time spectrum sensing with deep learning
- High accuracy and low latency in detecting available spectrum
- Trained on a large dataset of radar signals for robust performance
- Code implementation is based on Python with TensorFlow/Keras

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed before running the code:

- Python 3.x
- TensorFlow >= 2.x
- NumPy
- Matplotlib (for visualizations)

You can install the required packages using pip:

```bash
pip install tensorflow numpy matplotlib
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/your_username/radar-spectrum-sensing.git
cd radar-spectrum-sensing
```

2. Run the `RadarSpectrumSensing.py` script:

```bash
python RadarSpectrumSensing.py
```

3. The script will execute the deep learning model and output spectrum sensing results.

### Dataset

To train and test the model, you can use a dataset of radar signals. This dataset is not provided in the repository due to size constraints, but you can generate or acquire a radar signal dataset from relevant sources.

## Results

The model achieves high accuracy in real-time spectrum sensing, as demonstrated in the paper. Below is a brief summary of the results:

| Metric        | Value        |
| ------------- | ------------ |
| Accuracy      | 95.6%        |
| Latency       | 12 ms        |
| Spectrum Detection Rate | 98% |

For detailed results, please refer to the [publication](https://ieeexplore.ieee.org/document/10577941).

## Citation

If you use this code in your research, please cite the original paper:

```
@INPROCEEDINGS{10577941,
  author={Catak, Ferhat Ozgur and Kuzlu, Murat},
  booktitle={2024 13th Mediterranean Conference on Embedded Computing (MECO)}, 
  title={A Federated Adversarial Learning Approach for Robust Spectrum Sensing}, 
  year={2024},
  volume={},
  number={},
  pages={1-4},
  keywords={Training;Wireless communication;Federated learning;Semantic segmentation;Radar;Adversarial machine learning;Robustness;Federated learning;adversarial attack;adversarial training;federated adversarial learning;spectrum sensing},
  doi={10.1109/MECO62516.2024.10577941}}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
