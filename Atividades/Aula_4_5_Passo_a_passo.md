Aqui está o passo a passo da **Aula 4 e 5** com base nas screenshots fornecidas:

---

## Passo a Passo: Aula 4 e 5 - Benevid

### 1. Integração do Serviço de API (Tavily) com Langflow
Nesta etapa, foi feita a integração do serviço Tavily API ao Langflow. Confira a imagem abaixo para o processo visual:
![Integração serviço API de Busca](image-5.png)

---

### 2. Criação do Fluxo de Input de Pesquisa
Foi criado um fluxo de input de chat que permite a inserção de prompts para realizar pesquisas na API integrada.
![Criação do fluxo de input pesquisa](image-6.png)

---

### 3. Adicionando o Componente "Parse Data"
O componente de parse data foi adicionado ao fluxo, permitindo manipular as respostas da API.
![Parse Data adicionado ao fluxo](image-7.png)

---

### 4. Ajuste no Código: Parse Data como Corpo da Mensagem
O código foi ajustado para que o **parse data** seja utilizado como o corpo da mensagem para a pesquisa.
![Código inserido e ajustado](image-8.png)

---

### 5. Comportamento Esperado da Pesquisa na API
Aqui está a demonstração de como a API deve se comportar ao ser executada.
![Prompt de busca e resultado](image-9.png)
![Comportamento da execução (XML)](image-10.png)

---

### 6. Uso da API do Groq como Método de Pesquisa e Output da Mensagem
Foi utilizada a API do Groq como método de pesquisa, e aqui está o resultado gerado.
![API Groq e output](image-11.png)

---

### 7. Configuração do Astra DB com API e Token
Foi configurada a API e o token da Astra DB dentro do fluxo. Abaixo, está a imagem demonstrando como foi feito:
![Token API e endpoint do Astra DB]({481ADEB6-C5CA-4A5C-9845-4BE02CEEF7CF}.png)

---

### 8. Configuração do Componente Astra DB para PDF
O fluxo foi configurado para fazer upload de arquivos PDF no banco de dados Astra DB. Veja a configuração completa:
![Configuração do Astra DB para PDF]({622304EA-2462-4FF9-9442-173EB2CB7833}.png)

---

### 9. PDF Após Parse no Banco Astra DB
Depois de rodar o fluxo e dividir o PDF no banco de dados, o resultado foi visualizado conforme abaixo:
![Resultado PDF após parse no banco Astra DB]({6AB2CBAA-C882-491E-949E-C4FA1F3D0CDA}.png)

---

### 10. Definição da API e Configuração Inicial do Groq
Foi definida a API e as configurações iniciais do modelo Groq, conforme ilustrado na imagem:
![Configuração API e modelo Groq]({BEE40166-83CC-405F-BACC-4E998FEA95DD}.png)

---

### 11. Pesquisa no Astra DB Utilizando PDF
Nos primeiros testes, foi feito uma pesquisa dentro do PDF que já estava no banco Astra DB, buscando pela palavra "variância".
![Primeiros testes com PDF no Astra DB](image-12.png)

---

### 12. Resultado da Pesquisa de "Variância" no PDF
Aqui está o ponto exato no PDF onde a palavra "variância" foi encontrada.
![Palavra 'variância' no PDF]({59030106-4291-4B4E-A69C-AEBB4F6BBBC7}.png)

---

### 13. Integração do Mistral com Groq
Foi configurado um fluxo utilizando **Mistral** (API gerada no site) e **Groq** para realizar a pesquisa de palavras como mostrado anteriormente.
![Fluxo Mistral e Groq]({D1FFA34F-7DAA-4BEE-9676-6232E9948E4C}.png)

---

### 14. Fluxo do Crew AI
Durante a aula, foi apresentado o fluxo do **Crew AI**, que permite a formatação de notícias e pesquisas com agentes iterativos.
![Fluxo Crew AI]({8579FE6B-B15D-4066-BD7B-AAA77E138C6A}.png)

---

### 15. Exemplo de Prompt do Agente Humorista
Aqui está o exemplo de prompt do agente "Humorista", que formata as notícias com um tom mais humorístico.
![Exemplo do agente humorista]({91BEB5FA-DAD6-4CA9-8017-E1164EB63A0D}.png)

---

### 16. API Google Studio para Crew AI
Mostrando como a API do Google AI Studio foi obtida e utilizada no exemplo do Crew AI.
![API Google Studio]({E586C950-424F-413F-A8AA-838BC1A5F88D}.png)

---

### 17. Instalação do Docker e Dify no WSL
Foram seguidos os passos para instalar o **Docker** e o **Dify** no WSL.
![Instalação Docker e Dify no WSL]({7EE0FC06-301B-4A5A-A79D-820BBCE171CD}.png)

---

### 18. Conteúdo da Pasta Dify
Aqui está o conteúdo da pasta Dify, onde já contém o **nginx** configurado no arquivo **.env**.
![Conteúdo da pasta Dify]({F6B33B0B-FF86-4781-AED9-11AB27157B5B}.png)

---

### 19. Configuração da Porta do Nginx no Arquivo .env
A porta do **nginx** foi configurada para 8080 e 8443, e também foi definida a senha do administrador no arquivo **init**.
![Definição de porta no Nginx]({AF54C6E0-7214-48A1-B374-BF8D7B3D3BEF}.png)

---

### 20. Comando para Inicializar o Dify
Este é o comando utilizado para inicializar o **Dify** e baixar os componentes necessários.
![Comando Docker Compose]({19D89825-DA66-4DDC-B258-7209B7B4219F}.png)

---

### 21. Painel Inicial do Dify
Após a instalação, o **Dify** foi conectado ao PC, e o painel inicial foi visualizado.
![Painel inicial do Dify]({AB3C3438-9AC1-4050-ADB7-A759741F8958}.png)

---

Esses são os principais passos demonstrados durante a **Aula 4 e 5**.