# Creating the project folder called Shell


`mkdir Shell`


![Creating project folder called Shell](./Images/Creating%20project%20folder%20Shell.png)




# Move into the Shell folder

`cd Shell`


![Moving into the Shell folder](./Images/Moving%20into%20the%20Shell%20folder.png)

#  Creating a csv file name names.csv


`touch names.csv`


![Creating a csv file name names.csv](./Images)


#  Opening the names.csv file


`vim names.csv`


![Opening the names.csv file](./Images/Opening%20the%20names.csv%20file.png)


# Creating onboard.sh 


`vi onboard.sh`


![Creating onboard.sh](./Images/Creating%20onboard.sh.png)

# Copying over using scp


`scp -i AuxProject.pem onboard.sh ubuntu@52.71.13.27:~/;`


# Creating a file for the public key


`touch id_rsa.pub`


![Creating public key](./Images/Creating%20the%20public%20key.png)



# Pasting in the public key


`vi id_rsa.pub`


![Pasting in the public key](./Images/Pasting%20in%20the%20public%20key.png)


# creating a file for your private key


`touch id_rsa`


![creating a private key](./Images/creating%20private%20key.png)


# Pasting in the private key


`vi id_rsa`


![Pasting in the private key](./Images/Pasting%20in%20the%20private%20key.png)


#  Creating and Setting public key for users

`vi onboard.sh`


![Creating and Setting public key for users](./Images/Creating%20and%20Setting%20public%20key%20for%20users.png)



#  Creating developer Group

`sudo groupadd developers`
`sudo chmod +x onboard.sh`

![Creating developer Group](./Images/Creating%20developer%20Group.png)

![Creating developer Group](./Images)

#  Developer Group Created

`ls -l /home/`


![developer Group](./Images/developer%20Group.png)

#  Users test randomly

`ssh -i aux-proj.pem Williams@52.71.13.27`


![Users test randomly](./Images)








