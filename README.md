*Trigger - Integration with Oracle DB*
=============


This PL/SQL script will create a package containing the procedures required to send an event to Dollar Universe.
http://github.com/Automic-Community/Trigger---Integration-with-Oracle-DB

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Trigger_with_OracleDB.zip
								
								*Trigger-Integration_with_Oracle_DB.pdf
								
						


Documenation and Instructions
---

<p><span><strong class="bbc">Description</strong></span><br /><span><span><span>This PL/SQL script will create a package containing the procedures required to send an event to Dollar Universe. This includes the call to the login API, the logout API and the sending of the request.<br />Attached with this document, you will also find an example of oracle database trigger using the procedures of this package.</span></span></span><br /><br /><span><strong class="bbc">Prerequisites</strong></span><br /><span><span><span>This package can be installed via an Oracle DB client. No other external packages are required.<br />In Oracle 11g, an ACL (Access control List) is needed to allow the http tools to interact with an external host.<br />The following statements will create a new ACL with user JOHN as principal and access to host in domain "orsypgroup.com". </span></span></span><span><span><span>For more information, visit: </span></span></span><a class="bbc_url" title="External link" href="http://www.oracle-base.com/articles/11g/fine-grained-access-to-network-services-11gr1.php" rel="nofollow external">http://www.oracle-ba...vices-11gr1.php</a></p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
