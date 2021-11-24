# Dacon_KOGAS_Text_Summarization   
   
This is temporary format for recording project.   
After competition, i will rewrite it with more details.   

Competition Deadline : 12/10/21   
   
Code will be uploaded after competiton and modularization      
   
Current Rank (11/24/21 updated) :    
8/103 7/103 8/103 ( F-1 scores of ROUGE-1, ROUGE-2, ROUGE-L)   
8/36 7/36 8/36 ( Team score > default(0.0002))   
   
![image](https://user-images.githubusercontent.com/28786204/143210805-d913edc8-0723-4de8-8f73-55dc32b95012.png)   
   
I use 18000 of training datas that sequence length is lower than 1024 extracted from training source   
Because my model's max sequence length is 1024   
Epoch : 15  Learning rate : 1e-5   
   
   
Environments:   
CPU : Intel i7-11700   
GPU : RTX 3060 12GB   CUDA : 11.1   cuDNN : 8.0.5   
RAM : 24GB   
OS : Windows 10 64bit   
   
Pytorch == 1.8.0, Transformers == 4.12.3 Pyton == 3.8   
Pre-trained Model : https://huggingface.co/gogamza/kobart-base-v2   
Training source : AIhub's Text summarization dataset   
Test dataset : Dacon KOGAS summarization competition test dataset   
   
Work in Progress:   
Fine tuning on kobart-summarization(pre-trained model)   
