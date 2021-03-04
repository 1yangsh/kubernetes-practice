## kubernetes

> 컨테이너 운영을 자동화하기 위한 컨테이너 오케스트레이션 도구

### K8S Categories

- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/vagrant.md">vagrant</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/kubernetes_install.md">k8s install</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/kubernetes.md">k8s memo</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-replicaset.md">k8s replica set</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-deployment.md">k8s deployment</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-service.md">k8s service</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-namespace.md">k8s namespace</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-configmap.md">k8s configmap</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-secret.md">k8s secret</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/kubernetes/k8s-job.md">k8s job</a>
- <a href = "https://github.com/1yangsh/TIL/blob/master/pdf/4.Kubernetes.pdf">k8s pdf</a>

### k8s 주요 개념

| Resource or Object      | 용도                                                         |
| ----------------------- | ------------------------------------------------------------ |
| Node                    | 컨테이너가 배치되는 서비                                     |
| Namespace               | 쿠버네티스 클러스터 안의 가상 클러스터                       |
| Pod                     | 컨테이너의 집합 중 가장 작은 단위, 컨테이너의 실행 방법 정의 |
| Replica Set             | 같은 스펙을 갖는 파드를 여러 개 생성하고 관리하는 역할       |
| Deployment              | 레플리카 세트의 리비전을 관리                                |
| Service                 | 파드의 집합에 접근하기 위한 경로를 정의                      |
| Ingress                 | 서비스를 쿠버네티스 클러스터 외부로 노출                     |
| ConfigMap               | 설정 정보를 정의하고 파드에 전달                             |
| Persistent Volume       | 파드가 사용할 스토리지의 크리 및 종류를 정의                 |
| Persistent Volume Claim | 퍼시스턴트 볼륨을 동적으로 확보                              |

---

