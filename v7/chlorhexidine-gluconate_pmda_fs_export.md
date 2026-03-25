# PMDA FS Question Export — chlorhexidine gluconate

Generated at: 2026-03-25T08:22:35
Question bank: E:\PharmAppDev\database\PMDA\pmda_question_bank_v7\PMDA_RAG_Reusable_Question_Bank.md
Index dir: E:\PharmAppDev\database\PMDA\pmda_fs_index
Questions completed: 114

## Phase summaries

```json
{
  "non_ollama": {
    "phase": "non_ollama",
    "count": 111,
    "success": 111,
    "failed": 0,
    "elapsed_seconds_sum": 49999.748,
    "elapsed_seconds_avg": 450.4482,
    "retrieval_seconds_sum": 8521.0097,
    "generation_seconds_sum": 0.003,
    "estimated_context_tokens_sum": 141786,
    "estimated_prompt_tokens_sum": 150703,
    "estimated_answer_tokens_sum": 130477
  },
  "ollama": {
    "phase": "ollama",
    "count": 3,
    "success": 3,
    "failed": 0,
    "elapsed_seconds_sum": 498.3794,
    "elapsed_seconds_avg": 166.1265,
    "retrieval_seconds_sum": 197.1659,
    "generation_seconds_sum": 301.2092,
    "estimated_context_tokens_sum": 1205,
    "estimated_prompt_tokens_sum": 1450,
    "estimated_answer_tokens_sum": 814
  },
  "all": {
    "count": 114,
    "success": 114,
    "failed": 0,
    "elapsed_seconds_sum": 50498.1274
  }
}
```

## 1. What are the key warnings and contraindications?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > Usage pattern
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:52:43
- Finished: 2026-03-25T05:53:22
- Elapsed seconds: 38.9334
- Retrieval seconds: 38.9348
- Generation seconds: 0.0
- Estimated prompt tokens: 1074
- Estimated answer tokens: 1068

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the key warnings and contraindications?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the key warnings and contraindications?
Drug filter: chlorhexidine gluconate
Section hints: contraindication, warning

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=7.0359
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7215
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6784
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 28 | section=contraindication | score=6.6687
  22
13.Overdose
Not applicable

14. Application notes
(1) Administration route: Do not use for any purpose other than hand disinfection. (2) When using: Be careful as there are reports that chemical skin burns may occur if the solution is in contact with the skin for a long period of time.

15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

16.Others
Nothing in particular
- chlorhexidine gluconate | interview_form | page 18 | section=contraindication | score=6.6405
  7. Interaction
(1) Concomitant use contraindications and reasons not applicable (2) Precautions for concomitant use and reasons not applicable
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.6062
  - 13 -
14. Application notes
(1) Administration route Do not use for any purpose other than hand disinfection. (2) During use
1) Be careful not to accidentally get it in your eyes while using this drug. If it comes into contact with your eyes, immediately rinse thoroughly with water.
to do.
2) Be careful as there are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
to do.
3) Be careful of fire as it is flammable and explosive.
15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluco

Sources:
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 28
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 19
```

## 2. What are the contraindications?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:52:43
- Finished: 2026-03-25T05:53:57
- Elapsed seconds: 73.9822
- Retrieval seconds: 35.0547
- Generation seconds: 0.0
- Estimated prompt tokens: 1208
- Estimated answer tokens: 1131

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the contraindications?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the contraindications?
Drug filter: chlorhexidine gluconate
Section hints: contraindication

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=7.0832
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | interview_form | page 28 | section=contraindication | score=6.7252
  22
13.Overdose
Not applicable

14. Application notes
(1) Administration route: Do not use for any purpose other than hand disinfection. (2) When using: Be careful as there are reports that chemical skin burns may occur if the solution is in contact with the skin for a long period of time.

15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

16.Others
Nothing in particular
- chlorhexidine gluconate | interview_form | page 18 | section=contraindication | score=6.7148
  7. Interaction
(1) Concomitant use contraindications and reasons not applicable (2) Precautions for concomitant use and reasons not applicable
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.6530
  - 13 -
14. Application notes
(1) Administration route Do not use for any purpose other than hand disinfection. (2) During use
1) Be careful not to accidentally get it in your eyes while using this drug. If it comes into contact with your eyes, immediately rinse thoroughly with water.
to do.
2) Be careful as there are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
to do.
3) Be careful of fire as it is flammable and explosive.
15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluco
- Chlorhexidine Gluconate | smpc_label | page 1 | section=contraindication | score=6.6274
  0.5%
エタノール溶液(2分以上)手術室・病室・家具・器具・物品などの消毒
0.05%水溶液
(本剤の100倍希釈) 0.05%水溶液
14.1.2 創傷部位に使用する希釈水溶液は、調製後必ず滅菌処理す
ること。
14.1.3 本剤は、常水や生理食塩液等に含まれる陰イオンにより難
溶性の塩を生成することがあるので、希釈水溶液を調製する際には、新鮮な蒸留水を使用することが望ましい。
14.1.4 手洗い等に使用する本剤の希釈液は、少なくとも毎日新し
い溶液と取換えること。
14.1.5 本剤の希釈水溶液は安定であるが、高温に長時間保つこと
は避けること。高圧蒸気滅菌を行う場合は115°C 30分、121°C 20
分、126°C 15分で滅菌処理することができる。
14.1.6 本剤を取扱う容器類は常に清浄なものを使用すること。
14.1.7 本剤の希釈水溶液は調製後直ちに使用すること。やむを得
ず消毒用綿球等に長時間使用する希釈水溶液は微生物汚染を防止するために、希釈水溶液にアルコールを添加することが望ましい。エタノールの場合7vol%以上、イソプロパノールの場合4vol%以上になるように添加する。
14.1.8 器具類の保存に使用する場合は、腐食を防止するために、
高濃度希釈液(目安として本液0.3%以上)を使用し、微生物汚染を防止するために、希釈水溶液にアルコールを添加することが望
ましい。(アルコール添加量は上記14.1.7と同じ)本液は毎週新
しい溶液と取換えること。
14.1.9 綿球・ガーゼ等は本剤を吸着するので、これらを希釈液に
浸漬して用いる場合には、有効濃度
- chlorhexidine gluconate | interview_form | page 20 | section=contraindication | score=6.6225
  15

14. Application notes
(1) Administration Route Do not use for any purpose other than disinfecting hands and skin. (2) During use
1) Please note that repeated use may cause skin irritation due to degreasing.
2) Organic substances such as serum and pus reduce the bactericidal action, so if these are present,
Wash thoroughly before use.
3) Since soap weakens the bactericidal effect of this agent, be sure to thoroughly wash off the soap used for preliminary cleaning.
before use.
4) Be careful of fire as it is flammable and explosive.
5) There are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
So be careful.
15.Other notes
I

Sources:
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / interview_form / page 28
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 19
- Chlorhexidine Gluconate / smpc_label / page 1
- chlorhexidine gluconate / interview_form / page 20
```

## 3. What are the approved indications and dosage instructions?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:52:43
- Finished: 2026-03-25T05:54:40
- Elapsed seconds: 116.7739
- Retrieval seconds: 42.7909
- Generation seconds: 0.0
- Estimated prompt tokens: 1562
- Estimated answer tokens: 1302

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the approved indications and dosage instructions?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the approved indications and dosage instructions?
Drug filter: chlorhexidine gluconate
Section hints: dosage, indication

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=7.0782
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0665
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0485
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0382
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0088
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0025
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 4. What are the important precautions before using this drug?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:52:43
- Finished: 2026-03-25T05:56:52
- Elapsed seconds: 249.033
- Retrieval seconds: 132.269
- Generation seconds: 0.0
- Estimated prompt tokens: 1330
- Estimated answer tokens: 1194

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the important precautions before using this drug?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the important precautions before using this drug?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7641
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.4643
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.2964
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.1875
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.1813
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.1744
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 26
```

## 5. Before using this drug, what should patients be careful about?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:52:43
- Finished: 2026-03-25T05:58:56
- Elapsed seconds: 372.8305
- Retrieval seconds: 123.8006
- Generation seconds: 0.0
- Estimated prompt tokens: 1394
- Estimated answer tokens: 1184

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Before using this drug, what should patients be careful about?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Before using this drug, what should patients be careful about?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.6790
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6709
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.6674
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6495
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6368
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=5.6296
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 23
```

## 6. Who should not use this drug?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:52:43
- Finished: 2026-03-25T06:01:24
- Elapsed seconds: 520.822
- Retrieval seconds: 147.9889
- Generation seconds: 0.0001
- Estimated prompt tokens: 1512
- Estimated answer tokens: 1306

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Who should not use this drug?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Who should not use this drug?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide
Section hints: contraindication, dosage

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.8609
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.8409
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.8285
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=6.8101
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.7978
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.7899
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 7. What should patients avoid while taking this drug?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:53:22
- Finished: 2026-03-25T06:04:21
- Elapsed seconds: 658.7407
- Retrieval seconds: 176.8359
- Generation seconds: 0.0
- Estimated prompt tokens: 1392
- Estimated answer tokens: 1181

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What should patients avoid while taking this drug?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What should patients avoid while taking this drug?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.6910
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6826
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.6806
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6607
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6477
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=5.6431
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 23
```

## 8. What are the major adverse reactions and serious adverse events?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:53:57
- Finished: 2026-03-25T06:05:11
- Elapsed seconds: 673.9816
- Retrieval seconds: 50.2947
- Generation seconds: 0.0001
- Estimated prompt tokens: 1408
- Estimated answer tokens: 1238

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the major adverse reactions and serious adverse events?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the major adverse reactions and serious adverse events?
Drug filter: chlorhexidine gluconate
Section hints: adverse_event

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=adverse_event | score=7.0219
  Medium Contains 0.1g of chlorhexidine gluconate (
0.1w/v%)

:1) It has been diluted so it can be used as is. [Prevention of measurement/dilution errors] Contains 0.5g of chlorhexidine gluconate (medium)
0.5w/v%) Since it uses a volume-reducing bottle, it can be folded to reduce the volume and be disposed of, reducing disposal costs.
Ru. (12) Shock and anaphylaxis may occur as serious side effects.
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=7.0194
  1
I. Items related to overview
1. Development history
This agent is a topical disinfectant containing chlorhexidine gluconate as an active ingredient.

“Yakuhan” is a 20% chlorhexidine gluconate solution developed by Yakuhan Pharmaceutical Co., Ltd.
Established standards and test methods, conducted stability tests and bactericidal power tests, and approved on February 24, 2005.
Sales began on June 13, 2005.

Nichiiko Co., Ltd. began selling this drug on April 16, 2012.

2. Therapeutic and pharmaceutical properties of the product
(1) This agent is a topical disinfectant containing 19.0~21.0w/v% of chlorhexidine gluconate.
Ru.
(2) The packaging standard is a 500mL rectangular volume-reducing c
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=6.9696
  has been done. Additionally, the ``Guidelines for Standard Dialysis Operations and Infection Prevention in Dialysis Facilities (Sixth Edition)'' recommends using alcohol containing 1% or more of chlorhexidine gluconate to disinfect the skin at the puncture site, when inserting a dialysis catheter, and at the skin exit after insertion at the start of dialysis. As a result, there is an increasing demand for alcohol-containing preparations with 1% chlorhexidine gluconate as the active ingredient. ``Nipro'' is a formulation in which non-woven fabric is impregnated with a drug solution containing 1% chlorhexidine gluconate in ethanol as an active ingredient.``Nipro'' is a generic drug product wit
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=6.8978
  2. Therapeutic and pharmaceutical properties of the product
(1) A preparation containing 1% chlorhexidine gluconate and ethanol, which has an antimicrobial spectrum against various bacteria (excluding bacterial spores) including gram-negative bacteria, gram-positive bacteria, and acid-fast bacteria, and fungi. (2) As a quick-drying hand rub, it exhibits a bactericidal effect immediately after disinfection and a long-lasting effect, making it suitable for hand disinfection during surgery. (3) In consideration of reducing hand roughness, sodium hyaluronate and sodium d1-pyrrolidonecarboxylate liquid are added as moisturizing ingredients. (4) A low-viscosity lotion type designed to prevent spil
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=6.8659
  In September 2007, ``Hibis Club'' was introduced as ``Hibis Club Disinfectant'' as part of measures to prevent medical accidents.
4%" approval and the name was changed.
2. Therapeutic properties of the product
(1) This agent shows almost the same antibacterial effect as the Japanese Pharmacopoeia chlorhexidine gluconate solution. (See section VI-2-(2) Test results supporting drug efficacy.) (2) It has a sterilizing effect through foaming and cleaning effects, and is recognized to be fast-acting and long-lasting. (Refer to "VI-2-(2) Test results supporting drug efficacy" and "VI-2-(3) Time of onset and duration of action") (3) It is easy to use as it does not require preparation at the time o
- chlorhexidine gluconate | interview_form | page 24 | section=adverse_event | score=6.8242
  - 19 -

9. Administration to the elderly

10.Pregnant women, delivery women, and lactating women
administration to etc.

11.Administration to children, etc.

12.Clinical test results
influence

13.Overdose

14. Application notes

15.Other notes

16.Others

serious side effects
Shock (frequency unknown), anaphylaxis (frequency unknown):
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pressure, hives, difficulty breathing, etc. occur, immediately discontinue use and take appropriate measures.

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable.

1) Route of administration
Do not use for any purpose other than hand disinfecti

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 24
```

## 9. Are there precautions for pediatric patients, elderly patients, pregnancy, or breastfeeding?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:54:40
- Finished: 2026-03-25T06:08:09
- Elapsed seconds: 809.4957
- Retrieval seconds: 178.3043
- Generation seconds: 0.0
- Estimated prompt tokens: 1220
- Estimated answer tokens: 1136

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there precautions for pediatric patients, elderly patients, pregnancy, or breastfeeding?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there precautions for pediatric patients, elderly patients, pregnancy, or breastfeeding?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide
Section hints: warning, pregnancy

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=6.7493
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7012
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 11 | section=pregnancy | score=6.4888
  14. Application and drug delivery
Precautions Application Precautions (1) Route of Administration: Use only for external use. (2) When in use
1) Be careful not to accidentally get it in your eyes while using this drug. If it gets into your eyes
If this occurs, immediately rinse thoroughly with water.
2) When using over a wide area or for a long period of time, be careful not to inhale vapor.
3) Proteins such as serum and pus may coagulate and may not penetrate inside.
When using medical instruments etc. that have these on them, wash them thoroughly before use.
4) If used repeatedly on the same area (skin surface), it may cause skin roughness due to degreasing, etc.
Please be careful as this
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.3998
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 12 | section=pregnancy | score=6.3872
  (3) Reproductive and developmental toxicity test 17) Fetal test, genetic variability
Chlorhexidine gluconate for 10 days from the 6th to 15th gestation day of pregnant rats.
10, 25, and 50 mg/kg were administered orally. Regarding the mother body, only the maximum amount group
Slight irritation sensitivity and suppression of weight gain were observed, but no abnormalities were observed in the number of implantations, number of absorbed embryos, number of fetuses, sex ratio, abnormal external appearance, or skeletal variation.

(4) Other special toxicities 18) Hemolytic and tissue-damaging The minimum tissue-damaging concentration of chlorhexidine gluconate in chicken fetal heart was 1w/v%.
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=6.3778
  No particular abnormality was observed except for an increase in giant cells in the nodes19). (3) Reproductive and developmental toxicity test Reproductive test

Pregnant rats received 10, 25, and 50 mg/kg/day of chlorhexidine gluconate for 10 days from the 6th to 15th gestation day.

When administered orally, slight hypersensitivity and suppression of weight gain were observed in the mother at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton19). (4) Other special toxicities

1) Tissue damage

The minimum tissue-damaging concentration of chlorhexidine gluconate in chic

Sources:
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 12
- chlorhexidine gluconate / interview_form / page 20
```

## 10. Show the pages that discuss warnings, contraindications, and precautions.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > A. Core label / patient guide questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:56:52
- Finished: 2026-03-25T06:40:25
- Elapsed seconds: 2612.775
- Retrieval seconds: 1969.8412
- Generation seconds: 0.0001
- Estimated prompt tokens: 1388
- Estimated answer tokens: 1283

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show the pages that discuss warnings, contraindications, and precautions." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show the pages that discuss warnings, contraindications, and precautions.
Drug filter: chlorhexidine gluconate
Section hints: contraindication, warning

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=7.0286
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9585
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 28 | section=contraindication | score=6.9008
  22
13.Overdose
Not applicable

14. Application notes
(1) Administration route: Do not use for any purpose other than hand disinfection. (2) When using: Be careful as there are reports that chemical skin burns may occur if the solution is in contact with the skin for a long period of time.

15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

16.Others
Nothing in particular
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.8414
  - 13 -
14. Application notes
(1) Administration route Do not use for any purpose other than hand disinfection. (2) During use
1) Be careful not to accidentally get it in your eyes while using this drug. If it comes into contact with your eyes, immediately rinse thoroughly with water.
to do.
2) Be careful as there are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
to do.
3) Be careful of fire as it is flammable and explosive.
15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluco
- chlorhexidine gluconate | interview_form | page 20 | section=contraindication | score=6.8164
  15

14. Application notes
(1) Administration Route Do not use for any purpose other than disinfecting hands and skin. (2) During use
1) Please note that repeated use may cause skin irritation due to degreasing.
2) Organic substances such as serum and pus reduce the bactericidal action, so if these are present,
Wash thoroughly before use.
3) Since soap weakens the bactericidal effect of this agent, be sure to thoroughly wash off the soap used for preliminary cleaning.
before use.
4) Be careful of fire as it is flammable and explosive.
5) There are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
So be careful.
15.Other notes
I
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.7879
  14

11. Application notes
14. Application notes
14.1 Precautions when using drugs
14.1.1 This product should not be diluted and should be used as a undiluted solution.
14.1.2 Do not administer orally. If swallowed by mistake, wash the stomach with milk, raw eggs, gelatin, etc.
Take appropriate measures such as
14.1.3 Do not use for any purpose other than hand disinfection.
14.1.4 Take care to avoid contact with eyes. In case of contact with eyes, rinse thoroughly with water immediately.
14.1.5 There are reports of chemical skin burns caused by prolonged skin contact in solution form.
So be careful.
14.2 Precautions after using drugs
If white cloth coated with this agent is bleached with a ch

Sources:
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 28
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 20
- chlorhexidine gluconate / interview_form / page 19
```

## 11. What are the active ingredient and excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T05:58:56
- Finished: 2026-03-25T06:41:29
- Elapsed seconds: 2553.1092
- Retrieval seconds: 64.1291
- Generation seconds: 0.0001
- Estimated prompt tokens: 1212
- Estimated answer tokens: 1044

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the active ingredient and excipients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the active ingredient and excipients?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9599
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 11 | section=general | score=5.9554
  5
4. Quantification method of active ingredients
Based on the Japanese drug ``chlorhexidine gluconate solution.''
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9331
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.9124
  - 4 -
3. Confirmation test for active ingredients
law
4. Quantification method of active ingredients
According to the Japanese Bureau of Medicine's "Chlorhexidine Gluconate Solution Confirmation Test." Based on the ``Chlorhexidine gluconate liquid quantitative method'' of the Japanese Bureau.
- chlorhexidine gluconate | interview_form | page 8 | section=general | score=5.8846
  II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine GLUCONATE SOLUTION DISINFECTION CLOTH 4 x 4 disinfectant cloth (2) Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH (3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution (ethanol solution) containing 1w/v% chlorhexidine gluconate as an active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.
2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN) (3) Stem: unknown
3. Structural formula or demonstrative formula
4.Molecular formula and molecular weight
Molecular for
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8823
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 8
```

## 12. List the full qualitative composition of the product.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:01:24
- Finished: 2026-03-25T06:42:21
- Elapsed seconds: 2457.4403
- Retrieval seconds: 52.3267
- Generation seconds: 0.0
- Estimated prompt tokens: 1561
- Estimated answer tokens: 1292

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "List the full qualitative composition of the product." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: List the full qualitative composition of the product.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.9746
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9629
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9491
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9415
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9192
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9103
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 13. What is the quantitative composition per unit dose?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:04:21
- Finished: 2026-03-25T06:43:19
- Elapsed seconds: 2337.9698
- Retrieval seconds: 57.3642
- Generation seconds: 0.0
- Estimated prompt tokens: 1482
- Estimated answer tokens: 1268

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What is the quantitative composition per unit dose?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What is the quantitative composition per unit dose?
Drug filter: chlorhexidine gluconate
Section hints: dosage

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=7.0103
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=7.0034
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL
- chlorhexidine gluconate | interview_form | page 6 | section=dosage | score=6.9887
  IV.Items related to formulations
1. Dosage form

(1) Route of administrationExternal use

(2) Distinction of dosage forms, specifications, and properties Distinction of dosage forms: Liquid <0.02%> Specifications: Contains 0.02 w/v% of chlorhexidine gluconate when quantitatively determined. Properties: Colorless to pale yellow clear liquid with no odor and slightly bitter taste. <0.05%> Specification: Contains 0.05w/v% of chlorhexidine gluconate when quantitatively determined. Properties: Clear, colorless liquid with a slightly bitter taste. <0.1%> Specification: Contains 0.1w/v% of chlorhexidine gluconate when quantifying. Properties: Colorless to pale yellow clear liquid with no odor and s
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=6.9581
  -4-

IV.Items related to formulations
1.Dosage form
(1) Administration route: Use only for external use. (2) Distinction of dosage forms, appearance and properties
1) Distinction: External sterilizing disinfectant
2) Specifications: 1 package, Japanese Pharmacopoeia Chlorhexidine gluconate solution 0.09mL
(0.018g as chlorhexidine gluconate)
3) Appearance and properties: non-woven fabric (2 sheets) impregnated with chemical solution (chemical solution amount: 1.8mL)
It is. The chemical solution is colorless to slightly white. (3) Physical properties of the preparation No applicable data (4) Identification code not applicable (5) pH, osmotic pressure ratio, viscosity, specific gravity, stable
- chlorhexidine gluconate | interview_form | page 10 | section=dosage | score=6.9548
  IV.Items related to formulations
1.Dosage form
(1) Distinction of dosage form Disinfectant for external skin (2) Appearance and properties of the preparation Brand name Properties Chlorhexidine gluconate ethanol solution
1% disinfectant cloth 4×4 “Nipro”
It is a nonwoven fabric impregnated with a chemical solution. The chemical solution is colorless. (3) Identification code not applicable (4) No applicable data on physical properties of the preparation (5) Other not applicable
2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additive Brand name Active ingredient Additive Carrier Drug amount Chlorhexidine gluconate ethanol solution 1% Disinfecting clot
- chlorhexidine gluconate | interview_form | page 5 | section=dosage | score=6.9531
  (2) Distinction of dosage forms, specifications, and properties Distinction of dosage forms: Liquid <0.05%> Specifications: Contains 0.05 w/v% of chlorhexidine gluconate when quantitatively determined. Properties: Pale red, clear liquid with a slightly bitter taste. <0.1%> Specification: Contains 0.1w/v% of chlorhexidine gluconate when quantitatively determined. Properties: Pale red, clear liquid with no odor and bitter taste. <0.5%> Specification: Contains 0.5w/v% of chlorhexidine gluconate when quantifying. Properties: A clear red liquid with no odor and a bitter taste.
20
20
2

Sources:
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 10
- chlorhexidine gluconate / interview_form / page 5
```

## 14. What dosage forms and strengths are available?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:05:11
- Finished: 2026-03-25T06:44:16
- Elapsed seconds: 2344.8887
- Retrieval seconds: 57.2119
- Generation seconds: 0.0001
- Estimated prompt tokens: 1559
- Estimated answer tokens: 1296

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What dosage forms and strengths are available?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What dosage forms and strengths are available?
Drug filter: chlorhexidine gluconate
Section hints: dosage

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=7.1029
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0924
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0683
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0571
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0262
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0211
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 15. Which excipients are present in the 50 mg and 100 mg tablets?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:08:09
- Finished: 2026-03-25T06:45:02
- Elapsed seconds: 2212.4002
- Retrieval seconds: 45.8189
- Generation seconds: 0.0
- Estimated prompt tokens: 1204
- Estimated answer tokens: 1035

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients are present in the 50 mg and 100 mg tablets?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients are present in the 50 mg and 100 mg tablets?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8448
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8408
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant (chlorhexidine gluconate formulation) FERMASCRUB 4%FERMASCRUB 4%

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 20mL in 100mL
(Contains 4w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales appr
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.7971
  Created in June 2021 (1st edition)
Japan standard product classification number 872619

Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

External germicidal disinfectant

Dosage form Regulatory classification of disinfectant-impregnated cloth preparations Not applicable specifications/contents
In 1 package,
Contains 0.09mL of Japanese Pharmacopoeia chlorhexidine gluconate solution (0.18g as chlorhexidine gluconate). Contains lauromacrogol as an additive. Generic name Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing and sales approval Date of NHI drug price li
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=5.7272
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7196
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7025
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate solution

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
```

## 16. Are there differences in excipients between product strengths?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:40:25
- Finished: 2026-03-25T06:45:40
- Elapsed seconds: 315.1408
- Retrieval seconds: 38.291
- Generation seconds: 0.0
- Estimated prompt tokens: 1564
- Estimated answer tokens: 1295

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there differences in excipients between product strengths?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there differences in excipients between product strengths?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.9528
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9296
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9215
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8988
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8880
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8544
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 17. What formulation components are listed for this product?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:41:29
- Finished: 2026-03-25T06:46:18
- Elapsed seconds: 289.1352
- Retrieval seconds: 38.1164
- Generation seconds: 0.0
- Estimated prompt tokens: 1562
- Estimated answer tokens: 1294

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What formulation components are listed for this product?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What formulation components are listed for this product?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.9598
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9547
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9381
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9300
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9222
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9050
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
```

## 18. Does the document distinguish the active ingredient from excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:42:21
- Finished: 2026-03-25T06:46:57
- Elapsed seconds: 275.2806
- Retrieval seconds: 38.4764
- Generation seconds: 0.0
- Estimated prompt tokens: 1369
- Estimated answer tokens: 1150

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Does the document distinguish the active ingredient from excipients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Does the document distinguish the active ingredient from excipients?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9173
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 11 | section=general | score=5.9104
  5
4. Quantification method of active ingredients
Based on the Japanese drug ``chlorhexidine gluconate solution.''
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9019
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8948
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.8929
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8739
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
```

## 19. What pharmaceutical additives are mentioned in the label?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:43:19
- Finished: 2026-03-25T06:47:39
- Elapsed seconds: 260.2917
- Retrieval seconds: 42.3739
- Generation seconds: 0.0001
- Estimated prompt tokens: 1519
- Estimated answer tokens: 1296

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What pharmaceutical additives are mentioned in the label?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What pharmaceutical additives are mentioned in the label?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9166
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9094
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8878
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8784
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=5.8475
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8446
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / interview_form / page 1
```

## 20. Show the composition section.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:44:16
- Finished: 2026-03-25T06:48:21
- Elapsed seconds: 244.6056
- Retrieval seconds: 41.5303
- Generation seconds: 0.0
- Estimated prompt tokens: 1478
- Estimated answer tokens: 1258

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show the composition section." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show the composition section.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8875
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8785
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.8501
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.8404
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=5.8402
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=5.8256
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
```

## 21. Show the excipient information only.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:45:02
- Finished: 2026-03-25T06:49:04
- Elapsed seconds: 242.5577
- Retrieval seconds: 43.7647
- Generation seconds: 0.0
- Estimated prompt tokens: 1248
- Estimated answer tokens: 1080

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show the excipient information only." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show the excipient information only.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9433
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9354
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9116
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9013
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 32 | section=general | score=5.8924
  26
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 31 | section=general | score=5.8924
  25
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% Chlorhexidine Gluconate HIBICLENS® (USA): 4w/v% Chlorhexidine Gluconate HIBISTAT® (USA): 0.5w/w% Chlorhexidine Gluconate

2.Clinical support information overseas
No applicable materials

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 32
- chlorhexidine gluconate / interview_form / page 31
```

## 22. Extract the excipient list and dosage form.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:45:40
- Finished: 2026-03-25T06:49:44
- Elapsed seconds: 244.1245
- Retrieval seconds: 39.8665
- Generation seconds: 0.0
- Estimated prompt tokens: 1558
- Estimated answer tokens: 1295

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Extract the excipient list and dosage form." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Extract the excipient list and dosage form.
Drug filter: chlorhexidine gluconate
Section hints: dosage

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=7.1252
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.1053
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0940
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0831
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0457
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=7.0414
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 23. Summarize the formulation composition and pharmaceutical properties.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B1. Composition and dosage form
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:46:18
- Finished: 2026-03-25T06:50:29
- Elapsed seconds: 250.7601
- Retrieval seconds: 44.7445
- Generation seconds: 0.0001
- Estimated prompt tokens: 1566
- Estimated answer tokens: 1298

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the formulation composition and pharmaceutical properties." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize the formulation composition and pharmaceutical properties.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9392
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9313
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9088
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8993
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8823
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8730
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
```

## 24. List all excipients in the formulation.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:46:57
- Finished: 2026-03-25T06:51:13
- Elapsed seconds: 256.5903
- Retrieval seconds: 44.3044
- Generation seconds: 0.0001
- Estimated prompt tokens: 1557
- Estimated answer tokens: 1289

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "List all excipients in the formulation." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: List all excipients in the formulation.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9409
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9286
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9211
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9005
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8905
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8541
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 25. List all inactive ingredients.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:47:39
- Finished: 2026-03-25T06:51:55
- Elapsed seconds: 256.1878
- Retrieval seconds: 41.9731
- Generation seconds: 0.0
- Estimated prompt tokens: 1208
- Estimated answer tokens: 1039

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "List all inactive ingredients." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: List all inactive ingredients.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 11 | section=general | score=5.9605
  5
4. Quantification method of active ingredients
Based on the Japanese drug ``chlorhexidine gluconate solution.''
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9540
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9382
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9298
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.9168
  - 4 -
3. Confirmation test for active ingredients
law
4. Quantification method of active ingredients
According to the Japanese Bureau of Medicine's "Chlorhexidine Gluconate Solution Confirmation Test." Based on the ``Chlorhexidine gluconate liquid quantitative method'' of the Japanese Bureau.
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9098
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201

Sources:
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 1
```

## 26. What non-active ingredients are listed in this document?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:48:21
- Finished: 2026-03-25T06:52:36
- Elapsed seconds: 255.8497
- Retrieval seconds: 41.189
- Generation seconds: 0.0
- Estimated prompt tokens: 1214
- Estimated answer tokens: 1046

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What non-active ingredients are listed in this document?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What non-active ingredients are listed in this document?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 11 | section=general | score=5.9707
  5
4. Quantification method of active ingredients
Based on the Japanese drug ``chlorhexidine gluconate solution.''
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9558
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9407
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9328
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.9295
  - 4 -
3. Confirmation test for active ingredients
law
4. Quantification method of active ingredients
According to the Japanese Bureau of Medicine's "Chlorhexidine Gluconate Solution Confirmation Test." Based on the ``Chlorhexidine gluconate liquid quantitative method'' of the Japanese Bureau.
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9235
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu

Sources:
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 7
```

## 27. Which excipients are likely used as diluents, binders, disintegrants, or lubricants?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:49:04
- Finished: 2026-03-25T06:53:18
- Elapsed seconds: 253.9114
- Retrieval seconds: 41.8315
- Generation seconds: 0.0
- Estimated prompt tokens: 1249
- Estimated answer tokens: 1130

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients are likely used as diluents, binders, disintegrants, or lubricants?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients are likely used as diluents, binders, disintegrants, or lubricants?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=adverse_event | score=5.7980
  Medium Contains 0.1g of chlorhexidine gluconate (
0.1w/v%)

:1) It has been diluted so it can be used as is. [Prevention of measurement/dilution errors] Contains 0.5g of chlorhexidine gluconate (medium)
0.5w/v%) Since it uses a volume-reducing bottle, it can be folded to reduce the volume and be disposed of, reducing disposal costs.
Ru. (12) Shock and anaphylaxis may occur as serious side effects.
- chlorhexidine gluconate | interview_form | page 6 | section=indication | score=5.7905
  - 1 -
I. Items related to overview
1. Development history
Chlorhexidine gluconate is a biguanide disinfectant researched and synthesized by ICI Ltd. in the UK. It exhibits antibacterial activity against Gram-positive and -negative bacteria, and is widely used as a hand disinfectant.
Hibisoft Disinfectant 0.2% is an ethanol solution containing 0.2w/v% of chlorhexidine gluconate.
This is a quick-drying hand sanitizer developed by Shiseido with its antibacterial effect and skin protection properties in mind.
- chlorhexidine gluconate | interview_form | page 16 | section=indication | score=5.7648
  Use 0.05% aqueous solution as chlorhexidine gluconate to disinfect skin wound sites, operating rooms, hospital rooms, furniture, instruments, articles, etc. Use an aqueous solution of 0.05% or less as chlorhexidine gluconate to clean and disinfect the conjunctival sac. A 0.02% aqueous solution is used as chlorhexidine gluconate for skin disinfection of the vulva and external genitalia in obstetrics and gynecology and urology.

2. Dosage and dosage
See section V.1. Efficacy or effect.
- chlorhexidine gluconate | interview_form | page 13 | section=general | score=5.7429
  - 8 -

12.Titer

13. Possibility of contamination
some foreign matter

14. Containers that require attention
Information regarding containers with special appearance

15.Irritation

16.Others

and use it as the standard solution. Test the sample solution and standard solution using the absorbance measurement method, and measure the absorbance of Ar and As at a wavelength of 258 nm.
Amount (mg) of chlorhexidine gluconate (C22H30Cl2N10・2C6H12O7)
= Amount of chlorhexidine gluconate standard solution (mg) × Ar/As

*Chlorhexidine gluconate standard solution:
"Chlorhexidine gluconate solution". However, the content is 19.5~20.5 W/V%,
p-Chloraniline should be 100 ppm or less.

Not applicable.

Deco
- chlorhexidine gluconate | interview_form | page 6 | section=dosage | score=5.7377
  - 1 -
1. Development history
2.Therapeutic properties of the product
Pharmaceutical properties Microshield4 (MICROSHIELD4) is a hand disinfectant developed by Johnson & Johnson Medical Pty Ltd. It is a formulation containing chlorhexidine gluconate as an active ingredient. Chlorhexidine gluconate exhibits antibacterial activity against a wide range of Gram-positive and -negative bacteria, and is widely used as a hand disinfectant.
Dated June 2, 2004, Pharmaceutical and Shokuhou No. 0602009 “Strengthening measures to prevent pharmaceutical-related medical accidents”
Based on "About thoroughness", the brand name was changed from Microshield 4 to Microshield scrub liquid 4%.
1) This drug has
- chlorhexidine gluconate | interview_form | page 8 | section=indication | score=5.7324
  11. Active ingredients in the preparation
Conforms to "III. Items related to active ingredients 4. Confirmation test method for active ingredients". However, some changes have been made slightly. Confirmation test method

12. Active ingredients in the formulation
By ultraviolet-visible absorbance measurement. Quantitative method

13. Titer

14. Container material
polypropylene

15. Irritation

16. Others

V.Items related to treatment
1. Efficacy or effect
2. Dosage and dosage
<0.02%> Efficacy/Efficacy Directions/Dose For conjunctival sac cleaning/disinfection Use an aqueous solution of 0.02% or less as chlorhexidine gluconate. A 0.02% aqueous solution is used as chlorhexidine gluconate for s

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 13
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 8
```

## 28. Which excipients are related to coating, coloring, or preservation?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:49:44
- Finished: 2026-03-25T06:53:58
- Elapsed seconds: 253.8926
- Retrieval seconds: 39.8393
- Generation seconds: 0.0
- Estimated prompt tokens: 1566
- Estimated answer tokens: 1298

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients are related to coating, coloring, or preservation?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients are related to coating, coloring, or preservation?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.9360
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9235
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.8984
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 8 | section=general | score=5.8550
  II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine GLUCONATE SOLUTION DISINFECTION CLOTH 4 x 4 disinfectant cloth (2) Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH (3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution (ethanol solution) containing 1w/v% chlorhexidine gluconate as an active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.
2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN) (3) Stem: unknown
3. Structural formula or demonstrative formula
4.Molecular formula and molecular weight
Molecular for
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8539
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8445
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
```

## 29. Which excipients may influence stability or manufacturability?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:50:29
- Finished: 2026-03-25T06:54:40
- Elapsed seconds: 250.8811
- Retrieval seconds: 41.7427
- Generation seconds: 0.0
- Estimated prompt tokens: 1472
- Estimated answer tokens: 1283

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients may influence stability or manufacturability?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients may influence stability or manufacturability?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6373
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6275
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6148
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5910
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5807
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5768
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 30. Which excipients may affect solubility, viscosity, or release characteristics?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:51:13
- Finished: 2026-03-25T06:55:28
- Elapsed seconds: 254.3719
- Retrieval seconds: 47.7939
- Generation seconds: 0.0
- Estimated prompt tokens: 1103
- Estimated answer tokens: 986

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients may affect solubility, viscosity, or release characteristics?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients may affect solubility, viscosity, or release characteristics?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8849
  Revised August 2018 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

Topical Disinfectant Japanese Pharmacopoeia Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan" Chlorhexidine Gluconate Solution

Dosage form Liquid
No regulatory classification for pharmaceutical preparations
Specifications/Content Contains 19.0~21.0w/v% of chlorhexidine gluconate.
Generic name Japanese name: Chlorhexidine gluconate
Western name: Chlorhexidine Gluconate Date of manufacturing and sales approval Date of drug price listing/release
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8737
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8612
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 32 | section=general | score=5.8527
  26
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 31 | section=general | score=5.8526
  25
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% Chlorhexidine Gluconate HIBICLENS® (USA): 4w/v% Chlorhexidine Gluconate HIBISTAT® (USA): 0.5w/w% Chlorhexidine Gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 34 | section=general | score=5.8526
  28
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 32
- chlorhexidine gluconate / interview_form / page 31
- chlorhexidine gluconate / interview_form / page 34
```

## 31. Summarize excipient composition and likely formulation roles.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B2. Excipients and formulation roles
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:51:55
- Finished: 2026-03-25T06:56:12
- Elapsed seconds: 256.5359
- Retrieval seconds: 44.1386
- Generation seconds: 0.0
- Estimated prompt tokens: 1485
- Estimated answer tokens: 1266

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize excipient composition and likely formulation roles." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize excipient composition and likely formulation roles.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8688
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8596
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8421
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant (chlorhexidine gluconate formulation) FERMASCRUB 4%FERMASCRUB 4%

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 20mL in 100mL
(Contains 4w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales appr
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.8386
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.8288
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=5.8221
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
```

## 32. Are there any warnings related to excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B3. Excipient-related safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:52:36
- Finished: 2026-03-25T06:56:53
- Elapsed seconds: 256.1932
- Retrieval seconds: 40.8468
- Generation seconds: 0.0
- Estimated prompt tokens: 1326
- Estimated answer tokens: 1183

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there any warnings related to excipients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there any warnings related to excipients?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7257
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6837
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.5118
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.4128
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.4119
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.4001
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 26
```

## 33. Are there any excipient-related contraindications or precautions?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B3. Excipient-related safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:53:18
- Finished: 2026-03-25T06:57:33
- Elapsed seconds: 254.9848
- Retrieval seconds: 40.6224
- Generation seconds: 0.0
- Estimated prompt tokens: 1514
- Estimated answer tokens: 1320

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there any excipient-related contraindications or precautions?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there any excipient-related contraindications or precautions?
Drug filter: chlorhexidine gluconate
Section hints: contraindication, warning

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=7.0164
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9598
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.7925
  14

11. Application notes
14. Application notes
14.1 Precautions when using drugs
14.1.1 This product should not be diluted and should be used as a undiluted solution.
14.1.2 Do not administer orally. If swallowed by mistake, wash the stomach with milk, raw eggs, gelatin, etc.
Take appropriate measures such as
14.1.3 Do not use for any purpose other than hand disinfection.
14.1.4 Take care to avoid contact with eyes. In case of contact with eyes, rinse thoroughly with water immediately.
14.1.5 There are reports of chemical skin burns caused by prolonged skin contact in solution form.
So be careful.
14.2 Precautions after using drugs
If white cloth coated with this agent is bleached with a ch
- chlorhexidine gluconate | interview_form | page 20 | section=contraindication | score=6.7727
  14. Application notes

(1) Route of administration
Do not use for any purpose other than disinfecting hands and skin.                |
(2) When in use
1) Please note that repeated use may cause skin irritation due to degreasing.
2) Organic substances such as serum and visceral juices weaken the bactericidal action, so if these are present,
Wash thoroughly before use.
3) Since soap weakens the bactericidal effect of this agent, thoroughly wash off the soap used for preliminary cleaning.
before use.
4) Be careful of fire as it is flammable and explosive.
5 There are reports that chemical skin burns were caused when the solution was in contact with the skin for a long time.
So, be careful.

15.
- chlorhexidine gluconate | interview_form | page 12 | section=contraindication | score=6.7648
  2) Do not use instruments that may come into contact with nerves or mucous membranes, such as syringes or catheters.
If disinfected with disinfectant, rinse thoroughly with sterile purified water before use.
3) If a catheter with this drug attached is used for dialysis, it may be difficult to dissolve due to the components of the dialysate.
Catheters sterilized with this agent should be thoroughly rinsed with sterile purified water before use, as this product may produce toxic salts.
4) Organic substances such as serum and pus reduce the bactericidal action, so if they adhere
If so, wash thoroughly before use.
5) Since soaps reduce the bactericidal effect of this agent, do not use the soap u
- chlorhexidine gluconate | interview_form | page 13 | section=contraindication | score=6.7644
  <0.1%> <0.5%>
1) Be careful not to get the undiluted solution or highly concentrated solution in your eyes. In case of contact with eyes, immediately
Wash thoroughly with water.
2) Do not use this drug with instruments that may come into contact with nerves or mucous membranes, such as syringes or catheters.
If disinfected, rinse thoroughly with sterile purified water before use.
3) If a catheter with this drug attached is used for dialysis, it may be difficult to dissolve due to the components of the dialysate.
Catheters sterilized with this agent should be thoroughly rinsed with sterile purified water before use.
4) Organic substances such as serum and pus reduce the bactericidal action, s

Sources:
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 20
- chlorhexidine gluconate / interview_form / page 12
- chlorhexidine gluconate / interview_form / page 13
```

## 34. Which excipients may cause hypersensitivity or intolerance?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B3. Excipient-related safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:53:58
- Finished: 2026-03-25T06:58:16
- Elapsed seconds: 257.7155
- Retrieval seconds: 42.5761
- Generation seconds: 0.0
- Estimated prompt tokens: 1548
- Estimated answer tokens: 1298

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients may cause hypersensitivity or intolerance?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients may cause hypersensitivity or intolerance?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=5.7998
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 13 | section=general | score=5.7695
  - 8 -

12.Titer

13. Possibility of contamination
some foreign matter

14. Containers that require attention
Information regarding containers with special appearance

15.Irritation

16.Others

and use it as the standard solution. Test the sample solution and standard solution using the absorbance measurement method, and measure the absorbance of Ar and As at a wavelength of 258 nm.
Amount (mg) of chlorhexidine gluconate (C22H30Cl2N10・2C6H12O7)
= Amount of chlorhexidine gluconate standard solution (mg) × Ar/As

*Chlorhexidine gluconate standard solution:
"Chlorhexidine gluconate solution". However, the content is 19.5~20.5 W/V%,
p-Chloraniline should be 100 ppm or less.

Not applicable.

Deco
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7665
  I. Items related to overview

1. Development history

Povidone-iodine preparations are the mainstream for hand and skin disinfection in medical institutions, but they have drawbacks such as being difficult to dry and taking a long time to develop their effects. In addition, although alcohol preparations have excellent immediate disinfecting effects, they also have the disadvantage of short lasting activity. On the other hand, there are reports that chlorhexidine gluconate has a longer-lasting disinfectant effect than povidone-iodine preparations, and that it suppresses the incidence of surgical site infections and catheter-related bloodstream infections 1), 2). Among these, alcohol-containin
- chlorhexidine gluconate | interview_form | page 6 | section=dosage | score=5.7526
  - 1 -
1. Development history
2.Therapeutic properties of the product
Pharmaceutical properties Microshield4 (MICROSHIELD4) is a hand disinfectant developed by Johnson & Johnson Medical Pty Ltd. It is a formulation containing chlorhexidine gluconate as an active ingredient. Chlorhexidine gluconate exhibits antibacterial activity against a wide range of Gram-positive and -negative bacteria, and is widely used as a hand disinfectant.
Dated June 2, 2004, Pharmaceutical and Shokuhou No. 0602009 “Strengthening measures to prevent pharmaceutical-related medical accidents”
Based on "About thoroughness", the brand name was changed from Microshield 4 to Microshield scrub liquid 4%.
1) This drug has
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=5.7336
  No particular abnormality was observed except for an increase in giant cells in the nodes19). (3) Reproductive and developmental toxicity test Reproductive test

Pregnant rats received 10, 25, and 50 mg/kg/day of chlorhexidine gluconate for 10 days from the 6th to 15th gestation day.

When administered orally, slight hypersensitivity and suppression of weight gain were observed in the mother at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton19). (4) Other special toxicities

1) Tissue damage

The minimum tissue-damaging concentration of chlorhexidine gluconate in chic
- chlorhexidine gluconate | interview_form | page 6 | section=indication | score=5.7182
  - 1 -
I. Items related to overview
1. Development history
Chlorhexidine is a biguanide disinfectant that was researched and synthesized by ICI in the UK, and was developed by G. E. Davies et al.
It was first reported in 1954 in Br. J. Pharmacol. 1). According to this, certain types of polydiguanide cause P. aeruginosa.
Recognizing that it has a remarkable antibacterial effect on a wide range of microorganisms, including bacteria, they synthesized hundreds of compounds of this type, and selected the substance with the best antibacterial activity and action on a wide range of microorganisms. Chlorhexidine is also used as a drug in the form of hydrochloride, but this drug is sparingly soluble i

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 13
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 20
- chlorhexidine gluconate / interview_form / page 6
```

## 35. Are there warnings about preservatives, dyes, coating agents, or alcohol-containing excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B3. Excipient-related safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:54:40
- Finished: 2026-03-25T06:58:57
- Elapsed seconds: 256.8351
- Retrieval seconds: 40.8562
- Generation seconds: 0.0001
- Estimated prompt tokens: 1438
- Estimated answer tokens: 1243

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings about preservatives, dyes, coating agents, or alcohol-containing excipients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings about preservatives, dyes, coating agents, or alcohol-containing excipients?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7047
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6584
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2531
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2519
  慎重投与内容とその理由 ·································································································· 17

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 17

7.

相互作用 ······················································································································· 18

8.

副作用 ·························································································································· 18

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2516
  慎重投与内容とその理由 ·································································································· 15

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 15

7.

相互作用 ······················································································································· 16

8.

副作用 ·························································································································· 16

9.

高齢者への投与 ·············································································································· 16

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2511
  慎重投与内容とその理由 ·································································································· 16

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 16

7.

相互作用 ······················································································································· 17

8.

副作用 ·························································································································· 17

9.

高齢者への投与 ·············································································································· 18

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
```

## 36. Are there warnings about sugars, polyols, or sodium content in the formulation?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B3. Excipient-related safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:55:28
- Finished: 2026-03-25T06:59:41
- Elapsed seconds: 253.2682
- Retrieval seconds: 44.2258
- Generation seconds: 0.0001
- Estimated prompt tokens: 1434
- Estimated answer tokens: 1240

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings about sugars, polyols, or sodium content in the formulation?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings about sugars, polyols, or sodium content in the formulation?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7376
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6952
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.4204
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 18 | section=warning | score=6.3436
  - 12 -
(2) Serious side effects and initial symptoms Serious side effects: Shock (less than 0.1%), anaphylaxis (incidence unknown) Shock, anaphylaxis may occur, so carefully monitor the product, and if any symptoms such as decreased blood pressure, hives, or difficulty breathing occur, immediately discontinue use and take appropriate measures.

(3)Other side effects

Frequency unknown
Less than 0.1%
Hypersensitivity *1)

Skin irritation symptoms such as rash and hives *2)

*1) If any of these symptoms occur, immediately stop using the product and do not reuse it. *2) If any of these symptoms occur, discontinue use. (4) List of frequency of side effects by item and abnormal clinical test valu
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2818
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2804
  慎重投与内容とその理由 ·································································································· 17

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 17

7.

相互作用 ······················································································································· 18

8.

副作用 ·························································································································· 18

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
```

## 37. Does the product contain excipients that require caution in sensitive patients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B3. Excipient-related safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:56:12
- Finished: 2026-03-25T07:02:19
- Elapsed seconds: 367.6559
- Retrieval seconds: 158.5262
- Generation seconds: 0.0
- Estimated prompt tokens: 1568
- Estimated answer tokens: 1307

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Does the product contain excipients that require caution in sensitive patients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Does the product contain excipients that require caution in sensitive patients?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.6503
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.6326
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6256
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.6131
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6047
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.5958
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 38. Are there formulation-related warnings for pediatric patients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B4. Special-population and use-related formulation safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:56:53
- Finished: 2026-03-25T07:04:37
- Elapsed seconds: 463.9905
- Retrieval seconds: 137.1892
- Generation seconds: 0.0
- Estimated prompt tokens: 1330
- Estimated answer tokens: 1195

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there formulation-related warnings for pediatric patients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there formulation-related warnings for pediatric patients?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.4845
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.4457
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.2715
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.1704
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.1700
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.1548
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 26
```

## 39. Are there formulation-related warnings for elderly patients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B4. Special-population and use-related formulation safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:57:33
- Finished: 2026-03-25T07:07:09
- Elapsed seconds: 575.8807
- Retrieval seconds: 152.5058
- Generation seconds: 0.0
- Estimated prompt tokens: 1330
- Estimated answer tokens: 1194

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there formulation-related warnings for elderly patients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there formulation-related warnings for elderly patients?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.4840
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.4451
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.2709
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.1701
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.1696
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.1545
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 26
```

## 40. Are there warnings for pregnancy or breastfeeding related to formulation or excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B4. Special-population and use-related formulation safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:58:16
- Finished: 2026-03-25T07:07:52
- Elapsed seconds: 576.2595
- Retrieval seconds: 42.956
- Generation seconds: 0.0
- Estimated prompt tokens: 1170
- Estimated answer tokens: 1128

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings for pregnancy or breastfeeding related to formulation or excipients?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings for pregnancy or breastfeeding related to formulation or excipients?
Drug filter: chlorhexidine gluconate
Section hints: warning, pregnancy

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=6.7480
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.6977
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6506
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 12 | section=pregnancy | score=6.6376
  (3) Reproductive and developmental toxicity test 17) Fetal test, genetic variability
Chlorhexidine gluconate for 10 days from the 6th to 15th gestation day of pregnant rats.
10, 25, and 50 mg/kg were administered orally. Regarding the mother body, only the maximum amount group
Slight irritation sensitivity and suppression of weight gain were observed, but no abnormalities were observed in the number of implantations, number of absorbed embryos, number of fetuses, sex ratio, abnormal external appearance, or skeletal variation.

(4) Other special toxicities 18) Hemolytic and tissue-damaging The minimum tissue-damaging concentration of chlorhexidine gluconate in chicken fetal heart was 1w/v%.
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=6.6281
  No particular abnormality was observed except for an increase in giant cells in the nodes19). (3) Reproductive and developmental toxicity test Reproductive test

Pregnant rats received 10, 25, and 50 mg/kg/day of chlorhexidine gluconate for 10 days from the 6th to 15th gestation day.

When administered orally, slight hypersensitivity and suppression of weight gain were observed in the mother at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton19). (4) Other special toxicities

1) Tissue damage

The minimum tissue-damaging concentration of chlorhexidine gluconate in chic
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=6.6053
  No particular abnormality was observed except for an increase in the number of giant cells18). (3) No relevant data for genotoxicity test (4) No relevant data for carcinogenicity test (5) Reproductive and developmental toxicity test

Chlorhexidine gluconate 10, 25, or 50 mg/kg/day was orally administered to pregnant rats for 10 days from the 6th to the 15th gestation day.

When administered, slight hypersensitivity and suppression of weight gain were observed in mothers at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton18). (6) No relevant data for local irritation te

Sources:
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 12
- chlorhexidine gluconate / interview_form / page 20
- chlorhexidine gluconate / interview_form / page 20
```

## 41. Are there safety concerns for thyroid disorders, renal dysfunction, or systemic absorption?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B4. Special-population and use-related formulation safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:58:57
- Finished: 2026-03-25T07:08:35
- Elapsed seconds: 578.1456
- Retrieval seconds: 42.7404
- Generation seconds: 0.0
- Estimated prompt tokens: 1570
- Estimated answer tokens: 1302

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there safety concerns for thyroid disorders, renal dysfunction, or systemic absorption?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there safety concerns for thyroid disorders, renal dysfunction, or systemic absorption?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.8195
  Revised October 2017 (3rd edition)
Japan standard product classification number 872619

Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

Specifications and contents that do not apply to regulatory categories for external liquid preparations
1,000mL medium
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 250mL
(50g as chlorhexidine gluconate) Generic name: Japanese name: Chlorhexidine gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales approval Date of drug price listing/release date
Date of manufacturing and marketing approval: February 15, 2013
NHI drug price l
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8167
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.7709
  Created in June 2021 (1st edition)
Japan standard product classification number 872619

Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

External germicidal disinfectant

Dosage form Regulatory classification of disinfectant-impregnated cloth preparations Not applicable specifications/contents
In 1 package,
Contains 0.09mL of Japanese Pharmacopoeia chlorhexidine gluconate solution (0.18g as chlorhexidine gluconate). Contains lauromacrogol as an additive. Generic name Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing and sales approval Date of NHI drug price li
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.7667
  Revised October 2017 (3rd edition)
Japan standard product classification number 872619

Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

Specifications and contents that do not apply to regulatory categories for external liquid preparations
1,000mL Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL
Generic name: Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales approval Date of drug price listing/release date
Date of manufacturing and sales approval: February 15, 2013 (due to change in brand name)
Date of drug price listing: Dec
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.7640
  Revised April 2023 (8th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

Dosage form Regulatory classification for external liquid preparations Not applicable standards/contains
Contains 0.2g of chlorhexidine gluconate in 100mL
Generic name Japanese name: Chlorhexidine Gluconate Solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/release date
Date of manufacturing and sales approval: September 14, 2007 (due to change in brand name)
Date of listing on the NHI drug price standard
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=5.7449
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 6
```

## 42. Does prolonged use, large-surface application, or mucosal use increase formulation-related safety concerns?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B4. Special-population and use-related formulation safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T06:59:41
- Finished: 2026-03-25T07:09:18
- Elapsed seconds: 576.7818
- Retrieval seconds: 42.8654
- Generation seconds: 0.0
- Estimated prompt tokens: 1574
- Estimated answer tokens: 1311

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Does prolonged use, large-surface application, or mucosal use increase formulation-related safety concerns?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Does prolonged use, large-surface application, or mucosal use increase formulation-related safety concerns?
Drug filter: chlorhexidine gluconate
Section hints: dosage

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=7.0628
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.9903
  September 2021 (1st edition)
Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists
Disinfectant for hands MICROSHIELD Skincare Products Dosage form Regulatory classification for external liquid preparations Not applicable Specifications/Content Japanese Pharmacopoeia Contains 20% (v/v) of chlorhexidine gluconate solution
[Contains 4% (w/v) as chlorhexidine gluconate]
common name
Japanese name: Chlorhexidine gluconate solution
Western name: Chlorhexidine Gluconate Solution
Date of manufacturing and sales approval Date of NHI price list listing/release date
Date of manufacturing and sales approval: June 26, 2009 (d
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.9872
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant (chlorhexidine gluconate formulation) FERMASCRUB 4%FERMASCRUB 4%

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 20mL in 100mL
(Contains 4w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales appr
- chlorhexidine gluconate | interview_form | page 8 | section=dosage | score=6.9839
  2
II. Items related to name

1. Brand name
(1) Japanese name: Stericlone® Liquid 5

(2) Western name: STERICLON® SOLUTION 5

(3) Origin of name: The brand name Stericlone was derived from Steri...lize (to disinfect) and chlorhexidine gluconate, and the name was derived from ``brand name + dosage form + active ingredient concentration''.

2. Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate solution (JAN)

(2) Western name (nomenclature): Chlorhexidine Gluconate (JAN, USAN) Chlorhexidine Gluconate Solution (USP) Chlorhexidine Digluconate Solution (EP) Chlorhexidine (INN)

(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4. Molecular fo
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=6.9666
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=6.9591
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
```

## 43. Summarize special-population precautions relevant to formulation and excipients.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B4. Special-population and use-related formulation safety
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:02:19
- Finished: 2026-03-25T07:09:59
- Elapsed seconds: 459.8869
- Retrieval seconds: 41.6328
- Generation seconds: 0.0
- Estimated prompt tokens: 1335
- Estimated answer tokens: 1192

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize special-population precautions relevant to formulation and excipients." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize special-population precautions relevant to formulation and excipients.
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9668
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6696
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.5066
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.4088
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.4012
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.3931
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 26
```

## 44. What storage conditions and stability precautions are described?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B5. Stability, storage, packaging
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:04:37
- Finished: 2026-03-25T07:10:42
- Elapsed seconds: 365.1602
- Retrieval seconds: 42.4614
- Generation seconds: 0.0
- Estimated prompt tokens: 1473
- Estimated answer tokens: 1286

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What storage conditions and stability precautions are described?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What storage conditions and stability precautions are described?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: warning, stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6092
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.5997
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.5982
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5700
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5562
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5558
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 45. Which formulation components may be sensitive to light, heat, moisture, or oxidation?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B5. Stability, storage, packaging
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:07:09
- Finished: 2026-03-25T07:11:20
- Elapsed seconds: 250.4036
- Retrieval seconds: 37.748
- Generation seconds: 0.0
- Estimated prompt tokens: 1490
- Estimated answer tokens: 1270

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which formulation components may be sensitive to light, heat, moisture, or oxidation?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which formulation components may be sensitive to light, heat, moisture, or oxidation?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8182
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8088
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.7992
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant (chlorhexidine gluconate formulation) FERMASCRUB 4%FERMASCRUB 4%

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 20mL in 100mL
(Contains 4w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales appr
- Chlorhexidine Gluconate | smpc_label | page 2 | section=general | score=5.7924
  Candida albicans
TIMM 1623
0.004
within 30 seconds
*100 times diluted solution of 5% chlorhexidine gluconate solution "Metal"
Indicates the bactericidal effect of liquid (0.05w/v%).
19. Physical and chemical knowledge regarding active ingredients
Common name: Chlorhexidine Gluconate Solution
Chemical name: 1,1′-Hexamethylenebis[5-(4-chlorophenyl)biguanide],di-D-
gluconate
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76
Properties: Chlorhexidine gluconate solution is a colorless to slightly yellow clear liquid with no odor and a bitter taste. Miscible with water or acetic acid (100). Chlorhexidine gluconate
1mL of liquid is 5mL or less of ethanol (99.5) or 3mL of acetone.
It
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.7806
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=5.7731
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 1
- Chlorhexidine Gluconate / smpc_label / page 2
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
```

## 46. Are there packaging or container considerations relevant to stability?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B5. Stability, storage, packaging
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:07:52
- Finished: 2026-03-25T07:11:58
- Elapsed seconds: 246.0959
- Retrieval seconds: 38.6514
- Generation seconds: 0.0
- Estimated prompt tokens: 1474
- Estimated answer tokens: 1285

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there packaging or container considerations relevant to stability?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there packaging or container considerations relevant to stability?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6242
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6143
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.5908
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5730
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5701
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5574
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 47. Summarize formulation-related stability data and storage instructions.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B5. Stability, storage, packaging
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:08:35
- Finished: 2026-03-25T07:12:37
- Elapsed seconds: 242.5534
- Retrieval seconds: 39.1959
- Generation seconds: 0.0001
- Estimated prompt tokens: 1474
- Estimated answer tokens: 1285

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize formulation-related stability data and storage instructions." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize formulation-related stability data and storage instructions.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6342
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6246
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6162
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5920
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5801
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5779
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 8
```

## 48. What formulation details are most relevant for generic development?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B6. R&D / generic development
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:09:18
- Finished: 2026-03-25T07:13:16
- Elapsed seconds: 238.065
- Retrieval seconds: 38.3775
- Generation seconds: 0.0
- Estimated prompt tokens: 1566
- Estimated answer tokens: 1297

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What formulation details are most relevant for generic development?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What formulation details are most relevant for generic development?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.9298
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9095
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9019
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8814
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8677
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8536
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 8
```

## 49. Which excipients or formulation characteristics may be critical quality attributes?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B6. R&D / generic development
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:09:59
- Finished: 2026-03-25T07:13:54
- Elapsed seconds: 234.2292
- Retrieval seconds: 37.7948
- Generation seconds: 0.0
- Estimated prompt tokens: 1490
- Estimated answer tokens: 1270

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which excipients or formulation characteristics may be critical quality attributes?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which excipients or formulation characteristics may be critical quality attributes?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8082
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant (chlorhexidine gluconate formulation) FERMASCRUB 4%FERMASCRUB 4%

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 20mL in 100mL
(Contains 4w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales appr
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.7915
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.7828
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=5.7815
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=5.7760
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 6 | section=dosage | score=5.7734
  IV.Items related to formulations
1. Dosage form

(1) Route of administrationExternal use

(2) Distinction of dosage forms, specifications, and properties Distinction of dosage forms: Liquid <0.02%> Specifications: Contains 0.02 w/v% of chlorhexidine gluconate when quantitatively determined. Properties: Colorless to pale yellow clear liquid with no odor and slightly bitter taste. <0.05%> Specification: Contains 0.05w/v% of chlorhexidine gluconate when quantitatively determined. Properties: Clear, colorless liquid with a slightly bitter taste. <0.1%> Specification: Contains 0.1w/v% of chlorhexidine gluconate when quantifying. Properties: Colorless to pale yellow clear liquid with no odor and s

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 6
```

## 50. What formulation warnings should be reviewed before reformulation?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B6. R&D / generic development
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:10:42
- Finished: 2026-03-25T07:14:32
- Elapsed seconds: 230.0394
- Retrieval seconds: 38.2723
- Generation seconds: 0.0
- Estimated prompt tokens: 1431
- Estimated answer tokens: 1238

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What formulation warnings should be reviewed before reformulation?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What formulation warnings should be reviewed before reformulation?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9851
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.9473
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.4046
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm
- chlorhexidine gluconate | interview_form | page 21 | section=warning | score=6.3744
  15
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]

3. Precautions
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.3468
  6. Important basic precautions, their reasons and treatment methods
(1) In order to predict reactions such as shock and anaphylaxis, please conduct a thorough interview regarding your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug hypersensitivity before use. (2) Be sure to dilute this drug and use with caution when using the concentration*1. (3) The diluted aqueous solution of this drug used on the wound site should be sterilized after preparation. (4) Do not use for obstetrics and gynecology (disinfecting the vagina and vulva, etc.) or urology (disinfecting the bladder and external genitalia, etc.)*2.

(Explanation) *1 In order to al
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2815
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 26
- chlorhexidine gluconate / interview_form / page 21
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 5
```

## 51. Which sample documents contain excipient information?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B6. R&D / generic development
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:11:20
- Finished: 2026-03-25T07:15:09
- Elapsed seconds: 229.8473
- Retrieval seconds: 37.5532
- Generation seconds: 0.0
- Estimated prompt tokens: 1407
- Estimated answer tokens: 1188

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which sample documents contain excipient information?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which sample documents contain excipient information?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9668
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9581
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9551
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9337
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9224
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 32 | section=general | score=5.9196
  26
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 32
```

## 52. Which document is better for excipient details: label or patient guide?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B6. R&D / generic development
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:11:58
- Finished: 2026-03-25T07:17:28
- Elapsed seconds: 330.2133
- Retrieval seconds: 139.0118
- Generation seconds: 0.0001
- Estimated prompt tokens: 1227
- Estimated answer tokens: 1066

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which document is better for excipient details: label or patient guide?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which document is better for excipient details: label or patient guide?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.6537
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6461
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6257
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6121
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=5.5976
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | interview_form | page 18 | section=dosage | score=5.5960
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 18
```

## 53. Summarize composition, excipients, stability, and formulation-related safety risks.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > B. Formulation / composition / excipient / safety > B6. R&D / generic development
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:12:37
- Finished: 2026-03-25T07:18:08
- Elapsed seconds: 330.4066
- Retrieval seconds: 39.3959
- Generation seconds: 0.0
- Estimated prompt tokens: 1478
- Estimated answer tokens: 1288

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize composition, excipients, stability, and formulation-related safety risks." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize composition, excipients, stability, and formulation-related safety risks.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6218
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6123
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6003
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5879
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5783
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5695
  (3) Physical properties of the formulation
Specific gravity d: approx. 1.00 to 1.01

(4) Identification code

(5) Sterile or non-sterile preparations

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Active ingredient content〈0.05%〉
100mL of this product contains 0.05g of chlorhexidine gluconate.
<0.1%>
100mL of this product contains 0.1g of chlorhexidine gluconate.
<0.5%>
100mL of this product contains 0.5g of chlorhexidine gluconate.

(2) Additive polyoxyethylene nonylphenyl ether, red No. 2

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5.

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
```

## 54. Summarize the pharmacokinetics of this drug.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:13:16
- Finished: 2026-03-25T07:18:48
- Elapsed seconds: 331.7248
- Retrieval seconds: 39.6974
- Generation seconds: 0.0
- Estimated prompt tokens: 1554
- Estimated answer tokens: 1298

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the pharmacokinetics of this drug." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize the pharmacokinetics of this drug.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.5180
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.5115
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4915
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4835
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4608
  9

VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply.

(2) Blood levels confirmed in clinical trials do not apply.

(3) No data applicable to the toxic range

(4) Effects of food and concomitant medications Not applicable

2. Pharmacokinetic parameters
(1) Analysis method not applicable

(2) Absorption rate constant No relevant data available

(3) Disappearance rate constant not applicable

(4) Clearance not applicable

(5) Distribution volume not applicable

(6) No other relevant materials

3.Population analysis
(1) No relevant data for analysis method

(2) Parameter variation factors No applicable data
- chlorhexidine gluconate | interview_form | page 9 | section=pk | score=7.4287
  <W> Glucodin W ・Ethanol solution 0.5%

<B> Glucodin B ・Ethanol solution 0.5%

<R> Glucodin R ・Ethanol solution 0.5%
VI. Items related to drug efficacy and pharmacology
1. Pharmacologically relevant
compound or group of compounds

2. Pharmacological effects

(1) Site of action/Mechanism of action (1) Chlorhexidine gluconate solution acts on a wide range of microorganisms, and exhibits rapid bactericidal action against Gram-positive bacteria even at low concentrations2,3). Although it is effective against Gram-negative bacteria at relatively low concentrations, there is a wider range of susceptibility compared to Gram-positive bacteria4). (2) Although many fungi are susceptible, they are gener

Sources:
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 9
```

## 55. What are the key pharmacokinetic parameters such as Cmax, Tmax, AUC, and half-life?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:13:54
- Finished: 2026-03-25T07:19:26
- Elapsed seconds: 332.8159
- Retrieval seconds: 38.8848
- Generation seconds: 0.0
- Estimated prompt tokens: 1564
- Estimated answer tokens: 1309

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the key pharmacokinetic parameters such as Cmax, Tmax, AUC, and half-life?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the key pharmacokinetic parameters such as Cmax, Tmax, AUC, and half-life?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.5061
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.4804
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.4700
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4572
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4504
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4304
  9

VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply.

(2) Blood levels confirmed in clinical trials do not apply.

(3) No data applicable to the toxic range

(4) Effects of food and concomitant medications Not applicable

2. Pharmacokinetic parameters
(1) Analysis method not applicable

(2) Absorption rate constant No relevant data available

(3) Disappearance rate constant not applicable

(4) Clearance not applicable

(5) Distribution volume not applicable

(6) No other relevant materials

3.Population analysis
(1) No relevant data for analysis method

(2) Parameter variation factors No applicable data

Sources:
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 14
```

## 56. Describe the time course of plasma concentrations.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:14:32
- Finished: 2026-03-25T07:20:08
- Elapsed seconds: 336.2767
- Retrieval seconds: 41.7296
- Generation seconds: 0.0
- Estimated prompt tokens: 1408
- Estimated answer tokens: 1189

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Describe the time course of plasma concentrations." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Describe the time course of plasma concentrations.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- Chlorhexidine Gluconate | smpc_label | page 2 | section=general | score=5.8444
  Candida albicans
TIMM 1623
0.004
within 30 seconds
*100 times diluted solution of 5% chlorhexidine gluconate solution "Metal"
Indicates the bactericidal effect of liquid (0.05w/v%).
19. Physical and chemical knowledge regarding active ingredients
Common name: Chlorhexidine Gluconate Solution
Chemical name: 1,1′-Hexamethylenebis[5-(4-chlorophenyl)biguanide],di-D-
gluconate
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76
Properties: Chlorhexidine gluconate solution is a colorless to slightly yellow clear liquid with no odor and a bitter taste. Miscible with water or acetic acid (100). Chlorhexidine gluconate
1mL of liquid is 5mL or less of ethanol (99.5) or 3mL of acetone.
It
- chlorhexidine gluconate | interview_form | page 7 | section=adverse_event | score=5.8291
  1
I. Items related to overview

1. Development history
Chlorhexidine gluconate is a biguanide disinfectant that has a broad antimicrobial spectrum against Gram-positive and Gram-negative bacteria and exhibits rapid bactericidal action even at low concentrations. Chlorhexidine gluconate preparations are currently commercialized in Japan as 20w/v% liquid preparations, 5w/v% liquid preparations, and sterile preparations that have already been prepared to use concentrations. The concentrated solution is prepared by diluting it into an aqueous solution or an alcoholic solution of various concentrations depending on the purpose, and is sterilized as necessary before use. Furthermore, hand rub disi
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=5.8027
  (3) Physical properties of the formulation
Specific gravity d: approx. 1.00 to 1.01

(4) Identification code

(5) Sterile or non-sterile preparations

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Active ingredient content〈0.05%〉
100mL of this product contains 0.05g of chlorhexidine gluconate.
<0.1%>
100mL of this product contains 0.1g of chlorhexidine gluconate.
<0.5%>
100mL of this product contains 0.5g of chlorhexidine gluconate.

(2) Additive polyoxyethylene nonylphenyl ether, red No. 2

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5.
- chlorhexidine gluconate | interview_form | page 13 | section=indication | score=5.7970
  Enterobacter cloacae IFO 13595

7.81

Serratia marcescens IFO 12498

31.3

Note 1) MIC (μg/mL) indicates the concentration of chlorhexidine gluconate. (2) No relevant data on test results supporting drug efficacy (3) No relevant data on onset time/duration of action
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7865
  1
I. Items related to overview

1. Development history
This agent is a topical disinfectant containing chlorhexidine gluconate as an active ingredient. “5% Chlorhexidine Gluconate Solution/OY” was developed and planned by Oriental Pharmaceutical Co., Ltd.
We established the product rating and test method, conducted stability tests, and bactericidal power tests, and obtained approval on February 12, 2004.
Sales began on August 3, 2017. (Approval application based on Pharmaceutical Notification No. 481 (April 8, 1999))
Nichi-Iko Co., Ltd. began selling it on January 1, 2006.
On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.
On Ju
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7848
  I. Items related to overview

1. Development history

Povidone-iodine preparations are the mainstream for hand and skin disinfection in medical institutions, but they have drawbacks such as being difficult to dry and taking a long time to develop their effects. In addition, although alcohol preparations have excellent immediate disinfecting effects, they also have the disadvantage of short lasting activity. On the other hand, there are reports that chlorhexidine gluconate has a longer-lasting disinfectant effect than povidone-iodine preparations, and that it suppresses the incidence of surgical site infections and catheter-related bloodstream infections 1), 2). Among these, alcohol-containin

Sources:
- Chlorhexidine Gluconate / smpc_label / page 2
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 13
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
```

## 57. What population pharmacokinetic analyses are reported?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:15:09
- Finished: 2026-03-25T07:20:55
- Elapsed seconds: 345.1715
- Retrieval seconds: 46.4543
- Generation seconds: 0.0
- Estimated prompt tokens: 1556
- Estimated answer tokens: 1302

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What population pharmacokinetic analyses are reported?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What population pharmacokinetic analyses are reported?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.5300
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.5000
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.4897
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4749
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4682
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4466
  9

VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply.

(2) Blood levels confirmed in clinical trials do not apply.

(3) No data applicable to the toxic range

(4) Effects of food and concomitant medications Not applicable

2. Pharmacokinetic parameters
(1) Analysis method not applicable

(2) Absorption rate constant No relevant data available

(3) Disappearance rate constant not applicable

(4) Clearance not applicable

(5) Distribution volume not applicable

(6) No other relevant materials

3.Population analysis
(1) No relevant data for analysis method

(2) Parameter variation factors No applicable data

Sources:
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 14
```

## 58. Summarize absorption, distribution, metabolism, and excretion.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:17:28
- Finished: 2026-03-25T07:21:34
- Elapsed seconds: 245.6255
- Retrieval seconds: 39.4642
- Generation seconds: 0.0
- Estimated prompt tokens: 1383
- Estimated answer tokens: 1166

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize absorption, distribution, metabolism, and excretion." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize absorption, distribution, metabolism, and excretion.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8416
  Revised October 2007 (3rd edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

0.05% Glucodin R water
0.1% Glucodin R water
0.5% Glucodin R water
Glucodine R Water

Dosage form liquid drug specifications/content
0.05%: Contains 0.05g of chlorhexidine gluconate in 100mL.
0.1%: Contains 0.1 g of chlorhexidine gluconate in 100mL.
0.5%: Contains 0.5 g of chlorhexidine gluconate in 100mL.
Generic name Japanese name: Chlorhexidine gluconate Western name: Chlorhexidine Gluconate Date of manufacturing
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8196
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=5.7806
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7497
  2. Therapeutic properties of the product
(1) This agent is a quick-drying hand rub that contains chlorhexidine gluconate as an active ingredient. (2) Shock and anaphylaxis have been reported as serious side effects. (See section “VIII.8.(1) Serious side effects and early symptoms”)
3. Pharmaceutical properties of the product
(1) This drug is an ethanol solution containing 0.2g of chlorhexidine gluconate. (2) Contains a humectant (glycerin) to prevent rough hands.
(3) Packaging specifications include portable 60mL (poly: spray), 500mL (poly: square type), 1L (poly: square type) and
There is 5L (poly).
4.Characteristics that should be known regarding proper use
Materials related to proper use,
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7427
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=5.7363
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 18
```

## 59. What is known about oral absorption and bioavailability?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:18:08
- Finished: 2026-03-25T07:22:17
- Elapsed seconds: 248.7366
- Retrieval seconds: 42.5022
- Generation seconds: 0.0
- Estimated prompt tokens: 1539
- Estimated answer tokens: 1296

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What is known about oral absorption and bioavailability?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What is known about oral absorption and bioavailability?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9204
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.8956
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 8 | section=general | score=5.8518
  II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine GLUCONATE SOLUTION DISINFECTION CLOTH 4 x 4 disinfectant cloth (2) Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH (3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution (ethanol solution) containing 1w/v% chlorhexidine gluconate as an active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.
2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN) (3) Stem: unknown
3. Structural formula or demonstrative formula
4.Molecular formula and molecular weight
Molecular for
- chlorhexidine gluconate | interview_form | page 8 | section=dosage | score=5.8322
  2
II. Items related to name

1. Brand name
(1) Japanese name: Stericlone® Liquid 5

(2) Western name: STERICLON® SOLUTION 5

(3) Origin of name: The brand name Stericlone was derived from Steri...lize (to disinfect) and chlorhexidine gluconate, and the name was derived from ``brand name + dosage form + active ingredient concentration''.

2. Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate solution (JAN)

(2) Western name (nomenclature): Chlorhexidine Gluconate (JAN, USAN) Chlorhexidine Gluconate Solution (USP) Chlorhexidine Digluconate Solution (EP) Chlorhexidine (INN)

(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4. Molecular fo
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.8087
  1
I. Items related to overview
1. Development history
This agent is a topical disinfectant containing chlorhexidine gluconate as an active ingredient.

“Yakuhan” is a 20% chlorhexidine gluconate solution developed by Yakuhan Pharmaceutical Co., Ltd.
Established standards and test methods, conducted stability tests and bactericidal power tests, and approved on February 24, 2005.
Sales began on June 13, 2005.

Nichiiko Co., Ltd. began selling this drug on April 16, 2012.

2. Therapeutic and pharmaceutical properties of the product
(1) This agent is a topical disinfectant containing 19.0~21.0w/v% of chlorhexidine gluconate.
Ru.
(2) The packaging standard is a 500mL rectangular volume-reducing c
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.8083
  - 2 -
1.Selling name
1)Japanese name
2) Western name
3) Origin of the name
2.Common name
1) Japanese name (nomenclature)
2) Western name (nomenclature)
3) Stem
3. Structural formula or demonstrative formula
4.Molecular formula and molecular weight
5.Chemical name (nomenclature)
6.Usual name, alias, abbreviation
number, symbol number
7.CAS registration number
Micro shield scrab solution 4 %Micro:Very small. Shield: protect, block. Chlorhexidine Gluconate Solution (JP) Chlorhexidine (INN) Unknown

Molecular formula: C22H30Cl2N10・2C6H12O7 (chlorhexidine gluconate)
Molecular weight: 897.77 (chlorhexidine gluconate)
1,1’-hexamethylenebis[5-(4-chlorophenyl)biguanide] digluconate(IUPAC)
Other name:

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
```

## 60. What are the metabolism pathways and major enzymes involved?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:18:48
- Finished: 2026-03-25T07:22:57
- Elapsed seconds: 249.0126
- Retrieval seconds: 39.9774
- Generation seconds: 0.0
- Estimated prompt tokens: 1102
- Estimated answer tokens: 984

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the metabolism pathways and major enzymes involved?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the metabolism pathways and major enzymes involved?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 32 | section=general | score=5.8715
  26
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 31 | section=general | score=5.8715
  25
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% Chlorhexidine Gluconate HIBICLENS® (USA): 4w/v% Chlorhexidine Gluconate HIBISTAT® (USA): 0.5w/w% Chlorhexidine Gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 34 | section=general | score=5.8714
  28
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 5 | section=stability | score=5.7278
  6. Common names, aliases, abbreviations,
symbol number

7. CAS Registration Number
55-56-1(Chlorhexidine)
18472-51-0(Chlorhexidine Gluconate)

III. Items related to active ingredients
1. Regulatory classification of active ingredients
common medicine

2. Physicochemical properties

(1) Appearance/Properties Chlorhexidine gluconate usually exists as an aqueous solution, and its 20w/v% solution is a colorless to slightly yellow clear liquid with no odor and a bitter taste.

(2) Solubility
Miscible with water or acetic acid (100). 1mL of 20w/v% solution is 5mL of ethanol (99.5)
It is miscible with less than 3 mL of acetone, but becomes cloudy when increasing the amount of solvent.

(3) Hygrosco
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.7175
  -3-

III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Characteristics: Colorless to slightly yellow, clear liquid with no odor and bitter taste. (2) Solubility Miscible with water or acetic acid (100).
1 mL is miscible with less than 5 mL of ethanol (99.5) or less than 3 mL of acetone, but the solvent
becomes cloudy when increasing the amount of (3) No relevant data on hygroscopicity (4) No relevant data on melting point (decomposition point), boiling point, freezing point (5) No relevant data on acid-base dissociation constant (6) No relevant data on partition coefficient (7) Other major values
pH: The pH of a solution of 5.0mL of this product dissolved i
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.7164
  - 3 -
1.Physicochemical properties
1) Appearance/properties
2) Solubility
3) Hygroscopicity
4) Melting point (decomposition point),
boiling point, freezing point
5) Acid-base dissociation constant
6) Partition coefficient
7)Other main indications
value
2. Various conditions for active ingredients
stability under

JP Chlorhexidine Gluconate Solution, a colorless to slightly yellow clear liquid obtained as a 20% (w/v) aqueous solution, with no odor and a bitter taste.
This product is miscible with water or acetic acid (100). 1 mL of this product is less than 5 mL of ethanol (99.5)
Or, it is miscible with less than 3 mL of acetone, but becomes cloudy when the amount of solvent is increased. Chl

Sources:
- chlorhexidine gluconate / interview_form / page 32
- chlorhexidine gluconate / interview_form / page 31
- chlorhexidine gluconate / interview_form / page 34
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 8
```

## 61. What transporters are mentioned in the pharmacokinetic section?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:19:26
- Finished: 2026-03-25T07:23:35
- Elapsed seconds: 248.9491
- Retrieval seconds: 38.8191
- Generation seconds: 0.0
- Estimated prompt tokens: 1500
- Estimated answer tokens: 1295

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What transporters are mentioned in the pharmacokinetic section?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What transporters are mentioned in the pharmacokinetic section?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.5245
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.4927
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.4882
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 21 | section=pk | score=7.4844
  - 16 -

6. Excretion
1) Excretion site and route

2) Excretion rate

3) Excretion rate

7. Regarding transporters
Information to do

8. Removal rate by dialysis etc.

<Reference>7)
After oral administration of 14C-labeled chlorhexidine gluconate, it was detected in feces and urine.
The total amount detected over the 7 days is shown in the table below. There was little absorption from the gastrointestinal tract and it was excreted in the feces.

Animal species Dose (mg/kg) Urine (%) Feces (%) Rat
5
0.4
99.5
mouse
8
3.7
101.6
dog
5
0.8
102.0

Almost 100% in feces (listed in the table above).

No applicable materials.

No applicable materials.

Not applicable.
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4688
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4622
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.

Sources:
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 21
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
```

## 62. Are there pharmacokinetic data in renal or hepatic impairment?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:20:08
- Finished: 2026-03-25T07:24:14
- Elapsed seconds: 246.2225
- Retrieval seconds: 39.006
- Generation seconds: 0.0
- Estimated prompt tokens: 1558
- Estimated answer tokens: 1304

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there pharmacokinetic data in renal or hepatic impairment?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there pharmacokinetic data in renal or hepatic impairment?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.5211
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.4956
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.4823
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4679
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4649
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.4535
  - 14 -
5. Distribution
(1) Passage through the blood-brain barrier No relevant data (2) Passage through the blood-placenta barrier No relevant data (3) Transfer to milk No relevant data (4) Transfer to cerebrospinal fluid No applicable data (5) Transfer to other tissues No applicable data (6) Plasma protein binding rate No applicable data
6. Metabolism
(1) No relevant data on metabolic site and metabolic pathway (2) No relevant data on molecular species and contribution rate of enzymes involved in metabolism (CYP, etc.) (3) No relevant data on first-pass effect and its proportion (4) No relevant data on metabolite activity, activity ratio, and abundance ratio
7. Excretion
5% or 4% labeled ch

Sources:
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 19
```

## 63. Summarize pharmacokinetics in special populations.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C1. Pharmacokinetics
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:20:55
- Finished: 2026-03-25T07:24:56
- Elapsed seconds: 241.1912
- Retrieval seconds: 41.422
- Generation seconds: 0.0
- Estimated prompt tokens: 1555
- Estimated answer tokens: 1300

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize pharmacokinetics in special populations." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize pharmacokinetics in special populations.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.5087
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.5065
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4810
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4742
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4520
  9

VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply.

(2) Blood levels confirmed in clinical trials do not apply.

(3) No data applicable to the toxic range

(4) Effects of food and concomitant medications Not applicable

2. Pharmacokinetic parameters
(1) Analysis method not applicable

(2) Absorption rate constant No relevant data available

(3) Disappearance rate constant not applicable

(4) Clearance not applicable

(5) Distribution volume not applicable

(6) No other relevant materials

3.Population analysis
(1) No relevant data for analysis method

(2) Parameter variation factors No applicable data
- chlorhexidine gluconate | interview_form | page 9 | section=pk | score=7.4211
  <W> Glucodin W ・Ethanol solution 0.5%

<B> Glucodin B ・Ethanol solution 0.5%

<R> Glucodin R ・Ethanol solution 0.5%
VI. Items related to drug efficacy and pharmacology
1. Pharmacologically relevant
compound or group of compounds

2. Pharmacological effects

(1) Site of action/Mechanism of action (1) Chlorhexidine gluconate solution acts on a wide range of microorganisms, and exhibits rapid bactericidal action against Gram-positive bacteria even at low concentrations2,3). Although it is effective against Gram-negative bacteria at relatively low concentrations, there is a wider range of susceptibility compared to Gram-positive bacteria4). (2) Although many fungi are susceptible, they are gener

Sources:
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 9
```

## 64. What are the key PK findings?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C2. Interview form / deep technical routing
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:21:34
- Finished: 2026-03-25T07:25:35
- Elapsed seconds: 240.9374
- Retrieval seconds: 39.21
- Generation seconds: 0.0
- Estimated prompt tokens: 1492
- Estimated answer tokens: 1287

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the key PK findings?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the key PK findings?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.2829
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.2506
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.2447
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 21 | section=pk | score=7.2375
  - 16 -

6. Excretion
1) Excretion site and route

2) Excretion rate

3) Excretion rate

7. Regarding transporters
Information to do

8. Removal rate by dialysis etc.

<Reference>7)
After oral administration of 14C-labeled chlorhexidine gluconate, it was detected in feces and urine.
The total amount detected over the 7 days is shown in the table below. There was little absorption from the gastrointestinal tract and it was excreted in the feces.

Animal species Dose (mg/kg) Urine (%) Feces (%) Rat
5
0.4
99.5
mouse
8
3.7
101.6
dog
5
0.8
102.0

Almost 100% in feces (listed in the table above).

No applicable materials.

No applicable materials.

Not applicable.
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.2255
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.2186
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.

Sources:
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 21
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
```

## 65. What does the interview form say about storage and stability?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C2. Interview form / deep technical routing
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:22:17
- Finished: 2026-03-25T07:26:28
- Elapsed seconds: 251.2593
- Retrieval seconds: 52.8238
- Generation seconds: 0.0
- Estimated prompt tokens: 1472
- Estimated answer tokens: 1282

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What does the interview form say about storage and stability?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What does the interview form say about storage and stability?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6220
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6125
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6045
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5811
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5675
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5655
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 66. Which section of the interview form describes composition and formulation?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C2. Interview form / deep technical routing
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:22:57
- Finished: 2026-03-25T07:27:17
- Elapsed seconds: 260.5525
- Retrieval seconds: 49.2724
- Generation seconds: 0.0
- Estimated prompt tokens: 1567
- Estimated answer tokens: 1306

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which section of the interview form describes composition and formulation?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which section of the interview form describes composition and formulation?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=6.5744
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=6.5653
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=6.5526
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.5449
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=6.5380
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=6.5250
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201

Sources:
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
```

## 67. Show evidence from the pharmacokinetics section.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C2. Interview form / deep technical routing
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:23:35
- Finished: 2026-03-25T07:28:11
- Elapsed seconds: 276.0486
- Retrieval seconds: 54.3131
- Generation seconds: 0.0001
- Estimated prompt tokens: 1496
- Estimated answer tokens: 1291

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show evidence from the pharmacokinetics section." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show evidence from the pharmacokinetics section.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.5041
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.5005
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 21 | section=pk | score=7.4916
  - 16 -

6. Excretion
1) Excretion site and route

2) Excretion rate

3) Excretion rate

7. Regarding transporters
Information to do

8. Removal rate by dialysis etc.

<Reference>7)
After oral administration of 14C-labeled chlorhexidine gluconate, it was detected in feces and urine.
The total amount detected over the 7 days is shown in the table below. There was little absorption from the gastrointestinal tract and it was excreted in the feces.

Animal species Dose (mg/kg) Urine (%) Feces (%) Rat
5
0.4
99.5
mouse
8
3.7
101.6
dog
5
0.8
102.0

Almost 100% in feces (listed in the table above).

No applicable materials.

No applicable materials.

Not applicable.
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4794
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4718
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4499
  9

VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply.

(2) Blood levels confirmed in clinical trials do not apply.

(3) No data applicable to the toxic range

(4) Effects of food and concomitant medications Not applicable

2. Pharmacokinetic parameters
(1) Analysis method not applicable

(2) Absorption rate constant No relevant data available

(3) Disappearance rate constant not applicable

(4) Clearance not applicable

(5) Distribution volume not applicable

(6) No other relevant materials

3.Population analysis
(1) No relevant data for analysis method

(2) Parameter variation factors No applicable data

Sources:
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 21
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
- chlorhexidine gluconate / interview_form / page 14
```

## 68. Summarize the stability data of the active ingredient.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:24:14
- Finished: 2026-03-25T07:29:14
- Elapsed seconds: 299.6889
- Retrieval seconds: 62.6461
- Generation seconds: 0.0
- Estimated prompt tokens: 1470
- Estimated answer tokens: 1281

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the stability data of the active ingredient." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize the stability data of the active ingredient.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6605
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6520
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6401
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.6129
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6045
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5946
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 69. Summarize the stability data of the finished formulation.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:24:56
- Finished: 2026-03-25T07:30:14
- Elapsed seconds: 318.6604
- Retrieval seconds: 60.3939
- Generation seconds: 0.0
- Estimated prompt tokens: 1471
- Estimated answer tokens: 1282

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the stability data of the finished formulation." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize the stability data of the finished formulation.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6419
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6324
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6151
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5965
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5875
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5870
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 8
```

## 70. What stability results are reported under long-term storage conditions?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:25:35
- Finished: 2026-03-25T07:31:06
- Elapsed seconds: 331.0345
- Retrieval seconds: 51.5846
- Generation seconds: 0.0
- Estimated prompt tokens: 1474
- Estimated answer tokens: 1285

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What stability results are reported under long-term storage conditions?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What stability results are reported under long-term storage conditions?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6387
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6314
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6293
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5946
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5822
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5802
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 71. What accelerated stability studies are reported?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:26:28
- Finished: 2026-03-25T07:31:46
- Elapsed seconds: 318.3583
- Retrieval seconds: 40.1482
- Generation seconds: 0.0001
- Estimated prompt tokens: 1469
- Estimated answer tokens: 1279

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What accelerated stability studies are reported?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What accelerated stability studies are reported?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6504
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6411
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6290
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.6019
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5918
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5884
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 72. What stress conditions were tested, such as heat, humidity, and light?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:27:17
- Finished: 2026-03-25T07:32:24
- Elapsed seconds: 307.0682
- Retrieval seconds: 37.9837
- Generation seconds: 0.0
- Estimated prompt tokens: 1026
- Estimated answer tokens: 954

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What stress conditions were tested, such as heat, humidity, and light?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What stress conditions were tested, such as heat, humidity, and light?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=5.8479
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | interview_form | page 18 | section=dosage | score=5.8463
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8454
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=5.8414
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8361
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 22 | section=general | score=5.8249
  It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to the use of chlorhexidine gluconate preparations7). (2) Information based on non-clinical studies is not set.

-17-

Sources:
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 22
```

## 73. What changes occur under light exposure or photostability testing?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:28:11
- Finished: 2026-03-25T07:33:03
- Elapsed seconds: 291.4997
- Retrieval seconds: 38.741
- Generation seconds: 0.0001
- Estimated prompt tokens: 1364
- Estimated answer tokens: 1203

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What changes occur under light exposure or photostability testing?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What changes occur under light exposure or photostability testing?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=6.4496
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=6.4398
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 7 | section=adverse_event | score=6.4059
  Medium Contains 0.1g of chlorhexidine gluconate (
0.1w/v%)

:1) It has been diluted so it can be used as is. [Prevention of measurement/dilution errors] Contains 0.5g of chlorhexidine gluconate (medium)
0.5w/v%) Since it uses a volume-reducing bottle, it can be folded to reduce the volume and be disposed of, reducing disposal costs.
Ru. (12) Shock and anaphylaxis may occur as serious side effects.
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=6.4050
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=6.3974
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=6.3906
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 4
```

## 74. Are there any notable degradation risks or changes in appearance?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:29:14
- Finished: 2026-03-25T07:33:41
- Elapsed seconds: 266.8551
- Retrieval seconds: 38.0039
- Generation seconds: 0.0
- Estimated prompt tokens: 1567
- Estimated answer tokens: 1298

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there any notable degradation risks or changes in appearance?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there any notable degradation risks or changes in appearance?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8527
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=5.8431
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.8131
  4

IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form Liquid preparation for external use

(2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant 5% "Shioe" Color/Appearance: Red and clear liquid.

(3)Identification code not applicable

(4) No relevant data on physical properties of the preparation

(5)Other sterility: Not a sterile preparation

2. Composition of the formulation
(1)Content of active ingredient (active ingredient) and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Shioe" Active ingredient
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as
- chlorhexidine gluconate | interview_form | page 9 | section=dosage | score=5.8018
  4
IV.Items related to formulations

1.Dosage form
(1) Distinction of dosage form External liquid (2) Appearance and properties of the preparation Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichi-Iko" Dosage form/properties A clear red liquid with no odor. (3) Identification code not applicable (4) Physical properties of the drug product (see section “IV.6. Stability of drug products under various conditions”) (5) Others
pH:5.5~7.0(1→5)
specific gravity d
20
20:1.009~1.029
Not a sterile preparation
2. Composition of the formulation
(1)Content of active ingredients and additives Brand name: Chlorhexidine gluconate disinfectant solution 5% "Nichiiko" Active ingredients
100mL
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.7913
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 20 | section=indication | score=5.7688
  15
X. Items related to administrative matters

1.Regulatory classification
Preparation: Chlorhexidine gluconate scrub 4% "Nichiiko" No active ingredient: No chlorhexidine gluconate solution
2. Validity period
Validity period: 3 years
3. Storage method in packaged state
Store at room temperature
4.Precautions for handling
20. Handling precautions
Use the product as soon as possible after opening the container, even if it is within the expiration date.
5.Materials for patients
Medication guide for patients: Lost bookmark: Yes Other materials for patients: No
6.Same ingredients/same efficacy drugs
Same ingredients: Chlorhexidine gluconate disinfectant 5% "Nichiiko", chlorhexidine gluconate disi

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 20
```

## 75. What storage conditions and shelf-life are recommended?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:30:14
- Finished: 2026-03-25T07:34:19
- Elapsed seconds: 244.1054
- Retrieval seconds: 37.6442
- Generation seconds: 0.0
- Estimated prompt tokens: 1470
- Estimated answer tokens: 1273

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What storage conditions and shelf-life are recommended?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What storage conditions and shelf-life are recommended?
Drug filter: chlorhexidine gluconate
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.0455
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.0361
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.0321
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=6.9965
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=6.9870
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=6.9818
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 76. Are there data on post-reconstitution or post-preparation stability?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:31:06
- Finished: 2026-03-25T07:34:59
- Elapsed seconds: 233.0585
- Retrieval seconds: 40.536
- Generation seconds: 0.0
- Estimated prompt tokens: 1474
- Estimated answer tokens: 1284

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there data on post-reconstitution or post-preparation stability?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there data on post-reconstitution or post-preparation stability?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6118
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6019
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.5878
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5679
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5587
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5552
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 77. Summarize stability, storage, and packaging-related precautions.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C3. Stability
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:31:46
- Finished: 2026-03-25T07:35:39
- Elapsed seconds: 232.6776
- Retrieval seconds: 39.765
- Generation seconds: 0.0001
- Estimated prompt tokens: 1473
- Estimated answer tokens: 1286

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize stability, storage, and packaging-related precautions." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize stability, storage, and packaging-related precautions.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: warning, stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5974
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.5879
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.5805
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5621
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5457
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5450
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 78. Summarize the Risk Management Plan for this drug.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:32:24
- Finished: 2026-03-25T07:36:17
- Elapsed seconds: 232.707
- Retrieval seconds: 38.0141
- Generation seconds: 0.0
- Estimated prompt tokens: 1111
- Estimated answer tokens: 997

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the Risk Management Plan for this drug." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize the Risk Management Plan for this drug.
Drug filter: chlorhexidine gluconate
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=6.9674
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.5686
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.5653
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=6.5111
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 8 | section=rmp | score=6.4073
  2
(3) Since there is no need to prepare disinfectants, sterile cotton balls, sterile cotton swabs, or wash and sterilize universal pots and forceps, it is possible to save labor in hospital preparation work. (4) Since it is a single-use package, it can be used hygienically by preventing unsanitary uses such as adding disinfectants or cotton swabs. Furthermore, there is no need to manage the expiration date after preparation. (5) Convenient to carry and suitable for home medical care. (6) It is economical as it eliminates unnecessary consumption of disinfectants and cotton swabs that are left over.

4. Characteristics that should be known regarding proper use
Is there a material or optimal us
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=6.3329
  Table of contents

I. Items related to overview
1. Development history ............................. 1
2. Therapeutic properties of the product .......... 1
3. Pharmaceutical properties of the product ................ 1
4.Characteristics that should be known regarding proper use...... 1
5. Approval conditions and restrictions on distribution and use
...................................... 1
6.RMP overview ................................ 1

II. Items related to name
1. Brand name ................................ 2
2.Common name ................................ 2
3. Structural formula or demonstrative formula ..... 2
4.Molecular formula and molecular weight................... 2
5.Chemical name

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 4
```

## 79. What are the important identified risks in the RMP?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:33:03
- Finished: 2026-03-25T07:36:55
- Elapsed seconds: 232.1769
- Retrieval seconds: 38.2129
- Generation seconds: 0.0
- Estimated prompt tokens: 1032
- Estimated answer tokens: 976

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the important identified risks in the RMP?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the important identified risks in the RMP?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.3189
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1805
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1804
  VIII. Items related to safety (precautions, etc.)
1. Warning details and reasons ................ 12
2. Contraindications and their reasons .......... 12
3. Precautions related to efficacy or effects and their reasons
...................................... 12
4. Precautions and reasons related to usage and administration
................................................... 12
5.Important basic precautions and their reasons...... 12
6. Caution regarding patients with specific backgrounds
...................................... 12
7. Interaction ................................ 13
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.1148
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.0920
  10.Patients with specific backgrounds ................................ 13

11. Others ................................................................ 13

VIII. Items regarding safety (precautions, etc.) 14

1. Warning details and reasons .......................................... 14

2. Contraindications and their reasons ................................ 14

3. Precautions related to efficacy or effectiveness and their reasons... 14

4. Precautions and reasons related to usage and administration... 14

5.Important basic precautions and their reasons...... 14

6. Precautions regarding patients with specific backgrounds ...... 14

7. Interaction ...............................................
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.9232
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
```

## 80. What are the important potential risks in the RMP?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:33:41
- Finished: 2026-03-25T07:37:33
- Elapsed seconds: 232.4303
- Retrieval seconds: 38.2596
- Generation seconds: 0.0
- Estimated prompt tokens: 1032
- Estimated answer tokens: 976

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the important potential risks in the RMP?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the important potential risks in the RMP?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.3191
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1810
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1807
  VIII. Items related to safety (precautions, etc.)
1. Warning details and reasons ................ 12
2. Contraindications and their reasons .......... 12
3. Precautions related to efficacy or effects and their reasons
...................................... 12
4. Precautions and reasons related to usage and administration
................................................... 12
5.Important basic precautions and their reasons...... 12
6. Caution regarding patients with specific backgrounds
...................................... 12
7. Interaction ................................ 13
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.1152
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.0922
  10.Patients with specific backgrounds ................................ 13

11. Others ................................................................ 13

VIII. Items regarding safety (precautions, etc.) 14

1. Warning details and reasons .......................................... 14

2. Contraindications and their reasons ................................ 14

3. Precautions related to efficacy or effectiveness and their reasons... 14

4. Precautions and reasons related to usage and administration... 14

5.Important basic precautions and their reasons...... 14

6. Precautions regarding patients with specific backgrounds ...... 14

7. Interaction ...............................................
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.9235
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
```

## 81. What important missing information is listed in the RMP?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:34:19
- Finished: 2026-03-25T07:38:11
- Elapsed seconds: 232.57
- Retrieval seconds: 37.7819
- Generation seconds: 0.0
- Estimated prompt tokens: 1033
- Estimated answer tokens: 977

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What important missing information is listed in the RMP?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What important missing information is listed in the RMP?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.3208
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1853
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1831
  VIII. Items related to safety (precautions, etc.)
1. Warning details and reasons ................ 12
2. Contraindications and their reasons .......... 12
3. Precautions related to efficacy or effects and their reasons
...................................... 12
4. Precautions and reasons related to usage and administration
................................................... 12
5.Important basic precautions and their reasons...... 12
6. Caution regarding patients with specific backgrounds
...................................... 12
7. Interaction ................................ 13
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1684
  7. Preparation method and stability after dissolution ............. 5

8. Changes in combination with other drugs (physicochemical changes) ...... 5

9. Dissolution properties ................................................................ 5

10. Containers/Packaging ................................................ 6

11.Materials provided separately.................................. 6

12.Others ................................................................ 6

V. Items related to treatment 7

1.Efficacy or effect ................................................ 7

2. Precautions related to efficacy or effectiveness ................................ 7

3. Dosage and dosage ................
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.1187
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.9260
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 7
```

## 82. What routine pharmacovigilance activities are described in the RMP?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:34:59
- Finished: 2026-03-25T07:38:55
- Elapsed seconds: 236.301
- Retrieval seconds: 44.2665
- Generation seconds: 0.0
- Estimated prompt tokens: 1115
- Estimated answer tokens: 1009

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What routine pharmacovigilance activities are described in the RMP?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What routine pharmacovigilance activities are described in the RMP?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.3118
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1696
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.1057
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=6.9330
  Table of contents

I. Items related to overview
1. Development history ............................. 1
2. Therapeutic properties of the product .......... 1
3. Pharmaceutical properties of the product ................ 1
4.Characteristics that should be known regarding proper use...... 1
5. Approval conditions and restrictions on distribution and use
...................................... 1
6.RMP overview ................................ 1

II. Items related to name
1. Brand name ................................ 2
2.Common name ................................ 2
3. Structural formula or demonstrative formula ..... 2
4.Molecular formula and molecular weight................... 2
5.Chemical name
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.9168
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=6.9086
  7. Preparation method and stability after dissolution ............. 5

8. Changes in combination with other drugs (physicochemical changes) ...... 5

9. Dissolution properties ................................................................ 5

10. Containers/Packaging ................................................ 6

11.Materials provided separately.................................. 6

12.Others ................................................................ 6

V. Items related to treatment 7

1.Efficacy or effect ................................................ 7

2. Precautions related to efficacy or effectiveness ................................ 7

3. Dosage and dosage ................

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 4
```

## 83. What additional pharmacovigilance activities are described?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:35:39
- Finished: 2026-03-25T07:39:44
- Elapsed seconds: 245.5571
- Retrieval seconds: 49.0232
- Generation seconds: 0.0
- Estimated prompt tokens: 1207
- Estimated answer tokens: 1038

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What additional pharmacovigilance activities are described?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What additional pharmacovigilance activities are described?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=5.7771
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7751
  has been done. Additionally, the ``Guidelines for Standard Dialysis Operations and Infection Prevention in Dialysis Facilities (Sixth Edition)'' recommends using alcohol containing 1% or more of chlorhexidine gluconate to disinfect the skin at the puncture site, when inserting a dialysis catheter, and at the skin exit after insertion at the start of dialysis. As a result, there is an increasing demand for alcohol-containing preparations with 1% chlorhexidine gluconate as the active ingredient. ``Nipro'' is a formulation in which non-woven fabric is impregnated with a drug solution containing 1% chlorhexidine gluconate in ethanol as an active ingredient.``Nipro'' is a generic drug product wit
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7403
  2. Therapeutic properties of the product
(1) This agent is a quick-drying hand rub that contains chlorhexidine gluconate as an active ingredient. (2) Shock and anaphylaxis have been reported as serious side effects. (See section “VIII.8.(1) Serious side effects and early symptoms”)
3. Pharmaceutical properties of the product
(1) This drug is an ethanol solution containing 0.2g of chlorhexidine gluconate. (2) Contains a humectant (glycerin) to prevent rough hands.
(3) Packaging specifications include portable 60mL (poly: spray), 500mL (poly: square type), 1L (poly: square type) and
There is 5L (poly).
4.Characteristics that should be known regarding proper use
Materials related to proper use,
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7303
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7129
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate solution

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.7065
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 4
```

## 84. What routine risk minimization activities are described?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:36:17
- Finished: 2026-03-25T07:40:36
- Elapsed seconds: 259.5997
- Retrieval seconds: 52.0527
- Generation seconds: 0.0
- Estimated prompt tokens: 1204
- Estimated answer tokens: 1036

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What routine risk minimization activities are described?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What routine risk minimization activities are described?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=5.7827
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 6 | section=adverse_event | score=5.7474
  2. Therapeutic properties of the product
(1) This agent is a quick-drying hand rub that contains chlorhexidine gluconate as an active ingredient. (2) Shock and anaphylaxis have been reported as serious side effects. (See section “VIII.8.(1) Serious side effects and early symptoms”)
3. Pharmaceutical properties of the product
(1) This drug is an ethanol solution containing 0.2g of chlorhexidine gluconate. (2) Contains a humectant (glycerin) to prevent rough hands.
(3) Packaging specifications include portable 60mL (poly: spray), 500mL (poly: square type), 1L (poly: square type) and
There is 5L (poly).
4.Characteristics that should be known regarding proper use
Materials related to proper use,
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7328
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7153
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate solution

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 4 | section=general | score=5.7087
  I. Items related to overview
1. Development history
Chlorhexidine gluconate was developed by Davis in 1954 at the British laboratory of I.C.I.
It is a bactericidal disinfectant that has been reported as

2. Product features and usefulness

II. Items related to name
1. Brand name

(1) Japanese name: Chlorhexidine gluconate solution 20% “Yakuhan”

(2) Western name Chlorhexidine Gluconate Solution 20% "YAKUHAN"

(3) Origin of the name

2. Common name

(1) Japanese name: Chlorhexidine gluconate

(2) Western name Chlorhexidine Gluconate

3. Structural formula or demonstrative formula

4. Molecular formula and molecular weight
C22H30Cl2N10・2C6H12O7:897.76

5. Chemical name
2, 4, 11, 13-Tetraazatet
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.6982
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
```

## 85. What additional risk minimization materials are planned for patients or healthcare professionals?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:36:55
- Finished: 2026-03-25T07:44:30
- Elapsed seconds: 454.5152
- Retrieval seconds: 233.128
- Generation seconds: 0.0001
- Estimated prompt tokens: 1263
- Estimated answer tokens: 1102

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What additional risk minimization materials are planned for patients or healthcare professionals?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What additional risk minimization materials are planned for patients or healthcare professionals?
Drug filter: chlorhexidine gluconate
Doc type filter: patient_guide

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.6432
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6357
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6158
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.6043
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 32 | section=general | score=5.5896
  26
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 31 | section=general | score=5.5896
  25
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% Chlorhexidine Gluconate HIBICLENS® (USA): 4w/v% Chlorhexidine Gluconate HIBISTAT® (USA): 0.5w/w% Chlorhexidine Gluconate

2.Clinical support information overseas
No applicable materials

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 32
- chlorhexidine gluconate / interview_form / page 31
```

## 86. What effectiveness-related concerns are included in the RMP?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:37:33
- Finished: 2026-03-25T07:45:17
- Elapsed seconds: 463.7201
- Retrieval seconds: 47.4634
- Generation seconds: 0.0
- Estimated prompt tokens: 1114
- Estimated answer tokens: 1008

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What effectiveness-related concerns are included in the RMP?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What effectiveness-related concerns are included in the RMP?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.5576
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.3499
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1809
  Table of contents

I. Items related to overview
1. Development history ............................. 1
2. Therapeutic properties of the product .......... 1
3. Pharmaceutical properties of the product ................ 1
4.Characteristics that should be known regarding proper use...... 1
5. Approval conditions and restrictions on distribution and use
...................................... 1
6.RMP overview ................................ 1

II. Items related to name
1. Brand name ................................ 2
2.Common name ................................ 2
3. Structural formula or demonstrative formula ..... 2
4.Molecular formula and molecular weight................... 2
5.Chemical name
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1625
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1619
  7. Preparation method and stability after dissolution ............. 5

8. Changes in combination with other drugs (physicochemical changes) ...... 5

9. Dissolution properties ................................................................ 5

10. Containers/Packaging ................................................ 6

11.Materials provided separately.................................. 6

12.Others ................................................................ 6

V. Items related to treatment 7

1.Efficacy or effect ................................................ 7

2. Precautions related to efficacy or effectiveness ................................ 7

3. Dosage and dosage ................
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1608
  2
6.RMP Overview
Not applicable

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
```

## 87. What does the interview form or RMP say about RMP-related risks?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:38:11
- Finished: 2026-03-25T07:45:56
- Elapsed seconds: 465.3466
- Retrieval seconds: 39.4135
- Generation seconds: 0.0
- Estimated prompt tokens: 1114
- Estimated answer tokens: 1008

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What does the interview form or RMP say about RMP-related risks?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What does the interview form or RMP say about RMP-related risks?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.5372
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.3225
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1664
  Table of contents

I. Items related to overview
1. Development history ............................. 1
2. Therapeutic properties of the product .......... 1
3. Pharmaceutical properties of the product ................ 1
4.Characteristics that should be known regarding proper use...... 1
5. Approval conditions and restrictions on distribution and use
...................................... 1
6.RMP overview ................................ 1

II. Items related to name
1. Brand name ................................ 2
2.Common name ................................ 2
3. Structural formula or demonstrative formula ..... 2
4.Molecular formula and molecular weight................... 2
5.Chemical name
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1501
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1440
  7. Preparation method and stability after dissolution ............. 5

8. Changes in combination with other drugs (physicochemical changes) ...... 5

9. Dissolution properties ................................................................ 5

10. Containers/Packaging ................................................ 6

11.Materials provided separately.................................. 6

12.Others ................................................................ 6

V. Items related to treatment 7

1.Efficacy or effect ................................................ 7

2. Precautions related to efficacy or effectiveness ................................ 7

3. Dosage and dosage ................
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1339
  2
6.RMP Overview
Not applicable

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
```

## 88. What are the important identified risks and potential risks in the RMP documents?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:38:55
- Finished: 2026-03-25T07:46:42
- Elapsed seconds: 466.6454
- Retrieval seconds: 45.5607
- Generation seconds: 0.0
- Estimated prompt tokens: 1040
- Estimated answer tokens: 984

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the important identified risks and potential risks in the RMP documents?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the important identified risks and potential risks in the RMP documents?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.3007
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.1633
  VIII. Items related to safety (precautions, etc.)
1. Warning details and reasons ................ 12
2. Contraindications and their reasons .......... 12
3. Precautions related to efficacy or effects and their reasons
...................................... 12
4. Precautions and reasons related to usage and administration
................................................... 12
5.Important basic precautions and their reasons...... 12
6. Caution regarding patients with specific backgrounds
...................................... 12
7. Interaction ................................ 13
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1469
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.0868
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=7.0792
  10.Patients with specific backgrounds ................................ 13

11. Others ................................................................ 13

VIII. Items regarding safety (precautions, etc.) 14

1. Warning details and reasons .......................................... 14

2. Contraindications and their reasons ................................ 14

3. Precautions related to efficacy or effectiveness and their reasons... 14

4. Precautions and reasons related to usage and administration... 14

5.Important basic precautions and their reasons...... 14

6. Precautions regarding patients with specific backgrounds ...... 14

7. Interaction ...............................................
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=6.9041
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 7
```

## 89. Summarize the full RMP including risks, monitoring, and risk minimization actions.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > C. PK / stability / RMP > C4. RMP
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:39:44
- Finished: 2026-03-25T07:47:31
- Elapsed seconds: 466.6993
- Retrieval seconds: 49.0741
- Generation seconds: 0.0
- Estimated prompt tokens: 1119
- Estimated answer tokens: 1013

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the full RMP including risks, monitoring, and risk minimization actions." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize the full RMP including risks, monitoring, and risk minimization actions.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: rmp

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 6 | section=rmp | score=7.5395
  1
I. Items related to overview

1. Development history
This agent is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.

“Chlorhexidine gluconate scrub 4% “ORY”” was developed by Oriental Pharmaceutical Co., Ltd.
We planned the project, established standards and test methods, conducted stability tests and bactericidal power tests, and received approval on April 30, 2008.
Sales began on August 25, 2008. (Accepted based on Pharmaceutical Food and Food Safety No. 0331015 (March 31, 2005))
application)

On June 1, 2009, Oriental Pharmaceutical Industry Co., Ltd. changed its company name to Nichi-Iko Pharma Co., Ltd.

On June 1, 2012, Nichi-Iko Pharma Co., Lt
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1502
  4.Characteristics that should be known regarding proper use
Materials related to proper use, guidelines for promoting optimal use, etc. Title, reference RMP No materials created as an additional risk minimization activity Guidelines for promoting optimal use No insurance application considerations No notifications
5. Approval conditions and restrictions on distribution and use
(1) Approval conditions not applicable (2) Restrictions on distribution and use not applicable
6.RMP overview
Not applicable
-2-
- chlorhexidine gluconate | interview_form | page 7 | section=rmp | score=7.1210
  2
6.RMP Overview
Not applicable
- chlorhexidine gluconate | interview_form | page 3 | section=rmp | score=7.0652
  5. Clinical results................................................................... 6

VI. Items related to pharmacology ................................................ 9

1. Pharmacologically relevant compound or group of compounds ................................................ 9

2. Pharmacological effects ................................................................ 9
- chlorhexidine gluconate | interview_form | page 8 | section=rmp | score=6.9874
  2
(3) Since there is no need to prepare disinfectants, sterile cotton balls, sterile cotton swabs, or wash and sterilize universal pots and forceps, it is possible to save labor in hospital preparation work. (4) Since it is a single-use package, it can be used hygienically by preventing unsanitary uses such as adding disinfectants or cotton swabs. Furthermore, there is no need to manage the expiration date after preparation. (5) Convenient to carry and suitable for home medical care. (6) It is economical as it eliminates unnecessary consumption of disinfectants and cotton swabs that are left over.

4. Characteristics that should be known regarding proper use
Is there a material or optimal us
- chlorhexidine gluconate | interview_form | page 4 | section=rmp | score=6.9065
  Table of contents

I. Items related to overview
1. Development history ............................. 1
2. Therapeutic properties of the product .......... 1
3. Pharmaceutical properties of the product ................ 1
4.Characteristics that should be known regarding proper use...... 1
5. Approval conditions and restrictions on distribution and use
...................................... 1
6.RMP overview ................................ 1

II. Items related to name
1. Brand name ................................ 2
2.Common name ................................ 2
3. Structural formula or demonstrative formula ..... 2
4.Molecular formula and molecular weight................... 2
5.Chemical name

Sources:
- chlorhexidine gluconate / interview_form / page 6
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 3
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 4
```

## 90. What recent safety label changes mention this drug?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:40:36
- Finished: 2026-03-25T07:48:21
- Elapsed seconds: 464.3256
- Retrieval seconds: 49.6845
- Generation seconds: 0.0
- Estimated prompt tokens: 1561
- Estimated answer tokens: 1292

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What recent safety label changes mention this drug?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What recent safety label changes mention this drug?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9092
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9014
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.8956
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8810
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8688
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 8 | section=general | score=5.8517
  II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine GLUCONATE SOLUTION DISINFECTION CLOTH 4 x 4 disinfectant cloth (2) Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH (3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution (ethanol solution) containing 1w/v% chlorhexidine gluconate as an active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.
2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN) (3) Stem: unknown
3. Structural formula or demonstrative formula
4.Molecular formula and molecular weight
Molecular for

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 8
```

## 91. What new safety changes were issued for this drug?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:44:30
- Finished: 2026-03-25T07:49:06
- Elapsed seconds: 276.4173
- Retrieval seconds: 45.2207
- Generation seconds: 0.0
- Estimated prompt tokens: 1392
- Estimated answer tokens: 1173

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What new safety changes were issued for this drug?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What new safety changes were issued for this drug?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.9333
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9251
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9212
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.9032
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8906
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=5.8836
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 23
```

## 92. Are there safety warnings about fulminant hepatitis, severe skin reactions, or interstitial pneumonia?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:45:17
- Finished: 2026-03-25T07:49:54
- Elapsed seconds: 276.6475
- Retrieval seconds: 47.6929
- Generation seconds: 0.0001
- Estimated prompt tokens: 1340
- Estimated answer tokens: 1197

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there safety warnings about fulminant hepatitis, severe skin reactions, or interstitial pneumonia?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there safety warnings about fulminant hepatitis, severe skin reactions, or interstitial pneumonia?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9561
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6541
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.4825
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.3921
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.3886
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.3785
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 26
```

## 93. Are there severe skin reaction warnings in recent safety notices?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:45:56
- Finished: 2026-03-25T07:50:35
- Elapsed seconds: 279.0054
- Retrieval seconds: 41.7651
- Generation seconds: 0.0001
- Estimated prompt tokens: 310
- Estimated answer tokens: 260

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there severe skin reaction warnings in recent safety notices?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there severe skin reaction warnings in recent safety notices?
Drug filter: chlorhexidine gluconate
Doc type filter: safety_notice
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=7.5643
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres

Sources:
- chlorhexidine gluconate / safety_notice / page 1
```

## 94. Which safety notices mention liver dysfunction or hepatitis?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:46:42
- Finished: 2026-03-25T07:51:16
- Elapsed seconds: 274.4363
- Retrieval seconds: 40.9978
- Generation seconds: 0.0
- Estimated prompt tokens: 308
- Estimated answer tokens: 253

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which safety notices mention liver dysfunction or hepatitis?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Which safety notices mention liver dysfunction or hepatitis?
Drug filter: chlorhexidine gluconate
Doc type filter: safety_notice

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.1347
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres

Sources:
- chlorhexidine gluconate / safety_notice / page 1
```

## 95. Are there warnings related to pregnancy, fetal risk, or oligohydramnios?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:47:31
- Finished: 2026-03-25T07:51:59
- Elapsed seconds: 267.4064
- Retrieval seconds: 42.0471
- Generation seconds: 0.0
- Estimated prompt tokens: 1166
- Estimated answer tokens: 1124

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings related to pregnancy, fetal risk, or oligohydramnios?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings related to pregnancy, fetal risk, or oligohydramnios?
Drug filter: chlorhexidine gluconate
Section hints: warning, pregnancy

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 12 | section=pregnancy | score=6.9063
  (3) Reproductive and developmental toxicity test 17) Fetal test, genetic variability
Chlorhexidine gluconate for 10 days from the 6th to 15th gestation day of pregnant rats.
10, 25, and 50 mg/kg were administered orally. Regarding the mother body, only the maximum amount group
Slight irritation sensitivity and suppression of weight gain were observed, but no abnormalities were observed in the number of implantations, number of absorbed embryos, number of fetuses, sex ratio, abnormal external appearance, or skeletal variation.

(4) Other special toxicities 18) Hemolytic and tissue-damaging The minimum tissue-damaging concentration of chlorhexidine gluconate in chicken fetal heart was 1w/v%.
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=6.8931
  No particular abnormality was observed except for an increase in giant cells in the nodes19). (3) Reproductive and developmental toxicity test Reproductive test

Pregnant rats received 10, 25, and 50 mg/kg/day of chlorhexidine gluconate for 10 days from the 6th to 15th gestation day.

When administered orally, slight hypersensitivity and suppression of weight gain were observed in the mother at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton19). (4) Other special toxicities

1) Tissue damage

The minimum tissue-damaging concentration of chlorhexidine gluconate in chic
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=6.7664
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7092
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6641
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=6.6153
  No particular abnormality was observed except for an increase in the number of giant cells18). (3) No relevant data for genotoxicity test (4) No relevant data for carcinogenicity test (5) Reproductive and developmental toxicity test

Chlorhexidine gluconate 10, 25, or 50 mg/kg/day was orally administered to pregnant rats for 10 days from the 6th to the 15th gestation day.

When administered, slight hypersensitivity and suppression of weight gain were observed in mothers at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton18). (6) No relevant data for local irritation te

Sources:
- chlorhexidine gluconate / interview_form / page 12
- chlorhexidine gluconate / interview_form / page 20
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 20
```

## 96. Are there warnings about HBV reactivation or immunologic risks?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:48:21
- Finished: 2026-03-25T07:52:50
- Elapsed seconds: 269.3812
- Retrieval seconds: 51.6574
- Generation seconds: 0.0001
- Estimated prompt tokens: 1430
- Estimated answer tokens: 1235

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings about HBV reactivation or immunologic risks?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings about HBV reactivation or immunologic risks?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7174
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6738
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2653
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2640
  慎重投与内容とその理由 ·································································································· 17

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 17

7.

相互作用 ······················································································································· 18

8.

副作用 ·························································································································· 18

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2637
  慎重投与内容とその理由 ·································································································· 15

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 15

7.

相互作用 ······················································································································· 16

8.

副作用 ·························································································································· 16

9.

高齢者への投与 ·············································································································· 16

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2632
  慎重投与内容とその理由 ·································································································· 16

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 16

7.

相互作用 ······················································································································· 17

8.

副作用 ·························································································································· 17

9.

高齢者への投与 ·············································································································· 18

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
```

## 97. Are there metabolism-related warnings such as CYP2D6 ultrarapid metabolizer risk?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > D. Safety notice / signal-monitoring questions
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:49:06
- Finished: 2026-03-25T07:54:00
- Elapsed seconds: 293.7013
- Retrieval seconds: 69.5413
- Generation seconds: 0.0
- Estimated prompt tokens: 1335
- Estimated answer tokens: 1192

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there metabolism-related warnings such as CYP2D6 ultrarapid metabolizer risk?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there metabolism-related warnings such as CYP2D6 ultrarapid metabolizer risk?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9599
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.9154
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.4906
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.3994
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.3980
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.3856
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 26
```

## 98. Are there warnings about thyroid dysfunction or systemic iodine absorption?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > E. Povidone-iodine example set
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:49:54
- Finished: 2026-03-25T07:55:14
- Elapsed seconds: 319.927
- Retrieval seconds: 73.9182
- Generation seconds: 0.0
- Estimated prompt tokens: 1433
- Estimated answer tokens: 1238

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings about thyroid dysfunction or systemic iodine absorption?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings about thyroid dysfunction or systemic iodine absorption?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7203
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6773
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2680
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2667
  慎重投与内容とその理由 ·································································································· 17

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 17

7.

相互作用 ······················································································································· 18

8.

副作用 ·························································································································· 18

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2664
  慎重投与内容とその理由 ·································································································· 15

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 15

7.

相互作用 ······················································································································· 16

8.

副作用 ·························································································································· 16

9.

高齢者への投与 ·············································································································· 16

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2660
  慎重投与内容とその理由 ·································································································· 16

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 16

7.

相互作用 ······················································································································· 17

8.

副作用 ·························································································································· 17

9.

高齢者への投与 ·············································································································· 18

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
```

## 99. Are there formulation-related precautions for pregnancy or breastfeeding?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > F. High-value smoke-test sets > F1. Minimal 10-question formulation/safety set
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:50:35
- Finished: 2026-03-25T07:56:50
- Elapsed seconds: 374.0796
- Retrieval seconds: 95.9168
- Generation seconds: 0.0001
- Estimated prompt tokens: 1216
- Estimated answer tokens: 1124

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there formulation-related precautions for pregnancy or breastfeeding?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there formulation-related precautions for pregnancy or breastfeeding?
Drug filter: chlorhexidine gluconate
Section hints: warning, pregnancy

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9613
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 23 | section=pregnancy | score=6.7632
  15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.
- chlorhexidine gluconate | interview_form | page 11 | section=pregnancy | score=6.7444
  14. Application and drug delivery
Precautions Application Precautions (1) Route of Administration: Use only for external use. (2) When in use
1) Be careful not to accidentally get it in your eyes while using this drug. If it gets into your eyes
If this occurs, immediately rinse thoroughly with water.
2) When using over a wide area or for a long period of time, be careful not to inhale vapor.
3) Proteins such as serum and pus may coagulate and may not penetrate inside.
When using medical instruments etc. that have these on them, wash them thoroughly before use.
4) If used repeatedly on the same area (skin surface), it may cause skin roughness due to degreasing, etc.
Please be careful as this
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6619
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 12 | section=pregnancy | score=6.6489
  (3) Reproductive and developmental toxicity test 17) Fetal test, genetic variability
Chlorhexidine gluconate for 10 days from the 6th to 15th gestation day of pregnant rats.
10, 25, and 50 mg/kg were administered orally. Regarding the mother body, only the maximum amount group
Slight irritation sensitivity and suppression of weight gain were observed, but no abnormalities were observed in the number of implantations, number of absorbed embryos, number of fetuses, sex ratio, abnormal external appearance, or skeletal variation.

(4) Other special toxicities 18) Hemolytic and tissue-damaging The minimum tissue-damaging concentration of chlorhexidine gluconate in chicken fetal heart was 1w/v%.
- chlorhexidine gluconate | interview_form | page 20 | section=pregnancy | score=6.6392
  No particular abnormality was observed except for an increase in giant cells in the nodes19). (3) Reproductive and developmental toxicity test Reproductive test

Pregnant rats received 10, 25, and 50 mg/kg/day of chlorhexidine gluconate for 10 days from the 6th to 15th gestation day.

When administered orally, slight hypersensitivity and suppression of weight gain were observed in the mother at the maximum dose, but no abnormalities were observed in the number of implantations, number of respiratory embryos, number of fetuses, sex ratio, external shape, or skeleton19). (4) Other special toxicities

1) Tissue damage

The minimum tissue-damaging concentration of chlorhexidine gluconate in chic

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 12
- chlorhexidine gluconate / interview_form / page 20
```

## 100. Are there warnings related to thyroid disorders or systemic absorption?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > F. High-value smoke-test sets > F1. Minimal 10-question formulation/safety set
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:51:16
- Finished: 2026-03-25T07:58:42
- Elapsed seconds: 445.3946
- Retrieval seconds: 112.309
- Generation seconds: 0.0
- Estimated prompt tokens: 1333
- Estimated answer tokens: 1189

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Are there warnings related to thyroid disorders or systemic absorption?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Are there warnings related to thyroid disorders or systemic absorption?
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7248
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6835
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.5107
  -6-

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applicable materials

15.Irritation
Refer to "VIII. Items related to safety (precautions, etc.)", "2. Contraindications and their reasons (including contraindications in principle)", "6. Important basic precautions, their reasons and treatment methods", "8. Side effects", "14. Precautions for application".

16.Others
Not applicable
- chlorhexidine gluconate | interview_form | page 22 | section=warning | score=6.4145
  16
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2. Contraindications and their reasons (including contraindications in principle)
(Do not use on the following patients or areas) (1) Patients with a history of hypersensitivity to chlorhexidine preparations (2) Brain, spinal cord, ears (inner ear, middle ear, outer ear)
[If used directly on the auditory nerve or central nervous system, hearing loss or nerve damage may occur. ]
(3) Mucosal surfaces such as the vagina, bladder, and oral cavity [Shock and anaphylaxis may occur due to the use of chlorhexidine preparations on the above areas.
Similar symptoms have been reported. ]
(4) Eyes [There
- chlorhexidine gluconate | interview_form | page 11 | section=warning | score=6.4121
  -6-

8.Dissolution
Not applicable

9. Biological test methods
Not applicable

10. Confirmation test method for active ingredients in preparations
(1) Color reaction with methanol, bromine test solution and 8N sodium hydroxide test solution. (2) Precipitation reaction with copper sulfate test solution. (3) Melting point measurement method (chlorhexidine base). (4) Melting point measurement method (gluconic acid).

11. Determination of active ingredients in preparations
Potentiometric titration method

12.Titer
Not applicable

13.Contaminants that may be mixed in
No applicable materials

14. Information regarding containers that require caution and containers with special appearance
No applica
- chlorhexidine gluconate | interview_form | page 26 | section=warning | score=6.3997
  20
VIII. Items related to safety (precautions, etc.)

1. Warning details and reasons
Not applicable

2.Contraindications and their reasons (including contraindications in principle)
(Do not use in the following cases) Persons with a history of hypersensitivity to chlorhexidine preparations* (Explanation)*: Because there is a possibility of hypersensitivity.

3. Precautions and reasons for use related to efficacy or effect
Not applicable

4. Precautions and reasons related to usage and administration
Not applicable

5. Careful administration details and reasons
(Use with caution in the following cases) Persons with drug hypersensitivity

6.Important basic precautions, their reasons and treatm

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 22
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 26
```

## 101. Show evidence from the contraindications section.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > G. Retrieval / routing / section-heading / provenance validation
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:51:59
- Finished: 2026-03-25T08:00:27
- Elapsed seconds: 508.1023
- Retrieval seconds: 104.7501
- Generation seconds: 0.0004
- Estimated prompt tokens: 1212
- Estimated answer tokens: 1136

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show evidence from the contraindications section." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show evidence from the contraindications section.
Drug filter: chlorhexidine gluconate
Section hints: contraindication

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=7.0674
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | interview_form | page 28 | section=contraindication | score=6.7079
  22
13.Overdose
Not applicable

14. Application notes
(1) Administration route: Do not use for any purpose other than hand disinfection. (2) When using: Be careful as there are reports that chemical skin burns may occur if the solution is in contact with the skin for a long period of time.

15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

16.Others
Nothing in particular
- chlorhexidine gluconate | interview_form | page 18 | section=contraindication | score=6.6931
  7. Interaction
(1) Concomitant use contraindications and reasons not applicable (2) Precautions for concomitant use and reasons not applicable
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.6387
  - 13 -
14. Application notes
(1) Administration route Do not use for any purpose other than hand disinfection. (2) During use
1) Be careful not to accidentally get it in your eyes while using this drug. If it comes into contact with your eyes, immediately rinse thoroughly with water.
to do.
2) Be careful as there are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
to do.
3) Be careful of fire as it is flammable and explosive.
15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluco
- Chlorhexidine Gluconate | smpc_label | page 1 | section=contraindication | score=6.6190
  0.5%
エタノール溶液(2分以上)手術室・病室・家具・器具・物品などの消毒
0.05%水溶液
(本剤の100倍希釈) 0.05%水溶液
14.1.2 創傷部位に使用する希釈水溶液は、調製後必ず滅菌処理す
ること。
14.1.3 本剤は、常水や生理食塩液等に含まれる陰イオンにより難
溶性の塩を生成することがあるので、希釈水溶液を調製する際には、新鮮な蒸留水を使用することが望ましい。
14.1.4 手洗い等に使用する本剤の希釈液は、少なくとも毎日新し
い溶液と取換えること。
14.1.5 本剤の希釈水溶液は安定であるが、高温に長時間保つこと
は避けること。高圧蒸気滅菌を行う場合は115°C 30分、121°C 20
分、126°C 15分で滅菌処理することができる。
14.1.6 本剤を取扱う容器類は常に清浄なものを使用すること。
14.1.7 本剤の希釈水溶液は調製後直ちに使用すること。やむを得
ず消毒用綿球等に長時間使用する希釈水溶液は微生物汚染を防止するために、希釈水溶液にアルコールを添加することが望ましい。エタノールの場合7vol%以上、イソプロパノールの場合4vol%以上になるように添加する。
14.1.8 器具類の保存に使用する場合は、腐食を防止するために、
高濃度希釈液(目安として本液0.3%以上)を使用し、微生物汚染を防止するために、希釈水溶液にアルコールを添加することが望
ましい。(アルコール添加量は上記14.1.7と同じ)本液は毎週新
しい溶液と取換えること。
14.1.9 綿球・ガーゼ等は本剤を吸着するので、これらを希釈液に
浸漬して用いる場合には、有効濃度
- chlorhexidine gluconate | interview_form | page 20 | section=contraindication | score=6.6087
  15

14. Application notes
(1) Administration Route Do not use for any purpose other than disinfecting hands and skin. (2) During use
1) Please note that repeated use may cause skin irritation due to degreasing.
2) Organic substances such as serum and pus reduce the bactericidal action, so if these are present,
Wash thoroughly before use.
3) Since soap weakens the bactericidal effect of this agent, be sure to thoroughly wash off the soap used for preliminary cleaning.
before use.
4) Be careful of fire as it is flammable and explosive.
5) There are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
So be careful.
15.Other notes
I

Sources:
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / interview_form / page 28
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 19
- Chlorhexidine Gluconate / smpc_label / page 1
- chlorhexidine gluconate / interview_form / page 20
```

## 102. Show evidence from the warnings section.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > G. Retrieval / routing / section-heading / provenance validation
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:52:50
- Finished: 2026-03-25T08:02:02
- Elapsed seconds: 551.3426
- Retrieval seconds: 94.9028
- Generation seconds: 0.0001
- Estimated prompt tokens: 1424
- Estimated answer tokens: 1230

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show evidence from the warnings section." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show evidence from the warnings section.
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.9861
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6967
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 18 | section=warning | score=6.3439
  - 12 -
(2) Serious side effects and initial symptoms Serious side effects: Shock (less than 0.1%), anaphylaxis (incidence unknown) Shock, anaphylaxis may occur, so carefully monitor the product, and if any symptoms such as decreased blood pressure, hives, or difficulty breathing occur, immediately discontinue use and take appropriate measures.

(3)Other side effects

Frequency unknown
Less than 0.1%
Hypersensitivity *1)

Skin irritation symptoms such as rash and hives *2)

*1) If any of these symptoms occur, immediately stop using the product and do not reuse it. *2) If any of these symptoms occur, discontinue use. (4) List of frequency of side effects by item and abnormal clinical test valu
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2837
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2824
  慎重投与内容とその理由 ·································································································· 17

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 17

7.

相互作用 ······················································································································· 18

8.

副作用 ·························································································································· 18

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2821
  慎重投与内容とその理由 ·································································································· 15

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 15

7.

相互作用 ······················································································································· 16

8.

副作用 ·························································································································· 16

9.

高齢者への投与 ·············································································································· 16

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
```

## 103. Give the answer with citations and show the exact page references.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > G. Retrieval / routing / section-heading / provenance validation
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:54:00
- Finished: 2026-03-25T08:03:29
- Elapsed seconds: 568.8091
- Retrieval seconds: 87.0089
- Generation seconds: 0.0
- Estimated prompt tokens: 1564
- Estimated answer tokens: 1296

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Give the answer with citations and show the exact page references." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Give the answer with citations and show the exact page references.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.8970
  Revised November 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

External disinfectant Chlorhexidine Gluconate Disinfectant Solution Chlorhexidine Gluconate Disinfectant Solution 5% "Nichi-Iko" Chlorhexidine Gluconate Disinfectant Solution

Standards and contents without regulatory classification for external liquid preparations
Chlorhexidine gluconate solution 25mL in 100mL
(5w/v% as chlorhexidine gluconate) Contains Generic name Japanese name: Chlorhexidine gluconate liquid European name: Chlorhexidine Gluconate Solut
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8901
  Revised January 2024 (5th edition)
Japan standard product classification number: 872619

Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Hand disinfectant chlorhexidine gluconate preparation Chlorhexidine gluconate scrub 4% "Nichi-Iko" Chlorhexidine Gluconate Scrub

Standards and contents without regulatory classification for liquid dosage forms
Contains 20mL of chlorhexidine gluconate solution in 100mL (chlorhexidine
4.0w/v% as ruconate) Generic name Japanese name: Chlorhexidine gluconate liquid Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8671
  Created in December 2016 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form

Created in accordance with the Japanese Association of Hospital Pharmacists' IF writing guidelines (September 1998)

Bactericidal disinfectant for outer skin

Japanese Pharmacy Chlorhexidine Gluconate Solution Chlorhexidine Gluconate Solution 20% "Yakuhan"

Dosage form liquid drug specifications/content
Contains 19.0~21.0 w/v% of chlorhexidine gluconate.
Generic name: Japanese name: Chlorhexidine Gluconate Western name: Chlorhexidine Gluconate Date of manufacturing approval Date of drug price list listing Date of release
February 24, 2005
February 24, 2005
July 8, 201
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8591
  Created in September 2024 (1st edition)
Japanese standard product classification number
872619

Pharmaceutical interview form
Created in accordance with the Japan Society of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Disinfectant (chlorhexidine gluconate preparation) Chlorhexidine Gluconate Disinfectant Solution 5% “SIOE”

Dosage form

External liquid

Specifications and contents that do not apply to the regulatory category of the preparation
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 25mL in 100mL
(Contains 5g (5w/v%) as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine Gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of
- chlorhexidine gluconate | interview_form | page 1 | section=dosage | score=5.8288
  Revised December 2023 (7th edition)
Japan standard product classification number 872619
Pharmaceutical interview form
Created in accordance with the Japan Association of Hospital Pharmacists' IF writing guidelines 2018 (updated in 2019)

Dosage form Regulatory classification of liquid preparations for external use Not applicable specifications/content Contains 25 vol% of chlorhexidine gluconate solution (contains 5 w/v% as chlorhexidine gluconate) Generic name Japanese name: Chlorhexidine gluconate solution Western name: Chlorhexidine Gluconate Solution Date of manufacturing and sales approval Date of drug price listing/start of sales
Date of manufacturing and marketing approval: February 26
- chlorhexidine gluconate | interview_form | page 1 | section=general | score=5.8228
  Revised October 2017 (3rd edition)
Japan standard product classification number 872619

Pharmaceutical interview form
Created in accordance with the IF writing guidelines 2013 of the Japan Society of Hospital Pharmacists

Specifications and contents that do not apply to regulatory categories for external liquid preparations
1,000mL medium
Japanese Pharmacopoeia Chlorhexidine Gluconate Solution 250mL
(50g as chlorhexidine gluconate) Generic name: Japanese name: Chlorhexidine gluconate (JAN) Western name: Chlorhexidine Gluconate (JAN) Date of manufacturing and sales approval Date of drug price listing/release date
Date of manufacturing and marketing approval: February 15, 2013
NHI drug price l

Sources:
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
- chlorhexidine gluconate / interview_form / page 1
```

## 104. Show the supporting evidence and source page files for the PK answer.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > G. Retrieval / routing / section-heading / provenance validation
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:55:14
- Finished: 2026-03-25T08:04:57
- Elapsed seconds: 583.3488
- Retrieval seconds: 88.4583
- Generation seconds: 0.0001
- Estimated prompt tokens: 1501
- Estimated answer tokens: 1296

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Show the supporting evidence and source page files for the PK answer." --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Show the supporting evidence and source page files for the PK answer.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 21 | section=pk | score=7.4698
  - 16 -

6. Excretion
1) Excretion site and route

2) Excretion rate

3) Excretion rate

7. Regarding transporters
Information to do

8. Removal rate by dialysis etc.

<Reference>7)
After oral administration of 14C-labeled chlorhexidine gluconate, it was detected in feces and urine.
The total amount detected over the 7 days is shown in the table below. There was little absorption from the gastrointestinal tract and it was excreted in the feces.

Animal species Dose (mg/kg) Urine (%) Feces (%) Rat
5
0.4
99.5
mouse
8
3.7
101.6
dog
5
0.8
102.0

Almost 100% in feces (listed in the table above).

No applicable materials.

No applicable materials.

Not applicable.
- chlorhexidine gluconate | interview_form | page 9 | section=pk | score=7.4074
  <W> Glucodin W ・Ethanol solution 0.5%

<B> Glucodin B ・Ethanol solution 0.5%

<R> Glucodin R ・Ethanol solution 0.5%
VI. Items related to drug efficacy and pharmacology
1. Pharmacologically relevant
compound or group of compounds

2. Pharmacological effects

(1) Site of action/Mechanism of action (1) Chlorhexidine gluconate solution acts on a wide range of microorganisms, and exhibits rapid bactericidal action against Gram-positive bacteria even at low concentrations2,3). Although it is effective against Gram-negative bacteria at relatively low concentrations, there is a wider range of susceptibility compared to Gram-positive bacteria4). (2) Although many fungi are susceptible, they are gener
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.2624
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.2328
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.2284
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.2091
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl

Sources:
- chlorhexidine gluconate / interview_form / page 21
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 16
```

## 105. Which pages were used to answer the question on stability?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > G. Retrieval / routing / section-heading / provenance validation
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:56:50
- Finished: 2026-03-25T08:06:41
- Elapsed seconds: 591.6656
- Retrieval seconds: 104.2349
- Generation seconds: 0.0001
- Estimated prompt tokens: 1471
- Estimated answer tokens: 1282

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Which pages were used to answer the question on stability?" --drug-name "chlorhexidine gluconate" --json
```

### Result

```text
Question: Which pages were used to answer the question on stability?
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: stability

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.6259
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par
- chlorhexidine gluconate | interview_form | page 9 | section=stability | score=7.6168
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
1 mL of chlorhexidine gluconate solution is miscible with up to 5 mL of ethanol (99.5) or up to 3 mL of acetone.
However, when the amount of solvent is increased, it becomes cloudy. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data fo
- chlorhexidine gluconate | interview_form | page 23 | section=stability | score=7.6115
  -18-

X. Items related to administrative matters
1.Regulatory classification
Preparation: Chlorhexidine gluconate disinfectant solution 5% “NP” Not applicable
Active ingredient: Japanese Pharmacopoeia Chlorhexidine gluconate solution Not applicable

2. Validity period or expiration date
Expiration date: 3 years after manufacture (based on stability test results) (See section 5. Stability of formulations under various conditions in ``IV. Items related to formulations.'')

3.Storage method/storage conditions
Seal tightly and store at room temperature, protected from light.
- chlorhexidine gluconate | interview_form | page 4 | section=stability | score=7.5824
  -Table of Contents-

I. Items related to overview
1.
Development history · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 1
2.
Therapeutic and pharmaceutical properties of the product 1

II. Items related to name
1.
Sales name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · 2
2.
common name · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · · ·
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=7.5712
  3

III. Items related to active ingredients

1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste.

(2)Solubility
Miscible with water or acetic acid (100). 1mL of this product is 5mL or less of ethanol (99.5) or 3mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased.

(3) Hygroscopicity No applicable data available

(4) Melting point (decomposition point), boiling point, freezing point No relevant data available

(5) Acid-base dissociation constant
pKa=10.3, 2.2

(6) No relevant data for distribution coefficient

(7)Other main indication value
- chlorhexidine gluconate | interview_form | page 6 | section=stability | score=7.5687
  (3) Physical properties of the formulation
pH:5.5~7.0(1→20)
Specific gravity d:1.06~1.07

(4) Identification code

(5) Is it sterile?

(6) Acid value, iodine value, etc.

2. Composition of the formulation

(1) Content of active ingredients
When quantifying this product, use chlorhexidine gluconate (C22H30Cl2N10・
Contains 2C6H12O7)19.0~21.0w/v%.

(2) Additives

(3) Composition and volume of attached solution

3. Dissolve before use.
Preparation method of formulation

4. Dispersibility of suspensions and emulsions
caution against

5. Under various conditions of formulation
Stability When stored at room temperature for 3 years, 4-chloroaniline was gradually produced, and an associated increase

Sources:
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 23
- chlorhexidine gluconate / interview_form / page 4
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 6
```

## 106. What are the key warnings and contraindications for chlorhexidine gluconate?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H1. Query-form regression
- Generator: none
- Success: Yes
- Started: 2026-03-25T07:58:42
- Finished: 2026-03-25T08:08:29
- Elapsed seconds: 587.0942
- Retrieval seconds: 107.734
- Generation seconds: 0.0001
- Estimated prompt tokens: 1269
- Estimated answer tokens: 1212

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the key warnings and contraindications for chlorhexidine gluconate?" --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: What are the key warnings and contraindications for chlorhexidine gluconate?
Drug filter: chlorhexidine gluconate
Section hints: contraindication, warning

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 2 | section=contraindication | score=7.0929
  The IF Description Guidelines 2008 change the method of providing IFs from paper booklets to electronic data such as PDF.

(e-IF) became the principle. In line with this change, if there is a revision to the package insert such as ``addition of indications'' or ``revised warnings, contraindications, and important basic precautions'', the latest version of Stericlone® R liquid with added rationale for the revision.

0.05

The latest version of e-IF is available on the Pharmaceuticals and Medical Devices Agency's drug information website.
(http://www.info.pmda.go.jp/):
1-medium

Chlorhexidine gluconate
Contains 0.05g (0.05w/v %)

:
1

Medium

Contains 0.1g of chlorhexidine gluconate (
0.1w/v
%
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=7.0207
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.9885
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 28 | section=contraindication | score=6.9779
  22
13.Overdose
Not applicable

14. Application notes
(1) Administration route: Do not use for any purpose other than hand disinfection. (2) When using: Be careful as there are reports that chemical skin burns may occur if the solution is in contact with the skin for a long period of time.

15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluconate preparations.

16.Others
Nothing in particular
- chlorhexidine gluconate | interview_form | page 19 | section=contraindication | score=6.9051
  - 13 -
14. Application notes
(1) Administration route Do not use for any purpose other than hand disinfection. (2) During use
1) Be careful not to accidentally get it in your eyes while using this drug. If it comes into contact with your eyes, immediately rinse thoroughly with water.
to do.
2) Be careful as there are reports that chemical skin burns may occur when the solution is in contact with the skin for a long period of time.
to do.
3) Be careful of fire as it is flammable and explosive.
15.Other notes
It has been reported that IgE antibodies specific to chlorhexidine were detected in the serum of several patients who developed shock symptoms due to administration of chlorhexidine gluco
- Chlorhexidine Gluconate | smpc_label | page 1 | section=contraindication | score=6.8788
  0.5%
エタノール溶液(2分以上)手術室・病室・家具・器具・物品などの消毒
0.05%水溶液
(本剤の100倍希釈) 0.05%水溶液
14.1.2 創傷部位に使用する希釈水溶液は、調製後必ず滅菌処理す
ること。
14.1.3 本剤は、常水や生理食塩液等に含まれる陰イオンにより難
溶性の塩を生成することがあるので、希釈水溶液を調製する際には、新鮮な蒸留水を使用することが望ましい。
14.1.4 手洗い等に使用する本剤の希釈液は、少なくとも毎日新し
い溶液と取換えること。
14.1.5 本剤の希釈水溶液は安定であるが、高温に長時間保つこと
は避けること。高圧蒸気滅菌を行う場合は115°C 30分、121°C 20
分、126°C 15分で滅菌処理することができる。
14.1.6 本剤を取扱う容器類は常に清浄なものを使用すること。
14.1.7 本剤の希釈水溶液は調製後直ちに使用すること。やむを得
ず消毒用綿球等に長時間使用する希釈水溶液は微生物汚染を防止するために、希釈水溶液にアルコールを添加することが望ましい。エタノールの場合7vol%以上、イソプロパノールの場合4vol%以上になるように添加する。
14.1.8 器具類の保存に使用する場合は、腐食を防止するために、
高濃度希釈液(目安として本液0.3%以上)を使用し、微生物汚染を防止するために、希釈水溶液にアルコールを添加することが望
ましい。(アルコール添加量は上記14.1.7と同じ)本液は毎週新
しい溶液と取換えること。
14.1.9 綿球・ガーゼ等は本剤を吸着するので、これらを希釈液に
浸漬して用いる場合には、有効濃度

Sources:
- chlorhexidine gluconate / interview_form / page 2
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 28
- chlorhexidine gluconate / interview_form / page 19
- Chlorhexidine Gluconate / smpc_label / page 1
```

## 107. Please summarize the detailed pharmacokinetic profile including absorption, metabolism, and elimination.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H1. Query-form regression
- Generator: none
- Success: Yes
- Started: 2026-03-25T08:00:27
- Finished: 2026-03-25T08:10:13
- Elapsed seconds: 586.457
- Retrieval seconds: 104.1156
- Generation seconds: 0.0001
- Estimated prompt tokens: 1510
- Estimated answer tokens: 1306

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Please summarize the detailed pharmacokinetic profile including absorption, metabolism, and elimination." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Please summarize the detailed pharmacokinetic profile including absorption, metabolism, and elimination.
Drug filter: chlorhexidine gluconate
Doc type filter: interview_form
Section hints: pk

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 19 | section=pk | score=7.5060
  - 14 -

4) Disappearance rate constant

5) Clearance

6) Distribution volume

7) Plasma protein binding rate

3.Absorption

4. Distribution
1) Blood-brain barrier passage
hypersexuality

2) Transferability to the fetus

3)乳汁中への移行
sex

4) Migration into cerebrospinal fluid

Not applicable.

Not applicable.

Not applicable.

Not applicable.

Not applicable. Reference: (Overseas results) 6) Absorption of chlorhexidine gluconate was investigated using labeled 5% or 4% chlorhexidine gluconate solution. A 14C-labeled chlorhexidine gluconate solution was applied to the forearms of five healthy subjects.
After leaving it for 3 hours, the concentrations in blood and feces were measured. 6 hours after
- chlorhexidine gluconate | interview_form | page 18 | section=pk | score=7.4777
  - 13 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4
- chlorhexidine gluconate | interview_form | page 15 | section=pk | score=7.4714
  - 9 -
3. Absorption
Not applicable (Reference 1: Human [absorption/excretion 15)])
5% or 4% labeled chlorhexidine gluconate (18 μCi) was applied to 50 cm2 of the upper arm skin of 5 healthy men.
(containing 14C) was applied and left for 3 hours. 14C labeled substance was detected in blood 6 and 24 hours after application.
It wasn't done. When measuring the total amount of 14C-labeled substances in feces and urine 10 days after application, no 14C-labeled substances were detected in the urine, and 2 people
Less than 0.009% of the applied amount of 14C labeled substance was detected in the feces of patients. (Results in UK)
Fifteen healthy people disinfected their hands and arms with 10 mL of
- chlorhexidine gluconate | interview_form | page 21 | section=pk | score=7.4622
  - 16 -

6. Excretion
1) Excretion site and route

2) Excretion rate

3) Excretion rate

7. Regarding transporters
Information to do

8. Removal rate by dialysis etc.

<Reference>7)
After oral administration of 14C-labeled chlorhexidine gluconate, it was detected in feces and urine.
The total amount detected over the 7 days is shown in the table below. There was little absorption from the gastrointestinal tract and it was excreted in the feces.

Animal species Dose (mg/kg) Urine (%) Feces (%) Rat
5
0.4
99.5
mouse
8
3.7
101.6
dog
5
0.8
102.0

Almost 100% in feces (listed in the table above).

No applicable materials.

No applicable materials.

Not applicable.
- chlorhexidine gluconate | interview_form | page 16 | section=pk | score=7.4546
  11
VII. Items related to pharmacokinetics

1.Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply. (2) Blood concentration confirmed in clinical trials does not apply. (3) Toxic range does not apply. (4) Effects of food and concomitant drugs do not apply.
2. Pharmacokinetic parameters
(1) Analysis method No applicable data (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other not applicable
3. Population analysis
(1) Analysis method not applicable (2) Parameter variation factor not applicable
4. Absorption
16.2.1 5% or 4% labeled chl
- chlorhexidine gluconate | interview_form | page 14 | section=pk | score=7.4482
  - 9 -
VII. Items related to pharmacokinetics
1. Changes in blood concentration
(1) Therapeutically effective blood concentration does not apply (2) Blood concentration confirmed in clinical trials does not apply (3) No data applicable to toxic range (4) No data applicable to effects of food and concomitant drugs
2. Pharmacokinetic parameters
(1) Analysis method not applicable (2) Absorption rate constant not applicable (3) Disappearance rate constant not applicable (4) Clearance not applicable (5) Volume of distribution not applicable (6) Other applicable data not available
3. Population analysis
(1) No relevant data for analysis method (2) No relevant data for parameter variation factors
4.

Sources:
- chlorhexidine gluconate / interview_form / page 19
- chlorhexidine gluconate / interview_form / page 18
- chlorhexidine gluconate / interview_form / page 15
- chlorhexidine gluconate / interview_form / page 21
- chlorhexidine gluconate / interview_form / page 16
- chlorhexidine gluconate / interview_form / page 14
```

## 108. What are the active ingredient and excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H2. Retrieval-parameter regression
- Generator: none
- Success: Yes
- Started: 2026-03-25T08:02:02
- Finished: 2026-03-25T08:11:14
- Elapsed seconds: 552.4524
- Retrieval seconds: 60.9013
- Generation seconds: 0.0
- Estimated prompt tokens: 621
- Estimated answer tokens: 516

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the active ingredient and excipients?" --drug-name "chlorhexidine gluconate" --top-k 3
```

### Result

```text
Question: What are the active ingredient and excipients?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9599
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 11 | section=general | score=5.9554
  5
4. Quantification method of active ingredients
Based on the Japanese drug ``chlorhexidine gluconate solution.''
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9331
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 7
```

## 109. What are the active ingredient and excipients?

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H2. Retrieval-parameter regression
- Generator: none
- Success: Yes
- Started: 2026-03-25T08:03:29
- Finished: 2026-03-25T08:12:17
- Elapsed seconds: 528.2991
- Retrieval seconds: 62.8515
- Generation seconds: 0.0
- Estimated prompt tokens: 1708
- Estimated answer tokens: 1044

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "What are the active ingredient and excipients?" --drug-name "chlorhexidine gluconate" --top-k 8
```

### Result

```text
Question: What are the active ingredient and excipients?
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 7 | section=dosage | score=5.9599
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine gluconate disinfectant solution 5% "NP"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION FOR DISINFECTION
(3) Origin of name: The dosage form and content of the active ingredient, chlorhexidine gluconate, are listed, and "NP" is added from NIPRO.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula

4.Molecular formula and molecular weight
Molecular formula: C22H30Cl2N10・2C6H12O7
Molecular weight: 897.76

5.Chemical name (nomenclature)
1,1'-Hexamethylenebis[5-(
- chlorhexidine gluconate | interview_form | page 11 | section=general | score=5.9554
  5
4. Quantification method of active ingredients
Based on the Japanese drug ``chlorhexidine gluconate solution.''
- chlorhexidine gluconate | interview_form | page 7 | section=general | score=5.9331
  -2-

II. Items related to name
1.Selling name
(1) Japanese name: 1% chlorhexidine gluconate aqueous solution disinfectant cloth 4 x 4 "Nipro"
(2)Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH
(3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution containing 1w/v% chlorhexidine gluconate, the active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.

2.Common name
(1) Japanese name (nomenclature): Chlorhexidine gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine gluconate (JAN)
(3) Stem: unknown

3. Structural formula or demonstrative formula
Structural formula:

4.Molecular formula and molecular weight
Molecu
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.9124
  - 4 -
3. Confirmation test for active ingredients
law
4. Quantification method of active ingredients
According to the Japanese Bureau of Medicine's "Chlorhexidine Gluconate Solution Confirmation Test." Based on the ``Chlorhexidine gluconate liquid quantitative method'' of the Japanese Bureau.
- chlorhexidine gluconate | interview_form | page 8 | section=general | score=5.8846
  II. Items related to name
1.Selling name
(1) Japanese name: Chlorhexidine GLUCONATE SOLUTION DISINFECTION CLOTH 4 x 4 disinfectant cloth (2) Western name: CHLORHEXIDINE GLUCONATE SOLUTION DISINFECTION CLOTH (3) Origin of the name: This agent is a disinfectant cloth impregnated with a chemical solution (ethanol solution) containing 1w/v% chlorhexidine gluconate as an active ingredient. 4×4 indicates the size (cm) of the nonwoven fabric.
2.Common name
(1) Japanese name (nomenclature): Chlorhexidine Gluconate (JAN) (2) Western name (nomenclature): Chlorhexidine Gluconate (JAN) (3) Stem: unknown
3. Structural formula or demonstrative formula
4.Molecular formula and molecular weight
Molecular for
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.8823
  - 3 -
III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Properties Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and a bitter taste. (2) Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100).
Also, 1 mL of chlorhexidine gluconate solution is 5 mL or less of ethanol (99.5) or 3 mL or less of acetone.
However, it becomes cloudy when the amount of solvent is increased. (3) No relevant data for hygroscopicity (4) No relevant data for melting point (decomposition point), boiling point, freezing point (5) No relevant data for acid-base dissociation constant (6) No relevant data for par

Sources:
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 11
- chlorhexidine gluconate / interview_form / page 7
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 8
- chlorhexidine gluconate / interview_form / page 8
```

## 110. Summarize all major risks.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H3. Stress / comparison tests
- Generator: none
- Success: Yes
- Started: 2026-03-25T08:04:57
- Finished: 2026-03-25T08:13:16
- Elapsed seconds: 499.0646
- Retrieval seconds: 59.2289
- Generation seconds: 0.0
- Estimated prompt tokens: 912
- Estimated answer tokens: 844

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize all major risks." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Summarize all major risks.
Drug filter: chlorhexidine gluconate

Top retrieved evidence:
- chlorhexidine gluconate | interview_form | page 32 | section=general | score=5.8960
  26
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 31 | section=general | score=5.8960
  25
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% Chlorhexidine Gluconate HIBICLENS® (USA): 4w/v% Chlorhexidine Gluconate HIBISTAT® (USA): 0.5w/w% Chlorhexidine Gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 34 | section=general | score=5.8960
  28
XII.Reference materials

1. Release status in major foreign countries
PERIDEX® (USA): 0.12% chlorhexidine gluconate HIBICLENS® (USA): 4w/v% chlorhexidine gluconate HIBISTAT® (USA): 0.5w/w% chlorhexidine gluconate

2.Clinical support information overseas
No applicable materials
- chlorhexidine gluconate | interview_form | page 5 | section=stability | score=5.7413
  6. Common names, aliases, abbreviations,
symbol number

7. CAS Registration Number
55-56-1(Chlorhexidine)
18472-51-0(Chlorhexidine Gluconate)

III. Items related to active ingredients
1. Regulatory classification of active ingredients
common medicine

2. Physicochemical properties

(1) Appearance/Properties Chlorhexidine gluconate usually exists as an aqueous solution, and its 20w/v% solution is a colorless to slightly yellow clear liquid with no odor and a bitter taste.

(2) Solubility
Miscible with water or acetic acid (100). 1mL of 20w/v% solution is 5mL of ethanol (99.5)
It is miscible with less than 3 mL of acetone, but becomes cloudy when increasing the amount of solvent.

(3) Hygrosco
- chlorhexidine gluconate | interview_form | page 9 | section=general | score=5.7396
  3
6.Usual names, aliases, abbreviations, symbol numbers
Other name: Chlorhexidine gluconate

7.CAS registration number
18472-51-0(Chlorhexidine Gluconate)
55-56-1(Chlorhexidine)
- chlorhexidine gluconate | interview_form | page 8 | section=stability | score=5.7314
  -3-

III. Items related to active ingredients
1.Physicochemical properties
(1) Appearance/Characteristics: Colorless to slightly yellow, clear liquid with no odor and bitter taste. (2) Solubility Miscible with water or acetic acid (100).
1 mL is miscible with less than 5 mL of ethanol (99.5) or less than 3 mL of acetone, but the solvent
becomes cloudy when increasing the amount of (3) No relevant data on hygroscopicity (4) No relevant data on melting point (decomposition point), boiling point, freezing point (5) No relevant data on acid-base dissociation constant (6) No relevant data on partition coefficient (7) Other major values
pH: The pH of a solution of 5.0mL of this product dissolved i

Sources:
- chlorhexidine gluconate / interview_form / page 32
- chlorhexidine gluconate / interview_form / page 31
- chlorhexidine gluconate / interview_form / page 34
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 9
- chlorhexidine gluconate / interview_form / page 8
```

## 111. Compare the warnings for alprazolam and abaloparatide.

- Phase: non_ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H3. Stress / comparison tests
- Generator: none
- Success: Yes
- Started: 2026-03-25T08:06:41
- Finished: 2026-03-25T08:14:10
- Elapsed seconds: 448.686
- Retrieval seconds: 53.8518
- Generation seconds: 0.0
- Estimated prompt tokens: 1428
- Estimated answer tokens: 1233

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Compare the warnings for alprazolam and abaloparatide." --drug-name "chlorhexidine gluconate"
```

### Result

```text
Question: Compare the warnings for alprazolam and abaloparatide.
Drug filter: chlorhexidine gluconate
Section hints: warning

Top retrieved evidence:
- chlorhexidine gluconate | safety_notice | page 1 | section=warning | score=6.7307
  Attachment 3
261 Germicidal disinfectant

[Drug name] Chlorhexidine gluconate

[Measures] The precautions for use will be revised as follows.

Please refer to the description regarding shock in the [Important Basic Precautions] section.

"In order to predict reactions such as shock and anaphylaxis, be sure to thoroughly inquire about your history of hypersensitivity to chlorhexidine preparations and whether you have a predisposition to drug sensitivity before use."

The description regarding shock in the "Significant side effects" section of [Adverse reactions] has been changed to

“Shock, anaphylaxis:
Shock and anaphylaxis may occur, so carefully monitor the product. If decreased blood pres
- chlorhexidine gluconate | interview_form | page 24 | section=warning | score=6.6896
  (Explanation) *1 Chlorhexidine at a concentration of 0.5% or higher is highly toxic to the eyes, and if high concentrations of chlorhexidine enter the eye, serious corneal damage will occur15). *2 When diluted with purified water or tap water, chlorhexidine gluconate, which has mild potency, may be contaminated with bacteria such as Pseudomonas spp. and Serratia marcescens. Therefore, it should be sterilized after preparation16).
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2777
  慎重投与内容とその理由 ·································································································· 18

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 18

7.

相互作用 ······················································································································· 19

8.

副作用 ·························································································································· 19

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2764
  慎重投与内容とその理由 ·································································································· 17

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 17

7.

相互作用 ······················································································································· 18

8.

副作用 ·························································································································· 18

9.

高齢者への投与 ·············································································································· 19

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2761
  慎重投与内容とその理由 ·································································································· 15

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 15

7.

相互作用 ······················································································································· 16

8.

副作用 ·························································································································· 16

9.

高齢者への投与 ·············································································································· 16

10.

妊婦,産婦,授乳婦等への投与 ···································································
- chlorhexidine gluconate | interview_form | page 5 | section=warning | score=6.2756
  慎重投与内容とその理由 ·································································································· 16

6.

重要な基本的注意とその理由及び処置方法 ·········································································· 16

7.

相互作用 ······················································································································· 17

8.

副作用 ·························································································································· 17

9.

高齢者への投与 ·············································································································· 18

10.

妊婦,産婦,授乳婦等への投与 ···································································

Sources:
- chlorhexidine gluconate / safety_notice / page 1
- chlorhexidine gluconate / interview_form / page 24
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
- chlorhexidine gluconate / interview_form / page 5
```

## 112. Summarize composition, excipients, stability, and formulation-related safety risks.

- Phase: ollama
- Section: PMDA RAG Reusable Question Bank > H. Robustness / regression / stress tests > H2. Retrieval-parameter regression
- Generator: ollama
- Success: Yes
- Started: 2026-03-25T08:14:12
- Finished: 2026-03-25T08:17:19
- Elapsed seconds: 186.5934
- Retrieval seconds: 59.3541
- Generation seconds: 127.2377
- Estimated prompt tokens: 529
- Estimated answer tokens: 306

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize composition, excipients, stability, and formulation-related safety risks." --drug-name "chlorhexidine gluconate" --top-k 3 --generator ollama --model "llama3.2:3b" --ollama-timeout 600 --context-chars-per-hit 500
```

### Result

```text
Here is a concise summary of composition, excipients, stability, and formulation-related safety risks for chlorhexidine gluconate:

Composition/Excipients:
* Active ingredient: Chlorhexidine gluconate
* Solvents: Ethanol (99.5) or Acetone
* Other: Water or Acetic acid

Stability:
* Solution is colorless to slightly yellow, clear liquid with no odor and bitter taste
* Miscible with water or acetic acid (100), ethanol (99.5) up to 5 mL, or acetone up to 3 mL
* Becomes cloudy when solvent amount is increased

Formulation-related Safety Risks:
* None explicitly stated

Please note that the evidence provided does not cover formulation-related safety risks in detail.

Key Evidence:

* Chlorhexidine gluconate solution is a colorless to slightly yellow, clear liquid with no odor and bitter taste. (Drug / Interview_form / Page 8)
* Soluble chlorhexidine gluconate solution is miscible with water or acetic acid (100), ethanol (99.5) up to 5 mL, or acetone up to 3 mL. (Drug / Interview_form / Page 9)
* When the amount of solvent is increased, it becomes cloudy. (Drug / Interview_form / Page 8 and 9)

Source Citations:
Chlorhexidine gluconate / Interview_form / Page 8
Chlorhexidine gluconate / Interview_form / Page 9
```

## 113. Summarize the pharmacokinetics of this drug.

- Phase: ollama
- Section: PMDA RAG Reusable Question Bank > I. Optional Ollama variants
- Generator: ollama
- Success: Yes
- Started: 2026-03-25T08:17:21
- Finished: 2026-03-25T08:20:13
- Elapsed seconds: 171.6165
- Retrieval seconds: 75.2722
- Generation seconds: 96.3425
- Estimated prompt tokens: 514
- Estimated answer tokens: 256

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the pharmacokinetics of this drug." --drug-name "chlorhexidine gluconate" --top-k 3 --generator ollama --model "llama3.2:3b" --ollama-timeout 600 --context-chars-per-hit 500
```

### Result

```text
Here is a summary of the pharmacokinetics of chlorhexidine gluconate:

Concise answer: The pharmacokinetic parameters of chlorhexidine gluconate are limited by the available data. The absorption rate constant, disappearance rate constant, and clearance could not be determined due to lack of applicable data.

Key evidence bullets:
• Absorption of 14C-labeled chlorhexidine gluconate was detected in blood 6 and 24 hours after application (Reference 1: Human / interview_form / page=15)
• No 14C-labeled substances were detected in urine 10 days after application (Reference 1: Human / interview_form / page=15)
• Analysis method is not applicable for pharmacokinetic parameters (Reference 2: drug / interview_form / page=18)
• Absorption rate constant, disappearance rate constant, and clearance could not be determined due to lack of applicable data (Reference 3: drug / interview_form / page=18)

Source citations:
1. Human / interview_form / page=15
2. drug / interview_form / page=18
3. drug / interview_form / page=18
```

## 114. Summarize the full RMP including risks, monitoring, and risk minimization actions.

- Phase: ollama
- Section: PMDA RAG Reusable Question Bank > I. Optional Ollama variants
- Generator: ollama
- Success: Yes
- Started: 2026-03-25T08:20:15
- Finished: 2026-03-25T08:22:35
- Elapsed seconds: 140.1695
- Retrieval seconds: 62.5396
- Generation seconds: 77.629
- Estimated prompt tokens: 407
- Estimated answer tokens: 252

### Command

```bash
python fs_rag_chatbot.py "E:\\PharmAppDev\\database\\PMDA\\pmda_fs_index" "Summarize the full RMP including risks, monitoring, and risk minimization actions." --drug-name "chlorhexidine gluconate" --top-k 3 --generator ollama --model "llama3.2:3b" --ollama-timeout 600 --context-chars-per-hit 500
```

### Result

```text
Unfortunately, I cannot provide a full summary of the RMP including risks, monitoring, and risk minimization actions as the provided evidence is incomplete.

However, based on the available information, here is what can be extracted:

* Chlorhexidine gluconate is a hand disinfectant containing chlorhexidine gluconate solution as an active ingredient.
* The drug was developed by Oriental Pharmaceutical Co., Ltd. and received approval on April 30, 2008.
* There are no approval conditions or restrictions on distribution and use.

The RMP overview section is not applicable (source: [Rank 2] drug=chlorhexidine gluconate; doc_type=interview_form; page=7; section=rmp).

There are also no specific guidelines for promoting optimal use, insurance application considerations, or notifications (source: [Rank 1] drug=chlorhexidine gluconate; doc_type=interview_form; page=7; section=rmp).

Unfortunately, the provided evidence does not include information on risks, monitoring, and risk minimization actions.
```
