In this project, I created a three-node Jenkins cluster (Master - Test & Prod). Jenkins was installed on the Master node, with jobs executed on Test and Prod nodes. Three jobs (Job1, Job2, Job3) were triggered via GitHub webhook. A commit to the develop branch triggers Job1, which builds an image and launches a container on the Test node. A commit to the master branch triggers Job2 and Job3, which build images and launch containers on Test and Prod nodes, respectively. This setup allows for application testing on a test server and deployment on a production server as containers. 

Here is the architecture diagram of project:

![image](https://github.com/xshatv/autobuild-workflow/assets/151455425/14082863-e1a9-4844-8608-edc565f32974)


**Skills Used:** Ansible, GitHub, Jenkins, Docker, Dockerfile, Linux, Bash, Html.
