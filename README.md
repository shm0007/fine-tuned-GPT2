# Fine tuned GPT2 transformer model

This model is a fine-tuned version of GPT2 language model on a dataset containing thirteen Agatha Christies Books. It
achieves the following results on the evaluation set: Training Loss: 2.99, Validation Loss: 3.01

## Text corpus:
All the available books of Agatha Christie in the public domain are used to fine tune the model. 
Book list:
| File Name  | Word Count | Character Count | Book Type|
|:-----------------------------------:|:-----:|:----:|:-----:|
| The_Murder_on_the_Links.txt | 64470 | 383665 | Novel |
|The_Mysterious_Affair_at_Styles.txt|56456|341202|Novel|
|The_Secret_of_Chimneys.txt| 74431 | 455894 | Novel|
|And_Then_There_Were_None.txt| 52607 | 320398| Novel |
|The_murder_of_Roger_Ackroyd.txt | 69485|  416920 | Novel |
|Poirot_Investigates.txt | 52494 | 313466 | Novel |
|The_Big_Four.txt | 55230 | 319360 | Novel |
| The_Mystery_of_the_Blue_Train.txt| 71222 | 414922 | Novel |
|The_Secret_Adversary.txt | 10855 |  75138 | Novel |
|The_Man_in_the_Brown_Suit.txt |  10317 |  75261  | Novel |
| The_Hunters_Lodge_Case.txt | 4352 |  25602 | Short Story |
| The_Missing_Will.txt|3257  | 19004  | Short Story |
|The_Plymouth_Express_Affair.txt| 4858 |  29493  | Short Story |
|Total|  659261| 3928209||

## Model:
Fine-tuned model can be downloaded and directly used from HuggingFace pipeline. Link: 
https://huggingface.co/shm0007/gpt2-finetuned-agatha-christie
