# datafun-06-eda

## Project Overview
This project will complete an Exploratory Data Analaysis (EDA) by utilizing a standard seaborn dataset. The link to the EDA is here: [neely_eda.ipynb](https://github.com/bncodes19/datafun-06-eda/blob/main/neely_eda.ipynb)

## Dataset Description
The taxis dataset from the seaborn library will be utilized for this project. The dataset can be found at: [seaborn taxis dataset](https://github.com/mwaskom/seaborn-data/blob/master/taxis.csv.)

### Dataset field descriptions:
| **  Field **        | **  Description **                         |
|---------------------|--------------------------------------------|
|   pickup            |   A timestamp for pickup                   |
|   dropoff           |   A timestamp for drop-off                 |
|   passengers        |   Number of passengers                     |
|   distance          |   Distance traveled                        |
|   fare              |   Fare amount                              |
|   tip               |   Tip amount                               |
|   tolls             |   Toll amount                              |
|   total             |   Sum of fare, tip, and toll amounts       |
|   color             |   Taxi color                               |
|   payment           |   Payment type (e.g. cash or credit card)  |
|   pickup_zone       |   Pickup zone                              |
|   dropoff_zone      |   Drop off zone                            |
|   pickup_borough    |   Pickup borough                           |
|   dropoff_borough   |   Drop off borough                         |

### Dataset preview:
|   pickup               |   dropoff              |   passengers  |   distance  |   fare  |   tip   |   tolls  |   total  |   color   |   payment      |   pickup_zone            |   dropoff_zone           |   pickup_borough  |   dropoff_borough  |
|------------------------|------------------------|---------------|-------------|---------|---------|----------|----------|-----------|----------------|--------------------------|--------------------------|-------------------|--------------------|
|   2019-03-23 20:21:09  |   2019-03-23 20:27:24  |   1           |   1.6       |   7.0   |   2.15  |   0.0    |   12.95  |   yellow  |   credit card  |   Lenox Hill West        |   UN/Turtle Bay South    |   Manhattan       |   Manhattan        |
|   2019-03-04 16:11:55  |   2019-03-04 16:19:00  |   1           |   0.79      |   5.0   |   0.0   |   0.0    |   9.3    |   yellow  |   cash         |   Upper West Side South  |   Upper West Side South  |   Manhattan       |   Manhattan        |
|   2019-03-27 17:53:01  |   2019-03-27 18:00:25  |   1           |   1.37      |   7.5   |   2.36  |   0.0    |   14.16  |   yellow  |   credit card  |   Alphabet City          |   West Village           |   Manhattan       |   Manhattan        |
|   2019-03-10 01:23:59  |   2019-03-10 01:49:51  |   1           |   7.7       |   27.0  |   6.15  |   0.0    |   36.95  |   yellow  |   credit card  |   Hudson Sq              |   Yorkville West         |   Manhattan       |   Manhattan        |
|   2019-03-30 13:27:42  |   2019-03-30 13:37:14  |   3           |   2.16      |   9.0   |   1.1   |   0.0    |   13.4   |   yellow  |   credit card  |   Midtown East           |   Yorkville West         |   Manhattan       |   Manhattan        |


## Project Setup
1. Create a repository on GitHub in the browser
2. Clone the repository
```
git clone https://github.com/bncodes19/datafun-06-eda
```
3. Create the virtual environment in the project folder
``` shell
python3 -m venv .venv
```
4. Activate the virtual enivronment
``` shell
source .venv/bin/activate
```
5. List the required packages in a text file "requirements.txt". There should be one package per line. The requirements file should look like this:
```
jupyterlab
pandas
pyarrow
matplotlib
seaborn
```
6. Install the requirements file in a terminal
``` shell
python3 -m pip install -r requirements.txt
```
7. Freeze the requirements
``` shell
python3 -m pip freeze > requirements.txt
```
8. Create a .gitignore file in the project folder and add folders to ignore when uploading to GitHub:
```
.venv/
.vscode/
.DS_Store
```
9. Add, commit, and push changes to the remote repo often
```
git add .
git commit -m "commit message"
git push origin main
```
