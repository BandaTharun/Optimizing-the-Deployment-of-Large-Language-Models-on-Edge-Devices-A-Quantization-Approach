# Optimizing-the-Deployment-of-Large-Language-Models-on-Edge-Devices-A-Quantization-Approach




![Research](https://img.shields.io/badge/Research-LLM%20Edge%20Computing-blue) ![Python](https://img.shields.io/badge/Python-3.8+-green) ![Status](https://img.shields.io/badge/Status-Complete-success)

## 🎯 Project Overview

This research investigates deploying Large Language Models on resource-constrained edge devices through quantization techniques. The study compares 5 inference tools and demonstrates successful deployment on real edge hardware.

**Key Achievement**: Llamafile showed 39-46× faster performance than slower alternatives while maintaining quality on 4GB RAM devices.

## 🏆 Main Results

| Tool | Response Time (Single) | Response Time (Multi) | Best For |
|------|----------------------|---------------------|----------|
| **Llamafile** ⭐ | **10.71s** | **38.72s** | Edge deployment |
| Ollama | 13.42s | 193.24s | Local development |
| Llama-cpp | 30.99s | 287.25s | Custom integration |
| LangChain | 73.82s | 1899.82s | Complex applications |
| Ctransformers | 420.82s | 1998.82s | Simple CPU inference |

## 🔬 What Was Done

### Research Methods
- **Quantization Analysis**: Post-training quantization vs quantization-aware training
- **Tool Evaluation**: Systematic testing of 5 popular LLM inference tools
- **Performance Benchmarking**: Response time, CPU usage, memory consumption
- **Edge Validation**: Real deployment on resource-constrained devices

### Key Findings
- **Successful quantization** reduced model size without significant quality loss
- **Llamafile emerged as optimal** for edge deployment scenarios  
- **4GB RAM sufficient** for quantized LLM inference
- **39-46× performance improvement** over slower tools

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/BandaTharun/Optimizing-the-Deployment-of-llm-models.git
cd Optimizing-the-Deployment-of-llm-models



## 🎓 Academic Information

**Author**: Tharun Reddy Banda (Matricula: 51793A)  
**Institution**: Università degli Studi di Milano  
**Course**: Natural Language Processing (Master's in Computer Science)  
**Academic Year**: 2025/2026

## 📊 Research Impact

This work demonstrates the **practical feasibility** of running sophisticated language models on edge devices, enabling:
- **Privacy-preserving AI** (no cloud dependency)
- **Reduced latency** for real-time applications  
- **Cost-effective deployment** on consumer hardware
- **Offline functionality** for remote environments

## 📄 Full Documentation

Complete research methodology, results, and analysis available in: `docs/research_paper.pdf`

---

⭐ **Recommendation**: Use Llamafile for edge LLM deployment - it's fast, efficient, and requires zero installation.
