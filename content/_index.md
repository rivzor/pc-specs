---
description: "Персональный сайт: контактная информация, PC specs, гайды и проекты."
toc: false


---

<!-- Заголовок -->
{{< hextra/hero-headline >}}
  rivzor
  <br class="max-sm:hidden" />
  <span class="font-light text-4xl">- создаю простое и красивое</span>
{{< /hextra/hero-headline >}}

{{< hextra/hero-subtitle >}}
  Работаю с инфраструктурой, автоматизацией CI/CD
  <br class="max-sm:hidden" />
  и оптимизацией delivery-процессов.
{{< /hextra/hero-subtitle >}}

<!-- Навыки -->
{{< skills-container align="left" >}}

  {{< skill color="#0ea5e9" >}}Python{{< /skill >}}
  
  {{< skill color="#2563eb" >}}C++{{< /skill >}}
  
  {{< skill color="#eab308" >}}JavaScript{{< /skill >}}
  
  {{< skill color="#00add8" >}}Golang{{< /skill >}}
  
  {{< skill color="#ef4444" >}}Git{{< /skill >}}

{{< /skills-container >}}

<!-- Контакты -->
<h3 class="text-center text-2xl font-bold mt-12 mb-6">Мои контакты</h3>

{{< cards >}}
  {{< card link="https://t.me/rivzor" title="Telegram" icon="telegram" >}}
  {{< card link="https://github.com/rivzor" title="Github" icon="github" >}}
  {{< card link="https://steamcommunity.com/id/rivzorx/" title="Steam" icon="steam" >}}
  {{< card link="https://discordapp.com/users/346701837736476687" title="Discord" icon="discord" >}}
  {{< card link="mailto:i@rivzor.ru" title="Email" icon="mail" >}}
{{< /cards >}}

<!-- Разделитель -->
<div class="my-16 border-t border-neutral-200 dark:border-neutral-800"></div>
    
<!-- Раздел с моей сборкой -->
<div id="pc-specs" style="text-align: center; margin: 3rem 0 2rem; scroll-margin-top: 6rem;">
  <span style="font-size: 2.2rem; font-weight: 800; color: var(--primary);">
    Моя сборка
  </span>
</div>

{{< hextra/feature-grid cols="2" >}}

    {{< 
    hextra/feature-card 
    title="Основные компоненты" 
    subtitle="**ОС:** Windows 11 Pro<br>**Материнская плата:** MSI A520M-A Pro<br>**Процессор:** AMD Ryzen 5 5600 (6 ядер, 12 потоков, 3.5–4.4 ГГц)<br>**ОЗУ:** 32 ГБ DDR4 3600 МГц<br>**Видеокарта:** NVIDIA RTX 3060 Ti (8 ГБ)" 
    >}}
    
    {{< 
    hextra/feature-card 
    title="Хранилище" 
    subtitle="SSD NVMe 1 ТБ — DEXP<br>SSD 240 ГБ — SATA<br>HDD 1 ТБ — Seagate<br>HDD 1 ТБ — WD" 
    >}}

{{< /hextra/feature-grid >}}

<div style="padding-top:1rem"></div>

<div class="mt-6">
  {{< hextra/feature-card 
    title="Периферия" 
    subtitle="**Монитор:** MSI Optix G241 (IPS, 144Hz)<br>**Клавиатура:** Ajazz AK820 Pro (Gasket mount)<br>**Мышь:** VGN F1 MOBA (PAW3395, 55g)<br>**Звук:** Dark Project HS5" 
  >}}
</div>




<!-- Разделитель -->
<div id="faq" style="text-align: left; margin: 4rem 0 2rem;">
<span style="font-size: 1.6rem; font-weight: 800; color: var(--primary);">Частые вопросы</span>
</div>


{{< faq title="Почему ты выбрал Ryzen 5600?" >}}
В 2023 году это был **лучший** процессор по соотношению цена/производительность. 
Он холодный, легко берет разгон до `4.6 ГГц` и отлично работает с памятью 3600 МГц.<br>По прежнему считаю его отличным решением в своей ценовой категории.
{{< /faq >}}

{{< faq title="Какой софт используешь для деплоя?" >}}
В основном это связка:
1. **Docker** для контейнеризации.
2. **GitHub Actions** для CI/CD пайплайнов.
{{< /faq >}}

{{< faq title="Как организуешь свои задачи?" >}}
Для каждого проекта создаю небольшой {{< tip "Сервис для управления задачами и составления списков дел.">}}**Todoist**{{< /tip >}} и следую ему, попутно добавляя новые задачи
{{< /faq >}}

{{< faq title="Твоя любимая игра всех времен?" >}}
Безусловно {{< tip "Компьютерная игра в жанре action/RPG, разработанная и изданная польской студией CD Projekt RED" >}}Witcher 3{{< /tip >}}
{{< /faq >}}

{{< faq title="C++: Указатели vs Ссылки?" >}}
Указатели
{{< /faq >}}

{{< faq title="Нужен ли сторонний антивирус?" >}}
Windows Defender + голова на плечах = достаточно.
{{< /faq >}}

<!-- Недавние статьи -->
{{< latest-posts section="docs" >}}

<!-- Разделитель -->
<div id="roadmap" style="text-align: left; margin: 4rem 0 0;">
<span style="font-size: 1.6rem; font-weight: 800; color: var(--primary);">Дорожная карта</span>
</div>

Здесь я отмечаю прогресс по сайту, своим проектам и изучению технологий.

{{< roadmap >}}

  {{< roadmap-item status="active" date="Ноябрь 2025" title="Рефакторинг сайта" tag="Текущая задача" >}}
  Полное обновление дизайна.
  - [x] Переход на Hextra
  - [x] Поднятие домена `rivzor.space`
  - [x] Стеклянный дизайн (Glassmorphism)
  - [x] Добавление темной темы для графиков
  - [ ] Создание раздела `Вики` внутри этого сайта
  {{< /roadmap-item >}}

  {{< roadmap-item status="done" date="Ноябрь 2025" title="Разработка и запуск Ri-Wiki" tag="Выполнено" >}}
  Первая публичная версия сайта. Написаны базовые гайды и созданы несколько разделов. Миграция на {{< tip "Кастомная тема для Material for MkDocs">}}Zensical{{< /tip >}}
  {{< /roadmap-item >}}

  {{< roadmap-item status="planned" date="Декабрь 2025" title="Создание своей утилиты" tag="В планах" >}}
  Планирую разработать утилиту {{< tip "Универсальный софт для оптимизации Windows">}}Ri-WinTweaks{{< /tip >}} для оптимизации Windows в пару кликов. Либо с нуля, либо форк уже существующего проекта.
  {{< /roadmap-item >}}

  {{< roadmap-item status="planned" date="В далеком будущем" title="YouTube Канал" tag="В планах" >}}
  Возможно, начну снимать видео-гайды по сборкам.
  {{< /roadmap-item >}}

{{< /roadmap >}}



