Create a directory for frontend 
create a repo frontend 
clone it to deirectory frontend
create client.py file that loads yaml config file and print out the server IP address 
Create a directory for backend 
create a repo backend 
clone it to deirectory backend
create server.py file that loads yaml config file and print out the server IP address
Create a directory for full-stack 
create a repo full-stack 
clone it to deirectory full-stack
create configuration file that include a variable for the IP Address that should be readable by the client.py and server.py
add submodules: frontend and backend by :
git submodule add [add frontend repo http link] frontend
git submodule add [add backend repo http link] backend

Now after creating the submodule we have to test the repos: 
modify server.py and client.py in frontend and backend to ensure that both can read from donfig file
Create Action workflow:
create update_submodules.yml file
to update the full-stack repo when the changes aree push to the main
inside the file configure the email and username for github 




