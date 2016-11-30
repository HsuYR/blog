---
layout: post
title: "Block 1 藥理學 2"
date: 2016-09-29 22:10:32 +0800
categories: medicine pharmacology
published: no
---
## 學習目標

 * Volume of Distribution, V<sub>D</sub>, and Clearance, CL
 * Half-Life and Drug Accumulation
 * Bioavailability
 * Designing a Rational Dosage Regimen

Pharmacodynamics 處理 concentration-effect relationship，Pharmacokinetics 處理 dose-concentration relationship。
Pharmacokinetics 在研究藥物濃度時要考量兩項人體主要參數：Clearance 衡量身體移除藥物的能力、Volume of distribution 衡量身體有多少空間是藥物的分佈範圍。兩者可以用課本 Figure 3-2 來比喻。在上完這次課後，應該要有能力從藥物參數中規劃出簡單的給藥方案。

## Volume of Distribution, V<sub>D</sub>

 * Volume of Distribution（V<sub>D</sub>）無法直接測量，但可以從用藥量和血液中藥物濃度估算。
 * V = Amount of drug in body / C。其中 C 可以依據是計算血液、血漿、水分中藥物濃度，分別稱為 Cb、Cp、Cu，而計算出的 V 分別稱為 Vb、Vp、Vu。
 * 以此公式估算出的 V<sub>D</sub> 稱為 *apparent* volume of distribution。
 * 依據分佈方式平均與否，V<sub>D</sub> 可能比身體實際體積大（表示在組織間濃度較高）或是小到幾乎等於血漿體積（表示藥物集中在血漿中）。

## Clearance

 * Clearance 也可以用類似 V<sub>D</sub> 的方式估算，即 CL = Rate of elimination / C。CL 單位是 體積/時間，也就是每單位時間能夠處理多少體積的體液。
 * Clearance 是能夠加總的。不同器官如腎臟、肺臟、肝臟等可以分別計算其 Rate of elimination 再除以該器官所處濃度 C，最後加總能得到系統 CL。
 * Rate of elimination 對特定器官或系統並不是固定值，可能依據濃度變化而改變。如濃度提高，排除速率可能隨之上升或是因達到上限速率而維持相同速率。

### First-order Elimination

 * 當 Rate of elimination 與 C 成正比（或說 CL 為定值）時稱為 first-order elimination
 * 若為 first-order elimination 時，CL 可以用 dose / Area under the curve（AUC）估算

### Capacity-Limited Elimination

 * 當 CL 會因 C 改變而改變時稱為 capacity-limited elimination
 * 大多數 drug elimination pathway 都會因為濃度太高而飽和
 * 這時估算可以用 Rate of elimination = V<sub>max</sub> &times; C / (K<sub>m</sub> + C)。其中 V<sub>max</sub> 表示 elimination capacity，K<sub>m</sub> 是 rate of elimination 達 V<sub>max</sub> 的一半時的濃度。

### Flow-Dependent Elimination

 * 相較於 Capacity-Limited Elimination，Flow-Dependent Elimination 則是一到器官就被 eliminate。因此限制排除速率的就是藥物流入器官的速度。

## Half-Life

 * Half-Life（t<sub>1/2</sub>）指將藥物將到一半量所需要的時間。
 * t<sub>1/2</sub> = 0.7 &times; V / CL，其中 0.7 是 2 取自然對數的近似值。

### Drug Accumulation

 * 理論上身體內藥物要無限長的時間才會完全消失，因此間隔給藥時藥物會累積。在實行上，以四個 Half-Life 為分界，給藥間隔少於四個 Half-Life 的時候才會測量得到藥物累積。
 * 實際數學計算較複雜，因此常使用 Accumulation Factor 來作為藥物累積指標。
 * Accumulation Factor = 1 / Fraction lost in one dosing interval
 * 或是 = 1 / (1 - Fraction remaining)
 * Accumulation Factor 表示在長時間之後身體中藥物量與單次給藥量的比率。例如每次給藥量為 1，Accumulation factor 為 2，則長時間固定間隔給藥會使得身體中總藥量維持在 1 &times; 2 = 2。

## Bioavailability

Bioavailability 是指經由不同途徑（如口服或注射）到達循環系統的藥物量與給藥量的比率

### Extent of Absorption

 * Extent of Absorption（f）表示藥物吸收進入身體裡的比例
 * 一般認為靜脈注射為 100%
 * 而口服通常較低，因為腸道可能無法 100% 吸收藥物。脂溶性藥物可以通過細胞膜但難以溶解在體液中，親水性雖可以溶解在體液中但卻難以通過細胞膜，另外一些與 p-glycoprotein 相關的藥物會被腸壁上的幫浦不停的打回腸道中。

### First-pass Elimination

 * First-pass Elimination (ER) 表示經肝臟後藥物被移除的比率
 * 在經腸道吸收後，藥物會先由肝門系統到達肝臟。肝臟可以將藥物分解或是分泌到膽汁中而降低 Bioavailability。
 * 肝臟所造成的影響可以表示為 extraction ratio
 * ER = CL<sub>liver</sub> / Q，其中 Q 是單位時間流經肝臟的血量，一般 70kg 的人是 90L/h

綜合上面兩種可能損失藥物 availability 的參數，得到 Systemic Bioavailability，表示為 F，可以由 F = f &times; (1 - ER) 計算

### Rate of Absorption

 * Rate of Absorption 是指吸收速率。
 * 同劑量的藥物若是吸收速度快，能夠很快發生效果（到達 Target concentration，TC）但也比較快消耗完而難以維持藥物濃度。
 * 同劑量的藥物若是吸收速度慢，雖然較慢發生效果，但也能夠維持較久的藥物濃度。

### Extraction ratio and First-Pass Effect

 * 若是藥物容易在通過肝臟就被移除，會導致需要使用大量藥物。
 * 在肝硬化（hepatic cirrhosis）病患做過肝靜脈分流（portosystemic shunt）後流經肝臟血流變少。對容易被肝臟吸收的藥物來說會增加藥物 availability，但對於本來就不會被吸收的藥物來說只會有些微影響。

### Alternative Routes of Administration & First-Pass Effect

由於經過肝臟會有 First-Pass Effect，因此常常會考慮一些其他給藥途徑

 * Oral（口服）：方便但會經過肝臟
 * Topical（外用藥）：可以最大化局部效果並減少全身性影響
 * Transdermal（貼片）：延長藥物吸收時間，如尼古丁貼片
 * Sublingual（舌下錠）：可以避免經過肝臟，因為是直接透過舌下區域靜脈吸收
 * Rectal suppository（肛門塞劑）：與 Sublingual 相同沒有 First-Pass Effect，但較不方便。吸收藥物會直接到 IVC。
 * Inhalation（吸入式）：雖然沒經過肝臟，但肺臟有與腸道類似的排除功能，吸收效果較差

## 小總結一下

 * 從給藥經吸收到循環系統會只剩下原本的 F 倍（Bioavailability），F = f &times; (1 - ER)
 * 經過 Half-Life 後會只剩下一半，Half-Life 可以由 0.7 &times; V / CL 計算
 * Accumulation factor 可以計算在 steady state 時藥物濃度

## Designing a Rational Dosage Regimen

假設存在 Target concentration（TC），也就是能產生期望療效的藥物濃度。在給藥方案中，我們需要計算維持藥物濃度在 TC 的 Maintenance Dose，以及將身體中藥物濃度一開始便提升到 TC 的 Loading Dose。病人一開始先服用 Loading Dose 並在每隔一段間隔時間服用 Maintenance Dose。

### Maintenance Dose

Maintenance Dose 是指要維持藥物在固定濃度所需要的維持劑量。

要維持藥物在一定的濃度，進入身體的要和被排除的一樣多。

因此 Dosing rate = Rate of Elimination

= CL &times; TC

若是採用 Bioavailability 小於 100% 的 Route，例如 oral，

則 Dosing rate<sub>oral</sub> = Dosing rate / F<sub>oral</sub>

若是間歇給藥而不是連續給藥，

則 Maintenance Dose = Dosing rate &times; Dosing interval

值得注意的是 Maintenance Dose 的計算只和 CL 有關，並未包含 V<sub>D</sub> 和 Half-Life。因此雖然平均值都是 TC，但濃度最大與最小值在不同 Dosing interval 下並不相同，如課本 Figure 3-6。

### Loading Dose

當我們計算完 Maintenance Dose，知道如何維持穩定濃度，便可以開始計算多少初始藥量能提升藥物濃度到 TC。

Loading Dose = V<sub>D</sub> &times; TC

Loading Dose 計算上雖然簡單，但實際上藥物在體內散佈的情況相當複雜，並不像理論上一注入藥物便會立刻分散到全身。因此實務上雖然 Loading Dose 計算可能是相當精確的，但 Rate of administration （藥物注入速度）可能更重要，例如抗心律不整藥物 lidocaine 注入過快會造成局部高濃度而幾乎立即產生強烈毒性。
