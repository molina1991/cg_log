### Abrir pestañas de chrome con una URL (si no se indica URL se abre la pestaña vacía por defecto)
ssh user@IP -X google-chrome 'URL'

### Volumen:
- Conectarse por SSH
* Bajar el volumen un porcentaje: amixer -D pulse sset Master 10%-
* Subir el volumen un porcentaje: amixer -D pulse sset Master 10%+
* Unmute: amixer -D pulse sset Master unmute
* Mutear: amixer -D pulse sset Master mute

### Abrir disquetera:
- Conectarse por SSH
* eject

### Girar pantalla:
- Conectarse por SSH
* xrandr --output <HDMI1 (obtener con xrandr -q)> --rotate <normal,inverted,left,right>

### Cambiar botones del ratón:
- Conectarse por SSH
* xinput set-button-map <11 (obtener con xinput list)> 3 2 1
