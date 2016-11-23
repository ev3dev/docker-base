Ev3dev Docker Base
==================

This repository is for creating minimal docker images that serve as the base
for <https://github.com/ev3dev/docker-library>.

The images are created from official debian (armel and armhf) and raspbian
(armhf) sources using `qemu-debootstrap`.

Image names are in the format $OS-$DIST-$ARCH. The images are:

    ev3dev/debian-jessie-armel-qemu-minbase
    ev3dev/debian-jessie-armhf-qemu-minbase
    ev3dev/raspbian-jessie-armhf-qemu-minbase
    ev3dev/debian-testing-armel-qemu-minbase
    ev3dev/debian-testing-armhf-qemu-minbase
    ev3dev/raspbian-testing-armhf-qemu-minbase

Images are hosted on Docker Hub: <https://hub.docker.com/u/ev3dev/>.
