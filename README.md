---

# Text-to-Audio

Este projeto converte textos de arquivos PDF ou DOCX em áudio usando a API `edge-tts`, gerando arquivos de áudio em formato MP3 com vozes neurais em português.

## Pré-requisitos

### Usando o `requirements.txt` (Recomendado)

1. Clone o repositório:

   ```bash
   git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   cd SEU-REPOSITORIO
   ```

2. Instale as dependências com o comando:

   ```bash
   pip install -r requirements.txt
   ```

### Instalando manualmente

Se preferir não usar o `requirements.txt`, instale as dependências manualmente:

1. Instale o Python 3.11.9: [python.org](https://www.python.org/downloads/release/python-3119/).

2. Instale as bibliotecas:

   ```bash
   pip install edge-tts PyPDF2 python-docx
   ```

## Como usar

1. Coloque seu arquivo PDF (`livro.pdf`) ou DOCX (`livro.docx`) na mesma pasta do script.

2. Edite a variável `voice` no script para escolher a voz desejada:
   - "pt-BR-FranciscaNeural"
   - "pt-BR-AntonioNeural"

3. Execute o script no Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. O áudio gerado será salvo como `audio_edge.mp3`.

## Contribuições

Contribuições são bem-vindas! Abra uma *issue* ou envie um *pull request*.

## Licença

Este projeto está licenciado sob a licença MIT.

---