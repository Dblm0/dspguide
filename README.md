## The Scientist and Engineer's Guide to Digital Signal Processing By Steven W. Smith, Ph.D.
http://www.dspguide.com

## Contents

### FOUNDATIONS
#### [Chapter 1 - The Breadth and Depth of DSP][ch1]
- The Roots of DSP
- Telecommunications
- Audio Processing
- Echo Location
- Image Processing
#### [Chapter 2 - Statistics, Probability and Noise][ch2]
- Signal and Graph Terminology
- Mean and Standard Deviation
- Signal vs. Underlying Process
- The Histogram, Pmf and Pdf
- The Normal Distribution
- Digital Noise Generation
- Precision and Accuracy
#### [Chapter 3 - ADC and DAC][ch3]
- Quantization
- The Sampling Theorem
- Digital-to-Analog Conversion
- Analog Filters for Data Conversion
- Selecting The Antialias Filter
- Multirate Data Conversion
- Single Bit Data Conversion
#### [Chapter 4 - DSP Software][ch4]
- Computer Numbers
- Fixed Point (Integers)
- Floating Point (Real Numbers)
- Number Precision
- Execution Speed: Program Language
- Execution Speed: Hardware
- Execution Speed: Programming Tips

### FUNDAMENTALS
#### [Chapter 5 - Linear Systems][ch5]
- Signals and Systems
- Requirements for Linearity
- Static Linearity and Sinusoidal Fidelity
- Examples of Linear and Nonlinear Systems
- Special Properties of Linearity
- Superposition: the Foundation of DSP
- Common Decompositions
- Alternatives to Linearity
#### [Chapter 6 - Convolution][ch6]
- The Delta Function and Impulse Response
- Convolution
- The Input Side Algorithm
- The Output Side Algorithm
- The Sum of Weighted Inputs
#### [Chapter 7 - Properties of Convolution][ch7]                      
- Common Impulse Responses
- Mathematical Properties
- Correlation
- Speed
#### [Chapter 8 - The Discrete Fourier Transform][ch8]
- The Family of Fourier Transform
- Notation and Format of the Real DFT
- The Frequency Domain's IndependentVariable
- DFT Basis Functions
- Synthesis, Calculating the Inverse DFT
- Analysis, Calculating the DFT
- Duality
- Polar Notation
- Polar Nuisances
#### [Chapter 9 - Applications of the DFT][ch9]
- Spectral Analysis of Signals
- Frequency Response of Systems
- Convolution via the Frequency Domain
#### [Chapter 10 - Fourier Transform Properties][ch10]
- Linearity of the Fourier Transform
- Characteristics of the Phase
- Periodic Nature of the DFT
- Compression and Expansion, Multirate methods
- Multiplying Signals (Amplitude Modulation
- The Discrete Time Fourier Transform
- Parseval's Relation
#### [Chapter 11 - Fourier Transform Pairs][ch11]
- Delta Function Pairs
- The Sinc Function
- Other Transform Pairs
- Gibbs Effect
- Harmonics
- Chirp Signals
#### [Chapter 12 - The Fast Fourier Transform][ch12]
- Real DFT Using the Complex DFT
- How the FFT works
- FFT Programs
- Speed and Precision Comparisons
- Further Speed Increases
#### [Chapter 13 - Continuous Signal Processing][ch13]
- The Delta Function
- Convolution
- The Fourier Transform
- The Fourier Series

### DIGITAL FILTERS
#### [Chapter 14 - Introduction to Digital Filters][ch14]
 - Filter Basics
 - How Information is Represented in Signals
 - Time Domain Parameters
 - Frequency Domain Parameters
 - High-Pass, Band-Pass and Band-Reject Filters
 - Filter Classification
#### [Chapter 15 - Moving Average Filters][ch15]
 - Implementation by Convolution
 - Noise Reduction vs. Step Response
 - Frequency Response
 - Relatives of the Moving Average Filter
 - Recursive Implementation
#### [Chapter 16 - Windowed-Sinc Filters][ch16]
 - Strategy of the Windowed-Sinc
 - Designing the Filter
 - Examples of Windowed-Sinc Filters
 - Pushing it to the Limit
#### [Chapter 17 - Custom Filters][ch17]
 - Arbitrary Frequency Response
 - Deconvolution
 - Optimal Filters
#### [Chapter 18 - FFT Convolution][ch18]
 - The Overlap-Add Method
 - FFT Convolution
 - Speed Improvements
#### [Chapter 19 - Recursive Filters][ch19]
 - The Recursive Method
 - Single Pole Recursive Filters
 - Narrow-band Filters
 - Phase Response
 - Using Integers
#### [Chapter 20 - Chebyshev Filters][ch20]
 - The Chebyshev and Butterworth Responses
 - Designing the Filter
 - Step Response Overshoot
 - Stability
#### [Chapter 21 - Filter Comparison][ch21]
 - Match #1: Analog vs. Digital Filters
 - Match #2: Windowed-Sinc vs. Chebyshev
 - Match #3: Moving Average vs. Single Pole

### APPLICATIONS
#### [Chapter 22 - Audio Processing][ch22]
- Human Hearing
- Timbre
- Sound Quality vs. Data Rate
- High Fidelity Audio
- Companding
- Speech Synthesis and Recognition
- Nonlinear Audio Processing
#### [Chapter 23 - Image Formation & Display][ch23]
- Digital Image Structure
- Cameras and Eyes
- Television Video Signals
- Other Image Acquisition and Display
- Brightness and Contrast Adjustments
- Grayscale Transforms
- Warping
#### [Chapter 24 - Linear Image Processing][ch24]
- Convolution
- 3x3 Edge Modification
- Convolution by Separability
- Example of a Large PSF: Illumination Flattening
- Fourier Image Analysis
- FFT Convolution
- A Closer Look at Image Convolution
#### [Chapter 25 - Special Imaging Techniques][ch25]
- Spatial Resolution
- Sample Spacing and Sampling Aperture
- Signal-to-Noise Ratio
- Morphological Image Processing
- Computed Tomography
#### [Chapter 26 - Neural Networks (and more!)][ch26]
- Target Detection
- Neural Network Architecture
- Why Does it Work
- Training the Neural Network
- Evaluating the Results
- Recursive Filter Design
#### [Chapter 27 - Data Compression][ch27]
- Data Compression Strategies
- Run-Length Encoding
- Huffman Encoding
- Delta Encoding
- LZW Compression
- JPEG (Transform Compression
- MPEG
#### [Chapter 28 - Digital Signal Processors][ch28]
- How DSPs are Different from Other Microprocessors
- Circular Buffering
- Architecture of the Digital Signal Processor
- Fixed versus Floating Point
- C versus Assembly
- How Fast are DSPs
- The Digital Signal Processor Market
#### [Chapter 29 - Getting Started with DSPs][ch29]
- The ADSP-2106x family
- The SHARC EZ-KIT Lite
- Design Example: An FIR Audio Filter
- Analog Measurements on a DSP System
- Another Look at Fixed versus Floating Point
- Advanced Software Tools

### COMPLEX TECHNIQUES
#### [Chapter 30 - Complex Numbers][ch30]
- The Complex Number System
- Polar Notation
- Using Complex Numbers by Substitution
- Complex Representation of Sinusoids
- Complex Representation of Systems
- Electrical Circuit Analysis
#### [Chapter 31 - The Complex Fourier Transform][ch31]
- The Real DFT
- Mathematical Equivalence
- The Complex DFT
- The Family of Fourier Transforms
- Why the Complex Fourier Transform is Used
#### [Chapter 32 - The Laplace Transform][ch32]
- The Nature of the s-Domain
- Strategy of the Laplace Transform
- Analysis of Electric Circuits
- The Importance of Poles and Zeros
- Filter Design in the s-Domain
#### [Chapter 33 - The z-Transform][ch33]
- The Nature of the z-Domain
- Analysis of Recursive Systems
- Cascade and Parallel Stages
- Spectral Inversion
- Gain Changes
- Chebyshev-Butterworth Filter Design
- The Best and Worst of DSP
#### [Chapter 34 - Explaining Benford's Law][ch34]
- Frank Benford's Discovery
- Homomorphic Processing
- The Ones Scaling Test
- Writing Benford's Law as a Convolution
- Solving in the Frequency Domain
- Solving Mystery #1
- Solving Mystery #2
- More on Following Benford's law
- Analysis of the Log-Normal Distribution
- The Power of Signal Processing


<!-- references -->
[ch1]:./chapters/CH1.PDF
[ch2]:./chapters/CH2.PDF
[ch3]:./chapters/CH3.PDF
[ch4]:./chapters/CH4.PDF

[ch5]:./chapters/CH5.PDF
[ch6]:./chapters/CH6.PDF
[ch7]:./chapters/CH7.PDF
[ch8]:./chapters/CH8.PDF
[ch9]:./chapters/CH9.PDF
[ch10]:./chapters/CH10.PDF
[ch11]:./chapters/CH11.PDF
[ch12]:./chapters/CH12.PDF
[ch13]:./chapters/CH13.PDF

[ch14]:./chapters/CH14.PDF
[ch15]:./chapters/CH15.PDF
[ch16]:./chapters/CH16.PDF
[ch17]:./chapters/CH17.PDF
[ch18]:./chapters/CH18.PDF
[ch19]:./chapters/CH19.PDF
[ch20]:./chapters/CH20.PDF
[ch21]:./chapters/CH21.PDF

[ch22]:./chapters/CH22.PDF
[ch23]:./chapters/CH23.PDF
[ch24]:./chapters/CH24.PDF
[ch25]:./chapters/CH25.PDF
[ch26]:./chapters/CH26.PDF
[ch27]:./chapters/CH27.PDF
[ch28]:./chapters/CH28.PDF
[ch29]:./chapters/CH29.PDF

[ch30]:./chapters/CH30.PDF
[ch31]:./chapters/CH31.PDF
[ch32]:./chapters/CH32.PDF
[ch33]:./chapters/CH33.PDF
[ch34]:./chapters/CH34.PDF

