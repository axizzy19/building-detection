## Запуск проекта

### 1. Клонирование репозитория

```bash
git clone https://github.com/your-username/building-segmentation.git
cd building-segmentation
```

### 2. Создание окружения

```bash
conda create -n building_det python=3.9
conda activate building_det
```

### 3. Установка зависимостей

```bash
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
pip install numpy matplotlib opencv-python pandas scikit-learn pillow albumentations jupyter
```

### 4. Запуск Jupyter Notebook

```bash
jupyter notebook --no-browser --ip=0.0.0.0
```

### 5. Обучение модели
Веса модели сохранены в папке
```bash
models/unet.pth
```
