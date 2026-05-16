# 沐研萃 · AI 圖片題詞 v2.0
> 適用：ChatGPT (DALL·E 3) / Midjourney v6 / Adobe Firefly
> 風格主軸：**日系極簡 × 溫暖照護 × 自然光**

---

## 共通風格 Anchor（每個 prompt 開頭加上）

```
soft natural daylight, warm minimal Japanese aesthetic, sage green and cream palette,
shallow depth of field, calm and quiet mood, clean composition, photographic, 35mm film look,
muted earth tones, neutral cream background #fcfbf8
```

**負面提示（DALL·E 不直接吃 negative，但可加在 prompt 後）：**
`avoid oversaturated colors, harsh shadows, plastic texture, busy composition, cartoon style, 3D render, generic stock photography look, medical sterile hospital feel`

---

# Part 1 · 內容情境圖（已完成）

| 檔名 | 用途 | 狀態 |
|---|---|---|
| `assets/photos/hero-brand.png` | 首頁 Hero | ✅ 已替換 |
| `assets/photos/founder-factory.png` | 品牌故事 · 創辦人 | ✅ 已替換 |
| `assets/photos/care-tube-feeding.png` | 照護指南精選文 | ✅ 已替換 |
| `assets/photos/lifestyle-care.png` | 居家照護日常 | ✅ 已替換 |
| `assets/photos/step-01.png` ~ `step-06.png` | 照護 6 步驟 | ✅ 已替換 |
| `assets/photos/Aerial-Factory.png` | 工廠空拍 | ✅ 已替換 |
| `assets/photos/Testing-Laboratory.png` | SGS 實驗室 | ✅ 已替換 |
| `assets/photos/Delivery-Packaging.png` | 配送包裝 | ✅ 已替換 |

---

# Part 2 · 商品照（待替換）

## 配方類 · 6 支 · 1:1 比例（1200×1200）

通用模板：
```
Studio product photography of a single 200ml white aluminum foil pouch
standing upright on warm cream paper background,
clean blank surface (label will be added in post),
soft top-light from window, gentle drop shadow underneath,
small sage green eucalyptus sprig leaning at base on the left,
muji-style minimal aesthetic, e-commerce ready, 1:1 square, ultra clean composition
```

**6 支差異（取代「pouch」描述）：**

| # | 檔名 | 差異主體 |
|---|---|---|
| 01 | `my-standard.png` | classic white pouch with subtle sage green label band |
| 02 | `my-diabetic.png` | white pouch with deep-sea-blue label band, add a small dried wheat stalk on right |
| 03 | `my-renal.png` | white pouch with terracotta orange label band, add a single dried fig leaf |
| 04 | `my-protein.png` | white pouch with dark forest-green label band, add a small cluster of dried oats |
| 05 | `my-fiber.png` | white pouch with light sage label band, add a small bundle of fresh wheat grass |
| 06 | `my-fortified.png` | white pouch with deep navy label band, add a small ceramic measuring spoon |

> ⚠️ 標籤文字（中文「均衡配方」等）建議用 Photoshop 後製貼上，AI 不擅長排版小字。
> 也可以請 AI 留出乾淨的 label band 區域，再用商品設計稿覆蓋。

---

## 器材類 · 6 件 · 1:1 比例（1200×1200）

通用模板：
```
Product photography on warm cream paper background #fcfbf8,
single object centered, soft natural top light, subtle drop shadow,
muji-style minimal, premium medical-grade quality feel but warm not clinical,
1:1 square, 35mm photographic look, no people
```

**6 件器材：**

### A1 · 灌食袋（重力滴注式）`acc-bag.png`
```
Single clear medical-grade feeding bag hanging from above with adjustable roller clamp,
500ml capacity with milky liquid filled to halfway, drop line tubing visible,
sage green clamp accent, white-cream background, soft daylight,
Japanese minimal product photography, 1:1 square
```

### A2 · 灌食空針 60ml `acc-syringe.png`
```
Single 60ml food-grade catheter-tip feeding syringe lying horizontally at slight angle,
clear plastic barrel with measurement markings, sage green plunger,
on warm cream paper, soft top-light, drop shadow, minimal composition, 1:1 square
```

### A3 · 攜帶式加溫器 `acc-warmer.png`
```
Compact circular USB feeding warmer device, white ceramic-look exterior,
small digital display showing "37°C", subtle sage green ring detail,
sitting on warm cream paper background, soft natural light,
minimal product shot reminiscent of Apple or Bang & Olufsen aesthetic, 1:1 square
```

### A4 · 灌食架（折疊式） `acc-stand.png`
```
Modern foldable IV pole / feeding stand in matte chrome silver,
adjustable telescoping pole, top hook with empty hanger,
four-wheel base, standing upright on warm cream paper background,
minimal medical equipment photography, Muji aesthetic, 1:1 square, soft natural light
```

### A5 · 管路清潔組 `acc-cleaning.png`
```
Tube cleaning kit flat-lay on warm cream paper: 
long slim cleaning brush with sage-green handle,
small clear glass irrigation bottle,
a folded white cotton cloth,
soft natural light, top-down view, minimal Japanese product photography, 1:1 square
```

### A6 · 餵食湯匙組 `acc-utensil.png`
```
Three food-grade silicone feeding spoons arranged in fan formation,
sage green soft handles, white silicone bowl heads,
on warm cream paper background, top-down flat-lay,
soft natural light, gentle shadows, minimal aesthetic, 1:1 square
```

---

# Part 3 · 其他可能需要的圖

## 商品內頁 Hero 替代圖（情境照） · 1:1（1200×1200）

每支配方可以再多一張「情境照」（與包裝照不同），放在內頁第二張縮圖位：

```
Lifestyle still life: one bottle of [配方類型] formula on warm wooden kitchen counter,
beside a clean white ceramic cup half-filled with the milky liquid,
single small green plant in background out of focus,
morning window light, intimate home setting, no people,
35mm film photography, 1:1 square
```

## 照護指南其他主題小圖 · 1200×800（3:2）

可生這 6 張對應 6 個主題：

| 主題 | Prompt 焦點 |
|---|---|
| 配方挑選 | `top-down arrangement of 3 different white pouches on cream linen` |
| 鼻胃管灌食 | `clean medical tubing coiled neatly on white surface, single accessory` |
| 餵食時間 | `analog wall clock and small notebook on wooden table, warm light` |
| 開封後保存 | `single bottle in clean white refrigerator with soft interior light` |
| 不適處理 | `cup of warm tea with hand cradling it, blurred bedroom background` |
| 家屬喘息 | `empty rocking chair by sunny window, single book on the seat` |

每張加上共通 anchor。

## 品牌故事頁人物照（可選）· 4:5（800×1000）

```
Asian middle-aged man in soft beige linen apron working at modern small food production line,
gentle attention to single bottle in his hands, warm afternoon factory light,
documentary photography style, shallow depth of field, no eye contact with camera,
quiet emotional warmth, 4:5 portrait
```

## 認證徽章模擬（可選） · 1:1（400×400 各一）

```
Flat minimal certification badge design,
single line icon (shield with check / leaf / lab beaker),
sage green stroke on cream background,
text "SGS" / "ISO 22000" / "HACCP" below in clean sans-serif,
emblem-style, minimal, 1:1 square
```

---

# Part 4 · 風格參考關鍵字（給 AI 更精準）

加在 prompt 結尾：

- **攝影感參考：** `Kinfolk magazine, Cereal magazine, Anders Schønnemann, Hidetoshi Kuranari`
- **品牌美學參考：** `Muji, Aesop, Le Labo, Hario product photography`
- **避開：** `medical sterile hospital, plastic packaging, clinical white, generic stock`

---

# Part 5 · 替換流程

1. 用 ChatGPT 跑出圖（DALL·E 3 預設正方形 1024×1024 即可）
2. 命名為對應檔名（例：`my-standard.png`、`acc-bag.png`）
3. 上傳到 GitHub repo 對應路徑：
   - 配方類：`assets/products/`
   - 器材類：`assets/products/`
   - 情境照：`assets/photos/`
4. 推上去後重新整理網頁即生效

---

## 一次給 ChatGPT 的提示語範例

> 「請依照下面的風格與描述，產生 6 張產品照，每張 1:1 比例：[貼上 6 個配方/器材的 prompt]」

ChatGPT 一次最多 4 張，分兩次跑即可。
