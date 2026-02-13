# Chat


Uma interface de chat moderna e futurista com estética **Glassmorphism**, desenvolvida para proporcionar uma experiência visual imersiva e limpa.

## Características Visuais

* **Glassmorphism:** Utiliza `backdrop-filter: blur()` para criar um efeito de vidro fosco no container principal.
* **Fundo Dinâmico:** Um background animado com gradientes e desfoque (`blur`) que se move suavemente, simulando uma nebulosa.
* **UI Responsiva:** Estrutura flexível utilizando **CSS Flexbox** para garantir que as mensagens e áreas de entrada se ajustem corretamente.
* **Micro-interações:** O botão de envio possui efeitos de transição, escala e rotação no hover para melhorar o feedback do usuário.

## Detalhes do Design

### Glassmorphism & Cores
O projeto utiliza variáveis CSS para manter a consistência:
* **Accent Color:** `#7000ff` (Roxo elétrico) para mensagens enviadas e elementos de destaque.
* **Glass Background:** Transparência de 12% com bordas sutis para separar os elementos do fundo dinâmico.

### Layout de Mensagens
As bolhas de chat possuem bordas arredondadas assimétricas:
* **Incoming:** Bordas arredondadas exceto no canto inferior esquerdo.
* **Outgoing:** Bordas arredondadas exceto no canto inferior direito, acompanhadas de um `box-shadow` neon.

## Estrutura do Projeto

* `index.html`: Estrutura semântica contendo o header (info do usuário), section (área de mensagens) e footer (entrada de texto).
* `style.css`: Lógica de estilização, incluindo as animações `@keyframes move` para o fundo e o design do container de vidro.

## Tecnologias

* HTML5
* CSS3 (Custom Properties, Flexbox, Keyframes, Backdrop-filter)

---
*Nota: Este projeto é focado no Front-end UI e pode ser integrado facilmente com APIs de chat ou LLMs.*

<img width="953" height="773" alt="Image" src="https://github.com/user-attachments/assets/868c32f7-ce3c-4640-8fb1-45bffaae3411" />
