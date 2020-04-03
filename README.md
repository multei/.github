# Multei!

O Multei! é uma plataforma que permite que a denúncia anônima de estacionamento irregular em vagas preferenciais para pessoas com deficiência. A denúncia é feita através do envio de duas fotos do veículo e da localização da vaga onde a infração aconteceu.

## Elevator Pitch

Para pessoas com deficiência e suas acompanhantes que precisam de vagas preferenciais, o Multei é uma plataforma que permite a realização de denúncias de uso indevido das vagas por pessoas sem credencial e, diferentemente de aplicativos do tipo existente no mercado, nosso produto não exige a instalação de aplicativo, realização de cadastro identificado ou entrada de informações sobre o veículo para que a denúncia seja feita.

## Como funciona?

A ideia é que essa denúncia aconteça da forma mais simples possível: você tira uma foto de frente e outra da traseira do carro e confirma a denúncia com a sua localização. Depois, usamos inteligência artificial para detectar o modelo, marca, cor e até a placa do carro, necessários para a denúncia. 

As denúncias, após serem feitas pelas usuárias, serão repassadas para os órgãos competentes. No início, no MVP, esse repasse acontece de forma manual. O foco é na denúncia do uso indevido de vagas reservadas para pessoas com deficiência mas, no futuro, o app também poderá abranger vagas reservadas para pessoas idosas (com mais de 60 anos).

## Desafio atual

Nosso maior desafio atual é finalizar o fluxo de denúncia, que envolve tarefas de back-end e front-end.

## Recursos técnicos

- APIs de terceiros: Google Maps API, OpenALPR;
- CI: CircleCI e Travis;
- Cloud Platforms: Heroku, Google Cloud e Netlify;
- Repositórios: GitHub.com/multei;
- Management: GitHub Projects;
- Team Communication: inicialmente Chat e E-mail.

## Tecnologias usadas

- Back-end: Express, Multer, Google Cloud Storage API, Node.js, JavaScript;
- Front-end: Gatsby, Material UI, Muy, Metax, React, JavaScript, Jest, Cypress (testes e2e);
- Mobile: React Native, Muy, JavaScript, Jest, Detox (para testes end-to-end);
- Reconhecimento de veículos e placas: Node.js, Express, Rollup, OpenALPR, JavaScript.

## Frentes de produto

1. Estimular a coleta de denúncias;
2. Educar pessoas que não sabem;
3. Informar autoridades.

---

## Resources

- [Code of Conduct](CODE_OF_CONDUCT.md);
- [License](LICENSE);

## Contributing Guidelines

- [English](CONTRIBUTING.md);
- [Portuguese (Brazil)](CONTRIBUTING.pt-br.md).
