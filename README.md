# fork-sync-automation
A job that runs on github actions to sync all my PUBLIC forks. Will not work for private repos due to auth constraints.

Simply add the GH_PAT secret to your repo and it will run daily at 3:15 AM UTC. Depending on how many repos you've forked, and consequently how many branches the repos have, the script should run for less than a minute to ~5mins. Barely making a dent on your github actions monthly quotas. 
