🏢 Simulador de Investimentos em Fundos Imobiliários (FIIs)

📌 Sobre o Projeto

Projeto desenvolvido em Excel com o objetivo de simular investimentos em Fundos de Investimento Imobiliário (FIIs), permitindo ao usuário analisar diferentes cenários de aporte, prazo, rentabilidade e perfil de investidor.

A solução foi construída para facilitar a tomada de decisão, automatizando cálculos de projeção financeira e recomendações de alocação por meio de fórmulas, tabelas auxiliares e funções de busca.

🎯 Objetivo

Desenvolver uma ferramenta interativa capaz de:

💰 Simular investimentos em FIIs.
📈 Projetar o valor futuro das aplicações.
🎯 Sugerir percentuais de alocação conforme o perfil do investidor.
🔄 Permitir análises de múltiplos cenários alterando parâmetros de entrada.
📊 Apoiar a tomada de decisão financeira através de projeções automatizadas.
🧾 Funcionalidades Implementadas
✍️ Campos para Entrada de Dados

Foram criados campos específicos para que o usuário possa informar:

💵 Valor do investimento mensal
📅 Prazo da aplicação
📈 Taxa de rendimento estimada
👤 Perfil do investidor
🏢 Tipo de Fundo Imobiliário
Todos os cálculos são atualizados automaticamente a partir das informações inseridas.

🧮 Cálculo do Valor Futuro
Foi utilizada a função:

=VF()
para projetar o valor acumulado do investimento ao longo do tempo.

A função considera:

✅ Taxa de rendimento

✅ Prazo de investimento

✅ Valor dos aportes

✅ Capitalização composta

Dessa forma, o usuário consegue visualizar o potencial de crescimento do patrimônio em diferentes cenários.

🔎 Tabela de Apoio e Regras de Alocação
Foi criada uma planilha auxiliar para armazenar regras de recomendação de investimentos.

Estrutura Utilizada
A tabela utiliza uma chave combinada composta por:

Perfil do Investidor + Tipo de Fundo Imobiliário
Exemplo:

Conservador + Tijolo
Moderado + Papel
Agressivo + Híbrido
🔗 Automatização com PROCV
Foi utilizada a função:

=PROCV()
para localizar automaticamente os percentuais de alocação recomendados.

Benefícios

⚡ Consulta automática das informações.
🎯 Redução de erros manuais.
📊 Maior dinamismo nas simulações.
🔄 Atualização instantânea ao alterar o perfil ou o tipo de fundo.
🔒 Proteção e Controle da Planilha

Com o objetivo de preservar a integridade dos cálculos:

Foram implementadas as seguintes ações:

✅ Travamento de células com fórmulas

✅ Proteção de valores de referência

✅ Bloqueio de parâmetros base

✅ Manutenção da consistência dos resultados

Isso evita alterações acidentais em informações críticas da planilha.

🎨 Formatação e Usabilidade

Foram aplicadas técnicas de formatação para melhorar a experiência do usuário:

🎨 Paleta de cores padronizada
🔤 Formatação de fontes
📏 Ajustes de tamanho de células
🖼️ Organização visual do layout
📋 Aplicação de bordas e destaques
✅ Melhoria da legibilidade das informações
🧪 Testes e Validação

Foram realizados diversos testes alterando os parâmetros de entrada para verificar o correto funcionamento da ferramenta.

Cenários avaliados

📈 Diferentes taxas de rendimento
💵 Variações nos aportes mensais
📅 Mudanças no horizonte de investimento
👤 Diferentes perfis de investidor
🏢 Diferentes categorias de FIIs

Resultados

✅ Cálculos realizados corretamente.

✅ Recomendações retornadas conforme esperado.

✅ Atualizações automáticas funcionando adequadamente.

✅ Consistência dos resultados em diferentes cenários.

📊 Recursos Utilizados
📗 Microsoft Excel
🧮 Função VF (Valor Futuro)
🔎 Função PROCV
📋 Tabelas Auxiliares
🔒 Proteção de Células
📈 Simulação Financeira
💰 Planejamento de Investimentos


🎓 Competências Desenvolvidas

Matemática Financeira

Simulação de Investimentos

Modelagem de Planilhas

Excel Avançado

Automação de Cálculos

Funções Financeiras

Funções de Busca e Referência

Organização e Proteção de Dados

Análise de Cenários

🚀 Principais Resultados

✅ Criação de uma ferramenta de simulação de investimentos em FIIs.

✅ Automatização de projeções financeiras utilizando a função VF.

✅ Implementação de recomendações baseadas em perfil de investidor.

✅ Desenvolvimento de consultas automáticas utilizando PROCV.

✅ Construção de uma planilha organizada, segura e flexível para análise de cenários.

📸 Demonstração


📚 Observação
Este projeto foi desenvolvido para fins acadêmicos e de aprendizado, com foco na aplicação prática de conceitos de matemática financeira, modelagem de planilhas e simulação de investimentos em Fundos Imobiliários (FIIs).

⭐ Caso tenha gostado do projeto, considere deixar uma estrela no repositório.
