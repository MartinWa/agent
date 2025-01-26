Initialise with

```powershell
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt 

[System.Environment]::SetEnvironmentVariable('AZURE_OPENAI_API_KEY', 'REPLACE_WITH_YOUR_KEY_VALUE_HERE', 'User')
[System.Environment]::SetEnvironmentVariable('AZURE_OPENAI_ENDPOINT', 'REPLACE_WITH_YOUR_ENDPOINT_HERE', 'User')

$env:AZURE_OPENAI_API_KEY = 'REPLACE_WITH_YOUR_KEY_VALUE_HERE'
$env:AZURE_OPENAI_ENDPOINT = 'REPLACE_WITH_YOUR_ENDPOINT_HERE'
$env:TAVILY_API_KEY = 'REPLACE_WITH_YOUR_TAVILY_API_KEY_HERE'
```