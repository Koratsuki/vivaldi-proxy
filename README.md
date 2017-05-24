# vivaldi-proxy

#Esp

Proxy settings para Vivaldi -> https://vivaldi.com/

Editar/Añadir al archivo /usr/share/application/vivaldi-stable.desktop, y así Vivaldi usará proxy para navegar. Nota: cambiar proxy.dominio.cu por el proxy que tenga en su empresa/centro de trabajo.

Exec=/usr/bin/vivaldi-stable --proxy-server==proxy.dominio.cu:3128 --proxy-bypass-list=="*.dominio.cu;localhost;127.0.0.1;192.168.0.0/16" %U


#Eng

Proxy settings for Vivaldi Browser -> https://vivaldi.com/

Edit/Add this line to /usr/share/application/vivaldi-stable.desktop file, and Vivaldi will use proxy authentication. Note: Change proxy.dominio.cu for your company proxy.

Exec=/usr/bin/vivaldi-stable --proxy-server==proxy.dominio.cu:3128 --proxy-bypass-list=="*.dominio.cu;localhost;127.0.0.1;192.168.0.0/16" %U

