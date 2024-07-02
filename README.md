# HelloWorldLightningWebComponent

Este repositório contém um Lightning Web Component (LWC) simples que exibe "Hello World" na página inicial do Salesforce.

## Índice

- [Visão Geral](#visão-geral)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contato](#contato)

## Visão Geral

O HelloWorldLightningWebComponent é um exemplo básico de como criar e exibir um componente Lightning Web Component no Salesforce.

## Requisitos

- Conta no Salesforce com permissões de desenvolvedor.
- Salesforce CLI instalada.

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/HelloWorldLightningWebComponent.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd HelloWorldLightningWebComponent
    ```

3. Autentique-se no Salesforce CLI:
    ```bash
    sfdx force:auth:web:login
    ```

4. Crie uma nova organização:
    ```bash
    sfdx force:org:create -s -f config/project-scratch-def.json
    ```

5. Instale o componente:
    ```bash
    sfdx force:source:push
    ```

6. Abra a organização no navegador:
    ```bash
    sfdx force:org:open
    ```

7. Adicione o componente "HelloWorld" à página inicial:
    - Navegue até a página inicial no Salesforce.
    - Edite a página com o App Builder.
    - Arraste e solte o componente "HelloWorld" na página.
    - Salve e ative as alterações.

## Uso

Após a instalação, o componente "Hello World" estará visível na página inicial do Salesforce.

## Contato

Para mais informações, entre em contato através do email: [dev.alvarojordao@gmail.com](mailto:dev.alvarojordao@gmail.com).

---

Obrigado por utilizar o HelloWorldLightningWebComponent!
