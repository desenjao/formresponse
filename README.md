# Formulário de Estratégia - Marketing na Prática

Este é um formulário estratégico desenvolvido para o curso "Marketing na Prática" da EitaDevis e Lidera, com design futurista e integração com Google Sheets.

## 📋 Sobre o Projeto

Formulário HTML moderno e responsivo com 15 perguntas estratégicas para orientar a criação e execução do curso digital "Marketing na Prática". As respostas são automaticamente salvas em uma planilha do Google Sheets via SheetDB.

## 🚀 Funcionalidades

- Design futurista com efeitos de glassmorphism
- Interface responsiva para todos os dispositivos
- 15 perguntas estratégicas sobre o projeto do curso
- Validação de campos obrigatórios
- Integração com Google Sheets via SheetDB
- Feedback visual de sucesso/erro
- Animações e transições suaves

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com variáveis CSS e efeitos de vidro)
- JavaScript (para validação e integração)
- SheetDB.io (para integração com Google Sheets)

## 📊 Estrutura das Perguntas

O formulário contém perguntas sobre:
1. Objetivos principais do curso digital
2. Modelo de negócio inicial
3. Formatos de conteúdo prioritários
4. Nível de produção desejado
5. Canais de captação de alunos
6. Modelo de suporte ao aluno
7. Métricas de sucesso
8. Status do material existente
9. Recursos humanos necessários
10. Transformação prometida pelo curso
11. Bônus para conversão
12. Estratégia com afiliados
13. Mitigação de riscos
14. Prazo realista de lançamento
15. Observações adicionais

## ⚙️ Configuração

### Pré-requisitos
- Conta no SheetDB.io
- Planilha do Google Sheets configurada

### Instalação
1. Faça o download dos arquivos
2. Substitua a URL do SheetDB no código JavaScript:
```javascript
const SHEETDB_URL = "https://sheetdb.io/api/v1/SEU_ID_AQUI";
```
3. Configure sua planilha do Google Sheets com as colunas correspondentes às perguntas
4. Faça upload para seu servidor web

## 🎨 Personalização

### Cores
Modifique as variáveis CSS no início do arquivo:
```css
:root {
  --primary: #ff7a00;
  --primary-dark: #e06600;
  --primary-light: rgba(255, 122, 0, 0.15);
  --secondary: #7b61ff;
  /* ... outras cores */
}
```

### Perguntas
Edite as perguntas diretamente no HTML mantendo a estrutura existente.

## 📱 Responsividade

O formulário é totalmente responsivo e se adapta a:
- Desktop (acima de 768px)
- Tablets (entre 480px e 768px)
- Smartphones (abaixo de 480px)

## 🔌 Integração com SheetDB

O formulário usa a API do SheetDB para enviar dados para o Google Sheets. Certifique-se de:

1. Criar uma conta no [SheetDB](https://sheetdb.io/)
2. Configurar sua planilha do Google Sheets com as colunas corretas
3. Inserir sua URL da API no código JavaScript

## 📬 Fluxo de Dados

1. Usuário preenche o formulário
2. JavaScript valida os dados
3. Dados são enviados para SheetDB
4. SheetDB armazena os dados no Google Sheets
5. Usuário recebe confirmação de envio

## 🐛 Solução de Problemas

### Erro no envio
- Verifique a URL do SheetDB no código
- Confirme que a planilha do Google Sheets está configurada corretamente
- Verifique o console do navegador para mensagens de erro detalhadas

### Problemas de exibição
- Certifique-se de que todos os arquivos CSS e JavaScript estão carregando
- Teste em diferentes navegadores

## 📄 Estrutura de Arquivos

```
/
├── index.html          # Arquivo principal do formulário
└── (nenhum arquivo externo necessário)
```

## 👥 Contribuição

Para contribuir com este projeto:
1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Suporte

Para dúvidas ou problemas com o formulário, entre em contato através do repositório ou consulte a documentação do [SheetDB](https://sheetdb.io/docs).

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🔄 Atualizações Futuras

- [ ] Adicionar mais opções de personalização
- [ ] Implementar exportação de dados em CSV
- [ ] Adicionar dashboard de visualização das respostas
- [ ] Implementar autenticação de usuários

---

**Nota:** Este formulário foi desenvolvido especificamente para o curso "Marketing na Prática" da EitaDevis e Lidera, mas pode ser adaptado para outros projetos com necessidades similares.