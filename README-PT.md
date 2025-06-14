# Análise e Auditoria de Segurança Interna - Botium Toys
<p align="right">
  <a href="./README.md">Read in English 🇺🇸</a>
</p>

Projeto de portfólio desenvolvido como parte do <a href="https://www.coursera.org/google-certificates/cybersecurity-certificate">Certificado Profissional de Segurança Cibernética do Google</a>

### Sobre o Projeto
Este projeto simula uma auditoria de segurança completa para a "Botium Toys", uma empresa de brinquedos fictícia. O objetivo é transformar um cenário de alto risco (pontuação 8/10) em uma fortaleza de segurança, aplicando conceitos de cibersegurança do mundo real.

---

### Resumo do Projeto
A Botium Toys, uma empresa de brinquedos com presença física e online, apresentava uma pontuação de risco de 8 em 10 devido à falta de controles de segurança e conformidade com regulamentações. O escopo desta auditoria abrangeu todo o programa de segurança da empresa, incluindo seus ativos de TI, rede interna e sistemas. A análise focou em identificar os controles existentes, avaliar a conformidade com padrões como PCI DSS e GDPR, e propor um plano de ação para mitigar os riscos identificados.

---

### ➤ O Desafio
A Botium Toys, uma empresa em crescimento com operações de e-commerce, enfrentava um risco de segurança classificado como "Alto" devido à falta de controles essenciais. A missão era clara: diagnosticar as vulnerabilidades, avaliar a conformidade com padrões globais e criar um plano de ação estratégico para proteger os ativos da empresa e os dados de seus clientes.

---

### ➤ Minha Abordagem e Análise
Para resolver este desafio, segui uma metodologia estruturada em três fases:
1. **Diagnóstico de Controles:** Realizei uma avaliação completa dos controles de segurança atuais da empresa, comparando-os com as melhores práticas do setor.
2. **Análise de Conformidade:** Verifiquei a aderência da empresa às regulamentações PCI DSS (para pagamentos com cartão) e GDPR (para dados de clientes da União Europeia).
3. **Plano de Ação:** Desenvolvi um conjunto de recomendações priorizadas para mitigar os riscos mais críticos de forma eficiente.
---

### ➤ Diagnóstico de Segurança: O Que Foi Encontrado

### Controles Existentes ✅
A empresa já possuía uma segurança básica, o que era um bom ponto de partida:
* Firewalls
* Antivirus
* Controles de acesso físico (trancas e CFTV)

### Principais Vulnerabilidades Identificadas ❌
* **Controle de Acesso Falho:** O **princípio do menor privilégio** não é implementado, permitindo que qualquer funcionário acesse dados críticos de clientes.
*  **Falta de Continuidade dos Negócios/Recuperação de Desastres:** A ausência total de **backups** e um ** plano de recuperação de desastres** deixa a empresa vulnerável a uma paralisação completa.
*  **Dados de Pagamento Não Criptografados:** A **criptografia não é usada** para proteger os dados de cartão de crédito, o que é uma falha crítica de segurança.
*  **Políticas de Senha Fracas:** As políticas são fracas e não há um sistema para forçar sua aplicação, facilitando o acesso não autorizado.
*  **Sem Capacidade de Detecção de Ameaças** A empresa não possui um **Sistema de Detecção de Intrusão (IDS)**, deixando-a "cega" para potenciais ataques em andamento.

---

### ➤ Análise de Conformidade

| Regulamentação | Status | Detalhes da Análise |
| :--- | :--- | :--- |
| **PCI DSS** | 🔴 **Não Conforme** | Falhas críticas na proteção de dados de cartão de crédito (falta de criptografia e controle de acesso) violam os requisitos fundamentais. |
| **GDPR** | 🟡 **Parcialmente COnforme** | ✅ Possui um plano de notificação de violação. <br> ❌ Falha em garantir a segurança dos dados pessoais e em classificar os dados adequadamente. |

---

### ➤ Plano de Ação Estratégico

Para resolver as vulnerabilidades identificadas, desenvolvi um plano de ação focado em gerar o máximo impacto com o menor esforço inicial.

#### **Prioridade CRÍTICA (Implementação Imediata)**
1.  **Ativar Backups e Criar um Plano de Recuperação de Desastres:** Garantir que a empresa possa se recuperar de qualquer incidente.
2.  **Implementar Controle de Acesso (Menor Privilégio):** Restringir o acesso aos dados para apenas quem realmente precisa.
3.  **Criptografar Dados de Cartão de Crédito:** Proteger os dados de pagamento dos clientes e alcançar a conformidade com o PCI DSS.

#### **Prioridade ALTA (Próximos Passos)**
4.  **Modernizar a Política de Senhas:** Implementar uma política de senhas robusta e um sistema de gerenciamento para forçar sua aplicação automaticamente.
5.  **Implantar um Sistema de Detecção de Intrusão (IDS):** Ganhar visibilidade em tempo real sobre o tráfego da rede para detectar e responder a potenciais ameaças.

--- 

### ➤ Artefatos do Projeto
Os documentos de referência que serviram de base para esta auditoria estão disponíveis nos links abaixo:
* [Relatório de Escopo e Risco]([https://github.com/cleyandson/botium-toys-security-audit/blob/main/Documents/Botium%20Toys_%20Scope%2C%20goals%2C%20and%20risk%20assessment%20report.pdf](https://github.com/cleyandson/botium-toys-internal-audit-security/blob/main/Documents/Botium%20Toys_%20Scope%2C%20goals%2C%20and%20risk%20assessment%20report.pdf))
* [Categorias de Controles]([https://github.com/cleyandson/botium-toys-security-audit/blob/main/Documents/Control%20categories.pdf](https://github.com/cleyandson/botium-toys-internal-audit-security/blob/main/Documents/Control%20categories.pdf))
* [Checklist de Controles e Conformidade (preenchido por mim)]([https://github.com/cleyandson/botium-toys-security-audit/blob/main/Documents/Controls%20and%20compliance%20checklist%20-%20answered.pdf](https://github.com/cleyandson/botium-toys-internal-audit-security/blob/main/Documents/Controls%20and%20compliance%20checklist%20-%20answered.pdf))








