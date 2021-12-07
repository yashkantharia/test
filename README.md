import requests
import json

url = "https://vbv6kb6a31.execute-api.ap-south-1.amazonaws.com/default/pds_refresh"

payload = json.dumps({
  "pds_name": "test"
})
headers = {
  'x-api-key': 'EYamjoG8NW3YNTI6u1nPc3VbCL7fNLUn4cMO8Uq1',
  'Content-Type': 'application/json'
}

response = requests.request("GET", url, headers=headers, data=payload)

print(response.text)



"idfc_idfc_Idfc_Azure"."idfc_idfc"."SIP_Target_Weekly_Historic"
"idfc_idfc_Idfc_Azure"."idfc_idfc"."GS_AUM_Acti_Target_Weekly_Historic"
"idfc_idfc_Idfc_Azure"."idfc_idfc"."All_KPIs_Actuals_Weekly_Historic"
