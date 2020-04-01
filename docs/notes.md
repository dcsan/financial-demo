add upstream master to your own fork

```
##
git remote add upstream git@github.com:RasaHQ/financial-demo.git
git fetch --all
git merge upstream/master

# create new branch
git co -b day2
# merge upsteam / specific branch in
git merge upstream/workshop_day_2_sandbox
git push -u

```
