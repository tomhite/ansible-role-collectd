# Ansible Role: collectd
Ansible role to install and configure CollectD

## Requirements

## Role Variables in default

Variable indicating where the colectd docker container files are pushed to for building image on remote server
collectd_docker_install_dir: /var/lib/collectd-docker

Variable indicating where the collectd docker file and location for building image on remote server
collectd_docker_file: "/var/lib/collectd-docker/Dockerfile"

Target config file location and name WITHIN the docker namespace
collectd_conf_file: "/var/lib/collectd-docker/collectd.conf"

Target directory and file name for run script when the image is run - WITHIN the docker namespace
collectd_run_script_file: "/var/lib/collectd-docker/run.sh"

Target log file location and name WITHIN the docker namespace
collectd_log_file: "/var/log/collectd.log"

Version of docker
docker_api_version: 1.18

Port opened on the docker host port and container port
collectd_host_port: 25826
collectd_container_port: 25826

## Dependencies

## Example Playbook

## License

## Author Information



