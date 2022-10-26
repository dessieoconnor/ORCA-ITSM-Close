# ORCA-ITSM-Close
# Welcome to the ORCA-ITSM-Close wiki!

This small app will close off Orca Alerts on the Orca platform from Incidents created by the Orca ServiceNow ITSM integration. Once the incident is set to "resolved" or "closed", the Orca alert will be closed on your Orca instance. This saves waiting for the following scheduled scan. A verification scan will be triggered immediately.

## Installation.

* Import this application from this repo into ServiceNow using the Servicenow System Application Studio.

* Set the Orca API Key in ServiceNow system property: x_138672_orca_itsm.orca_api

* Set the API Base URL in ServiceNow system property: x_138672_orca_itsm.orca_api_base_url
