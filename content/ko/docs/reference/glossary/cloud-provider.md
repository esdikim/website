---
title: 클라우드 공급자
id: cloud-provider
date: 2018-04-12
full_link: /docs/concepts/cluster-administration/cloud-providers
short_description: >
  클라우드 컴퓨팅 플랫폼을 제공하는 조직.

aka:
- Cloud Service Provide
tags:
- community
---
 클라우드 컴퓨팅 플랫폼을 제공하는 사업자 또는 다른 조직.

<!--more-->

클라우드 공급자, 때로는 클라우드 서비스 공급자(CSP)라 부르며,
클라우드 컴퓨팅 플랫폼 또는 서비스를 제공한다.

많은 클라우드 공급자들은 관리되는 인프라를 제공한다(이를
Infrastructure as a Service 또는 IaaS 라 부른다).
관리되는 인프라를 통해 클라우드 공급자는
서버, 스토리지 그리고 네트워킹을 담당하고 쿠버네티스
클러스터 실행과 같은 계층을 관리한다.

사용자는 쿠버네티스를 관리되는 서비스(managed service)로도 찾을 수 있다. 때로는 이것을
Platform as a Service 또는 PaaS라 부른다. 관리되는 쿠버네티스를 사용하면
클라우드 공급자가 쿠버네티스 컨트롤 플레인만 아니라, 
노드와 연관되는 인프라(네트워킹, 스토리지 그리고 로드밸런서와 같은 기타 요소)
를 책임진다.
