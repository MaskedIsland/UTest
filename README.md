# UTest

## Introduction
The rapid development of urbanization has facilitated the process of urban planning, e.g., new commercial and residential areas, which results in a surge of the local traffic demand. In this paper, we study the 'plan-based urban traffic estimation' problem. Effective urban plan estimation is of great significance to mitigate the operational vulnerability of a transportation system, such as traffic congestion and accidents. Solving this problem is challenging due to the complex spatio-temporal dependencies preserved in the various urban data. In this paper, we propose a novel urban traffic estimation framework, UTest, which can provide traffic estimations in consecutive time slots via spatio-temporal graph learning. UTest aims to provide accurate estimation results automatically, thus human planners can finally adjust machine-generated plans before deploying them. The proposed UTest adopts and advances the graph learning structure through a few novel ideas: (1) modeling various travel demands as the spatio-temporal graphs to build the spatio-temporal dependencies explicitly, (2) integrating graph convolution neural networks to learn the local spatial dependencies along the underlying road networks, (3) employing multi-head self-attention mechanism to learn the temporal dependencies of the traffic across different time slots. We conduct extensive experiments on two real-world spatio-temporal datasets. Experimental results demonstrate that UTest outperforms major baselines in estimation accuracy under various settings and can produce more meaningful estimation results.

---

## Data
<div align=center><img width="500" height="700" src="https://github.com/MaskedIsland/UTest/blob/main/figures/data-processing.png"/></div>

## Model
<div align=center><img width="500" height="700" src="https://github.com/MaskedIsland/UTest/blob/main/figures/framework.png"/></div>


## Visualization

### Long sequence prediction
<div align=center><img width="1000" height="600" src="https://github.com/MaskedIsland/UTest/blob/main/figures/long-seq-prediction.png"/></div>

### RMSE
<div align=center><img width="650" height="400" src="https://github.com/MaskedIsland/UTest/blob/main/figures/CTS-RMSE.png"/></div>

### MAPE
<div align=center><img width="650" height="400" src="https://github.com/MaskedIsland/UTest/blob/main/figures/CTS-MAPE.png"/></div>


### Training process
<div align=center><img width="450" height="400" src="https://github.com/MaskedIsland/UTest/blob/main/figures/training-process.png"/></div>
