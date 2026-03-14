# DevOps Pipeline

## CI/CD Evreni

```

CI/CD:           (Jenkins, Git,  GitHub, GitOps,  GitHub Actions,    GitLab, GitLab CI,    Bitbucket, Bamboo)
Scripting        (Python, Bash, PowerShell)
Containers:      (Docker)
Orchestration:   (Kubernetes, Helm, ArgoCD)
Cloud            (AWS, Azure, GCP)
Virtualization:  (VMware, VirtualBox)
IaC:             (Terraform, Ansible, CloudFormation)
Monitoring:      (Prometheus, Grafana, ELK)
```

![DevOps 3 - Cloud Terraform.jpg](public/DevOps%203%20-%20Cloud%20Terraform.jpg)

---


IAM -> Users -> mydemouser


AWS'de yeni bir kullanıcı oluşturuyoruz.

Ona Admin yetkisi veriyoruz.


IAM -> Users -> mydemouser -> Create access key

---

Access key
AAAAAAAAAAAAAAAAAAA

Secret access key
BBBBBBBBBBBBBBBBBBBBB

---

Bir terminal aç. Uzaktaki AWS servislerini yönetmek için kullucaya ait Access key ve Secret access key verilerini girdik.

```
aws configure
```

```
AWS Access Key ID : AAAAAAAAAAAAAAAAAAA
AWS Secret Access Key : BBBBBBBBBBBBBBBBBBBBB
Default region name [us-east-1]: us-east-1
Default output format [json]: json
```


Terraform üzerinden de 01_provider.tf dosyasına da bu Access key ve Secret access key verilerini girdik.


#### ReactJS - [Next.js](https://nextjs.org) project [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

```bash
npm run dev
```

http://localhost:3000

---

##  1. Makine: Jenkins Master Node

```bash
aws configure
```


```
java --version
docker --version
jenkins --version
trivy --version
sonar-scanner --version
```

### Docker'da tüm containerları listeledik.
```
docker ps -a
```

```
docker stop CONTAINER_ID
docker start CONTAINER_ID

docker ps -a
```

#### Jenkins için Jenkins makinesinin PUBLIC_IP'sini alıp 8080 portuna gideceğiz.

http://PUBLIC_IP:8080

```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```

#### SonarQube için Jenkins makinesinin PUBLIC_IP'sini alıp 9000 portuna gideceğiz.

http://PUBLIC_IP:9000


#### React için Jenkins makinesinin PUBLIC_IP'sini alıp 3000 portuna gideceğiz.

http://PUBLIC_IP:3000


