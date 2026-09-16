# 🏀 Racha City

> O mapa vivo do basquete de rua de Salvador.

O **Racha City** é uma plataforma colaborativa onde a comunidade encontra quadras de basquete, descobre onde a bola vai rolar e avalia as condições de cada quadra — tudo alimentado por quem realmente joga.

---

## 📖 Sobre o projeto

Quem curte jogar em Salvador conhece o problema: você quer bater uma bola, mas não sabe onde tem quadra boa perto, se ela está em condição de jogo, nem se vai ter gente. E as quadras largadas seguem invisíveis, sem ninguém pra cobrar melhorias.

O Racha City resolve isso sendo um **mapa vivo**, mantido pela própria comunidade: ele mostra não só onde as quadras estão, mas onde a bola vai rolar hoje e em que estado cada quadra se encontra.

O projeto começa focado no **basquete em Salvador**, com planos de crescer para outras modalidades e cidades.

## ✨ Funcionalidades (MVP)

- 📍 **Mapa de quadras** — busca por proximidade, com endereço real e rota.
- 🏀 **Basquete Hoje** — anúncio de rachas com data/hora e confirmação de presença (vou / não vou).
- ⭐ **Avaliação da comunidade** — nota e tags de condição (piso, cesta, iluminação, segurança).
- 📷 **Fotos** com regra de atualização, para nenhuma quadra ficar com foto antiga.
- 💬 **Grupos de WhatsApp** da quadra, para a galera se organizar.
- 🔐 **Login com Google** — leitura pública; contribuição exige autenticação.
- 🛡️ **Moderação** — quadras novas passam por aprovação antes de entrar no mapa.

## 🎯 Diferencial

- **Foco local em Salvador** — profundidade de comunidade que um app nacional não alcança.
- **Camada de racha ao vivo** — não só onde jogar, mas quando e com quem.
- **Visão cívica** — dar visibilidade às quadras abandonadas, como base para cobrança de reforma.

## 🛠️ Tecnologias

| Camada | Stack |
|---|---|
| Front-end | React + Vite, Tailwind CSS, Leaflet (mapa) |
| Back-end | Java + Spring Boot |
| Banco de dados | MySQL |
| Infraestrutura | AWS (S3, RDS, EC2/Elastic Beanstalk) |

## 📐 Documentação

O projeto conta com documentação de modelagem (na pasta `/docs`):

- **Modelagem do Sistema** — atores, requisitos, casos de uso e regras de negócio.
- **Modelagem do Banco de Dados** — MER conceitual, MER lógico, DER e normalização (até 3FN).

## 🚧 Status

Em desenvolvimento. Fase de planejamento e modelagem concluída; implementação em andamento.

## 👤 Autor

**Pedro Henrique** — Técnico em Desenvolvimento de Sistemas (SENAI CIMATEC).

> Projeto de estudo e comunidade. Sugestões e contribuições são bem-vindas.
