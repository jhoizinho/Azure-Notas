# Boas Práticas no Microsoft Azure

## 1. Organização e Nomenclatura

- Use convenções claras para nomear recursos, como: `rg-prod-backup-eastus`.
- Separe ambientes por grupos de recursos: `rg-dev`, `rg-prod`, `rg-hml`.

## 2. Segurança

- Ative autenticação multifator (MFA) para todos os usuários.
- Utilize Azure AD com controle de acesso baseado em funções (RBAC).
- Evite deixar portas públicas abertas (como RDP e SSH).

## 3. Custos

- Configure alertas de orçamento via Azure Cost Management.
- Use o Azure Advisor para sugestões de economia.
- Automatize o desligamento de recursos não utilizados.

## 4. Monitoramento

- Configure Azure Monitor e Log Analytics.
- Ative alertas e dashboards para acompanhar o ambiente.
- Registre logs de atividades e diagnostique erros com Application Insights.

## 5. Backup e Recuperação

- Utilize Azure Backup para VMs e dados críticos.
- Faça testes periódicos de restauração.
