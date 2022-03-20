# alphabet_recognition
Using Google's Teachable Machine Learning to do image recognition of English alphabets
So far as on 20-3-22 , I didnot get the desired accuracy from Teachable machine's output. 
I have tried in different perspectives like training 600 images per letter, capturing either through file upload or webcam, capturing training images at different angles.
I interpreted the following difficulties in Teachable Machine,
                It is detecting and training RGB images by default. Hence during test phase- the different exposure or brightness of images leads to not getting the desired output
                It is not annotating the exact subject in the image as it is done in labelimg in tensor flow python. 
    
