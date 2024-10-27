<img src="https://github.com/ssajedi/upzone/blob/main/assets/logo.png" width="300">


# UPZONE
UpZone is your one-click solution to identifying your NYC lot's buildable zoning volume. The app searches multi-thousand-page zoning resolution documents and nyc.gov websites, identifies relevant zoning requirements with the help of large language models, and models a 3D volume in Rhino that is ready for designers to build their designs within. UpZone is an app developed during the 2024 [AECTech Hackathon](https://www.aectech.us/nyc-conference) by a diverse team of architects, software developers, ML engineers, computational designers, and structural engineers.

# Prerequisites
In order to use UPZone, you will need:
* A free [Shapediver](https://www.shapediver.com/) account
* An [OpenAI API key](https://platform.openai.com/)

# Zone parameters 
The team experimented with two methods to extract the following parameters:
* Setback: front, rear, side
* Sky exposure angle
* Height limit
* Maximum height for front yard line

## ChatGPT (method 1)
We utilized [Swiftlet](https://www.food4rhino.com/en/app/swiftlet) to call the ChatGPT API and extract these values from the LLM. Please refer to the grasshopper definition for further details on how prompt engineering was done. 

## Web search + Gemini experiment (method 2)
We utilized a python library to perform search using [DuckDuckGo library](https://pypi.org/project/duckduckgo-search/) and scrape web for the required values. The inputs were then fed to Google Geimini Flash 1.5. 

  
# Grasshopper Plugin
[Elcin and Jari]

# Team Members

| Name                                   | Company                        |
|----------------------------------------|--------------------------------|
| **Anish Reddy**                        | Perkins & Will                 | 
| **Eddy Lopez**                         | LPA                            |
| **Elcin Ertugrul**                     | Thornton Tomasetti (CORE)      |
| **Georgios Athanasopoulos**            | Thornton Tomasetti (CORE)      |
| **Jari Prachasartta**                  | KPF                            |
| **Jihoon Park**                        | Walter P Moore                 |
| **Joyce Hanlon**                       | Snøhetta                       |
| **Mahsa Dehghani**                     | Memo Studio & Corgan           |
| **Omid Sajedi**                        | Thornton Tomasetti (CORE)      |
| **Susanna van de Graaf**               | Thronton Tomasetti             |
