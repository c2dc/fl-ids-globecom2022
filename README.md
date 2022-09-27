# FL IDS Globecom 

## How to run the jupyter notebook.

Install python virtual env. 

```
    $ pip install venv	
```

Create virtual env. 

```
    $ python -m venv venv 

```

Activate virtual env. 

```
    $ source activate
```

Start jupyter lab.

```
    $ jupyter-lab .
```

## Generating DDoS only datasets 

[Download](https://staff.itee.uq.edu.au/marius/NIDS_datasets/) the Netflow v2 datasets:
 - ToN-IoT v2 
 - CIC-IDS v2 
 - BoT-IoT v2
 
After that run the "Extract DDOS Sub-Datasets.ipynb" notebook to generate the DDoS sub-datasets.

