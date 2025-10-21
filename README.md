# Early Chinese Hundred Schools of Thoughts Database  

A collection of structured datasets and visualizations to support research in **early Chinese history, philosophy, and society**. This project integrates machine-extracted texts, biographical data, and spatial-temporal mapping tools to facilitate both quantitative and qualitative approaches to early Chinese historiography.  

## Contents  

### 📘 Classical Chinese Texts (English Translation) Dataset

👉 [Access Table](TO DO)  
A structured corpus of **translated Classical Chinese texts**, compiled for linguistic, historical, and cultural research.
All texts are aligned by paragraph and include metadata such as book, chapter, and historical period.

---

#### 📊 Dataset Overview

* **Books:** 96
* **Chapters:** 4,039
* **Lines of Text:** 87,242
* **Languages:** Chinese (original) + English (translation)
* **Translation:** All texts are translated into English for comparative analysis.

---

#### 🧩 Data Structure

| Column                               | Description                                                    |
| ------------------------------------ | -------------------------------------------------------------- |
| `Paragraph`                          | Unique identifier for each paragraph or passage                |
| `TitleChinese`, `TitleEnglish`       | Title of the passage in Chinese and English                    |
| `ChineseText`, `EnglishText`         | Original text and its English translation                      |
| `Chapter Chinese`, `Chapter English` | Chapter title in both languages                                |
| `Book Chinese`, `Book English`       | Book title in both languages                                   |
| `Book period`                        | Historical period (e.g. “Warring States”, “Han”)               |
| `earliest_date`, `latest_date`       | Approximate date range (BCE/CE)                                |
| `link_title`                         | Short identifier or source tag                                 |
| `original_translation`               | Notes on whether the translation is manual or machine-assisted |

---

#### 🏺 Historical Coverage

The dataset spans multiple dynastic and intellectual periods, including:

* **Warring States texts** – e.g. *春秋左傳 (Chun Qiu Zuo Zhuan)*
* **Qin and Han dynasty works** – e.g. *焦氏易林 (Jiaoshi Yilin)*, *釋名 (Shi Ming)*

Each entry includes metadata on estimated composition dates and associated dynastic contexts.

---

#### 🧠 Use Cases

This dataset can be used for:

* 📚 Historical and philological studies
* 🤖 NLP and machine translation experiments
* 📈 Text mining and semantic analysis
* 🏺 Comparative literature and cultural research

---

#### ⚙️ File Info

* **Format:** CSV
* **Encoding:** UTF-8
* **Delimiter:** `,` (comma)
* **Sample size:** 87,242 rows

---

#### 🔗 Example Entry

| Field       | Example                                                                 |
| ----------- | ----------------------------------------------------------------------- |
| **Book**    | 春秋左傳 (*Chun Qiu Zuo Zhuan*)                                             |
| **Chapter** | 哀公 (*Ai Gong*)                                                          |
| **Period**  | Warring States (ca. 468 – 300 BCE)                                      |
| **Excerpt** | “In the seventeenth year, in spring, the Duke of Wei set a tiger trap…” |

---

### 2. Biographical Database of the Spring and Autumn and Warring States Periods  
- **2,017 entries** on individuals active between **770–221 BCE**.  
- Records include: **names, roles, affiliations, historical contexts**.  
- Useful for **prosopography, social network analysis, and comparative studies**.  

👉 [Access Database](https://webpage-test-in-s3-bucket-01.s3.us-east-2.amazonaws.com/biodb_sa_ws/index.html)  

---

### 🏺 *Zuo Zhuan* Text Dataset (人物资料集 / Individual Data Extracted from *Zuo Zhuan*)
👉 [Access Database](TO DO)  
A structured dataset derived from the *Zuo Zhuan* (左傳), containing extracted information on historical individuals, their roles, and relationships across the text.
This dataset enables quantitative analysis of personal networks, historical mentions, and social structure in early Chinese historiography.

---

#### 📊 Dataset Overview

* **Book:** *春秋左傳 (Zuo Zhuan)*
* **Chapters:** 255
* **Entries:** 3,285 extracted individuals
* **Languages:** Classical Chinese (original)
* **Data Type:** Annotated text + structured entity metadata

Each entry corresponds to one paragraph or passage and includes AI-extracted person names, identities, and chronological metadata.

---

#### 🧩 Data Structure

| Column                         | Description                                                      |
| ------------------------------ | ---------------------------------------------------------------- |
| `Paragraph`                    | Unique ID for each paragraph or passage                          |
| `TitleChinese`                 | Title of the section in Chinese                                  |
| `ChineseText`                  | Original Classical Chinese text                                  |
| `Chapter Chinese`              | Chapter name (e.g., 僖公元年)                                        |
| `Book Chinese`                 | Always “春秋左傳” (*Zuo Zhuan*)                                      |
| `Book period`                  | Historical context (e.g. Warring States)                         |
| `earliest_date`, `latest_date` | Estimated text composition range (BCE)                           |
| `name`                         | List of extracted individual names mentioned in the text         |
| `identity`                     | Contextualized description of each individual’s role or relation |
| `ChapterYear`                  | Chronological year corresponding to the event (BCE)              |

---

#### 🧠 Dataset Features

* **3,285 entries** of AI-extracted individuals from *Zuo Zhuan*
* Each entry includes:

  * Chronological **year and chapter**
  * **Named entities** (人物) with contextualized **roles, affiliations, and relationships**
  * Linkages across chapters for **network and frequency analysis**

---

#### 🔍 Analytical Potential

This dataset enables:

* **Prosopographical research** — mapping individuals and kinship networks
* **Temporal analysis** — tracking mentions across reigns and chapters
* **Social structure visualization** — linking rulers, ministers, and envoys
* **Linguistic pattern detection** — studying naming conventions and references

---

#### ⚙️ File Info

* **Entries:** 3,285 (sample file includes 1,000 rows)
* **Format:** CSV
* **Encoding:** UTF-8
* **Delimiter:** `,` (comma)
---

#### 🧩 Example Entry

| Field           | Example                   |
| --------------- | ------------------------- |
| **Chapter**     | 襄公二年                      |
| **Excerpt**     | “夏，齊姜薨，初，穆姜使擇美檟，以自為櫬…”    |
| **Individuals** | 姜夫人, 穆姜, 季文子, 季孙          |
| **Identities**  | 齐国君母, 姜夫人本人, 负责葬礼者, 其家族成员 |
| **Year**        | -571 BCE                  |

---

### 4. Biography by Time and Space (Map)  
- Interactive **map visualization** of biographical data.  
- Shows **spatial distribution** of individuals across states over time.  
- Highlights **regional concentrations, rise and decline of states**, and intersections of geography and chronology.  

👉 [Access Map](https://webpage-test-in-s3-bucket-01.s3.us-east-2.amazonaws.com/states_by_decade/states_by_decade/index.html)  

---

## Support  
This project is supported by **Harvard Library**.  
