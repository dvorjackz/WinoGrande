# "Winobert"

Trained a model which employs a RoBERTa with token dependency parsing and graph convolutional network layers to attempt to achieve high accuracy on resolving Winograd problems. Used the model to participate in the [Winogrande challenge](https://leaderboard.allenai.org/winogrande/submissions/about). Our results as of writing our paper placed us in the top 20 of the [leaderboards](https://winogrande.allenai.org).

The paper can be found in the repo as **paper.pdf**.

## Data

    ./data/
    ├── train_[xs,s,m,l,xl].jsonl          # training set with differnt sizes
    ├── train_[xs,s,m,l,xl]-labels.lst     # answer labels for training sets
    ├── dev.jsonl                          # development set
    ├── dev-labels.lst                     # answer labels for development set
    ├── test.jsonl                         # test set
    ├── sample-submissions-labels.lst      # example submission file for leaderboard    
    └── eval.py                            # evaluation script
    
Trained a model which employs a RoBERTa with a dependency parsing and graph convolutional network layer to attempt to achieve high accuracy on resolving Winograd problems. Used the model to participate in the [Winogrande challenge](https://leaderboard.allenai.org/winogrande/submissions/about). Our results as of writing our paper placed us in the top 20 of the [leaderboards](https://winogrande.allenai.org).

The paper can be found in the repo as **paper.pdf**
