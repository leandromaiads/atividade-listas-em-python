# atividade-listas-em-python

📝 README: Sistema de Cadastro de Produtos
Este é um projeto simples desenvolvido em Python para consolidar conceitos fundamentais da linguagem, como manipulação de coleções (listas), estruturas de repetição (for), condicionais (if/else), entrada de dados do usuário (input) e a função integrada zip() para iteração paralela.

🚀 Funcionalidades
O projeto está estruturado em 4 etapas evolutivas:

Visualização Inicial (Parte 1): Apresenta uma listagem inicial de produtos cadastrados com seus respectivos preços, formatados de maneira legível.
Cadastro Interativo (Parte 2): Permite ao usuário cadastrar novos produtos e preços dinamicamente no sistema através do terminal.
Remoção Segura (Parte 3): Remove o último item cadastrado das listas de forma segura, evitando erros caso o estoque já esteja completamente vazio.
Próximos Passos (Parte 4): Espaço reservado para futuras implementações, como buscas de produtos, atualizações de preços ou relatórios financeiros.
🛠️ Tecnologias Utilizadas
Linguagem: Python 3.x
Ambiente: Jupyter Notebook / Google Colab
💻 Como Rodar o Projeto
Certifique-se de ter o Python instalado ou utilize o Google Colab.
Execute a Parte 1 para inicializar as listas de produtos e preços padrão.
Rode a Parte 2 para testar a entrada de novos dados.
Utilize a Parte 3 para simular a exclusão (descarte) do último produto cadastrado.
📝 Exemplo de Código Utilizado
# Exemplo de iteração combinada em Python
for produto, preco in zip(produtos, precos):
    print(f"O produto {produto} custa R$ {preco:.2f}")
👤 Autor
Desenvolvido por você durante as práticas de fundamentos de programação em Python! 🚀
