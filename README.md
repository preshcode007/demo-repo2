#  Trying out the 2nd Demo accounts !!!

## Local Development
1. open index.html in your local browsergit 

# Challenges I encoutered 
While trying to commit from my local machine to Github I faced 2 challenges. 
- Firstly I encountered issues generating an SSH KEY as I was using the ``` ssh-keygen -t rsa -b 4096 -C okiemenprecious@gmail.com``` command. I then used the ``` ssh-keygen -t ed25519  -C okiemenprecious@gmail.com``` and it worked. I then realised that the RSA Algorithm was outdated and was replaced with ED25519 Algorithm.

- Secondly, I encountered challenges pushing my commited demo-repo from my local machine to Github. I was always getting an error message 
![failed to push to Github](assests/demo-repo.%20prob%20to%20gorigin-master%20(2).png)

I was able to resolve it by using the ```git push -u origin main```  command instead of the ```git push -u origin master``` command ![solution](assests/demo-repo.%20solu%20to%20gorigin-master%20(1).png)
