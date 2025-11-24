# InfoMundo - Explorador de Países

O **InfoMundo** é uma aplicação web interativa (SPA) que permite explorar informações detalhadas sobre países de todo o mundo. O projeto consome dados da [REST Countries API](https://restcountries.com/) e oferece funcionalidades de busca, filtragem, favoritos e comparação de dados demográficos.

## Funcionalidades

- **Exploração Global:** Visualize cartões com bandeiras e informações básicas de todos os países.
- **Busca e Filtros:** Pesquise por nome ou filtre por continentes (regiões).
- **Favoritos:** Salve países para acesso rápido (persitência local).
- **Comparação:** Selecione até 4 países para comparar população e área territorial em gráficos interativos.
- **Design Responsivo:** Interface moderna e adaptável para desktop e mobile.

## Tecnologias Utilizadas

- **React** (Vite + TypeScript)
- **Tailwind CSS** (Estilização)
- **Recharts** (Gráficos de comparação)
- **Lucide React** (Ícones)
- **REST Countries API** (Dados)

## Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/infomundo.git
   ```

2. Entre na pasta do projeto:
   ```bash
   cd infomundo
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

## Deploy no Vercel

Este projeto está configurado para deploy contínuo.
1. Crie um novo projeto no [Vercel](https://vercel.com).
2. Importe este repositório do GitHub.
3. O Vercel detectará automaticamente as configurações do Vite (`npm run build`).
4. Clique em **Deploy**.

---
Desenvolvido como projeto de portfólio.
