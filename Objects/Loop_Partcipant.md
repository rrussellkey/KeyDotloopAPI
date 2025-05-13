# KeyDotloopAPI
#Loop_Partcipant__c //object for the loop partcipant
Attributes
activateable: false
associateEntityType:
associateParentEntity:
compactLayoutable: true
createable: true
custom: true
customSetting: false
deepCloneable: false
defaultImplementation:
deletable: true
deprecatedAndHidden: false
feedEnabled: false
hasSubtypes: false
idEnabled: true
implementedBy:
implementsInterfaces:
isInterface: false
isSubtype: false
keyPrefix: a1s
label: Loop Participant
labelPlural: Loop Participants
layoutable: true
mergeable: false
mruEnabled: true
name: Loop_Participant__c
networkScopeFieldName:
queryable: true
replicateable: true
retrieveable: true
searchLayoutable: true
searchable: true
triggerable: true
undeletable: true
updateable: true
urlDetail: https://keyrealty.my.salesforce.com/{ID}
urlEdit: https://keyrealty.my.salesforce.com/{ID}/e
urlNew: https://keyrealty.my.salesforce.com/a1s/e
Child Relationships (73)
AIInsightValue.SobjectLookupValueId
cascadeDelete: true
childSObject: AIInsightValue
deprecatedAndHidden: false
field: SobjectLookupValueId
AIRecordInsight.TargetId
cascadeDelete: false
childSObject: AIRecordInsight
deprecatedAndHidden: false
field: TargetId
AgentWork.WorkItemId
cascadeDelete: true
childSObject: AgentWork
deprecatedAndHidden: false
field: WorkItemId
AgentWorkChangeEvent.WorkItemId
cascadeDelete: false
childSObject: AgentWorkChangeEvent
deprecatedAndHidden: false
field: WorkItemId
Agent_Commission_Plan__c_hd.ParentId
cascadeDelete: true
childSObject: Agent_Commission_Plan__c_hd
deprecatedAndHidden: false
field: ParentId
Agent_Sponsorship__c_hd.ParentId
cascadeDelete: true
childSObject: Agent_Sponsorship__c_hd
deprecatedAndHidden: false
field: ParentId
ApprovalSubmission.RelatedRecordId
cascadeDelete: false
childSObject: ApprovalSubmission
deprecatedAndHidden: false
field: RelatedRecordId
relationshipName: ApprovalSubmissions
ApprovalWorkItem.RelatedRecordId
cascadeDelete: false
childSObject: ApprovalWorkItem
deprecatedAndHidden: false
field: RelatedRecordId
relationshipName: ApprovalWorkItems
AttachedContentDocument.LinkedEntityId
cascadeDelete: true
childSObject: AttachedContentDocument
deprecatedAndHidden: false
field: LinkedEntityId
relationshipName: AttachedContentDocuments
AttachedContentNote.LinkedEntityId
cascadeDelete: true
childSObject: AttachedContentNote
deprecatedAndHidden: false
field: LinkedEntityId
relationshipName: AttachedContentNotes
Attachment.ParentId
cascadeDelete: true
childSObject: Attachment
deprecatedAndHidden: false
field: ParentId
relationshipName: Attachments
Client__c.Client__c
cascadeDelete: false
childSObject: Client__c
deprecatedAndHidden: false
field: Client__c
relationshipName: Client__r
CollaborationGroupRecord.RecordId
cascadeDelete: true
childSObject: CollaborationGroupRecord
deprecatedAndHidden: false
field: RecordId
relationshipName: RecordAssociatedGroups
CollaborationGroupRecordChangeEvent.RecordId
cascadeDelete: false
childSObject: CollaborationGroupRecordChangeEvent
deprecatedAndHidden: false
field: RecordId
CombinedAttachment.ParentId
cascadeDelete: true
childSObject: CombinedAttachment
deprecatedAndHidden: false
field: ParentId
relationshipName: CombinedAttachments
ContactRequest.WhatId
cascadeDelete: false
childSObject: ContactRequest
deprecatedAndHidden: false
field: WhatId
relationshipName: ContactRequests
ContentDistribution.RelatedRecordId
cascadeDelete: true
childSObject: ContentDistribution
deprecatedAndHidden: false
field: RelatedRecordId
ContentDocumentLink.LinkedEntityId
cascadeDelete: true
childSObject: ContentDocumentLink
deprecatedAndHidden: false
field: LinkedEntityId
relationshipName: ContentDocumentLinks
ContentDocumentLinkChangeEvent.LinkedEntityId
cascadeDelete: false
childSObject: ContentDocumentLinkChangeEvent
deprecatedAndHidden: false
field: LinkedEntityId
ContentVersion.FirstPublishLocationId
cascadeDelete: false
childSObject: ContentVersion
deprecatedAndHidden: false
field: FirstPublishLocationId
ContentVersionChangeEvent.FirstPublishLocationId
cascadeDelete: false
childSObject: ContentVersionChangeEvent
deprecatedAndHidden: false
field: FirstPublishLocationId
DuplicateRecordItem.RecordId
cascadeDelete: true
childSObject: DuplicateRecordItem
deprecatedAndHidden: false
field: RecordId
relationshipName: DuplicateRecordItems
EmailMessageChangeEvent.RelatedToId
cascadeDelete: false
childSObject: EmailMessageChangeEvent
deprecatedAndHidden: false
field: RelatedToId
EngagementTopic.TopicId
cascadeDelete: false
childSObject: EngagementTopic
deprecatedAndHidden: false
field: TopicId
relationshipName: EngagementInitiatedTopic
EngagementTopicChangeEvent.TopicId
cascadeDelete: false
childSObject: EngagementTopicChangeEvent
deprecatedAndHidden: false
field: TopicId
EntitySubscription.ParentId
cascadeDelete: true
childSObject: EntitySubscription
deprecatedAndHidden: false
field: ParentId
relationshipName: FeedSubscriptionsForEntity
EventChangeEvent.WhatId
cascadeDelete: false
childSObject: EventChangeEvent
deprecatedAndHidden: false
field: WhatId
EventRelation.RelationId
cascadeDelete: true
childSObject: EventRelation
deprecatedAndHidden: false
field: RelationId
relationshipName: EventRelations
EventRelationChangeEvent.RelationId
cascadeDelete: false
childSObject: EventRelationChangeEvent
deprecatedAndHidden: false
field: RelationId
FeedComment.ParentId
cascadeDelete: false
childSObject: FeedComment
deprecatedAndHidden: false
field: ParentId
FeedItem.ParentId
cascadeDelete: true
childSObject: FeedItem
deprecatedAndHidden: false
field: ParentId
FlowExecutionErrorEvent.ContextRecordId
cascadeDelete: false
childSObject: FlowExecutionErrorEvent
deprecatedAndHidden: false
field: ContextRecordId
FlowOrchestrationWorkItem.RelatedRecordId
cascadeDelete: false
childSObject: FlowOrchestrationWorkItem
deprecatedAndHidden: false
field: RelatedRecordId
relationshipName: FlowOrchestrationWorkItems
FlowRecordRelation.RelatedRecordId
cascadeDelete: false
childSObject: FlowRecordRelation
deprecatedAndHidden: false
field: RelatedRecordId
Loop_Participant__History.ParentId
cascadeDelete: true
childSObject: Loop_Participant__History
deprecatedAndHidden: false
field: ParentId
relationshipName: Histories
Loop_Participant__Share.ParentId
cascadeDelete: true
childSObject: Loop_Participant__Share
deprecatedAndHidden: false
field: ParentId
relationshipName: Shares
NetworkActivityAudit.ParentEntityId
cascadeDelete: false
childSObject: NetworkActivityAudit
deprecatedAndHidden: false
field: ParentEntityId
relationshipName: ParentEntities
NetworkFeedResponseMetric.ParentRecordId
cascadeDelete: false
childSObject: NetworkFeedResponseMetric
deprecatedAndHidden: false
field: ParentRecordId
NetworkUserHistoryRecent.RecordId
cascadeDelete: true
childSObject: NetworkUserHistoryRecent
deprecatedAndHidden: false
field: RecordId
relationshipName: NetworkUserHistoryRecentToRecord
Note.ParentId
cascadeDelete: true
childSObject: Note
deprecatedAndHidden: false
field: ParentId
relationshipName: Notes
NoteAndAttachment.ParentId
cascadeDelete: true
childSObject: NoteAndAttachment
deprecatedAndHidden: false
field: ParentId
relationshipName: NotesAndAttachments
ObjectRelatedUrl.ParentId
cascadeDelete: true
childSObject: ObjectRelatedUrl
deprecatedAndHidden: false
field: ParentId
ObjectRelatedUrlChangeEvent.ParentId
cascadeDelete: false
childSObject: ObjectRelatedUrlChangeEvent
deprecatedAndHidden: false
field: ParentId
Opportunity__hd.ParentId
cascadeDelete: true
childSObject: Opportunity__hd
deprecatedAndHidden: false
field: ParentId
PendingServiceRouting.WorkItemId
cascadeDelete: true
childSObject: PendingServiceRouting
deprecatedAndHidden: false
field: WorkItemId
PendingServiceRoutingChangeEvent.WorkItemId
cascadeDelete: false
childSObject: PendingServiceRoutingChangeEvent
deprecatedAndHidden: false
field: WorkItemId
PendingServiceRoutingInteractionInfo.PrimaryRecordId
cascadeDelete: true
childSObject: PendingServiceRoutingInteractionInfo
deprecatedAndHidden: false
field: PrimaryRecordId
PendingServiceRoutingInteractionInfo.TargetObjectId
cascadeDelete: true
childSObject: PendingServiceRoutingInteractionInfo
deprecatedAndHidden: false
field: TargetObjectId
ProcessException.AttachedToId
cascadeDelete: true
childSObject: ProcessException
deprecatedAndHidden: false
field: AttachedToId
relationshipName: ProcessExceptions
ProcessExceptionChangeEvent.AttachedToId
cascadeDelete: false
childSObject: ProcessExceptionChangeEvent
deprecatedAndHidden: false
field: AttachedToId
ProcessExceptionEvent.AttachedToId
cascadeDelete: false
childSObject: ProcessExceptionEvent
deprecatedAndHidden: false
field: AttachedToId
ProcessInstance.TargetObjectId
cascadeDelete: true
childSObject: ProcessInstance
deprecatedAndHidden: false
field: TargetObjectId
relationshipName: ProcessInstances
ProcessInstanceChangeEvent.TargetObjectId
cascadeDelete: false
childSObject: ProcessInstanceChangeEvent
deprecatedAndHidden: false
field: TargetObjectId
ProcessInstanceHistory.TargetObjectId
cascadeDelete: false
childSObject: ProcessInstanceHistory
deprecatedAndHidden: false
field: TargetObjectId
relationshipName: ProcessSteps
Real_Estate_Transaction__c.Client_Information__c
cascadeDelete: false
childSObject: Real_Estate_Transaction__c
deprecatedAndHidden: false
field: Client_Information__c
relationshipName: Real_Estate_Transactions__r
Real_Estate_Transaction__c_hd.ParentId
cascadeDelete: true
childSObject: Real_Estate_Transaction__c_hd
deprecatedAndHidden: false
field: ParentId
RecordAction.RecordId
cascadeDelete: true
childSObject: RecordAction
deprecatedAndHidden: false
field: RecordId
relationshipName: RecordActions
RecordActionHistory.ParentRecordId
cascadeDelete: false
childSObject: RecordActionHistory
deprecatedAndHidden: false
field: ParentRecordId
relationshipName: RecordActionHistories
RecordAlert.ParentId
cascadeDelete: false
childSObject: RecordAlert
deprecatedAndHidden: false
field: ParentId
relationshipName: RecordAlertParent
restrictedDelete: true
RecordAlert.WhatId
cascadeDelete: false
childSObject: RecordAlert
deprecatedAndHidden: false
field: WhatId
relationshipName: RecordAlertWhat
restrictedDelete: true
RecordAlertChangeEvent.ParentId
cascadeDelete: false
childSObject: RecordAlertChangeEvent
deprecatedAndHidden: false
field: ParentId
RecordAlertChangeEvent.WhatId
cascadeDelete: false
childSObject: RecordAlertChangeEvent
deprecatedAndHidden: false
field: WhatId
SurveySubject.SubjectId
cascadeDelete: false
childSObject: SurveySubject
deprecatedAndHidden: false
field: SubjectId
relationshipName: SurveySubjectEntities
SurveySubjectChangeEvent.SubjectId
cascadeDelete: false
childSObject: SurveySubjectChangeEvent
deprecatedAndHidden: false
field: SubjectId
TaskChangeEvent.WhatId
cascadeDelete: false
childSObject: TaskChangeEvent
deprecatedAndHidden: false
field: WhatId
TaskRelation.RelationId
cascadeDelete: true
childSObject: TaskRelation
deprecatedAndHidden: false
field: RelationId
relationshipName: TaskRelations
TaskRelationChangeEvent.RelationId
cascadeDelete: false
childSObject: TaskRelationChangeEvent
deprecatedAndHidden: false
field: RelationId
TopicAssignment.EntityId
cascadeDelete: true
childSObject: TopicAssignment
deprecatedAndHidden: false
field: EntityId
relationshipName: TopicAssignments
UserDefinedLabelAssignment.ItemId
cascadeDelete: true
childSObject: UserDefinedLabelAssignment
deprecatedAndHidden: false
field: ItemId
relationshipName: UserDefinedLabelAssignments
VideoCall.RelatedRecordId
cascadeDelete: false
childSObject: VideoCall
deprecatedAndHidden: false
field: RelatedRecordId
relationshipName: VideoRelatedRecords
VideoCallChangeEvent.RelatedRecordId
cascadeDelete: false
childSObject: VideoCallChangeEvent
deprecatedAndHidden: false
field: RelatedRecordId
VoiceCall.RelatedRecordId
cascadeDelete: false
childSObject: VoiceCall
deprecatedAndHidden: false
field: RelatedRecordId
relationshipName: RelatedRecords
VoiceCallChangeEvent.RelatedRecordId
cascadeDelete: false
childSObject: VoiceCallChangeEvent
deprecatedAndHidden: false
field: RelatedRecordId
Fields (27)
Cell_Phone__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Cell Phone
length: 255
name: Cell_Phone__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
City__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: City
length: 255
name: City__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Company_Name__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Company Name
length: 255
name: Company_Name__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Contact__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 18
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Contact
length: 18
name: Contact__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
referenceTo: Contact
relationshipName: Contact__r
restrictedPicklist: false
scale: 0
searchPrefilterable: true
soapType: tns:ID
sortable: true
type: reference
unique: false
updateable: true
Country__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Country
length: 255
name: Country__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
CreatedById
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 18
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Created By ID
length: 18
name: CreatedById
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
referenceTo: User
relationshipName: CreatedBy
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: tns:ID
sortable: true
type: reference
unique: false
updateable: false
CreatedDate
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 0
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: false
idLookup: false
label: Created Date
length: 0
name: CreatedDate
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:dateTime
sortable: true
type: datetime
unique: false
updateable: false
Email__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 240
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Email
length: 80
name: Email__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: email
unique: false
updateable: true
Full_Name__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Full Name
length: 255
name: Full_Name__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Id
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 18
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: true
label: Record ID
length: 18
name: Id
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: tns:ID
sortable: true
type: id
unique: false
updateable: false
IsDeleted
aggregatable: false
aiPredictionField: false
autoNumber: false
byteLength: 0
calculated: false
caseSensitive: false
createable: false
custom: false
defaultValue: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Deleted
length: 0
name: IsDeleted
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:boolean
sortable: true
type: boolean
unique: false
updateable: false
LastModifiedById
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 18
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Last Modified By ID
length: 18
name: LastModifiedById
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
referenceTo: User
relationshipName: LastModifiedBy
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: tns:ID
sortable: true
type: reference
unique: false
updateable: false
LastModifiedDate
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 0
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: false
idLookup: false
label: Last Modified Date
length: 0
name: LastModifiedDate
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:dateTime
sortable: true
type: datetime
unique: false
updateable: false
LastReferencedDate
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 0
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: false
idLookup: false
label: Last Referenced Date
length: 0
name: LastReferencedDate
nameField: false
namePointing: false
nillable: true
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:dateTime
sortable: true
type: datetime
unique: false
updateable: false
LastViewedDate
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 0
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: false
idLookup: false
label: Last Viewed Date
length: 0
name: LastViewedDate
nameField: false
namePointing: false
nillable: true
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:dateTime
sortable: true
type: datetime
unique: false
updateable: false
Loop_Participant_Id__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 240
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
externalId: true
filterable: true
groupable: true
idLookup: true
label: Loop Participant Id
length: 80
name: Loop_Participant_Id__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Loop__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 18
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Loop
length: 18
name: Loop__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
referenceTo: Loop__c
relationshipName: Loop__r
restrictedPicklist: false
scale: 0
searchPrefilterable: true
soapType: tns:ID
sortable: true
type: reference
unique: false
updateable: true
Name
aggregatable: true
aiPredictionField: false
autoNumber: true
byteLength: 240
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: false
idLookup: true
label: Loop Participant
length: 80
name: Name
nameField: true
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: false
OwnerId
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 18
calculated: false
caseSensitive: false
createable: true
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Owner ID
length: 18
name: OwnerId
nameField: false
namePointing: true
nillable: false
permissionable: false
polymorphicForeignKey: true
precision: 0
queryByDistance: false
relationshipName: Owner
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: tns:ID
sortable: true
type: reference
unique: false
updateable: true
Reference To (2)
Group
User
Phone__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Phone
length: 255
name: Phone__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Role__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Role
length: 255
name: Role__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: picklist
unique: false
updateable: true
Picklist Values (28)
ADMIN
active: true
defaultValue: false
label: ADMIN
value: ADMIN
APPRAISER
active: true
defaultValue: false
label: APPRAISER
value: APPRAISER
BUYER_ATTORNEY
active: true
defaultValue: false
label: BUYER_ATTORNEY
value: BUYER_ATTORNEY
BUYER
active: true
defaultValue: false
label: BUYER
value: BUYER
BUYING_AGENT
active: true
defaultValue: false
label: BUYING_AGENT
value: BUYING_AGENT
BUYING_BROKER
active: true
defaultValue: false
label: BUYING_BROKER
value: BUYING_BROKER
ESCROW_TITLE_REP
active: true
defaultValue: false
label: ESCROW_TITLE_REP
value: ESCROW_TITLE_REP
HOME_IMPROVEMENT_SPECIALIST
active: true
defaultValue: false
label: HOME_IMPROVEMENT_SPECIALIST
value: HOME_IMPROVEMENT_SPECIALIST
HOME_INSPECTOR
active: true
defaultValue: false
label: HOME_INSPECTOR
value: HOME_INSPECTOR
HOME_SECURITY_PROVIDER
active: true
defaultValue: false
label: HOME_SECURITY_PROVIDER
value: HOME_SECURITY_PROVIDER
HOME_WARRANTY_REP
active: true
defaultValue: false
label: HOME_WARRANTY_REP
value: HOME_WARRANTY_REP
INSPECTOR
active: true
defaultValue: false
label: INSPECTOR
value: INSPECTOR
INSURANCE_REP
active: true
defaultValue: false
label: INSURANCE_REP
value: INSURANCE_REP
LANDLORD
active: true
defaultValue: false
label: LANDLORD
value: LANDLORD
LISTING_AGENT
active: true
defaultValue: false
label: LISTING_AGENT
value: LISTING_AGENT
LISTING_BROKER
active: true
defaultValue: false
label: LISTING_BROKER
value: LISTING_BROKER
LOAN_OFFICER
active: true
defaultValue: false
label: LOAN_OFFICER
value: LOAN_OFFICER
LOAN_PROCESSOR
active: true
defaultValue: false
label: LOAN_PROCESSOR
value: LOAN_PROCESSOR
MANAGING_BROKER
active: true
defaultValue: false
label: MANAGING_BROKER
value: MANAGING_BROKER
MOVING_STORAGE
active: true
defaultValue: false
label: MOVING_STORAGE
value: MOVING_STORAGE
OTHER
active: true
defaultValue: false
label: OTHER
value: OTHER
PROPERTY_MANAGER
active: true
defaultValue: false
label: PROPERTY_MANAGER
value: PROPERTY_MANAGER
SELLER_ATTORNEY
active: true
defaultValue: false
label: SELLER_ATTORNEY
value: SELLER_ATTORNEY
SELLER
active: true
defaultValue: false
label: SELLER
value: SELLER
TENANT_AGENT
active: true
defaultValue: false
label: TENANT_AGENT
value: TENANT_AGENT
TENANT
active: true
defaultValue: false
label: TENANT
value: TENANT
TRANSACTION_COORDINATOR
active: true
defaultValue: false
label: TRANSACTION_COORDINATOR
value: TRANSACTION_COORDINATOR
UTILITIES_PROVIDER
active: true
defaultValue: false
label: UTILITIES_PROVIDER
value: UTILITIES_PROVIDER
State_Prov__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: State/Prov
length: 255
name: State_Prov__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Street_Name__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Street Name
length: 255
name: Street_Name__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Street_Number__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Street Number
length: 255
name: Street_Number__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
SystemModstamp
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 0
calculated: false
caseSensitive: false
createable: false
custom: false
defaultedOnCreate: true
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: false
idLookup: false
label: System Modstamp
length: 0
name: SystemModstamp
nameField: false
namePointing: false
nillable: false
permissionable: false
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:dateTime
sortable: true
type: datetime
unique: false
updateable: false
Unit_Number__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Unit Number
length: 255
name: Unit_Number__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Zip_Postal_Code__c
aggregatable: true
aiPredictionField: false
autoNumber: false
byteLength: 765
calculated: false
caseSensitive: false
createable: true
custom: true
defaultedOnCreate: false
deprecatedAndHidden: false
digits: 0
filterable: true
groupable: true
idLookup: false
label: Zip/Postal Code
length: 255
name: Zip_Postal_Code__c
nameField: false
namePointing: false
nillable: true
permissionable: true
polymorphicForeignKey: false
precision: 0
queryByDistance: false
restrictedPicklist: false
scale: 0
searchPrefilterable: false
soapType: xsd:string
sortable: true
type: string
unique: false
updateable: true
Record Type Infos (1)
Master
active: true
available: true
defaultRecordTypeMapping: true
developerName: Master
master: true
name: Master
recordTypeId: 012000000000000AAA
Supported Scopes (6)
everything
label: All loop participants
name: everything
mine
label: My loop participants
name: mine
queue_owned
label: Queue owned loop participants
name: queue_owned
scopingRule
label: Filter by scope
name: scopingRule
team
label: My team's loop participants
name: team
user_owned
label: User owned loop participants
name: user_owned
