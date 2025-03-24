# Módulo de Kernels de Convolución  

Este módulo proporciona una colección de filtros de convolución utilizados en redes neuronales convolucionales (CNN) para el procesamiento de imágenes. Permite aplicar distintos kernels a imágenes estáticas y videos en tiempo real.  

## 📌 Características  

✅ Aplicación de filtros predefinidos:  
- **Identidad** (imagen original)  
- **Blur** (suavizado de ruido)  
- **Gaussiano** (suavizado natural)  
- **Sobel X / Y** (detección de bordes)  
- **Laplaciano** (detección de bordes mejorada)  
- **Sharpen** (realce de detalles)  

✅ Procesamiento de imágenes estáticas y en video en tiempo real.  
✅ Selección interactiva de filtros para videos.  

## 🛠 Instalación  

Asegúrate de tener Python instalado y luego ejecuta:  

```bash
pip install numpy opencv-python matplotlib
🚀 Uso
Aplicar filtros a una imagen
Ejecuta la siguiente función para visualizar los efectos de los filtros en una imagen estática:

python
Copiar
Editar
from kernel_module import convolution_kernel

convolution_kernel()
Aplicar filtros en video en tiempo real
Para seleccionar un filtro y aplicarlo a la imagen capturada por la cámara:

python
Copiar
Editar
from kernel_module import choose_one_kernel

choose_one_kernel()
