#### 需要先把放在master节点的二进制文件拷贝到对应的node节点上
```
scp kubernetes/server/bin/kubelet k8s-node-01:/opt/kubernetes/bin/
scp kubernetes/server/bin/kubelet k8s-node-02:/opt/kubernetes/bin/
scp kubernetes/server/bin/kubelet k8s-node-03:/opt/kubernetes/bin/
```
```
scp kubernetes/server/bin/kube-proxy k8s-node-01:/opt/kubernetes/bin/
scp kubernetes/server/bin/kube-proxy k8s-node-02:/opt/kubernetes/bin/
scp kubernetes/server/bin/kube-proxy k8s-node-03:/opt/kubernetes/bin/
```
