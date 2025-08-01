---
title: "Documentation"
css: "scss/docs.scss"
isDocsRoot: true
_build:
  render: never
  list: never
  publishResources: false

LinkTitle: "文档"


section1:
  title: KubeSphere 文档
  content: 了解如何通过 KubeSphere 容器平台构建并管理云原生应用程序。获取文档、示例代码与教程等信息。
  image: /images/docs/v3.x/banner.png
  version: "v3.3"

sectionLink:
  docs:
    title: 常用文档
    description: 通过快速入门、教程和示例等学习使用 KubeSphere。
    list:
      - /docs/v3.3/quick-start/all-in-one-on-linux
      - /docs/v3.3/quick-start/minimal-kubesphere-on-k8s
      - /docs/v3.3/quick-start/create-workspace-and-project
      - /docs/v3.3/introduction/what-is-kubesphere
      - /docs/v3.3/pluggable-components
      - /docs/v3.3/installing-on-linux/introduction/multioverview
      - /docs/v3.3/pluggable-components/app-store
      - /docs/v3.3/pluggable-components/devops
      - /docs/v3.3/multicluster-management
      - /docs/v3.3/project-user-guide/configuration/image-registry
      - /docs/v3.3/devops-user-guide/how-to-use/pipelines/create-a-pipeline-using-jenkinsfile
      - /docs/v3.3/devops-user-guide/how-to-use/pipelines/create-a-pipeline-using-graphical-editing-panel
      - /docs/v3.3/project-user-guide/image-builder/source-to-image
      - /docs/v3.3/application-store/app-lifecycle-management
      
  videos:
    title: 视频教程
    description: 观看视频教程学习 KubeSphere。
    list:
      - link: https://www.bilibili.com/video/BV1KA411s7D3
        text: All-in-One 模式安装 KubeSphere
      - link: https://www.bilibili.com/video/BV16y4y1v7cn
        text: 多节点安装 KubeSphere
      - link: https://www.bilibili.com/video/BV1Pz4y1C7jr
        text: 离线安装 KubeSphere

section3:
  title: 在云服务上运行 KubeSphere 与 Kubernetes 技术栈
  description: 云厂商以托管的形式为用户提供 KubeSphere 服务，深度集成了公有云托管容器服务，用户可在几分钟内通过简单的步骤迅速构建高可用集群。您可在以下公有云上一键部署 KubeSphere。
  list:
    - image: /images/docs/v3.x/aws.jpg
      content: AWS Quickstart
      link: https://aws.amazon.com/quickstart/architecture/qingcloud-kubesphere/
    - image: /images/docs/v3.x/microsoft-azure.jpg
      content: Azure Marketplace
      link: https://market.azure.cn/marketplace/apps/qingcloud.kubesphere
    - image: /images/docs/v3.x/qingcloud.svg
      content: QingCloud QKE
      link: https://www.qingcloud.com/products/kubesphereqke/

  titleRight: 想要在您的云上托管 KubeSphere?
  btnContent: 与我们合作
  btnLink: /partner/
---
