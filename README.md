# -Pensamento-Computacional-e-Automa-o-com-Python---GS---2o-semestre
 Descrição do Projeto e Propósito

O **Sistema de Orientação de Carreiras** é uma aplicação desenvolvida em **Python orientado a objetos** que analisa perfis profissionais e recomenda **carreiras do futuro** com base em competências técnicas e comportamentais.

O sistema simula uma ferramenta inteligente de **orientação de carreira**, conectando **lógica de programação** e **automação** ao **desenvolvimento humano e profissional**, ajudando usuários a compreenderem seus pontos fortes e áreas de aprimoramento.

---

##  Instruções de Execução

### 🔹 Opção 1 – Executar no Google Colab (recomendado)
1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Crie um novo notebook e cole o código do arquivo `sistema_orientacao_carreiras.py`.
3. Execute todas as células.
4. No final, rode o comando:
   ```python
   iniciar_sistema()

6. Digite seu nome e as notas (0 a 10) para cada competência.
7. O sistema mostrará as carreiras mais compatíveis e dicas de melhoria personalizadas.

Principais Classes
Classe	Descrição

Competencia: 	Representa uma competência (ex: lógica, criatividade, colaboração).

Perfil: 	Armazena as competências e notas de um candidato.

Carreira: 	Define os requisitos e pesos de cada carreira.

Recomendador: 	Calcula a aderência entre o perfil e as carreiras, gerando recomendações.

SistemaCLI: 	Interface textual para interação com o usuário (menu principal).
