# Local installation

* install webdav volume driver from https://github.com/fentas/docker-volume-davfs
* create local mount from nextcloud: `docker volume create -d fentas/davfs -o ro -o url=https://mhanheide:NEXTCLOUD_APP_TOKEN@lcas.lincoln.ac.uk/nextcloud/remote.php/dav/files/mhanheide/L-CAS/Datasets -o uid=1000 -o gid=1000 nextcloud_mhanheide`