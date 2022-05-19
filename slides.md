---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  presenterOnly: true
download: true
hideInToc: true
---

# 執行力

我所看到的視界

<div class="pt-12">
  <span @click="$slidev.nav.next" class="rounded cursor-pointer py-1 px-2" hover="bg-white bg-opacity-10">
    OLD_TS 部內幹部分享 呂正中
  </span>
</div>

---
hideInToc: true
---

# 今天說什麼呢？

<Toc class="mt-16 px-20 text-2xl" :columns="2" />

---
layout: center
class: text-center
---

# 定義

我所看到的執行力是什麼呢？

<div class="flex mt-12 items-center">
  <span v-click="2" class="mr-2 text-5xl">
  <emojione:rocket class="inline" />快速的
  </span>
  <span v-click="1" class="text-3xl">
  將一件事做好、做完
  </span>
</div>

---

# 方法

想要做好一件事要用借助什麼方法

<div class="h-2/3 text-center grid grid-cols-2 grid-rows-3 justify-center items-center">
  <div v-click class="text-4xl">PDCA</div>
  <div v-click class="text-4xl">Scrum</div>
  <div v-click class="text-4xl">KPI</div>
  <div v-click class="text-4xl">OKR</div>
  <div v-click class="text-4xl col-span-2">Prototype</div>
</div>

---

# 手段

當方法有了，推進時為什麼還是覺得卡卡的呢？

<div v-click class="border flex divide-x-4 rounded-3xl h-[60%] mt-16 text-center items-center justify-center">
  <div class="w-1/2">

  <h2><carbon:user class="inline" />單兵作戰</h2>

  </div>
  <div class="w-1/2">

  <h2><carbon:user-multiple class="inline" />多人協作</h2>

  </div>
</div>



---
hideInToc: true
---

# 單兵作戰

不管是你是獨善其身或是孤狼，都需要

<div v-click="1" class="border flex divide-x-4 rounded-3xl h-[60%] mt-16 text-center items-center justify-center">
  <div v-click="1" class="w-1/2">
    <h2>
      <carbon:timer class="inline" />自制力
    </h2>
  </div>
  <div v-click="2" class="w-1/2">
    <h2>
      <carbon:cognitive class="inline" />知識
    </h2>
  </div>
  <div v-click="3" class="w-1/2">
    <h2>
      <carbon:machine-learning-model class="inline" />學習成長
    </h2>
  </div>
  <div v-click="4" class="w-1/2">
    <h2>
      <simple-icons:gunicorn class="inline" />突破困境
    </h2>
  </div>
</div>

---
hideInToc: true
---

# 多人協作

自已一人能做多少事呢？ 都說人多好辦事，但怎麼叫人跟你一起做事

<div v-click="1" class="border flex divide-x-4 rounded-3xl h-[60%] mt-16 text-center items-center justify-center">
  <div v-click="1" class="w-1/2">
    <h2>
      <ps:google-talk class="inline" />說服
    </h2>
  </div>
  <div v-click="2" class="w-1/2">
    <h2>
      <emojione:money-bag class="inline" />利誘
    </h2>
  </div>
  <div v-click="3" class="w-1/2">
    <h2>
      <openmoji:authority-building class="h-10 w-10 inline" />權勢
    </h2>
  </div>
</div>



---
layout: quote
class: text-center
---

# 案例

以我過往的成長經驗來檢討

---

## 第一次導入 Vue

剛進公司第2年，商用時期

- 單兵
  - 自制力： ★
  - 知識： ★
  - 學習成長： ★★ 外訓+自學
  - 突破困境： ★ 進度落後
- 協作
  - 說服： ★★ 前端知識獨佔優勢
  - 利誘： ★

---

## 區塊鏈

<p><span class="opacity-50 text-gray-400">剛進公司第2年，商用時期</span> → 線上第1.5年</p>

- 單兵
  - 自制力： ★★★★ 高工時投入
  - 知識： ★★
  - 學習成長： ★★
  - 突破困境： ★★★ 未知領域
- 協作
  - 說服： ★★ 前端人員可獨立完成全端
  - 利誘： ★★ 減少製作工具

---

## 金銀島改版

<p><span class="opacity-50 text-gray-400">剛進公司第2年，商用時期 → 線上第1.5年</span> → 線上第2.5年</p>

- 單兵
  - 自制力： ★★★★
  - 知識： ★★★
  - 學習成長： ★★★
  - 突破困境： ★★★ 大量頁面靈活運用共通元件
- 協作
  - 說服： ★★★ 漸漸地會講人話
  - 利誘： ★★ 一個vue檔全搞定不需要再東摳西摳

---

## 救世英雄 NFT 專案

<p><span class="opacity-50 text-gray-400">剛進公司第2年，商用時期 → 線上第1.5年 → 線上第2.5年</span> → 線上第3年</p>

- 單兵
  - 自制力： ★★ 身體不適
  - 知識： ★★★★ 累積的知識，讓產能依舊
  - 學習成長： ★★★
  - 突破困境： ★★★
- 協作
  - 說服： ★★★ 讓美術能用熟悉工具，快速生成示意產出
  - 利誘： ★★★ 減少美術工時

---

## 規劃成立前端小組

<p><span class="opacity-50 text-gray-400">剛進公司第2年，商用時期 → 線上第1.5年 → 線上第2.5年 → 線上第3年</span> → 線上第3.5年</p>

- 單兵
  - 自制力： ★★★ 逐漸康復
  - 知識： ★★★★
  - 學習成長： ★★★
  - 突破困境： ★★★ 數據收集、技術債
- 協作
  - 說服： ★★★★ 數據輔佐
  - 利誘： ★★★ 專業分工更高效

---
layout: center
class: text-center
hideInToc: true
---

# Q & A

