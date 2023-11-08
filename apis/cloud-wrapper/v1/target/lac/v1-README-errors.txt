
For both developers and tech writers, this reports on a range of
possible errors in the configuration of the source components on which
the API doc publication is based.  Inevitably, some issues logged here
are false positives.

## ERROR: 'category_stub' field in 'module.yaml' needs one of these values:

- cloud_security

- core_features

- enterprise_security

- media_delivery

- network_operator

- web_performance


## ERROR: In RAML, Response body with the following 'schema' does not specify 'example' JSON

- MultiCdnRandomSecret


## ERROR: Missing 'api_stub' field in the 'module.yaml' file; sample:

- tbd_change_this_api_stub


## ERROR: Missing 'category_stub' field in the 'module.yaml' file; sample:

- tbd_change_this_category_stub


## ERROR: Parameter needs 'example' value

- id


## ERROR: schema stub specified in RAML does not have a corresponding schema file. It may not link properly from the Request/Response tab:

- LocationDTO


## INFO: Descriptions within response definitions do not publish in documentation

- List of Cloud Wrapper configurations.

- HTTP 202 with the content location of the created Cloud Wrapper configuration.

- Cloud Wrapper configuration details.

- HTTP 202 with the content location of the updated Cloud Wrapper configuration.

- HTTP 202 if the request for Cloud Wrapper configurations activation is accepted.

- List of locations.

- Successful Response


## INFO: Your local 'learn.akamai.com' repo does not yet feature a publication file, likely because this is a new API with no doc published yet. Unable to generate a diff log showing differences with currently published API doc.

- Expect the publication file to be present at this path:
/Users/msierra/sandbox/learn.akamai.com/src/_enus/api/tbd_change_this_category_stub/tbd_change_this_api_stub/v1.md


## WARNING: If this POST operation creates a new resource, check if it responds with a 'Location' header, and specify if so

- TBD Post Configurations Resource

- TBD Post Activate Resource


## WARNING: JSON schema file needs a unique top-level 'id' value. Otherwise it will not properly link from Request/Response tabs.

- MultiCdnInfoDTO.json

- locationDTO.json

- CDNAuthKeyDTO.json


## WARNING: Problems in 'module.yaml' config file

- No DATA doc listings publish until the module.yaml file specifies a set of 'data' elements


## WARNING: RAML file specifies more than one top-level third URL
segment. It is better for each RAML file to define a single third
segment that appears after the major version number. In documentation,
that helps distinguish different categories of tightly coupled
functionality within the API service, and provides more flexibility
over the sequence in which they publish.

- cloud-wrapper.raml defines these top-level functional units:
    - /cloud-wrapper/v1/configurations
    - /cloud-wrapper/v1/locations
    - /cloud-wrapper/v1/multi-cdn


## WARNING: schema file linked from operation not included in module.yaml's 'data' section. (OK for internal-facing or non-object schemas.) To link request/response data to the object type, include the schema filename in a 'relatedSchemas' list alongside 'schemas' within the object type's specification.

- CWConfigurationListingDTO.json

- CWConfigurationCreateDTO.json

- CWConfigurationDTO.json

- CWConfigurationUpdateDTO.json

- CWActivationDTO.json

- MultiCdnInfoDTO.json

- CDNAuthKeyDTO.json

- MultiCdnRandomSecret.json

