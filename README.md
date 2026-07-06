# 🎲 Gerador de Cards Matemáticos - Corrida dos 100 Pontos

Este é um projeto interativo baseado em ambiente web voltado para professores e educadores. A ferramenta automatiza a criação de recursos didáticos gamificados para o ensino de expressões numéricas, permitindo gerar baralhos aleatórios e cartelas de pontuação perfeitamente otimizados para impressão em formato A4.

---

## 🚀 Funcionalidades Principais

* **Geração Aleatória**: subtopico algoritmo inteligente que cria expressões matemáticas personalizadas por nível, subtopico garantia de resultados estritamente positivos, subtopico validação de divisões exatas.
* **Customização Visual**: subtopico três conjuntos de ilustrações vetoriais integradas (Monstrinhos Felizes, Animais Divertidos e Espaço Sideral), subtopico ajuste de opacidade em tempo real (15%, 30% e 50%) para economia de toner.
* **Rastreamento e Segurança**: subtopico sistema de identificação por códigos alfanuméricos de lote (ex: `#A1B3`) gerados dinamicamente para correlacionar as cartas impressas ao gabarito do professor.
* **Impressão Inteligente**: subtopico CSS Paged Media configurado para folhas A4, subtopico botões dedicados para separar a impressão do material do professor (Cartas + Gabarito) do material dos estudantes (Tabelas).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estruturação semântica das páginas de impressão e painel de controle.
* **CSS3**: Grid layout exato para evitar quebras indesejadas, além de estilização responsiva e regras de `@media print`.
* **JavaScript (Vanilla)**: Motores lógicos para geração de equações matemáticas dentro de limites numéricos predefinidos e manipulação dinâmica de SVGs.

---

## 🎮 Dinâmica do Jogo: Corrida dos 100 Pontos

**Objetivo**: Ser o primeiro jogador a atingir 100 pontos, preenchendo os 20 pentágonos da sua cartela de pontuação (cada pentágono preenchido vale 5 pontos).

### **Preparação**:
1. Acesse o gerador, selecione o tema visual e a opacidade desejada.
2. Clique em **Gerar Novas Expressões** para criar um lote exclusivo.
3. Imprima as cartas e o gabarito (para uso exclusivo do professor).
4. Imprima as tabelas de pontuação na quantidade necessária para os alunos.
5. Recorte as 16 cartas do monte e coloque-as viradas para baixo no centro da mesa.

### **Como Jogar**:
* Os alunos jogam em duplas ou pequenos grupos, revezando os turnos.
* Na sua vez, o jogador compra a carta do topo:
    * **Carta Coringa**: Garante os pontos indicados gratuitamente. O aluno avança o equivalente na cartela.
    * **Carta de Expressão**: O aluno deve resolver a expressão numérica no seu quadro de registro. Se o resultado estiver correto (validado pelo professor por meio do código do lote no gabarito), ele ganha os pontos do *badge* da carta e pinta os pentágonos correspondentes. Se errar, não pontua.
* O jogo termina imediatamente quando o primeiro estudante conseguir colorir todos os 20 pentágonos (completando 100 pontos).

---

## 📦 Como Executar o Projeto

1. Baixe o arquivo principal `index.html` (ou o nome do arquivo salvo).
2. Dê um duplo clique no arquivo para abri-lo em qualquer navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
3. Não é necessário instalar nenhuma dependência, realizar compilações ou possuir conexão ativa com a internet. O projeto funciona de forma 100% offline.

---

## 📝 Licença

Este projeto é de uso livre para fins educacionais e pedagógicos. Sinta-se à vontade para clonar, modificar e distribuir novas versões em sua comunidade escolar.
