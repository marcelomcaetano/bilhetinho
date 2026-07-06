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
For :
    (M) Músicos que se apresentam ao vivo em bares, restaurantes e eventos
    (P) Pessoas que frequentam bares, restaurantes e eventos com música ao vivo
whose :
    (M) Recebem pedidos de música em bilhetes de papel
    (P) Gostaria de ouvir um música em especial e para isso precisa escrever em um papelzinho para que alguém entregue ao músico
the : 
    Bilhetinho
is a : 
    aplicativo mobile
that :
    Permite a interação entre músico e publico com pedidos de música
Different from :
    Da forma tradicional de pedir papel e caneta ao garçom e escrever um bilhetinho físico
our product :
    Elimina a perda de tempo, permitindo que qualquer pessoa presente no "evento" possa pedir sua música favorita (com poucos toques na tela do celular) dando ao músico controle total sobre os pedidos.
```

### Visão Resumida
>
> **"Conectar público e músico ao vivo de forma digital, substituindo o bilhete de papel por uma experiência moderna."**

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
| Permite ao público enviar pedidos de música | Não reproduz músicas (não é player) |
| Permite ao músico criar e gerenciar eventos | Não faz agendamento/contratação de shows |
| Lista eventos ao vivo por geolocalização | Não faz chat/mensagens entre público e músico |
| Permite ao músico cadastrar playlists | Não gerencia o estabelecimento (bar/restaurante) |

---

## 4. Product Goals (Objetivos do Produto)

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
