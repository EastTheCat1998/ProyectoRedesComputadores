 ProyectoRedesComputadores
Código e instrucciones del proyecto
 Análisis de Congestión en Redes LAN

 Descripción
Este proyecto analiza el tráfico de una red LAN a partir de archivos de captura (`.pcap`), detectando posibles congestiones y retransmisiones de paquetes. Utiliza `pyshark` para procesar los datos y `matplotlib` para la visualización gráfica.

Se puede correr el archivo run.sh que está en el repositorio o seguir las instrucciones a continuación. 

 Requisitos del Sistema
- Sistema Operativo:* WSL (Ubuntu)  
- Python 3.8 o superior 
- Wireshark instalado (para capturar paquetes y utilizar TShark)  
- Librerías necesarias: `pyshark`, `pandas`, `matplotlib`, `tkinter`

 Instalación
 1. Instalar Python y las dependencias
Si no tienes Python instalado, descárgalo desde [python.org](https://www.python.org/downloads/) y asegúrate de agregarlo al PATH.

Luego, instala las dependencias necesarias con:
```bash
pip install pyshark pandas matplotlib
```

2. Descargar el código
Puedes clonar este repositorio con Git:
```bash
git clone https://github.com/tu_usuario/Congestion-Redes-LAN.git](https://github.com/EastTheCat1998/ProyectoRedesComputadores
```
O descargar manualmente los archivos y ubicarlos en una carpeta.

3. Ejecutar el programa
Ejecutar en Python
```bash
python analisis.py
```
Aparecerá una ventana para seleccionar un archivo `.pcap`. El programa generará un `trafico.csv` con los resultados y un gráfico mostrando el tráfico de red.

Ejecutar el programa compilado (`.exe`)
Si tienes `analisis.exe`, simplemente haz doble clic en el archivo y sigue las instrucciones en pantalla.

Salida del Programa
El programa generará:
- Un archivo `trafico.csv`con los datos analizados.
- Un gráfico `grafico_paquetes.png` con el número de paquetes por segundo.

Notas Adicionales
- Si no se detectan retransmisiones, significa que la red no presentó congestión en ese momento.
- Puedes capturar más tráfico con Wireshark y volver a ejecutar el análisis para obtener diferentes resultados.

Autor: Esteban Erazo
Repositorio: [GitHub]([https://github.com/tu_usuario/Congestion-Redes-LAN)](https://github.com/EastTheCat1998/ProyectoRedesComputadores)

