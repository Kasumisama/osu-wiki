---
no_native_review: true
outdated_translation: true
outdated_since: 2c9fd01c55a5610c8b047b3bbf8683d414c02987
---

# Как записать реплей в osu!

[Хотите использовать Virtualdub вместо Sony Vegas? Нажмите здесь!](https://osu.ppy.sh/community/forums/posts/252802)

Всегда хотели записать реплей osu! для YouTube, но не придумали, как это сделать? Я объясню в этой теме, как вы можете это сделать. **Обратите внимание, что есть больше способов сделать это, это исключительно мой способ.** [Смотрите результат этого урока здесь (смотреть в HD и полноэкранном режиме!)](https://youtube.com/watch?v=JRGhQh69geI).

## Требования

- Софт для записи
  - [OBS](https://obsproject.com/)
  - [Fraps](https://fraps.com/)
  - [Action!](https://actionrecorder.com/)
  - [Bandicam](https://www.bandicam.com/)
- Софт для редактирования / рендеринга (Никогда не используйте Windows Moviemaker, оно резко портит качество видео!)
  - [Sony Vegas](https://www.vegascreativesoftware.com/us/vegas-pro/)
  - [Adobe Premier](https://www.adobe.com/products/premiere.html)
  - [AVS Video Editor](https://www.avs4you.com/avs-video-editor.aspx)
  - [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve)

### Настройка Fraps

Откройте Fraps и давайте поиграемся с настройками.

![Fraps](img/Recording_1.png "Fraps")

Убедитесь, что:

- Вы установили горячую клавишу для захвата видео, которая не будет мешать;
- Если вы получаете выходное видео с скачущей частотой кадров, то вы ограничили её до 30. Если это не так, просто оставьте 60 кадров в секунду;
- Если вы получаете выходное видео с низкой частотой кадров, вы записываете «половину размера». Видео будет составлять половину оригинального разрешения (альтернативно: вы можете запустить osu! в более низком разрешении при записи);
- На жестком диске осталось достаточно свободного места. Если нет, видео закончится рано, когда больше не останется места для хранения;
- Курсор скрыт на записи
- ВЫ ЗАПИСЫВАЕТЕ ЗВУК! Нет ничего хуже видео по osu! с запаздывающей добавленной музыкой.

## Запись вашего игрового процесса

Откройте osu!, пока на фоне работает Fraps. Если все идет правильно (и если вы не отключили эту функцию), вы увидите желтый счетчик FPS в углу экрана.

![osu! при запущенном Fraps](img/Recording_2.png "osu! при запущенном Fraps")

Теперь перейдите к тому, что вы хотите записать. а именно реплей, в котором вы получаете высокий балл! Когда вы окажетесь в той части, где вы хотите начать запись, нажмите горячую клавишу Захвата видео. Счетчик FPS может упасть и должен стать красным, значит запись началась. Поищите минутку, не меняется ли частота кадров в секунду. Если это так, попробуйте некоторые из этих советов, перечисленных выше.

![osu! при записи Fraps](img/Recording_3.png "osu! при записи Fraps")

Нажмите на горячую клавишу захвата видео еще раз, чтобы остановить запись.

## Редактирование выходного видео

Перетащите видео на временную шкалу в Sony Vegas. Если файлов несколько, Vegas автоматически добавит их в конец предыдущей части.

![Редактирование видеоклипа](img/Recording_4.png "Редактирование видеоклипа")

Теперь вы можете сделать некоторые дополнительные изменения.

## Рендеринг вашего видео

Теперь, когда вы закончили редактирование видео, перейдите в раздел `Файл` и нажмите кнопку `Отрендерить как`. Используйте следующие опции (в зависимости от вашей версии Vegas):

![Рендеринг видеоклипа](img/Recording_5.png "Рендеринг видеоклипа")

![Рендеринг видеоклипа](img/Recording_6.png "Рендеринг видеоклипа")

Нажмите кнопку `Сохранить`, и ваше видео будет готово через пару минут. Теперь оно готово для выкладывания на YouTube! Обратите внимание, что пройдет некоторое время, прежде чем видео будет доступно в высоком разрешении на YouTube, так что наберитесь терпения!

**А теперь иди снимай видео и распространяй osu!.** Руководство сделано [Remco32](https://osu.ppy.sh/users/9199), оригинальный тред [здесь](https://osu.ppy.sh/community/forums/topics/18112)
