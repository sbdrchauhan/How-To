# How-To: 
At several occassion I tend to search so many things to perform various important task.
It it I think a good idea I will collect all the how-to search I made during my learning.

## 1. How to **link** files/datasets from google drive to the colab:

- from google.colab import drive
  drive.mount('/content/drive')

Then, authentication link appears. You need to give colab your google id authentication where
you have kept your files/datasets

Now when calling that file: for example
- data = pd.read_csv('drive/My Drive/Data/ted.csv')

In the above line: I have stored my datafile into the Data folder inside My Drive of the google.
Please note: that you start your path to the file with 'drive' i.e. same with whichever name you've mounted your drive while authenticating

