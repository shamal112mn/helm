# Lab
How to use helmfile with github

Prerequizite:
1 Install helmfile: for mac -> brew install helmfile
2 run helm create chartName
3 # install helm git plugin 
helm plugin install https://github.com/aslafy-z/helm-git

4 create helmfile.yaml and paste in
---
repositories:
  - name: helloworld
    url: git+https://github.com/rahulwagh/helmchart@chartName?ref=master&sparse=0

releases:
  - name: helloworld
    chart: helloworld/helloworld
    installed: false 

