#  Nearby

**Nearby** é um aplicativo mobile de clube de benefícios focado em oferecer cupons de desconto exclusivos para você utilizar em estabelecimentos próximos à sua localização. Descubra vantagens incríveis na sua região de forma rápida, fácil e interativa!

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e bibliotecas do ecossistema mobile:

- **[React Native](https://reactnative.dev/)**: Framework para desenvolvimento de aplicativos móveis nativos utilizando React.
- **[Expo](https://expo.dev/)**: Plataforma que facilita o desenvolvimento, build e deploy de aplicações React Native.
- **[Expo Router](https://docs.expo.dev/router/introduction/)**: Roteamento baseado em arquivos para React Native, semelhante à estrutura web moderna.
- **[TypeScript](https://www.typescriptlang.org/)**: Superset do JavaScript que adiciona tipagem estática que traz mais segurança ao código.
- **[React Native Maps](https://github.com/react-native-maps/react-native-maps) & [Expo Location](https://docs.expo.dev/versions/latest/sdk/location/)**: Integração de mapas e captura em tempo real da geolocalização do usuário para encontrar os estabelecimentos vizinhos.
- **[Expo Camera](https://docs.expo.dev/versions/latest/sdk/camera/)**: Para iteração visual e leitura de códigos.
- **[@gorhom/bottom-sheet](https://ui.gorhom.dev/components/bottom-sheet/)**: Componente altamente customizável de menus em formato "Bottom Sheet".
- **[Axios](https://axios-http.com/)**: Cliente HTTP utilizado para consumir as APIs e serviços do backend.

## ⚙️ Como Executar o Projeto

### Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (versão LTS recomendada)
- [Git](https://git-scm.com/)
- Aplicativo **Expo Go** instalado no seu dispositivo físico (iOS ou Android) ou um emulador devidamente configurado (Android Studio ou Xcode).

### Passos para rodar localmente

1. Clone este repositório e acesse seu diretório:
```bash
git clone https://github.com/seu-usuario/nearby.git
cd nearby
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor de desenvolvimento do Expo:
```bash
npm start
# ou
npx expo start
```

4. **Abra o aplicativo:**
   - **No dispositivo físico:** Abra o app **Expo Go** e escaneie o QR Code que será exibido no terminal.
   - **No Emulador Android:** Aperte a tecla `a` no terminal.
   - **No Simulador iOS:** Aperte a tecla `i` no terminal.

## 📝 Scripts Disponíveis

No diretório do projeto, você poderá executar:

- `npm start`: Inicia o projeto com o servidor Expo local.
- `npm run android`: Executa a compilação nativa para rodar no Android (Requer ambiente configurado).
- `npm run ios`: Executa a compilação nativa para rodar no iOS (Requer Mac com Xcode).
- `npm run web`: Inicializa o app na versão web caso seja suportado.
- `npm run test`: Roda os testes configurados na aplicação com Jest.
