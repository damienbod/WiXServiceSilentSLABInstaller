MICROSOFT ENTERPRISE LIBRARY
SEMANTIC LOGGING APPLICATION BLOCK
c

Summary: The Semantic Logging Application Block provides a set of destinations (sinks) to persist application events published using a subclass of the EventSource class from the System.Diagnostics.Tracing namespace. Sinks include Windows Azure table storage, SQL Server databases, and rolling files with several formats and you can extend the block by creating your own custom formatters and sinks. For the those sinks that can store structured data, the block preserves the full structure of the event payload in order to facilitate analyzing or processing the logged data.

This out-of-process Windows Service logs events using the Event Tracing for Windows (ETW) infrastructure that is part of the Windows operating system.

In order to install the required dependencies for the service, run the install-packages.ps1 script.

The most up-to-date version of the release notes and known issues is available online:
http://aka.ms/el6release


Microsoft patterns & practices
http://microsoft.com/practices
