# Universidade Federal do Rio de Janeiro

**Alunos:** Yan Lukas W.T.P. e Carlos Henrique de Almeida Leal  
**Grupo:** X  
**Disciplina:** EEL873 - 2025/2 - Engenharia de Software  
**Professor:** Geraldo Xexéo  

---

## Objetivo

> Faça uma pesquisa da *Livraria Resolve* e descubra 5 desejos de suas partes interessadas em relação ao software necessário.  
> Em relação a todos os usuários, classifique usando o método **MoSCoW**.

---

## Requisitos e Prioridades (MoSCoW)

### Must-have
- **Plataforma de vendas online**  
  Objetivo central do Arnaldo; sem isso o projeto perde o propósito.  
  *Risco:* Bruna teme perda do diferencial → exige personalização no e-commerce.

- **Métodos de pagamento modernos (Pix, Cartão, PayPal) com antifraude**  
  Clientes exigem; vendedores relatam atrasos; sem isso não há agilidade.  
  *Risco:* chargeback em livros caros → precisa de política antifraude.

- **Fluxo integrado de pedidos (cliente ↔ fornecedor) com status**  
  Reclamações de erros e esquecimentos; Bruna pede visibilidade (pedido, recebido, enviado, pago).  
  *Risco:* sem controle, o site gera mais confusão do que solução.

- **Integração obrigatória com MySQL / ERP financeiro**  
  Restrição técnica explícita (Carlos e Bruna).  
  *Risco:* não é opcional — exigência da TI.

- **Cadastro e aprovação de clientes (com bloqueio de inadimplentes)**  
  Arnaldo exige aprovação prévia; vendedores citam a “lista negra”.  
  *Risco:* gestão de inadimplentes é sensível e pode gerar resistência dos clientes.

---

### Should-have
- **Relatórios de vendas, gastos por fornecedor e pedidos não atendidos**  
  Pedido de Armando e Bruna; fundamental para estratégia.  
  *Observação:* parece extra, mas é crítico para gestão.

- **Histórico e segmentação de clientes (perfil de compra)**  
  Apoio à fidelização e marketing (Bruna e Armando).  
  *Risco:* envolve tratamento de dados sensíveis (LGPD).

---

### Could-have
- **Promoções / catálogo digital de estoque remanescente**  
  Bruna quer aproveitar o pequeno estoque em ofertas.  
  *Risco:* existência de estoque pode mascarar falhas de gestão.

- **Notificações automáticas (email/WhatsApp) para clientes**  
  Melhoram a experiência e reduzem trabalho manual.  
  *Risco:* implementar cedo demais pode atrasar funcionalidades centrais.

---

### Won’t-have (por enquanto)
- **Mala direta impressa / catálogos físicos**  
  Primeiro pedido da Bruna, mas até ela disse que email já resolve.  
  *Risco:* alto custo e chance de priorizar algo sem retorno real.
