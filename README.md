# API Data Fetch and Citation Extraction
This Python script takes data from the listed API pages and processes it to display quotes based on the answer text and the given source. 
Each API response contains an array of objects where each object contains corresponding response text and sources. 
The label excludes the source (citations) from which the response text is obtained.

# Features
Fetches data from a paginated API endpoint.
Parses JSON responses, even if returned as strings.
Identifies relevant citations by comparing response texts with source contexts.
Outputs the results in a structured format.

# Prerequisites
Python 3.x+
requests library

# Usage
Save the script as fetch_citations.py.
Run the script:
"python fetch_citations.py"

## Example
# Input
![image](https://github.com/Ansh420/Assignment/assets/91012440/cde7362b-1272-4c95-b542-a5b08ae36b25)
# Output
The script will produce the following output:
![image](https://github.com/Ansh420/Assignment/assets/91012440/f6b2d149-9b4f-4484-9c38-efee4ef7eefe)

