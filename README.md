# vpin-jump-detector
VPIN-based Bitcoin market microstructure analysis system using Binance high-frequency trade data to detect informed trading activity and price jumps.

# VPIN Jump Detector: BTC Market Microstructure

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1P_z-BMr7CPXY-CQ6gi_APtBv0Wq761EP?usp=sharing)]

# Overview
An end-to-end quantitative tool to detect "Informed Trading" and "Liquidity Shocks" in Bitcoin markets using high-frequency Binance data.

# Key Features
* VPIN Calculation: Real-time estimation of order flow toxicity.
* Jump Detection: Implementation of the Barndorff-Nielsen & Shephard (BNS) technique.
* Volume Bar Generation: Transforming noisy tick data into information-rich volume segments.

# Visualizations
![Price Chart with Jumps](https://colab.research.google.com/drive/1P_z-BMr7CPXY-CQ6gi_APtBv0Wq761EP#scrollTo=zHA7rDUmeS2v&fullscreenOutput=true)
* Detecting a price jump following a VPIN spike.
