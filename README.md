# midterm_training_llm
## midrerm project for AI class.
## Model
GPT2 model architecture.
## Training Method
pretraining from scratch
## Dataset   
[openWebtxt](https://openwebtext2.readthedocs.io/en/latest/) 
## Quickstart
1. python data/openwebtext/prerare.py
2. python train.py --compile=False
3. After training on 1 A100 for 24 hours. We get a checkpoint in out directory
4. 
The checkpoin Link

通过百度网盘分享的文件：ckpt.pt
链接:https://pan.baidu.com/s/134GOZwq8sK7CMVbY_I2csw?pwd=k93a 
提取码:k93a
复制这段内容打开「百度网盘APP 即可获取」

![image](https://github.com/user-attachments/assets/e6d606cf-c204-4522-89e0-a6a4f4872cc3)
## Evaluation
1. move the checkpoint into out directory
2. python sample.py     --out_dir=out     --start="I see a Star"     --num_samples=1 --max_new_tokens=30

--start the input sentence

--num_samples the numer of inference output for a input

--max_new_token the maximum number of tokens of output
## 10 comprehensive sentence
1. I see a star-I see a Star Wars fan in the movie. And I think they were so disappointed that they didn’t give it a chance.
   ![image](https://github.com/user-attachments/assets/7a7bd67a-ee8e-4066-b90a-485f881de08a)
2. The singer sings well-The singer sings well, sometimes in the solo.
   ![image](https://github.com/user-attachments/assets/c336e654-c3ed-461d-b9ce-74057a2607b2)
3. Students are learning-Students are learning more about the ways they can use the resources they have so far to make it to the next level
   ![image](https://github.com/user-attachments/assets/9138d39d-4736-4311-ae6f-fc49e8446036)
4. Knowledge is power-Knowledge is power. Power works, but it is created when the right people are in power — and if you give it permission to do so, it increases your power
   ![image](https://github.com/user-attachments/assets/399492c2-34dd-4c0f-954d-ccf444bf9d6d)
5. Power is power-Power is power. Power works the same way,
   ![image](https://github.com/user-attachments/assets/43db692d-173b-4cff-a836-5f77eb58cb3e)
6. All is well-All is well, sometimes you just need to get your head up for the right thing in the right place. And then you’re wondering what that thing is
  ![image](https://github.com/user-attachments/assets/b6705cad-a6fa-428b-80b3-de212004da62)
7. Artificial Intelligence-Artificial Intelligence is a program developed by the National Science Foundation. The program is designed to help scientists learn how to better understand artificial intelligence and to work with data
 ![image](https://github.com/user-attachments/assets/b0e4cd56-812c-4be3-ad48-425a7a2635f3)
8. He is laughing-He is laughing. He immediately proceeded to shout at the other players for so long that they almost threw him in the head and dragged him through the crowd.
   ![image](https://github.com/user-attachments/assets/da0e7740-2299-4587-b9c7-19144df9b232)
9. The dancer dances well-The dancer dances well. He works with a pair of dancers and gets to dance his way in with them. He practices his dance as well, and is able to demonstrate
    ![image](https://github.com/user-attachments/assets/9e34e75f-b404-4dee-8500-dd5c7c459e6c)
10. Goodbye-Goodbye, Lina, and Rotten in case anything happened to you.
    ![image](https://github.com/user-attachments/assets/264664a7-14ad-4d1e-b423-f3e224e47648)










