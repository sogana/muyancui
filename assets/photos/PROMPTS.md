# 沐研萃 · AI 生圖題詞（Prompt）清單

> 適用：Midjourney v6 / DALL·E 3 / Stable Diffusion / Adobe Firefly
> 風格主軸：**日系極簡 × 溫暖照護 × 自然光**
> 共通負面提示（Negative）：`oversaturated, harsh shadows, plastic texture, busy composition, text, watermark, logo, cartoon, 3D render, fake-looking`

---

## 共通風格 Anchor（每個 prompt 開頭都加）

```
soft natural daylight, warm minimal Japanese aesthetic, sage green and cream palette,
shallow depth of field, calm and quiet mood, clean composition, photographic, 35mm film look,
muted earth tones, no people unless specified, --ar 4:5 --style raw
```

---

## 1 · 首頁 Hero（hero-brand.png 替換）

**尺寸：** 1600×1200（4:3）

**Prompt：**
```
Minimal still life of a single white nutrition bottle on a warm cream linen surface,
soft sage-green eucalyptus leaves softly out of focus in foreground,
gentle morning sunlight through sheer curtain, large negative space on right for text,
muji-style aesthetic, kinfolk magazine photography, 35mm, soft shadows
```

---

## 2 · 創辦人 / 工廠（founder-factory.png 替換）

**尺寸：** 800×1000（4:5）

**選項 A — 創辦人肖像：**
```
Asian middle-aged man in soft beige linen shirt, looking thoughtfully out a window,
wide kitchen counter with one bottle of nutrition formula beside him,
warm afternoon light, shallow depth of field, documentary portrait style,
quiet emotional warmth, no eye contact with camera
```

**選項 B — 工廠外觀：**
```
Exterior shot of a small modern food factory in rural Taiwan,
soft white walls, large glass windows, surrounded by rice fields under blue sky,
clean architectural lines, peaceful rural atmosphere, late afternoon golden hour
```

---

## 3 · 灌食情境（care-tube-feeding.png 替換）

**尺寸：** 1200×900（4:3）

**Prompt：**
```
Top-down still life on warm cream wooden table: one white nutrition bottle,
a clean glass measuring cup with milky liquid, a small ceramic plate, soft cotton napkin,
a single dried branch as accent, no medical equipment visible,
warm natural daylight, intimate kitchen-counter mood, gentle shadows
```

---

## 4 · 居家照護日常（lifestyle-care.png 替換）

**尺寸：** 1200×800（3:2）

**Prompt：**
```
Two adult hands gently holding a warm ceramic mug across a wooden table,
elderly hand and younger hand, soft afternoon window light,
warm tones, blurred background of a tatami-style living room,
emotional intimacy without showing faces, documentary lifestyle photography
```

---

## 5 · 照護步驟 6 張（step-01 ~ step-06 替換）

**尺寸：** 600×600（1:1）

| # | 步驟 | Prompt 主體 |
|---|---|---|
| 01 | 手部清潔 | `close-up of hands being washed under running water in white ceramic basin, soft daylight, clean simple composition` |
| 02 | 確認管路 | `gentle close-up of hands holding a clear medical syringe over a clean white surface, soft sage-green tones, minimal` |
| 03 | 調整體位 | `softly out-of-focus white pillows stacked at 45 degree angle on a beige bed sheet, warm window light, no person visible` |
| 04 | 溫和灌食 | `slow-motion drip of cream-colored liquid from a clear glass dropper into a white ceramic cup, dramatic minimal still life` |
| 05 | 沖洗管路 | `clear water being poured from a small glass pitcher into a clean glass tube, white background, ultra minimal` |
| 06 | 餐後觀察 | `analog wall clock with cream face hanging on warm beige wall, soft afternoon shadow, peaceful moment` |

每張都加共通 anchor。

---

## 6 · 商品實拍（替換目前 6 支瓶身 PNG）

**尺寸：** 1200×1200（1:1）

**通用 Prompt 模板：**
```
Studio product photography of a single white aluminum bottle on warm cream paper background,
no label visible — clean blank surface, soft top-light, gentle drop shadow,
sage green eucalyptus sprig leaning against bottle base on left,
muji-style minimal, e-commerce ready, ultra clean, 1:1 square format
```

> ⚠️ 標籤建議用 Photoshop 後製貼上，AI 不擅長排版小字。

---

## 7 · Footer / 品牌信任區建議圖

| 用途 | Prompt |
|---|---|
| SGS 檢驗實驗室 | `clean modern food laboratory interior, white tiles, glass beakers, single technician in white coat blurred in background, sage tones` |
| 雲林麥寮工廠空拍 | `aerial drone shot of small white factory building surrounded by green rice fields in Taiwan, golden hour light, peaceful rural composition` |
| 配送/包裝 | `single brown craft cardboard box with cream tissue paper folded inside, on wooden floor, soft window light, minimal` |

---

## 風格參考關鍵字（給 AI 工具更精準）

- **攝影師參考：** `Kinfolk magazine, Cereal magazine style, Hidetoshi Kuranari, Anders Schønnemann`
- **品牌參考：** `Muji, Aesop, Le Labo product photography`
- **避開：** `medical sterile look, hospital aesthetic, plastic packaging, clinical white`

---

## 替換流程

1. 用此清單跑出圖（推薦 Midjourney v6 + `--style raw --ar` 對應比例）
2. 命名為相同檔名（例：`hero-brand.png`）
3. 放回 `assets/photos/` 覆蓋
4. 重整網頁即生效，不需改 HTML
