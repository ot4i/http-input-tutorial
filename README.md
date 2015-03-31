# http-input-tutorial
Tutorial to show how to use HTTPInput and HTTPReply nodes to provide an rpc-style service over raw HTTP.
Note that for an rpc-style SOAP-based service, an Integration Service should be used instead based on a WSDL interface definition.
For resource-oriented HTTP requests in a REST style, a REST API is preferred based on a Swagger interface definition.
However there are existing applications which require integration but do not use an interface which can be modelled using WSDL or Swagger, and this tutorial gives an example of how to do this lower-level integration.
