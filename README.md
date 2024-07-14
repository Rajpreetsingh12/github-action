Steps for creating the workflow on the Github Action

1.create the folder named .github on local
2.and inside it created workflows and inside it created the main.yml file
    eg:- .github/workflows/main.yml
3.now come on the github repo dashboard click on the settings-secrets & variables-actions
4.on the Actions secrets and variables dashboard click on newrepository-secret button.
5.then created three secrets:-
                            1)EC2_HOST=public ip
                            2)EC2_SSH_KEY=content of the .pem key you downloaded on your local
                            3)EC2_USERNAME=ubuntu
6.now click on the actions button present on your repository dashboard.
7.now you will be able to see all of your workflows you created in that you will 
see the recent naming the the commit you did in the last on your remote from local.
8.now click on that then click on deploy button then your workflow will be getting dpeloyed.
and you will be able to see all the steps getting deployed one after one in a flow in that.
plz find attached ss link for reference.
![image](https://github.com/user-attachments/assets/5d854e52-80de-4a1d-9cc2-b4f229a65612)
