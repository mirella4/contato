# contato<!DOCTYPE html>
  <html lang="pt-br">
      <head>
          <meta charset="UTF-8">
          <title>contatos - Barbearia Alura</title>
          <link rel="stylesheet" href="style-contato">
      </head>
      <body>
          <header>
             <div class="caixa">
              <h1><img src="https://gitricardosantos.github.io/Barbearia/logo.png"></h1>
  <nav>
              <ul>
                  <li><a href="https://roselainerohling.github.io/Alura-Barbearia/index.html">Home</a></li>
                  <li><a href="https://roselainerohling.github.io/Alura-Produtos/index.html">Produtos</a></li>
                  <li><a href="http://www.google.com/maps/">Contato</a></li>
              </ul>
            </nav>
             </div>
          </header>
         <main>
   <form>
     <label for="nomesobrenome">Nome e sobrenome</label>
     <input type="text"id="nomesobrenome">
     <label for="email">Email</label>
     <input type="text"id="email">
     <label for="telefone">Telefone</label>
     <input type="text"id="telefone">
     <label for="mensagem">Mensagem</label>
     <textarea cols="70"rows="10"id="mensagem"
               class="input-padrao"></textarea>
 <div>
   <p>Como prefere o nosso contato?</p>
   <label for="radio-email">
     <input type="radio"name="contato"value="email"id="radio-email">
     Email
     </labe>
  <label for="radio-telefone">
     <input type="radio"name="contato"value="telefone"id="radio-telefone">
     Telefone
     </labe>
     <label for="radio-whatsapp">
     <input type="radio"name="contato"value="whatsapp"id="radio-whatsapp">
     Whatsapp
     </labe>
     </div>
     <div>
       <p>Qual horário prefere ser atendido?</p>
       <select>
         <option>Manhã</option>
         <option>Tarde</option>
         <option>Noite</option>
       </select>
     </div>
     <label class="checkbox">
       <input type="checkbox">
       Gostaria de receber nossas novidades por email?
     </label>
     <input type="submit"value="Enviar Formulario" class="enviar">
           </form>
        </main>

   </main>
         <footer>
 
         <footer>
    <img src="https://smee.com.br/mario/logo-branco.png">
    <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
</footer>
         </body>
     </html>
