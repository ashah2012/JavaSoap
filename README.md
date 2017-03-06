# JavaSoap
Learning notes and resources for JAX-WS.

## Web Service Jargons
WSDL - like Interface in java. Contract to know about the web service, the method name, arguments 
and return types. 

UDDI - We can query UDDI to know about a web service, once the service is up, it gets registered here. This is the place you query and look for the WSDL.

SOAP - Encode and Decode message over the network. It's a protocol.

SEI - Service Endpoint Interface - access an interface to ws endpoint. Translates a ws call to a soap message in XML format.

## Writing a SOAP client
Need a URL to the wsdl file.
`wsimport -keep -s src url`

Add the generated source files to src folder and in corresponding package.
