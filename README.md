# Thesis_DSS
Final Thesis: Built a deep learning neural model to correctly detect malaria parasites. After a model was completed, knowledge distillation was used to transfer the "knowledge" to a lighter, smaller neural network. Then gradcam was applied to observe the patters of both neural networks and to generated heatmaps, which were then compared using an image processing technique known as Structural Similarity Index (SSIM). 

Source for the data.  https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets

Source code for the knowledge distillation from here. https://keras.io/examples/vision/knowledge_distillation/

Source code for image comparison method SSIM is from here. https://www.pyimagesearch.com/2014/09/15/python-compare-two-images/

Source code for gradcam is from here. https://keras.io/examples/vision/grad_cam/
