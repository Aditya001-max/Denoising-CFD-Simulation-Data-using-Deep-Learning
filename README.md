# Denoising-CFD-Simulation-Data-using-Deep-Learning

# Method to use this File

1. Clone Repository
```
git clone https://github.com/Aditya001-max/Denoising-CFD-Simulation-Data-using-Deep-Learning.git  
cd Denoising-CFD-Simulation-Data-using-Deep-Learning

```
2. Install Requirements
Make sure you have Python 3 and necessary dependencies (e.g., numpy, scipy, tensorflow/keras, or pytorch).
Install using:
```
pip install -r requirements.txt
```
3. Obtain and Organize Data
Follow the repository’s instructions.md to download sample CFD datasets.
Place the datasets into the data/ folder, mirroring the example structure.
Your folder hierarchy should look like:
```
data/
  noisy_simulation.npy
  clean_simulation.npy
  ...
```
4. Run the Example Script
Open example in python conda environment.
Check and update file paths so that they point to your data in data/.
Adjust RPCA parameters (like thresholds or decomposition settings) as per question.

5. Run the Example
In MATLAB, run:
```
matlab
```
Or in Python:
```
python example.py
```
This script applies RPCA to noisy CFD data and visualizes the clean/low-rank output.
6. Apply to Your Own Data
- Add your CFD output (e.g., .npy, .mat) to the same folder.
- Ensure example.m or example.py references your files.
- Run the script to denoise your data and save outputs.

7. Analyze Results
Outputs typically include:
- Recovered low-rank fields (denoised phenomenon)
- Sparse components (noise or anomalies)
- Visualization plots or animated flows
8. Save or Export Outputs

