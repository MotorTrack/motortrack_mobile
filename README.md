<div align="center">

<img src="https://img.shields.io/badge/React%20Native-0.81-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
<img src="https://img.shields.io/badge/Expo-54-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/>
<img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/Status-Concluído-22C55E?style=for-the-badge" alt="Status"/>

<br/>
<br/>

#  MotoTrack (Mobile)

**Gerencie suas motos, oficinas e histórico de manutenções em um só lugar.**

Aplicativo mobile desenvolvido com React Native + Expo para motociclistas que desejam centralizar o controle completo da vida útil de seus veículos.

</div>

***

## Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Executar](#-como-executar)
- [Segurança](#-segurança)
- [Equipe](#-equipe)

***

##  Sobre o Projeto

O **MotoTrack Mobile** é uma aplicação desenvolvida para auxiliar motociclistas no gerenciamento completo de suas motos. A ideia central é centralizar informações importantes, cadastro de veículos, histórico de manutenções e oficinas de confiança em uma única interface intuitiva.

O sistema suporta tanto manutenções **preventivas** quanto **corretivas**, permitindo ao usuário acompanhar custos, datas e descrições de todos os serviços realizados.

> Projeto desenvolvido para fins **educacionais e acadêmicos**.

***
## Equipe

Este projeto foi desenvolvido pela seguinte equipe:

| Nome | Matrícula |
|---|---|
| Pedro Henrique Jerônimo da Silva | 00000855155 |
| Ygor de Tárcio da Silva Ferreira | 00000855656 |
| Matheus Vinnycius Vasconcelos de Santana | 00000855216 |
| Ludmylla Dias de Souza Santos | 00000855172 |
| Echilin Taina de Oliveira Santos | 00000855327 |
| Maysa Clara Cavalcante da Silva | 00000855217 |
| Marcela Maria da Silva Dias | 00000853790 |

***

## Funcionalidades

###  Autenticação
- Cadastro de nova conta
- Login com JWT
- Logout seguro

###  Gerenciamento de Motocicletas
- Cadastrar nova moto
- Editar informações do veículo
- Remover moto da garagem
- Visualizar garagem completa

###  Gerenciamento de Manutenções
- Registrar nova manutenção (descrição, data, custo)
- Consultar histórico de serviços por veículo

###  Gerenciamento de Oficinas
- Cadastrar oficina
- Editar dados da oficina
- Remover oficina
- Listar todas as oficinas cadastradas

###  Informações Complementares
- Tela **Sobre** o projeto
- Tela **Equipe** com perfil dos integrantes

***

##  Tecnologias

| Camada | Tecnologia | Finalidade |
|---|---|---|
| Mobile UI | React Native + Expo | Base do aplicativo |
| Navegação | Expo Router | Roteamento baseado em arquivos |
| Componentes | React Native Paper | Biblioteca de UI Material Design |
| Estado Global | Zustand | Gerenciamento de estado leve |
| Requisições HTTP | Axios | Comunicação com a API |
| Cache & Sync | TanStack Query (React Query) | Gerenciamento de dados assíncronos |
| Linguagem | JavaScript ES6+ | — |

***

##  Estrutura do Projeto

```
mototrack-mobile/
│
├── app/
│   ├── index.js
│   ├── cadastro.js
│   ├── garagem.js
│   ├── manutencoes.js
│   ├── oficinas.js
│   ├── nova-moto.js
│   ├── editar-moto.js
│   ├── nova-oficina.js
│   ├── editar-oficina.js
│   ├── equipe.js
│   ├── perfil-equipe.js
│   └── sobre.js
│
├── src/
│   ├── api/
│   ├── store/
│   ├── services/
│   ├── hooks/
│   └── components/
│
├── assets/
│
├── app.json
├── package.json
└── README.md
```

***

##  Como Executar

### Pré-requisitos

Certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (v18 ou superior recomendado)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Aplicativo **Expo Go** no seu celular ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent) / [iOS](https://apps.apple.com/app/expo-go/id982107779))

***

### Passo a passo

**1. Clone o repositório**

```bash
git clone https://github.com/seu-usuario/mototrack-mobile.git
```

**2. Acesse a pasta do projeto**

```bash
cd mototrack-mobile
```

**3. Instale as dependências**

```bash
npm install
```

**4. Inicie o servidor de desenvolvimento**

```bash
npm start
# ou
npx expo start
```

***

### Rodando no Dispositivo Físico

1. Abra o aplicativo **Expo Go** no seu celular.
2. Com o servidor rodando, escaneie o **QR Code** exibido no terminal ou no navegador.
3. O aplicativo será carregado automaticamente no seu dispositivo.


***

###  Rodando no Emulador

Para rodar em um emulador Android ou simulador iOS, pressione as teclas abaixo após iniciar o servidor:

| Tecla | Ação |
|---|---|
| `a` | Abrir no emulador Android |
| `i` | Abrir no simulador iOS (macOS) |
| `w` | Abrir no navegador web |

***

##  Segurança

A autenticação do sistema utiliza **JWT (JSON Web Token)**:

- O token é gerado pelo backend no momento do login.
- Armazenado localmente e enviado no cabeçalho `Authorization: Bearer <token>` em todas as requisições autenticadas.
- O logout invalida o token no cliente, encerrando a sessão.

***



<div align="center">

Desenvolvido usando **React Native** e **Expo**

</div>