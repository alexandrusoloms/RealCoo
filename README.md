# RealCoo - feature/00-spectrogram branch
real time bird detection on the bela mini beagleboard (bela.io)

# Overview

The `RealCoo` project attempts to use Machine Learning and Deep Learning techinques for Real Time birdsong detection on the Bela Mini device. It does this in n steps:

1. Data Extraction - using the UKY dataset, a spectrogram program needs to be created for each recording. The spectrogram will use mel-band frequencies and will be created in c++, following this python tutorial: <https://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html>
2. Preparing to run on `sandle` - deciding on the values of hyper-parameters as per `bulbul` network. And running all of them in a bash script. 

