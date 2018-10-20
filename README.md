# Deep-Learning
This project is a simple image classification based on keras 
## precondition
### 1. install neccesary package
    (1) numpy   
        pip3 install numpy
    (2) matplotlib
        python3 -m pip install -U matplotlib
    (3) keras
        pip3 install keras
    (4) tqdm
        pip3 install tqdm
    (5) cv2
        pip3 install opencv-python
### 2. prepare dataset
    (1) Download from kaggle
    (2) google 
### 3. request
    (1) For the dataset, you have to have two folder, one is trainset, other is testset.     
        30% of the trainset will be validation set
    (2) For this program, you can only classify two class of object

## Operation instruction
### 1.basic usage
    (1) After preparing the dataset and basic path name modification, you can run the main.py.    
    (2) Using checkpoint to store the best model every epoch and the program will load it after.
    (3) There will be a brief model summray. After that, you can see some test example with images and labels
        and also graphs about accuracy and loss.
### 2. inprovement
    (1) try more complex model 
    (2) use tensorflow, pytorch instead of keras
    
    
    
