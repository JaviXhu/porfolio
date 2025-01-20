<template>
  <q-page class="q-pa-md">
    <!-- Background Particles -->
    <div id="particles-js"></div>

    <!-- Main Content Container -->
    <div class="background-container q-pa-md">
      <!-- Profile Section -->
      <div class="q-mb-md text-center">
        <q-img src="contacto/perfil.jpeg" class="q-mb-sm" style="border-radius: 50%;" alt="Profile Picture"
          width="15%"></q-img>
        <h1>Javier Ramos Acosta</h1>
        <q-chip class="q-mb-xs" color="secondary" label="Desarrollador Web" style="font-size: 1.5rem;" /><br>
        <q-chip class="q-mb-xs" color="yellow" label="Trabajando Actualemnte"
          style="font-size: 1rem; font-style: 'bold'" />
        <h6>javierrm.cn@gmail.com</h6>
      </div>


      <!-- Navigation Badges -->
      <div class="q-gutter-md q-mb-lg text-center">
        <q-chip class="q-mb-xs" color="primary" label="Mi Portafolio" to="/portfolio" round />
        <q-chip class="q-mb-xs" color="primary" label="Sobre Mí" to="/about" round />
        <q-chip class="q-mb-xs" color="primary" label="Mis Trabajos" to="/works" round />

        <q-chip class="q-mb-xs" color="primary" label="Conocimientos" to="/skills" round />
        <q-chip class="q-mb-xs" color="primary" label="Tecnologías" to="/technologies" round />
      </div>

      <!-- Sections -->
      <div class="q-gutter-md">



        <!-- About Me -->
        <q-card class="my-card">
          <q-card-section>
            <div class="text-h6 q-mb-sm">Sobre Mí</div>
            <p>Me llamo Javier Ramos Acosta, aunque en el mundillo todo el mundo me llama Javixhu, soy un desarrollador
              web canario con 3 años estudiando y trabajando en el
              mundo de la programación. <br>Siempre tengo ganas de aprender cosas nuevas y de emprender proyectos
              innovadores o que llamen mi atención.<br> Soy proactivo y me gusta trabajar en equipo, ya que considero
              que el
              trabajo se hace más llevadero.</p>
            <p>Cabe recalcar que me considero más team backend que frontend, aunque en mi trayectoria he trabajado como
              fullstack en casi todos los proyectos en los que he participado.</p>
            <p>Echa un vistazo a mis trabajos en la seccion <q-chip class="q-mb-xs" color="primary" label="Mis Trabajos"
                to="/works" round /></p>
          </q-card-section>
        </q-card>

        <!-- Technologies -->
        <q-card class="my-card q-mt-md" id="tecnologiasCaja">
          <q-card-section>
            <div class="text-h6 q-mb-sm">Tecnologías</div>
            <div class="tecnologias-flex">
              <div class="tecnologia-item">
                <q-img src="tecnologias/vue.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Vue.js</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/quasar.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Quasar</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/html5.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">HTML5</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/css.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">CSS</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/js.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">JavaScript</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/php.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">PHP</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/java.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Java</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/py.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Python</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/mysql.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">MySQL</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/laravel.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Laravel</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/wp.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">WordPress</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/sass.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">SASS</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/git.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">GIT</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/docker.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Docker</q-chip>
              </div>

              <div class="tecnologia-item">
                <q-img src="tecnologias/figma.png" class="tecnologia-icon" contain /><br>
                <q-chip class="q-mb-xs" color="primary">Figma</q-chip>
              </div>
            </div>
          </q-card-section>
        </q-card>



        <q-card class="my-card q-mt-md">
          <q-card-section>
            <div class="text-h6 q-mb-sm">Mis Trabajos</div>
            <p>Una selección de mis trabajos más destacados y proyectos realizados.</p>
          </q-card-section>
          <q-separator spaced />

          <q-card-section>
            <div class="row q-col-gutter-md" id="trabajos">
              <!-- Trabajo 1 -->
              <q-card class="col-12 col-md-4 q-mb-md my-work-card">
                <q-card-section>
                  <div class="row">
                    <div class="col-12" align="center">
                      <q-img src="yendo.jpg" class="q-mb-sm my-work-img" alt="Icono de Yendo La Palma" />
                      <div class="text-h6 q-mb-sm">Yendo La Palma</div>
                      <!-- Añadir chip aquí -->
                      <q-chip color="green" text-color="white" class="q-mb-sm">Activo</q-chip>
                    </div>
                    <div class="col-12">
                      <p class="my-work-text">Pide comida a tus restaurantes favoritos de forma rápida y sencilla.
                        Servicio de reparto a domicilio y recogida directa en restaurante.</p>
                    </div>
                  </div>
                </q-card-section>
                <q-separator />
                <q-card-actions align="center">
                  <q-btn flat label="Ver más" color="primary" />
                </q-card-actions>
              </q-card>

              <!-- Trabajo 2 -->
              <q-card class="col-12 col-md-4 q-mb-md my-work-card">
                <q-card-section>
                  <div class="row">
                    <div class="col-12" align="center">
                      <q-img src="pc.jpg" class="q-mb-sm my-work-img" alt="Icono de Protección Civil" />
                      <div class="text-h6 q-mb-sm">Protección Civil Los Llanos</div>
                      <!-- Añadir chip aquí -->
                      <q-chip color="green" text-color="white" class="q-mb-sm">Activo</q-chip>
                    </div>
                    <div class="col-12">
                      <p class="my-work-text">Programa de gestión de inventario, eventos, voluntarios, vehículos,
                        materiales y más. Esta aplicación facilita la organización y seguimiento de todos los recursos y
                        actividades, asegurando una administración eficiente y precisa.</p>
                    </div>
                  </div>
                </q-card-section>
                <q-separator />
                <q-card-actions align="center">
                  <q-btn flat label="Ver más" color="primary" />
                </q-card-actions>
              </q-card>

              <!-- Trabajo 3 -->
              <q-card class="col-12 col-md-4 q-mb-md my-work-card">
                <q-card-section>
                  <div class="row">
                    <div class="col-12" align="center">
                      <q-img src="bikestation.png" class="q-mb-sm my-work-img" alt="Icono de BikeStation La Palma" />
                      <div class="text-h6 q-mb-sm">BikeStation La Palma</div>
                      <!-- Añadir chip aquí -->
                      <q-chip color="green" text-color="white" class="q-mb-sm">Activo</q-chip>
                    </div>
                    <div class="col-12">
                      <p class="my-work-text">La diversión con la bici y el disfrutar juntos de la naturaleza es nuestro
                        primer propósito. Los experimentados guías les proporcionan una introducción sobre la técnica de
                        la bici y su manejo, y pueden contarles un montón sobre la isla.</p>
                    </div>
                  </div>
                </q-card-section>
                <q-separator />
                <q-card-actions align="center">
                  <q-btn flat label="Ver más" color="primary" />
                </q-card-actions>
              </q-card>

              <!-- Trabajo 4 -->
              <q-card class="col-12 col-md-4 q-mb-md my-work-card">
                <q-card-section>
                  <div class="row">
                    <div class="col-12" align="center">
                      <q-img src="bindify.png" class="q-mb-sm my-work-img" alt="Icono de Bindify" />
                      <div class="text-h6 q-mb-sm">Bindify</div>
                      <!-- Añadir chip aquí -->
                      <q-chip color="red" text-color="white" class="q-mb-sm">Inactivo</q-chip>
                    </div>
                    <div class="col-12">
                      <p class="my-work-text">La aplicación propuesta era una web para fomentar el comercio local, con
                        posibilidad de ver eventos y publicaciones de comercios e interactuar con ellos, seguir
                        comercios y marcarlos como favoritos, ver puntos de fidelidad con un comercio, recibir
                        notificaciones, dejar reseñas en comercios, comentarios en eventos y publicaciones.</p>
                    </div>
                  </div>
                </q-card-section>
                <q-separator />
                <q-card-actions align="center">
                  <q-btn flat label="Ver más" color="primary" />
                </q-card-actions>
              </q-card>

              <!-- Trabajo 5 -->
              <q-card class="col-12 col-md-4 q-mb-md my-work-card">
                <q-card-section>
                  <div class="row">
                    <div class="col-12" align="center">
                      <q-img src="shisha.png" class="q-mb-sm my-work-img" alt="Icono de Shisha POS" />
                      <div class="text-h6 q-mb-sm">Shisha POS</div>
                      <!-- Añadir chip aquí -->
                      <q-chip color="red" text-color="white" class="q-mb-sm">Inactivo</q-chip>
                    </div>
                    <div class="col-12">
                      <p class="my-work-text">Aplicación POS (Punto de venta) diseñada para la venta de cócteles,
                        shishas y copas.</p>
                    </div>
                  </div>
                </q-card-section>
                <q-separator />
                <q-card-actions align="center">
                  <q-btn flat label="Ver más" color="primary" />
                </q-card-actions>
              </q-card>
            </div>
          </q-card-section>
        </q-card>


        <!-- Experiencia -->
        <q-card class="my-card q-mt-md">
          <q-card-section>
            <div class="text-h6 q-mb-sm">Experiencia Laboral</div>
            <div class="text q-mb-sm" style="color: #03EAFF">2 AÑOS COMO DESAROLLADOR WEB</div>
            <div class="timeline">
              <!-- Ejemplo de experiencia laboral -->
              <div class="timeline-item" v-for="(item, index) in experiences" :key="index">
                <div class="timeline-title" style="color: #03EAFF">{{ item.title }}</div>
                <div class="timeline-description">{{ item.description }}</div>
              </div>
            </div>
          </q-card-section>
        </q-card>


        <!-- Porfolios de alguno de mis compañeros -->
        <q-card class="my-card q-mt-md">
          <q-card-section>
            <div class="text-h6 q-mb-sm">Porfolios de Algunos de Mis Compañeros</div>
            <div class="row q-col-gutter-md" style="display: flex; justify-content: space-around; margin-top: 1%;">
              <!-- Ejemplo de portafolios -->
              <div class="col-12 col-md-6 col-lg-3">
                <div class="portfolio-item">
                  <img src="perfilCompañeros/aron.png" alt="Aarón" class="portfolio-img" /><br>
                  <q-chip class="q-mt-xs" color="green" label="Aarón " />
                </div>
              </div>
              <div class="col-12 col-md-6 col-lg-3">
                <div class="portfolio-item">
                  <img src="perfilCompañeros/david.jpeg" alt="David Martín" class="portfolio-img" /><br>
                  <q-chip class="q-mt-xs" color="green" label="David" />
                </div>
              </div>
              <div class="col-12 col-md-6 col-lg-3">
                <div class="portfolio-item">
                  <img src="perfilCompañeros/antonio.webp" alt="Antonio" class="portfolio-img" /><br>
                  <q-chip class="q-mt-xs" color="green" label="Antonio" />
                </div>
              </div>

            </div>
          </q-card-section>
        </q-card>

        <!-- Contacto -->
        <q-card class="my-card q-mt-md">
          <q-card-section>
            <div class="text-h6 q-mb-sm text-center">Contacto</div>
            <div class="q-gutter-sm row items-center" style="display: flex; justify-content: center;">
              <!-- Gmail Icon -->
              <img src="contacto/gmail.png" alt="contacto 1" class="contacto-img" />
              <!-- LinkedIn Icon -->
              <img src="contacto/linkedin.png" alt="contacto 1" class="contacto-img" />
              <!-- github Icon -->
              <img src="contacto/github.jpeg" alt="contacto 1" class="contacto-img" /><br>
            </div>
          </q-card-section>
        </q-card>




      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PortfolioPage',
  mounted() {
    this.loadParticlesJS();
  },
  data() {
    return {
      experiences: [
        { title: 'Desarrollo Frontend', description: 'Desarrollo de interfaces y componentes web utilizando tecnologías modernas como Vue.js , Quasar, React, Tailwind.(Bindify , Yendo , Bike-Station-La-Palma)' },
        { title: 'Desarrollo Backend', description: 'Implementación de servicios y APIs en el servidor utilizando Node.js y Laravel.(Bindify , Yendo , Proteccion Civil Los Llanos)' },
        { title: 'Gestión de Proyectos', description: 'Coordinación de equipos de desarrollo y gestión de proyectos utilizando metodologías ágiles(Bindify).' },
        { title: 'Comercial Electrica Canarias S.A', description: 'Puesto de comercial , trabajando como dependiente , conductor , y comercial telefonico' }
      ]
    }
  },
  methods: {
    loadParticlesJS() {
      const script = document.createElement('script');
      script.src = 'https://cdnjs.cloudflare.com/ajax/libs/particles.js/2.0.0/particles.min.js';
      script.onload = () => {
        particlesJS('particles-js', {
          particles: {
            number: {
              value: 100,
              density: {
                enable: true,
                value_area: 500
              }
            },
            color: {
              value: '#03EAFF'
            },
            shape: {
              type: 'circle',
              stroke: {
                width: 0,
                color: '#000000'
              },
              polygon: {
                nb_sides: 5
              },
              image: {
                width: 100,
                height: 100
              }
            },
            opacity: {
              value: 0.5,
              random: false,
              anim: {
                enable: false,
                speed: 1,
                opacity_min: 0.1,
                sync: false
              }
            },
            size: {
              value: 5,
              random: true,
              anim: {
                enable: false,
                speed: 40,
                size_min: 0.1,
                sync: false
              }
            },
            line_linked: {
              enable: true,
              distance: 150,
              color: '#ffffff',
              opacity: 0.4,
              width: 1
            },
            move: {
              enable: true,
              speed: 6,
              direction: 'none',
              random: false,
              straight: false,
              out_mode: 'out',
              attract: {
                enable: false,
                rotateX: 600,
                rotateY: 1200
              }
            }
          },
          interactivity: {
            detect_on: 'canvas',
            events: {
              onhover: {
                enable: true,
                mode: 'repulse'
              },
              onclick: {
                enable: true,
                mode: 'push'
              },
              resize: true
            },
            modes: {
              grab: {
                distance: 400,
                line_linked: {
                  opacity: 1
                }
              },
              bubble: {
                distance: 400,
                size: 40,
                duration: 2,
                opacity: 8,
                speed: 3
              },
              repulse: {
                distance: 100
              },
              push: {
                particles_nb: 4
              },
              remove: {
                particles_nb: 2
              }
            }
          },
          retina_detect: true,
          config_demo: {
            hide_card: false,
            background_color: '#b61924',
            background_image: '',
            background_position: '50% 50%',
            background_repeat: 'no-repeat',
            background_size: 'cover'
          }
        });
      };
      document.head.appendChild(script);

    }
  }

};
</script>

<style scoped lang="scss">
body,
html {
  height: 100%;
  margin: 0;
  background: black;
  color: #fff;
}

#particles-js {
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: center;
  position: fixed;
  background-color: black;
  top: 0;
  z-index: 1;
}

.background-container {
  position: relative;
  z-index: 2;
}

h1 {
  font-family: 'Montserrat', sans-serif;
  font-size: 3rem;
  font-weight: bold;
  color: #fff;
}

h6 {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.5rem;
  color: #ccc;
}

h5 {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.5rem;
  color: #ccc;
}

.my-card {
  background-color: rgba(0, 0, 0, 0.8);
  color: #fff;
  border-radius: 8px;
  padding: 1rem;
}

.my-work-card {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 1%;
  color: black;
  max-width: 400px;
}

.my-work-img {
  width: 100px;
  /* Adjust the size as needed */
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
}

.my-work-text {
  font-weight: bold;
  font-size: 0.9rem;
  /* Adjust the size as needed */
  display: flex;
  justify-content: center;
  align-items: center;
}

#textoCard {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 3%;
}

#trabajos {
  display: flex;
  justify-content: space-around;
  margin: 1%;
}

.tecnologias {
  display: flex;
  flex-direction: column;
}

.tecnologias-flex {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  /* Centra los elementos horizontalmente */
  align-items: center;
  /* Centra los elementos verticalmente */
  gap: 16px;
  /* Espacio entre los elementos */
}

.tecnologia-item {
  flex: 1 0 150px;
  /* Los elementos ocupan al menos 150px y pueden crecer */
  max-width: calc(33.333% - 16px);
  /* Tres elementos por fila en pantallas grandes */
  text-align: center;
  box-sizing: border-box;
  /* Incluye padding y border en el ancho total */
}

.tecnologia-icon {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-bottom: 8px;
  /* Espacio entre el icono y el chip */
  object-fit: cover;
}

/* Responsive adjustments */
@media (max-width: 1200px) {
  .tecnologia-item {
    max-width: calc(25% - 16px);
    /* Cuatro elementos por fila en pantallas medianas */
  }
}

@media (max-width: 900px) {
  .tecnologia-item {
    max-width: calc(50% - 16px);
    /* Dos elementos por fila en pantallas pequeñas */
  }
}

@media (max-width: 600px) {
  .tecnologia-item {
    max-width: calc(100% - 16px);
    /* Un elemento por fila en pantallas extra pequeñas */
  }
}




.timeline {
  position: relative;
  padding: 10px 0;
  margin-left: 20px;
}

.timeline-item {
  position: relative;
  margin: 20px 0;
  padding: 10px 20px;
  border-left: 2px solid #007bff;
  animation: fadeIn 0.5s ease-in-out;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: -7px;
  top: 10px;
  width: 14px;
  height: 14px;
  background: #007bff;
  border-radius: 50%;
}

.timeline-title {
  font-weight: bold;
  color: #333;
}

.timeline-description {
  margin-top: 5px;
  color: #666;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.portfolio-item {
  text-align: center;
  margin: 10px 0;
}

.portfolio-img {
  border-radius: 50%;
  width: 100px;
  /* Tamaño de la imagen */
  height: 100px;
  /* Tamaño de la imagen */
  object-fit: cover;
  border: 2px solid #007bff;
}

.q-chip {
  font-size: 14px;
}

.contacto-img {
  border-radius: 50%;
  width: 50px;

  /* Tamaño de la imagen */
  height: auto;
  /* Tamaño de la imagen */
  object-fit: cover;
  border: 2px solid #007bff;
}

.q-img {
  width: 25%;
  max-width: 250px;
  /* Tamaño máximo para pantallas grandes */
  min-width: 80px;
  /* Tamaño mínimo para pantallas pequeñas */
  aspect-ratio: 1;
  /* Asegura que el contenedor mantenga proporción 1:1 */
  border-radius: 50%;
  /* Hace que sea un círculo */
  object-fit: cover;
  /* Ajusta la imagen para llenar el contenedor */
  display: block;
  /* Evita problemas de alineación */
  margin: 0 auto;
  /* Centra horizontalmente */
}
</style>
