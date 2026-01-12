# Multi-Modal Music Clustering using VAEs

A comprehensive study of unsupervised music genre clustering using variational autoencoders (VAEs) with hybrid audio and text modalities.

## 📋 Overview

This project investigates three progressively complex tasks:
1. **Task 1 (Easy)**: Synthetic multilingual lyrics clustering with MLP-VAE
2. **Task 2 (Medium)**: Real FMA audio + metadata using Conv-VAE
3. **Task 3 (Hard)**: Conditional VAE with genre labels and advanced metrics

## 📊 Key Findings

- **Audio features dominate**: Silhouette score of 0.153 (audio) vs 0.066 (text)
- **Naive fusion fails**: Concatenated audio+text degrades to 0.059
- **CVAE preserves structure**: Conditioning on genre labels maintains clustering quality

## 📁 Project Structure

