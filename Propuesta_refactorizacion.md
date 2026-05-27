# Refactorizacion de las cookies

<div class="fondo-espacio-cookies" style="display:none;" data-nosnippet>
  <div class="espacio-cookies">
    <div class="espacio-cookies-scroll">

      <div class="informacion-general-cookies">
        <p>Este sitio web utiliza cookies para mejorar su experiencia. Las cookies
        necesarias se almacenan en su navegador por ser esenciales para el
        funcionamiento básico. También usamos cookies de terceros para analizar
        el uso del sitio, que se almacenarán solo con su consentimiento. Puede
        optar por no recibirlas, aunque esto puede afectar su navegación.</p>
      </div>

Los cambios principales respecto al original son: HTML más limpio sin IDs crípticos, JS sin jQuery (nativo), lógica de selección centralizada en getCookieSelections(), 
y eliminación de código duplicado entre los tres botones.


# Refactorizacion del footer

<div class="contenedor_subvencion_superior">
  <div class="container">
    <div class="row">
      <div class="subvencion_superior">

        <div class="col-xs-12 col-sm-12 col-md-4">
          <figure>
            <img src="https://www.pisapapeles.es/upload/img/subvencion/es_financiado_por_la_union_europea_rgb_pos.png"
                 alt="Financiado por la Unión Europea - Next Generation EU">
          </figure>
        </div>

        <div class="col-xs-12 col-sm-12 col-md-4">
          <figure>
            <img src="https://www.pisapapeles.es/upload/img/subvencion/logo-prtr-tres-lineas_color.png"
                 alt="Plan de Recuperación, Transformación y Resiliencia">
          </figure>
        </div>

      </div>
    </div>
  </div>
</div>
