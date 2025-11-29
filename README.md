## **README**

- This project simulates a simplified Continuous-Variable Quantum Key Distribution (CV-QKD) system.  
- It models Gaussian modulation at Alice and transmission through a lossy, noisy optical fiber.  
- Bob performs homodyne detection with realistic imperfections such as detector inefficiency and electronic noise.  
- Parameter estimation is carried out using variances and covariance between Alice’s and Bob’s data.  
- A toy model is used to approximate Eve’s possible information for visualization.  
- The mutual information and the toy secret key rate are calculated across different fiber distances.  
- Plots show how optical transmittance and SNR degrade as distance increases.  
- The key rate decreases steadily and collapses sharply near 40 km.  
- Beyond this distance, secure key generation is no longer possible under the chosen parameters.  
- The notebook provides a clear physical-layer understanding of how distance and noise limit CV-QKD performance.

  
