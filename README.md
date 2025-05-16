"#Formulario EPI - CCO | Emlurb" 

## Sobre o Projeto

Este é um projeto de formulário para controle de EPI (Equipamentos de Proteção Individual) no âmbito da CCO | Emlurb. O projeto é composto por três diretórios principais:

### Estrutura do Projeto

1. **API**  
    Diretório responsável pela API desenvolvida em **Spring Boot**, que fornece os serviços backend para o sistema.

2. **form-fiscais-epi-mobile**  
    Diretório do aplicativo mobile desenvolvido em **React Native (Expo Bare Minimum)**, utilizado para coleta de dados em campo.

3. **front-web**  
    Diretório da interface web desenvolvida em **Angular 21**, utilizada para visualização e gerenciamento dos dados.

### Cores Primárias

As cores primárias utilizadas no projeto são:  
- **Azul** (#0000FF)  
- **Branco** (#FFFFFF)  
- **Laranja** (#FFA500)

### Objetivo

O objetivo deste projeto é facilitar o controle e a gestão de EPIs, permitindo que fiscais registrem informações diretamente no aplicativo mobile, enquanto os dados podem ser acessados e gerenciados através da interface web.

### Como Executar

1. **API**  
    - Certifique-se de ter o **Java 21** instalado.  
    - Navegue até o diretório `API` e execute o comando:  
      ```bash
      ./mvnw spring-boot:run
      ```

2. **form-fiscais-epi-mobile**  
    - Certifique-se de ter o **Node.js** e o **Expo CLI** instalados.  
    - Navegue até o diretório `form-fiscais-epi-mobile` e execute:  
      ```bash
      npm install
      expo start
      ```

3. **front-web**  
    - Certifique-se de ter o **Node.js** instalado.  
    - Navegue até o diretório `front-web` e execute:  
      ```bash
      npm install
      ng serve
      ```

### Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

### Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.