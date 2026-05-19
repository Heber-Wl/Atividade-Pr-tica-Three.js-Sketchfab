# Atividade Prática — Visualizador 3D (Three.js + Sketchfab)

Este projeto consiste em uma aplicação web interativa desenvolvida com **Three.js** que carrega e renderiza um modelo 3D em tempo real diretamente no navegador. O usuário pode manipular livremente a câmera para visualizar o objeto de qualquer ângulo.

---

## 📦 Informações do Modelo 3D
* **Nome do Modelo:** FREE 1975 Porsche 911 (930) Turbo
* **Link de Origem:** [Sketchfab - Porsche 911](https://sketchfab.com/3d-models/free-1975-porsche-911-930-turbo-8568d9d14a994b9cae59499f0dbed21e)
* **Licença:** CC Attribution (Livre de restrições de direitos autorais para fins educacionais)

---

## 🎮 Controles da Cena (OrbitControls)
* **Botão Esquerdo do Mouse (ou arrastar com 1 dedo no touch):** Rotaciona a câmera ao redor do carro.
* **Scroll do Mouse (ou gesto de pinça no touch):** Controla o Zoom (aproxima ou afasta).
* **Botão Direito do Mouse (ou arrastar com 2 dedos no touch):** Ativa o Pan (desloca a câmera lateralmente ou verticalmente).

---

## 🚀 Como Executar o Projeto Localmente

Os navegadores modernos bloqueiam o carregamento de arquivos 3D (`.glb`/`.gltf`) diretamente do sistema de arquivos local por motivos de segurança (Erro de CORS). Portanto, **é obrigatório rodar o projeto por meio de um servidor local**.

Siga o passo a passo abaixo após clonar o repositório:

### Passo 1: Clonar o Repositório
Abra o seu terminal e clone este repositório para a sua máquina:

---

### Passo 2: Organizar a Pasta de Modelos
Certifique-se de que existe uma pasta chamada modelos na raiz do seu projeto.

O arquivo do modelo baixado do Sketchfab deve ser inserido dentro dela com o nome exatamente igual a modelo.glb.

Estrutura esperada: meu-projeto/modelos/modelo.glb

---

### Passo 3: Ajustar o Caminho no Código
Abra o arquivo index.html e verifique a variável do caminho do modelo (variável const modelPath). Ela deve apontar corretamente para o arquivo:

---

### Passo 4: Inicializar um Servidor Local

**Usando o VS Code (Mais Fácil)**
* Abra a pasta do projeto no Visual Studio Code.
* Instale a extensão chamada Live Server (caso ainda não tenha).
* Abra o arquivo index.html.
* Clique com o botão direito em qualquer lugar do código e selecione "Open with Live Server".

O navegador abrirá automaticamente no endereço http://127.0.0.1:5500.
