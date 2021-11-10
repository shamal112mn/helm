# Lab
How to use helmfile with github

<ul>
<li> Prerequizite: </li>
<li> 1 Install helmfile: for mac -> brew install helmfile </li>

<li> 2  install helm git plugin 
  helm plugin install https://github.com/aslafy-z/helm-git
</li>
 
 <li> 3 clone project</li>
<li> cd helm  -> to the helmfile f</li>
<li> vi helmfile to update false to true</li>
<li> run: helmfile sync    and will install helmcart</li>
<li> get nodeport IP and srv port</li>
<li> for minikube run:  minikube service serviceName --url </li>
<li> </li>
<li> to Uninstall</li>
<li>update helmfile from true to false </li>
<li>run: helmfile sync </li>
<li> </li>
<li> </li>
</ul>