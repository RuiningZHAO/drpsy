# drspy: a Data Reduction toolkit for Spectroscopy and Photometry

## Note

1. No NaNs or infs should be passed into functions without being masked in advance.
2. `use_uncertainty` and `use_mask` only control the use of uncertainty and mask frames in the calculations. Whether the two frames are returned by a function depends on the custom's input.
3. All calculations should be dimensionless to ensure best performence.
4. Header should not convert to meta directly. Should be ```meta = {'header': header}```