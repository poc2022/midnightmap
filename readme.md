# MidnightMap
## _Uncover Industrial Scale Web Attack Surfaces_

_A concept tool currently under development that provides intelligence into the attack surface of web applications
within geographic regions and/or TLDS_


## Current Features -

- Web technology Stack Analysis Output
- Optimised DuckDuckGo Lite Search Integration
- Removal of TLD Specific Common Domains to refine results
- Country Based IP Address Checks / TLD Specification
- Translation to Local Language
- DuckDuckGo Advanced Search Capabilities
- Same technology detection catalogue as Wappalyzer
- DuckDuckGo Acts as a Privacy Based Proxy for Searches and Translations

## Work In Progress -

- Replacing Webtech with Dynamic Content Loading Solution
- Numerous TLDs in a Single Command
- Graphical Data Analytics

## Known Issues -

- Some web applications with WAFs are not showing tech stack results properly
- Pages that require JS to load fully do not show all technologies

## Installation

MighdnightMap requires [Python 3 - 3.10+](https://www.python.org/) to run.

Git Clone the repository & navigate to the directory

```bash
git clone https://github.com/nathan-watson-uk/MidnightMap.git

cd MidnightMap
```

Install the requirements:

```bash
pip3 install -r requirements.txt
```

Install random-user-agent and webtech:
```bash
pip3 install random-user-agent
pip3 install webtech
```

Run the script and view the usage page:
```bash
python3 midnightmap.py -h
```

## Disclaimer -

The MidnightMap tool is provided for educational and research purposes only. By using this tool, you acknowledge and agree that:

- **User Responsibility**: You are solely responsible for your use of MidnightMap and any consequences thereof. The developers of MidnightMap shall not be responsible for any misuse or illegal use of this tool by users.

- **Legal Compliance**: You will comply with all applicable laws, regulations, and ethical standards governing your use of this tool, including but not limited to data protection laws and regulations.

