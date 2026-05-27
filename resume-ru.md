# Сергей Криницын

**AI Product Engineer · Full-stack (React + Python) · LLM Pipelines**

Nha Trang, Vietnam · Готов к релокации (Сербия, Армения, ОАЭ, EU)
Email: sergeykrin98@gmail.com · GitHub: [github.com/SergeyKrin9](https://github.com/SergeyKrin9)
Часовой пояс: UTC+7 (гибко: МСК ± 4ч)

---

## О себе

End-to-end продуктовый инженер: от LLM-пайплайна и FastAPI-бэкенда до продакшн-деплоя и SEO-автоматизации. За последний год запустил **10+ продуктов** в нишах PropTech, AI-контент, маркетинг-автоматизация и Telegram-боты с платежами.

Сильная сторона — связка **AI + современный фронт + бэкенд на Python/Node + автоматизация маркетинга**. Беру задачу от "нужна фича" до отгрузки в продакшн без передачи между ролями: дизайн → фронт → бэк → AI-логика → SEO/Direct/Метрика.

---

## Технологии

**AI / LLM**
OpenAI, Anthropic Claude, NVIDIA NIM (Llama), Google Gemini, prompt-engineering, cascade fallbacks с cost-оптимизацией, RAG-паттерны, structured outputs

**Frontend**
React 18, Vite, TypeScript, Tailwind CSS, Framer Motion, Three.js / R3F, React Router 7, lazy-loading, PWA, SEO-prerender

**Backend**
Node.js 20, Firebase (Firestore, Cloud Functions, Auth, Storage, Hosting), security rules, REST/Webhook APIs, Google Sign-In, custom claims

**Python (бэкенд + автоматизация)**
Python 3, **FastAPI, SQLAlchemy, APScheduler**, Flask, ffmpeg, PIL/Pillow, BeautifulSoup, requests, Firebase Admin SDK, SQLite, systemd-сервисы, cron-пайплайны, платежи через Telegram Stars

**Marketing Engineering**
Yandex.Direct API, Yandex.Metrika, Google Search Console, n8n, Telegram Bot API, VK API, YouTube Data API v3, SEO-автоматизация

**DevOps / Tools**
Git, GitHub, Firebase CLI, Ubuntu/systemd, Playwright (E2E), Vitest, MCP-серверы для AI-агентов

---

## Избранные проекты

### eDaru.su · Production маркетинг-платформа с полным циклом growth
Лендинг + бэкенд + бот + воркеры. Полная маркетинг-машина для курьерского сервиса (партнёрка Яндекс.Еды): SEO-страницы с автогенерацией контента через Gemini, управление кампаниями в Яндекс.Директ через API, аналитика через Яндекс.Метрику, автопостинг в Telegram + VK, сбор лидов через бот. Семь интеграций через MCP-серверы собственной разработки.

**Стек:** React 18 + Vite, Firebase Cloud Functions, Gemini API, Яндекс.Директ API, Яндекс.Метрика API, Google Search Console, VK API, Telegram Bot API, Yandex Webmaster, YouTube Data API
**Что закрыл:** объединил роль маркетолога, контент-менеджера и SEO-специалиста в один автоматический пайплайн
**Роль:** solo full-stack + growth engineering

### Broker Reels Studio · AI-видео из текста для маркетинга недвижимости
Python-пайплайн, который из карточки объекта генерирует короткое видео в стиле TikTok/Reels: LLM пишет сценарий → подбираются изображения → ffmpeg собирает видео с Ken Burns, плавной анимацией текста и музыкой → результат публикуется в Telegram-канал брокера. HTTP-сервер на Flask + Cloud Function для триггера из кабинета.

**Стек:** Python, ffmpeg, PIL, Flask, OpenAI/Anthropic API, Firebase Functions, Telegram Bot API
**Что закрыл:** ручной труд маркетолога/SMM в риелторских агентствах
**Роль:** идея, архитектура, реализация, деплой

### AxonLeads · Production SaaS для девелоперов недвижимости
Платформа для девелоперских компаний: загрузка проектов, шахматка юнитов с расчётом ROI, генерация PDF-презентаций, мультиролевая авторизация (superadmin / developer / broker / client). Веб-приложение + investor-portal с unlock-логикой и AI-парсингом прайс-листов.

**Стек:** React 18, Vite, Tailwind, Firestore (сложные subcollections), Cloud Functions, Firebase Auth + custom claims, jsPDF, pdfjs-dist
**Объём:** ~127K строк кода, продакшн
**Роль:** solo full-stack — от схемы данных до UI

### daily-poster · Автономный AI-генератор контента
Демон, который раз в сутки сам выбирает тему, генерирует пост через NVIDIA Llama, делает иллюстрацию через Gemini Image, собирает финальную карточку в PIL и публикует в Telegram-канал и группу ВКонтакте. Cost-optimized cascade: дёшевые модели для скоринга, дорогие — только для финальной генерации.

**Стек:** Python, NVIDIA NIM, Gemini API, FFmpeg, Firebase Admin SDK, systemd timer, Telegram/VK API
**Roi:** заменил ручной SMM на автопилот без потери качества контента
**Роль:** идея, реализация, прод-эксплуатация на Ubuntu-сервере

### BrokerOS · Multi-role CRM для real estate
CRM-кабинет с тремя ролями (агент / брокер / админ): лиды, объекты, комнаты-демо для клиентов, аналитика конверсии, AI-помощник для подбора объектов под запрос клиента. Security rules с tenant isolation, real-time подписки через onSnapshot.

**Стек:** React, Firestore security rules, Cloud Functions, onSnapshot, custom claims
**Роль:** архитектура данных + фронт + AI-интеграции

### ClientRoom · TikTok-style витрина объектов
Mobile-first витрина с vertical-feed (как в Reels), Framer Motion анимациями, lazy-load чанков, аналитикой просмотров и shared-link для брокеров. Производительность: prerender, code-splitting, оптимизация изображений.

**Стек:** React, Framer Motion, Vite chunks splitting, dynamic imports
**Роль:** UX-дизайн + реализация

### EnergyBot · Production Telegram-бот с GPT-4 и платежами
Платный Telegram-бот для консультаций. **FastAPI** + SQLAlchemy + SQLite, диалоги с OpenAI GPT-4o-mini с кэшированием, платежи через Telegram Stars, APScheduler для рассылок и плановых публикаций, админ-CRM-бот для управления (статистика, broadcasts, портфолио). MCP-сервер для Telegram-публикаций.

**Стек:** Python, FastAPI, SQLAlchemy, OpenAI API, APScheduler, python-telegram-bot, SQLite, MCP
**Роль:** архитектура бэкенда, бот-логика, платежи, админ-интерфейс

### Agnis Portal · B2B портал с AI и Telegram Mini Apps
Портал для записи на консультации + AI-помощник на Gemini + финансовые чарты + CMS через Sanity + интеграция с Telegram через SDK. Netlify Functions как бэкенд, реал-тайм данные, framer-motion.

**Стек:** React 19, Vite, Telegram Web App SDK, Google Generative AI (Gemini), Sanity CMS, Netlify Functions, Chart.js
**Роль:** full-stack + AI-интеграции

---

## Дополнительно

- **7+ MCP-серверов** собственной разработки для интеграции AI-агентов с инфраструктурой: Click.ru (Telegram Ads, VK Ads, Я.Директ), Яндекс.Директ (campaigns, bids), Я.Вебмастер, Google Search Console, YouTube Data API, VK API, кастомный Telegram-publisher. Это закрывает весь маркетинговый стек для агентских воркфлоу.
- **Финансовая автоматизация:** интеграция с API банка Точка, парсинг выписок, PnL-отчётность, трекинг карт Bybit
- **Скрейпинг-пайплайны** (FazWaz, DotProperty, Bayut, YouTube, VK): Python + BS4 + rate limiting + дедупликация + запись в Firestore + systemd
- **Дизайн-система** "warm precision luxury" собственной разработки: токены, типографика (Cinzel + Josefin Sans), Liquid Glass surfaces, единый визуальный язык across 5+ продуктов
- **Игровые эксперименты** (Phaser, Three.js): GTA-style courier mini-game — для отдыха и прокачки performance/canvas skills

---

## Языки

- **Русский** — родной
- **Английский** — Intermediate (B1-B2), активно прокачиваю до B2+

---

## Что ищу

Удалённая работа в найм (штат / ГПХ / контракт через EOR) в часовом поясе UTC-2 .. UTC+5. Открыт к релокации в Сербию, Армению, ОАЭ или ЕС.

**Желаемые роли:** AI Product Engineer · AI Solutions Engineer · Senior Full-stack (React + Python + LLM) · Marketing/Growth Engineer с AI-фокусом · Product Engineer в PropTech-стартапе.
