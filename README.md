### HOW TO OPEN JUPYTER NOTEBOOK IN A VIRTUAL ENVIRONMENT

**1. Go to your desired project folder** 
    e.g. ```C:\Users\Public\Documents>```

**2. Use this command to create virtual enviorment**

```python -m venv venv```

**3. Use this command to activate the virtual enviorment**

```.\venv\Scripts\activate```

**4. Use this command to install ```ipykernel```**

```pip install ipykernel```

**5. Use this command to install a new kernel with anyname you want**

```python -m ipykernel install --user --name <anyname>```

**6. Use this command to if there is a requirements.txt available or manually install packages with ```pip```**


```pip install -r requirements.txt```

**7. Finally open jupyterlab or jupyter notebook and select your kernel**

``` jupyter lab ``` or ```jupyter notebook``` 


**Note: In this way all the packages will be in one place and not conflicting in the main system**
