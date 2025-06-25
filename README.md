# 📚 N-gram Language Model Construction for Oromo & Amharic

This project performs **text preprocessing**, **orthographic normalization**, and builds a **5-gram language model** using the [KenLM](https://github.com/kpu/kenlm) toolkit. The target languages are **Oromo**, **Amharic**, and **Luo**, primarily for use in ASR (Automatic Speech Recognition) and NLP systems.

---

## 🎯 Objectives

- Clean and normalize large raw text corpora.
- Extract valid characters and count unique sentences.
- Build an ARPA-formatted 5-gram language model using **KenLM**.
- Optionally convert ARPA to binary format for fast querying.

---

## 🗂️ File Structure

```bash
ngram_oromo.py                       # Main script
general_update_14th_clean2.txt       # Preprocessed Amharic/Oromo text
5gram_corrected_orm.arpa             # Output ARPA model file
5gram.binary                         # (Optional) Binary model for fast use
