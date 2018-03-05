WSDLDownloader
==============

Utility to download WSDL/XSD including transitive dependencies (eg. xs:include)


Usage:
------

<pre>
> clone project 

> cd project folder

> mvn package

</pre>

Download your wsdl files via the build jar:

`java -jar WSDLdownloader-1.0-SNAPSHOT.jar <wsdl_url>`

After see your wsdl and xsd files in `dist/` directory.