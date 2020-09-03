# dsci510-lab1

Hi, guys. 

My name is Kexin Yan. My usc email address is kexinyan@usc.edu . 

Things you have to do to invoke lab1.py in Jupyter:

1. download it from github and unzip it

2. open Jupyter and create new python3 notebook

3. load your code and run it(shift+enter):
     
     a. if lab1.py in the jupyter folder: 
         
         %load lab1.py
     
     b. if they are in different folder: 
         
         %load lab1-folder-path/lab1.py
     
4. invoke the function

Things you have to do to invoke lab1.py in another python file:

1. download it from github and unzip it

2. load your code and run it:
     
     a. if lab1.py in same folder: 
     
         from lab1 import has_to_be_a_function_to_be_invoked
         has_to_be_a_function_to_be_invoked()  #use it again
     
     b. if they are in different folder: 
     
         import sys
         sys.path.append(r'lab1-folder-path')
         import lab1
         lab1.has_to_be_a_function_to_be_invoked()  #use it again

