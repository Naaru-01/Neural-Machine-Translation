# Neural Machine Translation

 

* I've Built a Neural Machine Translation (NMT) model to translate human-readable dates ("25th of June, 2009") into machine-readable dates ("2009-06-25"). 

* INPUT : "25th of June, 2009"
* OUTPUT : "2009-06-25"

* I've used an attention model, one of the most sophisticated sequence-to-sequence models. 

# Translating Human Readable Dates Into Machine Readable Dates

* This model I've built here could be used to translate from one language to another, such as translating from English to Hindi.

* However, language translation requires massive datasets and usually takes days of training on GPUs. 

* The network will input a date written in a variety of possible formats (*e.g. "the 29th of August 1958", "03/30/1968", "24 JUNE 1987"*) 

* The network will translate them into standardized, machine readable dates (*e.g. "1958-08-29", "1968-03-30", "1987-06-24"*). 
* We will have the network learn to output dates in the common machine-readable format YYYY-MM-DD. 

## `dataset`: a list of tuples of (human readable date, machine readable date).

## For more Information Read  

Neural_Machine_Translation.ipynb Notebook in this repo

# IMAGE 1 : Attention Mechanism

<img width="622" alt="attn_mechanism" src="https://user-images.githubusercontent.com/68388179/126276485-12c3c58b-056f-47e7-b88c-7ad04a41584c.png">

# IMAGE 2 : Attention Model 
<img width="884" alt="attn_model" src="https://user-images.githubusercontent.com/68388179/126276496-39f96a62-8307-4ad4-b179-be07dd202d92.png">
