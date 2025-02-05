# Generative Adversarial Network (GAN) - Fashion MNIST

## 📌 Descripción del Proyecto
Este proyecto implementa una **Red Generativa Adversarial (GAN)** para generar imágenes de prendas de vestir y accesorios a partir del dataset **Fashion MNIST**. La red consta de dos modelos:
- **Generador**: Crea imágenes falsas de prendas.
- **Discriminador**: Diferencia entre imágenes reales y generadas.

## 📂 Estructura del Proyecto
```
📂 GAN_FashionMNIST
│-- 📂 images/              # Imágenes generadas durante el entrenamiento
│-- 📂 models/              # Modelos guardados (generator.h5, discriminator.h5)
│-- 📜 README.md            # Documentación del proyecto
│-- 📜 GAN_FashionMNIST.ipynb # Cuaderno Jupyter con el código
```

## 🛠 Tecnologías Utilizadas
- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

## 📊 Dataset
Se utiliza **Fashion MNIST**, un conjunto de datos con imágenes de 28x28 píxeles en escala de grises de diferentes tipos de ropa, incluyendo:
- Camisetas
- Pantalones
- Zapatos
- Bolsos, entre otros.

## 🔧 Instalación y Configuración
1. Clonar el repositorio:
   ```sh
   git clone https://github.com/TU_USUARIO/mi_GAN_FashionMNIST.git
   cd mi_GAN_FashionMNIST
   ```
2. Instalar dependencias:
   ```sh
   pip install -r requirements.txt
   ```
3. Abrir el cuaderno Jupyter y ejecutar:
   ```sh
   jupyter notebook GAN_FashionMNIST.ipynb
   ```

## 🚀 Entrenamiento del Modelo
Para entrenar la GAN, ejecutar el cuaderno **GAN_FashionMNIST.ipynb**.

```python
train(train_dataset, EPOCHS)
```

El proceso generará imágenes sintéticas de prendas y guardará los modelos:
```sh
models/generator.h5
models/discriminator.h5
```

## 📷 Resultados
Cada 10 épocas, la GAN generará imágenes nuevas y las guardará en la carpeta **images/**.

Ejemplo de imágenes generadas:
![Ejemplo](images/image_at_epoch_50.png)

## 📤 Guardado de Modelos
```python
generator.save("models/generator.h5")
discriminator.save("models/discriminator.h5")
```

## 🔥 Contribuciones
Si deseas mejorar el proyecto:
1. Haz un fork del repositorio.
2. Crea una rama con tu nueva funcionalidad: `git checkout -b nueva_funcionalidad`
3. Sube los cambios: `git commit -m 'Añadida nueva funcionalidad'`
4. Haz un pull request.

## 📄 Licencia
Este proyecto está bajo la licencia **MIT**. ¡Siéntete libre de usarlo y mejorarlo!

---
🚀 **¡Gracias por tu interés en el proyecto!**

