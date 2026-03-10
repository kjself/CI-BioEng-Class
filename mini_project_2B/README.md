## Mini-Project 2B: Emotion recognition with bigger datasets and large-scale neural networks
This mini-project builds on the project conducted in Mini-Project 1B. In the previous project, the data that was observed and analyzed came from only one subject. In *this* project, we go on to observe the rest of the data, utilizing the high-performance computing (HPC) power of the FABRIC testbeds.

### Acquire the data:
Firstly, we must go to the [page containing the entire dataset](https://www.kaggle.com/datasets/wajahat1064/emotion-recognition-using-eeg-and-computer-games/data) on Kaggle. In all, there are 28 different subjects, each of which played the same 4 emotionally-distinct games (much like the first subject in 1B). We want to pull each of the 4 `.csv` files from the list on the right of the page, labeled **Data Explorer**, under the path `SP/Raw EEG Data/.csv format` for every player/subject $P$.
### Graph/use your data:
To conduct this experiment within a reasonable time frame, you will need more resources (e.g., CPUs, cores, et cetera) than are likely readily available to you. This is why this experiment makes use of a cloud resource like [FABRIC](https://portal.fabric-testbed.net/), where you can configure your resources how you want them.

Modify the code used in 1B in order to read through all of the `.csv` files and process them accordingly. You will notice a substantial jump in the time needed to train with all the extra data if done correctly.
### Testing the limits:
From there, we can alter the number of layers and/or the layer size(s) seen in the `model` cell. More layers influence the amount of time needed to iterate over the model, as well as the accuracy of said model.

Attached is an extended version of the 1B experiment with 12 subjects to reference in your model. This quantity can be grown and shrunk as desired to observe the changes relative to the size of the dataset.