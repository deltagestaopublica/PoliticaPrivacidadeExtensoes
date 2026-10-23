# Políticas de privacidade das extensões da Delta

Este repositório existe por um motivo só: **hospedar as páginas de política de privacidade** das extensões
de navegador da Delta. A Chrome Web Store exige uma URL pública de política de privacidade para qualquer
extensão que declare `host_permissions`, e o GitHub Pages (plano gratuito) só serve repositório público.

Publicado pelo GitHub Pages (branch `main`, raiz do repositório). A raiz
(<https://deltagestaopublica.github.io/PoliticaPrivacidadeExtensoes/>) lista as políticas; cada extensão tem a sua página:

| Extensão | Página |
|---|---|
| Filtro de Corresponsável (Procuradoria) | <https://deltagestaopublica.github.io/PoliticaPrivacidadeExtensoes/filtro-corresponsavel.html> |
| Saldo da Conta (Tesouraria) | <https://deltagestaopublica.github.io/PoliticaPrivacidadeExtensoes/saldo-da-conta.html> |

O repositório se chamava `privacidade-filtro-corresponsavel`; o endereço antigo do Pages deixou de
funcionar com a troca de nome (o GitHub não redireciona o Pages) — o link de cada extensão na Web Store
tem que apontar para a página dela, acima.

## O que NÃO está aqui

O código-fonte das extensões. Cada uma fica no seu repositório, que é **privado** e continua privado.
Aqui só existe o texto das políticas — páginas HTML estáticas, sem script, sem dado de cliente, sem nada
que a Delta não queira que o mundo leia.

## Ao mudar uma extensão

Se uma versão nova passar a acessar outro host, a guardar alguma coisa no navegador ou a mandar dado para
fora, **a página dela precisa mudar junto** — a política é uma declaração de fato, não um texto de praxe,
e o Google compara os dois na revisão. A fonte do texto fica no repositório da extensão
(ex.: `privacy-policy.html`); a cópia publicada fica aqui.
