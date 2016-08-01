Ev3dev Docker Base
==================

This repository is for creating minimal docker images that serve as the base
for <https://github.com/ev3dev/docker-library>.

The images are created from official debian (armel and armhf) and raspbian
(armhf)sources using `qemu-debootstrap`.

Image names are in the format $OS-$DIST-$ARCH. The images are:

    ev3dev-docker-docker.bintray.io/debian-jessie-armel
    ev3dev-docker-docker.bintray.io/debian-jessie-armhf
    ev3dev-docker-docker.bintray.io/raspbian-jessie-armhf
