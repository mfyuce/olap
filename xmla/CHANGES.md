CHANGES
=======

0.4
----
* keyword ``kerberos`` is gone. kerberos auth need is detected automatically
* BeginSession and EndSession provide XMLA Sessionsupport
* changes to work with icCube XMLA provider

0.3
----
* changed keyword ``doKerberos`` in XMLProvider.connect to ``kerberos``
* added ``sslverify`` keyword to XMLProvider.connect defaulting to ``True``.
  This will be handed to requests get method, so you can point it to your certificate bundle file.


0.2
----
* removed dependencies on specific versions in setup.py