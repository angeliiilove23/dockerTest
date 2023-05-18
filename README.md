# docker buil
git clone https://github.com/nowage/dockerTest
cd dockerTest/UbuntuDocer
docker build --rm -t angeliiilove/ut:v2 .
docker images

#docker run
docker run -it --name ut -v ~/df:/df --rm angeliiilove/ut:2
