# Gen_Ai_Chatbot

Description
This is my chatbot repository for deployment purpose. For a simple tutorial about build generative chatbot using pytorch you can visit Pytorch Chatbot Tutorial

Main Library 📚
• Pytorch
• Flask

Model 🤖
My chatbot using sequence-to-sequence architecture wich have Encoder and Decoder in it. For each Encoder and Decoder i'm using Bidirectional Gated Recurrent Unit imported from pytroch. In additon to improve chatbot performance i'm using Luong Attention Mechanism.

There is two different model that i'm deploying, the first one is the model who have good performance in bleu score, the second model is the best model in hyperparameter tunning process

Deploy Services 🚀
I'm using droplet from Digital Ocean with a little addition in memory. You can access my deployed model through this link :
• First Model
• Second Model
