# Lean Inception - Bilhetinho

> MVP desenvolvido para a disciplina de **Gestão Ágil de Projetos e Produtos**  
> Pós-Graduação em Engenharia de Software — PUC-Rio
---

## Autor

Marcelo M. Caetano  
[https://www.linkedin.com/in/marcelomcaetano/](https://www.linkedin.com/in/marcelomcaetano/)  

---

## Lean Inception - Miro

<https://miro.com/app/board/uXjVHH7nhPQ=/?share_link_id=974466635570>

## Product Backlog - PDF

- [product_backlog.pdf](product_backlog.pdf)

## Wireframe

- [01_musico_cadastro_login_home_criar.png](./wireframe/01_musico_cadastro_login_home_criar.png)
- [02_musico_evento_qrcode_pedidos.png](./wireframe/02_musico_evento_qrcode_pedidos.png)
- [03_publico_scanner_pedido_confirmacao.png](./wireframe/03_publico_scanner_pedido_confirmacao.png)

## 1. Contexto do Negócio

### Stakeholders

| Stakeholder | Descrição |
|---|---|
| **Músicos** | Artistas que realizam apresentações ao vivo em bares, restaurantes e eventos. São os criadores de eventos e receptores dos pedidos de música. |
| **Público** | Frequentadores de estabelecimentos com música ao vivo que desejam interagir com o músico solicitando músicas. |

### Time Scrum

| Papel | Qtd | Habilidades |
|---|---|---|
| Product Owner (PO) | 1 | Visão de produto, priorização de backlog, comunicação com stakeholders |
| Scrum Master (SM) | 1 | Facilitação, remoção de impedimentos, coaching ágil |
| Desenvolvedor Mobile | 2 | Desenvolvimento mobile (React Native ou Flutter), integração com APIs, geolocalização, UI/UX mobile |

**Tamanho do time:** 4 pessoas
**Modelo de trabalho:** Sprints de 2 semanas

---

## 2. Product Vision (Visão do Produto)

### Visão do Músico

```
Para músicos que se apresentam ao vivo em bares, restaurantes e eventos

Que recebem pedidos de música em bilhetes de papel ilegíveis, perdem pedidos
  durante o show e não têm controle sobre as solicitações do público

O Bilhetinho

É um aplicativo mobile

Que permite ao músico criar eventos, gerar um QR Code exclusivo e receber
  pedidos de música de forma digital, organizada e segura, visualizando
  e gerenciando os pedidos diretamente no seu dispositivo

Diferentemente dos bilhetes de papel entregues por garçons, que se perdem,
  são ilegíveis e podem conter conteúdo indevido

O nosso produto dá ao músico controle total sobre os pedidos, garantindo
  que apenas pessoas presentes no evento possam solicitar músicas,
  organizando os pedidos por ordem de chegada com opção de check
```

### Visão do Público

```
Para o público que frequenta bares e eventos com música ao vivo

Que deseja pedir uma música ao músico mas tem dificuldade por depender
  de papel, caneta e da intermediação do garçom, muitas vezes desistindo
  por vergonha ou falta de oportunidade

O Bilhetinho

É um aplicativo mobile

Que permite ao público escanear um QR Code no evento e enviar pedidos
  de música diretamente ao músico, sem necessidade de cadastro,
  de forma rápida, discreta e digital

Diferentemente do método tradicional de pedir papel e caneta ao garçom
  e escrever um bilhete físico que pode se perder ou nunca ser entregue

O nosso produto elimina a fricção e o constrangimento, permitindo que
  qualquer pessoa presente no evento peça sua música favorita com
  poucos toques na tela do celular
```

### Visão Resumida
>
> **"Conectar público e músico ao vivo de forma digital, substituindo o bilhete de papel por uma experiência moderna e sem fricção."**

---

## 3. The Product IS — IS NOT — DOES — DOES NOT DO

| IS (É) | IS NOT (Não É) |
|---|---|
| Um app mobile para interação entre público e músico | Uma plataforma de streaming de música |
| Uma ferramenta de pedidos de música ao vivo | Uma rede social para músicos |
| Um canal direto de comunicação público → músico | Um marketplace de contratação de músicos |
| Um facilitador de experiências em eventos ao vivo | Um sistema de venda de ingressos |

| DOES (Faz) | DOES NOT DO (Não Faz) |
|---|---|
| Permite ao público enviar pedidos de música via QR Code | Não reproduz músicas (não é player) |
| Permite ao músico criar e gerenciar eventos | Não faz agendamento/contratação de shows |
| Gera QR Code para validar presença no evento | Não processa pagamentos (MVP) |
| Lista eventos ao vivo por geolocalização | Não faz chat/mensagens entre público e músico |
| Permite ao músico cadastrar playlists | Não gerencia o estabelecimento (bar/restaurante) |
| Filtra eventos por data, local, músico | Não valida o conteúdo do pedido de música (MVP) |

---

## 4. Product Goals (Objetivos do Produto)

> Se você tivesse que resumir o produto em três objetivos de negócio, quais seriam?

### Conectar público e músico ao vivo

- Permitir que o público envie pedidos de música digitalmente
- Substituir o bilhete de papel por uma experiência digital
- Garantir que apenas pessoas presentes no evento enviem pedidos
- Mostrar eventos de música ao vivo por geolocalização

### Engajar e crescer a base de usuários

- Oferecer experiência sem cadastro para o público (baixa fricção)
- Facilitar a descoberta de eventos ao vivo próximos
- Permitir ao músico divulgar sua playlist e repertório
- Incentivar o público a usar o app em outros shows

### Monetizar a plataforma

- Oferecer planos premium para músicos (destaque de eventos, métricas avançadas)
- Viabilizar gorjeta digital do público para o músico
- Vender espaço publicitário dentro do app

---
