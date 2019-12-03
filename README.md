                __------__
              /~          ~\
             |    //^\\//^\|
           /~~\  ||  o| |o|:~\
          | |6   ||___|_|_||:| 
           \__.  /      o  \/'
            |   (       O   )
   /~~~~\    `\  \         /
  | |~~\ |     )  ~------~`\
 /' |  | |   /     ____ /~~~)\
(_/'   | | |     /'    |    ( |
       | | |     \    /   __)/ \
       \  \ \      \/    /' \   `\        __  __             _               _____ ____  _____  
         \  \|\        /   | |\___|      |  \/  |           | |             / ____|  _ \|  __ \ 
           \ |  \____/     | |           | \  / | ___  _ __ | | _____ _   _| |    | |_) | |__) |
           /^~>  \        _/ <           | |\/| |/ _ \| '_ \| |/ / _ \ | | | |    |  _ <|  ___/
          |  |         \       \         | |  | | (_) | | | |   <  __/ |_| | |____| |_) | |
          |  | \        \        \       |_|  |_|\___/|_| |_|_|\_\___|\__, |\_____|____/|_|
          -^-\  \       |        )           
               `\_______/^\______/  

## MonkeyCBP command line version

MonkeyCBP (A toolbox for connectivity-based parcellation of monkey brain) 

- Multi-ROI oriented brain parcellation
- Automatic parallel computing
- Modular and flexible structure
- Simple and easy-to-use settings

## Notice
-  Usage: `bash MonkeyCBP.sh batch_list.txt`


## Prerequisites:
===============================================

- Tools:
    - FSL (with FDT toolbox), SGE and MATLAB (with SPM8)
- Data files:
    - T1 image for each subject
    - b0 image for each subject
    - images preprocessed by FSL(BedpostX) for each subject
- Directory structure:
```
     Working_dir
     |-- sub1
     |   |-- T1_sub1.nii
     |   |-- b0_sub1.nii
     |-- ...
     |-- subN
     |   |-- T1_subN.nii
     |   |-- b0_subN.nii
     |-- ROI
     |   |-- ROI_L.nii
     |   `-- ROI_R.nii
     `-- log 
```
===============================================

