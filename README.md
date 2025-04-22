# AvaliacaoTickets

🧠 Justificativa Técnica
📌 Por que HTML, JavaScript (Vanilla) e Bootstrap?
A escolha por HTML5, JavaScript puro (Vanilla JS) e Bootstrap se deu por razões práticas, educacionais e de acessibilidade, tanto para o desenvolvedor quanto para o usuário final:

Simplicidade e Acessibilidade:

Não depende de frameworks como React ou Angular, mantendo o código leve, limpo e compreensível.

Ideal para aprendizado, manutenções rápidas e contribuições de novos desenvolvedores.

Zero Dependência de Back-End:

Utiliza localStorage para persistência de dados diretamente no navegador.

Não exige banco de dados, servidor ou configuração adicional — basta abrir o HTML no navegador.

Interface Moderna e Responsiva com Bootstrap 5:

Layout elegante e mobile-friendly com mínima codificação de CSS.

Boa usabilidade mesmo em dispositivos móveis e telas pequenas.

✅ Boas Práticas Aplicadas
Lógica bem separada entre cadastro de funcionários, tickets e relatórios.

Validações diretas e funcionais (ex: verificação de CPF duplicado, apenas funcionários ativos podem ter tickets).

IDs únicos e seguros com crypto.randomUUID().

Formulários reutilizáveis, com preenchimento automático ao editar.

Filtros de relatório combináveis, facilitando análises específicas.

Exportação para CSV prática e funcional.

💡 Exemplos de Boa Utilização
👤 Cadastro de Funcionários
Campos claros e obrigatórios.

Situação (ativo/inativo) visível e editável.

Exibição de última modificação para controle.

🎟️ Registro de Tickets
Associado apenas a funcionários ativos.

Armazena quantidade e data de forma automática.

Simples e direto para controle interno.

📊 Relatório de Tickets
Filtros por funcionário, situação e período.

Tabela dinâmica gerada via JavaScript.

Botão de exportação para análise externa (Excel, Google Sheets, etc).

🧪 Quando usar essa abordagem?
Essa solução é ideal para:

Sistemas internos simples (como controle de vale-transporte, tickets ou horas extras).

MVPs ou protótipos rápidos sem infraestrutura de backend.

Ambientes offline ou restritos.

Projetos educacionais ou testes de lógica.
