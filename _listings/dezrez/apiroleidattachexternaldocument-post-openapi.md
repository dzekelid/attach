---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Attaches an externally hosted document to a role
  version: 1.0.0
  description: Attaches an externally hosted document to a role.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/progression/lettings/uploadandattachtenantdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a tenant.
      description: Allows you to upload a document and attach it directly to a tenant..
      operationId: LettingsProgression_UploadAndAttachTenantDocumentBytenantInfoIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachtenantdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantInfoId
        description: The tenant Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Tenant
  /api/progression/lettings/uploadandattachlandlorddocument:
    post:
      summary: Allows you to upload a document and attach it directly to a tenant.
      description: Allows you to upload a document and attach it directly to a tenant..
      operationId: LettingsProgression_UploadAndAttachLandlordDocumentBylandlordInfoIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachlandlorddocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: landlordInfoId
        description: The tenant Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Tenant
  /api/progression/lettings/uploadandattachguarantorgroupdocument:
    post:
      summary: Allows you to upload a lettings document and attach it directly to
        a guarantor group.
      description: Allows you to upload a lettings document and attach it directly
        to a guarantor group..
      operationId: LettingsProgression_UploadAndAttachGurantorGroupDocumentByguarantorGroupIdBytenancyIdBydocumentDetai
      x-api-path-slug: apiprogressionlettingsuploadandattachguarantorgroupdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: guarantorGroupId
        description: The guarantor group Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenancyId
        description: The tenancy Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Lettings
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
      - Group
  /api/progression/lettings/uploadandattachguarantordocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: LettingsProgression_UploadAndAttachGuarantorDocumentByguarantorIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachguarantordocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: guarantorId
        description: The guarantor Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/progression/lettings/uploadandattachguarantorreferencedocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: LettingsProgression_UploadAndAttachGuarantorReferenceDocumentByguarantorIdByreferenceIdBydocumentDet
      x-api-path-slug: apiprogressionlettingsuploadandattachguarantorreferencedocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: guarantorId
        description: The guarantor Id
      - in: query
        name: referenceId
        description: The reference Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/progression/lettings/uploadandattachrighttorentdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a r ight
        to rent.
      description: Allows you to upload a document and attach it directly to a r ight
        to rent..
      operationId: LettingsProgression_UploadAndAttachRightToRentDocumentBytenantInfoIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachrighttorentdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantInfoId
        description: The tenant info Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - R
      - Ight
      - To
      - Rent
  /api/progression/lettings/uploadandattachtenantreferencedocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: LettingsProgression_UploadAndAttachTenantReferenceDocumentBytenantInfoIdByreferenceIdBytenantRoleIdB
      x-api-path-slug: apiprogressionlettingsuploadandattachtenantreferencedocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: referenceId
        description: The reference Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantInfoId
        description: The tenantInfoId Id
      - in: query
        name: tenantRoleId
        description: The reference Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/milestone/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a milestone.
      description: Allows you to upload a document and attach it directly to a milestone..
      operationId: Milestone_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apimilestoneiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Document save command
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The milestone Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Milestone
  /api/property/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a property.
      description: Allows you to upload a document and attach it directly to a property..
      operationId: Property_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apipropertyiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Details o
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The property Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Property
  /api/property/uploadandattachcertificatedocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: Property_UploadAndAttachCertificateDocumentBycertificateIdBydocumentDetailsContract
      x-api-path-slug: apipropertyuploadandattachcertificatedocument-post
      parameters:
      - in: query
        name: certificateId
        description: The Certificate Id
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/role/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a role.
      description: Allows you to upload a document and attach it directly to a role..
      operationId: Role_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apiroleiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Role
  /api/roomdescription/{id}/attachtorole:
    put:
      summary: Attach a RoomDescription to a PropertyMarketingRole
      description: Attach a roomdescription to a propertymarketingrole.
      operationId: RoomDescription_AttachToRoleByidByroleId
      x-api-path-slug: apiroomdescriptionidattachtorole-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Attach
      - RoomDescription
      - To
      - PropertyMarketingRole
  /api/sync/mailsync:
    post:
      summary: Syncronise Email with Rezi Events, attach documents etc
      description: Syncronise email with rezi events, attach documents etc.
      operationId: Sync_EmailBymailSyncDataContract
      x-api-path-slug: apisyncmailsync-post
      parameters:
      - in: body
        name: mailSyncDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Syncronise
      - Email
      - Rezi
      - Events
      - ""
      - Attach
      - Documents
      - Etc
  /api/branding/{id}/attachdocument:
    put:
      summary: Attaches a document to a brand.
      description: Attaches a document to a brand..
      operationId: Branding_AttachDocumentByidBydocumentId
      x-api-path-slug: apibrandingidattachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The documentId
      - in: path
        name: id
        description: The BrandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Document
      - To
      - Brand
  /api/branding/{id}/attachexternaldocument:
    put:
      summary: Attaches an external document to brand.
      description: Attaches an external document to brand..
      operationId: Branding_AttachExternalDocumentByidByexternalDocument
      x-api-path-slug: apibrandingidattachexternaldocument-put
      parameters:
      - in: body
        name: externalDocument
        description: Details of the external document
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The BrandId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - External
      - Document
      - To
      - Brand
  /api/group/{id}/attachdocument:
    put:
      summary: Attaches an existing document to a group
      description: Attaches an existing document to a group.
      operationId: Group_AttachDocumentByidBydocumentId
      x-api-path-slug: apigroupidattachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to attach
      - in: path
        name: id
        description: The id of the group to attach the document to
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Existing
      - Document
      - To
      - Group
  /api/group/{id}/attachexternaldocument:
    post:
      summary: Attaches the external document.
      description: Attaches the external document..
      operationId: Group_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apigroupidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: The document details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The identifier
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - External
      - Document
  /api/milestone/{id}/attachdocument:
    put:
      summary: Attaches an existing document to a milestone
      description: Attaches an existing document to a milestone.
      operationId: Milestone_AttachDocumentByidBydocumentId
      x-api-path-slug: apimilestoneidattachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to attach
      - in: path
        name: id
        description: The id of the milestone to attach the document to
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Existing
      - Document
      - To
      - Milestone
  /api/property/{id}/attachdocument:
    put:
      summary: Attaches an existing document to a property
      description: Attaches an existing document to a property.
      operationId: Property_AttachDocumentByidBydocumentId
      x-api-path-slug: apipropertyidattachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to attach
      - in: path
        name: id
        description: The id of the property to attach the document to
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Existing
      - Document
      - To
      - Property
  /api/property/{id}/attachexternaldocument:
    post:
      summary: Attaches an externally hosted document to a property
      description: Attaches an externally hosted document to a property.
      operationId: Property_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apipropertyidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: Details of the document to associate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The property Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Property
  /api/role/{id}/attachdocument:
    put:
      summary: Attaches an existing document to a role
      description: Attaches an existing document to a role.
      operationId: Role_AttachDocumentByidBydocumentId
      x-api-path-slug: apiroleidattachdocument-put
      parameters:
      - in: query
        name: documentId
        description: The id of the document to attach
      - in: path
        name: id
        description: The id of the role to attach the document to
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Existing
      - Document
      - To
      - Role
  /api/role/{id}/attachexternaldocument:
    post:
      summary: Attaches an externally hosted document to a role
      description: Attaches an externally hosted document to a role.
      operationId: Role_AttachExternalDocumentByidBydocumentDetails
      x-api-path-slug: apiroleidattachexternaldocument-post
      parameters:
      - in: body
        name: documentDetails
        description: Details of the document to associate
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Attaches
      - Externally
      - Hosted
      - Document
      - To
      - Role
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---