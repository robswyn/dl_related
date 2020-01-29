# About this repo

This Repo servers the dl_related notebooks for fastai and pytorch study.

* The Play Ground folder contains all Fastai course related stuff in my own understanding. The code has minor changes in compairson with 
Fastai course notebooks.
[Callbacks system, single shot detector, Retina net and focal loss]

* The NIC folder contains NIC image classification prototype model. It will be moved in the future.

* The fellowship folder is a temporary folder to work on Challenge problem from fellowship, it also has detailed explanation about few fastai factory functions. 
** to add counter function try this code (I have not tried)
      for c in data.classes:
        cnt = 0
        for i in range(len(data.train_ds.y)):
        if str(data.train_ds.y[i]) == c:
        cnt += 1
     print(f’{c}: {cnt}’)
