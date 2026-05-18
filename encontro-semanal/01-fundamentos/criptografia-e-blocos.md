# Semana 2: Criptografia e Blocos

**Data do Encontro:** xx/xx/xx
**Objetivo:** Compreender hashes (SHA-256), chaves públicas/privadas e assinaturas digitais como base técnica da blockchain.

---

### Conteúdo para Estudo

Abaixo estão os materiais selecionados para a base teórica:

* **Fundamentos da Blockchain:**
    * [Demo Interativa de Blockchain](https://andersbrownworth.com/blockchain/blockchain) — *Website interativo*
    * [Componentes da Blockchain (NIST)](https://nvlpubs.nist.gov/nistpubs/ir/2018/NIST.IR.8202.pdf) — *Artigo (pág. 7-17)*
* **Criptografia e Hash Functions:**
    * [O que é uma Hash Function?](https://corporatefinanceinstitute-com.translate.goog/resources/cryptocurrency/hash-function/?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc) — *Artigo*
    * [O quão seguro é 256 bit?](https://www.youtube.com/watch?v=S9JGmA5_unY) — *Vídeo (5 min)*
* **Bitcoin e Funcionamento:**
    * [Como o Bitcoin funciona?](https://www.youtube.com/watch?v=bBC-nXj3Ng4) — *Vídeo (3Blue1Brown — 25 min)*

---

### Atividades de Fixação

Dividimos as tarefas para que você possa praticar um pouco a cada semana até o próximo encontro.

#### **Semana A: Conceitos de Hash e Estrutura de Blocos**

1.  **Demo Interativa (Website):** Navegue pela demo interativa do Anders Brownworth e responda: ao alterar um dado dentro de um bloco, o que acontece com os hashes dos blocos seguintes? O que isso ilustra sobre a imutabilidade?

2.  **Hash Function (Artigo):** De acordo com o artigo, quais são as três características principais de uma hash function? Explique por que uma hash é unidirecional e como isso se relaciona com a segurança.

3.  **256 Bits de Segurança (Vídeo):** Após assistir ao vídeo de 5 minutos, explique em suas palavras por que um espaço de hashes de 256 bits é considerado praticamente impossível de ser quebrado por força bruta.

#### **Semana B: Chaves, Assinaturas e Bitcoin**

1.  **Chave Pública e Privada (NIST):** No artigo da NIST, sobre os componentes de um bloco (cabeçalho, dados, hash anterior). Explique como a combinação de hash anterior + assinatura digital garante que ninguém pode modificar um bloco sem ser detectado.

2.  **Como o Bitcoin Funciona (Vídeo):** Após assistir ao vídeo de 25 minutos do 3Blue1Brown, descreva o papel das chaves públicas e privadas nas transações Bitcoin. O que é uma assinatura digital e como ela é verificada por qualquer pessoa na rede?

3.  **Atividade Prática — Gerador de Hash:** Use um gerador de hash SHA-256 online (como [hash.sh](https://www.hash.sh/en/sha256)) e compare os hashes de duas mensagens ligeiramente diferentes (ex: `"bitcoin"` vs `"Bitcoin"`). O que muda no resultado? Por que pequenas alterações geram resultados completamente diferentes?

---
