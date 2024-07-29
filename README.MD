                                        Proyecto sobre la pagina de nike
 # Ocupa solo imagenes de la pagina oficial
 # Los dos elementos de boostrap requeridos son el NAV y el carrousel
 # Las 3 paginas requeridas son: Productos de hombre, mujer y niños. Junto con una seccion de login.
 # Los iconos implementados son en formato SVG



 .container{
  display: flex;
  flex-direction: row-reverse;
  margin: 0;
  padding: 0;
    &>aside{
        width: 30%;
        height: 100%;
        background-color: #0f0f0f;
        margin: 0;
        padding: 0;
        h2{
            color: white;
            font-family: "Montserrat", sans-serif;
            font-size: 24px;
            font-weight: 300;
            padding-top: 15px;
            display: flex;
            justify-content: center;
            align-items: center;
            
        }
        hr{
            color: white;
        }
        .hr_2{
            width: 80%;
        }
    
        ul{
           list-style: none;
           &>li{
            &>a{
                color: #c97c2a;
                text-decoration: none;
                &:hover{
                    color: #775d08;
                }
            }
           }
        }
      }

      .productos_hombre{
        width: 100%;
        height: 100vh;
        margin: 0;
        
      }
}
  
 