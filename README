This repository contains two Jupyter Notebooks that I used for solving the problem posed in the [ITS DM Hackathon 2017](http://www.itsc2017.org/hackathon.php), where lane changes were expected to be predicted using data captured at a vehicle. I finished in 6th place; however, the code here provided was able to produce an estimation slightly better which would be placed in 5th place.

The data used in the challenge is proprietary, and therefore is not published here. The visualizations and use of such data are only provided as an example.

## Details ##
I used an LSTM-based solution implemented in [PyTorch](http://pytorch.org/) to classify each sample in the sequence as "no lane change" (0), right lane change (1) and left lane change (-1). The classification algorithm is implemented in the **2_sequences.ipynb** file.

The file **1_adapt_data** was employed to preprocess and normalize the input data.

## Acknowledgments ##
The solution is somehow inspired by:

A. Jain, A. Singh, H. S. Koppula, S. Soh, and A. Saxena, “Recurrent Neural Networks for driver activity anticipation via sensory-fusion architecture,” in Proc. IEEE International Conference on Robotics and Automation (ICRA), 2016, pp. 3118–3125.

The code was partially adapted from the [PyTorch's LSTM example](http://pytorch.org/tutorials/beginner/nlp/sequence_models_tutorial.html#example-an-lstm-for-part-of-speech-tagging).

I want to thank [Jorge Beltrán](https://github.com/beltransen) for his help in the weeks leading up to the event.
