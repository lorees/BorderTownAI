## BorderTown AI is border security for Generation now! Leveraging the speed and accuracy of AI to perform security asessments at the Border. Which Border? Any Border! From the Large Campus to the Native American Reservation to the US Southern Border, BorderTown AI can assist. Please read on for our case study.

# BorderTown AI (Azure ML Project)

Welcome to BorderTown AI, where we are deploying an AI system to identify individuals who should undergo further examination upon re-entry to BorderTown. This system is exclusive to credentialed residents of BorderTown who do not exhibit suspicious behavior.

Crime scores are compiled from BorderTown PD and neighboring municipalities with information-sharing agreements. Upon ID issuance, residents authorize BorderTown to conduct criminal background checks and assign a corresponding crime score.

## Issue
BorderTown is an idyllic community renowned for its rare wildlife and breathtaking atmosphere. Nestled throughout the landscape are rare old-growth trees, and the parcels of land are vast. The residents are known for their friendliness and welcoming demeanor to all. However, BorderTown lacks native industries, aside from local shops and the BeeKeepers. Most residents venture outside of BorderTown for work and recreation, as there are casinos, pool halls, bowling alleys, and event centers in the surrounding municipalities. The remaining residents homesteda and thrive on bartering.

BorderTown operates as a communal community, where all residents share in the bounty. As a commune, they receive significant tax breaks and are regarded as a stand-alone municipality. It is in everyone's best interest to protect this community of 30,000 from outside invasion.

In recent times, BorderTown has observed a troubling rise in organized crime and drug smuggling. To address these challenges, they have turned to AI to predict who should be detained for further examination or questioning upon re-entry.

## BorderTown ID Card
To expedite admission into BorderTown, individuals must possess a BorderTown-issued ID card, issued to those over the age of 16. Here are some key points about the ID card:

- The ID card expedites admission.
- Daily travelers have been preapproved and issued a special status, exempt from this system.
- Despite pre-approval, daily travelers are subject to 100% random searches.

## Privacy Rules
BorderTown is actively working towards implementing an AI system to assist in identifying potential risks and criminal activities. Each resident issued an ID card receives a crime score based on various factors such as behavioral patterns and past encounters with law enforcement. This score will aid BorderTown officials in assessing potential threats and individuals who may require further scrutiny upon re-entry. The AI system, once fully operational, will analyze data patterns and trends to predict potential risks, enhancing the safety and security of the community.

### List of Smuggler Characteristics (Non-Daily Pedestrians):
- Anyone under the age of 18 should be flagged.
- Any person leaving BorderTown and returning in less than 4 hours are flagged.
    - Elderly persons over the age of 65 that stay for less than 4 hours are flagged.
- Females under the age of 24 with 3 kids or more are regularly apprehended with contraband (in the kids' diapers).
- Boys under the age of 25 that travel in groups of 2 or more are flagged.
- Any person leaving BorderTown and not returning for more than 72 hours are flagged.
- Any person with a crime score greater than 65 is not allowed re-entry to BorderTown and are flagged.

## Our Task
Our objective is to develop a pilot AI model and system tailored to BorderTown's needs, focusing on identifying characteristics of potential smugglers. This system aims to streamline re-entry requests for BorderTown agents by flagging individuals who fit specific criteria. Upon re-entry into BorderTown, individuals' ID cards are scanned, capturing their name, age, sex, crime score (ranging from 0 to 100), home address, and date of departure. The number of companions accompanying a traveler is entered by an agent or at one of the re-entry kiosks manually. Lastly, the new system must be fast so that pedestrian traffic can be expedited and the current bottlenecks at the entry point can finally be alleviated.

## Reasons for Flagging:
- `reason = 1`: Stay under 4 hours
- `reason = 2`: Age under 18 years old
- `reason = 3`: Female under 24 years old with 2 or more kids
- `reason = 4`: Male under 25 with 2 or more companions
- `reason = 5`: Stay greater than 72 hours
- `reason = 6`: Crime score greater than 65
- `reason = 7`: Administrative Selection - 100% Random - Acts as a control so people cannot learn the algorithm and bypass security

* 1A Detainment - Holding Cell Detainment \ Full Search \ Full Background Check \ Deportation \ Extradition
 
---

### Author
- **Name:** Loree S.
- **Email:** Lorees35@gmail.com
- **YouTube:**  https://www.youtube.com/c/kumputerkar
