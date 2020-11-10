# LLLR: Toy-model
A simple 3-layer fully connected network performing the density ratio estimation using the loss for log-likelihood ratio estimation (LLLR).

The structure of this project is inherited from [the SPRT-TANDEM code](https://github.com/TaikiMiyagawa/SPRT-TANDEM).  

## Tested Environment
- Python 3.5
- tensorflow 2.0.0
- CUDA 10.0
- cuDNN 7.6.4.38

## Tutorial 

## Example Results
![iteration-NMSE plot](./example_results/LLLRvsCE_NMSE.png)

## Files and Directories
 - utils
 - config
 - example_results
  
## Citation
___Please cite our paper if you use the whole or a part of our codes.___
```
Bibtex:

@misc{SPRT_TANDEM2020,
    title={Deep Neural Networks for the Sequential Probability Ratio Test on Non-i.i.d. Data Series},
    author={Akinori F. Ebihara and Taiki Miyagawa and Kazuyuki Sakurai and Hitoshi Imaoka},
    year={2020},
    eprint={2006.05587},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}

```
