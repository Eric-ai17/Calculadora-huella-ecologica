<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Calculadora de huella ecológica</title>
<style>
  :root {
    --mar: #0f4c5c;
    --manglar: #2f6b3a;
    --arena: #f3ead8;
    --papel: #fffdf7;
    --tinta: #1d2b2a;
    --atardecer: #e36414;
    --suave: #5c6b68;
    --borde: #d8cdb5;
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    font-family: "Avenir Next", "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    background: var(--arena);
    color: var(--tinta);
    line-height: 1.55;
  }
  header {
    background: var(--mar);
    color: var(--papel);
    padding: 3rem 1.25rem 4.5rem;
    position: relative;
    overflow: hidden;
  }
  header::after {
    content: "";
    position: absolute;
    left: -5%; right: -5%; bottom: -40px;
    height: 80px;
    background: var(--arena);
    border-radius: 50% 50% 0 0 / 100% 100% 0 0;
  }
  .contenido { max-width: 760px; margin: 0 auto; }
  h1 {
    font-family: Georgia, "Times New Roman", serif;
    font-size: clamp(2rem, 6vw, 3.2rem);
    line-height: 1.1;
    margin: 0 0 1rem;
    font-weight: 700;
  }
  header p { font-size: 1.15rem; max-width: 34em; margin: 0; opacity: .92; }
  .planetas { display: flex; gap: .5rem; margin-top: 1.5rem; flex-wrap: wrap; }
  .planeta {
    width: 34px; height: 34px; border-radius: 50%;
    background: radial-gradient(circle at 35% 35%, #7fc8a9, #2f6b3a 60%, #0f4c5c);
    box-shadow: inset -5px -5px 0 rgba(0,0,0,.18);
  }
  main { padding: 0 1.25rem 3rem; }
  form { background: var(--papel); border: 1px solid var(--borde); border-radius: 14px; padding: 1.5rem; }
  fieldset { border: none; padding: 0; margin: 0 0 1.75rem; }
  legend {
    font-family: Georgia, "Times New Roman", serif;
    font-size: 1.35rem;
    color: var(--manglar);
    margin-bottom: .75rem;
    padding: 0;
  }
  .campos { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1rem; }
  label { display: block; font-size: .95rem; margin-bottom: .3rem; }
  select, input {
    width: 100%;
    padding: .65rem .75rem;
    font: inherit;
    border: 1px solid var(--borde);
    border-radius: 8px;
    background: #fff;
    color: var(--tinta);
  }
  select:focus, input:focus, button:focus-visible {
    outline: 3px solid var(--atardecer);
    outline-offset: 2px;
  }
  button {
    width: 100%;
    padding: 1rem;
    font: inherit;
    font-size: 1.1rem;
    font-weight: 600;
    color: #fff;
    background: var(--manglar);
    border: none;
    border-radius: 10px;
    cursor: pointer;
  }
  button:hover:not(:disabled) { background: #245530; }
  button:disabled { background: var(--suave); cursor: wait; }
  #estado { margin: 1rem 0 0; text-align: center; color: var(--suave); min-height: 1.5em; }
  #resultado {
    display: none;
    margin-top: 1.5rem;
    background: var(--papel);
    border-left: 6px solid var(--atardecer);
    border-radius: 10px;
    padding: 1.5rem;
    white-space: pre-line;
    font-size: 1rem;
  }
  #resultado.error { border-left-color: #b00020; color: #b00020; }
  footer { text-align: center; color: var(--suave); font-size: .85rem; padding: 0 1rem 2rem; }
  @media (prefers-reduced-motion: no-preference) {
    #resultado.visible { animation: entra .4s ease-out; }
    @keyframes entra { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: none; } }
  }
</style>
</head>
<body>
<header>
  <div class="contenido">
    <h1>Calculadora de huella ecológica</h1>
    <p>Si todos vivieran como tú, ¿cuántos planetas Tierra harían falta? Contesta sobre tu alimentación, transporte, energía, consumo y residuos, y una IA estimará tu huella.</p>
    <div class="planetas" id="planetas" aria-hidden="true"><div class="planeta"></div></div>
  </div>
</header>

<main>
  <div class="contenido">
    <form id="formulario">
      <fieldset>
        <legend>Alimentación</legend>
        <div class="campos">
          <div>
            <label for="carne">¿Cada cuánto comes carne de res o cerdo?</label>
            <select id="carne" name="carne" required>
              <option>Nunca</option>
              <option>1-2 veces por semana</option>
              <option>3-5 veces por semana</option>
              <option>Diario</option>
            </select>
          </div>
          <div>
            <label for="local">¿Qué parte de tu comida es local o de temporada?</label>
            <select id="local" name="local" required>
              <option>Casi nada</option>
              <option>La mitad</option>
              <option>Casi toda</option>
            </select>
          </div>
        </div>
      </fieldset>

      <fieldset>
        <legend>Transporte</legend>
        <div class="campos">
          <div>
            <label for="transporte">Medio principal</label>
            <select id="transporte" name="transporte" required>
              <option>Caminar o bicicleta</option>
              <option>Camion urbano</option>
              <option>Moto</option>
              <option>Auto propio</option>
            </select>
          </div>
          <div>
            <label for="km">Kilómetros que recorres al día</label>
            <input id="km" name="km" type="number" min="0" step="0.1" value="0" required>
          </div>
          <div>
            <label for="vuelos">Vuelos en avión al año</label>
            <input id="vuelos" name="vuelos" type="number" min="0" step="1" value="0" required>
          </div>
        </div>
      </fieldset>

      <fieldset>
        <legend>Energía</legend>
        <div class="campos">
          <div>
            <label for="aire">Horas al día de aire acondicionado en casa</label>
            <input id="aire" name="aire" type="number" min="0" max="24" step="0.5" value="0" required>
          </div>
          <div>
            <label for="personas">Personas que viven en tu casa</label>
            <input id="personas" name="personas" type="number" min="1" step="1" value="1" required>
          </div>
        </div>
      </fieldset>

      <fieldset>
        <legend>Consumo</legend>
        <div class="campos">
          <div>
            <label for="ropa">Prendas nuevas que compras al mes</label>
            <input id="ropa" name="ropa" type="number" min="0" step="1" value="0" required>
          </div>
          <div>
            <label for="celular">¿Cada cuántos años cambias de celular?</label>
            <input id="celular" name="celular" type="number" min="0" step="0.5" value="2" required>
          </div>
        </div>
      </fieldset>

      <fieldset>
        <legend>Residuos</legend>
        <div class="campos">
          <div>
            <label for="separa">¿Separas la basura?</label>
            <select id="separa" name="separa" required>
              <option>Si</option>
              <option>A veces</option>
              <option>No</option>
            </select>
          </div>
        </div>
      </fieldset>

      <button type="submit" id="boton">Calcular mi huella</button>
      <p id="estado" role="status"></p>
    </form>

    <div id="resultado" aria-live="polite"></div>
  </div>
</main>

<footer>Estimación aproximada hecha con IA. Para un cálculo oficial usa footprintcalculator.org</footer>

<script>
  // Pega aquí la URL de tu webhook de Make (Webhooks > Custom webhook > Copy address)
  const WEBHOOK_URL = "https://hook.us2.make.com/wmyr6wj3fbwr582av7981cdaocqlykcp";

  const CAMPOS = ["carne", "local", "transporte", "km", "vuelos", "aire", "personas", "ropa", "celular", "separa"];

  const formulario = document.getElementById("formulario");
  const boton = document.getElementById("boton");
  const estado = document.getElementById("estado");
  const resultado = document.getElementById("resultado");
  const planetas = document.getElementById("planetas");

  function dibujarPlanetas(texto) {
    // Busca el número de planetas en el texto para mostrarlo visualmente (opcional)
    const coincidencia = texto.match(/Planetas necesarios[^0-9]*([0-9]+(?:[.,][0-9]+)?)/i);
    if (!coincidencia) return;
    const valor = parseFloat(coincidencia[1].replace(",", "."));
    if (isNaN(valor) || valor <= 0) return;
    const enteros = Math.min(Math.ceil(valor), 10);
    planetas.innerHTML = "";
    for (let i = 0; i < enteros; i++) {
      const p = document.createElement("div");
      p.className = "planeta";
      planetas.appendChild(p);
    }
  }

  formulario.addEventListener("submit", async function (evento) {
    evento.preventDefault();

    const datos = new URLSearchParams();
    CAMPOS.forEach(function (campo) {
      datos.append(campo, document.getElementById(campo).value);
    });

    boton.disabled = true;
    estado.textContent = "Calculando tu huella...";
    resultado.style.display = "none";
    resultado.className = "";

    try {
      const respuesta = await fetch(WEBHOOK_URL, { method: "POST", body: datos });
      if (!respuesta.ok) throw new Error("Respuesta " + respuesta.status);
      const texto = await respuesta.text();

      resultado.textContent = texto;
      resultado.className = "visible";
      resultado.style.display = "block";
      dibujarPlanetas(texto);
      resultado.scrollIntoView({ behavior: "smooth", block: "start" });
    } catch (error) {
      resultado.textContent = "No se pudo calcular, intenta de nuevo.";
      resultado.className = "error visible";
      resultado.style.display = "block";
    } finally {
      boton.disabled = false;
      estado.textContent = "";
    }
  });
</script>
</body>
</html>
