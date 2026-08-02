<p align="center">
  <img src="media/01-taskbar.png" alt="Lost Vikings walking on the Windows taskbar" width="820">
</p>

<h1 align="center">Taskbar Retrogames Heroes</h1>

<p align="center">
  <strong>Ретро-герои, которые гуляют по вашей панели задач</strong><br>
  <em>Retro game characters that walk on your taskbar / Dock / panel</em>
</p>

<p align="center">
  <a href="#-скачать">Windows</a> ·
  <a href="#-возможности">Features</a> ·
  <a href="#-спрайты-и-лицензия">Free &amp; sprites</a> ·
  <a href="https://t.me/gamebase54">Telegram</a> ·
  <a href="https://github.com/Carter54git">GitHub</a>
</p>

<p align="center">
  <img alt="Free" src="https://img.shields.io/badge/price-FREE-2ea44f?style=for-the-badge">
  <img alt="Platforms" src="https://img.shields.io/badge/Windows-macOS-Linux-1a3328?style=for-the-badge">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-f0c01a?style=for-the-badge">
</p>

---

## ✨ Что это?

Лёгкая desktop-игрушка: пиксельные герои из классических игр **бегают, прыгают и бездельничают** прямо на панели задач Windows (а также на Dock / панели в macOS и Linux).

Никаких установок «в систему», никакой рекламы, никакой платы — **программа распространяется абсолютно бесплатно**.

<p align="center">
  <img src="media/02-settings.png" alt="Settings window with character list" width="480">
</p>

---

## 🚀 Возможности

- **Панель задач как сцена** — герои ходят поверх taskbar / Dock
- **Быстрый спавн** — Sonic Trio, Lost Vikings, Hard Corps, Streets of Rage
- **Редактор персонажей** — вырежи кадры из спрайт-листа, сохрани своего героя
- **Трей / меню** — добавить героя, настройки, despawn all, About
- **Кроссплатформа** — Windows, macOS, Linux

<p align="center">
  <img src="media/03-editor.png" alt="Character Editor cutting frames from a sprite sheet" width="720">
</p>

---

## 📦 Скачать

| Платформа | Файл |
|-----------|------|
| **Windows x64** | [`downloads/TaskbarRetrogamesHeroes-windows-x64.zip`](downloads/TaskbarRetrogamesHeroes-windows-x64.zip) |

1. Распакуй архив  
2. Запусти `TaskbarRetrogamesHeroes.exe`  
3. Иконка появится в трее — оттуда можно добавлять героев  

> macOS / Linux: собирай из исходников (`build_unix.sh` / `run_heroes.sh` в репозитории проекта).

---

## 🎮 Кто уже в сборке

| | Герои |
|---|---|
| **Lost Vikings** | Erik · Baleog · Olaf |
| **Sonic** | Sonic · Tails · Knuckles |
| **Contra** | Ray · Sheena · Fang · Browny · Bill |
| **Streets of Rage** | Axel · Blaze |
| **и другие** | Kirby · Earthworm Jim · Sketch Turner · Mario · Samus |

Сделай своего героя через **Character Editor** — Load sheet / frames / folder.

---

## 🖱 Управление

| Действие | Как |
|----------|-----|
| Прыжок | ЛКМ по герою / Space |
| Разворот | Двойной клик |
| Меню | ПКМ (на Mac — Ctrl+клик) |
| Пауза / charge / switch | Контекстное меню героя |
| Настройки | Клик по иконке в трее |

---

## 🕹 Спрайты и лицензия

### Программа — бесплатно

Приложение **абсолютно бесплатное** (freeware / MIT):

- можно пользоваться без оплаты  
- можно копировать и раздавать друзьям  
- можно собирать из исходников  

См. файл [`LICENSE`](LICENSE).

### Спрайты — из открытых источников

Все встроенные спрайты взяты из **открытых / публичных источников** ретро-сообщества (в том числе архивы вроде [The Spriters Resource](https://www.spriters-resource.com/) и аналогичные).

- Мы **не** претендуем на права на персонажей и арт  
- Игра / издатель / художники остаются владельцами своих работ  
- Проект — некоммерческая фанатская игрушка для рабочего стола  

Подробности — в [`CREDITS.md`](CREDITS.md).

---

## 💬 Связь

- Telegram: [t.me/gamebase54](https://t.me/gamebase54)  
- GitHub: [github.com/Carter54git](https://github.com/Carter54git)  

---

## 🛠 Из исходников (кратко)

```bash
pip install -r requirements.txt
python launcher.py          # Windows / any
# или
./run_heroes.sh             # macOS / Linux
```

Сборка Windows: `build_exe.bat` → `dist/TaskbarRetrogamesHeroes/`  
Сборка Unix: `./build_unix.sh`

Если герои «висят» не на панели: `set HEROES_GROUND_Y=1050` (Y верхнего края панели).

---

<p align="center">
  <sub>Made for fun · Free forever · Retro forever</sub><br>
  <sub>© sprites belong to their original owners · app code MIT</sub>
</p>
