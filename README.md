# This README File is Still Under Construction
# DFRWS APAC 2023 Workshop: 
## Forensic Insights from Electromagnetic Radiation

### Introduction
Our digital electronics generate electromagnetic radiation. These radiation patterns are shown to be correlating with the internal operations of electronics circuitry. Electromagnetic side-channel analysis (EM-SCA) is the field that exploits electromagnetic radiation emitted from computing devices to exfiltrate sensitive information. EM-SCA can take us to places where the classical digital forensics approaches cannot go. This workshop is aimed at providing the foundation into the exciting field of EM-SCA for digital forensics, arming the participants with the required skills and directions to go deep into this field. During this half-day workshop, the participants will be exposed to the Software Defined Radio (SDR) equipment that can be used to acquire electromagnetic radiation, i.e., HackRF SDRs, and the procedure to capture, process, and analyse electromagnetic radiation from a diverse set of devices-under-test (DUT) — including IoT devices and smartphones — to extract forensically-useful insights.

### Workshop Agenda

#### Part 1:
1. Introduction and background
2. SDR hardware.
3. SDR software.
4. Capturing EM side-channel radiation.

#### Part 2:
5. Analysing EM dataset using Python.

### Preparing Your Computer for the Workshop

1. You need to have a computer with a GNU/Linux operating system running natively or as a virtual machine.
2. Instal the following necessary Python libraries.
3. Install Jupyter Notebook
4. Install GNURadio Companion (GRC) software.
5. Clone this Git repository so that you get the Jupyter Notebook files (.ipynb) that contains the code examples.

### Getting the Dataset

In this workshop, we will be using an EM dataset. In compressed form, it has a size of arund 12 GB. After uncompressing, it will be around 53 GB. There are two ways to get the EM dataset.

#### Option 1:
If you are physically attending the workshop in Singapore, we will provide plenty of USB sticks that have the dataset. So, you can simply copy the dataset to your computer during the workshop.

#### Option 2:
If you are joining the workshop remotely (online), or prefer to have the dataset in advance, you can download it from the following URL: https://aseados.ucd.ie/datasets/EMSCA/em-dataset.h5.gz
MD5 Hash value of the uncompressed dataset file (em-dataset.h5): b998495b45e7aea27e1912ea060d404d

See you at the workshop! 
