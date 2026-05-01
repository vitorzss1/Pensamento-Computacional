# Design do Projeto – Atividade de Decomposição

## Visão Geral

Este documento apresenta a estrutura lógica da atividade desenvolvida na disciplina de Pensamento Computacional. O objetivo do trabalho foi aplicar o conceito de decomposição para representar o processo de compra de ingressos online.

A atividade foi baseada em ações reais realizadas pelo usuário durante uma compra em aplicativos de eventos.

---

# Cenário Escolhido

O cenário utilizado foi a compra de ingressos para shows utilizando plataformas digitais como:

* Bilheteria Digital
* Sympla
* Ingressos.com
* R2 Comvc

O processo foi dividido em etapas menores para facilitar a análise e organização das ações.

---

# Decomposição do Processo

## Etapa 1 — Acesso ao celular

* Pegar o celular.
* Desbloquear utilizando senha PIN.

### Conceitos aplicados

* Autenticação.
* Controle de acesso.

---

## Etapa 2 — Busca da plataforma

* Procurar um aplicativo de venda de ingressos.
* Entrar na plataforma escolhida.

### Conceitos aplicados

* Navegação em sistemas.
* Seleção de serviços.

---

## Etapa 3 — Escolha do evento

* Escolher o dia e mês do show.
* Selecionar a opção desejada.

### Conceitos aplicados

* Filtragem de informações.
* Tomada de decisão.

---

## Etapa 4 — Cadastro

O usuário informa:

* Nome
* E-mail
* CPF

### Conceitos aplicados

* Cadastro de dados.
* Identificação do usuário.

---

## Etapa 5 — Pagamento

* Gerar o código de pagamento.
* Abrir o aplicativo do banco.
* Realizar o pagamento antes do vencimento do código.

### Conceitos aplicados

* Integração bancária.
* Validação de transações.
* Tempo limite de sessão.

---

## Etapa 6 — Confirmação

* Entrar no e-mail.
* Confirmar a compra.
* Visualizar o ingresso.

### Conceitos aplicados

* Confirmação automática.
* Entrega digital.

---

# Reconhecimento de Padrões

Durante a atividade, foram identificados padrões comuns em sistemas digitais:

* Login por autenticação.
* Cadastro de usuários.
* Pagamentos online.
* Confirmação automática por e-mail.

---

# Abstração

Foram considerados apenas os elementos principais do processo.

Detalhes como modelo do celular, banco utilizado ou aparência dos aplicativos não foram incluídos, pois não alteram a lógica principal da atividade.

---

# Fluxo Simplificado

```text id="1jxjpb"
Desbloquear celular
↓
Abrir aplicativo de ingressos
↓
Escolher evento
↓
Cadastrar dados
↓
Gerar pagamento
↓
Pagar no banco
↓
Receber confirmação
↓
Visualizar ingresso
```

---

# Conclusão

A atividade mostrou como uma tarefa cotidiana pode ser organizada utilizando pensamento computacional.

A decomposição ajudou a dividir o processo em etapas menores, facilitando a compreensão da lógica utilizada durante a compra de ingressos online.
