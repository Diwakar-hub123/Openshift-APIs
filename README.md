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


# **Create Namespace**

Create Namespace.

### Example 
```
{
  "metadata": 
    {
    "name": "test123", 
    "labels": 
        {
        "app": "frontend"
        }
    }
}
```
### Mandatory fields
```
apiVersion : v1
kind : String 
metadata :
    name : String 
    labels: key-value pair
```
### Documentation Link
"https://docs.openshift.com/container-platform/4.12/rest_api/metadata_apis/namespace-v1.html#namespace-v1"

# **Create_Persistent_volume**

Create_Persistent_volume.

### Example 
```
{
    "apiVersion": "v1",
    "kind": "PersistentVolume",
    "metadata": {
        "name": "pv12"
    },
    "spec": {
        "capacity": {
            "storage": "5Gi"
        },
        "accessModes": [
            "ReadWriteOnce"
        ],
        "persistentVolumeReclaimPolicy": "Retain",
        "storageClassName": "slow",
        "nfs": {
            "path": "/tmp",
            "server": "172.17.0.2"
        }
    }
}
```
# **Create_Storage_Class**

Create Storage Class.

### Example 
```
{
    "metadata": {
        "name": "example",
        "annotations": {
            "description": "example"
        }
    },
    "provisioner": "kubernetes.io/no-provisioner",
    "parameters": {
        "test": "test"
    },
    "volumeBindingMode": "WaitForFirstConsumer"
}
```
# **Create_Volume_Snapshot**

Create Volume Snapshot.

### Example 
```
{
    "apiVersion": "snapshot.storage.k8s.io/v1",
    "kind": "VolumeSnapshot",
    "metadata": {
        "name": "vs12",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "volumeSnapshotClassName": "vs12class",
        "source": {
            "persistentVolumeClaimName": "pv-12"
        }
    }
}
```
# **Create VolumeSnapshotClass**

Create VolumeSnapshotClass.

### Example 
```
{
    "apiVersion": "snapshot.storage.k8s.io/v1",
    "kind": "VolumeSnapshotClass",
    "metadata": {
        "name": "test-snapclass"
    },
    "driver": "hostpath.csi.k8s.io",
    "deletionPolicy": "Delete"
}
```
# **Create VolumeSnapshotContent**

Create VolumeSnapshotContent.

### Example 
```
{
    "apiVersion": "snapshot.storage.k8s.io/v1",
    "kind": "VolumeSnapshotContent",
    "metadata": {
        "name": "test-snap"
    },
    "spec": {
        "deletionPolicy": "Delete",
        "driver": "hostpath.csi.k8s.io",
        "source": {
            "snapshotHandle": "7bdd0de3-aaeb-11e8-9aae-0242ac110002"
        },
        "volumeSnapshotClassName": "example-snapclass",
        "volumeSnapshotRef": {
            "name": "example-snap",
            "namespace": "default"
        }
    }
}
```
# **Create PersistentVolumeClaim**

Create PersistentVolumeClaim.

### Example 
```
{
    "apiVersion": "v1",
    "kind": "PersistentVolumeClaim",
    "metadata": {
        "name": "example",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "accessModes": [
            "ReadWriteOnce"
        ],
        "volumeMode": "Filesystem",
        "resources": {
            "requests": {
                "storage": "1Gi"
            }
        },
        "selector": {
            "matchLabels": {
                "name": "example"
            }
        },
        "storageClassName": "localblock-sc"
    }
}
```
# **Create Pod**

Create Pod.

### Example 
```
{
    "apiVersion": "v1",
    "kind": "Pod",
    "metadata": {
        "name": "test0221",
        "labels": {
            "app": "httpd"
        },
        "namespace": "default"
    },
    "spec": {
        "containers": [
            {
                "name": "httpd",
                "image": "image-registry.openshift-image-registry.svc:5000/openshift/httpd:latest",
                "ports": [
                    {
                        "containerPort": 8080
                    }
                ]
            }
        ]
    }
}
```
# **Create Deployment**

Create Deployment.

### Example 
```
    {
        "apiVersion": "apps/v1",
        "kind": "Deployment",
        "metadata": {
            "namespace": "default",
            "name": "deploy1234",
            "annotations": {}
        },
        "spec": {
            "selector": {
                "matchLabels": {
                    "app": "name"
                }
            },
            "replicas": 3,
            "template": {
                "metadata": {
                    "labels": {
                        "app": "name"
                    }
                },
                "spec": {
                    "containers": [
                        {
                            "name": "container",
                            "image": "image-registry.openshift-image-registry.svc:5000/openshift/httpd:latest",
                            "ports": [
                                {
                                    "containerPort": 8080,
                                    "protocol": "TCP"
                                }
                            ],
                            "env": []
                        }
                    ],
                    "imagePullSecrets": []
                }
            },
            "paused": false
        }
    }
```
# **Create DeploymentConfig**

Create DeploymentConfig.

### Example 
```
{
    "apiVersion": "apps.openshift.io/v1",
    "kind": "DeploymentConfig",
    "metadata": {
        "namespace": "default",
        "name": "mydeploy12"
    },
    "spec": {
        "selector": {
            "app": "mydeploy1"
        },
        "template": {
            "metadata": {
                "labels": {
                    "app": "mydeploy1"
                }
            },
            "spec": {
                "containers": [
                    {
                        "name": "container",
                        "image": "image-registry.openshift-image-registry.svc:5000/openshift/httpd:latest",
                        "ports": [
                            {
                                "containerPort": 8080,
                                "protocol": "TCP"
                            }
                        ],
                        "env": [
                            {
                                "name": "test",
                                "value": "test"
                            }
                        ]
                    }
                ],
                "imagePullSecrets": []
            }
        },
        "strategy": {
            "type": "Rolling",
            "rollingParams": {
                "timeoutSeconds": 600,
                "updatePeriodSeconds": 1,
                "intervalSeconds": 1,
                "pre": {
                    "failurePolicy": "Abort",
                    "execNewPod": {
                        "containerName": "container",
                        "command": [
                            "hostname"
                        ]
                    }
                },
                "maxSurge": "25%",
                "maxUnavailable": "25%"
            }
        },
        "paused": false
    }
}
```
# **Create StatefulSet**

Create StatefulSet.

### Example 
```
{
    "apiVersion": "apps/v1",
    "kind": "StatefulSet",
    "metadata": {
        "name": "test-ss1",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "serviceName": "nginx",
        "replicas": 3,
        "selector": {
            "matchLabels": {
                "app": "nginx"
            }
        },
        "template": {
            "metadata": {
                "labels": {
                    "app": "nginx"
                }
            },
            "spec": {
                "terminationGracePeriodSeconds": 10,
                "containers": [
                    {
                        "name": "nginx",
                        "image": "gcr.io/google_containers/nginx-slim:0.8",
                        "ports": [
                            {
                                "containerPort": 80,
                                "name": "web"
                            }
                        ],
                        "volumeMounts": [
                            {
                                "name": "www",
                                "mountPath": "/usr/share/nginx/html"
                            }
                        ]
                    }
                ]
            }
        },
        "volumeClaimTemplates": [
            {
                "metadata": {
                    "name": "www"
                },
                "spec": {
                    "accessModes": [
                        "ReadWriteOnce"
                    ],
                    "storageClassName": "my-storage-class",
                    "resources": {
                        "requests": {
                            "storage": "1Gi"
                        }
                    }
                }
            }
        ]
    }
}
```
# **Create Secret**

Create Secret.

### Example 
```
{
    "metadata": {
        "namespace": "{{namespace}}",
        "name": "aws-secret1"
    },
    "apiVersion": "v1",
    "data": {
        "apikey": "dGhpcyBpcyB0ZXN0IHBhc3N3b3Jk"
    },
    "kind": "Secret",
    "type": "Opaque"
}
```
# **Create ConfigMap**

Create ConfigMap.

### Example 
```
{
    "apiVersion": "v1",
    "kind": "ConfigMap",
    "metadata": {
        "name": "mymap-123",
        "namespace": "{{namespace}}"
    },
    "data": {
        "secret": "hello i am good"
    },
    "binaryData": {
        "test": "ello"
    },
    "immutable": false
}
```
# **Create CronJob**

Create CronJob.

### Example 
```
{
    "apiVersion": "batch/v1",
    "kind": "CronJob",
    "metadata": {
        "name": "cron02",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "schedule": "@daily",
        "jobTemplate": {
            "spec": {
                "template": {
                    "spec": {
                        "containers": [
                            {
                                "name": "hello",
                                "image": "busybox",
                                "args": [
                                    "/bin/sh",
                                    "-c",
                                    "date; echo Hello from the Kubernetes cluster"
                                ]
                            }
                        ],
                        "restartPolicy": "OnFailure"
                    }
                }
            }
        }
    }
}
```
# **Create Job**

Create Job.

### Example 
```
{
    "apiVersion": "batch/v1",
    "kind": "Job",
    "metadata": {
        "name": "job02",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "selector": {},
        "template": {
            "metadata": {
                "name": "pi"
            },
            "spec": {
                "containers": [
                    {
                        "name": "pi",
                        "image": "perl",
                        "command": [
                            "perl",
                            "-Mbignum=bpi",
                            "-wle",
                            "print bpi(2000)"
                        ]
                    }
                ],
                "restartPolicy": "Never"
            }
        }
    }
}
```
# **Create DaemonSet**

Create DaemonSet.

### Example 
```
{
    "apiVersion": "apps/v1",
    "kind": "DaemonSet",
    "metadata": {
        "name": "daemon123",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "selector": {
            "matchLabels": {
                "app": "httpd"
            }
        },
        "template": {
            "metadata": {
                "labels": {
                    "app": "httpd"
                }
            },
            "spec": {
                "containers": [
                    {
                        "name": "httpd",
                        "image": "image-registry.openshift-image-registry.svc:5000/openshift/httpd:latest",
                        "ports": [
                            {
                                "containerPort": 8080
                            }
                        ]
                    }
                ]
            }
        }
    }
}
```
# **Create ReplicaSet**

Create ReplicaSet.

### Example 
```
{
    "apiVersion": "apps/v1",
    "kind": "ReplicaSet",
    "metadata": {
        "name": "replica12",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "selector": {
            "matchLabels": {
                "app": "httpd"
            }
        },
        "template": {
            "metadata": {
                "labels": {
                    "app": "httpd"
                }
            },
            "spec": {
                "containers": [
                    {
                        "name": "httpd",
                        "image": "image-registry.openshift-image-registry.svc:5000/openshift/httpd:latest",
                        "ports": [
                            {
                                "containerPort": 8080
                            }
                        ]
                    }
                ]
            }
        }
    }
}
```
# **Create ReplicationController**

Create ReplicationController.

### Example 
```
{
    "apiVersion": "v1",
    "kind": "ReplicationController",
    "metadata": {
        "name": "replica12",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "replicas": 2,
        "selector": {
            "app": "httpd"
        },
        "template": {
            "metadata": {
                "name": "httpd",
                "labels": {
                    "app": "httpd"
                }
            },
            "spec": {
                "containers": [
                    {
                        "name": "httpd",
                        "image": "image-registry.openshift-image-registry.svc:5000/openshift/httpd:latest",
                        "ports": [
                            {
                                "containerPort": 8080
                            }
                        ]
                    }
                ]
            }
        }
    }
}
```
# **Create HorizontalPodAutoscaler**

Create HorizontalPodAutoscaler.

### Example 
```
{
    "apiVersion": "autoscaling/v2beta2",
    "kind": "HorizontalPodAutoscaler",
    "metadata": {
        "name": "hpa123",
        "namespace": "{{namespace}}"
    },
    "spec": {
        "scaleTargetRef": {
            "apiVersion": "apps/v1",
            "kind": "Deployment",
            "name": "example"
        },
        "minReplicas": 1,
        "maxReplicas": 3,
        "metrics": [
            {
                "type": "Resource",
                "resource": {
                    "name": "cpu",
                    "target": {
                        "averageUtilization": 50,
                        "type": "Utilization"
                    }
                }
            }
        ]
    }
}
```
# **Create Service**

Create Service.

### Example 
```
{
    "apiVersion": "v1",
    "kind": "Service",
    "metadata": {
        "name": "service12",
        "namespace": "default"
    },
    "spec": {
        "selector": {
            "app": "MyApp"
        },
        "ports": [
            {
                "protocol": "TCP",
                "port": 80,
                "targetPort": 9376
            }
        ]
    }
}
```
# **Create Ingress**

Create Ingress.

### Example 
```
{
    "apiVersion": "networking.k8s.io/v1",
    "kind": "Ingress",
    "metadata": {
        "name": "ingress12",
        "namespace": "default"
    },
    "spec": {
        "rules": [
            {
                "http": {
                    "paths": [
                        {
                            "path": "/testpath",
                            "pathType": "Prefix",
                            "backend": {
                                "service": {
                                    "name": "test",
                                    "port": {
                                        "number": 80
                                    }
                                }
                            }
                        }
                    ]
                }
            }
        ]
    }
}
```
# **Create NetworkPolicy**

Create NetworkPolicy.

### Example 
```
{
    "kind": "NetworkPolicy",
    "apiVersion": "networking.k8s.io/v1",
    "metadata": {
        "name": "np-123",
        "namespace": "default"
    },
    "spec": {
        "podSelector": {}
    }
}
```
# **Create NetworkAttachmentDefinition**

Create NetworkAttachmentDefinition.

### Example 
```
{
    "apiVersion": "k8s.cni.cncf.io/v1",
    "kind": "NetworkAttachmentDefinition",
    "metadata": {
        "name": "nad123",
        "namespace": "default",
        "annotations": {
            "k8s.v1.cni.cncf.io/resourceName": "bridge.network.kubevirt.io/test",
            "description": "nad12"
        }
    },
    "spec": {
        "config": "{\"name\":\"nad12\",\"type\":\"cnv-bridge\",\"cniVersion\":\"0.3.1\",\"bridge\":\"test\",\"macspoofchk\":true,\"ipam\":{}}"
    }
}
```
# **Create Route**

Create Route.

### Example 
```
{
    "kind": "Route",
    "apiVersion": "route.openshift.io/v1",
    "metadata": {
        "name": "route12",
        "namespace": "default",
        "labels": {}
    },
    "spec": {
        "to": {
            "kind": "Service",
            "name": "route12"
        },
        "tls": {},
        "port": {
            "targetPort": 9376
        }
    }
}
```
