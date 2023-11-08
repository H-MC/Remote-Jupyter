# Setting Your Jupyter To Be Remotely

An easy way for your **Jupyter Lab** or **Jupyter Notebook** to be operated remotely on any browser of any device. This makes your local computer as a server and automatically running it in the background. 

## Step 1 : **Install Jupyter**
Install **Jupyter Lab** by the following command in cmd.

```cmd
pip install jupyterlab 
```


## Step 2 : **Set Your Jupyter Password**

Also enter the following command in cmd.
```cmd
jupyter server password
```
***Note:*** \
The password needs to be enter twice, and the entered password will not be shown in the window. 

After finishing this step, there will be a file `jupyter_server_config.json` created in `C:\Users\user\.jupyter`.


## Step 3 : **Create Configration File**

```cmd 
jupyter lab --generator-config
```
