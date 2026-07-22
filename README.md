<!-- Animated Wave Header - Claude Terracotta/Dark Theme -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a1a,50:C15F3C,100:1a1a1a&height=180&section=header&text=ClaudeMeter&fontSize=55&fontColor=F4F3EE&animation=fadeIn&fontAlignY=35&desc=By%20VexCrux&descSize=16&descAlignY=55&descColor=B1ADA1" alt="Header">

  <!-- Language Switcher - Rounded -->
  <p align="center">
    <img src="https://img.shields.io/badge/🇷🇺_Русский-Active-2ea44f?style=plastic&logo=googletranslate&logoColor=white" alt="Russian">
    <img src="https://img.shields.io/badge/🇬🇧_English-Available-6e7681?style=plastic&logo=googletranslate&logoColor=white" alt="English">
  </p>

  <!-- Browser Badges - Plastic Rounded -->
  <p align="center">
    <img src="https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white&style=plastic" alt="Chrome">
    <img src="https://img.shields.io/badge/Edge-Extension-0078D7?logo=microsoftedge&logoColor=white&style=plastic" alt="Edge">
    <img src="https://img.shields.io/badge/Brave-Extension-FB542B?logo=brave&logoColor=white&style=plastic" alt="Brave">
    <img src="https://img.shields.io/badge/Version-0.0.1-C15F3C?style=plastic" alt="Version">
  </p>

  <!-- Description -->
  <p align="center"><b>Real-Time Token Tracker for Claude AI</b></p>
  <p align="center"><i>Отслеживание токенов Claude AI в реальном времени</i></p>

  <!-- Quick Stats - Rounded -->
  <p align="center">
    <img src="https://img.shields.io/badge/⭐_Stars-0-ffd700?style=plastic" alt="Stars">
    <img src="https://img.shields.io/badge/🍴_Forks-0-ff6b6b?style=plastic" alt="Forks">
    <img src="https://img.shields.io/badge/📥_Downloads-0-4ecdc4?style=plastic" alt="Downloads">
  </p>

  <!-- Quick Navigation -->
  <p align="center">
    <a href="#-features--возможности">✨ Features</a> •
    <a href="#-installation--установка">🚀 Install</a> •
    <a href="#-project-structure--структура-проекта">📁 Structure</a> •
    <a href="#-settings--настройки">⚙️ Settings</a> •
    <a href="#-security-notes--примечания-по-безопасности">🛡️ Security</a>
  </p>

</div>

---

## ⚠️ Disclaimer / Предупреждение

> [!WARNING]
> **EN:** This extension is built **exclusively** for tracking Claude AI token usage and subscription periods. **Always use official builds from this repository.**
>
> **RU:** Расширение создано **исключительно** для отслеживания использования токенов Claude AI и сроков подписки. **Используйте только официальные сборки из этого репозитория.**

---

## 🔒 Full Control & Customization / Полный контроль

> [!IMPORTANT]
> **EN:** You decide how tracking works: **one-click toggle** to disable, **per-site exceptions** for trusted domains, and **granular controls** for token display, period alerts, and UI customization.
>
> **RU:** Вы сами решаете, как работает отслеживание: **полное отключение в один клик**, **исключения для сайтов** и **точечная настройка** отображения токенов, уведомлений о сроках и кастомизации интерфейса.

---

## ✨ Features / Возможности

| # | 🏷️ Feature (EN) | 🏷️ Возможность (RU) | 📋 Description |
|---|------------------|----------------------|---------------|
| 1 | **Master Toggle** | **Главный выключатель** | Instantly enable/disable the entire extension. / Мгновенное включение или отключение расширения. |
| 2 | **Site Exceptions** | **Исключения для сайтов** | Disable for specific pages or domains. / Отключение для конкретных страниц или доменов. |
| 3 | **Token Monitor** | **Мониторинг токенов** | Real-time stats: tokens used, tokens remaining, usage percentage, reset timer. / Статистика в реальном времени: использовано токенов, осталось, процент использования, таймер сброса. |
| 4 | **Period Tracker** | **Отслеживание периода** | Track subscription period: start date, end date, days remaining. / Отслеживание периода подписки: дата начала, дата окончания, дней осталось. |
| 5 | **Usage Alerts** | **Уведомления об использовании** | Get warned when tokens are running low or period is ending. / Предупреждения при заканчивающихся токенах или сроке подписки. |
| 6 | **Model Detection** | **Определение модели** | Auto-detect Claude model (Sonnet 5, Opus, etc.) and show model-specific limits. / Автоопределение модели Claude и отображение лимитов для каждой модели. |
| 7 | **Dark Mode UI** | **Тёмный режим интерфейса** | Beautiful dark theme matching Claude.ai design. / Красивый тёмный интерфейс в стиле Claude.ai. |
| 8 | **Lightweight** | **Оптимизация** | Zero bloat. Built for speed and stability. / Лёгкая архитектура без нагрузки на браузер. |

---

## 🚀 Installation / Установка

| Step | 📝 Action (EN) | 📝 Действие (RU) |
|------|---------------|------------------|
| **1** | Click **Code** → **Download ZIP** | Нажмите **Code** → **Download ZIP** |
| **2** | Extract ZIP to a dedicated folder | Распакуйте архив в отдельную папку |
| **3** | Open browser → `chrome://extensions/` | Откройте браузер → `chrome://extensions/` |
| **4** | Enable **Developer mode** (top-right toggle) | Включите **Режим разработчика** (переключатель справа вверху) |
| **5** | Click **Load unpacked** → select project folder | Нажмите **Загрузить распакованное** → выберите папку проекта |

> 💡 **EN:** Pin the extension icon to your toolbar for instant access.  
> 💡 **RU:** Закрепите иконку расширения на панели инструментов для быстрого доступа.

---

## 📁 Project Structure / Структура проекта

```text
📁 claudemeter/
├── 📁 assets/            # UI styles / Стили интерфейса
├── 📁 icons/             # Extension icons / Иконки расширения
├── 📄 background.js      # Background service worker / Фоновый скрипт
├── 📄 content-loader.js  # Script injection loader / Загрузчик скриптов
├── 📄 inject.js          # Injected content script / Инжектируемый скрипт
├── 📄 manifest.json      # Extension manifest / Манифест расширения
├── 📄 popup.html         # Popup UI markup / Интерфейс меню
└── 📄 popup.js           # Popup logic / Логика меню
```

---

## 🖼️ Interface Preview / Скриншоты интерфейса

<details>
<summary><b>📸 Click to expand / Нажмите, чтобы развернуть</b></summary>

<br>

**Main Panel — Token usage & period tracking / Главная панель — использование токенов и отслеживание периода:**

![Main Panel](assets/screenshot-main.png)

**Settings — Toggles, alerts, model selection / Настройки — переключатели, уведомления, выбор модели:**

![Settings](assets/screenshot-settings.png)

</details>

---

## ⚙️ Settings / Настройки

| 🔧 Section / Раздел | 🔧 Option / Опция | 📋 Description / Описание |
|---------------------|-------------------|---------------------------|
| **Token Display** / **Отображение токенов** | Show Token Bar / Показывать панель токенов | Toggle token usage bar below chat input. / Включение/отключение панели токенов под полем ввода чата. |
| | Show Percentage / Показывать процент | Display usage as percentage instead of raw numbers. / Отображение использования в процентах вместо чисел. |
| | Show Reset Timer / Показывать таймер сброса | Display countdown to next token reset. / Отображение обратного отсчёта до следующего сброса токенов. |
| **Period Tracking** / **Отслеживание периода** | Show Period Info / Показывать информацию о периоде | Display subscription period below chat input. / Отображение периода подписки под полем ввода чата. |
| | Alert Before End / Предупреждать перед окончанием | Notify N days before period ends. / Уведомление за N дней до окончания периода. |
| **Alerts** / **Уведомления** | Low Token Warning / Предупреждение о низких токенах | Warn when tokens below threshold. / Предупреждение при токенах ниже порога. |
| | Sound Alerts / Звуковые уведомления | Play sound on alert. / Воспроизведение звука при уведомлении. |
| **Model** / **Модель** | Auto-Detect / Автоопределение | Automatically detect Claude model from page. / Автоматическое определение модели Claude со страницы. |
| | Manual Select / Ручной выбор | Force specific model: `Sonnet 5`, `Opus 4.7`, `Haiku`. / Принудительный выбор модели: `Sonnet 5`, `Opus 4.7`, `Haiku`. |
| **Appearance** / **Внешний вид** | Dark Mode / Тёмный режим | Toggle dark/light theme. / Переключение тёмной/светлой темы. |
| | Compact Mode / Компактный режим | Minimize UI to save space. / Минимизация интерфейса для экономии места. |

> 📝 **EN:** Token limits vary by model and subscription tier. ClaudeMeter reads usage data from the Claude.ai interface and does not make external API calls.  
> 📝 **RU:** Лимиты токенов зависят от модели и уровня подписки. ClaudeMeter считывает данные об использовании из интерфейса Claude.ai и не делает внешних API-запросов.

---

## 🛡️ Security Notes / Примечания по безопасности

| 🔒 Feature / Функция | 🎯 Why It Matters / Зачем это нужно |
|----------------------|--------------------------------------|
| Local Data Only | All token data is read from the page DOM — no external API calls, no data leaks. / Все данные о токенах считываются из DOM страницы — никаких внешних API-запросов, никаких утечек данных. |
| No Credentials Stored | ClaudeMeter never stores your API keys or login credentials. / ClaudeMeter никогда не хранит ваши API-ключи или учётные данные. |
| Per-Site Control | Enable/disable tracking per domain to avoid conflicts. / Включение/отключение отслеживания для каждого домена для избежания конфликтов. |
| Privacy First | No analytics, no tracking, no telemetry — your data stays yours. / Никакой аналитики, отслеживания или телеметрии — ваши данные остаются вашими. |

---

<div align="center">

  <!-- Animated Wave Footer - Claude Terracotta/Dark Theme -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:C15F3C,50:1a1a1a,100:C15F3C&height=120&section=footer" alt="Footer">

  <p><b>Built for Claude users, by a Claude user. / Создано для пользователей Claude, пользователем Claude.</b></p>
  <p><b>Track smarter. Chat longer. / Отслеживай умнее. Общайся дольше.</b></p>
  <p>
    <sub>⭐ Star this repo if ClaudeMeter helps you stay in control! / Поставьте ⭐, если ClaudeMeter помогает вам держать всё под контролем!</sub>
  </p>

</div>
