sudo ln -s /home/pi/PiCamMatrix/init.d/camtopleft /etc/init.d/camtopleft
sudo ln -s /home/pi/PiCamMatrix/init.d/camtopright /etc/init.d/camtopright
sudo ln -s /home/pi/PiCamMatrix/init.d/cambottomleft /etc/init.d/cambottomleft
sudo ln -s /home/pi/PiCamMatrix/init.d/cambottomright /etc/init.d/cambottomright
sudo update-rc.d camtopleft defaults
sudo update-rc.d camtopright defaults
sudo update-rc.d cambottomleft defaults
sudo update-rc.d cambottomright defaults
