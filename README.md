# BPEL_Calculator
To launch the orchestrator we need to have installed an Apache Tomcat server in our computer with the binary distributions
ODE and AXIS2 as webapps. 
The axis2 services folder must content the compiled services described by the wsdl files suma.wsdl and resta.wsdl included in the repo.
The ode processes folder must content the files included in this proyect.
That included files in the proyect are:
- CalculadoraBPEL.bpel: the process flow descriptor. It invokes the "suma" or the "resta" axis2 service selected by the variable seleccion.
- CalculadoraBPELArtifacts: it defines the types, elements and namespaces used in the bpel file.
- deploy.xml: it contains deploy info like the partner links endpoints.
- suma.wsdl/resta.wsdl: axis2 services definitions.
