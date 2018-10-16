The BabbleSim project consists of many components, most of them optional
and each in its own separate git repository.

The recommended way to fetch them is by using `Androids repo
<https://source.android.com/setup/develop/repo>`_ ::

  mkdir ~/bsim/ && cd ~/bsim/
  repo init -u git@github.com:BabbleSim/manifest.git -m everything.xml -b master
  repo sync


This repository contains manifest files including different sets of components
covering different needs:

* everything.xml : All BabbleSim components hosted in this server
* zephyr_ci.xml  : Deprecated
* zephyr_docker.xml : Used BabbleSim components in Zephyr's CI docker image
