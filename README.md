
<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Rodrigo Matias Villalobos Diaz — Ingeniero en Telecomunicaciones</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
:root{
--bg:#0f1724; --card:#0b1220; --muted:#9aa4b2; --accent:#06b6d4; --glass: rgba(255,255,255,0.04);
--radius:14px; --maxw:1000px; --pad:24px;
font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
}
*{box-sizing:border-box}
html,body{height:100%}
body{margin:0;background:linear-gradient(180deg,#071028 0%, #07153a 100%);color:#e6eef6;display:flex;align-items:flex-start;justify-content:center;padding:40px 16px}
.wrap{width:100%;max-width:var(--maxw)}
header{display:flex;gap:20px;align-items:center;margin-bottom:22px}
.avatar{width:96px;height:96px;border-radius:18px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:#051923}
h1{margin:0;font-size:22px}
h2{margin:0;font-size:16px;color:var(--muted)}
.grid{display:grid;grid-template-columns:1fr 340px;gap:20px}
main{background:var(--glass);padding:var(--pad);border-radius:var(--radius);backdrop-filter:blur(6px)}
aside{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:var(--pad);border-radius:var(--radius);height:100%}
.section{margin-bottom:18px}
.card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:14px;border-radius:12px}
.skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.skill{padding:8px 10px;border-radius:10px;background:rgba(255,255,255,0.03);font-size:13px}
.projects{display:grid;gap:12px}
.project{display:flex;flex-direction:column;gap:8px;padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.015));}
a.btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:#042027;text-decoration:none;font-weight:600}
footer{margin-top:18px;color:var(--muted);font-size:13px}
.meta{color:var(--muted);font-size:13px}
pre{white-space:pre-wrap;font-size:13px}
/* Responsive */
@media (max-width:880px){.grid{grid-template-columns:1fr}aside{order:2}.wrap{padding-bottom:60px}}
</style>
</head>
<body>
<div class="wrap">
<header>
<div class="avatar">RM</div>
<div>
<h1><!-- EDITAR: NOMBRE -->Rodrigo Matias Villalobos Diaz</h1>
<h2><!-- EDITAR: TITULO -->Ingeniero en Telecomunicaciones, Conectividad y Redes • Programador</h2>
<div class="meta">La Serena, Chile • Trabajando en: Imatec (área informática)</div>
</div>
</header>


<div class="grid">
<main>
<section class="section card">
<h3>Acerca de mí</h3>
<p class="meta"><!-- EDITAR: RESUMEN --></p>
<p>Soy un profesional apasionado por el desarrollo de software y las redes. Me especializo en crear soluciones que conectan infraestructura y código para resolver problemas reales en entornos de salud y telecomunicaciones.</p>
</section>


<section class="section">
<h3>Proyectos destacados</h3>
<div class="projects">
<!-- EDITAR: DUPLICA ESTE BLOQUE POR CADA PROYECTO -->
<div class="project">
<strong>Nombre del proyecto</strong>
<div class="meta">Breve descripción (qué hace, tecnologías). • <a href="#" target="_blank">Repo</a></div>
<div>
<small class="meta">Stack: Python · JavaScript · Docker · Cisco (ejemplo)</small>
</div>
</div>
<!-- /FIN PROYECTO -->
</div>
