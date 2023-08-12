# Astronomical-Data-Science-with-python
This project is based on the study of astronomical data of galaxy M100 using python.
I have used python libraries to process the galaxy images and have made my inferences about the galaxy's characteristic features.

# INTRODUCTION TO FITS:
FITS (Flexible Image Transport System) is a widely used format for storing and sharing scientific data, especially in the field of astronomy and astrophysics. FITS image datasets are a specific type of data stored in the FITS format, primarily containing images captured by telescopes and other imaging instruments.

FITS image datasets enable astronomers to explore the universe's mysteries, study celestial objects, and uncover new phenomena. The format's flexibility accommodates a wide range of observations, from visible light to radio waves and beyond.

Astronomical organizations and observatories curate extensive archives of FITS image datasets, making them available to researchers for retrospective analysis, comparision, and discoveries.

Researchers use specialized software to process, enhance, and analyze FITS image datasets. These tools extract valuable insights, enhance image quality, and reveal hidden patterns.

# IMAGE PROCESSING OF FITS DATASETS:
Here's an overview of the image processing of FITS datasets:

**1. Preprocessing:**
   - **Bias Correction:** Remove electronic noise by subtracting the bias level from the image.
   - **Dark Subtraction:** Reduce thermal noise by subtracting dark frames (images taken with the shutter closed).
   - **Flat Fielding:** Correct for non-uniformities in sensitivity by dividing the image by a flat-field frame.

**2. Image Enhancement:**
   - **Stretching:** Adjust pixel values to utilize the full dynamic range for better visualization and contrast.
   - **Histogram Equalization:** Enhance details by redistributing pixel values to create a more balanced histogram.
   - **Color Mapping:** Assign colors to different wavelengths or intensities to reveal specific features.

**3. Image Registration:**
   - **Alignment:** Correct for small shifts or rotations between images, ensuring accurate comparison and analysis.
   - **Stacking:** Combine multiple images of the same object to improve signal-to-noise ratio and reveal faint details.

**4. Noise Reduction:**
   - **Median Filtering:** Replace each pixel value with the median value of its neighbors to reduce random noise.
   - **Gaussian Filtering:** Smooth the image while preserving important features using a Gaussian filter.

**5. Point Source Detection:**
   - **Aperture Photometry:** Measure the flux of point sources (stars) by analyzing light within a specified aperture.
   - **PSF Fitting:** Model point spread functions (PSFs) to accurately estimate source positions and fluxes.

**6. Feature Extraction:**
   - **Segmentation:** Identify distinct regions or objects in the image using techniques like thresholding or watershed.
   - **Morphological Operations:** Analyze object shapes, sizes, and orientations through operations like erosion and dilation.

**7. Spectral Analysis:**
   - **Spectral Extraction:** Separate data into spectral components for analysis in spectroscopy.
   - **Line Fitting:** Identify and measure spectral lines to determine properties like redshift and chemical composition.

**8. Data Visualization:**
   - **Image Combination:** Merge multiple images or data cubes to create composite images or multi-dimensional visualizations.
   - **Image Annotation:** Add labels, markers, and scale bars to aid in interpretation and communication.

**9. Calibration and Metadata:**
   - **Wavelength Calibration:** Convert pixel positions to physical wavelengths using calibration data.
   - **Metadata Utilization:** Incorporate header information for accurate interpretation and context.

# CONCLUSION
Advanced image processing often involves custom algorithms, machine learning, and specialized software tailored to the specific characteristics of FITS datasets. The goal of image processing in the context of FITS datasets is to uncover hidden details, reduce noise, and prepare the data for further analysis, ultimately contributing to our understanding of celestial objects and phenomena.
