# Guia Estratégico de Segurança para Startups (SSAMM)

## Visão Geral

Este projeto é uma página da web interativa que serve como um rascunho de um guia estratégico de segurança de software, adaptado especificamente para startups com recursos limitados e equipes pequenas. O conteúdo é um resultado preliminar de um Trabalho de Conclusão de Curso (TCC1) e tem como objetivo fornecer uma ferramenta prática para autoanálise e melhoria contínua da segurança.

O guia é baseado em modelos de maturidade de segurança renomados, como OWASP SAMM, OpenSAMM e Microsoft SDL, simplificando suas práticas para o contexto de uma startup.

## Seções Principais

O site está organizado nas seguintes seções:

### 1. **Início**
- Apresenta o propósito do guia, destacando sua base no OWASP SAMM, OpenSAMM e Microsoft SDL.
- Oferece uma introdução ao modelo adaptado para startups.

### 2. **Modelo SSAMM (Startup Software Assurance Maturity Model)**
Esta é a seção central do guia, detalhando um modelo de maturidade de segurança em cinco funções de negócio essenciais. Para cada função, são apresentados quatro níveis de maturidade (de 0 a 3), com explicações, atividades, benefícios e critérios de avaliação adaptados para startups.

As funções de negócio abordadas são:
- **Governança:** Foco em políticas, estratégias e treinamentos.
- **Design:** Aborda a construção de software seguro desde a concepção, com ênfase em modelagem de ameaças.
- **Implementação:** Cobre práticas de codificação segura e gestão de dependências.
- **Verificação:** Envolve testes manuais e automatizados para identificar vulnerabilidades.
- **Operações:** Foca no monitoramento e resposta a incidentes em produção.

### 3. **Vulnerabilidades Comuns em Startups**
Esta seção lista e descreve as vulnerabilidades mais comuns em startups, com base no **OWASP Top 10:2021**, **Common Vulnerabilities and Exposures (CVE)** e **Common Weakness Enumeration (CWE)**. Para cada vulnerabilidade, são fornecidos:
- Descrição
- Impacto potencial
- Estratégias de mitigação de baixo custo

Exemplos de vulnerabilidades incluem Quebra de Controle de Acesso, Falhas Criptográficas, Injeção, Log4Shell (CVE-2021-44228) e Validação de Entrada Incorreta (CWE-20).

### 4. **Sobre o Projeto**
Explica o contexto acadêmico do guia, informando que é um resultado preliminar de um TCC1 e que será refinado em um trabalho futuro (TCC2).

## Funcionalidades Interativas

- **Menu de Navegação:** Um menu fixo no topo da página permite a navegação rápida entre as seções. O menu é responsivo e se adapta a dispositivos móveis.
- **Modais Interativos:** Na seção do Modelo SSAMM, cada nível de maturidade é um botão que, ao ser clicado, abre um modal com informações detalhadas sobre as atividades, benefícios e critérios daquele nível.

## Tecnologias Utilizadas

- **HTML5:** Estrutura da página.
- **Tailwind CSS:** Framework de CSS para estilização rápida e responsiva.
- **Font Awesome:** Biblioteca de ícones.
- **JavaScript:** Utilizado para a interatividade do menu móvel e dos modais de informação.

## Como Usar

Abra o arquivo `index.html` em qualquer navegador web moderno para visualizar e interagir com o guia. Não há necessidade de instalar dependências ou executar um servidor local.