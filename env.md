
cd /etc/profile.d
echo export VARIABLE_NAME="VARIBALE_VALUE">/etc/profile.d/customenv.sh
chmod 0755 /etc/profile.d/customenv.sh
if we do second 
echo export VARIABLE_NAME222="VARIBALE_VALUE222">/etc/profile.d/customenv.sh
it will overwrite the first value
