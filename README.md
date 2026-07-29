# 🛡️ Guía Operativa Integral del Sistema Quirón

Esta guía está destinada al personal para la correcta carga, clasificación de hechos delictivos y estandarización de criterios operativos en el sistema Quirón.

---

## 📑 SECCIÓN 1: Instrucciones de Carga por Campo

<details>
<summary><b>📖 Ver Guía de Campos del Sistema Quirón (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left" width="25%">Campo</th>
    <th align="left" width="75%">Criterio y Instrucciones de Carga</th>
  </tr>
  <tr><td><b>Partido</b></td><td>Seleccionar el partido donde fue cometido el hecho (desplegable).</td></tr>
  <tr><td><b>Localidad</b></td><td>Seleccionar la localidad donde fue cometido el hecho (desplegable).</td></tr>
  <tr><td><b>Jurisdicción</b></td><td>Seleccionar la dependencia policial a la que le corresponde el lugar del hecho (dependencia interviniente).</td></tr>
  <tr><td><b>Lugar del hecho</b></td><td>Dirección exacta donde se cometió el hecho.</td></tr>
  <tr><td><b>Coordenadas</b></td><td>Se cargan de manera automática; de lo contrario, utilizar Google Maps para buscar y copiar las coordenadas exactas.</td></tr>
  <tr><td><b>Fecha del hecho</b></td><td>Colocar la fecha en que fue cometido el hecho (o fecha de denuncia si se desconoce con precisión).</td></tr>
  <tr><td><b>Hora del hecho</b></td><td>Horario en el que ocurrió el hecho. Si no consta en el acta, colocar excepcionalmentel el horario de carga en el SID. <br><b>Franjas horarias de análisis:</b> 00:00 a 06:00 hs, 06:00 a 12:00 hs, 12:00 a 18:00 hs, y 18:00 a 24:00 hs.</td></tr>
  <tr><td><b>Tipo de lugar</b></td><td>Locación física del ilícito (finca, vía pública, comercio, establecimiento educativo, etc.) mediante desplegable.</td></tr>
  <tr><td><b>Carátula</b></td><td>Calificación legal del hecho (desplegable). <i>Tildar la casilla correspondiente en caso de ser en grado de tentativa.</i></td></tr>
  <tr><td><b>Modalidad</b></td><td>Colocar según el instructivo técnico correspondiente a cada delito analizado.</td></tr>
  <tr><td><b>Imputados</b></td><td>Registrar Femenino/Masculino. Si son varios o de distintos géneros, consignar ambos. El número exacto y desglose se detalla en Observaciones.</td></tr>
  <tr><td><b>Víctimas</b></td><td>Registrar Femenino/Masculino y consignar ambos si corresponde. Detallar cantidad y menores en Observaciones.</td></tr>
  <tr><td><b>Menores</b></td><td>Registrar Femenino/Masculino. Detallar desglose de cantidad y género en Observaciones si es necesario.</td></tr>
  <tr><td><b>Lesionados</b></td><td>Registrar Sí o No. En Observaciones se especifica el tipo de lesión (golpes, arma de fuego, arma blanca). Exclusivamente hechos dolosos.</td></tr>
  <tr><td><b>Armas</b></td><td>Tipificar el elemento utilizado: Fuego, Blanca o Impropia.</td></tr>
  <tr><td><b>Observaciones</b></td><td>Campo abierto para volcar todo dato relevante, número exacto de víctimas/imputados discriminados por género, hallazgos de rodados, etc.</td></tr>
</table>
</details>

---

## 🔍 SECCIÓN 2: Buscador de Carátulas y Modalidades

Escriba en la caja para filtrar de forma inmediata cualquier delito, modalidad o criterio operativo:

<div style="margin: 20px 0;">
  <input type="text" id="buscadorGuia" onkeyup="filtrarGuia()" placeholder="🔍 Escriba aquí (ej: motochorro, estruche, estafa, arma...)" style="width: 100%; padding: 12px; font-size: 16px; border: 2px solid #ccc; border-radius: 6px;">
</div>

<div id="contenedorGuia">

<details open>
<summary><b>ROBO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Escruche</b></td><td>Ingreso a viviendas en ausencia de los propietarios con uso de fuerza sobre un acceso.</td></tr>
  <tr><td><b>Entradera</b></td><td>Delincuentes sorprenden a las víctimas en el acceso a sus domicilios haciéndolas ingresar.</td></tr>
  <tr><td><b>Asalto en Finca</b></td><td>Víctimas sorprendidas en el interior de sus domicilios o propiedad.</td></tr>
  <tr><td><b>Asalto en Vía Pública</b></td><td>Hechos en espacio público con ejercicio de violencia mediante intimidación de arma.</td></tr>
  <tr><td><b>Asalto en Comercio</b></td><td>Interior de comercios con ejercicio de violencia e intimidación con arma.</td></tr>
  <tr><td><b>Motochorros</b></td><td>Víctimas abordadas por delincuentes movilizados en motovehículo.</td></tr>
  <tr><td><b>Roba Cables</b></td><td>Sustracción específica de cables (tendido eléctrico, TV, internet, etc.).</td></tr>
  <tr><td><b>Robo Simple</b></td><td>Sustracción con violencia donde el objetivo es el elemento y no la persona (medidores, caños de gas, garrafas, herramientas).</td></tr>
  <tr><td><b>Roba Ruedas</b></td><td>Sustracción exclusiva de ruedas del automotor (la rueda de auxilio interna va en "Pertenencias").</td></tr>
  <tr><td><b>Rompevidrios</b></td><td>Ruptura de cristales de vehículos estacionados para sustraer elementos del interior.</td></tr>
  <tr><td><b>Pertenencias en Vehículos</b></td><td>Sustracción de elementos del interior de automóviles mediante forzamiento de cerraduras, puertas o uso de inhibidores (sin rotura de vidrios).</td></tr>
  <tr><td><b>Bicicleta</b></td><td>Sustracción de bicicletas mediante robo (con violencia o amenaza).</td></tr>
  <tr><td><b>Choferes / Repartidores</b></td><td>Atentados a choferes de transporte público, taxis, remises, apps (DiDi, Uber) o repartidores (Rappi, etc.).</td></tr>
  <tr><td><b>Salidera Bancaria</b></td><td>Asalto tras realizar extracción de dinero en banco o cajero automático.</td></tr>
  <tr><td><b>Piraña</b></td><td>Actuación conjunta, rápida y violenta de varios sujetos sobre la víctima u objetivo.</td></tr>
  <tr><td><b>Viuda Negra</b></td><td>Vínculo de confianza intencional para acceder al domicilio y suministrar sustancias de somnolencia para sustraer bienes.</td></tr>
  <tr><td><b>Piratas del Asfalto</b></td><td>Ilícitos cometidos contra camiones que transportan mercadería en rutas.</td></tr>
  <tr><td><b>Piratas Urbanos</b></td><td>Delincuentes en zonas urbanas contra vehículos de reparto menor o paquetería (Mercado Libre, correo) sin logística compleja.</td></tr>
  <tr><td><b>Arrebatador / Simple / Otros</b></td><td>Arrebato con violencia física o asaltos generales no encuadrados en categorías previas (incluye mechera con violencia, polichorro, punga con forcejeo).</td></tr>
</table>
</details>

<details>
<summary><b>HURTO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Arrebatador / Oportunista</b></td><td>Sustracción rápida al paso y de manera inmediata sin que la víctima tenga tiempo de reaccionar, o aprovechando bienes momentáneamente desatendidos.</td></tr>
  <tr><td><b>Patentes</b></td><td>Sustracción específica del dominio (chapa patente) del vehículo.</td></tr>
  <tr><td><b>Mechera</b></td><td>Sustracción en comercios ocultando mercadería entre prendas, cuerpo o efectos personales sin violencia física.</td></tr>
  <tr><td><b>Punga</b></td><td>Sustracción de pequeñas cosas (carteras, billeteras, celulares) en lugares concurridos mediante habilidad y sigilo.</td></tr>
  <tr><td><b>Hurto / Pertenencias / Bicicletas</b></td><td>Sustracción simple por descuido o puerta abierta, de efectos en vehículos/viviendas sin violencia sobre ingresos, o bicicletas sin medidas de seguridad.</td></tr>
</table>
</details>

<details>
<summary><b>HOMICIDIO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Femicidio</b></td><td>Asesinato de una mujer por cuestiones de género.</td></tr>
  <tr><td><b>Intrafamiliar</b></td><td>Muerte de uno o más miembros de una familia a manos de otro de la misma.</td></tr>
  <tr><td><b>En Riña</b></td><td>Muerte resultante en el marco de una riña o agresión con más de dos participantes.</td></tr>
  <tr><td><b>En ocasión de Robo</b></td><td>Homicidio producido con motivo u ocasión de un robo en curso.</td></tr>
  <tr><td><b>Ajuste de Cuentas</b></td><td>Asesinato premeditado para vengar un agravio o deuda pendiente.</td></tr>
  <tr><td><b>Simple / Indeterminado</b></td><td>Homicidio doloso tradicional sin agravantes específicas o bajo investigación preliminar.</td></tr>
</table>
</details>

<details>
<summary><b>SUSTRACCIÓN AUTOMOTOR Y MOTOVEHÍCULOS (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Asalto</b></td><td>Robo del rodado al propietario mediante intimidación (aclarar hallazgo en observaciones).</td></tr>
  <tr><td><b>Levantamiento</b></td><td>Sustracción del rodado estacionado en vía pública sin moradores (llaves amaestradas, puenteo, remolque).</td></tr>
  <tr><td><b>Motochorro</b></td><td>Sustracción de auto o moto perpetrada por masculinos a bordo de motocicletas.</td></tr>
  <tr><td><b>Hallazgo</b></td><td>Aparición de rodado (aclarar en observaciones si fue de manera inmediata).</td></tr>
</table>
</details>

<details>
<summary><b>ENFRENTAMIENTOS (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>En ocasión de Robo</b></td><td>Víctima repele ilícito con arma de fuego (aclarar si es personal policial en observaciones).</td></tr>
  <tr><td><b>Ajuste de Cuentas</b></td><td>Enfrentamiento armado para vengar agravio o deuda.</td></tr>
  <tr><td><b>Procedimiento Policial</b></td><td>Enfrentamiento directo entre personal policial y delincuentes.</td></tr>
  <tr><td><b>En Riña</b></td><td>Disputa armada en el marco de una reyerta grupal.</td></tr>
  <tr><td><b>Bandas Antagónicas</b></td><td>Enfrentamiento entre dos grupos rivales por disputas territoriales o barriales.</td></tr>
</table>
</details>

<details>
<summary><b>ESTAFA (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Informática</b></td><td>Fraudes perpetrados a través de medios digitales (MarketPlace, WhatsApp, redes, phishing, etc.) sin contacto presencial.</td></tr>
  <tr><td><b>Cuento del Tío</b></td><td>Engaño que puede iniciarse de forma virtual (llamadas/mensajes) pero se concreta de manera presencial.</td></tr>
  <tr><td><b>Otros</b></td><td>Demás engaños defraudatorios no incluidos en las anteriores.</td></tr>
</table>
</details>

<details>
<summary><b>ABUSO SEXUAL Y DELITOS CONTRA LA INTEGRIDAD (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Simple</b></td><td>Atentados contra el pudor o tocamientos sin acceso carnal (aclarar contexto en observaciones: familiar, vía pública, etc.).</td></tr>
  <tr><td><b>Con Acceso Carnal</b></td><td>Acceso por vía vaginal, anal o bucal con fuerza o intimidación.</td></tr>
  <tr><td><b>Estupro</b></td><td>Relación sexual con menor adolescente (13 a 16 años) sin violencia física, aprovechando inmadurez/confianza donde no hay consentimiento válido.</td></tr>
  <tr><td><b>Grooming</b></td><td>Contacto digital de un adulto con un menor mediante redes o chats para obtener favores sexuales o imágenes íntimas.</td></tr>
</table>
</details>

<details>
<summary><b>ESTUPEFACIENTES - LEY 23.737 (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Comercialización / Tenencia / Consumo</b></td><td>Venta, fraccionamiento, tenencia simple o consumo de sustancias prohibidas.</td></tr>
  <tr><td><b>Siembra</b></td><td>Cultivo de plantas y semillas aptas para producción de estupefacientes.</td></tr>
</table>
</details>

<details>
<summary><b>ENCUBRIMIENTO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Vía Pública</b></td><td>Identificación de personas circulando en rodados con pedido de secuestro activo.</td></tr>
  <tr><td><b>Taller</b></td><td>Procedimientos o denuncias en talleres o comercios en el marco de la Ley 13.081.</td></tr>
  <tr><td><b>Domicilio Particular</b></td><td>Ocultamiento de efectos procedentes de ilícitos en fincas o comercios particulares.</td></tr>
</table>
</details>

<details>
<summary><b>RESTO DE DELITOS Y LEYES ESPECIALES (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;"><th align="left">Carátula</th><th align="left">Modalidad</th><th align="left">Descripción y Criterios Operativos</th></tr>
  <tr><td><b>Abigeato</b></td><td>Abigeato / Faena</td><td>Sustracción de ganado en general o faena clandestina en el lugar del hecho.</td></tr>
  <tr><td><b>Abuso de Armas</b></td><td>Abuso de Armas</td><td>Disparos de arma de fuego contra personas o bienes sin resultar personas heridas.</td></tr>
  <tr><td><b>Tenencia / Portación de Armas</b></td><td>Tenencia / Portación</td><td>Posesión o portación ilegítima de armas de fuego listas para su uso en la vía pública.</td></tr>
  <tr><td><b>Lesiones</b></td><td>Sin Modalidad</td><td>Afecciones dolosas a la integridad física (leves, graves, gravísimas) empleando armas de fuego, blancas o impropias.</td></tr>
  <tr><td><b>Usurpación</b></td><td>Usurpación</td><td>Ocupación ilegal de inmuebles o terrenos (aclarar en observaciones si hubo moradores o si es vivienda/terreno).</td></tr>
  <tr><td><b>Privación Ilegítima de la Libertad</b></td><td>Sin Modalidad</td><td>Retención o encierro de una persona contra su voluntad.</td></tr>
  <tr><td><b>Extorsión</b></td><td>Extorsión</td><td>Coacción ilegítima para obligar a otro a entregar bienes o dinero.</td></tr>
  <tr><td><b>Falsificación o Adulteración</b></td><td>Sin Modalidad</td><td>Modificación ilegítima de documentos, numeración registral de armas o automotores.</td></tr>
  <tr><td><b>Juego Clandestino</b></td><td>Sin Modalidad</td><td>Explotación o apuestas en juegos de azar no autorizados legalmente.</td></tr>
  <tr><td><b>Ley 24.192</b></td><td>Ley 24.192</td><td>Violencia en espectáculos deportivos.</td></tr>
  <tr><td><b>Ley 25.761</b></td><td>Autopartes</td><td>Infracciones en desarmaderos y comercio ilegal de autopartes.</td></tr>
</table>
</details>

</div>

<script>
function filtrarGuia() {
  let input = document.getElementById('buscadorGuia');
  let filtro = input.value.toLowerCase();
  let detalles = document.getElementsByTagName('details');

  for (let i = 0; i < detalles.length; i++) {
    let detalle = detalles[i];
    // Omitimos el primer details que corresponde a la guía de campos para que no se oculte al buscar carátulas
    if (i === 0) continue; 

    let filas = detalle.getElementsByTagName('tr');
    let encontroEnDetalle = false;

    if (filtro === "") {
      detalle.open = (i === 1); // Deja abierto solo Robo por defecto
      detalle.style.display = "";
      for (let j = 1; j < filas.length; j++) {
        filas[j].style.display = "";
      }
      continue;
    }

    for (let j = 1; j < filas.length; j++) {
      let fila = filas[j];
      let textoFila = fila.textContent.toLowerCase();

      if (textoFila.indexOf(filtro) > -1) {
        fila.style.display = "";
        encontroEnDetalle = true;
      } else {
        fila.style.display = "none";
      }
    }

    if (encontroEnDetalle) {
      detalle.open = true;
      detalle.style.display = "";
    } else {
      detalle.style.display = "none";
    }
  }
}
</script>
