# DOCUMENTS REQUIRED
For developing a perfect software following documents are mandatory in series:

URS ( User Requirements Specification): The URS point wise describes all the requirements of the software.
UI: Depending on the URS certain pages of the software are designed. This also includes error messages, pop up messages etc.
SRS (System Requirements Specification): The SRS point wise defines system requirements depending on the URS.
STC (System Test Cases): After the software is developed system testing is done with and recorded in STC
UAT (User Acceptance Testing): After all system test cases are successful user acceptance testing in conducted to check if the software covers all points as mentioned in the URS and is prepared as expected
DTL (Defect Track Log): All bugs/defects recorded during UAT/STC are mentioned in DTL so that they can be fixed
After all bugs are fixed second cycle of STC and UAT is conducted to check if everything is fine now and fulfill user expectation. And finally the software is ready to use.


# DATABASE


Collection: users
{
"UserType": ""
}

Collection: questions
{
	"_id":"343kj34344",
	"clientId": "flipkart2016",
	"subject": "Customers"							// Customers / Business / Client
	questions : [
		{
			"question": "How much rating would like to give for the delivery service?",
			"type": "RATING",
			"validation":"",
			"default":"3"
		},
		{
			"question": "Whould you like to order again?",
			"type": "bool",
			"validation":"",
			"default":"0"
		},
		{
			"question": "How many people you want to introduce?",
			"type": "number",
			"validation":"",
			"default":"0"
		}		

	]

}

Collection: answers
{
	"_id":"",
	"orderId": "3412234",

}








Minimum platform:
- RESTful
- Webserver included


			json/xml/soap
Backend  <-------->   Frontend (Browsers, Mobile Apps, Thirdparty Services)



input -> Process -> output



page/terms-and-condition


=================================================
Basic platform
=================================================
Basic Backend
	-  RESTful
	-  User Management (login, logout, register, enable, disable, forgot password, )
	-  Help System  (requesting help for a certain command)
	-  Multi Lingual Content
	-  HTTPS
	-  Routing  ( GET: /api/1.0.0/questions/343kj34344,  POST: /api/1.0.0/feedback)
	-  JWT
	-  Cross-origin resource sharing (CORS) 
	-  Versioning
	-  Configuration files
	-  Custom Log
	-  SMTP


=================================================
Basic Frontend
	-  Angular 2
	-  Bootstrap 4
	-  Static pages
	-  Theme system
	-  Routing    (home, contact, about, feedback, feedback/questions)
	-  Multi lingual content
	
