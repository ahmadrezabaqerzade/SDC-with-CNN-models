In this project we have a two part for training a dataset and we train a dataset with two ways. 
Our dataset have three part that one part is image dataset and two other part are class label and four feature for regressional dataset that we can use for output or input.

1)I the first part at the first we train a dataset with two input part: 
  a)CNN Dataset (image dataset that for training we use a CNN model)
  b)Numerical Dataset . 
Our output is classificational dataset that have a 5 class :0, 1, 2, 3, 4


 2)In the second part we have a one input part: image dataset. For output we have a two part:
  a)Regressional Dataset
  b)Classificational Dataset

In the first part of training we have model that give a two part dataset and get a one part output(Classificational output). We use a one loss function in part one that is a CrossEntropyLoss for classificational output. But in part2 we use a two loss function that it has a regressional loss function and classificational loss function. Our loss function in part2 are Huber loss function for regressional output and CrossEntropyLoss for classificational output.
