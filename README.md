# Exam Solutions Master

> 문제풀이 service

## Version 1

- [ ] 사용자가 텍스트를 사용해 문제에 대한 정보를 제공하면 해당 문제에 대한 답과 해설을 제공  

> korean & english

## Version 2

- [ ] 사용자가 그림을 통해 문제에 대한 정보를 제공하면 해당 문제에 대한 답과 해설을 제공  

> only english

## Version 3

- [ ] 사용자가 그림을 통해 문제에 대한 정보를 제공하면 해당 문제에 대한 답과 해설을 제공 후 해당 정보 서버에 저장  

> text => korean, english, image => english

## Skill Set

- Backend => Go(gin-gonic)
- Frontend => Next.js
- IaC => Terraform
- Deploy => AWS, Docker, EKS, ECR
- CI/CD => Jenkins, ArgoCD
- AI => ChatGPT, AWS Badrock, AWS textract
- Monitoring => Datadog, Prometheus, Grafana

## Final

- [ ] Frontend(React) - 사용자의 입력을 백엔드에 넘겨주고 응답값을 가져오는 페이지 개발
- [ ] Backend(Go) - 문제에 대한 정보를 해석하고 답과 해설 리턴
- [ ] IaC - VPC, EKS, ECR, IAM role 구축 및 삭제 자동화
- [ ] monitoring

## Progress

### Deploy(Kubernetes)

- [x] Kubernetes 환경 구축
  - [EC2위에 Kubernetes Cluster 구축하기 (MicroK8s)](https://war-oxi.github.io/posts/EC2%EC%97%90-k8s-Cluster%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/)
  - [EC2위의 MicroK8s Cluster에 Local에서 명령 하기
](https://war-oxi.github.io/posts/MicroK8s-Local%EC%97%90%EC%84%9C-%EB%AA%85%EB%A0%B9/)
  - [MicroK8s에 Worker Node 추가하기
](https://war-oxi.github.io/posts/MicroK8s%EC%97%90-Worker-Node-%EC%B6%94%EA%B0%80/)

### CI/CD 구성

- [x] Jenkins 구축
- [ ] ArgoCD 구축

### Frontend

- [ ] UI 구현
- [ ] Backend Server에 데이터 전송
- [ ] Backend Server에서 응답 값 받아오기

### Backend

- [ ] Exam Data 받기 API 개발
- [ ] Exam Data 해답 API 개발

### IaC

- [ ] AWS VPC 생성, 삭제 구현
- [ ] AWS EKS Cluster 생성, 삭제 구현
- [ ] AWS ECR Repository 생성, 삭제 구현

### Monitoring

- [ ] Prometheus 구축
  - [ ] Data Labeling (원하는 정보만)
- [ ] Grafana Dash Board 구축
- [ ] DataDog 구축
