# BypassX

Обход блокировок для Windows в один тумблер: автоподбор стратегии, Cloudflare WARP,
блокировка рекламы и прокси для Telegram.

**[Скачать последнюю версию →](https://github.com/GhostResident/BypassX/releases/latest)**
(файл `BypassX_…_x64-setup.exe`)

Одно переключение — и заблокированные сайты открываются. Программа сама подберёт
подходящую стратегию, а новые версии будет предлагать установить сама.

## Установка

1. Скачайте `*-setup.exe` со страницы [Releases](https://github.com/GhostResident/BypassX/releases/latest) и запустите.
2. Нужны права администратора — перехват пакетов работает через драйвер.
3. Антивирус может ругнуться на драйвер перехвата пакетов: это известное ложное
   срабатывание, оно касается всех программ на базе zapret.

Дальше программа обновляется сама: когда выходит новая версия, на главном экране
появляется баннер. Каждое обновление подписано — программа не установит файл, у
которого подпись не совпадает.

## О репозитории

Этот репозиторий содержит только релизы. Исходный код закрыт.

Нашли ошибку или есть вопрос — [создайте issue](https://github.com/GhostResident/BypassX/issues).

---

*BypassX использует [zapret](https://github.com/bol-van/zapret) и
[zapret-discord-youtube](https://github.com/Flowseal/zapret-discord-youtube),
[TG WS Proxy](https://github.com/Flowseal/tg-ws-proxy), WinDivert и Cloudflare WARP —
у каждого проекта своя лицензия.*
