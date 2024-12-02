# Global-deforestation---Capstone-Project

[!Alt text]https://res.cloudinary.com/dwg1qhmrv/image/upload/v1733169807/y0fuvnmgccwz9pbup4iv.jpg

* **1.1 Project Overview** This report aims to discuss the topic of deforestation & what we can do as a population to stop it.
Deforestation is a worldwide concern & according to the Green Earth Blog - many countries - such as Honduras, The Phillipines & Benin - have high deforestation rates. We will explore why the world needs trees, the leading causes of deforestation, the objectives of the project as well as the origin of the data & the importance of the study. Using statistical data analysis, creating visuals & training & evaluating models - my goal is to find possible solutions to the issue of deforestation.   
Finally - I hope to prove that tackling deforestation requires global cooperation, sustainable land management, reforestation efforts, and responsible consumption patterns. Protecting forests is essential not only for preserving biodiversity and mitigating climate change but also for ensuring a sustainable future for all life on the planet.



* **1.2 Problem Statement:**
Why do we need trees? According to the World Wildlife Fund
"Forests cover nearly one-third of the land area on our planet and are home to most of the world’s life on land. They are also essential to human health, purifying our water and air and serving as our first line of defense against new infectious diseases. Additionally, forests provide more than 86 million green jobs and resources such as food and fuel that support billions of people’s livelihoods. Forests also play a critical role in mitigating climate change because they act as carbon sinks—soaking up carbon dioxide that would otherwise be free in the atmosphere and contributing to ongoing changes in climate patterns."

So what are the leading causes of deforestation?

1. Agriculture - Agriculture is one of the leading causes of deforestation, primarily driven by the need for more land to meet growing food demands.The process unfolds through several key processes such as expansion of farmland,shifting cultivation,livestock ranching,plantation agriculture,slash-and-burn agriculture & agricultural infrastructure leading to loss of biodiversity, soil erosion, water cycle disruption, and increased greenhouse gas emissions, all of which exacerbate climate change.

2. Loss of Biodiversity - Forests are home to an enormous variety of species. When forests are destroyed, many plants, animals, and microorganisms lose their habitat, leading to the extinction of species and reduced biodiversity.
3. Climate Change - Forests play a vital role in regulating the Earth's climate by absorbing carbon dioxide (CO₂) during photosynthesis. When trees are cut down or burned, they release stored CO₂ back into the atmosphere, contributing to global warming and exacerbating climate change.
4. Disruption of Water Cycles - Forests help regulate the water cycle by absorbing and releasing moisture through transpiration. Deforestation can reduce rainfall, contribute to droughts, and increase the risk of flooding, disrupting local and global water systems.
5. Soil Degradation - Trees and vegetation help anchor the soil, preventing erosion. Deforestation leaves the soil exposed to the elements, leading to erosion, reduced soil fertility, and desertification in some regions.
6. Impact on Indigenous Communities - Many indigenous and local communities rely on forests for their livelihood, food, and cultural practices. Deforestation threatens their way of life and forces them to relocate, often leading to economic hardship and loss of cultural heritage.
7. Economic Consequences - While deforestation may provide short-term economic benefits (e.g., through logging or agriculture), it can lead to long-term economic losses. The depletion of natural resources, loss of ecosystem services, and environmental degradation can harm economies dependent on agriculture, tourism, and natural resources.



* **1.3 Project Objectives:**

The objectives of this project are the following:
- To analyze historical trends in global forest coverage
- To quantify regional contributions to global deforestation in percentage & in kilometers squared
- To evaluate the rate of forest area decline in percentage & in kilometers squared
- To compare forest area change across countries and regions in percentage & kilometers squared
- To create geospatial visualizations of forest area changes over a period of 30 years
- To predict future forest coverage in percentage & in kilometers squared

* **1.4 Origin of the Data:**

The data was sourced from the Kaggle website. The data consist of two files in the .csv format.One named forest_area_km & forest_area_percentage. It includes columns for country name, country code & year.

* **1.5 Importance of the Study:**
Why does deforestation matter?

There are about 250 million people who depend on forests and savannas for subsistence and income, many of whom are among the world's rural poor. Eighty percent of Earth's land animals and plants live in forests, and deforestation threatens many species. Removing trees disrupts the forest's canopy, leading to more extreme temperature swings that can harm plants and animals. With wild habitats destroyed and human life expanding, the line between animal and human areas blurs, opening the door to zoonotic diseases, as seen with the 2014 Ebola outbreak in West Africa.

In short - knowing about the impact of deforestation is vital for safeguarding the planet's environmental health, maintaining biodiversity, and ensuring sustainable livelihoods. It empowers individuals and governments to make informed choices that can help mitigate the damage and work toward a more sustainable and resilient future for all life on Earth.

**Loading of Packages**
The following packages were loaded into the Anaconda environment
Package                   Version
------------------------- -----------
anyio                     4.6.2
argon2-cffi               21.3.0
argon2-cffi-bindings      21.2.0
asttokens                 2.0.5
async-lru                 2.0.4
attrs                     24.2.0
Babel                     2.11.0
beautifulsoup4            4.12.3
bleach                    6.2.0
Bottleneck                1.4.2
branca                    0.6.0
Brotli                    1.0.9
certifi                   2024.8.30
cffi                      1.17.1
charset-normalizer        3.3.2
click                     8.1.7
click-plugins             1.1.1
cligj                     0.7.2
colorama                  0.4.6
comm                      0.2.1
contourpy                 1.3.1
cryptography              43.0.3
cycler                    0.11.0
debugpy                   1.6.7
decorator                 5.1.1
defusedxml                0.7.1
executing                 0.8.3
fastjsonschema            2.20.0
fiona                     1.9.5
folium                    0.14.0
fonttools                 4.51.0
GDAL                      3.6.2
geopandas                 0.14.2
greenlet                  3.0.1
h11                       0.14.0
httpcore                  1.0.2
httpx                     0.27.0
idna                      3.7
ipykernel                 6.29.5
ipython                   8.27.0
jedi                      0.19.1
Jinja2                    3.1.4
joblib                    1.4.2
json5                     0.9.25
jsonschema                4.23.0
jsonschema-specifications 2023.7.1
jupyter_client            8.6.0
jupyter_core              5.7.2
jupyter-events            0.10.0
jupyter-lsp               2.2.0
jupyter_server            2.14.1
jupyter_server_terminals  0.4.4
jupyterlab                4.2.5
jupyterlab-pygments       0.1.2
jupyterlab_server         2.27.3
kiwisolver                1.4.4
mapclassify               2.5.0
MarkupSafe                2.1.3
matplotlib                3.9.2
matplotlib-inline         0.1.6
mistune                   2.0.4
mkl_fft                   1.3.11
mkl_random                1.2.8
mkl-service               2.4.0
nbclient                  0.8.0
nbconvert                 7.16.4
nbformat                  5.10.4
nest-asyncio              1.6.0
networkx                  3.3
notebook                  7.2.2
notebook_shim             0.2.3
numexpr                   2.10.1
numpy                     1.26.4
overrides                 7.4.0
packaging                 24.1
pandas                    2.2.2
pandocfilters             1.5.0
parso                     0.8.3
pillow                    11.0.0
pip                       24.2
platformdirs              3.10.0
ply                       3.11
prometheus_client         0.21.0
prompt-toolkit            3.0.43
psutil                    5.9.0
pure-eval                 0.2.2
pycparser                 2.21
Pygments                  2.15.1
PyMySQL                   1.0.2
pyparsing                 3.2.0
pyproj                    3.6.1
PyQt5                     5.15.10
PyQt5-sip                 12.13.0
PySocks                   1.7.1
python-dateutil           2.9.0.post0
python-json-logger        2.0.7
pytz                      2024.1
pywin32                   305.1
pywinpty                  2.0.10
PyYAML                    6.0.2
pyzmq                     25.1.2
referencing               0.30.2
requests                  2.32.3
rfc3339-validator         0.1.4
rfc3986-validator         0.1.1
rpds-py                   0.10.6
Rtree                     1.0.1
scikit-learn              1.5.2
scipy                     1.14.1
seaborn                   0.13.2
Send2Trash                1.8.2
setuptools                72.1.0
shapely                   2.0.5
sip                       6.7.12
six                       1.16.0
sniffio                   1.3.0
soupsieve                 2.5
SQLAlchemy                2.0.34
stack-data                0.2.0
terminado                 0.17.1
threadpoolctl             3.5.0
tinycss2                  1.2.1
tornado                   6.4.1
traitlets                 5.14.3
typing_extensions         4.11.0
tzdata                    2023.3
unicodedata2              15.1.0
urllib3                   2.2.3
wcwidth                   0.2.5
webencodings              0.5.1
websocket-client          1.8.0
wheel                     0.44.0
win-inet-pton             1.1.0
xyzservices               2022.9.0

**Create an Environment**
In Anaconda - click on create. Then name your environment e.g Python. Once you are satisfied - you can click on save. Then click on the the play button to open the environment.

**Memebers on this Team**
One - myself (Keryn Beth Rabe)
email address : keryn36@gamil.com












