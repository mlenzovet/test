test-multiplicate.ipynb - решение задачи умножения листа самого на себя

goznak-class.ipynb - задача классификации

никаких команд и алгоритмов не нужно, просто запускаем все в ноутбуке - работает 

os.walk('/kaggle/input') - нужно только заменить адрес на путь к своим папкам в распакованном виде или в виде ZIP

learn.predict(npy_load(path))[0] - чтобы сделать предсказание из своего .npy файла - нужно подставить сюда path к нему

чтобы не ставить библиотеки, можно либо воспользоваться kaggle ноутбуком, или его образом https://console.cloud.google.com/gcr/images/kaggle-gpu-images/GLOBAL/python@sha256:2af29ddd126e13ed6b1aebdd84c7f87992e71290f852f0bccd53df1ed7408594/details
