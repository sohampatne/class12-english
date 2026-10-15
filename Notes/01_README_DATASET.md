# CBSE Class 12 English Core — Past Year Question Papers Dataset (2022–2026)

## 📌 Dataset Overview

This dataset comprehensively parses, structures, and links all CBSE Class 12 English Core previous year question paper PDF files from **2022 to 2026** (including Main Board Examinations and Compartment / Supplementary Examinations).

Every single question across all sets is parsed, categorized by section, mapped to its NCERT textbook and chapter, and annotated with the **exact years it was asked** (`years_asked`) and its frequency of occurrence across examination series and sets.

---

## 📁 Generated Files

| File | Size | Description |
| :--- | :--- | :--- |
| [`cbse_class12_english_questions.json`](./cbse_class12_english_questions.json) | ~2.0 MB | **Unified Question Bank** containing **1,236 unique questions** across Reading, Writing, and Literature with chapter mapping, word limits, marks, and **`years_asked`** cross-year tracking. |
| [`cbse_class12_english_papers.json`](./cbse_class12_english_papers.json) | ~3.6 MB | **Hierarchical Paper-by-Paper Collection** containing all **93 question papers**, their sections, metadata (QP code, Series, Set, Max Marks, Time), and structured questions. |

---

## 📊 Summary Statistics

- **Total PDF Pages Processed**: **1,536 pages** (across 23 PDF files)
- **Total Individual Question Papers**: **93 papers**
  - **2022 Main Exams**: 15 papers (5 Series, Sets 1–3, Term 2 descriptive format)
  - **2023 Main Exams**: 15 papers (5 Series, Sets 1–3, 80-mark standard format)
  - **2024 Main Exams**: 15 papers (5 Series, Sets 1–3, 80-mark standard format)
  - **2025 Main Exams**: 18 papers (6 Series, Sets 1–3, 80-mark standard format)
  - **2026 Main Exams (`ENGLISH_CORE 2026`)**: 15 papers (Series QR1SP, S2RPQ, Q3SPR, S4PRQ, S5RPQ, Sets 1–3)
  - **Compartment Exams (2022–2025)**: 12 papers (Sets 1–3 for each academic year)
  - **2026 Compartment Exams (`ENGLISH_CORE Compartment Examination 2026`)**: 3 papers (Series S7PQR, Sets 1–3)
- **Total Unique Questions in Question Bank**: **1,236 questions**
- **Multi-Year Repeated Questions**: **19 questions** tracked with appearances across multiple board exam years.

---

## 📂 Section-Wise Question Breakdown

| Section | Question Count | Question Types Included |
| :--- | :--- | :--- |
| **Section C: Literature** | **731** | Short Answer (Flamingo/Vistas), Long Answer, Poetry Extracts, Prose Extracts |
| **Section B: Creative Writing Skills** | **494** | Notice Writing, Invitations & Replies, Letters to Editor / Applications, Articles & Reports |
| **Section A: Reading Skills** | **11** | Discursive/Descriptive Passages, Case-Based Factual Passages (with ~18–20 subquestions each) |

---

## 📅 Questions by Year Mentioned

- **Year 2022**: 112 questions
- **Year 2023**: 318 questions
- **Year 2024**: 263 questions
- **Year 2025**: 258 questions
- **Year 2026**: 312 questions

---

## 🔁 Notable Multi-Year Repeated Questions (including 2026)

1. **The Rattrap (Flamingo)**:
   > *"Why did the crofter show thirty kronor to the rattrap peddler ?"*
   - **Years Asked**: `[2022, 2026]`
   - **Insight**: Asked in 2022 Term 2 board examination, and repeated in the 2026 board examination series!

2. **The Rattrap (Flamingo)**:
   > *"Why did the peddler decline the ironmaster's invitation ?"*
   - **Years Asked**: `[2024, 2026]`

3. **The Rattrap (Flamingo)**:
   > *"Why did the peddler respect the confidence reposed in him by the crofter ?"*
   - **Years Asked**: `[2024, 2026]`

4. **The Interview (Flamingo)**:
   > *"What is the belief in some primitive cultures about being photographed ?"*
   - **Years Asked**: `[2024, 2026]`

5. **Poets and Pancakes (Flamingo)**:
   > *"What caused the lack of communication between the Englishman and the people at Gemini Studios ?"*
   - **Years Asked**: `[2025, 2026]`

6. **Indigo (Flamingo)**:
   > *"Why did Gandhi agree to a settlement of 25% refund to the farmers ?"*
   - **Years Asked**: `[2022, 2025]`

7. **The Third Level (Vistas)**:
   > *"Why did the booking clerk refuse to accept the money offered by Charley ? (The Third Level)"*
   - **Years Asked**: `[2023, 2025]`

8. **On the Face of It (Vistas)**:
   > *"Why does Derry not like being with people ?"*
   - **Years Asked**: `[2023, 2024]`

---

## 💡 JSON Schema Guide for AI Reference

### Schema: `cbse_class12_english_questions.json`

```json
{
  "question_id": "CBSE-ENG12-Q0932",
  "section": "Section C: Literature",
  "question_type": "Short Answer Questions (Flamingo / Vistas)",
  "book": "Flamingo (Prose)",
  "chapter_or_poem": "The Rattrap",
  "question_text": "Why did the crofter show thirty kronor to the rattrap peddler ?",
  "marks": 2,
  "word_limit": "40-50 words",
  "years_asked": [2022, 2026],
  "years_count": 2,
  "total_appearances": 2,
  "appearances": [
    {
      "year": 2022,
      "exam_type": "Main",
      "qp_code": "1/5/1",
      "series": "A5BAB/5",
      "set": "1",
      "question_number": "Q5(iii)",
      "paper_id": "CBSE_2022_MAIN_1_5_1_SET1"
    },
    {
      "year": 2026,
      "exam_type": "Main",
      "qp_code": "1/3/1",
      "series": "Q3SPR",
      "set": "1",
      "question_number": "Q10(iv)",
      "paper_id": "CBSE_2026_MAIN_1_3_1_SET1"
    }
  ]
}
```

### Schema: `cbse_class12_english_papers.json`

```json
{
  "paper_id": "CBSE_2026_MAIN_1_3_1_SET1",
  "metadata": {
    "year": 2026,
    "exam_type": "Main",
    "qp_code": "1/3/1",
    "series": "Q3SPR",
    "set": "1",
    "time_allowed": "3 hours",
    "max_marks": 80,
    "start_page": 1,
    "end_page": 19,
    "total_pages": 19
  },
  "sections": [
    {
      "section_name": "Section A: Reading Skills",
      "marks": 20,
      "questions": [...]
    },
    {
      "section_name": "Section B: Creative Writing Skills",
      "marks": 18,
      "questions": [...]
    },
    {
      "section_name": "Section C: Literature",
      "marks": 40,
      "questions": [...]
    }
  ]
}
```
