# Face Recognition мини проект для Senim.kz

- Используемый скрипт взят отсюда: https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_from_video_file.py
- Используется библиотека [face_recognition](https://github.com/ageitgey/face_recognition)

facerec_from_video_file.py выполняет следующие действия:
1. Берет информацию о размерах лиц Димаш Кудайбергена и Игоря Крутого с фотографий: dimash.jpg, igor.jpg
2. Читает видео файл dimash_igor.mp4, находит и определяет лица
3. Сохраняет видео файл output.avi, где рисует четырехугольники вокруг определенных лиц и прописывает имена

Вы можете скачать output.avi для просмотра результата.

## Чтобы запустить скрипт у себя на компьютере

Для простоты установки необходимых библиотек работаем на Anaconda Prompt:
```
conda create -n face_rec python=3.5.6
conda activate face_rec
conda install -c menpo dlib
conda install -c anaconda cmake
pip install face_recognition
conda install -c menpo opencv3 
```
После этого можно запустить скрипт:
```
python facerec_from_video_file.py 
```
