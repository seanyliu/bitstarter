git checkout develop
EDIT
git commit -a -m "MESSAGE"
git push origin develop

git checkout staging
git merge develop
git push origin staging
git push staging-heroku staging:master

git checkout master
git merge staging
git push origin master
git push production-heroku master:master

https://d396qusza40orc.cloudfront.net/startup%2Flecture_slides%2Flecture7-deployment-dns-custom-domains.pdf
