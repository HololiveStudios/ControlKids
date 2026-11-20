# ControlKids - Children Control PWA

## 1. Objetivo e Finalidade
Progressive Web App (PWA) para acompanhamento parental, controle de limites e gestão de tempo de tela de crianças.

## 2. Tecnologias Utilizadas
- React, TypeScript, Vite, Tailwind CSS, Firebase, Framer Motion, date-fns, Lucide React, PWA

## 3. Arquitetura e Estrutura de Diretórios
Aplicação PWA com React e Vite, integrada ao Firebase para sincronização em nuvem e persistência de dados em tempo real. Interface animada com Framer Motion.

## 4. Principais Arquivos e Responsabilidades
- `src/App.tsx`: Fluxos centrais de controle e monitoramento infantil.
- `firebase.json`: Configurações de hosting e regras de dados Firebase.
- `vite.config.ts`: Configurações do Vite e capacidades PWA.

## 5. Funcionalidades Identificadas
- Monitoramento e controle de atividades de crianças
- Suporte a instalação como aplicativo PWA offline-first
- Animações e interações táteis fluidas com Framer Motion e react-use-gesture
- Sincronização em nuvem com Firebase

## 6. Como Compilar ou Executar
```bash
npm install
npm run dev
# Build PWA: npm run build
```

## 7. Estado Atual do Projeto
**Completo**

## 8. Pendências e Limitações Identificadas
Ajuste de permissões e regras de segurança granulares no Firebase Firestore.
