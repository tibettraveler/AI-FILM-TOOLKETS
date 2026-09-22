CharacterDS 是一份skill。可以安裝在chatGPT

讓角色不只被「畫出來」，而是被完整建立、辨識、展示與延伸。

CharacterDS 是一套以 角色深度 DS（Deep Character Design System） 為核心的模組化技能，專注於角色身份一致性、靜態美術設定、動態人物展示，以及兩者之間的連動。

它不是單純的 Character Sheet 產生器，也不是固定 Prompt 模板庫。
CharacterDS 的核心價值，是把角色的 Identity、Visual Design、Presentation、Motion Showcase 組織成一套可持續擴充的角色展示系統。

What CharacterDS Does

CharacterDS 目前支援兩大能力體系：

Static Presentation

建立具有一致身份與視覺邏輯的靜態角色 DS，包括：

Character Sheet

Identity Lock Sheet

Turnaround

表情與微表情

頭部與局部結構

服裝、材質與配件細節

姿態與輪廓

配色與視覺層級

單張或多張協同設定板

版面不是固定格子模板，而是由模組化 Layout System 組裝。
局部內容可替換、增減與重排，同時維持清楚的視覺主次、間距、閱讀順序與整體美感。

當使用者沒有指定唯一版面時，CharacterDS 可主動提出 3 組具有實質差異的搭配方案，再依用途選擇最適合的構圖方向。

Dynamic Presentation

將角色從靜態設定延伸成動態展示，包括：

人物介紹蒙太奇

Identity Reveal

Material Showcase

Emotion Build

Signature Detail Intro

Dress-up Final Reveal

Invisible Dressing Room

單角色 Showcase

雙角色／多角色交叉展示

多變種 Dynamic Showcase

CharacterDS 不把一份長 Prompt 當成固定答案，而是將動態展示拆成可組裝的：

Motion + Shot + Reveal + Narrative + Asset Control

因此同一角色可以建立不同節奏、不同展示語言與不同揭示策略，而不必每次重新撰寫整套 Prompt。

Static + Motion

CharacterDS 支援真正的 動靜搭配。

靜態 DS 中確認的：

Identity Anchors

Hero View

Signature Details

Outfit / Material

Expression Set

Pose / Silhouette

都可以轉譯成動態展示節點。

這使角色的設定圖與展示影片不再是兩份彼此無關的產物，而是共享同一身份核心與資產定義的配套內容。

目前支援：

static-only

motion-only

static+motion-paired

multi-variant-showcase

Built for Character Consistency

CharacterDS 將角色身份視為最高優先級。

它會區分並管理：

Identity

Anatomy

Outfit

Prop

Accessory

Surface Marks

State Variants

角色可以換表情、換姿勢、換鏡位、換背景，甚至在明確狀態下換裝，但不應因此變成另一個角色。

對非人型、機械或特殊結構角色，CharacterDS 也不強迫套用人體模板；不存在的部位會改用實際存在、功能最接近的結構，而不是憑空新增。

Multi-character Showcase

雙角色與多角色展示是 CharacterDS 的正式能力之一。

CharacterDS 會分別建立角色資產歸屬，避免常見的交叉污染，例如：

A 的武器漂到 B

A 的服裝局部出現在 B 身上

角色切換後五官或身形混合

換裝過程出現半套 A、半套 B 的混合狀態

跨角色切換時，可以延續：

Motion

Rhythm

Camera Direction

Narrative Beat

但不會自動延續：

Identity

Anatomy

Outfit

Prop

Accessory

換句話說：

節奏可以接棒，角色資產不能串錯。

Controlled Continuity

CharacterDS 不把「連續性」視為單一概念。

它透過 Continuity Channels 分別管理：

身份是否延續

資產是否延續

動作是否延續

節奏是否延續

鏡頭方向是否延續

敘事節點是否延續

因此可以做出流暢的 Match Cut、Relay Cut 或雙角色交叉展示，同時降低角色與資產漂移風險。

Less Mirroring. More Visual Variety.

雙角色展示很容易陷入大量對稱、鏡像與機械式 A/B/A/B 節奏。

CharacterDS 內建 Motion Variation Control，會主動檢查：

動作家族是否重複

左右方向是否過度鏡像

Shot Scale 是否單調

Camera Direction 是否重複

Silhouette 是否缺乏變化

動靜強弱是否沒有對比

雙角色焦點是否過度平均

預設策略是 互補，而不是鏡像。

例如：

A 大幅動作 → B 微表情

A 強動作 → B 材質細節

A 先 Reveal → B 延後 Reveal

A 正向運動 → B 斜向承接

讓交叉展示更有節奏，也更耐看。

Narrative Template Library

CharacterDS 內建可持續擴充的角色展示敘事模板。

目前包括：

Single Character

identity-reveal

dress-up-final-reveal

invisible-dressing-room

material-showcase

emotion-build-reveal

signature-detail-intro

Duo / Multi-character

duo-cross-showcase

contrast-duet

relay-reveal

dual-final-reveal

這些不是固定成片模板，而是可與 Motion、Shot、Reveal 等模組重新組裝的敘事骨架。

新的展示變種也可持續加入，而不需要破壞既有技能結構。

Prompt Assembly & QC

CharacterDS 在輸出動態 Prompt 前，會依優先級重新組裝內容：

Identity Anchors

Asset Binding / State

Shot Ownership

Continuity Channels

Narrative / Sequence Plan

Motion / Shot / Reveal Grammar

Variation Control

Style / Lighting / Environment

Concise Hard Boundaries

同時進行 Prompt 清理：

合併重複否定句

優先使用正向、具作用域的描述

移除不必要的模型綁定

移除無控制價值的畫質堆詞

避免不必要的逐幀／逐秒控制

在高複雜度任務中拆成合理的 sequence blocks

目的不是把 Prompt 寫得更長，而是讓每一段提示都具有明確控制價值。

Three-Scheme Advisor

CharacterDS 在「未指定唯一方案」時，可主動提供 3 組方向。

靜態 DS

可依角色與用途提出：

Identity Focus

Design Focus

Showcase Focus

動態展示

可依素材提出：

Identity / Reveal Focus

Material / Design Focus

Contrast / Performance Focus

三案必須在結構、視覺重心或展示策略上具有實質差異，而不是單純交換位置或角色順序。

What CharacterDS Is — and Is Not

CharacterDS 專注於：

角色本身如何被定義、固定、展示與延伸。

它目前不是：

Production / Generation-Control Character DS

跨 Segment / Shot 的影片生成控制系統

模型特定 Conditioning Package

Prop Design Skill

Scene Design Skill

Merchandise / Product Design Skill

AFPT 的內部流程模組

角色既有的武器與配件可以作為 Identity Asset 被鎖定與展示，但 CharacterDS 不負責重新設計 Prop。

這種邊界讓 CharacterDS 能保持獨立發展，持續深化角色專業能力。

Current Architecture

CharacterDS
├─ Static Presentation
│  ├─ Art Setting Sheet
│  └─ Identity Lock Sheet
│
├─ Dynamic Presentation
│  └─ Detail Showcase
│
├─ Identity & Consistency
│  ├─ Identity Core
│  ├─ Anatomy Adaptation
│  ├─ Asset Binding
│  └─ Quality Consistency
│
├─ Static Composition
│  ├─ Layout System
│  └─ Composition Advisor
│
├─ Dynamic Grammar
│  ├─ Motion Continuity
│  ├─ Shot Grammar
│  ├─ Reveal Control
│  ├─ Continuity Channels
│  └─ Motion Variation Control
│
├─ Multi-character Control
│  └─ Cross-character Isolation
│
├─ Presentation Intelligence
│  ├─ Narrative Template Library
│  ├─ Showcase Advisor
│  └─ Static–Motion Bridge
│
└─ Prompt Quality
   └─ Prompt Assembly QC

Why CharacterDS

一般角色設定工具通常停留在「把角色整理成一張設定板」。

CharacterDS 希望再往前一步：

先建立角色。
再固定角色。
再讓角色被有效地展示。
最後讓靜態設定與動態表演成為同一套角色資產。

這就是 CharacterDS 的核心定位：

A deep character DS for consistent static design and expressive dynamic presentation.
