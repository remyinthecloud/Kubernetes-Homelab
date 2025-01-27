## K3S Installtion

This is where I'll be documenting my experience installing k3s for the first time.

K3s is a lightweight kubernetes distrubution which is perect for my homelab setup.

I will be following the official k3s doc here: https://docs.k3s.io/installation




#### Notes
Installation went successful. 

Only issues I face was running `kubectl` commands getting permission error. Not a huge problem but I rather not have to type sudo everytime, root user has read and write permissions to the k3s.yaml file is why this happens. 

I tried to copy the file in my user home directory to give it the same permissions. Showed me I need a lot more practice moving, creating, and copying directories and files. 

Was a bit of a headache as I successfully copied but still got permission denied. 

I decided to just modify the permissions to give my user read permissions. `chmod 644`