# Neuroimaging-Analysis-Machine-Learning-Tools
Compilation of scripts used for neuroimaging analysis, including homogenized segmentation and ML

gen_graphs_fin.ipynb: python notebook detailing my segmentation algorithm of an aging brain. Gray matter (GM) segmented using a subject-specific anatomical atlas, and white matter (WM) and white matter hyperintensities (WMH) segmented using solid angles. This results in a fairly comprehensive mapping of aging brains with unique brain geometries with homogenized (relatively anatomically consistent) nodes and edges. Suitable for graph neural networks, where node index and edge index ideally conveys spatial information across a cohort. 
