# Ionic Angular 12

Projeto Ionic configurado com Angular 12.

## Versões

- Angular: 12.2.16
- Ionic: 6.7.5
- TypeScript: 4.3.5
- Node: 16.x

## Instalação

```bash
npm install
```

## Executar

```bash
# Desenvolvimento
npm start

# ou com Ionic CLI
npx ionic serve
```

## Build

```bash
npm run build
```

## Estrutura

```
ionic-angular12/
├── src/
│   ├── app/
│   │   ├── home/              # Página inicial
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   └── app-routing.module.ts
│   ├── assets/                # Recursos estáticos
│   ├── environments/          # Configurações de ambiente
│   ├── theme/                 # Temas e variáveis CSS
│   ├── global.scss           # Estilos globais
│   ├── index.html
│   ├── main.ts
│   └── polyfills.ts
├── angular.json              # Configuração Angular
├── ionic.config.json         # Configuração Ionic
├── package.json
└── tsconfig.json            # Configuração TypeScript
```

## Notas

- O projeto usa Angular 12 com Ionic 6 para melhor compatibilidade
- TypeScript 4.3.x é a versão máxima suportada pelo Angular 12
- RxJS 6.6.x (Angular 12 não suporta RxJS 7+)
