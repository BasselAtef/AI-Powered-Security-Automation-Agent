# AI-Powered-Security-Automation-Agent
This Agent scans URLs using VirusTotal and returns a formal security report.

📋 Prerequisites
Before running this notebook, please install the required versions of the LangChain packages:
(These commands are copy-paste ready)

pip install langchain==0.3.13
pip install langchain-core==0.3.63
pip install langchain-openai==0.2.14


⚙️ Setup
API Keys: You will need to provide your own API keys in the notebook:

api_key: Your Google Gemini API Key.
VT_API_KEY: Your VirusTotal API Key.

Note: If you have problems with the free API(eg. Not enough credits) Try to change the Gemini model version to gemini-1.5-flash or other versions.

⚙️ Usage
You can insert the URL that you want to scan after the invoke section.
This is just an example:

ex_agent.invoke({
    "input": "Please analyze this link and give me a security report: http://example.com/index.html"
}



