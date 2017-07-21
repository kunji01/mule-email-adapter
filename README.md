# mule-email-adapter

--Share email common flows in Mule projects in adapter-handler way.<br/>

•	Catch exceptions globally in an application to send emails by simply adding a VM processor. <br/>
•	Send a notification to email in a flow dynamically giving subject and content. <br/>
•	Log integration activities to monitoring app and/or send emails. <br/>
•	Centrally manage Email addresses for individual application without interrupting operations. <br/><br/>

--This repository contains adapters to connect to handlers in repository <a href="https://github.com/kunji01/mule-email-adapter-handler">mule-email-adapter-handler</a>.
If you do not want to change or add adapters, just want email in your flows, you do not need this repository, clone or download repository 
<a href="https://github.com/kunji01/mule-email-adapter-handler">mule-email-adapter-handler</a>.<br/>

--Make it yours<br/>
You need to clone or download this project and project mule-email-adapter-handler both to your Anypoint studio to implement adapters and handlers, Change an adapter in this repository may require to change its respective handler in mule-email-adapter-handler too. If you do not make any changes, just distribute mule-email-adapter.jar in target folder to other projects. You do not need to deploy this application, you have to deploy mule-email-adapter-handler to the Mule runtime where you host the other projects. Read the repository <a href="https://github.com/kunji01/mule-email-adapter-handler">mule-email-adapter-handler</a> for detail.
