<template>
  <section id="asistir">
    <div class="q-pa-xl">
      <div class="column wrap items-center">
        <div style="width: 120vh;">
          <p>
            <span class="text-h5 text-weight-bold" style="color: var(--q-primary)">VENUE</span>
          </p>
        </div>

        <div class="row" style="width: 120vh;">
          <div class="col-8">
            <p>
              La Pycamp se realizará en {{ $store.state.asistir_lugar }}
            </p>

            <p>
              <span class="text-weight-bold">
                Nombre
              </span><br>
              {{ $store.state.asistir_nombre_lugar }}
            </p>

            <p>
              <span class="text-weight-bold">
                Dirección
              </span><br>
              {{ $store.state.asistir_direccion }}
            </p>

            <p>
              <span class="text-weight-bold">
                Descripción
              </span><br>
              <span class="justify-center">
                {{ $store.state.asistir_descripcion }}
              </span>
            </p>

            <p>
              <span class="text-weight-bold">
                Capacidad máxima
              </span><br>
              {{ $store.state.asistir_cap_max }} personas
            </p>

            <p>
              <span class="text-weight-bold">
                Comida
              </span><br>
              {{ $store.state.asistir_comida }}
            </p>

            <p>
              <span class="text-weight-bold">
                ¿Cómo llegar?
              </span><br>
                Recopilamos un poco de información para llegar desde Barcelona al Bosc de La Massana. El tiempo de viaje es de entre 1h 30m y 2h 30m aproximadamente y consiste de 3 tramos.
            </p>
            <p style="text-decoration: underline;">Entre Barcelona y Girona</p>
            <p>
            </p>
            <p>
              <ul>
                <li>Tren rápido AVANT (AVE): 18€ -- ~40 minutos de viaje. Horarios y reserva en Renfe.</li>
                <li>Tren Regional: 8.40€ -- ~1h 30m de viaje. Horarios en Renfe. El billete se compra en la estación.</li>
                <li>Tren Media Distancia: 11.25€ -- ~1h 20m de viaje. Horarios en Renfe. Tiene más frecuencia que el Tren Regional. El billete se compra en la estación.</li>
                <li>Todos los trenes salen desde Estació Sants y te dejan en la estación Girona.</li>
              </ul>
            </p>

            <p style="text-decoration: underline;">Entre Girona y Salt</p>
            <p>
              <ul>
                <li>Autobús L4 entre parada Plaça Marquès de Camps (Girona) y parada Espai Gironès (Salt) (1.4€ -- ~15 minutos de viaje). Solo funciona de Lunes a Sábados. Horarios en Adjuntament Girona. El billete se compra directamente en el autobús.</li>
                <li>Entre Salt y El Bosc de la Massana</li>
                <li>Caminar 1.4 km -- ~18 min.</li>
              </ul>
            </p>
          </div>

          <div class="column wrap justify-around q-pl-md">
              <div class="row q-pb-md">
                <img 
                  src="@/assets/foto_venue_1.jpg"
                  class="q-pt-sm"
                >
              </div>

              <div class="row q-pb-md">
                <img 
                  src="@/assets/foto_venue_2.jpg"
                  class="q-pt-sm"
                >
              </div>

              <div class="row q-pb-md">
                <img 
                  src="@/assets/foto_venue_3.jpg"
                  class="q-pt-sm"
                >
              </div>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<style scoped>
  .center-button {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 75%;
  }

  img {
    width: 285px;
    height: auto;
  }


</style>

<script>
  export default {
    name: 'MasInfo'
  }
</script>
