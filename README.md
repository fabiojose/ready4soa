# ready4soa
Study Roadmap, laboratories, references, guides, tools and examples to get ready for Service Oriented Architecture

## SOA Maturity Level 1: Initial Services

### Roadmap

The roadmap is divided in three parts: one, two and three.

* One: Learn XML and related specifications

* Two: Introduction into *wstown* and understanding the "what" principle

  > wstown - Web Services Town - A lot of specifications, technologies, patterns and tools to work with Web Services.

  – Fábio J. Moraes

* Three: Implementing Web Services and understanding the "how" principle

#### Part One

XML and related specifications.

##### To Learn

1. XML
2. XSD
3. XPath
4. XQuery
5. XSLT

##### ![L](http://www.iconsdb.com/icons/download/black/test-tube-24.png) Labs

1. [XML][xml_labs] 
2. [XSD][xsd_labs]
3. [XPath][xpath_labs]
4. [XQuery][xquery_labs]
[xml_labs]: xml/org/wellformed
[xsd_labs]: xsd/org
[xpath_labs]: xpath
[xquery_labs]: xquery

#### Part Two

Introduction into *wstown* and understanding the "what" principle

##### To Learn

1. WSDL
2. SOAP
3. WS-Security

#### Part Three

Implementing Web Services and understanding the "how" principle

##### Labs

1. Java

#### To Study

1. Enterprise Service Bus - ESB

##### ESB Laboratories

## SOA Maturity Level 2: Architected Services 

## SOA Maturity Level 3: Business and Collaborative Services  

## SOA Maturity Level 4: Measured Business Services

## SOA Maturity Level 5: Optimized Business Services

# People

### A collection of roles at *soaland*

* * *

## Solution Architect

## Enterprise Architect

## ¿SOA Architect?

# Design Pattern

### A collectoin of design patterns at *soaland*

# Meanings

### A collection of meanings at *soaland*

* * * 

## SOA

Stands for [Service-Oriented Architecture] [soa]

> Service-Oriented Architecture (SOA) is an architectural style that supports service-orientation.

– opengroup.org

[soa]: http://www.opengroup.org/soa/source-book/soa/soa.htm

## ESB

Stands for [Enterprise Service Bus] [esb]

> An ESB is as standards-base integration platform that combines messaging, web services, data transformation, and intelligent routing to reliably connect and coordinate the interaction of significant numbers of diverse applications across extended enterprises with transactional integrity.

– David A. Chappell

[More][esb_more]

[esb]: https://books.google.com.br/books/about/Enterprise_Service_Bus.html?id=Uhue3faV2mwC
[esb_more]: http://www.ibm.com/developerworks/websphere/techjournal/1105_flurry/1105_flurry.html

## WS 

Stands for [Web Service] [ws]

> Web services provide a standard means of interoperating between different software applications, running on a variety of platforms and/or frameworks

[Learn] [ws_learn]
[ws]: http://www.w3.org/TR/ws-arch/
[ws_learn]: http://www.w3schools.com/webservices/

## WS-*

Stands for Web Service specifications

## WS-Gloss

Stands for [Web Services Glossary] [wsgloss]

> (...) a glossary of Web services terms defined and used in the Web Services Architecture (...) in order to refer to a common coherent framework.

[wsgloss]: http://www.w3.org/TR/ws-gloss/

## WS-I

Stands for [Web Services Interoperability Organization] [wsi]

> The Web Services Interoperability Organization (WS-I) is an open industry organization chartered to establish Best Practices for Web services interoperability, for selected groups of Web services standards, across platforms, operating systems and programming languages.

[Basic Profile 1.2][wsi_more1.2]

[Basic Profile 2.0][wsi_more2.0]

[wsi]: http://www.ws-i.org
[wsi_more1.2]: http://ws-i.org/Profiles/BasicProfile-1.2-2010-11-09.html
[wsi_more2.0]: http://ws-i.org/Profiles/BasicProfile-2.0-2010-11-09.html

## WS-BPEL

Stands for [Web Services Business Process Execution Language] [wsbpel]

> WS-BPEL provides a language for the specification of Executable and Abstract business processes. (...)  that should facilitate the expansion of automated process integration (...)

[More] [wsbpel_more]
[wsbpel]: http://docs.oasis-open.org/wsbpel/2.0/OS/wsbpel-v2.0-OS.html
[wsbpel_more]: http://xml.coverpages.org/bpel4ws.html

## WS-Addressing

Stands for [Web Services Addressing] [wsaddressing]

> WS-Addressing provides transport-neutral mechanisms to address Web services and messages.(...)

[More] [wsaddressing_more]
[wsaddressing]: http://www.w3.org/Submission/ws-addressing/
[wsaddressing_more]: http://xml.coverpages.org/ws-Addressing.html

## WS-Policy

Stands for [Web Services Policy] [wspolicy]

> (...) defines a base set of constructs that can be used and extended by other Web services specifications to describe a broad range of service requirements and capabilities.

[wspolicy]: http://www.w3.org/TR/ws-policy/

## WS-SecurityPolicy

## WS-PolicyAttachment

## WS-Security <a name="wssecurity_anchor"/>

Stands for [Web Services Security] [wssecurity]

> (...) standard set of SOAP [SOAP11, SOAP12] extensions that can be used when building secure Web services to implement message content integrity and confidentiality.

[More] [wssecurity_more]
[wssecurity]: https://www.oasis-open.org/committees/download.php/16790/wss-v1.1-spec-os-SOAPMessageSecurity.pdf
[wssecurity_more]: https://www.oasis-open.org/committees/wss

## WSS

[WS-Security] (#wssecurity_anchor)

## WS-Trust

Stands for [Web Services Trust] [wstrust]

> (...) defines extensions that build on [WS-Security] (#wssecurity_anchor) to provide a framework for requesting and issuing security tokens, and to broker trust relationships.

[wstrust]: http://docs.oasis-open.org/ws-sx/ws-trust/200512/ws-trust-1.3-os.html

## WS-Federation

Stands for [Web Services Federation Language] [wsfederation]

> (...) defines mechanisms to allow different security realms to federate, such that authorized access to resources managed in one realm can be provided to security principals whose identities and attributes are managed in other realms. (...)

[wsfederation]: http://docs.oasis-open.org/wsfed/federation/v1.2/os/ws-federation-1.2-spec-os.html

## WS-Transaction <a name="wstransaction_anchor"/>

Stands for [Web Services Transaction] [wstransaction]

> Defining protocols for coordinating the outcome of distributed application actions

[wstransaction]: https://www.oasis-open.org/committees/ws-tx/

## WS-TX

[WS-Transaction] (#wstransaction_anchor)

## WS-Coordination

Stands for [Web Services Coordination] [wscoordination]

> The WS-Coordination specification describes an extensible framework for providing protocols that coordinate the actions of distributed applications.(...)

[wscoordination]: http://docs.oasis-open.org/ws-tx/wstx-wscoor-1.2-spec.html

## WS-AtomicTransaction

Stands for [Web Services Atomic Transaction] [wsatomictransaction]

> The WS-AtomicTransaction specification provides the definition of the Atomic Transaction coordination type that is to be used with the extensible coordination framework described in WS-Coordination. This specification defines three specific agreement coordination protocols for the Atomic Transaction coordination type: completion, volatile two-phase commit, and durable two-phase commit.(...)

[wsatomictransaction]: http://docs.oasis-open.org/ws-tx/wstx-wsat-1.2-spec-os/wstx-wsat-1.2-spec-os.html

## WS-BusinessActivity

Stands for [Web Services Business Activity] [wsbusinessactivity]

> The WS-BusinessActivity specification provides the definition of two Business Activity coordination types: AtomicOutcome or MixedOutcome, that are to be used with the extensible coordination framework described in the WS-Coordination specification.(...)

[wsbusinessactivity]: http://docs.oasis-open.org/ws-tx/wstx-wsba-1.2-spec-os/wstx-wsba-1.2-spec-os.html

## WS-ReliableExchange <a name="wsreliableexchange_anchor"/>

Stands for [Web Services Reliable Exchange][wsreliableexchange]

[wsreliableexchange]:http://docs.oasis-open.org/ws-rx/

## WS-RX

[WS-ReliableExchange] (#wsreliableexchange_anchor)

## WS-ReliableMessaging

Stands for [Web Services Reliable Messaging][wsreliablemessaging]

[wsreliablemessaging]:http://docs.oasis-open.org/ws-rx/wsrm/v1.2/wsrm.html

## XML

Stands for [Extensible Markup Language] [xml]

> Extensible Markup Language (XML) is a simple, very flexible text format derived from SGML (ISO 8879).

[Learn] [xml_learn]

[More] [xml_more]
[xml]: http://www.w3.org/TR/REC-xml/
[xml_learn]: http://www.w3schools.com/xml/
[xml_more]: http://www.w3.org/standards/xml/core.html

## (XML) Well Formed <a name="xmlwellformed_anchor"/>

> An XML document with correct syntax is "Well Formed".

  – w3schools

[More][xmlwellformed_more]
[xmlwellformed_more]:http://www.w3schools.com/xml/xml_doctypes.asp

## (XML) Valid

> A "valid" XML document must be [well formed](#xmlwellformed_anchor). In addition it must conform to a document type definition.

  – w3schools

[More][xmlvalid_more]
[xmlvalid_more]:http://www.w3schools.com/xml/xml_doctypes.asp

## PCDATA

Stands for [Parsed Character Data][pcdata]

> (...)is a term used about text data that will be parsed by the XML parser. 

[pcdata]:http://www.w3schools.com/xml/xml_cdata.asp

## CDATA

Stands for [Character Data] [cdata]

> The term CDATA is used about text data that should not be parsed by the XML parser.

[Learn] [cdata_learn]

[cdata]: http://www.w3.org/TR/REC-xml/#sec-cdata-sect
[cdata_learn]: http://www.w3schools.com/xml/xml_cdata.asp

## XML Signature

Stands for [XML Signature Syntax and Processing] [xml_signature]

> (...) XML Signatures provide integrity, message authentication, and/or signer authentication services for data of any type, whether located within the XML that includes the signature or elsewhere.

[xml_signature]: http://www.w3.org/TR/xmldsig-core/

## XML Encryption

Stands for [XML Encryption Syntax and Processing] [xml_encryption]

> (...) a process for encrypting data and representing the result in XML. The data may be arbitrary data (including an XML document), an XML element, or XML element content. The result of encrypting data is an XML Encryption element which contains or references the cipher data.

[xml_encryption]: http://www.w3.org/TR/xmlenc-core/

## XSD

Stands for [XML Schema Definition Language] [xsd]

> (...) offers facilities for describing the structure and constraining the contents of XML documents (...)

[Learn] [xsd_learn]
[xsd]: http://www.w3.org/TR/xmlschema11-1/
[xsd_learn]: http://www.w3schools.com/schema/

## XPath

Stands for [XML Path Language] [xpath]

> XPath 2.0 is an expression language that allows the processing of values conforming to the data model (...) 
data model provides a tree representation of XML documents (...)

[Learn] [xpath_learn]
[xpath]: http://www.w3.org/TR/xpath20/
[xpath_learn]: http://www.w3schools.com/xpath/

## XQuery

Stands for [XML Query Language] [xquery]

> (...) uses the structure of XML intelligently can express queries across all these kinds of data (...) designed to be broadly applicable across many types of XML data sources.

[Learn] [xquery_learn]
[xquery]: http://www.w3.org/TR/xquery/
[xquery_learn]: http://www.w3schools.com/xquery/

## XSL <a name="xsl_anchor"/>

Stands for [Extensible Stylesheet Language] [xsl]

> An XSL stylesheet specifies the presentation of a class of XML documents by describing how an instance of the class is transformed into an XML document that uses the formatting vocabulary.

[xsl]: http://www.w3.org/TR/xsl/

## XSLT 

Stands for [XSL Transformations] [xslt]

> The term stylesheet reflects the fact that one of the important roles of XSLT is to add styling information to an XML source document, by transforming it into a document consisting of [XSL](#xsl_anchor) formatting objects (...), or into another presentation-oriented format such as HTML, XHTML, or SVG. However, XSLT is used for a wide range of transformation tasks, not exclusively for formatting and presentation applications. (...)

[Learn] [xslt_learn]
[xslt]: http://www.w3.org/TR/xslt20/
[xslt_learn]: http://www.w3schools.com/xsl/

## WSDL

Stands for [Web Services Description Language] [wsdl]

> WSDL is an XML format for describing network services as a set of endpoints operating on messages containing either document-oriented or procedure-oriented information.(...)

[Introduction] [wsdl_intro]

[Advanced] [wsdl_advanced]

[wsdl]: http://www.w3.org/TR/wsdl
[wsdl_intro]: http://www.w3schools.com/webservices/ws_wsdl_intro.asp
[wsdl_advanced]: http://www.ibm.com/developerworks/webservices/tutorials/ws-understand-web-services2/ws-understand-web-services2.html

## One-Way

[One-Way Operation] [oneway]

> One-Way operations have no output, just the input, which means no response.

[oneway]: http://www.w3.org/TR/wsdl#_one-way

## Request/Response <a name="requestresponse_anchor"/>

[Request-response Operation] [requestresponse]

> Request-response operations have input, output and faults sometimes.

[requestresponse]: http://www.w3.org/TR/wsdl#_request-response

## Request/Reply

[Request/Response] (#requestresponse_anchor)

## Request/Reaction

## SOAP

## SOAP 1.1 vs. SOAP 1.2

[More] [soap11x12]
[soap11x12]: http://www.w3.org/2003/06/soap11-soap12.html

## UDDI

## BPM

## BPMN

## BPEL

## BAM

## BRMS

## CEP

## EDA

## SEDA

## EAI

## EII

## B2B

## A2A

## B2C

## REST

## RESTful

## JSON

## HTTP

## HTTPS

## SSL

## XML Appliance

## Endpoint

## End-to-End

## Asynchronous transport

## Synchronous transport

## Acknowledgement

## Ack

## Reliable

## Non-repudiation

## VETRO

data-enrichment

http://www.oracle.com/technetwork/articles/jumpstart-for-osb-development-page--084129.html

## Choreography

http://stackoverflow.com/questions/4127241/orchestration-vs-choreography

## Orchestration

## Routing

validation, transformation

## Canonical Model

## Canonical Schema

## Canonical XML

http://www.w3.org/TR/xml-c14n

http://www.informit.com/articles/article.aspx?p=31961

## CDM

Stands for Canonical Data Model

http://erwin.com/community/expert-blogs/the-canonical-data-model/

## Governance

http://simplicable.com/new/10-soa-design-patterns-every-architect-should-know

http://refcardz.dzone.com/refcardz/soa-patterns

http://apprenda.com/platform/licensing/
