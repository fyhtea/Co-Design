# **Co-design for Deep Learning**
A collection of works for software/hardware co-design in deep learning.

## **Benchmarks**
- [BenchNN, IISWC,2012](https://pdfs.semanticscholar.org/d93c/d4e26b6f74d6560023cfa96c93862cf96fe9.pdf?_ga=2.38439075.1603099740.1509953943-120118359.1490099485)
- [Fathom, IISWC,2016](https://pdfs.semanticscholar.org/9bde/366e1897ad3b370b3bc473b0de456c75f078.pdf?_ga=2.38439075.1603099740.1509953943-120118359.1490099485)
- [DeepBench, 2016](https://github.com/baidu-research/DeepBench)
- [BenchIP, 2017](https://pdfs.semanticscholar.org/c94c/2cf52fef0503c09268c7d1faee60465ee08e.pdf?_ga=2.97230879.1603099740.1509953943-120118359.1490099485)

## **Architecture**
### #综合讨论类
- QAPPA : A Framework for Navigating Quality-Energy Tradeoffs with Arbitrary Quantization
- `Understanding the Impact of Precision Quantization on the Accuracy and Energy of Neural Networks(DATE, 2017, Brown)`


### #One-size-fits-all(取worst case作为量化设计的考虑)
- DianNao:A Small-Footprint High-Throughput Accelerator for Ubiquitous Machine-Learning
- Minerva:Enabling Low-Power,Highly-Accurate Deep Neural Network Accelerators
 
### #KU Leuven(通过动态精度调节实现对量化的支持)
- `DVAFS:Trading Computational Accuracy for Energy Through Dynamic-Voltage-Accuracy-Frequency-Scaling (DATE,2017,KU Leuven)`
- ENVISION:A 0.26-to-10TOPS/W Subword-Parallel Dynamic-Voltage-Accuracy-Frequency-Scalable Convolutional Neural Network Processor in 28nm FDSOI (ISSCC,2017,KU Leuven)
- `Minimum Energy Quantized Neural Networks (Arxiv,2017,KU Leuven)`

### #Toronto(通过串行地执行每一位实现对量化的支持)
- Proteus:Exploiting Numerical Precision Variability in Deep Neural Networks(ICS,2016)
- `Stripes: Bit-Serial Deep Neural Network Computing(IEEE Computer Architecture Letters,2016)`
- `Bit-pragmatic Deep Neural Network Computing (MICRO,2017)`
- Loom: Exploiting Weight and Activation Precisions to Accelerate Convolutional Neural Networks(Arxiv, 2017)
- Dynamic Stripes: Exploiting the Dynamic Precision Requirements of Activation Values in Neural Networks(Arxiv, 2017)
- Tartan: Accelerating Fully-Connected and Convolutional Layers in Deep Learning Networks by Exploiting Numerical Precision Variability(Arxiv, 2017)

### #Brown University(power of 2量化，乘加计算简化为移位)
- `Hardware-Software Codesign of Accurate, Multiplier-free Deep Neural Networks(DAC, 2017)`
- Understanding the Impact of Precision Quantization on the Accuracy and Energy of Neural Networks(DATE, 2017)

### #BinaryNet(binaryNet, 通过位运算实现)
- YodaNN: An Ultra-Low Power Convolutional Neural Network Accelerator Based on Binary Weights(ISVLSI,2016)
- FINN: A Framework for Fast, Scalable Binarized Neural Network Inference(FPGA, 2017)
- `Accelerating Binarized Neural Networks: Comparison of FPGA, CPU, GPU, and ASIC(2017, intel)`


## **Modeling for Hardware**

- Aladdin: APre-RTL, Power-Performance Accelerator Simulator Enabling Large Design Space Exploration of Customized Architectures
- PARADE: A Cycle-Accurate Full-System Simulation Platform for Accelerator-Rich Architectural Design and Exploration
- Co-Designing Accelerators and SoC Interfaces using gem5-Aladdin

## **Automatic Generation**
- Automatic Generation of Efficient Accelerators for Reconfigurable Hardware(ISCA,16,Stanford)

## **Tutorial & survey**

- [Effient ..]()
- [ISVLSI]()

## **Related Resources**

- [Quantization](https://github.com/aaron-xichen/pytorch-playground/blob/master/roadmap_zh.md)
- [embedded_ai](https://github.com/PerfXLab/embedded_ai)
