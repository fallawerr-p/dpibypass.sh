<div align="center">


# <img src="https://cdn-icons-png.flaticon.com/128/5968/5968756.png" height=28 /> <a href="https://github.com/fallawerr-p/">Fallawerr</a><a href="https://github.com/fallawerr-p/dpibypass.sh">/dpibypass.sh</a> <img src="https://cdn-icons-png.flaticon.com/128/1384/1384060.png" height=28 />

</div>

## ⚙️Использование

1. Включите Secure DNS
    * В Chrome - "Использовать безопасный DNS", и выбрать поставщика услуг DNS (выбрать вариант, отличный от поставщика по умолчанию)
    * В Firefox - "Включить DNS через HTTPS, используя: Максимальную защиту", затем "Выбрать поставщика" и вписать URL поставщика вручную, например можно использовать `https://dns.google/dns-query` (т.к. поставщик Cloudflare может быть заблокирован)
    * В Windows 11 поддерживается включение Secure DNS прямо в настройках ОС - [инструкция тут](https://www.howtogeek.com/765940/how-to-enable-dns-over-https-on-windows-11/). Рекомендуется, если вы пользуетесь Windows 11

2. Скачайте архив (zip/rar) со [страницы последнего релиза](https://github.com/fallawerr-p/dpibypass.sh/releases/latest)

3. Зайдите в свойства скачанного архива и поставьте галочку "Разблокировать". Если вы используете архиватор 7-Zip или PeaZip, этот шаг можно пропустить

4. Распакуйте содержимое архива по пути, который не содержит кириллицу/спец. символы

5. Выполняйте эти команды по очереди:
- chmod +x dpibypass.sh
- sudo ./dpibypass.sh install
- sudo ./dpibypass.sh start
- sudo ./dpibypass.sh test discord.com


### Все проблемы можно создать в issues

* [тут](https://github.com/fallawerr-p/dpibypass.sh/issues)

## 🗒️Добавление адресов прочих ресурсов

Список адресов для обхода можно расширить, добавляя их в:
- **`custom.txt`**

## ⭐Поддержка проекта

Вы можете поддержать проект, поставив :star: этому репозиторию (сверху справа этой страницы)

Также вы можете материально поддержать оригинального разработчика zapret [тут](https://github.com/Flowseal/zapret-discord-youtube)

<a href="https://star-history.com/#Flowseal/zapret-discord-youtube&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=fallawerr-p/dpibypass.sh&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=fallawerr-p/dpibypass.sh&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=fallawerr-p/dpibypass.sh&type=Date" />
 </picture>
</a>

## ⚖️Лицензирование

Проект распространяется на условиях лицензии [MIT]


💖 Отдельная благодарность разработчику [zapret](https://github.com/Flowseal/zapret-discord-youtube) - [Flowseal](https://github.com/Flowseal)
