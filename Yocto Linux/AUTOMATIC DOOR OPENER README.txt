setup:

echo "src npm http://iotdk.intel.com/repos/3.5/iotdk/galileo/i586/" > /etc/opkg/iotdk.conf
opkg update
opkg install nodejs
opkg install nodejs-npm

