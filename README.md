Controle de Estoque

## Rodando o projeto

*.Clone esse repositório
*.Crie um virtualenv com Python 3
*.Ative p virtualenv
*.Instale as dependências
*.Rode as migrações

'''
git clone https:/github.com/open-estoque.git
cd open-estoque
python3 -m venv .venv
source .venv/bin/activate
pip install -r requeriments.txt
python contrib/env_gen.py
python manage.py migrate




