Video:
https://www.youtube.com/watch?v=Mm0P1aiB_bo

Installing SIP on Ubuntu:

2- replace other files in this repo:
https://github.com/tecno14/SIP

3- update sip.conf settings like:
localnet=10.0.0.0/255.0.0.0
externip=203.161.38.176

4-

sip set debug off
sudo asterisk -vvvr
module load chan_sip.so
reload
sip show peers
exit

5- install sip clients
