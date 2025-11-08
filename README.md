# 💻 Projeto: Desenvolvimento de Portfólio Pessoal

![Capa do Projeto](./img/fotomonitor.png)

Este projeto foi desenvolvido como prática de **HTML5** e **Tailwind CSS**, com o objetivo de aplicar conceitos de **layout responsivo**, **componentização com classes utilitárias** e **organização de seções em uma página web**.  
O resultado final é um site que simula um portfólio pessoal moderno e funcional.

---

## 🧠 Objetivos do Projeto

- Aprender a estruturar páginas utilizando **HTML semântico**  
- Utilizar o **Tailwind CSS** para estilizar e tornar o site **responsivo**  
- Praticar conceitos de **Flexbox**, **Grid** e **design responsivo**  
- Organizar o projeto de forma modular (separando HTML, CSS e imagens)  
- Compreender como o **Tailwind gera o CSS final** via terminal  

---

## ⚙️ Ferramentas Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)

---

## 🧩 Estrutura do Projeto

📁 src/
┣ 📜 index.html # Página principal do portfólio
┣ 📜 input.css # Arquivo base do Tailwind
📁 img/
┣ 🖼️ fotoJoao.jpg # Foto de perfil
┣ 🖼️ fotomonitor.png # Captura do projeto
┣ 🖼️ fotocaderno.jpg
┣ 🖼️ fotocelular.jpg
┗ 🖼️ logo.png
📜 output.css # CSS gerado pelo Tailwind

yaml
Copiar código

---

## 🧱 Conceitos Aplicados

- **Flexbox e Grid Layout** → para alinhar e distribuir elementos nas seções  
- **Classes responsivas do Tailwind** (`sm:`, `md:`, `lg:`) → para adaptar o layout em diferentes telas  
- **Utilização de `object-cover`, `rounded-full`, `drop-shadow-lg`** → para manipular imagens e sombras  
- **Uso de `npx tailwindcss` com `--watch`** → para gerar o CSS automaticamente durante o desenvolvimento  

---

## 🧭 Como Executar

```bash
# Instalar o Tailwind (caso não tenha)
npm install -D tailwindcss

# Gerar o CSS final
npx tailwindcss -i ./src/input.css -o ./output.css --watch
Depois, basta abrir src/index.html no navegador ou usar o Live Server do VS Code.

📚 O que aprendi
Durante o desenvolvimento, pude:

Entender melhor a estrutura e sintaxe do Tailwind CSS

Criar um layout totalmente responsivo sem escrever CSS manual

Aplicar componentização com classes utilitárias

Melhorar a organização de pastas e arquivos em um projeto web

Integrar HTML, CSS e imagens de forma consistente

🧠 Conclusão
O projeto foi uma ótima oportunidade para consolidar conhecimentos sobre HTML, CSS utilitário e design responsivo.
Além disso, serviu como base para futuros projetos mais complexos, como a construção de um portfólio profissional com React e Tailwind CSS.

🖤 Desenvolvido por João Pedro Sabino — Projeto de aprendizado em Front-End
