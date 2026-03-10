# 🎵 Modos de Ressonância em Tubos Sonoros

O **Modos de Ressonância em Tubos Sonoros** é uma aplicação web interativa criada para visualizar e compreender o comportamento das ondas estacionárias em tubos sonoros. O projeto combina animação, simulação física e reprodução sonora para mostrar como variam a pressão, o deslocamento das partículas de ar, a frequência e o comprimento de onda em tubos abertos e fechados.

## ✨ Funcionalidades

- Simulação visual de ressonância em tubos sonoros
- Alternância entre:
  - **tubo aberto**
  - **tubo fechado**
- Controle do número harmônico por meio de slider
- Exibição dinâmica de:
  - comprimento de onda
  - frequência
- Visualização simultânea de:
  - deslocamento das partículas de ar
  - variação de pressão
- Reprodução sonora do modo selecionado
- Diferença sonora entre tubo aberto e fechado:
  - onda senoidal para tubo aberto
  - onda quadrada para tubo fechado
- Restrição automática dos harmônicos inválidos em tubo fechado
- Seção explicativa sobre os fundamentos físicos da simulação
- Interface responsiva com visual limpo e didático

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Tailwind CSS**
- **Tone.js**
- **Canvas API**

## 🎯 Objetivo do Projeto

O projeto foi desenvolvido para fins didáticos, ajudando estudantes e professores a compreenderem conceitos fundamentais da acústica, especialmente o fenômeno da **ressonância em tubos sonoros** e a formação de **ondas estacionárias**.

A proposta é apresentar, de forma intuitiva, a relação entre teoria e visualização prática, tornando mais acessíveis conceitos como:

- frequência natural
- harmônicos
- comprimento de onda
- pressão sonora
- deslocamento de partículas
- diferença entre tubos abertos e fechados

## ⚙️ Como funciona

A aplicação considera:

- **Comprimento do tubo (L)** = 1,70 m
- **Velocidade do som (v)** = 343 m/s

Com base nesses valores, o sistema calcula automaticamente a frequência e o comprimento de onda do harmônico selecionado.

### Tubo aberto
Permite todos os harmônicos:

- n = 1, 2, 3, 4...

Fórmula utilizada:

`f(n) = (n · v) / 2L`

### Tubo fechado
Permite apenas harmônicos ímpares:

- n = 1, 3, 5, 7...

Fórmula utilizada:

`f(n) = (n · v) / 4L`

## ▶️ Como usar

1. Abra o projeto em um navegador moderno.
2. Escolha o tipo de tubo:
   - **Aberto**
   - **Fechado**
3. Ajuste o valor do harmônico no controle deslizante.
4. Observe a animação das partículas e a distribuição de pressão no tubo.
5. Clique no botão **play** para ouvir o som correspondente ao modo de ressonância.
6. Consulte os valores atualizados de frequência e comprimento de onda.
7. Expanda a seção explicativa para estudar a física por trás da simulação.

## 📚 Conceitos abordados

O simulador trabalha com temas importantes de acústica e física ondulatória, como:

- ressonância
- ondas estacionárias
- nós e antinós
- pressão sonora
- deslocamento das partículas
- harmônicos naturais
- comportamento acústico de tubos abertos e fechados

## 🔍 Recursos visuais e didáticos

A interface apresenta:

- tubo desenhado em canvas
- partículas animadas representando o ar
- cores que indicam variações de pressão
- botão de reprodução sonora
- painéis informativos com dados calculados
- explicações complementares em formato expansível

## 🎓 Aplicações educacionais

Este projeto pode ser utilizado em:

- aulas de física
- aulas de acústica musical
- disciplinas de teoria do som
- atividades de demonstração interativa
- estudos de instrumentos de sopro

## 📱 Responsividade

A aplicação foi projetada para funcionar bem em:

- computadores
- tablets
- dispositivos móveis

## 📁 Estrutura do Projeto

O projeto está concentrado em um único arquivo HTML com:

- **HTML**: estrutura da interface
- **CSS**: identidade visual e personalização dos controles
- **JavaScript**: cálculos físicos, animação, interações e reprodução sonora

## 📄 Licença

Este projeto pode ser utilizado para fins educacionais, científicos e demonstrativos.
