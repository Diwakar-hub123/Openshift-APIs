# Openshift-APIs

All URIs are relative to *https://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
POST|/api/v1/namespaces | Creates Namespace
DELETE|/api/v1/namespaces/{{namespace}}| Delete_Namespace
GET|/api/v1/namespaces|Get_Namespace
GET|/api/v1/namespaces/{{namespace}}|Get_Namespace_by_name
POST|/apis/kubevirt.io/v1/namespaces/{{namespace}}/virtualmachines|Create Virtual_Machine
PUT|/apis/subresources.kubevirt.io/v1alpha3/namespaces/{{namespace}}/virtualmachines/testingvm/start|Start_Virtual_machine|
PUT|/apis/subresources.kubevirt.io/v1alpha3/namespaces/{{namespace}}/virtualmachines/testingvm/stop|Stop Virtual_Machine
PUT|/apis/subresources.kubevirt.io/v1alpha3/namespaces/default/virtualmachines/testingvm/restart|Restart_Virtual_Machine
DELETE|/apis/kubevirt.io/v1/namespaces/default/virtualmachines/<vmname>|Deleting_Virtual_Machine
POST|/apis/kubevirt.io/v1/namespaces/default/virtualmachines/<vmname>|Create_Persistent_volume
PUT|/api/v1/persistentvolumes/pv12|Update_persistent_volume
GET|/api/v1/persistentvolumes|Get_All_persistent_volumes
GET|/api/v1/persistentvolumes/pv12|Get_persistent_volumes By Name
DELETE|/api/v1/persistentvolumes/pv12|Delete_persistent_volume
PATCH|/api/v1/persistentvolumes/pv12|Edit_Labels
PATCH|/api/v1/persistentvolumes/pv12|Edit_Annotations
POST|/apis/storage.k8s.io/v1/storageclasses|Create _storage_Class
PUT|/apis/storage.k8s.io/v1/storageclasses/example|Update_Storage_class
PUT|/api/v1/persistentvolumes/pv12|Update_persistent_volume
GET|/apis/storage.k8s.io/v1/storageclasses|Get_storage_classes
GET|/apis/storage.k8s.io/v1/storageclasses/example|Get_storage_class_by_name
DELETE|DELETE/apis/storage.k8s.io/v1/storageclasses/example|Delete_Storage_class
PATCH|/apis/storage.k8s.io/v1/storageclasses/example|Edit_labels
PATCH|/apis/storage.k8s.io/v1/storageclasses/example|Edit_annotations
POST|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots|create_volume_snapshot
POST|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots/vs12|update_volume_snapshot
GET|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots|Get_All_VolumeSnapshot
GET|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots/vs12|Get_All_VolumeSnapshot _by_Name
DELETE|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots/vs12|Delete_volume_snapshot
PATCH|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots/vs12|Edit_labels
PATCH|/apis/snapshot.storage.k8s.io/v1/namespaces/{{namespace}}/volumesnapshots/vs12|Edit_annotations
POST|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses|create_volume_snapshot_class
PUT|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses/example|update_volume snapshot_class
DELETE|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses/example-snapclass|delete_volume_snapshot_class
GET|apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses|Get_All Volume Snapshot Classes
GET|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses/example-snapclass|Get_All Volume Snapshot Classes by Name
DELETE|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses/example-snapclass|Delete Volume Snapshot Class
PATCH|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses/example-snapclass|Edit_labels
PATCH|/apis/snapshot.storage.k8s.io/v1/volumesnapshotclasses/example-snapclass|Edit_annotation
POST|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents|create_volumesnapshotcontents
PUT|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents/example-snapcontent|update_volume_snapshot_content
GET|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents|Get All Volume Snapshot Contents
GET|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents/example-snapcontent|Get Volume Snapshot Contents By Name
DELETE|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents/example-snapcontent|Delete_volume_snapshot_content
PATCH|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents/example-snapcontent|Edit_labels
PATCH|/apis/snapshot.storage.k8s.io/v1/volumesnapshotcontents/example-snapcontent|Edit_annotation
POST|/api/v1/namespaces/{{namespace}}/persistentvolumeclaims|Create_persistent_volume_claim
PUT|/api/v1/namespaces/{{namespace}}/persistentvolumeclaims/example|Update Persistent Volume Claim
GET|/api/v1/namespaces/{{namespace}}/persistentvolumeclaims|Get All Persistent Volume Claims
GET|/api/v1/namespaces/{{namespace}}/persistentvolumeclaims/example|Get Persistent Volume Claim By Name
DELETE|/api/v1/namespaces/{{namespace}}/persistentvolumeclaims/sc12|Delete_persistent_colume_claim
POST|/api/v1/namespaces/default/services|create_services
PUT|/api/v1/namespaces/{{namespace}}/services/service12|Update_services
GET|/api/v1/namespaces/{{namespace}}/services|Get All services
GET|/api/v1/namespaces/{{namespace}}/services/service12|Get_Services_by_name
DELETE|/api/v1/namespaces/{{namespace}}/services/service12|Delete_Service
PATCH|/api/v1/namespaces/{{namespace}}/services/service12|Edit Labels
PATCH|/api/v1/namespaces/{{namespace}}/services/service12|Edit_Annotations
PATCH|/api/v1/namespaces/{{namespace}}/services/example|Edit_Pod_selector
POST|/apis/route.openshift.io/v1/namespaces/{{namespace}}/routes|create_route
GET|/apis/route.openshift.io/v1/namespaces/{{namespace}}/routes|Get All routes
GET|/apis/route.openshift.io/v1/namespaces/{{namespace}}/routes/route12|Get_routes_by_name
DELETE|/apis/route.openshift.io/v1/namespaces/{{namespace}}/routes|Delete_route
PATCH|/apis/route.openshift.io/v1/namespaces/{{namespace}}/routes/example|Edit Labels
PATCH|/apis/route.openshift.io/v1/namespaces/{{namespace}}/routes/example|Edit_Annotations
POST|/apis/networking.k8s.io/v1/namespaces/default/ingresses|create_ingress
PUT|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/ingresses/ingress12|Update Ingress
GET|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/ingresses|Get All Ingresses
GET|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/ingresses/ingress12|Get_Ingresses_by_name
DELETE|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/ingresses/ingress12|Delete_Ingress
PATCH|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/ingresses/ingress12|Edit Labels
PATCH|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/ingresses/ingress12|Edit_Annotations
POST|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies|create_Network_policies
PUT|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies/np-12|Update Network Policies
GET|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies|Get All Network Policies
GET|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies/np-12|Get Network Policies_by_name
DELETE|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies/np-12|Delete_Network Policies
PATCH|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies/np-12|Edit Labels
PATCH|/apis/networking.k8s.io/v1/namespaces/{{namespace}}/networkpolicies/np-12|Edit_Annotations
POST|/apis/k8s.cni.cncf.io/v1/namespaces/default/network-attachment-definitions|create_network_attachment_definitions
PUT|/apis/k8s.cni.cncf.io/v1/namespaces/{{namespace}}/network-attachment-definitions/nad-01|Update Network Atachment Definition
GET|/apis/k8s.cni.cncf.io/v1/namespaces/{{namespace}}/network-attachment-definitions|Get All Network Atachment Definition
GET|/apis/k8s.cni.cncf.io/v1/namespaces/{{namespace}}/network-attachment-definitions/nad-01|Get Network Atachment Definition_by_name
DELETE|/apis/k8s.cni.cncf.io/v1/namespaces/{{namespace}}/network-attachment-definitions/nad-01|Delete_Network Atachment Definition
PATCH|/apis/k8s.cni.cncf.io/v1/namespaces/{{namespace}}/network-attachment-definitions/nad-01|Edit Labels
PATCH|/apis/k8s.cni.cncf.io/v1/namespaces/{{namespace}}/network-attachment-definitions/nad-01|Edit_Annotations
POST|/api/v1/namespaces/{{namespace}}/pods|create_pod
POST|/apis/apps/v1/namespaces/default/deployments|create_deployment
POST|/apis/apps.openshift.io/v1/namespaces/default/deploymentconfigs|create_deploymwnt_configs
POST|/apis/apps/v1/namespaces/{{namespace}}/statefulsets|create_statefulsets
POST|/api/v1/namespaces/{{namespace}}/secrets|create_secrets
POST|/api/v1/namespaces/{{namespace}}/configmaps|create_configmaps
POST|/apis/batch/v1/namespaces/{{namespace}}/cronjobs|create_cronjobs
POST|/apis/batch/v1/namespaces/{{namespace}}/jobs|create_jobs|POST/apis/apps/v1/namespaces/{{namespace}}/daemonsets|create_daemon_sets
POST|/apis/apps/v1/namespaces/{{namespace}}/replicasets|create_replicaSets
POST|/api/v1/namespaces/{{namespace}}/replicationcontrollers|create_ReplicationControllers
POST|/apis/autoscaling/v2beta2/namespaces/{{namespace}}/horizontalpodautoscalers|create_HorizontalPodAutoScalers
