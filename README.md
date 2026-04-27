# rangle
Rangle Drupal project

proto_payload.@type="type.googleapis.com/google.cloud.audit.AuditLog"
protoPayload.methodName="google.cloud.apigee.v1.DeploymentService.DeployApiProxy"
protoPayload.response.environment="productsales-dv"
protoPayload.response.apiProxy="Catalog-Rules-Management-BS"

Check specific sharedflow deployment

proto_payload.@type="type.googleapis.com/google.cloud.audit.AuditLog"
protoPayload.methodName="google.cloud.apigee.v1.DeploymentService.DeploySharedFlow"
protoPayload.response.apiProxy="sf-Verify-Token-via-Keys"

check kvm

proto_payload.@type="type.googleapis.com/google.cloud.audit.AuditLog"
protoPayload.methodName="google.cloud.apigee.v1.KeyValueMapService.CreateEnvironmentKeyValueMap"
protoPayload.request.keyValueMap.name="external-product-discovery-autocomplete"
