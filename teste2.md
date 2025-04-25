teste de login com usuario invalido

Objetivo do Teste
Verificar se o sistema SOFTE CRM bloqueia corretamente tentativas de login com credenciais inválidas, garantindo que:

Credenciais incorretas resultem em mensagem de erro clara.

O acesso à área restrita seja negado.

Pré-condições
Acesso à página de login do SOFTE CRM.

Credenciais inválidas para teste (usuário: admin/meldo).

Passos Executados
Acesso à Página de Login

Acessou-se a tela inicial do SOFTE CRM, onde são exibidos os campos para inserção de credenciais e o botão Log in.

Inserção de Credenciais Inválidas

Foram inseridas as credenciais admin/meldo (usuário/senha inválidos ou formato incorreto).

Tentativa de Login

Acionou-se o botão Log in para validar o acesso.

Validação da Resposta do Sistema

O sistema exibiu a mensagem de erro: "Login credentials incorrect, please try again", indicando falha na autenticação.

Não houve redirecionamento para a área restrita.

Resultados Obtidos
Funcionalidade de Login:

O sistema rejeitou as credenciais inválidas e exibiu uma mensagem de erro clara e específica.

O acesso à área restrita foi bloqueado, conforme esperado.

Interface:

A mensagem de erro foi exibida de forma destacada, sem comprometer a usabilidade da página.

Campos de login e botão permaneceram funcionais após a tentativa falha.

Conclusão
TESTE APROVADO ✅

O sistema impediu o acesso com credenciais inválidas e comunicou o erro adequadamente.

A mensagem de erro "Login credentials incorrect, please try again" foi precisa e evitou ambiguidades.

Não houve vazamento de informações sensíveis (ex.: confirmação de existência do usuário admin)




Evidence:
![Captura de tela 2025-04-23 191155](https://github.com/user-attachments/assets/9bf74c5c-ed59-4ce4-b6e7-efdba2222ba2)

