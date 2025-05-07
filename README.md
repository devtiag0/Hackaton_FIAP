# Hackaton_FIAP

#  Projeto: Personalização e Engajamento com IA Generativa

##  Visão Geral da Solução

Este projeto apresenta uma solução inovadora para **otimizar a experiência do cliente** utilizando **IA generativa**, com foco em três pilares:

1. **Análise inteligente de dados de clientes**
2. **Geração automatizada de conteúdo personalizado**
3. **Campanhas personalizadas e automáticas baseadas em perfil**

A proposta foi desenvolvida como um MVP funcional, com base em dados simulados, e demonstra como tecnologias como **IBM WatsonX.ai**, **Gemini**, **Python** e **Flutter** podem ser combinadas para gerar valor real e mensurável em estratégias de marketing, relacionamento e vendas.

---

## 🗺️ Diagrama da Solução

```text
                                +-------------------------------+
                                | Entrada de Dados Internos     |
                                | (Clientes: CRM / CSV / API)   |
                                +---------------+---------------+
                                                |
                                                v
                                +-------------------------------+
                                | Pré-processamento             |
                                | (Python + Pandas)             |
                                +---------------+---------------+
                                                |
                                                v
     +-------------------------+      +-------------------------+     
     | Entrada de Dados        |      | Entrada de Dados        |
     | Externos / Potenciais   |      | Comportamento Online    |
     | (Web, Leads, Redes Soc.)|      | (Cookies, Interesse etc)|
     +-------------+-----------+      +-------------+-----------+
                   \                           /
                    \                         /
                     \_______________________/
                              |
                              v
              +-------------------------------+
              | Análise e Segmentação por IA   |
              | (IBM WatsonX.ai)              |
              +---------+---------+-----------+
                        |                     |
                        v                     v
      +-------------------------+   +---------------------------+
      | Produtos / Serviços     |   | Produtos / Serviços       |
      | para Clientes Atuais    |   | para Potenciais Clientes  |
      +-------------------------+   +---------------------------+
                        |                     |
                        v                     v
+--------------------------+     +--------------------------------------+
| Campanhas Personalizadas |     | Estratégias de Captação por Mídias  |
| (E-mail, App, SMS)       |     | (Social Ads, Postagens, WhatsApp)   |
+------------+-------------+     +---------------------+----------------+
             |                                         |
             v                                         v
+-------------------------------+         +-----------------------------+
| Interface Flutter (Cliente)  |         | Páginas de Conversão /      |
| Recomendações Personalizadas |         | Landing Pages para Novos    |
+-------------------------------+         | Leads ou Vendas Diretas     |
                                          +-----------------------------+

