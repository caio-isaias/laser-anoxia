# Folder structure

![Folder sctructure example](./folder_structure_example.png)

Folders \_h (human) and \_m (machine) contain, respectively the code script (jupyter notebook) and code output.

Folders in the same level as `feature-selection`,`parameter-analysis` and `unsupervised-ml-analysis` are independet, meaning that files in each of their output folder(\_m) aren't needed their function. Folder in different levels should be depedent, as `data-processing/_m` are needed to each of the lower folder analysis.