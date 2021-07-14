# Repositório do Curso de Testes do Grupy-Sanca

Veja [online](http://test.grupysanca.com.br)!

## Como gerar o material

1. instale as dependências:
   ```bash
   $ python -m venv venv
   $ source venv/bin/activate
   $ pip install -Ur requirements.txt
   ```

   - caso queira gerar o PDF, installe LaTeX:
     ```bash
     # no Arch btw
     $ sudo pacman -Syu texlive-{bin,core,latexextra}
     ```
2. gere o HTML:
   ```bash
   $ make html
   ```
3. [opcional] gere o pdf:
   ```bash
   $ make latexpdf
   ```
4. spellchecker:
   - intale o `enchant`, `hunspell`, e um dicionário pt-br (`hunspell-pt-br`):

     ```bash
     # no Arch btw
     $ sudo pacman -Syu hunspell enchant
     $ paru -Sy hunspell-pt-br # from AUR
     # no Ubuntu:
     $ sudo apt install hunspell hunspell-pt-br enchant
     ```

     E rode: `sphinx-build -b spelling -nW source/ build/`
5. para rodar o doctest:
   ```bash
   $ sphinx-build -b doctest -n source/ build
   ```
