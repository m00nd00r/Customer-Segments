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
		conda env create -f requirements/segments-osx.yml
		source activate segments
	```

	For __Windows__:
	```
		conda env create -f requirements/segments-windows.yml
		activate segments
	```

### Code

Code is in the notebook `customer_segments.ipynb` notebook file. Additional supporting code can be found in `renders.py`.

### Run

In a terminal or command window, navigate to the top-level project directory `creating_customer_segments/` (that contains this README) and run the following commands:  

```
	jupyter notebook customer_segments.ipynb
```

This will open the Jupyter Notebooks in your browser.

## Data

The modified Wholesale Customers Dataset has 440 samples with each sample containing 8 features and is included as `customers.csv`. You can find more information on this dataset on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) page.

**Features**
1) FRESH: annual spending (m.u.) on fresh products (Continuous);
2) MILK: annual spending (m.u.) on milk products (Continuous);
3) GROCERY: annual spending (m.u.)on grocery products (Continuous);
4) FROZEN: annual spending (m.u.)on frozen products (Continuous)
5) DETERGENTS_PAPER: annual spending (m.u.) on detergents and paper products (Continuous)
6) DELICATESSEN: annual spending (m.u.)on and delicatessen products (Continuous);
7) CHANNEL: customersâ€™ Channel - Horeca (Hotel/Restaurant/CafÃ©) or Retail channel (Nominal)
8) REGION: customersâ€™ Region â€“ Lisnon, Oporto or Other (Nominal) 

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

