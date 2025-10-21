# Early Chinese Hundred Schools of Thoughts Database  

A collection of structured datasets and visualizations to support research in **early Chinese history, philosophy, and society**. This project integrates machine-extracted texts, biographical data, and spatial-temporal mapping tools to facilitate both quantitative and qualitative approaches to early Chinese historiography.  

## Contents  

# 📘 Classical Chinese Texts (English Translation) Dataset

A structured corpus of **translated Classical Chinese texts**, compiled for linguistic, historical, and cultural research.
All texts are aligned by paragraph and include metadata such as book, chapter, and historical period.

---

## 📊 Dataset Overview

* **Books:** 96
* **Chapters:** 4,039
* **Lines of Text:** 87,242
* **Languages:** Chinese (original) + English (translation)
* **Translation:** All texts are translated into English for comparative analysis.

---

## 🧩 Data Structure

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

## 🏺 Historical Coverage

The dataset spans multiple dynastic and intellectual periods, including:

* **Warring States texts** – e.g. *春秋左傳 (Chun Qiu Zuo Zhuan)*
* **Qin and Han dynasty works** – e.g. *焦氏易林 (Jiaoshi Yilin)*, *釋名 (Shi Ming)*

Each entry includes metadata on estimated composition dates and associated dynastic contexts.

---

## 🧠 Use Cases

This dataset can be used for:

* 📚 Historical and philological studies
* 🤖 NLP and machine translation experiments
* 📈 Text mining and semantic analysis
* 🏺 Comparative literature and cultural research

---

## ⚙️ File Info

* **Format:** CSV
* **Encoding:** UTF-8
* **Delimiter:** `,` (comma)
* **Sample size:** 87,242 rows

---

## 🔗 Example Entry

| Field       | Example                                                                 |
| ----------- | ----------------------------------------------------------------------- |
| **Book**    | 春秋左傳 (*Chun Qiu Zuo Zhuan*)                                             |
| **Chapter** | 哀公 (*Ai Gong*)                                                          |
| **Period**  | Warring States (ca. 468 – 300 BCE)                                      |
| **Excerpt** | “In the seventeenth year, in spring, the Duke of Wei set a tiger trap…” |


👉 [Access Table](TO DO)  

---

### 2. Biographical Database of the Spring and Autumn and Warring States Periods  
- **2,017 entries** on individuals active between **770–221 BCE**.  
- Records include: **names, roles, affiliations, historical contexts**.  
- Useful for **prosopography, social network analysis, and comparative studies**.  

👉 [Access Database](https://webpage-test-in-s3-bucket-01.s3.us-east-2.amazonaws.com/biodb_sa_ws/index.html)  

---

### 3. Biographical Database of the *ZuoZhuan*  
- **3,285 entries** of AI-extracted individuals from the *ZuoZhuan*.  
- Each entry linked to: **chronological date, role, affiliation, relationships**.  
- Enables analysis of **distribution, frequency, and interconnectedness** of individuals across the text.  

👉 [Access Database](TO DO)  

---

### 4. Biography by Time and Space (Map)  
- Interactive **map visualization** of biographical data.  
- Shows **spatial distribution** of individuals across states over time.  
- Highlights **regional concentrations, rise and decline of states**, and intersections of geography and chronology.  

👉 [Access Map](https://webpage-test-in-s3-bucket-01.s3.us-east-2.amazonaws.com/states_by_decade/states_by_decade/index.html)  

---

## Support  
This project is supported by **Harvard Library**.  
