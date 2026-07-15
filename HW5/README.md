Ensure that the dataset loaders are marked as "download = True", if you have problems with download speed as I have, I included the files which would be downloaded under [this Google Drive]([https://drive.google.com/drive/folders/1LMrYZQb_rrqWznaYa7aOnG82PJR-biu6?usp=drive_link](https://drive.google.com/drive/folders/1LMrYZQb_rrqWznaYa7aOnG82PJR-biu6?usp=sharing)).

Make sure that if you add these files, you place them inside "./data/cifar-100-python" as that is where the dataset loader looks for them. Add all the files (train,test,meta) inside that directory.

If you add your own files, make sure "download = False" inside the dataset loader arugments
