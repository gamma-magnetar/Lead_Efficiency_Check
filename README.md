🔍 Lead Efficiency Check

A smart lead scoring system that enriches and ranks raw B2B lead data based on three critical signals: job title relevance, email validity, and website authenticity. Built to help growth and marketing teams prioritize outreach effectively by surfacing the best leads at the top.

🧠 Objective

To design a lead quality pipeline that analyzes raw CSVs of B2B leads and produces a ranked, enriched output. The system helps teams:

1 . Prioritize outreach with confidence

2 . Focus on credible leads

3 . Cut noise from invalid or spammy data





🔧 How to Use

1️⃣ Clone the repo

git clone https://github.com/gamma-magnetar/Lead_Efficiency_Check.git
cd Lead_Efficiency_Check

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Set up .env file

Create a .env file in the root with:

TOGETHER_API_KEY=your_together_ai_key
NEVERBOUNCE_API_KEY=your_neverbounce_key

4️⃣ Prepare your leads file

Save your lead file as leads_input.csv file in the path.

Ensure your leads_input.csv has the following columns:

name,title,email,linkedin_url,company,domain

5️⃣ Run the program (run logic/main.py)

python logic/main.py

Enter your target role when prompted (e.g., Marketing Manager).

