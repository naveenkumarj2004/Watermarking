# A Novel Quantum-Enhanced Video Watermarking Technique for Secure and Robust Video Protection

A pseudo-quantum-enhanced video watermarking research project designed to protect digital video content against unauthorized copying, tampering, piracy and signal-processing attacks while maintaining high visual quality.

---

## Patent Information

| Field | Details |
|---|---|
| **Patent Application Number** | 202541122031 |
| **Patent Publication ID** | IN202541122031 |
| **Patent Type** | Published Indian Patent Application |
| **Current Description** | Patent application published; grant status is not claimed in this repository |
| **Official Search Portal** | [IP India Public Search](https://iprsearch.ipindia.gov.in/PublicSearch/) |

To verify the patent publication:

1. Open the IP India Public Search portal.
2. Select the appropriate patent-search option.
3. Search using application number `202541122031`.
4. The publication may also be searched using `IN202541122031`.

> This repository does not claim that the patent has been granted. It documents a published patent application and the associated undergraduate research prototype.

---

## Project Information

| Field | Details |
|---|---|
| **Project Type** | B.Tech Project-II |
| **Institution** | Vellore Institute of Technology |
| **School** | School of Computer Science and Engineering |
| **Department** | Information Security |
| **Project Completion** | April 2025 |
| **Project Title** | A Novel Quantum-Enhanced Video Watermarking Technique for Secure and Robust Video Protection |
| **Patent Application Number** | 202541122031 |
| **Patent Publication ID** | IN202541122031 |
| **Contributors** | Naveen Kumar J, Tamil Kumaran R and Avishkar SP |
| **Project Supervisor** | Dr. Naresh K |
| **Primary Domain** | Multimedia Security and Digital Watermarking |
| **Research Areas** | Video Security, Digital Rights Management, DWT, Pseudo-Quantum Watermarking and Content Protection |

---

## Table of Contents

- [Patent Information](#patent-information)
- [Project Information](#project-information)
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Research Motivation](#research-motivation)
- [Project Objectives](#project-objectives)
- [Research Scope](#research-scope)
- [System Architecture](#system-architecture)
- [Watermarking Workflow](#watermarking-workflow)
- [Methodology](#methodology)
- [Watermarking Techniques](#watermarking-techniques)
- [Technologies Used](#technologies-used)
- [Prototype Implementation](#prototype-implementation)
- [Installation](#installation)
- [Running the Prototype](#running-the-prototype)
- [Evaluation Metrics](#evaluation-metrics)
- [Experimental Results](#experimental-results)
- [Visual Frame Comparison](#visual-frame-comparison)
- [Security Value](#security-value)
- [Applications](#applications)
- [Current Limitations](#current-limitations)
- [Future Enhancements](#future-enhancements)
- [Repository Structure](#repository-structure)
- [Repository Scope](#repository-scope)
- [Contributors](#contributors)
- [Patent and Research Disclaimer](#patent-and-research-disclaimer)

---

## Project Overview

The rapid growth of digital video distribution has increased concerns related to:

- Unauthorized copying
- Digital piracy
- Video tampering
- Ownership disputes
- Illegal redistribution
- Loss of content authenticity
- Modification after decryption
- Removal of ownership information

Encryption can protect video content while it is being transmitted or stored.

However, after the video is decrypted and accessed by an authorized user, it may still be:

- Copied
- Modified
- Shared without authorization
- Re-uploaded to another platform
- Distributed without ownership information

Digital video watermarking addresses this problem by embedding ownership, authentication or tracking information directly into video frames.

The watermark remains associated with the video even after the video is decrypted.

This project proposes a **Pseudo-Quantum Enhanced Video Watermarking technique**, referred to as **QTWM**, that combines classical video watermarking with simulated quantum-inspired operations.

The project evaluates four watermarking approaches:

- Discrete Wavelet Transform watermarking
- Quantum Transformation Method
- Hybrid DWT and QTM
- Hybrid DWT and QTM with Gaussian noise

The purpose of the research is to balance:

- Imperceptibility
- Robustness
- Security
- Computational efficiency
- Watermark recoverability

---

## Problem Statement

Traditional video watermarking methods often struggle to simultaneously achieve:

- High visual quality
- Strong resistance to attacks
- Low processing time
- Secure watermark embedding
- Reliable watermark recovery

Classical watermarking systems may be vulnerable to:

- Compression
- Cropping
- Scaling
- Rotation
- Frame dropping
- Frame shuffling
- Re-encoding
- Gaussian noise
- Watermark removal
- Reverse engineering
- Brute-force attacks

Some watermarking methods provide strong robustness but introduce visible distortion.

Other methods preserve video quality but may be easier to attack or remove.

The emergence of quantum computing also raises concerns regarding the long-term security of traditional cryptographic and watermarking systems.

This project investigates a software-level pseudo-quantum approach that simulates quantum-inspired behaviour using classical computing.

The proposed method aims to improve watermark unpredictability and resilience without requiring real quantum hardware.

---

## Research Motivation

The project was motivated by the growing use of digital video in:

- Online streaming
- Education
- Social media
- Entertainment
- Virtual communication
- Digital publishing
- Medical applications
- Security surveillance

As the commercial and intellectual value of multimedia content increases, content creators and organizations require stronger methods to establish:

- Ownership
- Authenticity
- Integrity
- Traceability
- Usage rights

Traditional encryption alone does not permanently associate ownership information with the content.

The project therefore explores watermarking as an embedded security mechanism that can remain connected to the video after access or decryption.

Pseudo-quantum techniques were investigated because real quantum hardware remains expensive and difficult to access.

Quantum-inspired operations can be simulated using classical algorithms to introduce:

- Randomness
- Unpredictability
- Probabilistic behaviour
- Complex transformations
- Increased resistance to unauthorized analysis

---

## Project Objectives

The main objectives of the project are:

- Design a pseudo-quantum-enhanced video watermarking approach.
- Embed watermark information into digital video frames.
- Preserve the visual quality of the original video.
- Improve watermark robustness against common attacks.
- Compare quantum-inspired watermarking with traditional DWT watermarking.
- Evaluate the effect of Gaussian noise on watermarked frames.
- Improve the balance between imperceptibility and robustness.
- Evaluate watermark quality using PSNR, SSIM and MSE.
- Evaluate watermark recovery using NC and BER.
- Measure processing time per frame.
- Support future digital-rights-management applications.
- Develop a software-level implementation without requiring quantum hardware.
- Investigate the future potential of quantum-inspired multimedia security.

---

## Research Scope

The project focuses on software-based video watermarking using:

- Discrete Wavelet Transform
- Quantization-based or quantum-inspired transformations
- Hybrid DWT and QTM processing
- Gaussian-noise simulation
- Frame-level watermark embedding
- Performance measurement

The project evaluates watermarking performance using:

- Peak Signal-to-Noise Ratio
- Structural Similarity Index
- Mean Squared Error
- Normalized Correlation
- Bit Error Rate
- Entropy
- Correlation
- Processing Time Per Frame

The research is limited to a classical-computing simulation.

It does not use:

- Actual quantum hardware
- Real quantum communication
- Physical qubits
- Production quantum-key-distribution infrastructure
- Real-time commercial video-streaming deployment

---

## System Architecture

The proposed architecture follows an end-to-end watermarking pipeline.

It accepts an original video and watermark information, processes the video frames, embeds the watermark, optionally applies attacks and evaluates the resulting watermarked content.



<img width="1230" height="630" alt="image" src="https://github.com/user-attachments/assets/e50d807d-067a-49c3-916b-a15aeda65cfe" />



### Architecture Components

#### 1. User Interface Module

The user-interface module allows users to:

- Select or upload a video
- Provide watermark information
- Configure embedding parameters
- Start the watermarking process
- View results
- Save the watermarked video

The interface may be implemented as:

- Command-line interface
- Jupyter Notebook
- Desktop graphical interface

#### 2. Video Preprocessing Module

The preprocessing module performs:

- Video loading
- Metadata reading
- Frame extraction
- Frame resizing
- Grayscale conversion
- Data-type conversion
- Frame normalization

The watermark may also be:

- Resized
- Converted to binary
- Normalized
- Scrambled
- Prepared for embedding

#### 3. Watermark Embedding Module

The embedding module:

- Applies DWT to video frames
- Divides frames into frequency sub-bands
- Selects suitable embedding coefficients
- Applies pseudo-quantum transformation
- Embeds watermark bits
- Reconstructs the frame using inverse DWT

#### 4. Attack Simulation Module

The attack-simulation module can evaluate the watermark under:

- Gaussian noise
- Cropping
- Scaling
- Rotation
- Compression
- Re-encoding
- Frame dropping
- Frame shuffling

#### 5. Watermark Extraction Module

The proposed system architecture includes an extraction stage that:

- Applies DWT to received frames
- Identifies the embedding sub-band
- Retrieves watermark information
- Reverses pseudo-quantum transformations
- Reconstructs the extracted watermark

#### 6. Evaluation Module

The evaluation module calculates:

- PSNR
- SSIM
- MSE
- NC
- BER
- Entropy
- Correlation
- Processing time

---

## Watermarking Workflow

The overall process begins by loading a video and extracting selected frames.

The frames are transformed, watermarked and compared against the original frames.

<img width="1120" height="580" alt="image" src="https://github.com/user-attachments/assets/cbabb7f9-a167-46cd-a047-3a3b32e2fd50" />


### Processing Flow

```text
Input Video
        ↓
Video Frame Extraction
        ↓
Frame Preprocessing
        ↓
Watermark Text Conversion
        ↓
Binary Watermark Generation
        ↓
DWT or QTM Watermark Embedding
        ↓
Hybrid DWT and QTM Processing
        ↓
Optional Gaussian-Noise Simulation
        ↓
Watermarked Frame Reconstruction
        ↓
Original and Watermarked Frame Comparison
        ↓
Performance Metric Calculation
        ↓
Result Table and Output Video
```

---

## Methodology

### 1. Video Input

The prototype accepts an input video such as:

```text
input_video.mp4
```

OpenCV is used to:

- Open the video
- Read video metadata
- Move to selected frame positions
- Extract individual frames
- Create output video files

### 2. Frame Selection

The current prototype evaluates selected frames:

```python
selected_frames = [27, 76, 98, 121, 142]
```

These frames are used to compare watermarking performance across different video scenes.

### 3. Watermark Preparation

A text watermark is converted into binary form.

For example:

```text
Watermark
```

Each character is converted into an eight-bit binary representation.

### 4. Frame Transformation

For DWT-based processing, each colour channel is decomposed into:

- Approximation coefficients
- Horizontal-detail coefficients
- Vertical-detail coefficients
- Diagonal-detail coefficients

These are represented as:

```text
cA = Approximation coefficients
cH = Horizontal-detail coefficients
cV = Vertical-detail coefficients
cD = Diagonal-detail coefficients
```

### 5. Watermark Embedding

Watermark bits are inserted into selected frame coefficients or pixel values.

The project evaluates four approaches:

- DWT
- QTM
- DWT and QTM
- DWT and QTM with Gaussian noise

### 6. Frame Reconstruction

Inverse DWT is used to reconstruct the frame after watermark embedding.

The processed values are clipped to the valid pixel range:

```text
0 to 255
```

### 7. Attack Simulation

Gaussian noise is introduced into selected watermarked frames to simulate:

- Transmission distortion
- Signal interference
- Noise-based attacks
- Real-world processing damage

### 8. Metric Calculation

The original and watermarked frames are compared using:

- PSNR
- SSIM
- MSE
- NC
- Entropy
- Correlation
- Processing time

### 9. Output Generation

The prototype:

- Displays original and watermarked frames
- Prints performance tables
- Writes processed frames to output video files

---

## Watermarking Techniques

### Discrete Wavelet Transform Watermarking

Discrete Wavelet Transform separates each video frame into frequency components.

The frame is divided into:

- Approximation sub-band
- Horizontal-detail sub-band
- Vertical-detail sub-band
- Diagonal-detail sub-band

In the prototype, watermark bits are embedded into the horizontal-detail coefficients.

```text
Original Channel
        ↓
DWT Decomposition
        ↓
cA, cH, cV and cD
        ↓
Watermark Embedding in cH
        ↓
Inverse DWT
        ↓
Watermarked Channel
```

#### Advantages

- Good visual quality
- Frequency-domain embedding
- Better robustness than direct pixel modification
- Suitable for image and video watermarking
- Supports multi-resolution analysis

#### Limitations

- Embedding strength requires careful selection
- High embedding strength may introduce distortion
- Very low strength may reduce recoverability

---

### Quantum Transformation Method

The current prototype uses a quantization-based transformation that modifies frame pixel values according to binary watermark bits.

For a watermark bit equal to `1`, the pixel value is increased.

For a watermark bit equal to `0`, the pixel value is decreased.

```text
Watermark Bit = 1 → Pixel Value + QTM Factor

Watermark Bit = 0 → Pixel Value - QTM Factor
```

The project describes this as a pseudo-quantum or quantum-inspired method because it is intended to simulate greater randomness and unpredictability using classical computation.

> The current public prototype does not run on quantum hardware.

#### Advantages

- Simple implementation
- Small frame modification
- Configurable embedding factor
- Low visual distortion when a small factor is used

#### Limitations

- The current prototype does not include a full quantum circuit.
- It does not use physical qubits.
- Security depends on implementation and parameter selection.
- The current code uses deterministic pixel modifications.

---

### Hybrid DWT and QTM

The hybrid approach first applies DWT watermarking.

The resulting frame is then processed using QTM.

```text
Original Frame
        ↓
DWT Watermark Embedding
        ↓
DWT-Watermarked Frame
        ↓
QTM Watermark Embedding
        ↓
Hybrid Watermarked Frame
```

The purpose of the hybrid method is to combine:

- Frequency-domain robustness
- Pixel-level transformation
- Additional watermark complexity
- Greater resistance against attacks

---

### Hybrid DWT and QTM with Gaussian Noise

This approach first applies:

1. DWT watermarking
2. QTM watermarking
3. Gaussian-noise addition

```text
Original Frame
        ↓
DWT
        ↓
QTM
        ↓
Gaussian Noise
        ↓
Noise-Tested Watermarked Frame
```

This method is used to evaluate how the watermarked video behaves under noise-based distortion.

The noise-added result is expected to have lower visual-quality metrics because it is intentionally modified.

---

## Technologies Used

### Programming Language

- Python

### Development Environment

- Jupyter Notebook
- Google Colab
- Visual Studio Code

### Video and Image Processing

- OpenCV
- scikit-image
- Pillow
- FFmpeg

### Numerical Processing

- NumPy
- SciPy
- Pandas

### Wavelet Processing

- PyWavelets

### Data Visualization

- Matplotlib
- Seaborn

### Version Control

- Git
- GitHub

---

## Prototype Implementation

This repository contains the available experimental Python prototype developed for the project.

The prototype performs:

- Video-frame extraction
- DWT watermark embedding
- Quantization-based watermark embedding
- Hybrid DWT and QTM processing
- Gaussian-noise testing
- Frame comparison
- Performance-metric calculation
- Experimental output-video generation

### Prototype Capabilities

- Reads an input MP4 video.
- Selects predefined video frames.
- Embeds a text watermark.
- Applies DWT to individual colour channels.
- Embeds watermark bits in horizontal-detail coefficients.
- Applies QTM-based pixel modification.
- Combines DWT and QTM.
- Adds Gaussian noise.
- Calculates PSNR.
- Calculates SSIM.
- Calculates MSE.
- Calculates normalized correlation.
- Calculates entropy.
- Calculates correlation coefficient.
- Measures processing time.
- Displays original and processed frames.
- Creates experimental output-video files.

### Implementation Status

The repository contains an academic experimental prototype.

It does not represent a complete production implementation of every module described in the research report or patent application.

The available code focuses mainly on:

- Watermark embedding
- Frame processing
- Algorithm comparison
- Quality measurement
- Noise testing

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

Move into the project directory:

```bash
cd YOUR-REPOSITORY-NAME
```

### Create a Virtual Environment

For macOS or Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

For Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

The `requirements.txt` file should contain:

```text
opencv-python
numpy
PyWavelets
matplotlib
scikit-image
pandas
```

---

## Running the Prototype

Place an input video in the project folder and name it:

```text
input_video.mp4
```

Run the Python file:

```bash
python prototype_watermarking.py
```

The script evaluates:

```text
DWT
QTM
DWT + QTM
DWT + QTM + Gaussian Noise
```

Example function calls:

```python
process_video(
    input_video_path,
    watermark_text="Watermark",
    algorithm="DWT"
)

process_video(
    input_video_path,
    watermark_text="Watermark",
    qtm_factor=0.25,
    algorithm="QTM"
)

process_video(
    input_video_path,
    watermark_text="Watermark",
    qtm_factor=0.25,
    algorithm="DWT+QTM"
)

process_video(
    input_video_path,
    watermark_text="Watermark",
    qtm_factor=0.25,
    algorithm="DWT+QTM+Gaussian Noise"
)
```

The script generates output files such as:

```text
output_DWT.mp4
output_QTM.mp4
output_DWT+QTM.mp4
output_DWT+QTM+Gaussian Noise.mp4
```

---

## Evaluation Metrics

### Peak Signal-to-Noise Ratio

PSNR measures the visual quality of the watermarked frame compared with the original frame.

A higher PSNR generally indicates less distortion.

```text
Higher PSNR = Better visual quality
```

### Structural Similarity Index

SSIM evaluates similarity in:

- Structure
- Brightness
- Contrast

```text
SSIM close to 1 = High structural similarity
```

### Mean Squared Error

MSE measures the average squared difference between corresponding pixels.

```text
Lower MSE = Lower distortion
```

### Normalized Correlation

NC measures similarity between original and extracted watermark information.

```text
NC close to 1 = High watermark similarity
```

### Bit Error Rate

BER measures the proportion of watermark bits that are incorrectly recovered.

```text
Lower BER = Better watermark recovery
```

### Entropy

Entropy measures the amount of information or randomness present in the frame.

### Correlation Coefficient

Correlation evaluates the relationship between original and processed pixel values.

```text
Correlation close to 1 = Strong similarity
```

### Processing Time Per Frame

PTPF measures the time required to process one frame.

```text
Lower PTPF = Faster processing
```

---

## Experimental Results

The report compares four watermarking techniques:

- DWT
- QTWM
- DQTWM
- DQTWM with Gaussian noise

<img width="1150" height="695" alt="image" src="https://github.com/user-attachments/assets/e3df3526-8ab9-4046-be3f-a12ef13e6629" />

### Reported Performance Comparison

| Metric | DWT | QTWM | DQTWM | DQTWM with Gaussian Noise |
|---|---:|---:|---:|---:|
| **PSNR** | 71.201 | 89.65 | 71.10 | 71.10 |
| **SSIM** | 0.999 | 1.00 | 0.999 | 0.999 |
| **MSE** | 0.005 | Approximately 0.000071 | 0.005 | 0.005 |
| **NC** | Approximately 1.003 | 1.00 | 1.00 | Approximately 1.003 |
| **BER** | Approximately 0.001 | Approximately 0.000009 | Approximately 0.000 | Approximately 0.000 |
| **Entropy** | 7.114 | 7.11 | 7.113 | 7.113 |
| **Correlation** | 0.999 | 1.00 | 0.999 | 0.999 |
| **PTPF** | Approximately 0.212 seconds | Approximately 0.272 seconds | Approximately 0.309 seconds | Approximately 0.361 seconds |



### PSNR Comparison

The report identifies QTWM as the technique with the highest reported PSNR.

<img width="1140" height="1430" alt="image" src="https://github.com/user-attachments/assets/4f23e043-de97-400d-8ef3-185f80afba54" />


The reported PSNR values suggest:

- QTWM produced the least visible distortion.
- DWT preserved strong visual quality.
- DQTWM maintained high visual quality.
- Gaussian-noise processing increased distortion.

### Structural Similarity and Correlation

<img width="1140" height="700" alt="image" src="https://github.com/user-attachments/assets/06a27472-9a41-4e5b-a2d0-24ac582655fb" />


The report states that:

- QTWM achieved an SSIM of `1.0`.
- QTWM and DQTWM produced NC values close to `1.0`.
- High similarity indicates limited structural change.
- Gaussian-noise testing introduced additional distortion.

### Processing Time

The report identifies DWT as the fastest tested technique.

Approximate processing time per frame:

| Technique | Processing Time Per Frame |
|---|---:|
| DWT | 0.212 seconds |
| QTWM | 0.272 seconds |
| DQTWM | 0.309 seconds |
| DQTWM with Gaussian Noise | 0.361 seconds |

This indicates a trade-off between:

- Processing speed
- Watermark complexity
- Noise robustness
- Security enhancement

---

## Visual Frame Comparison

The report compares selected original and watermarked frames.

<img width="1100" height="640" alt="image" src="https://github.com/user-attachments/assets/a94fd23a-59a7-4ba9-921c-35128b1f99d3" />


The visual comparison includes:

- Original frames
- DWT-watermarked frames
- QTWM-watermarked frames
- DQTWM-watermarked frames
- DQTWM frames with Gaussian noise

The report observes that:

- DWT introduces minimal visible changes.
- QTWM provides high imperceptibility.
- DQTWM maintains a balance between robustness and quality.
- DQTWM with Gaussian noise produces more visible distortion.
- Highly textured regions may show stronger noise artifacts.

---

## Security Value

The project demonstrates how watermarking can support:

- Ownership verification
- Copyright protection
- Digital-rights management
- Tamper detection
- Piracy prevention
- Content authentication
- Forensic tracking
- Unauthorized-distribution investigation

The pseudo-quantum approach investigates whether quantum-inspired transformations can increase:

- Watermark unpredictability
- Resistance to reverse engineering
- Security complexity
- Robustness against attacks

---

## Applications

Potential applications include:

### Entertainment

- Movies
- Television
- Streaming content
- Subscription video services

### Education

- Online course videos
- Lecture recordings
- Training materials
- Copyrighted educational media

### Digital Publishing

- Licensed video content
- Premium media
- Subscription-based publications

### Healthcare

- Medical videos
- Diagnostic recordings
- Telemedicine media

### Security and Forensics

- Surveillance footage
- Digital-evidence tracking
- Ownership verification
- Tamper investigation

### Social Media

- Original creator-content protection
- Unauthorized repost detection
- Content-source identification

### Digital Rights Management

- Usage-right enforcement
- Content tracking
- Ownership registration
- Licensing verification

---

## Current Limitations

### Prototype Limitations

- Only selected video frames are processed.
- The complete video is not processed frame by frame.
- Audio is not preserved in the generated output.
- Watermark extraction is not implemented in the available public prototype.
- BER is not directly calculated by the available public code.
- The prototype does not include secure key management.
- QKD is not implemented using real quantum infrastructure.
- The code does not contain an actual quantum circuit.
- Compression, cropping, scaling and rotation attacks are not fully implemented in the available script.
- The prototype is not optimized for real-time video streaming.
- The current output video contains only the selected processed frames.

### Metric Limitations

- Some calculations in the prototype should convert image arrays to floating-point values before subtraction or dot-product operations.
- Normalized-correlation values from unsigned integer arrays may be affected by overflow.
- Processing-time measurement should evaluate the actual selected algorithm instead of measuring only the DWT function.
- Results should be reproduced after metric-calculation cleanup before making production-level performance claims.

### Research Limitations

- The system uses simulated pseudo-quantum behaviour.
- Actual quantum hardware was not used.
- Results were obtained in an academic experimental environment.
- Production-scale multimedia testing was not performed.
- Large-scale real-time deployment was not validated.
- Patent publication does not automatically mean patent grant.
- The project should not be presented as a commercial security product.

---

## Future Enhancements

### Complete Video Processing

Process every video frame while preserving:

- Frame rate
- Resolution
- Video duration
- Audio synchronization
- Original metadata

### Watermark Extraction

Implement a complete extraction pipeline that:

- Detects embedded watermark locations
- Reverses DWT embedding
- Reverses pseudo-quantum processing
- Recovers the original watermark
- Verifies ownership information

### Bit Error Rate Evaluation

Calculate BER by comparing:

- Original watermark bits
- Extracted watermark bits

### Secret-Key Management

Add:

- Secure random-key generation
- Encrypted key storage
- Session-based keys
- Key rotation
- Key-dependent embedding locations

### Attack Testing

Evaluate the watermark against:

- Gaussian noise
- Salt-and-pepper noise
- Cropping
- Rotation
- Scaling
- Blur
- Sharpening
- Video compression
- Frame dropping
- Frame shuffling
- Format conversion
- Screen recording
- Re-encoding

### Real Quantum Integration

Future versions could investigate:

- Qiskit
- Quantum circuits
- Quantum Fourier Transform
- Hadamard gates
- Quantum-random-number generation
- Quantum-key-distribution simulation
- Access to real quantum-computing services

### Performance Optimization

Future optimization could include:

- GPU acceleration
- Parallel frame processing
- Batch processing
- Multiprocessing
- CUDA
- Cloud deployment

### Digital-Rights-Management Integration

The system could be integrated with:

- Copyright databases
- Blockchain ownership records
- Licensing systems
- Media-distribution platforms
- Content-management systems

### Machine-Learning Integration

Machine learning could be used for:

- Content-adaptive watermark placement
- Attack detection
- Automatic strength adjustment
- Intelligent frame selection
- Piracy detection
- Watermark-recovery enhancement

### User Interface

A future user interface could allow users to:

- Upload videos
- Enter watermark text
- Select watermarking algorithms
- Adjust embedding strength
- Run attack simulations
- View performance graphs
- Download watermarked videos

---

## Repository Structure

```text
patent-watermarking-project/
├── README.md
├── prototype_watermarking.py
├── requirements.txt
├── input_video.mp4
└── images/
    ├── watermarking-flow-model.png
    ├── watermarking-workflow.png
    ├── performance-comparison-table.png
    ├── psnr-ptpf-comparison.png
    ├── nc-ssim-comparison.png
    └── frame-quality-comparison.png
```

> The sample input video does not need to be publicly uploaded if it is copyrighted, private or too large.

---

## Repository Scope

This repository is a public academic and patent-project showcase.

It contains:

- Project documentation
- Patent-application details
- Available experimental prototype code
- Watermarking methodology
- Selected architecture diagrams
- Performance comparisons
- Visual frame comparisons
- Research limitations
- Future development directions

The repository does not necessarily contain:

- The complete patent specification
- Every experiment described in the report
- A complete production implementation
- Real quantum-computing code
- Real quantum hardware integration
- Commercial deployment code
- Confidential legal or university documents
- Private signatures
- Student identification numbers
- Proprietary input videos

---

## Contributors

### Naveen Kumar J

B.Tech in Computer Science and Engineering  
Specialization in Information Security  
Vellore Institute of Technology

### Tamil Kumaran R

B.Tech Project Contributor  
Vellore Institute of Technology

### Avishkar SP

B.Tech Project Contributor  
Vellore Institute of Technology

### Project Supervisor

**Dr. Naresh K**  
Associate Professor Senior  
School of Computer Science and Engineering  
Vellore Institute of Technology

---

## Patent and Research Disclaimer

This repository documents an undergraduate academic research prototype associated with the following published Indian patent application:

- **Patent Application Number:** `202541122031`
- **Patent Publication ID:** `IN202541122031`

The repository does not claim that the patent has been granted.

The patent status should be independently verified through the official IP India Public Search portal:

[https://iprsearch.ipindia.gov.in/PublicSearch/](https://iprsearch.ipindia.gov.in/PublicSearch/)

The implementation is an academic prototype developed for:

- Research
- Education
- Experimental evaluation
- Technical demonstration

It is not a production multimedia-security product.

The performance figures reflect the project report’s experimental methodology and conditions.

The available public code may not implement every module, result or capability described in the complete research report or patent application.
