itontools
=========

ITisOpen.net's cloud toolbox

Developped for Ubuntu but should be really easy to port to Red Hat. I just could not find time to do it.

Make sure your boto installation is up-to-date before continuing. To do so, run the following command:

$ sudo easy_install -U boto

cd /opt
sudo git clone git://github.com/patlachance/itontools.git
sudo vi /opt/itontools/etc/itontools.cfg
sudo cp /opt/itontools/etc/rc.itontools /etc/init.d/itontools
sudo chmod 755 /etc/init.d/itontools
sudo ln -s ../init.d/itontools /etc/rc2.d/S99itontools

