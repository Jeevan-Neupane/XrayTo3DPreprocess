
## Installation
To get started, create an environment using conda
```sh
conda create -n env_name python=3.8
conda activate env_name
conda env update -f requirements.yaml
pip install .

```

## Downloading the dataset:
```sh
python3 workflow/verse19/download.py
python3 workflow/verse19/subjectwise_directory.py
```

### Requirements for Data Preprocessing:
- Compile DRR Generator and add to path
 
Detailed explanation on : [docs/install_requirements.md](docs/install_requirements.md)


## Sample Command for dataset preprocessing

```sh
python3 preprocessing_vertebra.py configs/full/Verse2019-DRR-full.yaml --dataset verse2019 --parallel
```





```

Time to download the dataset
|Dataset        | Time              | Size (GB) | #CT Scans         |
|---            | ---               | ---       |---           |
|Verse20        | 2 hr @ 4 MB/s     |36           | 214         |
|Verse19        |                   |12           |160         |
|Totalsegmentor |                   |           |           |
|RibFrac        |                   |56           |         |
|LIDC           |                   |           |           |
|CTPelvic1k     |                   |           |           |
|CTSpine1k      |                   |           |           |
|RSNACervical   |                   |           |           |


```

## Synapse 

In order to access the dataset from Synapse, it is necessary to create an account and obtain a token.

## Steps to Get the Token

1.Go to [synapse.org](https://www.synapse.org/)

2. Click on Register
![Click on Register](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446680/naamii/fmaxf4ndswmwgzxsutf5.png)

3.Click on create account with google

![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446623/naamii/evote8yeuptxumtut1h2.png)

4.Select the google account
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446621/naamii/ffxdn1y99stj3xzp0g5f.png)

5.Select the username
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446626/naamii/em4os1bagcjuwzdp4vxk.png)


6.Accept all the terms and conditions.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446667/naamii/jcxlrxjrkxdsga9ootln.png)


7.Click on the account logo to open sidebar and then click account settings.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446654/naamii/ubqcnumcupchbvfxru0s.png)

8.Select personal access token.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446648/naamii/yyqchajjbuuk0nwxacyc.png)


9.Click on create new token.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446660/naamii/m504f4gupe9fplwdhg4p.png)

10.Give name to the token and give the required permissions.
![Click on sign in with google](
https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446624/naamii/d89kclbhsugh7rpqsrzm.png)

11.Save the token  to secure place for future use since it couldn't be accessed again.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741446628/naamii/psyxsynusvhjfa8yejlg.png)


## How to get access to dataset in synapse

1.Click on search icon in sidebar.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741615411/naamii/lrhdh1mohsnzwsgcnaeh.png)

2.Enter the synapse id of the required dataset in search box and click on search.

We have only two dataset for cervix to be accessed from synapse:
```
cervix_synapse_id = syn3546986
cervix_synapse_id = syn3379050
```
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741615411/naamii/zvtivntehzp9pgjc0gwh.png)


3.You will see the dataset page.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741615411/naamii/qvi7a3u0wqp6pdyd11xm.png)


4.Scroll down until you see the join button.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741615412/naamii/usse2htwrvuishxrtqde.png)

5.A popup to change the name to ananomous will appear.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741615927/naamii/qckmzrw0pqyepp7ryu7k.png)

6.Click on save and you will be displayed that you have successfully joined the challenge.
![Click on sign in with google](https://res.cloudinary.com/de1yfnzdz/image/upload/v1741615928/naamii/cphszfzc5ukcj1qylcun.png)