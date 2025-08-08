# **Desafio Front-end Júnior**

Seja bem-vindo! Este desafio foi projetado para avaliar sua capacidade técnica como candidato(a) à vaga de **Desenvolvedor(a) Front-end Júnior**.

---

## **Proposta**
Você deverá desenvolver uma aplicação **React.js** com duas páginas principais: **Lista de Gatos** e **Formulário de Cadastro em Etapas**.  
O objetivo é avaliar:
- Consumo de APIs e manipulação de dados assíncronos;
- Organização e componentização do código;
- Validações de formulários;
- Boas práticas de interface e experiência do usuário.

---

## **Navegação**
A aplicação deve ter um **menu superior** com dois links:
- **Lista de gatos**
- **Formulário**

---

## **1) Página: Lista de Gatos**
- Deve requisitar a lista de **tags** no endereço:  
  `https://cataas.com/api/tags`
- As tags devem ser exibidas como **cards expansíveis**.
- Cada card deve exibir no título o **nome da tag**.
- Ao clicar no título do card, o corpo do card deve se **expandir abaixo do título** para exibir:
    - A lista de **IDs** obtida no endereço:  
      `https://cataas.com/api/cats`
    - **Filtragem:** exibir apenas os gatos cuja lista de tags **contenha a tag do card** selecionado.

**Referência visual:**
![image](https://user-images.githubusercontent.com/6603813/120489184-d1a52c00-c38d-11eb-8cae-d281fc76ec92.png)

---

## **2) Página: Formulário (3 etapas)**
O formulário deve ser dividido em **3 etapas**, cada uma em um **React Component** separado:

**Etapa 1**
- Email (**obrigatório**)
- Senha (**obrigatório**)
- Confirmação de senha (**obrigatório**)

**Etapa 2**
- Nome (**obrigatório**)
- Sobrenome (**obrigatório**)
- Data de nascimento

**Etapa 3**
- Endereço completo (**obrigatório**)

**Regras e comportamentos:**
- As etapas devem ser exibidas **uma de cada vez**, com **abas** para navegação **livre** entre elas;
- Cada etapa deve ter um **botão de avançar** para a próxima etapa;
- O **botão de Enviar** deve estar **visível em todas as etapas**, porém **desabilitado** até que **todas as 3 etapas** estejam válidas;
- Caso haja **erro** em uma etapa, a **aba** correspondente deve ter um **indicador visual de erro**;
- Quando uma etapa for validada corretamente, a aba deve ter um **indicador de concluída**;
- Ao finalizar todas as etapas e clicar em **Enviar**, deve aparecer uma **modal de confirmação de sucesso**.

**Referência visual:**
![image](https://user-images.githubusercontent.com/6603813/120489206-d7027680-c38d-11eb-9a52-a95aa640c905.png)

---

## **Estilo**
- Você é livre para definir cores, fontes e estilos visuais.
- O foco será avaliar clareza, organização e usabilidade.

---

## **Entrega**
- Publique seu projeto no **GitHub** em um repositório público.
- Inclua no **README**:
    - Passos para rodar o projeto;
    - Dependências utilizadas.

---

## **Observações**
- Se a API estiver offline, utilize os arquivos `.json` incluídos no projeto para simular as requisições.

---

## **Diferenciais**
- Uso de **React Hooks** e **React Router**.
- Componentização reutilizável.
- Uso de **bibliotecas de UI** (Material UI, Chakra UI, Tailwind CSS, etc.).