#  𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀 𝗮𝗻𝗱 𝗖𝗹𝗼𝘂𝗱 𝗡𝗮𝘁𝗶𝘃𝗲 𝗦𝗲𝗰𝘂𝗿𝗶𝘁𝘆 𝗔𝘀𝘀𝗼𝗰𝗶𝗮𝘁𝗲 (𝗞𝗖𝗦𝗔)

Purpose: A Certified Kubernetes and Cloud Native Security Associate is an associate-level certification designed for candidates interested in advancing to the professional level through a demonstrated understanding of foundational knowledge and skills of security technologies in the cloud native ecosystem.

<div align="center">
  <img src="https://www.cncf.io/wp-content/uploads/2024/03/kubernetes-kcsa-color.svg" width="400" alt="Kubernetes KCSA">
</div>


Certification can be found at the [LF Training Portal](https://training.linuxfoundation.org/certification/kubernetes-and-cloud-native-security-associate-kcsa/).

# Facts about KCSA

- Cost - 250.00 USD ( Discounts are available through Linux Foundation programs such as [LIFT Scholarship](https://www.linuxfoundation.org/about/lift-scholarships) + KubeCon Attendee Vouchers, and Black Friday Sales.)
- Certification Valid for 3 Years
- Includes 12 Month Exam Eligibility
- One Retake if you didn't PASS
- Multiple Choice Exam ( 60 Questions ) 
- Duration of Exam 90 minutes
- Passing Marks - 75 / Total Marks - 100 or 45/60 Questions should be correct
- During the exam, you can access Notepad/Calculator in the PSI Secure browser, but it is not required for this exam.
- Exams are scored automatically and barring any exceptions or technical difficulties, a score report will be emailed to you, within 24 hours of completing the exam. ( **Note:** I got mine in 2 mins after exam completion ) 


# Weightage of Different Topics

```mermaid
pie
    title Cloud Native Security Question Distribution
    "Overview of Cloud Native Security" : 14
    "Kubernetes Cluster Component Security" : 22
    "Kubernetes Security Fundamentals" : 22
    "Kubernetes Threat Model" : 16
    "Platform Security" : 16
    "Compliance and Security Frameworks" : 10
```
# Resources in Details 
Following a section-wise approach for the exam helps. You can start from the top and go to the bottom to cover the syllabus: 

Based on the search results, here are the links I found to complete your cloud native security sections:

## 🐳 **Cloud Native Security**

→ Container image scanning (eg: [trivy](https://github.com/aquasecurity/trivy) )

→[ Multi-stage Docker builds](https://docs.docker.com/build/building/multi-stage/)

→ Container registries

→ [gVisor](https://gvisor.dev/docs/)/[Firecracker](https://firecracker-microvm.github.io/) ( Mostly a CKS topic, but important)

→ Image signing ( [cosign](https://github.com/sigstore/cosign) )

→ [Image Digest vs Image tags](https://candrews.integralblue.com/2023/09/always-use-docker-image-digests/)

→ [Container breakout prevention](https://www.aquasec.com/cloud-native-academy/container-security/container-escape/)

→ [CWPP (Cloud Workload Protection Platform)](https://www.paloaltonetworks.com/cyberpedia/what-is-cwpp-cloud-workload-protection-platform)[9]

→ Multi-tenancy models(Soft vs Hard)

→ [Docker socket security](https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html)

→ [4 Cs of CN Security](https://www.wiz.io/academy/cloud-native-security) ( Cloud, Cluster, Container, Code ) 

## 📊 **Compliance and Security Frameworks**

→ [NIST Cybersecurity Framework](https://en.wikipedia.org/wiki/NIST_Cybersecurity_Framework)

→ [NIST SP 800-53 Rev.5](https://hyperproof.io/nist-800-53/)

→ [FedRAMP](https://www.hackerone.com/knowledge-center/what-federal-risk-and-authorization-management-program-fedramp)

→ [HIPAA](https://www.zscaler.com/zpedia/what-is-hipaa-security-rule)

→ [CIS Controls](https://en.wikipedia.org/wiki/The_CIS_Critical_Security_Controls_for_Effective_Cyber_Defense)

→ [CIS Kubernetes Benchmark (with kube-bench)](https://github.com/aquasecurity/kube-bench)

→ Microsoft SDL

→ NSA/CISA guidance

→ MITRE ATT&CK

→ OPA Gatekeeper

→ Kyverno

## ⚙️ **Kubernetes Cluster Component Security**

→ [kube-apiserver configuration](https://goteleport.com/blog/kubernetes-api-access-security/)( diff flags for diff controllers) 

→ [etcd encryption](https://kubernetes.io/docs/tasks/administer-cluster/encrypt-data/)

→ kubelet security

→ [kube-scheduler](https://www.cncf.io/blog/2021/08/20/how-to-secure-your-kubernetes-control-plane-and-node-components/)

→ [kube-proxy](https://www.kubernetes.dev/blog/2024/01/05/kube-proxy-non-privileged/)

→ [Static pods](https://kubernetes.io/docs/tasks/configure-pod-container/static-pod/)

→ Cluster health checks

→ Services (ClusterIP/NodePort/LoadBalancer)

→ Ingress

→ PersistentVolumes

→ StatefulSets

→ DaemonSets

→ HPA (Horizontal Pod Autoscaler)

→ kubeadm auth vs authorize controls

## 🔐 **Kubernetes Security Fundamentals**

→ [RBAC (Roles/RoleBindings + ClusterRole/ClusterRoleBindings)](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)

→ [Security contexts](https://www.jit.io/resources/devsecops/8-steps-to-configure-and-define-kubernetes-security-context)[

→ [Pod Security Standards/PSA](https://kubernetes.io/docs/concepts/security/pod-security-standards/)

→ [Pod Security Policies (Deprecated + comparison with PSA)](https://kubernetes.io/docs/concepts/security/pod-security-policy/)

→ [NetworkPolicies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)

→ [Secrets vs ConfigMaps](https://www.getambassador.io/blog/kubernetes-configurations-secrets-configmaps)

→ ServiceAccounts

→ Namespaces

→ Admission controllers

→ Audit policies

→ Image pull policies

→ Certificate management

## 🎯 **Kubernetes Threat Model**

→ [STRIDE framework](https://github.com/accuknox/k8sthreatmodeling)

→ [Threat modeling process](https://github.com/accuknox/k8sthreatmodeling) +  Threat modeling  b/w k8s components like API-Server and CNI

→ Privilege escalation

→ Information disclosure

→ Tampering/spoofing

→ Denial of service

→ Elevation of privileges

→ Trust boundaries

→ Attack persistence

## 🖥️ **Platform Security**

→ Linux tools (strace, netstat)

→ Certificate management (OpenSSL)

→ TLS/SSH

→ kubectl commands

→ Service Mesh ( [mTLS](https://istio.io/latest/docs/tasks/security/authentication/mtls-migration/) ) 

→ [AppArmor](https://kubernetes.io/docs/tutorials/security/apparmor/)

→[ PKI (Public Key Infrastructure)](https://en.wikipedia.org/wiki/Public_key_infrastructure)

→ File integrity

→ Package management

→ Network diagnostics

→ Monitoring tools ([Grafana](https://grafana.com/))



# Resources
- [KodeKloud KCSA](https://learn.kodekloud.com/user/courses/kubernetes-and-cloud-native-security-associate-kcsa)


# Study Tips
- Play with the tools like ArgoCD a bit to understand them clearly
- Focus on implementing and running a simple GitOps Application for Clarity
- Learn a bit of Architecture of the Tools as it helps you remember theory for longer

# Exam Tips ( PSI ) 
- Keep your desk tidy and run the System Check before the exams.
-  Carry an ID that has not expired.
- The exam can be started 30 minutes prior to your scheduled time, which is an excellent opportunity to complete the security checks and begin the exam early. It helps me to calm down and not rush during the exam :) 
- Delete the PSI Browser from your system to save time for your next exam. 
- Mark the questions `To Review` if you need more clarification and want to get back later. You have a dashboard with all the questions collectively listed, which helps you to get back to easily
  
# Certificate and a Credly Badge
Once you PASS it, you get the certificate mailed to you ⬇️


![image](https://github.com/user-attachments/assets/b5eb7e13-5b6e-482b-9694-f0408907b9a9)


With that, you can move on to the next certification from the catalogue and don't forget to Star ⭐ this repo. Feel free to contribute any resource, that was helpful to you! 

