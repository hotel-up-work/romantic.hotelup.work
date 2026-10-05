# Romantic Guest House

Live site: https://romantic.hotelup.work

## About
Romantic Guest House — гостьовий дім (`guest_house`) у Кам’янці-Подільському, вул. Руська, 3. Сторінка продає STAY + RELAX + OUTSIDE за формулою STAY · RELAX · TOGETHER; сценарій «Вихідні для двох» (не пакет), сімейні номери показано окремо, щоб бренд не був couples-only.

## Amenities (verified, list.json)
- Приватна ванна кімната, міні-кухня, балкон — лише «у частині номерів» / уточнювати по номеру
- Сімейні номери
- Сауна, SPA-зона, гаряча купіль (hot spring bath) — без термальних/лікувальних тверджень, без масажів і процедур
- Сонячна тераса, зона BBQ (без обіцянок щодо палива/гриля)
- Приватна пляжна зона — лише як outdoor-картка з застереженням і зірочкою; немає в hero, SEO і schema
- Безкоштовний Wi-Fi, безкоштовна парковка на території, рецепція 24/7, екскурсійне бюро, платний трансфер з/до аеропорту
- Заїзд 14:00–00:00, виїзд до 12:00

## Not published
Кондиціонування (є в manuscript, але немає в `amenities_verified`), кількість номерів, місткість, категорії, ціни, харчування, email, сайт, Instagram, види з тераси, розташування «біля Старого міста».

## Contact
- Phone: +380 96 514 56 78 — єдиний підтверджений канал
- Booking.com: https://www.booking.com/hotel/ua/oriental-rooms-with-balcony.html (slug із list.json; варто перевірити, що це саме цей об’єкт)
- Google: https://www.google.com.ua/travel/hotels/entity/ChoIs8Dh-N-Z_53RARoNL2cvMTFmeTU0Z2NtdxAB
- Google Maps: `https://maps.google.com/?cid=15076922139231150131`

## Reviews
Google 4.9/5 (159) і Booking.com 9.6/10 (104) — знімок на 29.09.2026, окремо, без середнього і без aggregateRating.

## Booking flow
Форма «Перевірити проживання» (телефон — обов’язковий, ім’я, гості, дати, побажання) і форма бронювання сауни / гарячої купелі / SPA-зони після секції «Relax» надсилають запити в HotelOS. Поруч — телефон, Booking.com і адреса.

## Forms
HotelOS (`kp-romantic`): `stay-request`, `sauna-request`.

## Photos
Тимчасові стокові фото з Pexels (ліцензія Pexels, атрибуція не обов’язкова), 1440×960 JPG у `images/`. Hero і фінальний банер — реальна Кам’янець-Подільська фортеця (як орієнтир міста); решта — ілюстративні, не фото самого Romantic Guest House. Замінити на власні фото гостьового дому, коли будуть.

| Файл | Pexels ID | Автор |
|---|---|---|
| `hero.jpg` | 39235872 | Tetiana Boriskova |
| `final.jpg` | 34988528 | Valeria Drozdova |
| `sauna.jpg` | 17227605 | Hiroom |
| `spa.jpg` | 6186740 | Tima Miroshnichenko |
| `bath.jpg` | 30302449 | NadiaB |
| `terrace.jpg` | 31993913 | Rescriptt |
| `bbq.jpg` | 29887397 | Rebornfilmes |
| `room.jpg` | 15271518 | Magda Ehlers |
| `family.jpg` | 28054887 | Ahmet Cotur |
| `beach.jpg` | 33067880 | Arlind Photography |

Використані на hero/final (background), у секції «Галерея» (`#gallery`, 7 підписаних кадрів: Сауна, Гаряча купіль, SPA-зона, Тераса, BBQ, Номери, Сімейні номери) та як мініатюри в картках секції "Outside" (Тераса, BBQ, Приватна пляжна зона). Фото пляжної зони — ілюстративне (річковий берег з шезлонгами, не конкретне місце біля Romantic Guest House); картка й надалі не в hero, SEO і schema, з тим самим застереженням-зірочкою.
