## Hi there 👋

  <h1>Андрей Ильин</h1>
  <p><b>Data Scientist · ML Engineer</b></p>
  <p>Санкт-Петербург, Россия</p>

  <p>
    <a href="mailto:adversinsight@gmail.com">Email</a> ·
    <a href="https://t.me/andruxxann">Telegram</a> ·
    <a href="https://github.com/addrree">GitHub</a>
  </p>
</div>

---

## О себе
Занимаюсь прикладным ML/DS: от подготовки данных и метрик до прототипирования моделей и пайплайнов.  

---

## Избранные проекты

### 🔹 Vision Transformer (ViT) для идентификации лица с поддержкой масок
**Что сделано:** ViT-эмбеддинги лиц + учёт маски в self-attention, сравнение эмбеддингов (similarity search).  
**Ключевые компоненты:** Patch Embedding, CLS-token, Transformer Encoder (MHSA/MLP/LayerNorm), Mask Attention.  
**Метрики/анализ:** Accuracy/Precision, визуализация эмбеддингов (t-SNE/UMAP).  
**Стек:** Python, PyTorch, timm, torchvision, scikit-learn, Matplotlib/Seaborn.  
→ Репозиторий: https://github.com/addrree/ViT

### 🔹 RestoringValues — восстановление пропусков в потоковых данных датчиков
**Пайплайн:** WebSocket-симулятор → async-приём данных → импутация пропусков (KNN) → расчёт метрик → Dash-дашборд.  
**Метрики:** MAPE (и др. в логике расчётов), мониторинг качества в реальном времени.  
**Стек:** Python, websockets/asyncio, pandas, scikit-learn, Dash/Plotly.  
→ Репозиторий: https://github.com/addrree/RestoringValues

### 🔹 TDA для временных рядов (Human Activity Recognition, UCI)
**DS-пайплайн:** EDA временных рядов → динамические характеристики → Takens embedding →  
persistent homology / persistence diagrams → векторизация топологических признаков → ML-классификация/кластеризация.  
**Методы:** показатель Хёрста, экспоненты Ляпунова, диаграммы персистентности.  
**Стек:** Python, NumPy/pandas/SciPy, scikit-learn, giotto-tda, TensorFlow/Keras, Matplotlib.  
→ Репозиторий: https://github.com/addrree/TDA

### 🔹 Generate_dataset — генератор синтетического аудио-датасета
**Что делает:** генерирует `.wav` и разметку `.yaml`, комбинируя речь/музыку/шумы по YAML-сценариям.  
**Фичи:** препроцессинг в mono 16kHz PCM WAV, сценарии с ducking/fade/тишиной, управление длительностью и вероятностями.  
**Стек:** Python, FFmpeg, YAML, CLI-скрипты.  
→ Репозиторий: https://github.com/addrree/Generate_dataset

### 🔹 optics_hack — оптимизация оптических схем (хакатон)
**Идея:** генетический алгоритм и оптимизация параметров оптической схемы; есть режим генерации случайной схемы + дальнейшая оптимизация.  
**Инструменты:** генетический алгоритм, scipy.optimize.minimize, многопроцессный запуск (scoop).  
**Результаты:** в репозитории приведены примеры решений с низкими значениями loss (вплоть до однозначных).  
→ Репозиторий: https://github.com/addrree/optics_hack

---

## Технологии
- **ML/DL:** PyTorch, timm, scikit-learn, TensorFlow/Keras  
- **Data:** pandas, NumPy, SciPy  
- **Визуализация:** Matplotlib, Plotly/Dash  

---

## Контакты
- Email: adversinsight@gmail.com  
- Telegram: https://t.me/andruxxann

