# Exercício-04:

## Contatos frequentemente contatados

Utilizando o array `contatos` encontrado no `<script>` do arquivo HTML encontrado nessa pasta, construa uma página com no mínimo elementos já presentes no arquivo HTML.

Você deve:
1. Ordenar o array `contatos` de modo que os 5 primeiros itens sejam os contatos que tenham o maior número de `mensagens`;
2. Criar um novo array com apenas os primeiros 5 elementos do array `contatos` depois de ordenado;
3. Preenchecer os `<li>`s com os dados dos contatos (imagem, nome e descrição);

**Neste exercício usaremos:**
 - seletor de elementos da DOM
 - manipulação de texto dos elementos
 - manipulação de atributo dos elementos

<details>
  <summary>Dicas</summary>
  <ul>
    <li>Podemos usar a função <code>sort()</code> para ordenar o array</li>
    <li>Podemos usar a função <code>slice()</code> para criar um novo array com apenas os primeiros 5 elementos</li>
    <li>Podemos selecionar todos os itens da lista com <code>document.querySelectorAll('li')</code>, dar um loop na lista retornada e para cada item da lista executarmos um <code>document.querySelector()</code> em cada elemento do item da lista</li>
  </ul>
</details>

---

###### tags: `front-end` `módulo 2` `exercício de casa` `DOM` `JS`
