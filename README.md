# Jenkins-Pipeline-CI-CD

**The idea is to have Jenkins setup, and can accomplish the following:**

- Create a github public repo 
- The repo should have a basic html code [Link](https://www.mkyong.com/html/html-tutorial-hello-world/)
- Any code changes pushed to Github repo should trigger a Jenkins job which should run [html linter](https://pypi.org/project/html-linter/) 
- In case the linter fails, the Jenkins job should fail, in case it passes, another Job should be triggered automatically that deploys the code using Apache Server. 
Commit After Github linkage.
