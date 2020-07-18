Multi-H Dataset is a data set for multiple homographies estimation and fundamental matrix estimation. It's created with software blender. 

The dataset is ordered by different image pairs. There are

1. Right.png - right image
2. Left.png - left image
3. ground_truth.txt - the calculated ground truth of multiple homographies matrices. 
4. ground_truthX.py - the python code to calculate the ground truth
5. Normal_cass_XX.blend - the blender scene where the image comes from.

And man can use the blender file with the ground_truth.py file to create own image pair. The detail can be got from the thesis:`https://git.scc.kit.edu/hc9025/thesis-bo-cao`