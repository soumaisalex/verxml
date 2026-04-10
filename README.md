# 📄 Visualizador de DANFE XML (Modelo 55)

Uma ferramenta web leve, rápida e focada em privacidade para visualização de arquivos XML de Notas Fiscais Eletrônicas (NF-e).

📍 **Acesse agora:** [https://verxml.pages.dev](http://verxml.pages.dev)

---

## 🚀 Diferenciais e Práticas de Mercado

### 1. Visualização Direta vs. Geração de PDF
A grande maioria dos serviços atuais foca em "Converter XML para PDF". Este projeto adota uma abordagem moderna: **Visualização Nativa**.
* **Sem downloads desnecessários:** Você visualiza todos os dados da nota diretamente na tela de forma estruturada.
* **Aproveitamento do Navegador:** Em vez de gerar um PDF pesado via servidor, utilizamos CSS `@media print`. Isso permite que o usuário use a função nativa do sistema (Ctrl+P) para imprimir ou "Salvar como PDF" apenas se realmente precisar.

### 2. 100% Gratuito e Sem Cadastro
O VerXML foi criado para ser uma ferramenta de utilidade pública para desenvolvedores e contadores. Não há telas de login, captchas ou limites de uso.

### 3. Privacidade e Segurança (Client-Side)
Seguindo as melhores práticas de segurança de dados, o arquivo XML é lido através da API `FileReader` do JavaScript. **Nenhum dado é enviado para um servidor externo**; o processamento acontece integralmente no seu navegador.

---

## 🛠️ Ferramentas Utilizadas

* **HTML5 & CSS3:** Estrutura e estilização avançada com foco em impressão.
* **JavaScript (Vanilla):** Manipulação de DOM e parsing de XML sem dependências.
* **Tailwind CSS:** Framework de estilização moderno para uma interface limpa.
* **Cloudflare Pages:** Hospedagem de alta performance e disponibilidade.

---

## ⚠️ Limitações Importantes

* **Modelo 55:** Este visualizador é compatível exclusivamente com a **NF-e (Nota Fiscal Eletrônica de mercadorias)** modelo 55.
* **NFS-e:** Atualmente **não é compatível** com Notas de Serviço (NFS-e).

---

## 👨‍💻 Desenvolvido por

**Alex Passos**
Siga-me no Instagram para acompanhar meus projetos: [@soumaisalex](https://instagram.com/soumaisalex)

---
*Este projeto foi desenvolvido com foco em facilitar o dia a dia de quem precisa de uma consulta rápida a arquivos fiscais com total segurança.*
