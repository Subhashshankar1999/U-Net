# U-Net
This project aims to classify the cancerous part in thyroid nodules in ultrasound images. Ultrasound imaging is one of the frequently used diagnostic tools to detect and classify abnormalities of the thyroid gland. In this proposed method, we have the following stages: Pre-processing the ultrasound image to reduce noise and highlight important features. In pre-processing, we resize the input image and pass it through three different filters and transformations that is a bilateral filter, wavelet transformation, and Fourier transformation. The final image is a sum of all three processed images where 80% is of bilateral filter, 15% is of Fourier transformed image, and 5% is of wavelet transformed image. With the help of Cuda, we train a model based on U-Net architecture.
