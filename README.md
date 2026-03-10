# 🎯 Desafio Prático QA Júnior 2026 - Beedoo

**Candidato:** Diogo Lacerda Medeiros Chaves
**LinkedIn:** [https://www.linkedin.com/in/diogolacerdamedeiroschaves/]

---

## 1. Análise Inicial da Aplicação
- **Objetivo do Sistema:** Trata-se de um site de anúncio de cursos que oferece ao usuário a oportunidade de cadastrar e expor seus cursos disponíveis em plataformas online como Udemy, Hotmart e Coursera. Além de fornecer a oportunidade de anunciar cursos presenciais. A aplicação atua como uma vitrine de cursos.
- **Principais Funcionalidades Identificadas:** Cadastro de cursos, Lista de Cursos cadastrados pelo usuário e Card dos cursos cadastrados.
- **Riscos Iniciais Observados:** Notei que o formulário de cadastro tem campos críticos que aceitam entradas inválidas e não possui mecanismos e restrições de segurança, algo que compromete a integridade dos dados e impede falhas no funcionamento da aplicação. Além de falhas na interface que afetam a experiência do usuário.

## 2. Decisões Tomadas e Raciocínio (Estratégia de Teste)
- Decidi focar na técnica de **Particionamento de Equivalência** e **Análise de Valor Limite** nos campos do formulário para garantir a cobertura sem criar testes redundantes.
- Priorizei o fluxo principal (Caminho Feliz / Testes Positivos) e adicionei Testes Negativos focados em mensagens de erro e validação de segurança.
- Dividir os casos de teste em cada campo a ser testado otimizou o fluxo de trabalho criando uma dinâmica mais rápida de trabalho.
- Na ausência de uma lista de requisitos, os testes foram desenhados na ótica exploratória do QA - investigativa, analítica e destrutiva - e perspectiva do usuário final, mitigando riscos de falhas críticas na jornada e usabilidade.

## 3. Casos de Teste (Google Sheets)
Os cenários e casos de teste detalhados foram documentados em uma planilha estruturada.
🔗 **[Clique aqui para acessar a Planilha de Casos de Teste](https://docs.google.com/spreadsheets/d/19ZMBk8UC5N5B4iaz4rJzIhnMDjK2HseP-Jx6peVripw/edit?usp=sharing)**

## 4. Relatório de Bugs Encontrados
*Para facilitar a leitura do time de desenvolvimento, estruturei os principais bugs encontrados abaixo:*

| ID | Título do Bug | Severidade | Status |
|---|---|---|---|
| BUG-043 | Um curso é criado quando todos os campos do FORMULÁRIO são deixados vazios | 🔴 Bloqueador | Aberto |
| BUG-002 | O curso não é excluído quando clicar no botão Excluir curso | 🟡 Crítico | Aberto |
| BUG-050 | Não é possível editar as informações de um curso cadastrado | 🟡 Crítico | Aberto |

*(Nota: O passo a passo completo, resultados esperados e atuais de cada bug estão detalhados na aba "Relatório de Bug" na Planilha do Google Sheets anexada acima).*

## 5. Evidências de Teste
Todas as evidências da execução (prints de tela com marcações e gravações de comportamento inesperado) foram organizadas em nuvem.
🔗 **[Clique aqui para acessar a Pasta de Evidências no Google Drive](https://drive.google.com/drive/folders/1ccgv0tutqvcLEQTGzXDOITQ9sDdR0hhq?usp=drive_link)**

---
*Documentação elaborada com base nas boas práticas do ISTQB e gestão rigorosa da qualidade.*
