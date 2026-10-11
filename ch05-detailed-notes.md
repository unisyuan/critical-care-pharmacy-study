# 第 05 章詳細重點整理

依提供的 2024 教材整理。專有名詞與藥名保留英文；原稿有疑義處保留核對註。

## 複習架構：同時評估療效、安全與資源
Pharmacoeconomics 的問題是「付出哪些成本，得到哪些結果」；medication safety 的問題是「流程在哪裡可能造成可避免傷害」。兩者都需先定義比較方案與分析範圍。

### 1. 經濟評估的基本設定
- Perspective 決定納入的成本：醫院、payer、病人及社會的觀點可能得到不同結論。
- 區分 direct medical、direct nonmedical、indirect 與 intangible costs；藥品 acquisition cost 只是成本的一部分。
- 分析需交代時間範圍、資源使用、結果的來源與假設；sensitivity analysis 用來檢查哪些不確定參數會改變結論。

### 2. 四種分析如何辨認
|分析|結果單位|必要前提／重點|
|---|---|---|
|Cost-minimization|比較成本|已可靠確認療效／結果相當|
|Cost-effectiveness|自然臨床單位|如存活、事件避免或住院天數；需解釋增量成本與增量效果|
|Cost-utility|效用調整結果|常使用 QALYs，兼顧存活與生活品質|
|Cost-benefit|成本與效益均以金額表示|需交代如何將效益貨幣化|
- 平均 cost-effectiveness 與 incremental comparison 不同。較便宜不一定較有價值，較有效也不一定符合資源決策。

### 3. Medication Error、ADE 與 ADR
- Medication error 是可預防的用藥流程事件，可以沒有造成傷害；ADE 指藥物相關傷害。
- Preventable ADE 是造成傷害的可預防事件。ADR 與使用過程是否有 error 需分別評估。
- Near miss 提供改善機會，不能只關注已造成傷害的事件。事件分類、嚴重度與因果關係應採一致定義。

### 4. ICU 用藥安全系統
- 風險涵蓋 prescribing、transcribing、dispensing、administration、monitoring 與 handoff。
- 標準濃度、清楚 labeling、合理限制、CPOE／CDS、barcode、藥師審查及團隊溝通是互補措施。
- 科技也會產生 alert fatigue、錯誤選擇與新的 workflow 問題；導入後仍需評估實際風險。
- 自願通報、trigger tools、chart review 與主動 surveillance 的偵測能力不同，通報件數不能直接代表真實發生率。

### 5. Drug Interaction 評估
1. 判定 PK／PD mechanism，確認證據與臨床嚴重度。
2. 評估實際劑量、途徑、時間、腎肝功能與其他合併因素。
3. 選擇避免組合、改藥、調整劑量／時間或加強 monitoring。
4. 告知團隊，並記錄何時重新評估；不能只憑資料庫的 interaction 等級判斷全部病人。

### 6. Formulary Proposal
比較 efficacy、safety、替代療法與完整使用成本；交代預估族群、限制條件、教育、儲存／調劑／給藥風險與監測需求。導入後用 MUE 核對使用是否符合原預期，必要時修訂條件或移除替代藥。


# 分主題詳細條目

## I. PHARMACOECONOMICS — 藥物經濟學

### A. 概述

原稿 PDF 頁：[7](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=7)。

1. Pharmacoeconomics 是描述並分析 drugs、pharmaceutical services 的 costs，以及其對 individuals、health care systems 及／或 society 的 effects。
2. Economic evaluations 辨識、測量並比較 pharmaceutical product 或 service 的 costs 與 consequences。依評估的 disease state／therapy、alternative therapies、perspective（例如 payer、provider、patient、society）及 intended outcome，可能傳達不同結果。
a. 完整 pharmacoeconomic analyses 包括：
i. Cost-benefit。
ii. Cost-effectiveness。
iii. Cost-minimization。
iv. Cost-utility。
b. Humanistic outcomes 或 patient-reported outcome measures 包括：
i. Functional status。
ii. Health status。
iii. Health-related quality of life。
iv. Patient satisfaction。
v. Quality of life。

### B. Costs 類型

原稿 PDF 頁：[7](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=7)。

1. Costs versus charges。
a. 文獻常單獨使用 charges 一詞，但 charges 實際為 costs（亦稱 expenses）加 profit；或特定使用項目的 acquisition cost（例如給予的 medication dose 成本）加提供 service 的估計成本（例如 medication use process 相關的 workflow、personnel）再加 markup。
2. Costs 類型（Table 1）。
#### Table 1. Costs 類型
|Cost 類型|定義|範例|
|---|---|---|
|Direct|與預防、偵測或治療 disease／illness 相關的 costs|以下 medical 與 non-medical costs|
|• Medical|與 medical care 相關的 costs|Fixed：保持固定、不依 use volume 變動，通常不納入 pharmacoeconomic evaluations，例如 rent、salaried workers。Variable：依 use volume 變動，例如 laboratory tests、medications、procedures。|
|• Non-medical|因 disease／illness 產生、但不涉及購買 medical services 的 costs|Child care、specialty diets、transportation。|
|Indirect|與 morbidity／mortality 相關，因 disease／illness 導致 productivity 變動的 costs|因無法工作產生的 costs、因 premature death 損失的 income。|
|Intangible|Disease 的 nonfinancial outcomes 相關 costs|ICU survival 後 posttraumatic stress disorder 的 costs；post-ICU syndrome。|
|Incremental|購買 medical care 額外 benefit／effect 的 additional costs|為控制在 ICU 新發生的 atrial fibrillation，增加額外 medications。|
|Total|包含上述全部 costs|N/A。|
N/A = not applicable。Table 1 為 economic evaluations 使用的 cost 類型摘要。

### C. Pharmacoeconomic Evaluations 的類型（Table 2）

原稿 PDF 頁：[8](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=8)、[9](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=9)。

1. Full economic evaluation 有數種類型；主要差別在於如何測量及評價個人獲得的 benefits。
#### Table 2. Pharmacoeconomic Evaluations 摘要ᵃ
|Economic evaluation|Cost measurement|Consequences／outcomes|Consequences／outcomes 的 measurement／valuation|範例|Challenges|
|---|---|---|---|---|---|
|Cost analysis（partial evaluation）|Monetary|不考慮，故非 full economic evaluation。|不考慮，故非 full economic evaluation。|ARDS 病人 cisatracurium 與 rocuronium 的 cost 比較，不考慮任何 outcome。|與 CMA、CBA、CEA、CUA 相比 challenges 有限。|
|Cost-benefit analysis（CBA）|Total cost of care，以 monetary 表達。|Single 或 multiple effect／outcome，不必是兩 alternatives 共有；effects 轉為 monetary units，使不同 alternatives 可比較。|Monetary units。|Pharmacist-led blood factor prescription 與 standard of care 對醫院 andexanet costs 的比較。|將 consequences 轉為 monetary units。|
|Cost-effectiveness analysis（CEA）|Total cost of care，以 monetary 表達。|所有 alternatives 必須有單一共同關注的 effect／outcome，但達成程度不同；alternative strategies outcomes 不等同，以單向 natural units 測量。|Nonmonetary physical effectiveness units（例如 life-years gained、surrogate endpoint）。|Andexanet 與 4F-PCC 對 bleeding-related mortality 的比較。|確定 decision tree clinical pathway 的 probabilities，以確定 consequences。|
|Cost-minimization analysis（CMA）|Total cost of care，以 monetary 表達。|必須評估；所有 alternatives 共同關注的單一 effect／outcome，已證明 equivalent。|Identical。|因假定 equivalent outcomes，比較藥品與其 biosimilar 的 cost。|證明 consequences identical。|
|Cost-utility analysis（CUA）|Total cost of care，以 monetary 表達。|Single 或 multiple effect／outcome，不必兩 alternatives 共有；effects 轉為 QALYs，使不同 alternatives 可比較。|Utility values 與 QALYs。|比較 andexanet 與 4F-PCC 的 patient outcomes，以 patient utility（QALY）測量。|測量 utilities。|
ᵃ Andexanet = coagulation factor Xa（recombinant）、inactivated-zhzo。
4F-PCC = 4-factor prothrombin complex concentrate；QALY = quality-adjusted life-year。
修改自：Drummond MF, Sculpher MJ, Claxton K, et al. Methods for the Economic Evaluation of Health Care Programmes, 4th ed. Oxford University Press, 2015.

### D. Pharmacoeconomics 的應用

原稿 PDF 頁：[10](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=10)。

1. Formulary management：確定新上市或核准 medications 應納入／排除，以及有／無可能影響 prescribing patterns 的 use criteria。
2. 制訂 clinical guidelines、policies、protocols，在 safety 與 efficacy 情境下促進最 cost-effective、理想的 medication use。
5. Population health analytics（例如使用 pharmacoeconomic analyses，確定 health system 內 EBM treatment decisions）。

## II. DRUG-RELATED EVENTS：MEDICATION ERRORS、ADEs、ADRs、PREVENTABLE ADEs

### A. 概述

原稿 PDF 頁：[10](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=10)。

1. 在美國，每年 770,000 起 injuries／deaths 由 ADRs 引起；每家醫院 ADEs cost burden 超過 $5.6 million。
a. 至多 60% hospital readmissions 可歸因 medication access issues 或 ADEs — 此資料在 EHR data explosion 之前，若 EHR 使用不協調，可能更糟。
b. Severe ADE 增加 hospital LOS 8–12 天，每位病人成本 $16,000–$24,000。
c. 美國 preventable ADEs 的 cost burden 為每家醫院每年 $4.1 million。Medical malpractice lawsuits 經常與 ADEs 相關或由其引起。
2. 病人 critically ill 時，接受 high-risk medication 的機會較高，且因 altered pharmacokinetics、organ failure 對藥品反應改變，ADEs risk 增加。
3. TJC medication management standard 要求醫院回應 actual／potential ADEs、significant ADRs、medication errors。至少需 response、document、report、manage ADEs。Pharmacist 作為 drug expert，應在 prospective order verification 扮演重要角色，必要時 intervention 以預防 ADEs。

### B. Drug-Related Events 的定義

原稿 PDF 頁：[11](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=11)、[12](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=12)、[13](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=13)。

1. Figure 1 摘要 drug-related events。
3. Adverse drug events
a. 因 drug use 造成的 injuries，包括 drug 本身造成的 harm（ADRs、overdoses），以及 drug 使用造成的 harm，包括 dose changes 與停用 drug therapy。
b. 整體而言，ADE 是較廣的詞，描述任何與 medication 相關的 harmful event，包括 overdose 等不適當使用；ADR 則用於 medication 正常使用時發生的 adverse response，包括 harm。
6. Adverse drug reactions
a. 定義
i. WHO 定義 ADRs 為「任何有害且非預期的 drug response，發生於通常用於 disease prophylaxis、diagnosis、therapy，或 modification of physiological function 的 doses」。
ii. Karch 與 Lasagna定義 ADRs 為「任何有害且非預期的 drug response，發生於人類用於 prophylaxis、diagnosis、therapy 的 doses，但排除未達預期目的的 therapeutic failure」。
iii. 兩定義主要差異：WHO 定義將 therapeutic failures 視為 unintended effect 與 ADR；Karch、Lasagna 定義則不包含。兩者均指通常人類使用的 doses，因此排除 overdoses 與超過 normal doses 的 medication errors。
iv. Therapeutic failures 所致 ADRs，若有易取得且詳細的資料紀錄 drug、therapeutic failure，可顯著影響 patient care。
b. 依定義的範例
i. WHO
(a) Clopidogrel 未能預防 ischemic stroke。
(b) Enoxaparin 未能預防 deep vein thrombosis。
(c) Famotidine 未能預防 IV ketorolac-induced gastropathy。
(d) Pantoprazole 未能預防重症病人 stress ulcer 引起的 GI bleeding。
ii. Karch、Lasagna
(a) 用 lorazepam 治療 anxiety，可能造成 sedation。
(1) 此為 unintended adverse reaction；反之，在重症病人用 lorazepam 達到 sedation 為 intended effect，不是 ADR。
(b) 用 diphenhydramine 治療 allergic rhinitis 時，造成 unintended sedation。
(1) 此為 ADR；反之，將 diphenhydramine 作 sedative hypnotic 為 intended effect，不是 ADR。

### C. FDA-Reportable ADEs

原稿 PDF 頁：[13](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=13)。

1. 向 FDA 報告 ADE 時，FDA 將 ADEs 定義為 drugs／devices 相關的 serious adverse events，且「patient outcome 為 death、life-threatening（真正有死亡風險）、hospitalization（初次或延長）、disability（重大、持續、永久）、congenital anomaly，或需要 intervention 預防 permanent impairment／damage」。FDA-reportable serious ADEs 可包括：
a. Acetaminophen-induced hepatotoxicity。
b. Apixaban-induced intracranial hemorrhage。
c. Gentamicin-induced irreversible ototoxicity。
2. FDA 也關注新上市 drugs 的 serious ADE reports，或新／舊 drugs 過去未曾報告的 novel adverse events。
a. FAERS database 設計為 medications、biologics 的 postmarketing surveillance tool。其他 therapies，例如 medical devices，有各自 reporting system。
b. CDC 與 FDA 共同贊助 VAERS，聚焦辨識美國核准 vaccines 相關 adverse events 的 potential signals。
3. FAERS、VAERS 為 postmarketing surveillance systems，其 limitations 包含：
a. Adverse event 缺乏確定性（可能未驗證）。
b. Underreporting。
c. 較不嚴重 adverse events 可能更少報告。
d. 提供的 detail 可能不足。

### D. 設計 ADE Reporting Program

原稿 PDF 頁：[14](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=14)、[15](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=15)。

1. 完整 ADE program 應有 policy、procedure，包含 ADE detection、reporting、management、surveillance、education guidelines。Appendix 1 為 ADE reporting form。
9. ADE committee 應：
a. 指定哪些 ADEs 可預防，說明為何可預防，並確定可能 preventive measures。
b. 確定哪些 ADEs 向 FDA 或 manufacturer 報告。
c. 報告誰偵測、誰報告、紀錄、處置 ADEs 的資料。
d. 依 drug／drug class 及 specialty units 提供 trending data。
e. 與醫院自身過去年份 ADEs benchmarking，並與 biomedical literature 發表的其他醫院資料比較。Total ADE data 可按以下報告：
i. ADEs 總數。
ii. 每次 admission 的 ADEs。
iii. 每位 patient 的 ADEs。
iv. 每 patient-days 的 ADEs。
v. 每 doses dispensed 的 ADEs。
vi. 每 doses administered 的 ADEs。
10. 常見報告方法以 total admissions 為分母，可接受 benchmark 2.5%–10%（例如 10,000 admissions 的醫院報告 1000 ADEs，即 10% ADE reporting rate）。ADE benchmarks 難以確定，因多項 variables 影響 reporting methods，例如 facility 或 reporter 使用的 ADE definition、可報告的 clinical pharmacists 人數、reporting systems 的 vigilance 與 emphasis、以 technology 或 reports 增加 reporting。

### E. 在病人 Medical Record 紀錄 ADRs 與 ADEs

原稿 PDF 頁：[15](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=15)。

1. Allergy data 一律紀錄於 medical record，patient profile 必須包含。最好紀錄引起 allergy 的特定 medication、reaction 類型、發生時間。
1. Mild ADR／ADE：提高 patient monitoring 需求，可伴隨或不伴隨 vital signs 變化，但最終無 patient harm；或任何導致增加 laboratory monitoring 的 adverse event。
3. Severe ADR／ADE：導致 patient harm、prolonged hospitalization、轉至較高 care level、permanent organ damage（例如 irreversible hepatotoxicity、renal failure），或 death，且 ADE causality nomogram score 為 probable。
ᵃ 另有其他 ADE severity scales。
ADE = adverse drug event；ADR = adverse drug reaction；BP = blood pressure。

### F. Medication Error 與 ADR／ADE Surveillance 方法

原稿 PDF 頁：[16](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=16)、[17](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=17)。

1. ADEs 可 prospective、retrospective detection。
a. Pharmacists 可在每日 patient care rounds 主動偵測，或 medication histories、transitions of care（例如 ICU 轉 step-down）、discharge counseling 時與病人溝通發現。
b. CDS 範例為 automated triggers，用於 prospective events surveillance（事件發生前）。也可透過 medical record reviews、medication histories、chart reviews retrospective detection（事件後，故 intervention 機會有限）。
3. Retrospective incident voluntary reporting 是所有 health care professionals 的 ethical obligation。
a. 多數機構以 voluntary reporting 為 event identification 主要來源，但 events 嚴重 underreported。
b. Safety pharmacists 通常負責彙整資料，由機構 ADE committee 審查 aggregate reports、確定可能 prevention methods。此為 retrospective evaluation，因 events 通常在有可用時間時評估，往往在病人出院時。若可即時評估，也可為 prospective method。
c. Trigger／tracer drugs。
i. EHR 內 CDS system 可利用 trigger／tracer drugs 偵測 ADEs；兩詞同義。這些 drugs 通常開立以治療 ADEs，例如 antidotes、physiologic antagonists、gastric decontamination agents，觸發 targeted medical record review。範例見 Box 2。
ii. 可為 CDS system 設定 tracer drugs list，當 prescribers 開立時，詢問是否為 ADE，若是，發生何種 ADE。Clinical pharmacist 可接著 report、manage potential ADE。
iii. 優點之一為紀錄可能未報告的 ADEs，特別是 clinical pharmacist 不在 unit／daily rounds 時，也允許更多 physician-reported ADEs。
d. Therapeutic drug concentration、abnormal laboratory value monitoring 是另一 ADE detection 來源。Pharmacy 可設計 daily reports，包括所有 abnormal drug serum concentrations，如 phenytoin、digoxin、lithium、vancomycin、aminoglycosides，或其他 laboratory monitoring values（例如 lisinopril、potassium）。Clinical pharmacist 可對所有 supratherapeutic concentrations、laboratory abnormalities 執行 ADE targeted medical record review。這些為基本 CDS functions，以 medications、laboratory values 作 alerts knowledge；目前也使用更 advanced、「smarter」alerts，含 risk scoring-based approaches，協助排定 pharmacist reviews 優先順序。

## III. 2017 SCCM CLINICAL PRACTICE GUIDELINE：SAFE MEDICATION USE IN THE ICU

### A. Guideline 的架構

原稿 PDF 頁：[19](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=19)。

1. 2017 年制訂，literature searches 至 2015 年底，聚焦 34 個 PICO（population／problem／patient、intervention／indicator、control／comparator／comparison、outcomes）questions，包括 adult、pediatric ICU patient data。
2. 首個處理 ICU safe medication use 的 clinical guideline。指出許多領域仍需 rigorous research 指導 practice。
4. Recommendations 依 GRADE system（quality of evidence：A = high 至 D = very low；strength：0 = no recommendation、1 = strong、2 = weak）。

### B. Environment and Patient 重點

原稿 PDF 頁：[19](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=19)。

1. ICU 病人的 ADE risk factors 不同，medication errors severity 高於 general care／non-ICU 病人（皆 grade C）。
2. Guidelines 建議以 educational efforts 降低 ICU medication errors（2C）。
3. 因缺乏資料，對向病人及／或家屬 disclosure medication errors／ADEs 沒有 recommendation；但 National Quality Forum 建議如此。

### C. Medication Use Process 重點

原稿 PDF 頁：[19](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=19)、[20](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=20)。

1. 四階段：prescribing、dispensing、administration、monitoring。
2. Prescribing
a. Guidelines 建議實施 CPOE，降低 medication errors 與 preventable ADEs（2B）。部分資料支持 errors reduction，但 evidence 矛盾：omission errors 降低，duplicate order errors 增加。
b. Guidelines 建議 CDS systems，降低 medication errors、ADEs 數量（2C）。
i. CDS systems 是提升 clinician decision-making 的 tools（例如 allergy、drug-drug interaction、dosing recommendations）。
ii. Trigger-initiated CDS alerts 有 alert fatigue 疑慮，因缺乏 patient-specific considerations（例如 ICU level of care），需平衡 sensitivity、specificity。
c. Guidelines 建議 protocols／bundles，降低 medication errors／ADEs（2B）。
d. 對 ICU 或 transitions of care 使用 medication reconciliation 降低 medication errors、ADEs，未提供 recommendation。
4. Administration
a. Guidelines 建議 ICU 使用 BCMA 降低 medication errors 及／或 ADEs（2C）。
i. Benefit evidence 矛盾，但資料多數提示 errors、potential ADEs 降低。
ii. BCMA 限制之一為 workarounds 降低 effectiveness。
b. Guidelines 建議 smart IV infusion pumps，降低 errors、ADEs rate（2C）。
i. Guardrails 使用及評估的 error 類型，evidence 矛盾。
ii. Smart pumps 有 auditory alarm fatigue 疑慮，尤其 ICU 有其他 auditory alarms。

### D. Patient Safety Surveillance Systems 重點

原稿 PDF 頁：[20](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=20)。

1. Guidelines 強烈建議 direct observation 作 active medication surveillance system，辨識 errors（1A）。
2. Guidelines 建議 nontargeted chart review 相較 voluntary reporting 可增加 ADEs identified，但 resource-intensive（2C）。
3. Guidelines 建議 targeted chart review 相較 voluntary reporting 提升 ADE detection（2B）；策略包括僅評估 medical record 特定部分（例如 ICU discharge note）或 trigger medications。

## IV. DRUG INTERACTION SURVEILLANCE AND PREVENTION

### A. 定義

原稿 PDF 頁：[21](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=21)。

1. 某 drug effects 可被另一 substance（例如 medication、dietary）改變；可能 intentional、clinically insignificant，或 harmful、potentially life-threatening。
2. Drug-related toxicity 可能可預防，也可能需 therapeutic intervention（例如 monitoring、停用 medication）。
B. 有 documented drug interaction 與 known outcomes，依 clinical context 可視為 medication error、preventable ADE 或 ADR。
C. Drug infusion compatibility interactions（例如 Y-site）在 ICU 更常見，因 prolonged infusions 的可能性較高。
D. Drug interaction databases 包括 Lexicomp、IBM Micromedex、Epocrates、Clinical Pharmacology、Hansten and Horn’s Drug Interaction Analysis and Management、Stockley’s Drug Interactions、PDR Drug Interactions。許多 EHRs 包含 Medi-Span、First Databank。
1. 多數 compilation databases 有 drug interaction software，pharmacist 可提供 drug list，database 提供 interaction type、severity。值得注意，databases 間 severity agreement 估計 <50%。

### E. 避免／處置 Drug Interactions 的 Safety Measures

原稿 PDF 頁：[21](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=21)。

1. Pharmacist review、validation。
a. Pharmacists 在 pharmacology、drug interactions 受高度訓練，應對 drug interactions 運用 advanced analysis、clinical qualification／management。
b. 限制包括病人所有 medications 不一定由同一 pharmacy 調劑，以及 EHR 可擷取、用以判斷 drug-drug interactions 存在及 clinical relevance 的 potential data 不足。
2. 使用具 drug interaction detection CDS alerts 的 EHRs。
a. 範例：passive pop-up warnings／alerts、active alerts with soft stops（例如 documented nausea allergy）、active alerts with hard stops（例如 documented anaphylaxis allergy）。
b. Order verification 時可能向 prescriber／pharmacist 提供高頻率 alerts，導致 desensitization（alert fatigue）。
c. 儘管 CDS 有 potential benefits，ICU population override 常見，依 alert type 約 80%。ICU 不適當 override CDS alerts 與 patient harm risk 增加相關。
d. 可用 severity 或 interaction tiering 作 alert selection criterion，減少 alerts number，以管理 drug-drug interaction alert fatigue。
3. 以 education 預防 drug interactions（例如 lectures、patient care rounds）。

### F. 如何評估 Drug Interaction Cases

原稿 PDF 頁：[21](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=21)、[22](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=22)。

1. Causation assessment 包含 temporal relationship、object 與 precipitant drug pharmacologic properties、patient factors／disease states、其他 drugs 可能 contribution，以及可行時 positive dechallenge。Temporal sequence 為確定 cause 的關鍵要素。
2. Naranjo 等 ADE nomograms 設計用於 ADEs，非 drug-drug interactions，因此不應用於評估 interaction cases。
3. Drug interaction probability scale 可確定 drug-drug interaction causation，包括特定病人的 adverse outcomes（Appendix 2）。
a. 此 scale 模仿 Naranjo ADR probability scale；評估 10 個 interaction-related questions，以 yes、no、unknown、not available 回答，計分並加總。總分決定 interaction probability：
i. Highly probable：>8。
ii. Probable：5–8。
iii. Possible：2–4。
iv. Doubtful：≤2。〔原文此處 ≤2 與 possible 的 2 重疊；附錄原量表為 <2，兩者保留其各自原文。〕
b. Evaluator 必須全面了解 object、precipitator drugs 的 pharmacologic properties，尤其 pharmacokinetics、pharmacodynamics、mechanisms of drug action／interaction，可能限制其使用。

## V. FORMULARY PROPOSAL

原稿 PDF 頁：[22](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=22)。

A. Drug formulary 應完整，包含 patient care 所需所有 medications。
B. TJC medication management standard 要求醫院制訂並核准選擇 medications 納入 formulary 的 criteria。

### C. 最少應包含：

原稿 PDF 頁：[22](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=22)、[23](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=23)。

1. Indications（FDA label-approved、off-label）。
#### Box 3. Drug Evaluation Monograph 要素
- Brand name。
- Generic name。
- Manufacturer。
- Therapeutic classification。
- FDA status：Prescription、nonprescription、controlled substance。
- 與任何其他 FDA label-approved medications 的 look-alike／sound-alike names。
- 與 formulary 中任何其他 FDA label-approved medications 的 look-alike／sound-alike names。
- FDA label approval 日期。
- FDA rank（priority、standard）。
- FDA label-approved indication。
- Unlabeled indications。
- Potential unlabeled uses。
- 不在 formulary 的 similar agents。
- 在 formulary 的 similar agents。
- 如何依現有 national guidelines 使用 drug。
- 如何依 hospital guidelines、protocols、pathways 使用 drug。
- Dosage form。
- Dosage strength。
- Mechanism of action。
- Absorption。
- Distribution。
- Metabolism。
- Excretion。
- Common ADRs。
- Significant、life-threatening ADRs／ADEs。
- Boxed warnings。
- Precautions。
- Contraindications。
- Drug-drug interactions。
- Drug-food interactions。
- Drug-laboratory test interactions。
- IV incompatibilities。
- IV compatibilities。
- Pregnancy category。
- Breastfeeding 期間使用。
- Dosage regimen recommendations。
- Special populations dosage regimen recommendations，例如 children、older adults、renal／hepatic impairment、dialysis 病人。
- Administration routes 及／或 limitations。
- Special administration techniques（prescriber certification、smart pump limitations）。
- 可用 preparations。
- Storage、stability considerations。
- Availability concerns（specialty pharmacy restrictions）。
- 相關 clinical trials 的 critical review，包含重要 critique、conclusions。
- Similar／alternative agents comparison trials 的 critical review。
- Cost analysis，包括 annual projected costs。
- Economic evaluations。
- 可用 pharmacoeconomic analyses。
- Institution-specific budget impact analysis。
- Third-party payers reimbursement。
- 此 agent 是否有 severe medication errors／sentinel events？
- 是否需特定 storage circumstances，避免 errors／mix-ups？
- 是否需 tall man lettering、precautionary、high-risk labeling，避免 potential errors／mix-ups？
- Manufacturer labeling 是否清楚、安全且適合 dispensing？
- 是否有 abuse potential？
- Patient education requirements。
- 此 agent 是否替代現有 agent，是否需 formulary deletion？
- 應／不應納入 formulary 的理由；addition recommendation。
- References。
ADE = adverse drug event；ADR = adverse drug reaction；IV = intravenous(ly)。
F. Box 3 列出 drug 核准納入 hospital formulary 前，應審查的 monograph 要素。

### G. 應以完整 literature review 確定 drug efficacy、toxicity profile，以較強 levels of evidence 指導是否加入 formulary 的 decisions。

原稿 PDF 頁：[24](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=24)。

1. Prospective double-blind RCTs 應比 retrospective cohort、case-control studies 權重更高；但應對所有 studies 類型的 limitations critical appraisal，以了解 study strength。
2. 依 included studies number、criteria，也可考慮 meta-analyses。
3. 只有無其他 evidence 時才使用 case reports。
H. 制訂 monograph 的 pharmacists 必須熟悉 drug literature evaluation、pharmacoeconomics。
I. Drug evaluations 應包含 evidence references，並註明 opinion statements。

### J. Internal prescribing data 也可用於 formulary decisions，例如：

原稿 PDF 頁：[24](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=24)。

1. 特定時間 drug quantity。
2. Medication use evaluation data。
4. Medication error data。
K. 新 drugs approval trials 通常 sample size、ADE detection 能力有限（尤其 long-term effects），因此可行時，應先觀察新 drugs safety profiles 再考慮加入 formulary。例如有些 drugs 可能以 1：20,000 病人的 rate 造成 hepatic failure 等 life-threatening toxicity，需 >100,000 postmarketing patient exposures 才產生 toxicity signal。

### L. Drugs 可不限制使用納入 formulary，也可附 restrictions，例如：

原稿 PDF 頁：[24](https://unisyuan.github.io/critical-care-pharmacy-study/pdf/ch05.pdf#page=24)。

1. 限符合 use criteria 的特定 population（例如 monitoring level、已嘗試其他 therapies）。
2. 限 ADE（例如 hepatotoxicity）risk 低的特定 population。
3. 限特定 providers。
M. Drug 經 formulary approval 後，應定期進行 MUE 或 use reviews（包括 institutional guidelines compliance）、cost、safety、efficacy 評估；最好 3–6 個月內及一年再評估。目標為確定 drug effectiveness，即 RCT 之外 real-world use，不同於納入 formulary 前評估的 efficacy。需較早 re-evaluation（例如 3 個月）的 approvals 包括 efficacy data 很有限、擔憂不遵守 formulary restrictions、safety events high risk、cost 很高的 medications。
N. 同一 class 的所有 formulary drugs 應年度評估；prescribing information 有重大變化、landmark trial／publication 影響使用，或同 class 有新 FDA label-approved agents 時，應更頻繁評估。評估通常促使更新、修改 current use。
