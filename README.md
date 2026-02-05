# 📊 Agregador de Dados para Imposto de Renda

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## 📋 Sobre o Projeto

Ferramenta desenvolvida em Excel para **organizar e consolidar** todas as informações necessárias para a declaração de Imposto de Renda Pessoa Física (IRPF). Este agregador de dados foi criado com foco em **eficiência**, **validação automática** e **navegação intuitiva**, facilitando o controle e a preparação dos documentos fiscais.

## 🎯 Objetivos

Este projeto foi desenvolvido como parte do desafio DIO com os seguintes objetivos de aprendizagem:

- ✅ Aplicar conceitos de Excel avançado em ambiente prático
- ✅ Desenvolver ferramenta com validações e fórmulas automáticas
- ✅ Documentar processos técnicos de forma clara e estruturada
- ✅ Utilizar GitHub para compartilhamento de projetos

## 🚀 Funcionalidades

### 📑 Dashboard Interativo
- Visão consolidada de todos os dados
- Navegação rápida entre abas
- Indicadores principais em tempo real
- Atualização automática das informações

### 💰 Controle de Rendimentos
- **Rendimentos Tributáveis**: Registro mensal de salários, pró-labore e outros rendimentos
- **Rendimentos Isentos**: Controle de dividendos, PLR e rendimentos não tributáveis
- Cálculo automático de totais anuais
- Validação de dados com listas suspensas

### 📝 Despesas Dedutíveis
Organização por categorias:
- **Saúde**: Plano de saúde, consultas, exames, odontologia
- **Educação**: Ensino fundamental, médio, superior e técnico
- **Previdência Privada**: PGBL
- **Dependentes**: Dedução por dependente
- Subtotais automáticos por categoria

### 🏠 Bens e Direitos
- Registro de imóveis (apartamentos, casas, terrenos)
- Veículos automotores
- Contas bancárias e investimentos
- Comparativo de valores entre anos
- Códigos padronizados conforme tabela da Receita Federal

### 💳 Dívidas e Ônus Reais
- Financiamentos imobiliários
- Financiamento de veículos
- Empréstimos bancários
- Comparativo de saldos entre anos

### 📊 Resumo Consolidado
- Consolidação automática de todos os dados
- Cálculo de patrimônio líquido
- Observações e lembretes importantes
- Visão completa para declaração

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel / LibreOffice Calc**
- **Fórmulas Excel**: SUM, validações, referências entre abas
- **Formatação Condicional**: Destaque de campos importantes
- **Validação de Dados**: Listas suspensas para padronização
- **Python (Desenvolvimento)**: openpyxl para geração automatizada

## 📥 Como Usar

### Download e Instalação

1. **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/agregador-ir.git
```

2. **Baixe o arquivo Excel**:
   - Acesse a pasta do projeto
   - Faça o download de `Agregador_IR_2025.xlsx`

3. **Abra no Excel ou LibreOffice Calc**

### Preenchimento dos Dados

1. **Comece pelo Dashboard**:
   - Leia as instruções de navegação
   - Familiarize-se com a estrutura

2. **Preencha sequencialmente**:
   - Rendimentos → Rendimentos Isentos → Despesas Dedutíveis → Bens e Direitos → Dívidas

3. **Utilize os menus de validação**:
   - Campos com listas suspensas têm opções pré-definidas
   - Campos em azul claro são para entrada de dados

4. **Confira o Resumo**:
   - Todos os totais são calculados automaticamente
   - Verifique a consistência dos dados

## 📸 Capturas de Tela

### Dashboard Principal
O dashboard oferece navegação rápida e indicadores consolidados:
- Total de Rendimentos Tributáveis
- Total de Rendimentos Isentos
- Total de Despesas Dedutíveis
- Total de Bens e Direitos

### Rendimentos
Organização mensal com campos para:
- Fonte pagadora e CNPJ
- Tipo de rendimento (lista suspensa)
- Valor bruto e IRRF retido
- Total anual automático

### Despesas Dedutíveis
Categorização por cores:
- 🟢 Verde: Saúde
- 🔵 Azul: Educação
- 🟠 Laranja: Previdência
- 🟤 Marrom: Dependentes

### Resumo Consolidado
Visão completa com:
- Cálculos automáticos de todos os totais
- Patrimônio líquido
- Observações importantes

## 🔧 Estrutura Técnica

### Abas da Planilha

```
├── Dashboard (Navegação e Indicadores)
├── Rendimentos (Rendimentos Tributáveis)
├── Rendimentos Isentos (Rendimentos Não Tributáveis)
├── Despesas Dedutíveis (Deduções Permitidas)
├── Bens e Direitos (Patrimônio)
├── Dívidas (Ônus Reais)
└── Resumo (Consolidação Final)
```

### Padrão de Cores

| Cor | Uso | RGB |
|-----|-----|-----|
| Azul Escuro | Cabeçalhos | #366092 |
| Cinza Claro | Campos de Entrada | #E7E6E6 |
| Azul Claro | Totais | #D9E1F2 |
| Amarelo | Alertas/Avisos | #FFF2CC |

### Principais Fórmulas

**Dashboard - Total de Rendimentos:**
```excel
=Rendimentos!B100
```

**Resumo - Patrimônio Líquido:**
```excel
='Bens e Direitos'!E100-Dívidas!E50
```

**Despesas - Total Geral:**
```excel
=E12+E20+E23+E30
```

## ✅ Validações Implementadas

- ✔️ **Validação de Tipo de Rendimento**: Lista suspensa com opções predefinidas
- ✔️ **Formatação Monetária**: Todos os valores em formato R$ #,##0.00
- ✔️ **Fórmulas Protegidas**: Cálculos automáticos não podem ser sobrescritos
- ✔️ **Zero Erros de Fórmula**: Todas as 26 fórmulas validadas e funcionando

## 📚 Documentação de Desenvolvimento

### Processo de Criação

1. **Planejamento**: Definição das abas e estrutura de dados
2. **Desenvolvimento**: Criação da planilha com Python (openpyxl)
3. **Formatação**: Aplicação de cores, fontes e estilos profissionais
4. **Validação**: Teste de todas as fórmulas e referências
5. **Documentação**: Criação de README e materiais de apoio

### Script de Geração

O arquivo `create_ir_spreadsheet.py` contém o código Python que gera automaticamente a planilha Excel com todas as formatações, fórmulas e validações.

**Principais bibliotecas utilizadas:**
- `openpyxl`: Manipulação de arquivos Excel
- `openpyxl.styles`: Formatação (cores, fontes, bordas)
- `openpyxl.worksheet.datavalidation`: Validação de dados

## ⚠️ Observações Importantes

> 🔴 **ATENÇÃO**: Esta planilha é uma **ferramenta auxiliar** de organização de dados. Não substitui a orientação de um contador profissional.

- 📌 Sempre confira os dados com documentos oficiais (informes de rendimento)
- 📌 Mantenha todos os comprovantes guardados por 5 anos
- 📌 Consulte um contador para situações específicas ou dúvidas
- 📌 Os códigos de bens e direitos seguem a tabela da Receita Federal

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma Branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido como parte do desafio DIO - Digital Innovation One

---

## 📞 Contato e Suporte

Para dúvidas, sugestões ou reportar problemas:
- Abra uma [Issue](https://github.com/seu-usuario/agregador-ir/issues)
- Entre em contato através do GitHub

---

## 🌟 Agradecimentos

- **DIO - Digital Innovation One** pelo desafio e oportunidade de aprendizado
- Comunidade de desenvolvedores que compartilham conhecimento
- Receita Federal do Brasil pelas orientações sobre IRPF

---

**⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!**

---

### 📊 Status do Projeto

```
✅ Dashboard          - Concluído
✅ Rendimentos        - Concluído
✅ Rendimentos Isentos - Concluído
✅ Despesas Dedutíveis - Concluído
✅ Bens e Direitos    - Concluído
✅ Dívidas            - Concluído
✅ Resumo             - Concluído
✅ Documentação       - Concluído
```

### 🔮 Melhorias Futuras

- [ ] Adicionar gráficos de evolução patrimonial
- [ ] Criar aba de planejamento tributário
- [ ] Implementar cálculo de imposto devido
- [ ] Adicionar importação de dados de informes
- [ ] Criar versão web da ferramenta

---

*Última atualização: Fevereiro 2026*
