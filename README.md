# Patch-diffusion
В папке "diffusion" реализованны две модели патч диффузии при помощи двух классов, Original_AD (классическая модель анизотропной диффузии) и Patch_based_AD (модель патч диффузии).

В каждом классе есть метод anisotropic_diffusion на вход которому передается путь до черно-белого изображения, возвращает метод объект класса Mat из opencv.

Также были добавлены в папку dataset изображения, использованные при написании курсовой работы. Названия изображений соответствуют стандартному отклонению шума AWGN,примененного к изображению (0 - дефолтное изображение).

В тексте курсовой работы присутствуют некоторые примеры работы двух моделей
