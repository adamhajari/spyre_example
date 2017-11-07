Steps:
---

1. work through google's [hello world example](https://cloud.google.com/python/getting-started/hello-world#deploy_and_run_hello_world_on_app_engine)
2. clone this repo and cd to repo's directory
3. test app locally
4. push repo to the google cloud repo
5. create instance with startup-script


## content of repo
1. startup script
2. spyre app
3. requirements.txt


git commit -am "Updating configuration"
git config credential.helper gcloud.sh
git remote add cloud https://source.developers.google.com/p/spyre-example/
git push cloud