# Reproduce Figure Plots for GPT-4-LLM 

The notebooks are developed to produce the figure plots in the paper: 

```
``Instruction Tuning with GPT-4'' (https://arxiv.org/abs/2304.03277)
Baolin Peng*, Chunyuan Li*, Pengcheng He*, Michel Galley, Jianfeng Gao (*Equal Contribution)
```

#### Install

Please install the required packages before running the plot generation code.

```
pip install -r requirements.txt
```

#### 1. Reproduce all figure plots in the paper

Select the `main_plots.ipynb` notebook and execute the included code. Note that without modification, we have copyed our extracted results into the notebook, and script will output figures in the paper. Some related data for plots have been provided in [data](./data), the generated plots are saved in [output](./output) If you've run your own training and wish to plot results, you'll have to organize your results in the same format instead. 

Shortcut: to skip all the work and just see the results, take a look at this notebook with [cached plots](./main_plots.ipynb).


#### 2. Analyze GPT-4 Output for Alpaca Instructions

Select the `instruction_visualize_gpt4.ipynb` notebook and execute the included code.

