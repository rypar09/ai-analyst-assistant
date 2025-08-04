# AI Analyst Assistant 📊🤖

This project automatically extracts, summarizes, and analyzes the most critical sections from the latest 10-K filings of public companies — using the SEC API and OpenAI’s language models. The output includes both a comprehensive full-length research report and a clean, one-page investment brief, each formatted in Microsoft Word.

---

## 🧠 What It Does
✅ Fetches the latest 10-K filing for selected tickers from the SEC
✅ Extracts Items 1 (Business), 1A (Risk Factors), and 7 (MD&A)
✅ Summarizes and analyzes these sections using OpenAI (GPT-3.5 or GPT-4)
✅ Produces two output documents:
      - A detailed Full Equity Research Report (with analyst placeholders)
      - A short, objective Investment Brief in flowing paragraph form
✅ Converts all outputs to clean .docx Word files

---

## 🚀 How to Use

1. **Clone the repository**

git clone https://github.com/rypar09/ai-analyst-assistant.git
cd ai-analyst-assistant

2. **Install dependencies**

pip install -r requirements.txt

3. **Set up your environment variables**
   
Create a `.env` file in the project root with the following content:
   SEC_API_KEY=your-sec-api-key-here
   OPENAI_API_KEY=your-openai-api-key-here

You can use the provided `.env.example` as a template.

4. **Run the notebook**

Open `AIAnalystAssistant.ipynb` in Jupyter or VS Code, update the tickers list, and run all cells.

---

## 📄 Example Outputs

- 10k_sections/ — Extracted raw sections (txt)
- full_reports/ - Full-length research reports (txt + docx)
- investment_briefs/ - One-page investment briefs (txt + docx)


---

## 🔐 API Notes

- [SEC API](https://sec-api.io/docs/) — Used to pull 10-K filings  
- [OpenAI API](https://platform.openai.com/docs) — Used to generate summaries & analysis

---

## 🛡️ Disclaimer

This tool is for **educational and research purposes only**. 
It does not constitute investment advice.

---

## 🙌 Credits

Built by [@rypar09](https://github.com/rypar09)

