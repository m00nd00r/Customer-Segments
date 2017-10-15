# Unsupervised Learning
## Creating Customer Segments
### see https://m00nd00r.github.io/Customer-Segments/ for project info

## Install

This project requires **Python 2** and uses the Anaconda package manager.
If you haven't already please download and install Anaconda.

Instructions:
1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/m00nd00r/Custoner-Segments.git
		cd Custoner-Segments
	```
    
2. Obtain the necessary Python packages.  
	
	For __Mac/OSX/Linux__:
	```
		conda create -n segments python=2 numpy pandas matplotlib scikit-learn jupyter
		source activate segments
	```

	For __Windows__:
	```
		conda create -n segments python=2 numpy pandas matplotlib scikit-learn jupyter
		activate segments
	```

### Code

Code is in the notebook `customer_segments.ipynb` notebook file. Additional supporting code can be found in `renders.py`.

### Run

In a terminal or command window, navigate to the top-level project directory `creating_customer_segments/` (that contains this README) and run the following commands:

```jupyter notebook customer_segments.ipynb```

This will open the Jupyter Notebooks in your browser.

## Data

The dataset used in this project is included as `customers.csv`. You can find more information on this dataset on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) page.
