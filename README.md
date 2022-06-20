# Desafio Front-end Júnior

Seja bem-vindo! Este desafio foi projetado para avaliar a sua capacidade técnica como candidato.

Crie um aplicativo react com um menu superior contendo 2 links: "Lista de gatos" e "Formulário"

O link "Lista de gatos" deve direcionar a aplicação para uma rota que:
- Deve requisitar uma lista de tags no endereço: https://cataas.com/api/tags
- As tags deverão ser exibidas em forma de cards expansíveis.
- No título de cada card deve aparecer o nome da tag.
- Quando clicar no titulo do card, o corpo dele deve aparecer de forma a se expandir abaixo do título.
- Dentro do corpo do card deve aparecer uma lista dos ids obtidos como resposta do endereço https://cataas.com/api/cats, cujas a lista de tags contenha a tag do card selecionado.

![image](https://user-images.githubusercontent.com/6603813/120489184-d1a52c00-c38d-11eb-8cae-d281fc76ec92.png)

O link "Formulário" deve direcionar a aplicação para uma rota que:
- Exibe um formulário de cadastro em 3 etapas
- A primeira etapa deve solicitar:
	- Email (obrigatório)
	- Senha (obrigatório)
	- Confirmação de senha (obrigatório)
- A segunda etapa deve solicitar:
	- Nome (obrigatório)
	- Sobrenome (obrigatório)
	- Data de nacimento
- A terceira etapa deve solicitar:
	- Endereço completo (obrigatório)
- As etapas devem ser mostradas uma de cada vez, com abas para que o usuário alterne livremente entre elas
- Cada etapa precisa necessariamente ser escrita em um React Component separado
- Em cada etapa deve haver um botão de avançar para a próxima etapa
- Em todas as estapas o botão de enviar deve estar visível, mas ficará desabilitado até que todo o cadastro das 3 abas esteja concluído
- Caso haja algum erro de formulário em alguma etapa, a aba daquela etapa deve ter um indicador visual de erro
- Quando preencher uma etapa corretamente, a aba daquela etapa deve ter um indicador visual de concluída
- Quando todas as etapas forem preenchidas corretamentes e o usuário clicar em "enviar", deve aparecer uma modal de confirmação de sucesso na tela.

![image](https://user-images.githubusercontent.com/6603813/120489206-d7027680-c38d-11eb-9a52-a95aa640c905.png)

Você é livre para escolher os estilos visuais, fontes e cores.

O nosso objetivo é avaliar sua capacidade de lidar com multiplas requisições, organizar dados de fontes assíncronas e trabalhar com validações de formulários complexos.

Crie o seu projeto como um repositório público do github e nos envie o link.
