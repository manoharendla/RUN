# RUN

1.Create a new repository in internal github.com with  name AutomateJenkinsInternal
2. From  terminal go into your git folder and run  git clone https://github.com/manoharendla/AutomateJenkins.git 
3. run rm -rf AutomateJenkins/.git
4. cd AutomateJenkins
5. cp -Rf . ../AutomateJenkinsInternal
6. cd ../AutomateJenkinsInternal
7. docker build -t jenkins-cicd .
8. Run the docker tag and push command used earlier
