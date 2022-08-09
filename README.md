🔱Download NirAharon/BoT-SORT Github Resources 
====
🔗https://github.com/NirAharon/BoT-SORT

[![Image from Gyazo](https://i.gyazo.com/e5fb4fc98174bbf080f8a539a412b5cf.gif)](https://gyazo.com/e5fb4fc98174bbf080f8a539a412b5cf)

🔱Do the following Pre-Work
====
## 1.Create a new environment

  conda create -n botsort_env python=3.7
  conda activate botsort_env

## 2.Install Pytorch corresponded to your CUDA version
Enter the cmd to check version.
  nvidia-smi
  
  ![image](https://user-images.githubusercontent.com/46515944/183584522-c359b89b-bf65-48dd-8095-de87bd444333.png)

Go through Pytorch to copy installmental command.

🔗https://pytorch.org/get-started/locally/

![image](https://user-images.githubusercontent.com/46515944/183584819-e64fd41f-f879-4644-af0f-4eb068f47b8e.png)

After that, you must make sure that your Torch can work.

Enter the cmd to make sure.

    python
    import torch
    torch.cuda.is_available() 

If it work successfully, it'll show **True**.

![image](https://user-images.githubusercontent.com/46515944/183584183-508ccb89-4750-49c1-93b1-6ce329ebcc57.png)


🔱Amend the code
====
Near 50 lines in set.py

Just add encoding='utf-8' behind "r".

![image](https://user-images.githubusercontent.com/46515944/183583132-d70eae3c-4592-4ae0-984d-27f962b24b15.png)

then enter the following in prompt
  python setup.py develop

If you finished, it would be like this.

![image](https://user-images.githubusercontent.com/46515944/183581630-2253bbe2-ded3-441b-a328-4e899359cb1d.png)

🔱Install requirements
====
