# 🛠️ Build Notes

This document captures the foundational steps, thought process, and planning behind the development of the IPL Dashboard project.

---

## 📂 Dataset Information

We began by identifying a reliable IPL dataset to power the application.

- The dataset is sourced from **Kaggle**:  
  [IPL Dataset (2008–2025) by Abhishek Marathe](https://www.kaggle.com/datasets/maratheabhishek/ipl-dataset-2008-to-2025?utm_source=chatgpt.com&select=ipl_matches_data.csv)

- We specifically used the **`ipl_matches_data.csv`** file, which contains detailed match-level data spanning all IPL seasons.

- Kaggle allows you to **customize the dataset** based on your project needs before downloading — so feel free to filter out unnecessary fields or seasons as required.

---

## 🧠 Planning Phase

Before jumping into development, we invested time in **application architecture** and **system design**. This helped ensure:

- Code scalability and modularity
- Clean separation of backend and frontend responsibilities
- Efficient data ingestion and querying
- Smooth UI/UX experience with minimal re-renders

To begin shaping the product visually, a **hand-drawn wireframe/UI sketch** was created. This sketch helped:

- Define the core layout
- Plan feature placement
- Guide frontend development with a visual reference

📌 You can find the initial sketch inside the `README.md` under the section:  
[✍️ Raw Design (Before Development)](README.md#️-raw-design-before-development)

---

Each match can be a seprate page where
we will talk about all the things that are associate with tha match like who won the toss and stuff like that

![Raw Design](./Designs/SecondPage.png)
