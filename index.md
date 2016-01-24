# nova-docker-pull-images
This project is part of NUBOMEDIA www.nubomedia.eu  
   
Nova-docker pach for pulling docker containers on compute nodes that are running docker as a hypervisor.

Rename the file variables-example.py to variables.py and change the necessary values
If you have password authentication disabled on you master then you have to provide a private key file location replacing master_id_rsa value for the master_key variable.

For running it you should install pip and then install all the libraries in requirements.txt

```
easy_install pip
pip install -r requirements.txt --upgrade
```

Then run it with:
```
python main.py
```
