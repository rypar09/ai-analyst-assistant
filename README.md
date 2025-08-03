# AI Analyst Assistant 📊🤖

This project automatically extracts, summarizes, and analyzes the **MD&A section** from the most recent 10-K filings for public companies — using the SEC API and OpenAI's language model. The final output is a formal Word report suitable for investment research.

---

## 🧠 What It Does

✅ Fetches the latest 10-K filing for selected tickers from the SEC  
✅ Extracts the MD&A (Management’s Discussion & Analysis) section  
✅ Summarizes and analyzes the section using OpenAI (GPT-3.5)  
✅ Generates a clean, formal investment brief in Word format

---

## 🗂️ Project Structure

ai-analyst-assistant/
├── AIAnalystAssistant.ipynb # Main Jupyter notebook
├── .env.example # Template for API keys
├── requirements.txt # Dependencies
├── .gitignore # Files/folders to ignore
├── summaries/ # GPT-generated summaries (ignored)
├── mdna_texts/ # Raw MD&A text files (ignored)
├── word_reports/ # Final Word document reports (ignored)
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

- `AAPL_mdna.txt` — Raw extracted MD&A section  
- `AAPL_summary.txt` — GPT-generated summary  
- `AAPL_summary.docx` — Formal investment brief

---

## 🔐 API Notes

- [SEC API](https://sec-api.io/docs/) — Used to pull 10-K filings  
- [OpenAI API](https://platform.openai.com/docs) — Used to generate summaries & analysis

---

## 🛡️ Disclaimer

This tool is for **educational and research purposes only**. It does not constitute investment advice.

---

## 🙌 Credits

Built by [@rypar09](https://github.com/rypar09)

