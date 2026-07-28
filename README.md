# 🥔 Quantium Chip Category Analysis & Store Trial Impact Study

> Can a new store layout actually move the needle on sales — or are you just watching normal noise? This project answers that question with real statistical rigor, not guesswork.

---

## The Business Problem

A retail client is planning strategy for the next half of the year and needs answers to two questions:

1. **Who actually drives chip category sales, and why?**
2. **Did a new store layout, trialed in 3 stores, genuinely increase sales — or would those stores have sold more anyway?**

This project answers both, end-to-end: from raw transaction data to a client-ready presentation, using the same experimental design logic real retail analytics teams use to test in-store changes.

---

## Key Findings

Who spends the most?  
**Older Families (Budget)** and **Young Singles/Couples (Mainstream)** — for completely different reasons

What actually drives sales differences?  
Purchase **frequency** and **customer volume** — not basket size, not pack size

Which brand wins?  
**Kettle** — nearly 2x the sales of the next closest competitor

Did the new store layout work?  
**Yes.** All 3 trial stores showed statistically significant sales increases — up to **+74%** in the strongest-performing store |

> The most interesting result isn't that sales went up — it's that they went up at *different times and speeds* in each store, which changes how you'd recommend rolling this out.


## What This Project Actually Involved

### Part 1 — Category & Customer Analysis
- Cleaned 260K+ rows of transaction data (outlier removal, feature extraction, category filtering)
- Engineered features: pack size, brand, customer lifestage & spend tier
- Identified sales drivers across 21 customer segments
- Analyzed seasonality, brand performance, and store-level concentration

### Part 2 — Store Trial Impact Analysis
This is the core of the project — a proper **causal impact study**, not just a before/after comparison:

- Built monthly store-level metrics (sales, customers, transactions per customer)
- Filtered to stores with complete 12-month data for fair comparison
- **Selected control stores** for each trial store using a combined correlation + magnitude-similarity score across 3 metrics
- **Scaled control stores** to each trial store's pre-trial baseline
- Ran **significance testing (t-tests)** on trial-period performance vs. control, using pre-trial variability as the noise threshold
- Visualized trial vs. control performance to make the effect visible, not just statistical

### Part 3 — Client Reporting
- Translated every technical finding into plain-language business insight
- Built a client-ready presentation using the **Pyramid Principle** (answer first, then supporting evidence)
- Designed for a non-technical stakeholder — zero jargon, all commercial action

---

## Sample Visuals

<img width="3600" height="1800" alt="total_sales_by_segment" src="https://github.com/user-attachments/assets/4793aaf9-2c81-4b1c-8ba0-54b283b7ba32" />
<img width="3600" height="1800" alt="sales_by_pack_size" src="https://github.com/user-attachments/assets/38117039-a6ca-498a-bbdb-add3b7d3f4b2" />
<img width="3600" height="1800" alt="customers_by_segment" src="https://github.com/user-attachments/assets/f5f39977-6bf1-484a-bba6-c06187e48c9d" />
<img width="3600" height="1800" alt="sales_over_time" src="https://github.com/user-attachments/assets/376bf67c-bee4-47be-8c42-6a751ef4cc37" />
<img width="1650" height="1950" alt="trial_vs_control_all" src="https://github.com/user-attachments/assets/54e5f67f-ed87-4e90-81b4-4741dd2df945" />

---

## Tools & Techniques

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `SciPy (stats)` · `Jupyter Notebook` · `PowerPoint`

**Techniques:** data cleaning & feature engineering, exploratory data analysis, control group experiment design, statistical hypothesis testing, data storytelling

---

## What I'd Tell Someone Reading This

The technical part — cleaning data, building models, running t-tests — is the easy half. The harder, more valuable skill this project forced me to practice was **proving an effect is real before recommending action on it**, and then explaining *why* it's real to someone who doesn't want to hear the word "t-value." That's the actual job of a data analyst, and it's the part I found most useful to build.

---

## Let's Connect

I'm currently looking for **Data Analyst / Business Analyst** opportunities. If this project is relevant to a role you're hiring for, or you just want to talk shop about retail analytics, feel free to reach out.

- GitHub: [gauravmandhan2-design](https://github.com/gauravmandhan2-design)
- LinkedIn: https://www.linkedin.com/in/gaurav-mandhan-719a95407/

---

*This project was completed as part of the Quantium Data Analytics Virtual Internship on [Forage](https://www.theforage.com/). Analysis, code, and commentary are my own.*
