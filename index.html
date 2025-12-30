<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Malla Medicina UCSUR 2025</title>

<style>
:root{
  --rosa-fondo:#fff1f2;
  --rosa-card:#fce7f3;
  --rosa-ok:#fbcfe8;
  --morado:#9333ea;
  --morado-borde:#e9d5ff;
  --gris:#e5e7eb;
}
body{
  font-family: Arial, sans-serif;
  background: var(--rosa-fondo);
  padding: 20px;
}
h1{
  text-align:center;
  color: var(--morado);
}
.grid{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
  gap:15px;
}
.ciclo{
  background: var(--rosa-card);
  border: 2px solid var(--morado-borde);
  border-radius: 14px;
  padding:10px;
}
.ciclo h2{
  text-align:center;
  color: var(--morado);
}
.curso{
  background:white;
  border:1px solid #ddd;
  border-radius:8px;
  padding:6px 8px;
  margin:4px 0;
  cursor:pointer;
  display:flex;
  justify-content:space-between;
  align-items:center;
}
.curso.locked{
  background: var(--gris);
  color:#9ca3af;
  cursor:not-allowed;
}
.curso.completed{
  background: var(--rosa-ok);
  text-decoration: line-through;
}
.creditos{
  font-size: 12px;
  color: var(--morado);
}
#progreso{
  margin-top:20px;
  text-align:center;
  font-weight:bold;
  color: var(--morado);
}
</style>
</head>

<body>

<h1>Malla Curricular Medicina Humana – UCSUR 2025</h1>
<div class="grid" id="contenedor"></div>
<div id="progreso"></div>

<script>
const cursos = {

"Ciclo 1":{
 "Química":{creditos:5, prereq:[]},
 "Matemática":{creditos:3, prereq:[]},
 "Lengua y Oratoria":{creditos:3, prereq:[]},
 "Introducción a la Medicina":{creditos:2, prereq:[]},
 "Desempeño Universitario":{creditos:2, prereq:[]},
 "Biología Celular y Molecular":{creditos:6, prereq:[]}
},

"Ciclo 2":{
 "Redacción General":{creditos:3, prereq:["Lengua y Oratoria"]},
 "Realidad Nacional":{creditos:2, prereq:[]},
 "Morfofisiología I":{creditos:6, prereq:["Biología Celular y Molecular"]},
 "Introducción a la Investigación":{creditos:3, prereq:["Introducción a la Medicina","Lengua y Oratoria"]},
 "Bioquímica":{creditos:5, prereq:["Química"]},
 "Anatomía General":{creditos:3, prereq:["Biología Celular y Molecular"]}
},

"Ciclo 3":{
 "Morfofisiología II":{creditos:7, prereq:["Morfofisiología I","Anatomía General"]},
 "Inmunología":{creditos:3, prereq:["Morfofisiología I"]},
 "Genética Médica":{creditos:3, prereq:["Biología Celular y Molecular"]},
 "Filosofía":{creditos:3, prereq:[]},
 "Estadística General":{creditos:4, prereq:["Matemática"]},
 "Educación Ambiental":{creditos:2, prereq:["Desempeño Universitario"]}
},

"Ciclo 4":{
 "Morfofisiología III":{creditos:7, prereq:["Morfofisiología II"]},
 "Infectología Básica":{creditos:5, prereq:["Bioquímica","Morfofisiología I"]},
 "Fisiopatología I":{creditos:4, prereq:["Morfofisiología II"]},
 "Desarrollo y Crecimiento":{creditos:3, prereq:["Biología Celular y Molecular"]},
 "Bioética":{creditos:2, prereq:["Introducción a la Medicina","Redacción General"]}
},

"Ciclo 5":{
 "Salud Mental":{creditos:4, prereq:["Filosofía"]},
 "Morfofisiología IV":{creditos:6, prereq:["Morfofisiología III"]},
 "Fundamentos de Medicina Interna":{creditos:2, prereq:["Filosofía","Realidad Nacional"]},
 "Fisiopatología II":{creditos:5, prereq:["Morfofisiología II"]},
 "Bioestadística":{creditos:2, prereq:["Estadística General"]}
},

"Ciclo 6":{
 "Semiología Basada en la Simulación":{creditos:2, prereq:["Fisiopatología I","Fisiopatología II","Inmunología","Morfofisiología II","Morfofisiología III","Morfofisiología IV"]},
 "Semiología":{creditos:5, prereq:["Fisiopatología I","Fisiopatología II","Inmunología","Morfofisiología II","Morfofisiología III","Morfofisiología IV"]},
 "Farmacología":{creditos:6, prereq:["Infectología Básica"]},
 "Apoyo al Diagnóstico":{creditos:3, prereq:["Morfofisiología IV"]},
 "Anatomía Patológica":{creditos:4, prereq:["Fisiopatología II"]}
},

"Ciclo 7":{
 "Seguridad del Paciente y Calidad":{creditos:2, prereq:["Bioética"]},
 "Nutrición y Prácticas Saludables":{creditos:4, prereq:["Farmacología"]},
 "Metodología de la Investigación":{creditos:2, prereq:["Bioestadística"]},
 "Medicina Interna I":{creditos:10, prereq:["Anatomía Patológica","Semiología","Semiología Basada en la Simulación"]},
 "Epidemiología":{creditos:4, prereq:["Bioestadística"]}
},

"Ciclo 8":{
 "Salud Pública":{creditos:4, prereq:["Epidemiología"]},
 "Medicina Interna II":{creditos:10, prereq:["Medicina Interna I"]},
 "Medicina Basada en la Evidencia":{creditos:2, prereq:["Epidemiología","Metodología de la Investigación"]},
 "Atención Primaria en Salud":{creditos:4, prereq:["Epidemiología"]}
},

"Ciclo 9":{
 "Tesis I":{creditos:2, prereq:["Medicina Basada en la Evidencia"]},
 "Terapéutica":{creditos:2, prereq:["Medicina Interna II"]},
 "Simulación Clínica Integrada":{creditos:3, prereq:["Medicina Interna II"]},
 "Medicina Legal":{creditos:2, prereq:["Bioética","Semiología","Semiología Basada en la Simulación"]},
 "Medicina Interna III":{creditos:10, prereq:["Medicina Interna II"]}
},

"Ciclo 10":{
 "Simulación Quirúrgica":{creditos:2, prereq:["Medicina Interna III","Simulación Clínica Integrada"]},
 "Ecografía":{creditos:2, prereq:["Apoyo al Diagnóstico","Semiología"]},
 "Cuidados Paliativos y Rehabilitación Física":{creditos:2, prereq:["Bioética","Terapéutica"]},
 "Cirugía":{creditos:11, prereq:["Medicina Interna III","Simulación Clínica Integrada"]},
 "Análisis de Casos I":{creditos:2, prereq:["Medicina Interna III","Simulación Clínica Integrada","Terapéutica"]}
},

"Ciclo 11":{
 "Tesis II":{creditos:2, prereq:["Tesis I"]},
 "Simulación Pediátrica":{creditos:2, prereq:["Medicina Interna III","Simulación Clínica Integrada"]},
 "Simulación Gineco-Obstétrica":{creditos:2, prereq:["Cirugía","Simulación Quirúrgica"]},
 "Pediatría":{creditos:10, prereq:["Medicina Interna III","Simulación Clínica Integrada"]},
 "Ginecología y Obstetricia":{creditos:6, prereq:["Cirugía","Simulación Quirúrgica"]}
},

"Ciclo 12":{
 "Preinternado":{creditos:16, prereq:["Ginecología y Obstetricia"]},
 "Informática Biomédica":{creditos:2, prereq:["Atención Primaria en Salud"]},
 "Gerencia en Salud":{creditos:2, prereq:["Atención Primaria en Salud"]},
 "Análisis de Casos II":{creditos:2, prereq:["Análisis de Casos I"]}
},

"Ciclo 13":{
 "Trabajo de Investigación":{creditos:1, prereq:["Preinternado"]},
 "Internado en Pediatría":{creditos:10, prereq:["Preinternado"]},
 "Internado en Medicina":{creditos:10, prereq:["Preinternado"]}
},

"Ciclo 14":{
 "Internado en Cirugía":{creditos:10, prereq:["Preinternado"]},
 "Internado en Ginecología y Obstetricia":{creditos:10, prereq:["Preinternado"]}
}

};

const estado = JSON.parse(localStorage.getItem("malla2025") || "{}");

function guardar(){
  localStorage.setItem("malla2025", JSON.stringify(estado));
}

function render(){
  const cont = document.getElementById("contenedor");
  cont.innerHTML = "";
  let total = 0;
  let completos = 0;

  for(const ciclo in cursos){
    const box = document.createElement("div");
    box.className = "ciclo";
    box.innerHTML = `<h2>${ciclo}</h2>`;

    for(const curso in cursos[ciclo]){
      total++;
      const {creditos, prereq} = cursos[ciclo][curso];
      const habilitado = prereq.every(p => estado[p]);

      const div = document.createElement("div");
      div.className = "curso";
      div.innerHTML = `<span>${curso}</span><span class="creditos">${creditos} cr</span>`;

      if(!habilitado) div.classList.add("locked");
      if(estado[curso]){
        div.classList.add("completed");
        completos++;
      }

      if(habilitado){
        div.onclick = () => {
          estado[curso] = !estado[curso];
          guardar();
          render();
        };
      }

      box.appendChild(div);
    }
    cont.appendChild(box);
  }

  document.getElementById("progreso").textContent =
    `Progreso total: ${Math.round((completos/total)*100)}%`;
}

render();
</script>

</body>
</html>
