# 🚘 SmartPark - Sistema de Gestão de Estacionamento Inteligente 🚖

> **Projeto de Extensão Universitária | Análise e Desenvolvimento de Sistemas (ADS)**
> *Solucionando o caos urbano e garantindo a privacidade do seu Condomínio.*

---

## Sobre o Projeto
O **SmartPark** nasceu para resolver um problema real: a obstrução de calçadas e a dificuldade de identificação de veículos em condomínios. Muitas vezes, um carro estacionado irregularmente gera conflitos, congestionamentos e perda de tempo para a portaria. 

A solução proposta utiliza **Tags QR Code** fixadas nos veículos, permitindo uma comunicação rápida, segura e, acima de tudo, em conformidade com a **LGPD (Lei Geral de Proteção de Dados)** garantindo a via de mão dupla segura e sustentavél.

### O que o sistema faz?
1. **Escaneamento Instantâneo:** Vizinhos ou pedestres escaneiam o QR Code no adesivo do carro e identifica o condominio do automovel.
2. **Notificação Silenciosa:** O sistema identifica o veículo escaneado e envia um alerta direto para o painel da portaria.
3. **Privacidade Preservada:** Quem escaneia o código **não vê** o nome, telefone ou apartamento do morador.
4. **Agilidade na Gestão:** Reduz o tempo de identificação de **15 minutos para apenas 2 minutos**.

---

## Tecnologias Empregadas

Este projeto foi o meu ponto de partida para consolidar conhecimentos em:

* **Front-End:** [React](https://reactjs.org/) / [Next.js](https://nextjs.org/) & [Tailwind CSS](https://tailwindcss.com/) (Interface moderna e responsiva).
* **Back-End:** [Node.js](https://nodejs.org/) com Framework Express.
* **Banco de Dados:** [PostgreSQL](https://www.postgresql.org/) (Modelagem relacional e integridade de dados).
* **Comunicação Real-time:** [Socket.io](https://socket.io/) (Para notificações instantâneas na portaria).
* **Segurança:** Implementação de conceitos de criptografia de IDs e conformidade com a LGPD.

---

## Como funciona? (Arquitetura)



1. **Leitura:** O smartphone lê o QR Code (Ex: `smartpark.com/v/abc-123`).
2. **Validação:** O servidor Node.js recebe o ID, consulta o banco PostgreSQL e identifica a unidade.
3. **Alerta:** A portaria recebe o aviso: *"O veículo do Bloco A, Apto 102 precisa ser movido"*.

---

## Impacto Social
O SmartPark não é apenas um software, é uma ferramenta de **convivência coletiva**.
- **Acessibilidade:** Garante calçadas livres para cadeirantes e pedestres.
- **Segurança de Dados:** Elimina a necessidade de bilhetes com telefones expostos nos painéis dos carros.
- **Aprendizado:** Aplicação prática de Engenharia de Software, UX Design e Segurança da Informação.

---

## 📈 Próximos Passos
- [ ] Implementação do módulo de geração de PDF para impressão das tags.
- [ ] Histórico de recorrência de infrações para a administração do condomínio.
- [ ] Integração com Telegram/WhatsApp para notificar o morador diretamente.

---
**Desenvolvido como parte do currículo de ADS.** "Tecnologia invisível que resolve problemas reais." - Projeto de extensão baseado na projeção da eficiencia do sistema. 