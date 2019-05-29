# lime-repo

Based on the git project
https://github.com/ThreatResponse/lime-compiler

Folder structure:
Build/Modules: contains all pre-complied images
Build/Repodata: contain hashs and kernel descriptio of all pre-complied files
Archive: compressed KO file per distribution.


config file
images:
  amzn1:
    image: "amazonlinux"
    tag: "latest"
    distribution: 'amzn1'
  debian7:
    image: "debian"
    tag: "7"
    distribution: 'debian'
  debian8:
    image: "debian"
    tag: "8"
    distribution: 'debian'
  centos6:
    image: "centos"
    tag: "6"
    distribution: 'centos'
  centos7:
    image: "centos"
    tag: "7"
    distribution: 'centos'
  ubuntu-12.04:
    image: "ubuntu"
    tag: "12.04"
    distribution: "ubuntu"
  ubuntu-14.04:
    image: "ubuntu"
    tag: "14.04"
    distribution: 'ubuntu'
  ubuntu-15.10:
    image: "ubuntu"
    tag: "15.10"
    distribution: "ubuntu"
  ubuntu-16.04:
    image: "ubuntu"
    tag: "16.04"
    distribution: "ubuntu"
  ubuntu-16.10:
    image: "ubuntu"
    tag: "16.10"
    distribution: "ubuntu"
