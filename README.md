Распознаем рукописную цифру, написанную на листе от руки.

Последовательность шагов:

1. На бумаге рисуем произвольную цифру (желательно нарисовать цифру размером не более 5 * 5 мм и без наклона)
2. Фотографируем
3. Загружаем фото
4. С помощью функции image.load_img(path, target_size=(28, 28), color_mode = ‘grayscale’) загружаем картинку в переменную.
5. С помощью функции image.img_to_array(img) преобразуем изображение в numpy-массив.
6. Выполняем инверсию цветов, нормирование и решейп массива.
7. Выполняем распознавание собственной рукописной цифры.
