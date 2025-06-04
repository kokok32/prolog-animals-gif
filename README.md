# Prolog Animals GIF Viewer 🐾

Малко уеб приложение, което използва Prolog (Tau-Prolog) за извеждане на животни и показва съответните анимирани GIF изображения.

## Как се използва

1. Въведи Prolog заявка, например:
   animal(X).
2. Ще се покаже първото животно, намерено в базата, с GIF.

## Добавяне на нови животни

1. Добави в `knowledge` секцията:
```prolog
animal(tiger).
Добави в animalAnimations:

tiger: '<img src="https://media.giphy.com/media/tK4jKnfG3Vhza/giphy.gif" class="animal-gif" alt="Tiger" />'
---

## ✅ **3. Качи в GitHub**

```bash
cd prolog-animals-gif
git init
git add .
git commit -m "Първоначална версия на Prolog животни с GIF"
git branch -M main
git remote add origin https://github.com/ТВОЕТО_ПОТРЕБИТЕЛСКО_ИМЕ/prolog-animals-gif.git
git push -u origin main
