# Wordpress Server with docker-compose

1. Clone this repository
```
$ git clone https://github.com/cbelda/docker-wordpress.git
```
2. Start docker containers
```
# docker-compose up -d
```

3. Explore your current directory to check if all volumes had been correctly created:
```
root@your-domain.com:~/wordpress# ll
total 16
drwxr-xr-x  3 root root 4096 Mar 22 16:04 ./
drwx------ 33 root root 4096 Mar 22 16:05 ../
-rw-r--r--  1 root root  474 Mar 22 16:04 docker-compose.yml
-rw-r--r--  1 root root  198 Mar 22 16:04 README.md
drwxr-xr-x  3 root root 4096 Mar 22 10:07 volumes/
```