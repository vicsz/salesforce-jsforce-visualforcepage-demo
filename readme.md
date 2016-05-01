# salesforce-jsforce-visualforcepage-demo
Demo of integrating JsForce with Salesforce instance, and then deploying into Salesforce via VisualForce Pages.

## Development Steps:
1. Local Dev Setup
..1. Replace Username, Password, and SecurityToken with correct values
..2. Locally testing will require Cross Orgin calls -- Safari will allow this for local files, Chrome will not
..3. Ensure that your account has access to corresponding tables via SOQL
2. Edit local with different SOQL calls, and different charts 
3. Deploy to Salesforce VisualForce Pages.
..1. You will require additional access -- i.e. admin
..2. Goto -> User -> Setup -> App Setup -> Develop -> Visualforce Pages
..3. Add (or Edit) a new page 
..4. Cut and paste code into editor and strip LOCAL CODE, and uncomment SALESFORCE CODE
..5. Ensure other users have access to your page 

## Design Considerations:
1. Encapulate all code into one file to simplify SalesForce page/component management
 
