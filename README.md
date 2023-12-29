# Plamsa-image-denoising

# Abstract
Imaging diagnostics, which offers information about the tokamak plasma edge as well as the plasma interior, facilitates the realization of plasma shape and position, impurity distribution, and Magneto-hydrodynamics (MHD) instabilities. Tomographic reconstruction is one of the powerful tools to analyze imaging diagnostic data.  The imaging diagnostic is contaminated with noises with a wide variety of origins. Hence, denoising these images relaxes the computational expenses for the tomographic reconstructions and the edge detection algorithms. In this work, we compare the performance of five different Deep Learning (DL) based techniques (REDNet, MWCNN, PRIDNet, CBDNet, and DnCNN) and six traditional denoising methodologies (Median, Gaussian, Bilateral, Wiener, BM3D, NLM). DL-based methods are trained using a synthetic dataset containing a variety of images where stochastic noises of different distributions have been added. Denoising is performed on a simulated noisy image of the circular tokamak plasma, in the visible range, for tangential viewing geometry. The denoising quality is observed as a function of noise magnitude. The Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM) values are estimated for each denoising attempt. The comparison suggests that the machine learning (ML) based method, MWCNN, shows promising results across different noise values while showing impressive PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index Measure) values in the order of 55.98 and 0.999 respectively. It is also observed that the ML models show poor results when the training data is not sufficient. Therefore, unlike conventional denoising methodologies, for desirable results, we need substantially diverse training data for satisfactory results. However, our results show that DL-based denoising methods perform better than widely used conventional methodologies, and open up many possibilities for research requiring denoising as a precursor for several plasma imaging-based diagnostics.
