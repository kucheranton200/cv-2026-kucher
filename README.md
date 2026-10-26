# Компьютерное зрение, 2026

- **Студент:** Кучер Антон Петрович
- **Группа:** Т26КЗ-Т.МО41
- **Вариант данных:** 12

Репозиторий с решениями лабораторных работ курса [«Компьютерное зрение»](https://github.com/ykvnkm/computer-vision-course).

## Работы

| № | Тема | Папка | Статус |
| --: | --- | --- | --- |
| 1 | Среда, репозиторий и первый взгляд на данные | [lab01](lab01/) | в работе |
| 2 | Классическая обработка: фильтры, пороги, контуры | [lab02](lab02/) | не начата |
| 3 | Данные: разметка, дубликаты, разбиение, аугментации | [lab03](lab03/) | не начата |
| 4 | Классификация и перенос обучения | [lab04](lab04/) | не начата |
| 5 | Детекция объектов | [lab05](lab05/) | не начата |
| 6 | Сегментация и промптовые модели | [lab06](lab06/) | не начата |

## Итоговый проект

https://github.com/kucheranton200/sign_language_recognition

## Как запустить

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Данные варианта скачиваются скриптом из репозитория курса:

```bash
git clone https://github.com/ykvnkm/computer-vision-course.git
cd computer-vision-course
python data/get_data.py --variant NN
```

Порядок запуска каждой работы описан в README её папки.