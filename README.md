# Credit Transfers Files

Aplicativo Android com WebView para transferência de arquivos, login, upload/download e interface web embutida.

## Repositório

- GitHub: https://github.com/callonlogin-ops/credit-transfers-files

## Estrutura do projeto

- `app/` — módulo Android principal
- `app/src/main/assets/index.html` — interface web embutida
- `app/src/main/java/.../MainActivity.java` — WebView + integração Android
- `app/src/main/res/` — recursos do app

## Como abrir

1. Abra o projeto no Android Studio.
2. Sincronize o Gradle.
3. Escolha um emulador ou dispositivo físico.
4. Execute o app.

## Funcionalidades

- Login com formulário simples
- WebView com carregamento de interface local (`index.html`)
- Upload de arquivos pela WebView
- Download de arquivos em dispositivo
- Suporte a arquivos em Android via `WebChromeClient`
- Navegação em HTTPS/HTTP local com configuração de rede

## Observação

Este é um projeto base funcional para Android/HTML/JavaScript, pronto para extensões e customização.
