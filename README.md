# 15MCRCB-SSD-Spoof-Detection

Training and evaluation scripts for the 15MCRCB-SSD regional replay and channel-based speech spoofing dataset.

## Overview

This repository contains baseline model training and evaluation notebooks used in the experimental validation of the 15MCRCB-SSD dataset.

The dataset includes:

- 219,670 audio files  
- ~896 hours of speech  
- 15 recording regions  
- 5 replay and channel-based spoofing conditions  

All spoofed recordings were generated through real physical playback and transmission processes to preserve ecological validity.

## Spoofing Conditions

1. Real vs. Monster  
2. Real vs. Monster–Telephone  
3. Real vs. Radio  
4. Real vs. Robot  
5. Real vs. Telephone  

## Repository Structure

```
15MCRCB-SSD-Spoof-Detection/
│
├── notebooks/
│   ├── RealVsMonster_Split.ipynb
│   ├── RealVsRadio_Split.ipynb
│   ├── RealVsTelephone.ipynb
│   ├── RealVsRobot.ipynb
│   └── RealVsMonsterTelephone.ipynb
│
├── requirements.txt
├── README.md
└── LICENSE
```

## Requirements

Python 3.8+

Main libraries:

- PyTorch  
- NumPy  
- Librosa  
- Scikit-learn  
- Pandas  
- Matplotlib  
- tqdm  

Install dependencies:

```
pip install -r requirements.txt
```

## Citation

If you use this code or the 15MCRCB-SSD dataset in your research, please cite the corresponding IEEE Data Description paper.

## License

This project is released under the MIT License.
