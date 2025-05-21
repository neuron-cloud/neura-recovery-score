# NEURA Recovery Risk Score (v0.1)

NEURA is an AI-powered recovery intelligence tool that predicts post-treatment risk and generates emotionally aware patient support, based on free-text clinical notes.

This prototype simulates two major NEURA functions:
1. **Clinical Recovery Risk Score** — Uses LLMs to extract and score 5 recovery domains: Cognitive, Emotional, Functional, Adherence, Social
2. **Recovery OS (Patient Layer)** — Generates journaling prompts and guidance to support post-treatment emotional healing

---

## 💻 Demo Instructions

### Option 1: Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `NEURA_Recovery_Risk_Score_v0_1.ipynb` notebook
3. Paste your **OpenAI API key** in the marked cell
4. Run all cells and view outputs

> This notebook uses the `gpt-4o` model but can be adapted for `gpt-3.5-turbo` if needed.

---

## 🧠 Sample Input

```
38F no PMH p/t RUMC w/HA x1 yr worsening in last 2 months, CTH w/Lt frontotemporal lesion extending into Lt thalamus, w/8mm Rt MLS, mild obstructive hydro. Pt reports intermittent WFD and intermittent confusion x2mo. No ACAP. H/H 8.4/27.9, PLT 404, Coags pending. Exam - intact
```

---

## 🧾 Sample Output

- **Recovery Risk Score:** 60/100 (Moderate)
- **Journaling Prompt Example:**  
  “Reflect on your resilience: What inner strengths did you discover in yourself during this journey?”

---

## 🔐 API Key Security

This notebook includes a placeholder line for your OpenAI API key:

```python
client = OpenAI(api_key="YOUR_API_KEY_HERE")
```

Never share your actual API key publicly.

---

## 📬 Contact

Built by **Dr. Mychael Delgardo**  
Email: mwdelgardo@gmail.com  
Demo inquiries, feedback, or pilot partnerships welcome.

---

## 🪪 License

Open-source, MIT License.
