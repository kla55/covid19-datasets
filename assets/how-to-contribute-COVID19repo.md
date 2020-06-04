# HOW TO CONTRIBUTE:

## BACKGROUND:


The vision of developing this repository is to have an exhaustive list of high quality datasets, APIs and projects pertaining to COVID 19 which will be open to communities such as academia, research and education.

The following contributions to the repo are welcomed:

1) New high quality datasets that contain information or statistics pertaining to COVID 19 (these can be tabular data, image data or text data). 
2) If you find new projects related to any existing dataset. Please feel free to add those to dataset-details page of that particular dataset.
3) Any outdated information pertaining to the current dataset.
4) New API links related to COVID-19.
5) Projects related to COVID - 19 data. 
6) Any grammatical errors, structural errors or any errors in generals (outdated links,etc.).


## HOW TO CONTRIBUTE A NEW DATASET:
_If this is your first time contributing to a open-source project, have a look at this great [tutorial](https://www.youtube.com/watch?v=dSl_qnWO104)._

Please follow this simple procedure in order to have a successful contribution towards the repository.

1) Fork the `covid19-datasets` [repo](https://github.com/sfu-db/covid19-datasets).
2) Clone **your** forked repo using `git clone <your forked repo>`
3) Contributing to the dataset can be of 2 types: either you can edit information related to an existing dataset or share a new dataset. If you are sharing a new dataset there are five simple steps to be followed, they are given below:
    * In the dataset-details directory, create a new .md page for the dataset using the template provided [here](https://github.com/sfu-db/covid19-datasets/blob/master/assets/dataset-details-template.md).
    * Add the link of the new page your have created to [README.md](https://github.com/sfu-db/covid19-datasets/blob/master/README.md), under the correct category (tabular, image or text data).
    * Using the template provided [here](https://github.com/sfu-db/covid19-datasets/blob/master/assets/pandas-profile-template.py), you can generate a pandas-profile HTML page. Once you have generated your .html page, please add your .py script file to [scripts folder](https://github.com/sfu-db/covid19-datasets/tree/master/scripts)
    * The next step would include adding your pandas-profile HTML page to the [webpages folder]() and include the link to the **Dataset Profile:** section of your dataset details page. The link would be similar to this `https://sfu-db.github.io/covid19-datasets/webpages/name-of-your-dataset.html`
    * The last step would be to add the link to your pandas-profile webpage to index.html. For example for the OWID dataset we would add the following `<li><a href="webpages/owiddataset.html">OWID dataset Pandas-profiling report</a></li>`. You can check whether your webpage is live using this [link](https://sfu-db.github.io/covid19-datasets/). Please give 5-10 minutes before the webpage goes live.
    
5) Once you are done editing or adding a new dataset, perform a pull request from the original dataset `covid19-datasets` [repo](https://github.com/sfu-db/covid19-datasets).
6) Once your pull request passes the maintainer's review it will be merged. 

Thank you for your contribution, we at SFU-DB appreciate it!
