# WEB-work-schedule-checker

## English

### 📜 Description
Schedule 4/4 is a tiny static website that tells you whether a person (@dukui_yurii) is working today or has a day off. It is built for a 4 on / 4 off rotation: four working days, then four days off, repeating forever. No more asking "are you free today?" – just open the page.

### 🎮 Features

* **Instant Status** – A big "Working day" / "Day off" label for today, plus info on when the current block ends.
* **Monthly Calendar** – Working days are highlighted in yellow, days off in green, today has an outline.
* **Month Navigation** – Flip through months with the arrow buttons to look ahead (or back).
* **Upcoming Blocks** – A list of the next work and rest periods with exact dates.
* **Configurable Start Date** – Set the first day of any working block with a date picker; it is saved in the browser's local storage.
* **Shareable Link** – Pass the start date in the URL, e.g. `?start=2026-10-09`.
* **Responsive Design** – Looks good on both phones and desktops.
* **Dark Theme** – Switches automatically based on your system settings.

### 📜 Usage

* **Previous / Next Month** – `‹` and `›` buttons above the calendar
* **Change Schedule Start** – Date field at the bottom of the page
* **Share a Specific Schedule** – Add `?start=YYYY-MM-DD` to the URL
* **Permanent Default Date** – Edit the `DEFAULT_START` constant in `index.html`

### ⚙️ How It Works
The number of days between the start date and the selected day is divided by 8. A remainder of 0–3 means a working day, 4–7 means a day off. Dates are compared in UTC, so daylight saving time changes don't break anything.

### 🛠️ Installation
No installation required! Simply open the `index.html` file in your browser. You can also use the site directly on GitHub Pages: [https://orangep1llow.github.io/WEB-work-schedule-checker/]

### 📧 Credits

* Created special for: @dukui_yurii
* Developer: StanisLove
* Vibe-coded with: Claude (Anthropic) – yes, an AI wrote most of it, and we're not hiding it 😄

---

## Українська

### 📜 Опис
Графік 4/4 – це маленький статичний сайт, який показує, працює людина (@dukui_yurii) сьогодні чи має вихідний. Він розрахований на графік 4/4: чотири робочі дні, потім чотири вихідні, і так по колу. Більше не треба питати «ти сьогодні вільний?» – достатньо відкрити сторінку.

### 🎮 Функції

* **Миттєвий статус** – Великий напис «Робочий день» / «Вихідний» на сьогодні та інформація про те, коли закінчується поточний блок.
* **Календар на місяць** – Робочі дні підсвічені жовтим, вихідні зеленим, сьогоднішній день виділено рамкою.
* **Перемикання місяців** – Гортайте місяці стрілками, щоб дивитися наперед (або назад).
* **Найближчі блоки** – Список наступних періодів роботи та відпочинку з точними датами.
* **Налаштовувана дата початку** – Оберіть перший день будь-якого робочого блоку через вибір дати; значення зберігається в локальному сховищі браузера.
* **Посилання з налаштуванням** – Передайте дату початку в URL, наприклад `?start=2026-10-09`.
* **Адаптивний дизайн** – Гарно виглядає і на телефонах, і на десктопах.
* **Темна тема** – Вмикається автоматично залежно від системних налаштувань.

### 📜 Використання

* **Попередній / наступний місяць** – Кнопки `‹` та `›` над календарем
* **Змінити початок графіка** – Поле з датою внизу сторінки
* **Поділитися конкретним графіком** – Додайте `?start=YYYY-MM-DD` до посилання
* **Постійна дата за замовчуванням** – Змініть константу `DEFAULT_START` в `index.html`

### ⚙️ Як це працює
Кількість днів між датою початку та обраним днем ділиться на 8. Залишок 0–3 означає робочий день, 4–7 – вихідний. Дати порівнюються в UTC, тому перехід на літній/зимовий час нічого не ламає.

### 🛠️ Встановлення
Жодного встановлення не потрібно! Просто відкрийте файл `index.html` у своєму браузері. Ви також можете користуватися сайтом безпосередньо на GitHub Pages: [https://orangep1llow.github.io/WEB-work-schedule-checker/]

### 📧 Автори

* Створено спеціально для: @dukui_yurii
* Розробник: StanisLove
* Навайбкоджено разом з: Claude (Anthropic) – так, більшість коду написав ШІ, і ми цього не приховуємо 😄