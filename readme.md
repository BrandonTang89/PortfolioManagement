# QRT Portfolio Optimisation

## Dependencies

Most of the requirements are in `requirements.txt`.
Apart from that, the model I wrote uses [pytorch](https://pytorch.org/get-started/locally/#windows-prerequisites) which has somewhat complicated installation processes.

## Factor Selection

We have some issues in alignment of data. Many of the factors are published at different time scales. Particularly true for the fundamental factors like `TR.InvtrPriceToBook` or `TR.F.EVToEBITDA`.
