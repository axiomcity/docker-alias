# docker-alias


# DOCKER - CONTAINER 20
alias dalias="cat /home/david/.bashrc | grep '# DOCKER'"

alias drun="sudo docker run -itd" # DOCKER
alias dps="sudo docker ps -a" # DOCKER
alias dlogs="sudo docker logs -f"  # DOCKER

alias dstop="sudo docker stop" # DOCKER
alias dstopall="sudo docker container ps -aq | xargs sudo docker stop" # DOCKER

alias drm="sudo docker rm -f" # DOCKER
alias drmall="sudo docker container ps -aq | xargs sudo docker rm -f" # DOCKER

alias drestart="sudo docker restart" #DOCKER
alias drestartall="sudo docker container ps -aq | xargs sudo docker restart" #DOCKER

alias dkill="sudo docker kill" #DOCKER
alias dkillall="sudo docker container ps -aq | xargs sudo docker kill" #DOCKER

alias dpause="sudo docker pause" #DOCKER
alias dpauseall="sudo docker container ps -aq | xargs sudo docker pause" #DOCKER

# 80
alias dattach="sudo docker attach"  # DOCKER
alias dcommit="sudo docker commit"  # DOCKER
alias dcp="sudo docker cp"  # DOCKER
alias dcpall="sudo docker container ps -aq | xargs sudo docker cp"
alias dcreate="sudo docker create"  # DOCKER
alias ddiff="sudo docker diff"  # DOCKER
alias dexec="sudo docker exec"  # DOCKER
alias dexport="sudo docker export"  # DOCKER $ docker export <container_id> -o <filename>.tar
alias dinspect="sudo docker inspect"  # DOCKER
alias dport="sudo docker port"  # DOCKER
alias dprune="sudo docker prune"  # DOCKER
alias drename="sudo docker "  # DOCKER
