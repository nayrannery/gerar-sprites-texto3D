# Geração de sprites

Projeto para geração se sprites com letras digitadas

## Requisitos

- Node.js instalado no sistema.
- Fontes adicionais convertidas para o formato .json.
- [Site para conversão de fontes](http://gero3.github.io/facetype.js/) (recomenda-se optar por fontes com poucos detalhes).

## Instalação

1. Clone o repositório do projeto:

   ```bash
   git clone https://github.com/nayrannery/gerar-sprites-texto3D.git
   ```

2. Navegue até a pasta do projeto:

   ```bash
   cd seu-projeto
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

## Utilização

1. Certifique-se de ter as fontes convertidas para o formato .json e adicione-as à pasta `/fontes` do projeto.

2. Execute os seguintes comandos para rodar o servidor localmente:

   ```bash
   npm install -g live-server
   live-server --port=8000
   ```

3. Atalhos do aplicativo:
   - "L" para definir uma nova letra ou frase.
   - A área branca é definida como o padrão de 160x160 pixels. Você pode alterar esses parâmetros conforme necessário.
   - "R" para rotacionar a letra em 1 milissegundo.

4. Para salvar a imagem, clique com o botão direito do mouse e escolha "Salvar imagem". Será necessário usar outro software para recortar cada sprite adequadamente.

5. Geralmente, são necessários 10 salvamentos para uma volta completa da letra. No entanto, esse número pode variar dependendo da letra e de sua simetria.




