
For tech writers, this reports on a range of possible editorial errors
and indicators of significant subject matter. Inevitably, some issues
logged here are false positives.  Ignore any issues that appear within
sample data or in-line monospaced literals.

## COPY-EDIT: Avoid any references to doc items that are 'above' or 'below'
here

https://collaborate.akamai.com/confluence/display/TCSG/A#A-above,below

- This above-the-fold initial introduction

- above-the-fold content.

- at based on the intro section above, the

- above the _API summary_ table in th

- le. No headings should appear above the

- along with the link above. If not, describe the example

- the screen shot that appears below this text: _define

- e This and Any Other Headings Below That Don't Apply

- d a typical error JSON object below. If the API's error

- If not, describe the example below. Also,

- sample table below. Make sure for any link, ther


## COPY-EDIT: Avoid parenthetical clauses

https://collaborate.akamai.com/confluence/display/TCSG/Punctuation#Punctuation-Parentheses

- (`###`) throughout. (Any nested fourth-level headin

- want to modify. (Best practice is not to allow

- "name": "Asia (Japan)",

- "name": "Asia (Singapore and Japan)",

- file. Use third-level headings (`###`)

- throughout. (Any nested fourth-level headin


## COPY-EDIT: Check for unnecessary and/or useless alternators

https://collaborate.akamai.com/confluence/display/TCSG/Punctuation#Punctuation-Slashes

- ormat this as a simple, short, topic/comment list


## COPY-EDIT: Consider 'this' or 'these' rather than 'the following'

https://collaborate.akamai.com/confluence/display/TBD

- already set up.  It includes the following mandatory set of

- e this section. Retain any of the following set of


## COPY-EDIT: Consider a contraction may be more conversational, except when
it includes the main verb of a clause

https://collaborate.akamai.com/confluence/display/TCSG/C#C-contractions

- An Etag or `If-Match` header does not match, indicating the content

- ant to modify. (Best practice is not to allow this PATCH-like

- his section is supplementary. It is _not_ a substitute for

- client context over how close it is to the limit. See the

- elow. Make sure for any link, there is a corresponding

- typically occurs when the URL you are calling responds to GET reque

- ed](#getstarted) to make sure you have permission to access all the


## COPY-EDIT: Don't hyphenate 'multi-' by default unless following word starts
with 'i'

https://collaborate.akamai.com/confluence/display/TCSG/M#M-multi-(prefix)

- e>/cloud-wrapper/<wbr>v1/<wbr>multi-cdn/<wbr>providers</code> |

- e>/cloud-wrapper/<wbr>v1/<wbr>multi-cdn/<wbr>auth-keys{?contractId,<w

- e>/cloud-wrapper/<wbr>v1/<wbr>multi-cdn/<wbr>random-secret</code> |

- e>/cloud-wrapper/<wbr>v1/<wbr>multi-cdn/<wbr>providers</code></span>

- e>/cloud-wrapper/<wbr>v1/<wbr>multi-cdn/<wbr>auth-keys?contractId=A-B

- e>/cloud-wrapper/<wbr>v1/<wbr>multi-cdn/<wbr>random-secret</code></sp


## COPY-EDIT: Use the '&mdash;' entity with no surrounding whitespace rather
than dash characters to set off any dash clauses, but otherwise
avoid them and use commas instead

https://collaborate.akamai.com/confluence/display/TCSG/Punctuation#Punctuation-Dashestalk-40148

- "comments": "testConfiguration - Update


## DOMAIN: Possibly significant subject matter that may need discussion

- The 'Content-Location' header may signify API support for asynchronous responses.


## FORMAT: Scalar JSON member may appear after array or object.
(Run 'json-format -t' on the sample JSON file)

https://pulsar.akamai.com/user-documentation/guides/apidoc-3-data/#1-basic-json-syntax

- },         "provisionStatus": "ACTIVE",

- },     "activate": true,

- },     "provisionStatus": "IN_PROGRESS",

- },     "multiCDNEnabled": true,

- ],         "lastUpdatedBy": "hgildong",

- ],         "lastUpdatedBy": "jperez",

- ],         "provisionStatus": "ACTIVE",

- ],         "enableSoftAlerts": true

- ],     "lastUpdatedBy": "mrossi",

- ],         "enableSoftAlerts": true,


## INFO: Optional fields in 'module.yaml' file no longer affect published output.

- File a DOCHUB ticket to modify the API's published 'status'.

- File a DOCHUB ticket to modify the API's 'description' (summary blurb).


## KEYWORD: Avoid referring to 'endpoints' if referring to an API's callable
'operations'.

https://pulsar.akamai.com/user-documentation/guides/apidoc-1-introduction/#checklist-review-api-terminology

- endpoint. See the


## KEYWORD: Avoid referring to 'resources' if referring to an API's callable
'operations'. Otherwise OK in error doc when referring more
abstractly to situations like 'resource not found'.

https://pulsar.akamai.com/user-documentation/guides/apidoc-1-introduction/#checklist-review-api-terminology

- or most APIs, the top of the [Resources](#resources) section

- Summarize the various resources you interact with and how the

- detailed in the [Resources](#resources) section, doc needs a complet

- [Resources](#resources) section. Likewise, every dat

- ### Resource limiting

- orts both, title it _Rate and resource limiting_.)  See the

- irements/api-editorial-guide/#resource-limiting)

- ## Resources

- | [TBD Get Configurations Resource](#getconfigurationsresource)

- | [TBD Post Configurations Resource](#postconfigurationsresource)

- | [TBD Post Activate Resource](#postactivateresource) | POS

- | [TBD Get Locations Resource](#getlocationsresource) | GET

- | [TBD Get Providers Resource](#getprovidersresource) | GET

- | [TBD Get Auth-keys Resource](#getauthkeysresource) | GET

- | [TBD Get Random-secret Resource](#getrandomsecretresource) |

- ### TBD Get Configurations Resource [getconfigurationsresource]

- ### TBD Post Configurations Resource [postconfigurationsresource]

- ### TBD Post Activate Resource [postactivateresource]

- ### TBD Get Locations Resource [getlocationsresource]

- ### TBD Get Providers Resource [getprovidersresource]

- ### TBD Get Auth-keys Resource [getauthkeysresource]

- ### TBD Get Random-secret Resource [getrandomsecretresource]

- /httpstatuses.com/201) | TBD: Resource successfully created. |

- com/301) | TBD: The requested resource has permanently moved to the

- com/302) | TBD: The requested resource is temporarily available at t

- com/303) | TBD: The requested resource is available at the link prov

- No permission to access this resource. This most likely reflects a

- /httpstatuses.com/404) | TBD: Resource not found. This typically occ

- urs when a resource keyed by a URL path parameter

- with the current state of the resource. See [Concurrency control](#c

- ses.com/410) | TBD: Requested resource is no longer available. |

- ses.com/423) | TBD: Requested resource is locked. See [Concurrency c


## KEYWORD: Avoid sample data that refers to 'test' items, as it suggests a
QA suite.  Samples should refer to recognizable use cases.



- "notes": "test",


## KEYWORD: Make sure 'field' doesn't refer to the API's URL 'parameter' or
a data 'member.'

https://pulsar.akamai.com/user-documentation/guides/apidoc-1-introduction/#checklist-review-api-terminology

- rameter needs a `description` field. |


## KEYWORD: Make sure 'parameters' refers to path parameters or query
parameters that appear in the API's request URLs. Don't use the
term to refer to anything else within the API, such as data
members.  Otherwise clarify if it refers to something else
outside the API.

https://pulsar.akamai.com/user-documentation/guides/apidoc-1-introduction/#checklist-review-api-terminology

- operation, parameter, header, and _steps_ doc in t

- <div markdown="1" class="parameters">

- | Parameter | Type | Sample | Description

- | URL path parameters ||||

- | `TBD_needs_example` | TBD: parameter needs a `description` field.

- | Required query parameters ||||

- a, or an invalid set of query parameters or values. |

- resource keyed by a URL path parameter no longer exists, or if the r


## KEYWORD: Make sure initial instance is 'Akamai Control Center'; also link
the term to the control.akamai.com portal if appropriate, e.g.
when describing a procedure

https://collaborate.akamai.com/confluence/display/TCSG/A#A-AkamaiControlCentertalk-72353

- vice as it appears within the Control Center interface,


## KEYWORD: Make sure to refer to a URL, rather than a URI, when the address
is intended to be accessible over a network, such as a web page
or an API endpoint. The term URI is a superset that includes
addresses simply used to uniquely identify something rather than
to navigate to it. For example, API error type URIs such as this
are typically non-navigable:
"/sandbox-api/error-types/duplicate-property"
Note that both URLs and URIs may represent "path" expressions
that aren't "fully qualified" with a scheme such as "https" or
a hostname.

https://collaborate.akamai.com/confluence/pages/viewpage.action?spaceKey=TCSG&title=Utalk-45567

- ems may feature a link to the URL to GET each item. Any

- | URL path parameters ||||

- if problem-specific URLs included in the response obje

- rs when a resource keyed by a URL path parameter no longer exis

- ts, or if the request URL is garbled in some other way.

- his typically occurs when the URL you are calling responds to G


## KEYWORD: No 'the' before 'Control Center' unless the phrase modifies
another noun

https://collaborate.akamai.com/confluence/display/TCSG/A#A-AkamaiControlCentertalk-72353

- service as it appears within the Control Center interface,


## LANGUAGE: 'Retrieve' means to regain possession after losing something,
rather perilous and likely not the intended meaning. Try 'get'.

https://collaborate.akamai.com/confluence/display/TBD

- ovides separate operations to retrieve data


## LANGUAGE: Avoid the vague term 'provision'; prefer more tangible action
verbs such as 'create', 'deploy', or 'activate'

https://collaborate.akamai.com/confluence/pages/viewpage.action?spaceKey=TCSG&title=P#P-provision

- "provisionStatus": "ACTIVE",

- "provisionStatus": "IN_PROGRESS",


## LANGUAGE: Make sure 'user' refers to end users, not the same people as our
customers who deploy content for them

https://collaborate.akamai.com/confluence/display/TCSG/U#U-user

- xt](https://pulsar.akamai.com/user-documentation/requirements/ap

- d the set of conceptual nouns users need to interact

- affect how the user interacts with the API. These

- es](https://pulsar.akamai.com/user-documentation/requirements/ap

- limits the number of objects users can create or

- success. Users may get warnings about issues

- users can save rule tree objects in

- r operations whose data input users

- "user@nomail-akamai.com"

- identity of the Control Panel user corresponding to the API clie


## LANGUAGE: Minimize passive voice constructions

https://collaborate.akamai.com/confluence/display/TCSG/P#P-passivevoice

- title: "Still To Be Named API v1"

- be fully documented in the [Data](#data) section.

- the API. These _API features_ are unrelated to the functionality the API

- igurations in saved state can be activated using this API.

- which the existing keys is to be fetched. |

- exists, or if the request URL is garbled in some other way. |

- match, indicating the content has been modified since you initially accessed

- 23) | TBD: Requested resource is locked. See [Concurrency control](#c


## LANGUAGE: Use 'for example' or 'such as' rather than 'e.g.'

https://collaborate.akamai.com/confluence/display/TCSG/E#E-e.g.

- e.g., that a 204 response indicate


## LANGUAGE: You must minimize imperative constructions, because it is required

https://collaborate.akamai.com/confluence/display/TCSG/M#M-must

- | Required query parameters ||||

- data but failing to specify a required `Content-Length` header to de


## SPELLING: Check code blocks

- 000Z 01T09 05T14 26T18 26T23 2HGIWNW 31T23 6b496b67783966695a674867

- akamai arl jperez CDN1 CDNConfig CDNEnabled cdns CDNSettings

- Centurylink cgupta config Config Config1 Config1ARL1 Config2

- Config2ARL1 Config3 Config3ARL1 Configuration1 Configuration2

- Configuration3 cpcode dn00x fms Fmxbx8Blic1601271015453 jp key1 key2

- Level3 Level3Auth nomail odpmtest1 odpmtest11 origin846 pcm PMtest1

- priyanka sgjp shnaraya sro VOD


## SPELLING: Check main text

- Akamai akamaiapis akzz api APIs auth Auth BC123 cdn CDN Cdn CDNAuth

- CDNProviders CWActivation CWConfiguration dn002 DTO Etag hostname

- hostnames html https json JSON lk luna md navbar permalink RAML

- reqsyntax schemas TBD tbd toc v1 wbr xml XXXXXXXXXXXXXXXX


## TBD: Remaining items



- TBD:

- TBD: For all content in the __OVE

- TBD: This section assumes that ba

- he access level to __TBD__.  (TBD: On the page linked in the pr

- TBD: For most APIs, the top of th

- TBD: In addition to the _steps_ t

- TBD: Remove this section. Retain

- TBD: Whether JSON data responses

- TBD: Whether the API limits the r

- TBD: If the API limits the number

- TBD: If more than one client migh

- TBD: If you GET an object with se

- TBD: Whether a success response o

- TBD: Whether the API provides sep

- TBD: Whether the API allows you t

- TBD: Whether an API operation may

- TBD: For content that appears at

- | [TBD Get Configurations Resource](

- | [TBD Post Configurations Resource]

- | [TBD Get Id of Cloud Wrapper confi

- | [TBD Put Id of Cloud Wrapper confi

- | [TBD Post Activate Resource](#post

- | [TBD Get Locations Resource](#getl

- | [TBD Get Providers Resource](#getp

- | [TBD Get Auth-keys Resource](#geta

- | [TBD Get Random-secret Resource](#

- ### TBD Get Configurations Resource [

- ### TBD Post Configurations Resource

- ### TBD Get Id of Cloud Wrapper confi

- teger | `TBD_needs_example` | TBD: parameter needs a `descripti

- ### TBD Put Id of Cloud Wrapper confi

- ### TBD Post Activate Resource [posta

- ### TBD Get Locations Resource [getlo

- ### TBD Get Providers Resource [getpr

- ### TBD Get Auth-keys Resource [getau

- ### TBD Get Random-secret Resource [g

- "TBD": "Need JSON 'example' along

- TBD: For content in the __ERRORS_

- TBD: Embed a typical error JSON o

- "tbd": "insert sample response obj

- TBD: "This section lists the full

- tps://httpstatuses.com/200) | TBD: The operation succeeded. |

- tps://httpstatuses.com/201) | TBD: Resource successfully create

- tps://httpstatuses.com/202) | TBD: Request accepted, but not ye

- tps://httpstatuses.com/204) | TBD: Successfully processed reque

- tps://httpstatuses.com/207) | TBD: A batch of operations produc

- tps://httpstatuses.com/300) | TBD: Response offers a choice of

- tps://httpstatuses.com/301) | TBD: The requested resource has p

- tps://httpstatuses.com/302) | TBD: The requested resource is te

- tps://httpstatuses.com/303) | TBD: The requested resource is av

- tps://httpstatuses.com/400) | TBD: Bad Request. This typically

- tps://httpstatuses.com/401) | TBD: API authentication failure.

- tps://httpstatuses.com/403) | TBD: No permission to access this

- tps://httpstatuses.com/404) | TBD: Resource not found. This typ

- tps://httpstatuses.com/405) | TBD: Method not supported. This t

- tps://httpstatuses.com/408) | TBD: Request timeout. This typica

- tps://httpstatuses.com/409) | TBD: Something in the request dat

- tps://httpstatuses.com/410) | TBD: Requested resource is no lon

- tps://httpstatuses.com/411) | TBD: Missing `Content-Length`. Th

- tps://httpstatuses.com/412) | TBD: An Etag or `If-Match` header

- tps://httpstatuses.com/413) | TBD: Request body exceeds maximum

- tps://httpstatuses.com/415) | TBD: Unsupported media type. This

- tps://httpstatuses.com/423) | TBD: Requested resource is locked

- tps://httpstatuses.com/429) | TBD: Too many requests. See [Rate

- tps://httpstatuses.com/500) | TBD: Internal server error. |

- tps://httpstatuses.com/501) | TBD: Functionality not supported.

- tps://httpstatuses.com/502) | TBD: Platform timeout error. |

- tps://httpstatuses.com/503) | TBD: Too many requests. Service i

- tps://httpstatuses.com/507) | TBD: Insufficient storage for siz

