# Seamless Banking

Прототип бесшовного перехода между веб- и мобильным банковским приложением.
Магистерская диссертация, Московский политехнический университет, 09.04.02.

## Демо-интерфейс банка

https://mospoliteh2627-alt.github.io/guvanchsha/

Статическая демонстрация: дашборд, перевод, QR-переход, timeline, история. Без backend — данные локальные.

## Ссылки

- Project-доска: https://github.com/users/mospoliteh2627-alt/projects/1
- Исходный код: https://github.com/mospoliteh2627-alt/seamless-banking (public)
- Релиз APK/IPA: https://github.com/mospoliteh2627-alt/seamless-banking/releases/tag/v1.0.0
- Документация сборки: https://github.com/mospoliteh2627-alt/seamless-banking/blob/main/docs/NATIVE_BUILD.md

## Что внутри

- Fastify 5 + Redis/in-memory: handoff, lease, RBAC, аудит, идемпотентность.
- PWA: QR-переход, timeline, получатели, админка, research.
- Flutter: web/mobile, Face ID/PIN sheet, процесс/SLA.
- Android APK и iOS unsigned IPA.
- 3 Node E2E, 2 Flutter-теста, Playwright UI flow.

## Статус

Android собран и проверен; iOS собран без подписи. Полевого SUS/CES пока нет.
