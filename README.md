# Proyecto-Reviviendo-una-vieja-laptop-con-Linux
Documentación sobre la instalación de Linux Mint para uso diario en una vieja laptop DELL, más la configuración de exegol para correr Kali Linux dentro de ambiente Docker para desarrollo de futuros laboratorios en el ámbito de la ciberseguridad


Decidí darle nueva vida a mi vieja laptop Dell, por lo que decidí cargarle una versión de Linux con bajos requisitos, ya que, al ser tan antigua, no corría bien ningún programa ni proceso.
Pero no por ser un equipo viejo, significa que este sea obsoleto. Mientras verificaba las especificaciones de hardware, me percaté de que cuenta con una tarjeta de red que soporta el modo monitoreo, lo que abre las posibilidades para laboratorios de pentesting utilizando comandos de Kali Linux como airmon-ng o aircrack-ng.
Con esto en mente, la elección fue Linux Mint 22.3 Xfce Edition por sus bajos requisitos de hardware y similar aspecto y funcionamiento a Windows (ya se lo que estan pensando, Mint no es conocido por sus herramientas para pentesting específicamente).
Como es una versión mas liviana que Linux Mint standard, eso nos deja con espacio suficiente en disco para correr Kali dentro de un container utilizando Docker, con el repositorio de Exegol para que Kali se comunique e interactue directamente con el hardware del equipo (la tarjeta de red en este caso es lo que mas nos interesa)
De esta manera, maté dos pájaros de un tiro. Por una parte, tengo un sistema operativo funcional para uso diario que le da nueva vida a un viejo notebook. Por otra parte, tengo una potente herramienta de pentesting con acceso directo al hardware del dispositivo para pruebas reales.

