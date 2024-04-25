# Exam Solutions Master
문제풀이 service

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
