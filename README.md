# Desafio AWS CloudFormation
Desafio sobre **Infraestrutura como Código (IaC)** utilizando o **AWS CloudFormation**.

O objetivo é entender como criar e gerenciar recursos na AWS de forma automatizada usando templates em **YAML**.

---

## 🧠 Conceitos Principais
- **CloudFormation** permite criar recursos AWS automaticamente.
- **IaC (Infrastructure as Code)** traz padronização e agilidade.
- Suporta arquivos **YAML** e **JSON**.
- Facilita a replicação e manutenção da infraestrutura.

---

## 💡 Exemplo de Template YAML
```yaml
AWSTemplateFormatVersion: "2010-09-09"
Description: Exemplo simples de CloudFormation

Resources:
  MeuBucketS3:
    Type: AWS::S3::Bucket
    Properties:
      BucketName: exemplo-cloudformation-dio
