# midterm_training_llm
## midrerm project for AI class.
## Model
I use GPT2 model architecture.
## Training Method
pretraining from scratch
## Dataset   
[openWebtxt](https://openwebtext2.readthedocs.io/en/latest/) 
## Quickstart
1. python prerare.py
2. python train.py --compile=False
3. After training on 1 A100 for 24 hours. We get a checkpoint in out directory

![image](https://github.com/user-attachments/assets/e6d606cf-c204-4522-89e0-a6a4f4872cc3)
## Evaluation
1. python sample.py     --out_dir=out     --start="I see a Star"     --num_samples=1 --max_new_tokens=30

--start the input sentence

--num_samples the numer of inference output for a input

--max_new_token the maximum number of tokens of output
## 10 comprehensive sentence
1. I see a star-I see a Star Wars fan in the movie. And I think they were so disappointed that they didn’t give it a chance.
   ![image](https://github.com/user-attachments/assets/7a7bd67a-ee8e-4066-b90a-485f881de08a)

