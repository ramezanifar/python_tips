# How to make an exe from a python file

1- install pyinstaller  
2- open a terminal at the place where the python file is located  
3- run this command:
``` path_to_py_installer\pyinstaller.exe python_file_name --onefile```  
**Example:**  
``` "C:\Program Files (x86)\Python38-32\Scripts\pyinstaller.exe" main.py --onefile ```  


# How to convert py files to pyc
## Python 2
1- Run this command in a linux terminal:  
``` sudo python -m compileall python_file_name```    
2- You can use ```.``` to compile all files in the directory or use wildcard characters like ```*.py```  
3- In windows, just remove the sudo

## Python 3
1- Run this command in a linux terminal:   
``` sudo python -m compileall python_file_name -b```    
2- You can use ```.``` to compile all files in the directory or use wildcard characters like ```*.py```  
3- the ```-b``` is to generate the pys files in the same directory (folder) as the source files. Otherwise, they will be generated in a directory (folder) caled ```__pycache__```  
4- In windows, just remove the sudo  



