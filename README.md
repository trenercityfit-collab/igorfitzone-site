
# IgorFitZone v3.0+ (Netlify Ready)

Сайт тренера с админкой (Decap CMS), PayPal, бронированием и бэкапами.

## Запуск
1) Netlify → New site from Git → GitHub → выбрать `igorfitzone-site`.
2) Settings → Identity → Enable, затем Git Gateway.
3) Domain settings → добавить `igorfitzone.com` (DNS у регистратора).
4) Откройте `/admin` и войдите через GitHub.

## Бэкапы
- Ручной снапшот: кнопка в `/admin` (Make-сценарий должен сделать commit).
- Авто: `.github/workflows/backup.yml` — еженедельно.

## Восстановление
GitHub → Commits → Revert.

## Перенос на Hostinger
Netlify → Deploys → Download deploy as ZIP → загрузить в `public_html`.

## Интеграции
- GA4: G-KJNZSMGH2D
- PayPal: включён в кнопках оплаты
- Make Webhook: настроен в формах/оплатах/отзывах
