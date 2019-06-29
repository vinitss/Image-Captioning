# Image-Captioning

Given a image , it uses resnet architecture to get a context vector , 
this context vector is then passed to LSTM decoder which uses Luong attention (general) in order to focus on parts of images , for generation of the caption (sentence)
During training , teacher forcing is used , and for testing greedy decoding is done . 
