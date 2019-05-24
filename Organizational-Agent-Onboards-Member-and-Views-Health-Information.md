Organizational Agent Onboards Member and Views Health Information
=================================================================



**_Endpoint_**

From the Organizational Agent's account, https://app.sharemy.health/org/dashboard  then click "Create Account"



**_Test Objective_**

A Member’s account is setup, access is granted to the organization, and Member connects HIXNY data source for self/org viewing.

**_Preconditions_**

* An Organization is setup in VMI and the SMH app
* An Org Agent is logged into the ShareMyHealth application
* Personal health information must exist for the member in HIXNY

**_Steps_**

* An Organizational Agent verifies the new Member’s identity.
* An Organization clicks “Create Account” from the Agent dashboard.
* An organization supplies first name, last name, birthdate, username and mobile phone number (optional) for the member in the form.
* Member completes setup by agreeing to terms of service, setting password, agreeing to share with the organization, and connectinging to the HIXNY data source. This can be completed by QR code, URL or private window. Test all 3 options: URL, QR code and private window.

**_Test Data_**

See table below for member data

**_Expected Results_**

* Member has an IAL of 2 set in the identity provider
* Member acceptance of TOS is recorded in the DB
* Organization Agent can view personal health information of Member
* Member can view personal health information of Member

**_Actual Results_**


