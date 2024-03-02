# Objective
Since the free version of CHAT-GPT doesnt allow GPT to access the website, I prepared a webscrapping logic that scrapes the data from the website and based on the requirement, the data along with the requirement would be passed to CHAT-GPT and then the respponse from that is parshed and shown.

# Example
First the prompt would ask **"share the link that need to be accessed"** the link we shared, **'https://www.iucn.org/resources/issues-brief/marine-plastic-pollution'**

Then share what needs to be done with that website after system raises **"share what GPT need to do with that website"**. In the example case, we shared like **"you are summarizer, given a text summarise the important points alone and ignore unnecessary details"**

Then we sent the text as well as the requirement o Chat-GPT and parshed the response finally displayed as below

"Marine plastic pollution is a significant issue with at least 14 million tons of plastic ending up in the ocean every year. Plastic accounts for 80% of all marine debris, ranging from surface waters to deep-sea sediments. Plastic pollution poses severe threats to marine species who can ingest or become entangled in plastic debris, often resulting in severe injuries and death. In addition to affecting marine life, plastic pollution also threatens food safety and quality, human health, coastal tourism, and contributes to climate change. There is a stated urgent need for exploring new and existing legally binding agreements to address marine plastic pollution. The sources of plastic debris stem from both land-based activities such as urban and stormwater runoff, industrial activities, and inadequate waste disposal, as well as ocean-based sources like the fishing industry. Effective solutions require collaborative efforts from governments, research institutions, industries, and consumers to redesign products, rethink disposal methods, shift towards more sustainable consumption patterns, and increase funding for research to provide evidence-based solutions"

# Workflow
![alt-text](https://github.com/rakesh09111996/Summary_generation_GPT_API/blob/77e972354325c30538933b0ec32399db313ca4d2/webscrapping_GPT_API.png)
