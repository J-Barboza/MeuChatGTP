# Configurando o Ambiente de Desenvolvimento para o MeuChatGPT

## Pré-requisitos
1. **Node.js e NPM**: Certifique-se de que o Node.js e o npm (gerenciador de pacotes Node) estão instalados em seu sistema. [Baixe aqui](https://nodejs.org).

2. **React Native CLI ou Expo CLI**: Instale o React Native CLI globalmente no seu computador com o comando `npm install -g react-native-cli`. Alternativamente, use o Expo CLI com o comando `npm install -g expo-cli`.

## Configuração do Projeto
1. **Crie um novo projeto React Native**: Use o CLI para iniciar um novo projeto React Native com o comando `npx react-native init MeuChatGPT` ou `expo init MeuChatGPT`.

2. **Navegue para a pasta do projeto**: Use o comando `cd MeuChatGPT`.

3. **Instale a biblioteca Axios**: Utilize Axios para fazer solicitações HTTP à API da OpenAI. Instale com o comando `npm install axios`.

4. **Instale a biblioteca React-Native-Dotenv**: Proteja sua chave de API, armazenando-a em um arquivo `.env` com esta biblioteca. Instale com o comando `npm install react-native-dotenv`.

5. **Instale bibliotecas para gerenciamento de estado (opcional)**: Para gerenciar o estado do token da API e as mensagens do chat, considere usar uma biblioteca como Redux ou MobX.

6. **Instale bibliotecas de UI (opcional)**: Para um design minimalista e eficiente, considere utilizar uma biblioteca de componentes de interface do usuário, como React Native Elements ou NativeBase.

7. **Configuração do ESLint e Prettier**: Garanta a qualidade do código configurando o ESLint e o Prettier em seu projeto. O ESLint ajudará a identificar problemas, enquanto o Prettier formatará automaticamente seu código para garantir consistência e legibilidade.

Agora que seu ambiente de desenvolvimento está configurado, você está pronto para começar a codificar seu aplicativo!
