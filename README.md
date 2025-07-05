# Thesis
This code was created as part of the master's thesis 'A digital knowledge infrastructure to provide information on scientific videos and podcasts' and includes the code used to analyze the survey.

Surveys can be contributed to via the following links: 
* [[DE] WissKomm Wiki](https://survey.uni-hannover.de/index.php/139333?lang=de)
* [[EN] SciCom Wiki](https://survey.uni-hannover.de/index.php/139333?lang=en)

For fellow researchers interested in the survey design, all surveys are inspectable in their entirety at once as well:
* [\[DE\] WissKomm Wiki](https://html-preview.github.io/?url=https://github.com/wittenborg/2025-scicom-ki-survey/blob/master/de/LimeSurvey%20-%20WissKomm%20Wiki.html)
* [\[EN\] SciCom Wiki](https://html-preview.github.io/?url=https://github.com/wittenborg/2025-scicom-ki-survey/blob/master/en/LimeSurvey%20-%20SciCom%20Wiki.html)

For the building blocks of the infrastructure see:
 -  [https://github.com/xEatos/dashboardduck](https://github.com/xEatos/dashboardduck) (Web-Page)
 -  [https://github.com/xEatos/searchsnail](https://github.com/xEatos/searchsnail) (Media Search Microservice)
 -  [https://github.com/xEatos/integrationindri](https://github.com/xEatos/integrationindri) (Integration & Import Microservice)

If you would like to cite this work:
```
@article{stehr_digitale_2025,
	title = {Eine digitale {Wissensinfrastruktur} zur {Bereitstellung} von {Informationen} über wissenschaftliche {Videos} und {Podcasts}},
	url = {https://repo.uni-hannover.de/handle/123456789/19141},
	doi = {10.15488/18996},
	language = {ger},
	urldate = {2025-04-29},
	author = {Stehr, Niklas},
	month = apr,
	year = {2025},
	note = {Publisher: Hannover : Gottfried Wilhelm Leibniz Universität},
}
```

## Setup

Install the dependencies in a virtual env:

```
python -m venv .venv

.venv/Scripts/activate

pip install -r ./requirements.txt

```
