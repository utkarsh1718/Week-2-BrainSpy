# Week-2-BrainSpy
In this task, I focused on understanding and visualizing MRI data in both NIfTI (.nii/.nii.gz) and DICOM (.dcm) formats. The approach was divided into several clear steps aligned with the problem statement:
Step 1: Loading and Inspecting Data
Step 2: Metadata ExtractionStep 
Step 3: Stacking and Visualization
Step 4: Orientation and Format Comparison

For DICOM, the conversion from .nii.gz was done using SimpleITK, writing each slice to .dcm.
Converting NIfTI to DICOM required careful handling of voxel types (float32 not supported by default in GDCM).
DICOM visualization was more sensitive to file ordering, requiring robust sorting logic.
Finding a valid DICOM dataset online was time-consuming due to broken or expired links.

CONCLUSION.
This task helped build practical experience with 3D medical imaging data. I now understand the structural differences between DICOM and NIfTI formats, how to load and visualize them in Python, and the challenges of working with real-world clinical data formats.
