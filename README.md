# Sample UCCX Scripts

Sample UCCX Scripts is a collection of scripts for Cisco Contact Center you can use as templates for more advanced scripting requirements. See below for details on each sample script.


## Sample Rest API Script
This script checks the incoming calling number of the contact and makes a REST API call to Cisco UDS Service to check for any user with a mobile number that matches the incoming calling number, it then allows the user to update their CUCM pin. This script should be used for an example on how to use the "Make REST call" step in contact center express.



## Sample Advanced Prompts Script
This script shows an example of using container prompts and generated prompts, a call is placed into the CSQ and if the caller is queued, we use the reporting statistic step to determine how many calls are waiting. Based on number of calls waiting we generate a prompt that vocalizes the number using the create generated prompt step. Finally we use the "Create container prompt" step which concatenates the "You are caller number", "1", "in queue" prompts. 



## Installation

Simply download the .aef files and upload to contact center as appropriate, scripts come with sample audio prompts with computer generated text-to-speech voices, we recommend replacing these as soon as possible.





## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Thank you very much for any contributions to our shared pool of knowledge!

## License
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
GNU AGPL v3
