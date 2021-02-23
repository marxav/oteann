# oteann
This project includes the code of the Artificial Neural Network used for the [OTEANN](https://arxiv.org/abs/1912.13321) paper. 
* [oteann.ipynb](oteann.ipynb) contains the ANN code
* [oteann_results_2019-12-27.csv](oteann_results_2019-12-27.csv) contains a set of example results
* [oteann_display_results.ipynb](oteann_display_results.ipynb) allows displaying a CSV set of results

The OTEANN ANN allows:
* translating a pronounced word into a spelled word;
* or translating a spelled word into a pronounced word.

Both words and pronunciations are encoded as a sequence of Unicode characters.

![](oteann-writing.png?raw=true)

![](oteann-reading.png?raw=true)

## Citation
This code was used for the following paper:
```bibtex
@misc{marjou2020oteann,
      title={OTEANN: Estimating the Transparency of Orthographies with an Artificial Neural Network}, 
      author={Xavier Marjou},
      year={2020},
      eprint={1912.13321v1},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
