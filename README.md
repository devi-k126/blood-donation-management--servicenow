# blood-donation-management--servicenow
Automated Blood Donation Management on ServiceNow | Flow Designer auto-matches donors by blood group &amp; city  | PDI: dev422711.service-now.com | 


Blood Donation Management - ServiceNow

PDI: dev422711.service-now.com | By devi-k126 | 

## What is this?
When a patient needs blood, system automatically finds donor in same city with same blood group.

## Live Proof
Donor: alax (Blood A, Thrissur)
Request: john (Needs Blood A, Thrissur)
Result: System auto-matched -> john -> alax

## Tables Used
1. Donors - List of donors
2. Blood Requests - Patient requests (john, james)
3. Donor Matches - Auto created matches

## How I Built
- Created Scoped App in ServiceNow Studio
- Created 3 Custom Tables
- Built Flow in Flow Designer
  Trigger: When Blood Request is created
  Action: Find donors + Create match

## Tech
ServiceNow, Flow Designer, Studio

## Author
devi-k126
