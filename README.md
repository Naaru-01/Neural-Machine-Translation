# Neural Machine Translation
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
 

* I've Built a Neural Machine Translation (NMT) model to translate human-readable dates ("25th of June, 2009") into machine-readable dates ("2009-06-25"). 

* INPUT : `"25th of June, 2009"`
* OUTPUT : `"2009-06-25"`

>I've used an `attention model`, one of the most sophisticated `sequence-to-sequence models`. 
>Implementation and summary given in ` Neural_Machine_Translation.ipynb ` notebook in this repository.
## Translating Human Readable Dates Into Machine Readable Dates

* This model I've built here could be used to translate from one language to another, such as translating from English to Hindi.

* However, language translation requires massive datasets and usually takes days of training on GPUs. 

* The network will input a date written in a variety of possible formats (*e.g. "the 29th of August 1958", "03/30/1968", "24 JUNE 1987"*) 

* The network will translate them into standardized, machine readable dates (*e.g. "1958-08-29", "1968-03-30", "1987-06-24"*). 
* We will have the network learn to output dates in the common machine-readable format YYYY-MM-DD. 

 >`Dataset Used `: A list of tuples of (human readable date, machine readable date).

 



### `IMAGE 1 : Attention Model Architecture ` 
<img width="884" alt="attn_model" src="https://user-images.githubusercontent.com/68388179/126276496-39f96a62-8307-4ad4-b179-be07dd202d92.png">

### `IMAGE 2 : Attention Mechanism Architecture `

<img width="622" alt="attn_mechanism" src="https://user-images.githubusercontent.com/68388179/126276485-12c3c58b-056f-47e7-b88c-7ad04a41584c.png">

