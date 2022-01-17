

| Converge before | Converge after 
| - | - 
![](img1/1.png) |![](img1/2.png) 
    
    
#MIN-MAX
<img src="img1/Conv.gif" alt="" title="Title text" />


| C- | C-max | C-min
| - | - | -
    ![alt](img1/c1.png) |![alt](img1/c-avarage-pool.png) |  ![alt](img1/c-max-pool.png)


#### Create the course environment

```
conda env create
```

wait for the environment to create.

#### Activate the environment (Mac/Linux)
```
conda activate ztdl
```

#### Activate the environment (Windows)
```
conda activate ztdl
```

Check that your prompt changed to

```
(ztdl) $
```

#### Launch Jupyter Notebook

```
jupyter notebook
```

#### Open your browser to

```
http://localhost:8888
```




#### Troubleshooting installation
If for some reason you don't see `Houston we are go!`, the simplest solution is to delete the environment and start from scratch again.

To remove the environment:

- close the browser and go back to your terminal
- stop jupyter notebook (CTRL-C)
- deactivate the environment (Mac/Linux):

```
conda deactivate
```

- deactivate the environment (Windows 10):

```
deactivate ztdl
```

- delete the environment:

```
conda remove -y -n ztdl --all
```

- restart from environment creation and make sure that each steps completes till the end.


