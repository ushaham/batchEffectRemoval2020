Repository for the paper "Removal of Batch Effects using Distribution-Matching Residual Networks" by Uri Shaham, Kelly P. Stanton, Jun Zhao, Huamin Li, Khadir Raddassi, Ruth Montgomery, and Yuval Kluger.

Requirements:
    Python 3.7.4
    PyTorch1.4
    
Usage example:

python train.py --file1 <path_to_sample1> --file2 <path_to_sample2>

The two sample files need to be in .csv format, where each line corresponds to a data point and each column to a marker. Both files need to have he same number of columns.

Any further questions should be referred to Uri Shaham, uri.shaham@yale.edu
