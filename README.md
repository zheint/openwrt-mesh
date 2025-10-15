# openwrt-mesh

![language](https://img.shields.io/github/languages/top/onemarcfifty/openwrt-mesh)    ![License](https://img.shields.io/github/license/onemarcfifty/openwrt-mesh)    ![Last Commit](https://img.shields.io/github/last-commit/onemarcfifty/openwrt-mesh)     ![FileCount](https://img.shields.io/github/directory-file-count/onemarcfifty/openwrt-mesh)    ![Stars](https://img.shields.io/github/stars/onemarcfifty/openwrt-mesh)    ![Forks](https://img.shields.io/github/forks/onemarcfifty/openwrt-mesh)

Scripts to support my Wifi-Mesh videos on https://youtube.com/onemarcfifty

make_dumb_ap:    turns a factory-setting OpenWrt router into a dumb Access point
make_mesh_point: adds mesh functionality, Mesh network and Wifi network

1. SSH into your router
2. run make_dumb_ap.sh
3. wget -O make_dumb_ap.sh (https://raw.githubusercontent.com/onemarcfifty/openwrt-mesh/refs/heads/main/make_dumb_ap.sh)
	    chmod +x make_dumb_ap.sh
		sh make_dumb_ap.sh
	
4. the router reboots - find the new IP and log into ssh again
5. run make_mesh_point.ssh
6. wget -O make_mesh_point.sh https://raw.githubusercontent.com/zheint/openwrt-mesh/refs/heads/main/make_mesh_point.sh
	    chmod +x make_mesh_point.sh
		sh make_mesh_point.sh

You now have an access point with mesh!

Enjoy.
