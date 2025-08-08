---
marp: true
paginate: true
html: true
---

# +α

---

## あるエンジニアからの学び

**ギターメンテナンス技術者**との会話で
印象的だった言葉

> 「期待を超えてパフォームしなければ、
> 何かに置き換われる存在になってしまう」

**この+αをどこに置くか**が、
仕事の価値を決める

---

## 組織の仕事で考えてみると？

個人の+αは重要。
でも組織全体ではどうだろう？

**人と人の境界線**で
何が起きているのか見てみよう。

---
## 仕事の境界問題

**担当が明確に分かれている時**

<span class="problem-text">**問題**: 境界がぴったり合うことはない</span>

- 黄色い部分（誰の担当？）が発生
- **結果として仕事が漏れる、品質が下がる**

<section>

<svg width="500" height="200" viewBox="0 0 500 200">
  <!-- Person A's work area -->
  <rect x="50" y="60" width="150" height="80" fill="#ff6b6b" opacity="0.7" stroke="#d63031" stroke-width="3"/>
  <text x="125" y="105" text-anchor="middle" font-size="18" font-weight="bold" fill="white">Person A</text>
  
  <!-- Gap in the middle -->
  <rect x="200" y="60" width="100" height="80" fill="#ffeaa7" opacity="0.8" stroke="#fdcb6e" stroke-width="2" stroke-dasharray="5,5"/>
  <text x="250" y="90" text-anchor="middle" font-size="16" fill="#e17055">???</text>
  <text x="250" y="110" text-anchor="middle" font-size="14" fill="#e17055">誰がやる？</text>
  <text x="250" y="130" text-anchor="middle" font-size="14" fill="#e17055">漏れる！</text>
  
  <!-- Person B's work area -->
  <rect x="300" y="60" width="150" height="80" fill="#74b9ff" opacity="0.7" stroke="#0984e3" stroke-width="3"/>
  <text x="375" y="105" text-anchor="middle" font-size="18" font-weight="bold" fill="white">Person B</text>
  
  <!-- Warning arrows -->
  <path d="M 250 40 L 250 55" stroke="#e74c3c" stroke-width="4" marker-end="url(#arrowhead)"/>
  <path d="M 250 145 L 250 160" stroke="#e74c3c" stroke-width="4" marker-end="url(#arrowhead)"/>
  
  <!-- Arrow marker definition -->
  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="0" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#e74c3c"/>
    </marker>
  </defs>
</svg>

</section>

---

## 解決策：+αの効果

**現実**: 人間同士、完璧な境界線は引けない

<span class="solution-text">**だからこそ**: お互いが自分の領域から
**少し+αを出す**ことで、初めて全体をカバーできる</span>

**これが+αの真の価値**

<section>

<svg width="500" height="200" viewBox="0 0 500 200">
  <!-- Person A's work area with overflow -->
  <rect x="50" y="60" width="150" height="80" fill="#ff6b6b" opacity="0.7" stroke="#d63031" stroke-width="3"/>
  <text x="125" y="105" text-anchor="middle" font-size="18" font-weight="bold" fill="white">Person A</text>
  
  <!-- A's +α overflow -->
  <ellipse cx="200" cy="100" rx="50" ry="40" fill="#ff6b6b" opacity="0.4"/>
  <text x="200" y="85" text-anchor="middle" font-size="14" font-weight="bold" fill="#d63031">+α</text>
  <text x="200" y="105" text-anchor="middle" font-size="12" fill="#d63031">+α</text>
  
  <!-- Person B's work area with overflow -->
  <rect x="300" y="60" width="150" height="80" fill="#74b9ff" opacity="0.7" stroke="#0984e3" stroke-width="3"/>
  <text x="375" y="105" text-anchor="middle" font-size="18" font-weight="bold" fill="white">Person B</text>
  
  <!-- B's +α overflow -->
  <ellipse cx="300" cy="100" rx="50" ry="40" fill="#74b9ff" opacity="0.4"/>
  <text x="300" y="85" text-anchor="middle" font-size="14" font-weight="bold" fill="#0984e3">+α</text>
  <text x="300" y="105" text-anchor="middle" font-size="12" fill="#0984e3">+α</text>
  
  <!-- Overlap area - success! -->
  <ellipse cx="250" cy="100" rx="30" ry="25" fill="#00b894" opacity="0.8"/>
  <text x="250" y="95" text-anchor="middle" font-size="14" font-weight="bold" fill="white">✓</text>
  <text x="250" y="110" text-anchor="middle" font-size="12" font-weight="bold" fill="white">カバー!</text>
  
  <!-- Flow arrows -->
  <path d="M 180 100 L 220 100" stroke="#ff6b6b" stroke-width="3" marker-end="url(#arrowhead2)"/>
  <path d="M 320 100 L 280 100" stroke="#74b9ff" stroke-width="3" marker-end="url(#arrowhead2)"/>
  
  <defs>
    <marker id="arrowhead2" markerWidth="8" markerHeight="6" refX="0" refY="3" orient="auto">
      <polygon points="0 0, 8 3, 0 6" fill="#00b894"/>
    </marker>
  </defs>
</svg>

</section>

---

## でも、ちょっと待って

**現実的な制約**があることも事実

**一人の人が出せる+αの量は有限**
そして限界がある

<svg width="500" height="250" viewBox="0 0 500 250">
  <!-- Individual capacity - circular -->
  <circle cx="125" cy="125" r="60" fill="#e74c3c" opacity="0.7" stroke="#d63031" stroke-width="3"/>
  <text x="125" y="120" text-anchor="middle" font-size="16" font-weight="bold" fill="white">個人の+α</text>
  <text x="125" y="135" text-anchor="middle" font-size="14" fill="white">有限</text>
</svg>

---

## 組織構造で考える：Top Down の限界

**従来の階層構造**

<div class="two-column">

<div class="column-left">

**現実**:
- 上層部の+αは**限られている**
- 組織が大きくなるほど**末端まで届かない**
- 黄色い部分＝カバーされない領域が拡大

</div>

<div class="column-right">
<svg width="400" height="300" viewBox="0 0 400 300">
  <!-- Triangle structure -->
  <polygon points="200,50 100,200 300,200" fill="#ecf0f1" stroke="#95a5a6" stroke-width="2"/>
  
  <!-- Top level -->
  <circle cx="200" cy="80" r="25" fill="#e74c3c"/>
  <text x="200" y="87" text-anchor="middle" font-size="20" fill="white">👑</text>
  
  <!-- Middle levels -->
  <circle cx="160" cy="130" r="15" fill="#f39c12"/>
  <circle cx="240" cy="130" r="15" fill="#f39c12"/>
  <text x="160" y="137" text-anchor="middle" font-size="12" fill="white">👤</text>
  <text x="240" y="137" text-anchor="middle" font-size="12" fill="white">👤</text>
  
  <!-- Bottom level -->
  <circle cx="120" cy="170" r="12" fill="#3498db"/>
  <circle cx="160" cy="170" r="12" fill="#3498db"/>
  <circle cx="200" cy="170" r="12" fill="#3498db"/>
  <circle cx="240" cy="170" r="12" fill="#3498db"/>
  <circle cx="280" cy="170" r="12" fill="#3498db"/>
  <text x="120" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="160" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="200" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="240" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="280" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  
  <!-- Limited overflow from top -->
  <ellipse cx="200" cy="110" rx="40" ry="20" fill="#e74c3c" opacity="0.3"/>
  <text x="200" y="115" text-anchor="middle" font-size="12" fill="#c0392b">限られた+α</text>
  
  <!-- Gap areas -->
  <ellipse cx="140" cy="200" rx="30" ry="15" fill="#f1c40f" opacity="0.6"/>
  <ellipse cx="260" cy="200" rx="30" ry="15" fill="#f1c40f" opacity="0.6"/>
  <text x="140" y="205" text-anchor="middle" font-size="10" fill="#d68910">不足</text>
  <text x="260" y="205" text-anchor="middle" font-size="10" fill="#d68910">不足</text>
  
  <!-- Downward arrows showing insufficient flow -->
  <path d="M 200 105 L 140 190" stroke="#e74c3c" stroke-width="2" stroke-dasharray="3,3" opacity="0.7"/>
  <path d="M 200 105 L 260 190" stroke="#e74c3c" stroke-width="2" stroke-dasharray="3,3" opacity="0.7"/>
</svg>


</div>

---

## 新しい視点：Bottom Up の可能性

**逆転の発想**

<div class="two-column">

<div class="column-left">

**仮説**:
- 現場の一人ひとりが+αを出せば
- **多点からの+α**が生まれる
- 結果として**より多くの領域をカバー**できるはず

</div>

<div class="column-right">
<main>
<svg width="400" height="300" viewBox="0 0 400 300">
  <!-- Inverted triangle structure for Bottom Up -->
  <polygon points="200,50 100,200 300,200" fill="#e8f5e8" stroke="#27ae60" stroke-width="2"/>
  
  <!-- Top level (same position as Top Down) -->
  <circle cx="200" cy="80" r="25" fill="#e74c3c"/>
  <text x="200" y="87" text-anchor="middle" font-size="20" fill="white">👑</text>
  
  <!-- Middle levels (same position as Top Down) -->
  <circle cx="160" cy="120" r="15" fill="#f39c12"/>
  <circle cx="240" cy="120" r="15" fill="#f39c12"/>
  <text x="160" y="127" text-anchor="middle" font-size="12" fill="white">👤</text>
  <text x="240" y="127" text-anchor="middle" font-size="12" fill="white">👤</text>
  
  <!-- Bottom level (same position as Top Down) -->
  <circle cx="120" cy="170" r="12" fill="#27ae60"/>
  <circle cx="160" cy="170" r="12" fill="#27ae60"/>
  <circle cx="200" cy="170" r="12" fill="#27ae60"/>
  <circle cx="240" cy="170" r="12" fill="#27ae60"/>
  <circle cx="280" cy="170" r="12" fill="#27ae60"/>
  <text x="120" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="160" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="200" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="240" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  <text x="280" y="177" text-anchor="middle" font-size="10" fill="white">👥</text>
  
  <!-- Multiple +α from bottom level (現場からの豊富な+α) -->
  <ellipse cx="120" cy="150" rx="25" ry="15" fill="#2ecc71" opacity="0.6"/>
  <ellipse cx="160" cy="150" rx="25" ry="15" fill="#2ecc71" opacity="0.6"/>
  <ellipse cx="200" cy="150" rx="25" ry="15" fill="#2ecc71" opacity="0.6"/>
  <ellipse cx="240" cy="150" rx="25" ry="15" fill="#2ecc71" opacity="0.6"/>
  <ellipse cx="280" cy="150" rx="25" ry="15" fill="#2ecc71" opacity="0.6"/>
  
  <!-- Upward arrows showing bottom-up flow -->
  <path d="M 120 155 L 170 125" stroke="#27ae60" stroke-width="3" marker-end="url(#arrowhead3)"/>
  <path d="M 160 155 L 170 125" stroke="#27ae60" stroke-width="3" marker-end="url(#arrowhead3)"/>
  <path d="M 200 155 L 200 105" stroke="#27ae60" stroke-width="3" marker-end="url(#arrowhead3)"/>
  <path d="M 240 155 L 230 125" stroke="#27ae60" stroke-width="3" marker-end="url(#arrowhead3)"/>
  <path d="M 280 155 L 230 125" stroke="#27ae60" stroke-width="3" marker-end="url(#arrowhead3)"/>

  <defs>
    <marker id="arrowhead3" markerWidth="8" markerHeight="6" refX="0" refY="3" orient="auto">
      <polygon points="0 0, 8 3, 0 6" fill="#27ae60"/>
    </marker>
  </defs>
</svg>

  <!-- Success text -->
  <text x="200" y="250" text-anchor="middle" font-size="16" font-weight="bold" fill="#27ae60">豊富な+α供給！</text>
</main>
</div>

</div>

---

## だからこそ、問いたい

**有限な個人の+α**

**無限に近い組織のニーズ**

このギャップを前提として...

---

# あなたは
# どこに
# +αを置きますか？

---

## ありがとうございました

### 質疑応答