# ❓ Perguntas Frequentes (FAQ)

## 📋 Sobre a Ferramenta

### O que é o Agregador de Dados IR?
É uma planilha Excel/Calc gratuita que ajuda a organizar todas as informações necessárias para preencher a declaração de Imposto de Renda Pessoa Física.

### Esta planilha substitui o programa da Receita Federal?
**NÃO.** Esta é apenas uma ferramenta de **organização** dos dados. Você ainda precisará usar o programa oficial da Receita Federal para fazer a declaração.

### Preciso pagar para usar?
**NÃO.** O projeto é 100% gratuito e open source sob licença MIT.

### Funciona no LibreOffice Calc?
**SIM.** A planilha funciona tanto no Microsoft Excel quanto no LibreOffice Calc.

---

## 💰 Sobre Rendimentos

### Onde coloco meu salário?
Na aba **"Rendimentos"**, preencha mês a mês com os valores do seu informe de rendimentos.

### E se trabalho como PJ?
- Se recebe **pró-labore**: aba "Rendimentos"
- Se recebe **dividendos**: aba "Rendimentos Isentos"
- Se tem **lucro da empresa**: consulte um contador

### Tenho duas fontes de renda. Como faço?
Use linhas diferentes para cada fonte pagadora, mesmo que seja no mesmo mês.

### Rendimento de aluguel vai onde?
Na aba **"Rendimentos"** se for tributável, ou **"Rendimentos Isentos"** se for isento.

---

## 📝 Sobre Deduções

### Posso deduzir plano de saúde?
**SIM.** Todo o valor pago com planos de saúde é dedutível (sem limite).

### Curso de inglês é dedutível?
**NÃO.** Apenas educação formal (fundamental, médio, superior, técnico e pós-graduação).

### Psicólogo e psiquiatra são dedutíveis?
**SIM.** Entram como despesas médicas na categoria Saúde.

### Academia é dedutível?
**NÃO.** Academia não é considerada despesa médica dedutível.

### Quantos dependentes posso declarar?
Não há limite, mas cada dependente deve atender aos critérios da Receita Federal:
- Filhos até 21 anos
- Filhos universitários até 24 anos
- Cônjuge
- Pais, avós (se você sustenta)
- Entre outros casos específicos

---

## 🏠 Sobre Bens e Direitos

### Preciso declarar meu carro?
**SIM**, se o valor foi superior a R$ 5.000,00 (em anos recentes - confirme o limite atual).

### E se comprei o carro em 2025?
Coloque **R$ 0,00** na coluna "Valor 31/12/2024" e o valor pago na coluna "Valor 31/12/2025".

### Conta corrente precisa declarar?
**SIM**, se o saldo total de suas contas em 31/12 foi superior ao limite da Receita Federal.

### Qual valor do imóvel devo colocar?
O valor de **aquisição** (quanto você pagou), NÃO o valor de mercado atual.

### Tenho ações. Onde declaro?
Na aba "Bens e Direitos", use o código adequado (geralmente 31 ou 47, dependendo do tipo).

---

## 💳 Sobre Dívidas

### Preciso declarar meu financiamento?
**SIM**, declare o saldo devedor em 31/12 de cada ano.

### Cartão de crédito entra?
Só se você tinha uma dívida **parcelada** significativa em 31/12.

### Empréstimo pessoal?
**SIM**, declare o saldo devedor.

---

## 🔧 Problemas Técnicos

### As fórmulas não estão calculando
**Solução:**
1. Verifique se a edição está habilitada
2. Pressione F9 para forçar recálculo
3. Certifique-se de não ter editado as células de fórmula

### Os valores não aparecem com R$
**Solução:**
- As células já estão formatadas corretamente
- Digite apenas números (sem R$, sem pontos de milhar)
- Exemplo: digite `5000` não `5.000,00`

### Apaguei uma fórmula sem querer
**Solução:**
- Use Ctrl+Z para desfazer
- Ou baixe o arquivo original novamente

### O arquivo não abre
**Solução:**
- Verifique se tem Excel 2013+ ou LibreOffice 5+
- Tente abrir com LibreOffice Calc (gratuito)
- Desative proteção de arquivo de fontes desconhecidas

---

## 📊 Sobre os Dados

### Como faço backup dos meus dados?
1. Salve cópias em locais diferentes
2. Use nomes descritivos: `IR_2025_backup_05fev.xlsx`
3. Considere usar nuvem (Dropbox, Google Drive, OneDrive)

### Posso compartilhar minha planilha preenchida?
**NÃO RECOMENDADO.** Seus dados fiscais são sensíveis. Compartilhe apenas o arquivo vazio.

### Os dados ficam salvos automaticamente?
**NÃO.** Você precisa salvar manualmente (Ctrl+S) regularmente.

---

## ⚖️ Questões Legais

### Esta ferramenta é aprovada pela Receita Federal?
Não há "aprovação" da Receita para ferramentas de organização. Esta é uma planilha particular de organização de dados.

### Posso confiar 100% nos cálculos?
A planilha tem fórmulas testadas, mas **sempre confira os valores**. É sua responsabilidade a declaração correta.

### E se eu errar algo?
Você pode retificar sua declaração posteriormente. Mas sempre revise tudo antes de enviar!

### Preciso de contador?
**Recomendamos fortemente**, especialmente se:
- Sua situação for complexa
- Você é empresário
- Tem rendimentos no exterior
- Tem dúvidas sobre deduções

---

## 🆘 Onde Buscar Ajuda

### Dúvidas sobre a planilha:
- Leia o [Tutorial Completo](TUTORIAL.md)
- Consulte este FAQ
- Abra uma [Issue no GitHub](https://github.com/seu-usuario/agregador-ir/issues)

### Dúvidas sobre declaração de IR:
- Site da Receita Federal: [gov.br/receitafederal](https://www.gov.br/receitafederal)
- Telefone: 146
- Procure um contador

### Dúvidas técnicas do Excel:
- Suporte Microsoft Office
- Fóruns do LibreOffice

---

## 🔮 Recursos Futuros

### Vão adicionar mais funcionalidades?
Sim! Veja o [Changelog](CHANGELOG.md) para melhorias planejadas.

### Posso sugerir melhorias?
**SIM!** Abra uma issue ou faça um pull request.

### Como contribuir com o projeto?
Leia o [Guia de Contribuição](CONTRIBUTING.md).

---

## ⚠️ Isenção de Responsabilidade

Esta ferramenta é fornecida "como está", sem garantias. O usuário é responsável por:
- Verificar a exatidão dos dados
- Consultar um profissional qualificado
- Cumprir com todas as obrigações fiscais

**Os criadores desta ferramenta não se responsabilizam por erros na declaração de imposto de renda.**

---

## 📞 Contato

**Não respondemos dúvidas sobre legislação tributária.**

Para dúvidas sobre a **ferramenta**:
- Issues: [GitHub Issues](https://github.com/seu-usuario/agregador-ir/issues)
- Documentação: [README.md](README.md)

Para dúvidas sobre **imposto de renda**:
- Receita Federal: 146
- Contador profissional

---

**🎯 Não encontrou sua resposta? Abra uma issue no GitHub!**

*Última atualização: Fevereiro 2026*
