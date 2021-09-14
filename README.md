# Using Transformers to Extract Names from Canadian Political Emails
In this project, we use Transformers to extract the names of people mentioned in emails received from the mailing lists of the four major Canadian political parties with a national presence: Conservative Party of Canada, Liberal Party of Canada, Green Party of Canada, and New Democratic Party. 

## Input-Output Example
### Input
John —<br /><br />
According to our records, your donations so far this year total: $0*
Our Party has a brand new leader who is working hard to defeat Justin Trudeau in 2019.
There has never been a better time to become a donor.
Will you join our special team of donors with a  $19 donation [https://donate.conservative.ca?mpi=[campaignid]&val=19] today?
Donate whatever you can, and become part of something amazing!
Donate $9 [https://donate.conservative.ca?mpi=[campaignid]&val=9]      Donate $19 [https://donate.conservative.ca?mpi=[campaignid]&val=19]      Donate $29 [https://donate.conservative.ca?mpi=[campaignid]&val=29]      Donate $39 [https://donate.conservative.ca?mpi=[campaignid]&val=39]      Donate $99 [https://donate.conservative.ca?mpi=[campaignid]&val=99]
if you have very recently donated, or donated under a different email address, we could have this wrong.
Authorized by the registered agent of the Conservative Party of Canada.
This email was sent to: connod@mikesmit.com
We believe email is an important way to stay in touch with Canadians. If you no longer wish to receive e-mail updates from us,  click here to unsubscribe http://conservativepartyofcanada.cmail20.com/t/t-u-ktjjidl-tlhjutlku-x/.<br /><br />
Conservative Party of Canada<br />
1720-130 Albert St.<br />
Ottawa, ON K1P 5G4
### Output
['John', 'Justin Trudeau']

## Visualization Example
"Justin Trudeau" - Mentions by Party in 2015
![JT_Mentions_2015](https://user-images.githubusercontent.com/56233883/133182335-2b50619f-14cf-4d26-a1fb-f741a9c1abf5.png)

## Dataset
https://dataverse.scholarsportal.info/dataset.xhtml;jsessionid=0438c715c98d146246c38fde7937?persistentId=doi%3A10.23685%2FGZQ8Z2&version=&q=&fileTypeGroupFacet=&fileAccess=
