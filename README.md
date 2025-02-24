# Odoo-Patch-WT
URI: https://nightly.odoo.com/master/nightly/deb, https://www.webtoolkit.eu/wt  
  
## Odoo18 Enterprise Edition Configuration
URI: https://odoo.mxc.cc/odoo/system-parameters  
New: database.expiration_date = 9999-12-31 23:59:59  
End: sudo systemctl restart odoo.service  
Alt:  
    sudo update-alternatives --install /usr/lib/python3/dist-packages/odoo odoo /usr/lib/python3/dist-packages/odoo-ce 1  
    sudo update-alternatives --install /usr/lib/python3/dist-packages/odoo odoo /usr/lib/python3/dist-packages/odoo-ee 2  

