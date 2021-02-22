# Montag

---

## Table of Contents

[Git and Github](#git-and-github)

[Tools](#tools)

[Specific to tomn](#tomn)

---

## Push README


```bash
git add README.md; git commit -m "Changed README.md file"; git push origin master

```

---

## Sandbox

```bash
cp /Volumes/Data/Projects/___ProjectBuilder/Buttons.jar .

java -jar Buttons.jar

docker rmi $(docker images |grep 'imagename')
```

---

## Docker - Start and Stop

```bash
docker stop $(docker ps -aq) && docker rm $(docker ps -aq)

```

```bash
docker exec -it my-tomcat-container /bin/sh
docker rmi -f $(docker images -a -q)
```



---

## Browser

```bash
/usr/bin/open -a /Applications/Google\ Chrome.app http://localhost:8080/

```

---

## Finder

```bash
/usr/bin/open -a /System/Library/CoreServices/Finder.app .

```


---

# Git and Github

---

## Clone project

```bash
cd ~
git clone https://github.com/tomnoland/Montag
cd Montag

```
---

## Hub - Create and Add Remote Repo

```bash
hub create
git remote add $PROJECT_NAME git@github.com:tomnoland/$PROJECT_NAME.git

```

---

## Push all

```bash
GIT_COMMIT_MESSAGE=

```

```bash
git add .
git commit -m $GIT_COMMIT_MESSAGE
git push origin master

```

---

## Pull

git pull origin master

---

## Tools


```bash
cd New-Project-Template

```

```bash
/usr/bin/open -a /System/Library/CoreServices/Finder.app .

```

```bash
"/Applications/NetBeans/Apache NetBeans 11.1.app/Contents/Resources/NetBeans/bin/netbeans" README.md

```

---

## tomn


```bash
cd New-Project-Template

```

```bash
/usr/bin/open -a /System/Library/CoreServices/Finder.app .

```

```bash
"/Applications/NetBeans/Apache NetBeans 11.1.app/Contents/Resources/NetBeans/bin/netbeans" README.md

```

---

## Sandbox


```bash
echo Buttons.jar > .gitignore
echo Project_Notes.txt-e >> .gitignore
echo ./resources/scripts/SetGithubDeployKey.sh >> .gitignore
echo .ssh >> .gitignore
git add .
git commit -m "And so, it begins."

```
---
