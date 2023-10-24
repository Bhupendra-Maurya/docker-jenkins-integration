# This is Github integration with Jenkins
- First create a Web site using Html,Css,Js
- Create a Dockerfile and add these lines into it.
- Now build the file and give a tagname.
- Now go to Jenkins
  - Create a Freeproject
  - Add your git credentials
  - Add your git repo.
  - Slect your branch (*/main/master etc.)
  - `Write the build steps`
    - docker build . -t  mywebsite
    - docker run -p 8000:8000 -d mywebsite
### Apply & Save
