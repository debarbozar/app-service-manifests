# app-service-manifests

Bem-vindo ao repositório **app-service-manifests**!

Este repositório foi criado com o objetivo de aprendizado e testes, utilizando o WSL  em conjunto com o Minikube para o gerenciamento de clusters Kubernetes.  
O foco é permitir que experimentar, testar e aprender sobre a configuração e implantação de serviços em ambientes controlados e simulados em conjuto com pipeline que será integrada nesses serviços.

Aqui, você encontrará todos os manifestos necessários para configurar, documentar e implantar serviços de forma padronizada.

## Objetivo

- Centralizar os manifestos dos meus serviços de aplicação.
- Padronizar e documentar configurações e dependências.
- Simplificar o processo de implantação e manutenção.
- Garantir rastreabilidade e controle de versões das configurações.

## Exemplo de uso

```yaml
apiVersion: v1
kind: Service
metadata:
  name: meu-servico
spec:
  ports:
    - port: 80
  selector:
    app: meu-app
```

## Contribuição

Sugestões de melhoria, correções e novas ideias são sempre bem-vindas!  
Para contribuir:
- Abra uma issue com sua sugestão ou relato de problema.
- Envie um pull request com suas alterações.

---