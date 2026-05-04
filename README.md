# 📂 Estrutura de Diretórios: Projeto Inventário

sistema_inventario/
│
├── config/                 # Configurações sensíveis e globais
│   └── config.php          # Credenciais do DB e constantes (ex: URL_BASE)
│
├── core/                   # O "coração" do sistema (Lógica PHP)
│   └── conexao.php         # Script PDO de conexão com o banco
│
├── public/                 # Arquivos acessíveis pelo navegador (Frontend)
│   ├── css/                # Folhas de estilo (Bootstrap ou CSS próprio)
│   ├── js/                 # Scripts JavaScript (Validações e Ajax)
│   └── assets/             # Imagens e ícones
│
├── includes/               # Fragmentos de código reutilizáveis
│   ├── header.php          # Cabeçalho e Menu
│   └── footer.php          # Rodapé e scripts JS
│
├── api/                    # Ponte para integração com o Python
│   └── produtos.php        # Endpoint que fornece JSON para o Python
│
├── scripts_python/         # Automação e Inteligência (POO)
│   ├── main.py             # Script principal de análise
│   ├── classes/            # Classes Python (Ex: Produto.py, APIClient.py)
│   └── relatorios/         # Local onde o Python salvará arquivos CSV/PDF
│
├── views/                  # Telas do sistema (Interface)
│   ├── login.php           # Tela de acesso
│   ├── dashboard.php       # Painel principal
│   └── cadastro_item.php   # Formulário de entrada de produtos
│
└── index.php               # Ponto de entrada (Redirecionamento)