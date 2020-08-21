# predict-image-classifier
 This is a python script that uses a trained network to predict the class for an input image.
 # Usage
 
 #### 1. (Basic):
 
 python predict.py /path/to/image checkpoint
 
 #### 2. (Return K most likely classes): 
 
 python predict.py input checkpoint --top_k 3
 
 #### 3. (use a mapping of categoris to real names): 
 
 python predict.py input checkpoint --category_names cat_to_name.json
 
 #### 4. (Use GPU for inference): 
 
 python predict.py input checkpoint --gpu
