**PAT (personal access token)**
from 2021 GITHUB stopped providing access using username and password it uses PAT. 
Go to Account > settings > Developer settings > PAT classic > Genterate token > <onetimegeneratedtoken>
How to push files from local repo to remote repo (Github)?
Create a connection with remote repository
step1: **create a repository in the github**
step2: **add remote repository to the local git**
git remote add myapp <https connection from repo created in github>
step3: git push myapp master
