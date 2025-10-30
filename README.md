# OP-Lockdown

Data and Python code for the article entitled, "Impact of COVID-19 lockdown on particulate matter oxidative potential at urban background versus traffic sites", with co-authors including Lucille Joanna S. Borlaza, Vy Dinh Ngoc Thuy, Stuart Grange, Stéphane Socquet, Emmanuel Moussu, Gladys Mary, Olivier Favez, Christoph Hueglin, Jean-Luc Jaffrezo, and Gaëlle Uzu. This article was submitted to RCS Atmospheres last 23 January 2023. DOI: 10.1039/D3EA00013C

This code has been implemented to reproduce the main analysis applied in the study (will be referenced once published). It uses long-term data of particulate matter (PM) and black carbon (BC) mass concentration, and oxidative poential activity of PM collected in an urban site in Grenoble, France and a traffic site in Bern, Switzerland. 

COVID-19 lockdown restrictions were first implemented in March 2020 to control the spread of the disease from the SARS-CoV-2 virus. These restrictions have provided a rare opportunity to assess air quality during a window with significantly reduced human-led activities. Many studies have reported a decrease in pollution levels during this period, but very limited information on the OP, an emerging metric of PM exposure. Most studies also used a traditional comparison with historical average, which may not be estimating the real pollution levels without the lockdown restrictions in place. 

To obtain a more realistic pollution level, a machine learning technique called Random Forest (RF) regression model was applied to predict a business-as-usual (BAU) level for OP, PM, and BC in both sites. 
