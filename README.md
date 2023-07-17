# capstone-aws
**Rough order in which the capstone was completed**
  
  • Installed Git Bash
  
  • Created a folder for the cloned repository
 
  • Changed directory to the folder
 
  • Cloned the repository - git clone https://github.com/babaJay23/capstone-aws.git
  
  • Created the empty dockerfile
  
  • Edited the file to include the proper content
  
  • Pushed to my github repository
  
  • Built the Docker image - docker build -t gitcapstone
  
  • Ran docker images to verify - docker images --filter reference=gitcapstone
  
  • Run image - docker run -t -i -p 80:80 gitcapstone
  
  • Set up AWS EC2 instance
  
  • Unable to connect through ip and ec2 connect
  
  • Terminate EC2 instance
  
  • Create new EC2 instance  ![image](https://github.com/Khai5/gitcapstone/assets/82977630/2d1ae014-f3f5-43ff-a8d2-62b317809e59) 
  
  • Able to connect
  
  • Update instance - sudo yum install -y
  
  • Install most recent Docker Engine Package - sudo amazon-linux-extras install docker
  
  • Start Docker - sudo service docker start
  
  • Ensure Docker daemon starts on reboot - sudo systemctl enable docker
  
  • Enable ec2-user to use docker without sudo - sudo usermod -a -G docker ec2-user
  
  • Reboot EC2 instance due to error: Cannot connect to the Docker daemon.
  
  • Clone repository - git clone https://github.com/Khai5/gitcapstone.git
   
  • Use ls command to check for proper cloning
  
  • Change directory to proper location - cd gitcapstone
  
  • Use ls to check for files
  
  • Use docker info to check integrity
  
  • Build new image - docker build gitcapstone
  
  • Run container on port 80 - docker run -t -i -p 80:80 gitcapstone
  
  • Realize that I forgot to make changes to the html
  
  • Change some words on index.html and upload new picture and then pushed ![image](https://github.com/Khai5/gitcapstone/assets/82977630/40bd2a66-7893-4e98-817e-4234524cbd3e) ![image](https://github.com/Khai5/gitcapstone/assets/82977630/e7a1f414-3db7-4dea-b01b-ff34b3dacb24) ![image](https://github.com/Khai5/gitcapstone/assets/82977630/3258c5e5-5601-4bb8-a641-b8fb84195091)
 
  • Ctrl C to close the container
  
  • Pulled new updates - git pull https://github.com/Khai5/gitcapstone.git
  
  • Check status - docker info ![image](https://github.com/Khai5/gitcapstone/assets/82977630/36d60875-4d3c-43c3-a3bf-253d5b94a7ed)
  
  • Rebuild container for updates - docker build -t gitcapstone
  
  • Run container on port 80 - docker run -t -i -p 80:80 gitcapstone
  
  • Created a file with yaml extension
  
  • Copy and pasted the code into the file
  
  • Upload onto CloudFormation
  
  • Run into formatting issues
  
  • Attempt to fix by adding indentation and creating stack in repetition until errors subside ![image](https://github.com/Khai5/gitcapstone/assets/82977630/56ea9d2f-cd98-4c71-af9f-e36585113e11)

  • Try YAML online formatters to no success

  • Run out of time
