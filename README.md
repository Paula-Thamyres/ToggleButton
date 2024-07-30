# ViaCep Android App

![Badge Status](https://img.shields.io/badge/status-active-brightgreen)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?logo=android-studio&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)

## Descrição

O ViaCep Android App é uma aplicação desenvolvida em Kotlin que consome a API pública ViaCep para buscar informações de endereços brasileiros a partir do CEP informado pelo usuário. A aplicação utiliza a arquitetura MVC (Model-View-Controller) para organizar o código e facilitar a manutenção e escalabilidade.

### GIF de Demonstração
![GIF do projeto](https://github.com/rfemina/Via-Cep/blob/master/viaCep-gif.gif)

### YouTube
[![Assista ao vídeo](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/9In1lbcDZew)

### Arquivo APK
[![Arquivo APK](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/rfemina/Via-Cep/blob/master/ViaCep.apk)

## Índice

- [Instalação](#instalação)
- [Uso](#uso)
- [Arquitetura](#arquitetura)
- [Objetivos](#objetivos)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Instalação

Siga os passos abaixo para configurar e rodar o projeto em sua máquina local.

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/Via-Cep.git
    cd Via-Cep
    ```

2. Abra o projeto no Android Studio:
    - File -> Open -> Selecione a pasta do projeto

3. Sincronize as dependências do Gradle:
    - Android Studio geralmente faz isso automaticamente, mas você pode forçar a sincronização clicando em `Sync Project with Gradle Files`.

4. Execute o projeto:
    - Conecte um dispositivo Android ou inicie um emulador.
    - Clique em `Run` ou use o atalho `Shift + F10`.

## Uso

1. Abra o aplicativo no seu dispositivo Android.
2. Digite um CEP válido no campo de texto.
3. Clique em "Buscar".
4. O endereço correspondente ao CEP será exibido na tela.

## Arquitetura

O projeto segue a arquitetura MVC (Model-View-Controller), entretanto com as nomenclaturas alteradas:

- **Model:** Contém a lógica de dados e as classes de modelo.
- **Ui:** Responsável pela interface do usuário.
- **Repository:** Gerencia a comunicação entre o Model e a View.
- **Api:** Interface para consumo e conversão do arquivo em Json 

### Estrutura de Pastas

```markdown
- src/
  - main/
    - java/
      - com/projetosrafaelfemina/viacep/
        - api/
          - Api.class
        - model/
          - Adress.class
        - repository/
          - CepRepository.class
        - ui/
          - ActivityUtils.class
      - MainActivity.class
    - res/
      - layout/
        - activity_main.xml
```
## Objetivos

Objetivo Principal:

Permitir que os usuários busquem informações de endereços a partir do CEP.

Requisitos:

  - Consumir a API ViaCep.
  - Exibir informações de endereço de maneira clara.
  - Manter uma arquitetura organizada (MVC).

## Tecnologias Utilizadas
  - Kotlin
  - Android Studio
  - Retrofit - Para consumo da API
  - Gson - Para parseamento de JSON
  - ViaCep API


## Contribuição
Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

  - Faça um fork do projeto
  - Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
  - Commit suas mudanças (git commit -m 'Add some AmazingFeature')
  - Push para a branch (git push origin feature/AmazingFeature)
  - Abra um Pull Request


## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

## Contato

    - Nome: Paula Thamyres da Silva Femina
    - E-mail: paula.arthamys@gmail.com
    - Link do Projeto: https://github.com/Paula-Thamyres/ToggleButton/
    - Linkedin: https://www.linkedin.com/in/paula-femina-87044796/
