# Projeto Automação com Appium Android

Este projeto é um tutorial baseado no trabalho de Elias Nogueira, especialista em qualidade de software e automação de testes. Ele demonstra como configurar e executar testes automatizados em dispositivos Android utilizando o Appium.

## Pré-requisitos

- Node.js instalado
- Appium Server instalado
- Android SDK configurado
- Dispositivo Android ou emulador configurado
- Java JDK instalado

## Configuração do Projeto

1. Clone este repositório:
    ```bash
    git clone <url-do-repositorio>
    ```
2. Instale as dependências:
    ```bash
    npm install
    ```
3. Configure as variáveis de ambiente para o Android SDK:
    ```bash
    export ANDROID_HOME=/caminho/para/android-sdk
    export PATH=$ANDROID_HOME/platform-tools:$PATH
    ```

## Estrutura do Projeto

- `tests/`: Contém os testes automatizados.
- `config/`: Configurações do Appium e do dispositivo.
- `package.json`: Dependências do projeto.

## Executando os Testes

1. Inicie o Appium Server:
    ```bash
    appium
    ```
2. Execute os testes:
    ```bash
    npm test
    ```

## Referências

- [Elias Nogueira - Blog](https://eliasnogueira.com)
- [Documentação do Appium](https://appium.io)

## Licença

Este projeto é apenas para fins educacionais e segue as diretrizes de uso justo.
