# Changelog

The newest release is first. Everything under the top heading becomes the release notes on
GitHub and the "What's new" section on the landing page, so write it for the person using
the app, not for the person who wrote the commit. From 0.1.1 the notes are published in
Ukrainian and English, so both sections are kept here in step.

## 0.1.4 — 2026-10-06

### Українською

- Нова окрема програма для наглядачів груп — «Звіти групи». У «Звітах за місяць» →
  «Наглядачі груп» секретар створює файл звіту для наглядача групи, наглядач відкриває
  його у «Звітах групи», вносить звіти своєї групи в одній таблиці й зберігає файл для
  секретаря. Секретар імпортує його назад і бачить кожен новий звіт поруч із наявним —
  як у TSWIN — і сам вибирає, що прийняти.
- У файл для наглядача потрапляють лише імена вісників групи, їхнє піонерське служіння і
  вже подані звіти — без адрес, телефонів, дат і приміток. За бажанням файл можна
  захистити паролем; тоді він зашифрований, і звіти повертаються під тим самим паролем.
- Повернутий файл приймає лише та база даних, у якій його створено, і лише для вісників,
  які були в ньому. Звіти за закритий місяць не імпортуються.
- Години звітують лише піонери — але тільки починаючи зі звіту за листопад 2023 року.
  Звіти за давніші місяці зберігають і показують години всіх вісників. Одна година, якою
  TSWIN позначав участь вісника, тепер зараховується як участь, а не як година, і вже
  імпортовані звіти виправлено.
- Зміна статусу записується як подія з датою: перейшов в інший збір, помер, вилучений зі
  збору, відрікся від збору, став неактивним — і шлях назад. Картка S-21 показує, що
  сталося і коли.
- Запис можна стерти назавжди. Ім'я, контакти та примітки видаляються, а підсумки місяців,
  уже надісланих до філіалу, не змінюються.

### English

- A separate new app for group overseers — Group Reports. From Monthly reporting → Group
  overseers the secretary creates a report file for the group overseer; the overseer
  opens it in Group Reports, enters the group's reports in a single table and saves a
  file for the secretary. Imported back, each incoming report is shown beside the one
  already held — the way TSWIN did it — and the secretary picks what to take.
- The overseer's file carries only the group's publishers' names, their pioneer standing
  and the reports already handed in — no addresses, phones, dates or notes. It can be
  protected with a password, which encrypts it, and the reports come back under the same
  password.
- A returned file is accepted only by the database that created it, and only for the
  publishers who were on it. Reports for a closed month are not imported.
- Only pioneers report hours — but only from the November 2023 report on. Earlier months
  keep and show every publisher's hours. The single hour TSWIN used to mark a publisher's
  participation now counts as participation rather than as an hour, and reports already
  imported have been corrected.
- A change of status is recorded as a dated event: moved to another congregation, died,
  removed from the congregation, disassociated, became inactive — and the way back. The
  S-21 card shows what happened and when.
- A record can be erased for good. The name, contacts and notes are removed, while the
  totals of months already sent to the branch stay as they were.

## 0.1.3 — 2026-09-23

### Українською

- Інтерфейс тепер доступний також російською та польською — разом з українською та
  англійською це чотири мови, перемикаються будь-коли в «Налаштуваннях» або на екрані
  розблокування.

### English

- The interface is now also available in Russian and Polish — with Ukrainian and English,
  four languages in total, switchable any time from Settings or the unlock screen.

## 0.1.2 — 2026-09-07

### Українською

- Кнопка «Друк» тепер відкриває передперегляд: справжні сторінки A4 з розривами, як їх
  побачить принтер, з погортанням сторінка за сторінкою. Системний діалог друку
  відкривається вже звідти.
- У передперегляді можна вибрати орієнтацію (книжкову чи альбомну), масштаб від 100 до
  50 % і, для звичайних звітів, чи друкувати назву збору та дату формування. Аркуш
  перемальовується одразу, тож видно, що саме зміниться.
- Там же можна вказати, які сторінки друкувати — один діапазон, як-от `2-4` або `5-`, з
  підрахунком аркушів і кнопкою «Ця сторінка». Нечитабельний діапазон видно в полі, і
  друк не почнеться, доки він не виправлений.
- Три кнопки експорту згорнулися в одну — «Експорт» з переліком PDF, CSV і TSV. Для
  бланка, який таблиці не пише, лишається тільки PDF.
- Параметри звіту зібрані під кнопкою «Параметри» й нарешті мають підписи: «Кого
  друкувати», «Порядок», окремий вісник, група. Раніше це були чотири однакові списки
  поспіль, а на вузькому вікні вони ще й розсовували заголовок сторінки на три рядки.
- Картки S-21 можна впорядкувати за групами, за абеткою або піонерами спершу, а також
  надрукувати картки неактивних вісників.
- Прапорці на офіційних бланках друкуються намальованими квадратами: раніше вони
  залежали від шрифту й подекуди виходили нерівними.
- Після експорту повідомлення про збережений файл можна натиснути, щоб одразу його
  відкрити.

### English

- The Print button now opens a preview: real A4 pages with the breaks the printer will
  make, turned one at a time. The system print dialog follows from there.
- The preview carries the choices that belong to the sheet: orientation, a scale from 100
  down to 50 per cent and, on ordinary reports, whether the congregation's name and the
  date sit under the title. The pages are redrawn at once, so a change is visible before
  it is printed.
- It also takes a page range — one range, such as `2-4` or `5-`, with a count of sheets
  and a button for the page on screen. A range that cannot be read is marked on the field
  and printing waits until it is fixed.
- The three export buttons are now one: Export, offering PDF, CSV and TSV. A form that
  writes no table offers PDF alone.
- A report's parameters are gathered behind a Parameters button and are labelled at last —
  who to print, the order, one publisher, one group. They were four identical lists in a
  row, and on a narrow window they squeezed the page title into three lines.
- S-21 cards can be ordered by group, alphabetically or pioneers first, and cards for
  inactive publishers can be printed.
- Checkboxes on the official forms are drawn as squares rather than typed as characters,
  which depended on the font and came out uneven on some systems.
- After an export, the message naming the saved file can be clicked to open it.

## 0.1.1 — 2026-09-05

### Українською

- Мова інтерфейсу при першому запуску береться з мови системи. Вибрана вручну мова
  заміщує її назавжди.
- У «Налаштуваннях» з'явився розділ з версією програми, адресою сайту, поштою для
  звернень і кнопкою перевірки оновлень. Перевірка звертається до github.com лише тоді,
  коли ви натискаєте кнопку — програма нічого не надсилає сама.
- На сторінці вісника вкладка «Звіти» стала таблицею службового року: дванадцять місяців
  із можливістю виправити звіт просто в рядку. Раніше вона показувала те саме, що й
  «Картка вісника»; картка лишилась без змін.
- У списку груп служіння видно назву групи та її наглядача, а не лише номер і кількість.
- Бічна панель отримала намальовані значки замість текстових символів, частина яких на
  деяких системах показувалась порожніми квадратами.
- У зібраній програмі прибрано меню розробника.

### English

- The interface language follows the system language on a first launch. A language chosen
  by hand overrides it from then on.
- Settings now carries the application version, the website, the support address and a
  check for updates. The check contacts github.com only when the button is pressed — the
  app never reaches out on its own.
- On a publisher's page, the Reports tab is now a service-year table: twelve months, each
  editable in place. It previously showed the same thing as the publisher card, which is
  unchanged.
- The field service group list shows each group's name and overseer, not only its number
  and head count.
- The sidebar has drawn icons in place of text characters, some of which appeared as empty
  boxes on certain systems.
- A packaged build no longer carries a developer menu.

## 0.1.0 — 2026-09-04

First public build.

- Encrypted local database: one SQLCipher file, one passphrase, no account and no network.
- People, field service groups, appointments and relationships, all effective-dated so
  reassigning someone keeps the history.
- Monthly publisher reports and meeting attendance.
- Import from TSWIN: monthly CSV (UTF-8 or Windows-1251) and the XML export, staged and
  previewed before anything is committed.
- 33 reports with CSV, TSV, print and PDF output, including the official S-21 and S-88
  forms.
- Backups and restore, both encrypted with the same key as the live file.
- Ukrainian and English interface.
