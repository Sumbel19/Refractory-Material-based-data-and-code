# Refractory-Materials-based-data-and-code
The design present in this research work is a unique and robust which covers a wider range of shapes of meta-absorbers made up of different materials. The dataset containing 52,000 samples is collected via commercial EM software i.e., CST Microwave Studio®. This dataset is employed for the forward and inverse design models presented in the work "AI-Driven Rapid Optimization for Nano-Meta-Photonics".

This Repository contains the image and absorption spectrum dataset collected against the geometrical input parameters for "Machine-learning-driven accelerated deign-method for Meta-devices".

The code files for both Forward and Inverse models are also shared. 

The file input_data.csv has variation over geometrical parameters.

The zip file contains rgb images of 3D meta-atoms having various shapes and made of different materials (indicated by the color of the nano-resonator).

output_data.csv: The outputs are [500x1] vectors which are the absorption spectrums over the broadband wavelength range (300nm-1200nm) to cover the optical domain of the EM spectrum. The role of these inputs and outputs is reversed for inverse design model. (The data limit of 25 MB here on github made it impossible to load the file altogether. Therefore, the absorption files for each materials are uploaded separately. When to be used in codes they must be combined first in order "Chromium, Molybdenum, Niobium, Rhenium, Tantalum, Titanium, Tungsten, ZrN, V and TiN".

Overall dataset contains sixteen (16) shapes of ten (10) refractory materials.
