# Esp32-Cam-3-First-Letters-Prizes-First-Title-Prize

# Image. 
Submissions must be an image of the virtually unrolled segment, showing visible and legible text.
Submit a single static image showing the text region. Images must be generated programmatically, as direct outputs of CT data inputs, and should not contain manual annotations of characters or text.
For the First Title Prize, please illustrate the ink predictions in spatial context of the title search, similar to what is shown here. You do not have to read the title yourself, but just have to produce an image of it that our team of papyrologists are able to read.
Specify which scroll the image comes from. For multiple scrolls, please make multiple submissions.
Include a scale bar showing the size of 1 cm on the submission image.
Specify the 3D position of the text within the scroll. The easiest way to do this is to provide the segmentation file (or the segmentation ID, if using a public segmentation).

# Methodology. 
A detailed technical description of how your solution works. We need to be able to reproduce your work, so please make this as easy as possible:
For fully automated software, consider a Docker image that we can easily run to reproduce your work, and please include system requirements.
For software with a human in the loop, please provide written instructions and a video explaining how to use your tool. We’ll work with you to learn how to use it, but we’d like to have a strong starting point.
Please include an easily accessible link from which we can download it.

# Hallucination mitigation. 
If there is any risk of your model hallucinating results, please let us know how you mitigated that risk. Tell us why you are confident that the results you are getting are real.
We strongly discourage submissions that use window sizes larger than 0.5x0.5 mm to generate images from machine learning models. This corresponds to 64x64 pixels for 8 µm scans. If your submission uses larger window sizes, we may reject it and ask you to modify and resubmit.

# Other information. 
Feel free to include any other things we should know.
