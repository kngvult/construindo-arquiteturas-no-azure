# construindo-arquiteturas-no-azure
Construindo Arquiteturas no Azure

# Desafio: Construindo Arquiteturas no Azure

## Objetivo
Este projeto tem como objetivo aplicar os conceitos aprendidos sobre **arquiteturas na nuvem com Microsoft Azure**, replicando ou melhorando o modelo proposto no laboratório da DIO.

## O que aprendi
Durante o desenvolvimento do projeto, explorei os seguintes pontos:
- Diferença entre **IaaS, PaaS e SaaS** e como cada um se aplica em arquiteturas.  
- Uso de **Grupos de Recursos** para organizar os componentes.  
- Criação de **Máquinas Virtuais** e configuração de **Conjuntos de Disponibilidade**.  
- Configuração de **Banco de Dados no Azure** (SQL Database).  
- Implementação de **Zonas de Disponibilidade** para alta resiliência.  
- Conceitos de **Elasticidade e Escalabilidade** aplicados a aplicações críticas.  
- Monitoramento e segurança com **Azure Monitor** e **NSG (Network Security Groups)**.  

## Passo a Passo Documentado
1. Criar um **Grupo de Recursos** para centralizar os componentes.  
2. Configurar **Máquinas Virtuais** em conjunto de disponibilidade.  
3. Criar uma instância de **Banco de Dados SQL**.  
4. Configurar **rede virtual e firewall**.  
5. Implementar **Zonas de Disponibilidade** para garantir alta disponibilidade.  
6. Testar a comunicação entre os serviços.  
7. Documentar a arquitetura final.  

## Evidências
- Diagrama da Arquitetura final (diagrama.png).

### Diagrama de Arquitetura (Fluxograma Textual)

Internet 🌐  
│  
└── Azure Load Balancer  
  │  
  ├── Web Tier  
  │  ├── Web VM 1  
  │  └── Web VM 2  
  │  
  ├── Application Tier  
  │  ├── App VM 1  
  │  └── App VM 2  
  │  
  └── Database Tier  
    ├── Azure SQL Database  
    └── Storage Account  

🔒 Segurança e Monitoramento  
  ├── Network Security Group (NSG)  
  └── Azure Monitor  

🏢 Alta Disponibilidade  
  ├── Zone 1  
  ├── Zone 2  
  └── Zone 3


## Conclusão
Esse desafio reforçou minha compreensão sobre como projetar arquiteturas na nuvem utilizando o Azure, equilibrando **flexibilidade, alta disponibilidade, segurança e gerenciabilidade**.  

---

**Autor(a):** Ana Quézia de Oliveira Souza
