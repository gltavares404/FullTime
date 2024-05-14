
import router from '@/router';
<template style="background-color: rgba(15,15,15);">
  <main style="background-color: rgba(15,15,15);">  
    <nav class="navbar navbar-expand-lg bg-body-" style="justify-content: center; align-items: center; background-color: rgba(37,37,37); border: rgba(37,37,37); color: white">
  <div class="container-fluid" style="justify-content: center; align-items: center; background-color: rgba(37,37,37)">
    <img src="/src/img/logo.png" style="width: 90px; margin: 16px;">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent" style="background-color: rgba(37,37,37);">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link class="nav-link" to="/"  style="color: gray;">Página Inicial</router-link>        </li>
        <li class="nav-item">
          
          <router-link class="nav-link" to="/about" aria-current="page" style="color: white;">Histórico de Pedidos</router-link>
        </li>
        <!-- <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Histórico de Pedidos
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li> -->
      </ul>
      <form class="d-flex" role="search" style="color: white; align-items: center;">
        <input class="form-control me-2" type="search" placeholder="" aria-label="Search" style="background-color: rgba(30,30,30); border: none; color: white;">
        <button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Buscar</button>
      </form>
      <div style="display: flex; padding: 10px;align-items: center; justify-content: space-between; flex-direction: row;">
        <img src="/src/img/dog.jpg" style="width: 48px; border-radius: 48px; margin: 10px;">
      </div>
      <router-link class="nav-link" to="/login">Sair</router-link>
    </div>
  </div>
</nav>

  
  
  <h2 style="text-align: left; padding-top: 20px; font-weight: 900;  margin-left: 100px; color: white">
    Histórico de Pedidos
  </h2>
  <p style="text-align: left; font-weight: 500; color: gray; padding-bottom: 20px;  margin-left: 100px">Confira o seu histórico de entregas</p>
<div class="tabela" style="display: flex;">
  <table class="table table-dark table-hover" style="padding: 20px; margin-left: 100px; margin-right: 100px; width: 90%; ">
    <thead style="padding: 20px;">
      <tr>
        <th scope="col">ID</th>
        <th scope="col">Título</th>
        <th scope="col">Endereço</th>
        <th scope="col">Horário</th>
        <th scope="col">Data</th>
        <th scope="col">Confirmação</th>


      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1</th>
        <td>Mesa de madeira</td>
        <td>Rua Cachorro Feliz, 450</td>
        <td>15h00</td>
        <td>22/04/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">2</th>
        <td>Mudança Gigante</td>
        <td>Rua Nova Marília, 387</td>
        <td>11h00</td>
        <td>05/06/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>


      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Espelho Grande</td>
        <td>Rua Presidente Prudente, 50</td>
        <td>13h40</td>
        <td>14/12/2024</td>
        <td><button style="border: none; background-color: rgb(240, 36, 36); padding: 6px; color: white; font-weight: 500; border-radius: 4px; box-shadow: 2px 2px 1px rgb(150, 36, 36);">Imagem</button></td>

      </tr>
      
    </tbody>
  </table>
</div>
  </main>
</template>