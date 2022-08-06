How to run:

1. Download and unzip files:
    1. [Cleora master](https://github.com/Synerise/cleora) - move it to *main* directory as *cleora-master*
    2. [Cleora engine](https://github.com/Synerise/cleora/releases) - move it to *cleora-master* directory
    3. [Facebook large dataset](https://snap.stanford.edu/data/facebook-large-page-page-network.html) - move it to *
       data-source* directory
    4. [Trivago clicks dataset](https://www.cs.cornell.edu/~arb/data/trivago-clicks/) - move it to *data-source*
       directory
    5. [Walmart trips dataset](https://www.cs.cornell.edu/~arb/data/walmart-trips/) - move it to *data-source*
       directory
2. Run *data_conversion.ipynb* to preprocess datasets
3. Enjoy working with *main_cleora.ipynb* file

Additional notebooks (using them require doing steps 1 and 2 from above section):

1. *data_analysis.ipynb* can be used to obtain details and statistics of datasets
2. *balancing.ipynb* can be used to generate balanced versions of datasets using RandomOverSampler method in versions with
   resampling nodes or hyperedges