## **README.md - Cat Cafés em São Paulo**

### **Descrição**

este projeto web é um diretório simples que contém os arquivos necessários para criar um site que lista cat cafés em São Paulo. O site permite que os usuários pesquisem por cat cafés usando palavras-chave e exibe os resultados da pesquisa de forma organizada. Este projeto foi feito durante o curso Imersão Dev da Alura.

### **Estrutura do Projeto**

* **index.html:** o arquivo principal que contém a estrutura HTML do site, incluindo o cabeçalho, o corpo e o rodapé.
* **styles.css:** o arquivo CSS que contém as regras de estilo para estilizar a aparência do site.
* **dados.js:** um arquivo JavaScript que contém um array de objetos, cada um representando um cat café com informações como título, descrição, tags e link.
* **app.js:** o arquivo JavaScript principal que contém a lógica para a pesquisa e a exibição dos resultados.

### **Como Funciona**

1. **Interface do Usuário:**
   * o usuário digita uma palavra-chave no campo de pesquisa.
   * ao clicar no botão "Pesquisar", a função `pesquisar()` em `app.js` é chamada.

2. **Lógica de Pesquisa:**
   * a função `pesquisar()` pega o valor digitado pelo usuário e converte tudo para letras minúsculas para facilitar a comparação.
   * a função itera sobre cada objeto no array `dados` e compara a palavra-chave com o título, descrição e tags de cada cat café.
   * se houver correspondência, um novo elemento HTML é criado e adicionado à seção de resultados, exibindo o título, descrição e um link para o cat café.

3. **Exibição dos Resultados:**
   * os resultados da pesquisa são exibidos na seção `resultados-pesquisa` do HTML.
   * se não houver resultados, uma mensagem é exibida informando o usuário.

### **Como Executar o Projeto**

1. **Criar um servidor local:**
   * você pode usar um servidor local como o Live Server do Visual Studio Code ou o Python com o módulo `http.server` para servir os arquivos do projeto.
2. **abrir o arquivo index.html no navegador:**
   * abra o arquivo `index.html` em seu navegador para visualizar o site.

### **Personalização**

* **Dados dos Cat Cafés:**
  * para adicionar ou modificar informações sobre os cat cafés, edite o arquivo `dados.js`.
* **Estilo:**
  * para personalizar a aparência do site, edite o arquivo `styles.css`.
* **Funcionalidades Adicionais:**
  * você pode adicionar funcionalidades como filtros, ordenação, ou até mesmo um mapa para localizar os cat cafés.

### **Observações**

* este é um projeto simples para fins demonstrativos. Para um site mais robusto, você pode considerar usar um framework como React ou Vue.
* para melhorar a experiência do usuário, você pode adicionar mais informações sobre cada cat café, como horário de funcionamento, preços e fotos.
* é importante garantir que os dados dos cat cafés estejam atualizados e sejam precisos.

**Este README.md fornece uma visão geral do projeto e pode ser usado como ponto de partida para futuras melhorias.**

**Para uma experiência mais completa, sugiro que você explore os seguintes tópicos:**

* **HTML:** estrutura básica de uma página web.
* **CSS:** estilização de elementos HTML.
* **JavaScript:** lógica de programação para interagir com o DOM.
* **Git:** controle de versão para gerenciar o código do projeto.
