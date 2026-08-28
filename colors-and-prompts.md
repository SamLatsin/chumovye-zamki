# 🎨 Цветовые схемы и промты

Справочник по оформлению карт: палитры домов, шрифты и промты для генерации/очистки артов.

---

## Общий стиль

| Элемент | Значение |
|---|---|
| Обводка (шрифт) | `#15140F` (чёрный) |
| Шрифт названий | **Vinque** |
| Лента «Карта приказа» | `#E9DDD3` |
| Шрифт смут дополнительный | `#7D6441` (**Isabella-Decor**) |

### Задник карты
| Элемент | Цвет |
|---|---|
| Центр | `#61B1BD` |
| Контур | `#617AA3` |
| Надпись «СМУТА» | `#D7D786` |

---

## Палитры домов

Каждый дом: **Лента** (фон плашки названия) + **Акцент** (обводка/детали).

| Дом | Лента | Акцент |
|---|---|---|
| 🟢 Зелёный (знания) | `#8EBC8B` | `#2B5F1F` |
| 🔴 Красный (власть) | `#DB443F` | `#7F1714` |
| 🔵 Синий (интриги) | `#8BB8DF` | `#234A68` |
| 🌸 Розовый (любовь) | `#DB71A9` | `#6D1B49` |
| 🟠 Рыжий (изобилие) | `#EC6A38` | `#9C390D` |
| ⚫ Чёрный (пираты) | `#232323` | `#FFFFFF` |
| 🟤 Бежевый (стойкость) | `#EEDED3` | `#FFFFFF` *(текст замка — `#B09D59`)* |
| 🟡 Жёлтый (свет) | `#EBBF58` | `#C9920A` |

---

## 🖼️ Промты для очистки задников

Промт для вытаскивания «чистого» арта из готовой карты (убрать плашки, ленты, текст и восстановить скрытое под ними).

### Вертикальные карты (персонажи, приказы)

> Формат **63×88 мм**

```
Recreate this image at full print quality without any overlaid elements. Keep only the
character and the background exactly as they are.

Requirements:
- Remove all text, logos, watermarks, captions, banners, ribbons, borders, frames, and any
  other graphics layered on top of the artwork
- Do not add any new elements
- Reconstruct any part of the character or background that was hidden behind removed overlays,
  matching the surrounding art style, lighting, and colors seamlessly
- No rounded corners — full rectangular bleed
- Output dimensions: 63×88 mm at 600 dpi (1488×2079 px)
- Deliver a clean, flat source image with nothing covering the illustration
```

### Горизонтальные карты (смуты, слуги)

> Формат **88×63 мм**

```
Recreate this image at full print quality without any overlaid elements. Keep only the
character and the background exactly as they are.

Requirements:
- Remove all text, logos, watermarks, captions, banners, ribbons, borders, frames, and any
  other graphics layered on top of the artwork
- Do not add any new elements
- Reconstruct any part of the character or background that was hidden behind removed overlays,
  matching the surrounding art style, lighting, and colors seamlessly
- No rounded corners — full rectangular bleed
- Output dimensions: 88×63 mm at 600 dpi (2079×1488 px)
- Deliver a clean, flat source image with nothing covering the illustration
```

---

## ☀️ Базовый промт стиля (Дополнение «Свет с небес»)

Шапка, общая для всех персонажей Жёлтого дома. Третий блок меняется под конкретную роль.

```
Painterly 3D animated movie style illustration, semi-realistic cartoon look, big
expressive eyes, soft rounded features, warm cinematic lighting, richly detailed medieval
fantasy costume with golden embroidery, half-length character portrait, atmospheric themed
background, vertical 5:7 aspect ratio, no text, no watermark, high detail.

Warm golden-yellow palette of the Sunlit House: gold and honey robes with ivory and white
accents, glowing sunlit atmosphere, sun and light motifs, bright hopeful mood.

[описание конкретного персонажа]
```
