# text_resources

The text resources provided here are examples that can be used to create a Disclaimer Template on Cisco Secure Email Gateway.

From the Gateway UI:
1) Click Mail Policies > Text Resources
2) Click Add Text Resource...
3) Provide a Name for your Text Resource
4) For Type, select Disclaimer Template
5) Paste in the <html> provided example
6) Click Submit
7) In the right-hand corner, click Commit Changes and complete the Uncommited Changes on the UI

The text resource can then be added to any Message or Content Filter.

Lets use the example of "header_questionable":
<img src="https://github.com/Cisco-Email-Security/text_resources/blob/main/assets/text_resource_questionable.jpg?raw=true" alt="header_questionable Example" title="header_questionable Example">

Using the "Add Disclaimer Text" action in the Content Filter:
<img src="https://github.com/Cisco-Email-Security/text_resources/blob/main/assets/content_filter_questionable.jpg?raw=true" alt="Content Filter Example" title="Content Filter Example">
  
The end result would look like:
<img src="https://github.com/Cisco-Email-Security/text_resources/blob/main/assets/questionable_email.jpg?raw=true" alt="Email Example" title="Email Example">
