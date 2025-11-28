---
title: Активация Windows/Office
linkTitle: Активация Windows/Office
description: Легко активируем продукты майкрософт
date: 2025-11-26T18:52:29.491Z
authors:
    - name: rivzor
weight: 40
tags:
    - Windows
    - Office
    - Активация
comments: true
lastmod: 2025-11-26T18:52:32.712Z
---

{{< callout type="warning" >}}
Руководство по активации Windows приведено **только для ознакомления** и не является призывом к действию
{{< /callout >}}


Пошаговая инструкция по активации Windows и Office с использованием **Microsoft Activation Scripts (MAS)**. Скрипты позволяют активировать систему и офисные продукты разными методами: HWID, Ohook, TSforge и Online KMS.

---

{{% steps %}}

#### Запуск скрипта

Откройте `Powershell` (Пуск -> `Powershell`).

#### Ввод команды:
  - Windows 11/10/8:

      ```powershell {filename="powershell"}
      irm https://get.activated.win | iex
      ```
  
  - Windows 7:

      ```powershell {filename="powershell"}
      iex ((New-Object Net.WebClient).DownloadString('https://get.activated.win'))

#### Активация

Появится меню активации. Выберите зелёные пункты для активации Windows или Office.
Готово!

{{% /steps %}}

{{< faq title="Если скрипт все равно не запускается" >}}
1. Скачать файл: **[MAS_AIO.cmd](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true)**
2. Запустить `MAS_AIO.cmd`
{{< /faq >}}




