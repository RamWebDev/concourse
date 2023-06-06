login:
	fly -t ps login -c http://localhost:6080 -u test -p test

status:
	fly -t ps status

targets:
	fly -t ps targets

userinfo:
	fly -t ps userinfo

pipelines:
	fly -t ps pipelines

run-pipeline:
	fly -t ps set-pipeline -c ./pipelines/find-all.yml -p mod1-pipeline

destroy-pipeline:
	fly -t ps destroy-pipeline -p mod1-pipeline

run-pipeline-load:
	fly -t ps set-pipeline -c ./mode3-pipeline-1.yml -p mod3-pipeline-1 --load-vars-from cred.yml

workers:
	fly -t ps workers -d

# alias ft="fly -t ps"