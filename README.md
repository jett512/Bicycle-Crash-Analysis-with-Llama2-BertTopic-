# Bicycle-Crash-Analysis-with-Llama2-BertTopic-
Topic Modeling using BERTopic with Llama Integration on Crash Narratives of SUV involved Bicycle Crashes
![GitHub Logo](https://github.com/jett512/Bicycle-Crash-Analysis-with-Llama2-BertTopic-/blob/main/Figures/WF_Git.drawio.png)

This repository addresses the critical concern of safety in transportation, particularly focusing on the vulnerability of road users such as cyclists, pedestrians, and motorcyclists. The aim is to highlight the underreporting of injuries, especially those involving cyclists, in official road crash statistics. The significance of considering all road users in policy decisions is emphasized throughout. Topic modeling was done by leveraging [BERTopic](https://github.com/MaartenGr/BERTopic) with their recent support for Llama2 integration. Below is a plot showing the latent topics within the crash narratives recieved from the [Ohio Department of Transportation](https://www.transportation.ohio.gov/)

![GitHub Logo](https://github.com/jett512/Bicycle-Crash-Analysis-with-Llama2-BertTopic-/blob/main/Figures/cluster_topic.png)

# Dependencies 
All of these are installed within the notebook, but are included below for local environments
## BERTopic + llama-cpp-python
* llama-cpp-python
* bertopic


## DataMapPlot
* datamapplot

## GPU-accelerated HDBSCAN + UMAP
* cudf-cu12
* dask-cudf-cu12
* cuml-cu12
* cugraph-cu12
* cupy-cuda12x
* wget
* huggingface.co/TheBloke/OpenHermes-2.5-Mistral-7B-GGUF

## Benchmarking
* octis
* genism
* datasets
