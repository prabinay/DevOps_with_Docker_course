 docker run -it 2eb79d63a355 sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'
  596 

apt-get update
apt-get install curl

curl helsinki.fi
