import requests
import json

url = "https://idfcrefreshrelay.azurewebsites.net:443/api/swagger_refresh/triggers/manual/invoke?api-version=2020-05-01-preview&sp=%2Ftriggers%2Fmanual%2Frun&sv=1.0&sig=dmxbUHgTrh9rRpjtPeWkCT6Wwubda56bR22kLdZe8CE"

payload = json.dumps({
  "pds_name": "test"
})
headers = {
  'Content-Type': 'application/json'
}

response = requests.request("GET", url, headers=headers, data=payload)

print(response.text)



"idfc_idfc_Idfc_Azure"."idfc_idfc"."SIP_Target_Weekly_Historic"

"idfc_idfc_Idfc_Azure"."idfc_idfc"."GS_AUM_Acti_Target_Weekly_Historic"

"idfc_idfc_Idfc_Azure"."idfc_idfc"."All_KPIs_Actuals_Weekly_Delta"
