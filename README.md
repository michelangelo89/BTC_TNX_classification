# Data analysis
- BTC_TNX_classification
- Description: Classify licit and illicit transactions
- Data Source:https://www.kaggle.com/ellipticco/elliptic-data-set
- Type of analysis: supervides classification

## Description
The Elliptic Data Set maps Bitcoin transactions to real entities belonging to licit categories (exchanges, wallet providers, miners, licit services, etc.) versus illicit ones (scams, malware, terrorist organizations, ransomware, Ponzi schemes, etc.). The task on the dataset is to classify the illicit and licit nodes in the graph.

[1] Elliptic, www.elliptic.co.

[2] M. Weber, G. Domeniconi, J. Chen, D. K. I. Weidele, C. Bellei, T. Robinson, C. E. Leiserson, "Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics", KDD ’19 Workshop on Anomaly Detection in Finance, August 2019, Anchorage, AK, USA.

# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for BTC_TNX_classification in gitlab.com/{group}.
If your project is not set please add it:

- Create a new project on `gitlab.com/{group}/BTC_TNX_classification`
- Then populate it:

```bash
##   e.g. if group is "{group}" and project_name is "BTC_TNX_classification"
git remote add origin git@github.com:{group}/BTC_TNX_classification.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
BTC_TNX_classification-run
```

# Install

Go to `https://github.com/{group}/BTC_TNX_classification` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:{group}/BTC_TNX_classification.git
cd BTC_TNX_classification
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
BTC_TNX_classification-run
```
