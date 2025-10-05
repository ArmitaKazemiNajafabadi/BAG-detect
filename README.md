# BAG-detect
Optimal monitoring and attack detection of networks modeled by Bayesian attack graphs


This repository contains the implementation of optimal minimum mean square error (MMSE) attack detection algorithms for Bayesian Attack Graphs (BAGs), as described in our paper published in Cybersecurity journal.

*Note: the codes in this repository are not the final version and require cleaning/instructions.*

# Optimal Monitoring and Attack Detection of Networks Modeled by Bayesian Attack Graphs

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![DOI](https://img.shields.io/badge/DOI-10.1186%2Fs42400--023--00155--y-blue)](https://doi.org/10.1186/s42400-023-00155-y)

This repository contains the implementation of optimal minimum mean square error (MMSE) attack detection algorithms for Bayesian Attack Graphs (BAGs), as described in our paper published in Springer's *Cybersecurity* journal.

## Overview

Early detection of attacks is crucial for protecting complex networks, particularly critical infrastructures that are susceptible to multi-stage threats. This work focuses on designing optimal monitoring and detection strategies for networks represented through Bayesian Attack Graphs (BAGs). The proposed approach leverages probabilistic modeling to capture system vulnerabilities and the dynamics of attack progression, enabling timely estimation of ongoing attacks.


### Key Contributions

- **MMSE-Optimal Detection**: Derives the optimal minimum mean square error attack detection policy for the most general form of BAGs
- **Adaptive Monitoring**: Introduces a resource-efficient monitoring policy that activates when prediction error exceeds thresholds
- **Matrix-Form Computations**: Provides exact and efficient implementations for real-time deployment

## Problem Statement

Traditional attack detection techniques for BAGs assume network compromises will be detected through routine monitoring - an unrealistic assumption given the complexity and stealth of modern threats. Our approach addresses:

- **Partial Observability**: Networks with limited monitoring coverage
- **Resource Constraints**: Optimal allocation of monitoring resources
- **Multi-stage Attacks**: Detection of attacks across network components
- **Probabilistic Modeling**: Uncertainty in attacker behavior and attack progression

## Methodology

### Bayesian Attack Graph Model
- Models attacker behavior and attack progression probabilistically
- Captures vulnerabilities, interactions, and dependencies across network components
- Represents multi-step attack paths through the network

### Optimal Detection Algorithm
1. **State Estimation**: Uses Kalman filtering principles adapted for BAG structure
2. **Prediction**: Forecasts attack progression based on current observations
3. **Detection**: Applies MMSE-optimal decision rules
4. **Adaptation**: Dynamically adjusts monitoring resources based on prediction confidence

### Adaptive Monitoring Policy
- Monitors nodes when expected predictive error exceeds user-defined thresholds
- Optimizes resource allocation across network components
- Balances detection accuracy with monitoring costs

## Repository Structure

```
incomplete
```

### Prerequisites
- incomplete
- Python 
- NumPy
- Matplotlib for visualization

### Setup
```bash
incomplete
```


## Experimental Results

Our experiments on synthetic BAGs with various topologies demonstrate:
- **Superior Detection Accuracy**: Significantly outperforms baseline methods
- **Resource Efficiency**: Optimal allocation reduces monitoring costs by 30-40%
- **Scalability**: Maintains performance on large network topologies
- **Robustness**: Consistent performance across different attack scenarios

See `notebooks/performance_evaluation.ipynb` for detailed analysis.

## Citation

If you use this code in your research, please cite our paper:

```bibtex
@article{kazeminajafabadi2023optimal,
  title={Optimal monitoring and attack detection of networks modeled by {B}ayesian attack graphs},
  author={Kazeminajafabadi, Armita and Imani, Mahdi},
  journal={Cybersecurity},
  volume={6},
  number={1},
  pages={22},
  year={2023},
  publisher={Springer}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- **Armita Kazeminajafabadi** - [GitHub](https://github.com/ArmitaKazemiNajafabadi)
- **Mahdi Imani** 

## Acknowledgments

- Published in *Cybersecurity* journal (SpringerOpen)
- Supported by the National Science Foundation award IIS-2202395, ARMY Research Office award W911NF2110299, and Oracle Cloud credits and related resources provided by the Oracle for Research program.

## Support

For questions about the implementation or paper, please:
Contact the authors directly on LinkedIn 

---

**Keywords**: Bayesian Attack Graphs, Network Security, Attack Detection, MMSE Estimation, Cybersecurity, Optimal Monitoring




