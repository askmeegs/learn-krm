

# 🔁 Learn KRM! 

KRM = the Kubernetes Resource Model 


## ☸️ What is KRM?

*   [Concepts - What is Kubernetes?](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/) - kubernetes.io 
*   [Concepts - Kubernetes Components](https://kubernetes.io/docs/concepts/overview/components/) - kubernetes.io
*   [Concepts - Understanding Kubernetes Objects](https://kubernetes.io/docs/concepts/overview/working-with-objects/kubernetes-objects/) - kubernetes.io 
*   [Concepts - Configuration Best Practices](https://kubernetes.io/docs/concepts/configuration/overview/) - kubernetes.io 


## 🔎 Why adopt KRM?

*   [Blog post - “Why is Kubernetes getting so popular?”](https://stackoverflow.blog/2020/05/29/why-kubernetes-getting-so-popular/) - Ricardo Aravena, StackOverflow
*   [Blog post - “Kubernetes Design and Development Explained”](https://thenewstack.io/kubernetes-design-and-development-explained/) - Saad Ali, TheNewStack 
*   [Blog post - “I do declare! Infrastructure automation with Configuration as Data” ](https://cloud.google.com/blog/products/containers-kubernetes/understanding-configuration-as-data-in-kubernetes)- Kelsey Hightower and Marc Balch, Google Cloud 
*   [Blog post - “How GitOps and the KRM make multi-cloud less scary](https://seroter.com/2021/01/12/how-gitops-and-the-krm-make-multi-cloud-less-scary/)” - Richard Seroter, Google Cloud 
*   [Video - Cloud Native Resource Management @ GCP Next ‘19](https://www.youtube.com/watch?v=s_hiFuRDJSE) - Gregg Donovan, Michael Kibbe, Sonam Saxena (Google)  


## 💻  Tools 

*   [VSCode - YAML extension ](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
*   [Google Cloud Code](https://cloud.google.com/code/docs/vscode/features) - Deploy Kubernetes YAML directly from an IDE 
*   [kustomize](https://github.com/kubernetes-sigs/kustomize): “kustomize lets you customize raw, template-free YAML files for multiple purposes, leaving the original YAML untouched and usable as is.” 
*   [kpt](https://github.com/GoogleContainerTools/kpt): “a toolkit to help you manage, manipulate, customize, and apply Kubernetes Resource configuration data files” 
*   [ConfigSync (Google Cloud)](https://cloud.google.com/kubernetes-engine/docs/add-on/config-sync/overview) - sync KRM from Git repositories to GKE clusters
*   [Azure Service Operator for Kubernetes](https://github.com/Azure/azure-service-operator): “helps you provision Azure resources and connect your applications to them from within Kubernetes.”
*   [Google Cloud Config Connector](https://cloud.google.com/config-connector/docs/overview): “a Kubernetes addon that allows you to manage Google Cloud resources through Kubernetes.” 
*   [AWS Controllers for Kubernetes](https://aws-controllers-k8s.github.io/community/): “lets you define and use AWS service resources directly from Kubernetes.”  
*   [OpenPolicyAgent](https://www.openpolicyagent.org/docs/latest/): “an open source, general-purpose policy engine that unifies policy enforcement across the stack.”  (see also: [Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/)) 
*   [PolicyController ](https://cloud.google.com/anthos-config-management/docs/concepts/policy-controller) (Google Cloud) - managed OPA Gatekeeper GKE Admission Controller (only allow compliant KRM into the cluster)
*   [gcloud resource-config bulk-export](https://cloud.google.com/sdk/gcloud/reference/beta/resource-config/bulk-export) - export live Google Cloud object state to KRM files, for declarative management 

## 🛠 How-tos 

*   [Blog Post - Introduction to YAML- Creating a Kubernetes deployment](https://www.mirantis.com/blog/introduction-to-yaml-creating-a-kubernetes-deployment/#:~:text=YAML%20Basics&text=When%20defining%20a%20Kubernetes%20manifest,so%20you%20can%20track%20changes) - Nick Chase, Mirantis
*   [Tutorial - Declarative Management of Kubernetes Objects Using Configuration Files - ](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/declarative-config/)kubernetes.io 
*   [KubeBuilder book - What is a Resource?  ](https://book-v1.book.kubebuilder.io/basics/what_is_a_resource.html)
*   [Managing Resources](https://kubernetes.io/docs/concepts/cluster-administration/manage-deployment/) - kubernetes.io 
*   [Blog post - How To Manage Your Kubernetes Configurations with Kustomize](https://www.digitalocean.com/community/tutorials/how-to-manage-your-kubernetes-configurations-with-kustomize) - Jason Simmons, DigitalOcean 
*   [Google Cloud Code - Working with Google Cloud Platform and Kubernetes YAML](https://cloud.google.com/code/docs/vscode/yaml-editing)
*   [Solution Guide - Safe Rollouts with Anthos Config Management - Google Cloud](https://cloud.google.com/solutions/safe-rollouts-with-anthos-config-management)
*   [Solution Guide - Best practices for policy management with Anthos Config Management and GitLab](https://cloud.google.com/solutions/best-practices-for-policy-management-with-anthos-config-management) - Google Cloud 
*   [Solution Guide - Validating apps against company policies in a CI pipeline ](https://cloud.google.com/anthos-config-management/docs/tutorials/app-policy-validation-ci-pipeline)- Google Cloud 
*   [Solution Guide - Managing cloud infrastructure using kpt ](https://cloud.google.com/solutions/managing-cloud-infrastructure-using-kpt) - Google Cloud 


## 🌊 Deep Dives 

*   [Extending the Kubernetes API with Custom Resources](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/) - kubernetes.io 
*   [What is a Kubernetes operator? - RedHat ](https://www.redhat.com/en/topics/containers/what-is-a-kubernetes-operator)
*   [Twitter - Kubernetes/Borg/Omega history + KRM](https://threader.app/thread/1121054924979064832) - Brian Grant, Google  
*   [GitHub - Architecture - the Kubernetes Resource Model](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/architecture/resource-management.md) - Brian Grant, Google 
*   [GitHub - Declarative Application Management in Kubernetes](https://github.com/kubernetes/community/blob/master/contributors/design-proposals/architecture/declarative-application-management.md) - Brian Grant, Google 

 
