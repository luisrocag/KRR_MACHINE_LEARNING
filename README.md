# Kernel Ridge Regression 

## 🎯 Objetivo del proyecto
Este proyecto implementa Kernel Ridge Regression (KRR) 

## 🧠 Descripción del método
KRR es un método de aprendizaje supervisado basado en espacios RKHS. 
El modelo resuelve el problema:

min_f sum (y_i - f(x_i))^2 + lambda ||f||^2

La solución tiene la forma:

f(x) = sum alpha_i K(x, x_i)

donde K es un kernel (RBF en este caso).

## ⚙️ Instrucciones de ejecución

### 1. Clonar repositorio
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo

### 2. Crear entorno (opcional pero recomendado)
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows

### 3. Instalar dependencias
pip install -r requirements.txt

### 4. Ejecutar código
python src/main.py

## 📊 Datos
Los datos se encuentran en la carpeta `data/` o pueden descargarse ejecutando:

python data/download_data.py

## 📈 Resultados
Los resultados se guardan en la carpeta `results/`.

## 📚 Referencias
- Schölkopf & Smola, Learning with Kernels
- Otros papers relevantes
