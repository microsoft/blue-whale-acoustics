# Introduction 
This project is collaboration with researchers from University of Washington (Kate Stafford, Trevor Branch). The goal of this project is to use audio recordings and correpsonding annotations to build an automatic classifier for calls from 4 different species of blue whales, and to estimate the total number of calls from each population in the audio recordings.

# Getting Started
The code can be run in Python environment. 
1.	Users need to install corresponding packages in the "requirements.txt" file. 
2.	The Jupyter notebooks show step-by-step how to build high accuracy classification model with raw audio data and corresponding annotations of detected blue whale calls.

# Build and Test

To run the code, first run:
```
pip install -r requirements.txt
```

# Users can follow the steps to leverage deep learning techniques to build classifier model:
- step 1: generate spectrograms based on annotations;
- step 2: build convolutional neural networks (CNN) which is the baseline model here;
- step 3: build Siamese network model (SNN) to classify blue whale calls and to estimate the number of calls. This model has higher accuracy compared to CNN. 
- Note: the full data is not public yet so we only included a small sample of the full data. 

# Publication
The published paper can be found at https://asa.scitation.org/doi/full/10.1121/10.0004828?journalCode=jas


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
