# Plate-based Autonomous car
Autonomous miniature car that drives based on plates with numbers on it. Each number has a command associated with and the car recognizes the number (using FlaNN library trained with MNIST database) to know what should it do. The car system is based on a raspberry-pi, working as a server, and a local linux computer, working as a client.

## Technologies and Technics
<li> Cekeikon: A OpenCV based library for Image Processing and Computer Vision - http://www.lps.usp.br/hae/software/cekeikon5.html
<li> TCP/IP Communication Based on Sockets
<li> FlaNN - Library for performing fast approximate nearest neighbor searches. - https://github.com/flann-lib/flann
