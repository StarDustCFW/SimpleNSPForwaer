# SimpleNSPForwader
* Instala [devkitPro](https://github.com/devkitPro/installer/releases/latest)
* Edita [compile.bat](/compile.bat)
```bat
echo ------------------------------------------
rem Edit This
set APP_ICON=Icon.jpg
set APP_TITLE=RetroArch
set APP_AUTHOR=Kronos2308
set APP_VERSION=1.9.5
set APP_TITLEID=05B80C7D3B860000
set APP_USEL=sdmc:/switch/retroarch_switch/retroarch_switch.nro
set APP_USE=sdmc:/switch/retroarch_switch.nro
echo -----------------------------------

```
Deberas escribir los valores según necesites
<li>APP_ICON icono dell nsp 
<li>APP_TITLE Titulo del NSP
<li>APP_AUTHOR El autor del nsp
<li>APP_VERSION Version Pude ser lo que sea solo numeros
* importantes
<li>APP_TITLEID Title ID del nsp
<li>APP_USEL es la ruta principal que se usara primero
<li>APP_USE Ruta alternativa si la primera no existe 
