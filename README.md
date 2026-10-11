    <!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Juan José Charry Naranjo · Portafolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,800&display=swap" rel="stylesheet">
<style>
:root{--bg:#F1F3F6;--ink:#101C33;--mute:#4D5A70;--line:#C9D0DB;--accent:#1D5FA8;--row:#E5E9F0;
  box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0E1626;--ink:#E8EEF8;--mute:#9AA8BF;--line:#26324A;--accent:#7DB8F5;--row:#16213A}}
:root[data-theme="dark"]{--bg:#0E1626;--ink:#E8EEF8;--mute:#9AA8BF;--line:#26324A;--accent:#7DB8F5;--row:#16213A}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Bricolage Grotesque",system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.55}
main{max-width:860px;margin:0 auto;padding:clamp(2rem,7vw,5rem) clamp(1.25rem,5vw,2rem) 4rem}
h1{font-size:clamp(2.6rem,10vw,5.6rem);line-height:.95;letter-spacing:-.035em;font-weight:800;margin:0 0 1.5rem}
.role{font-size:clamp(1.05rem,2.6vw,1.3rem);margin:0 0 .4rem;max-width:34em}
.meta{color:var(--mute);margin:0 0 2.5rem}
.bar{display:flex;height:14px;border-radius:7px;overflow:hidden;gap:3px;margin:0 0 .6rem}
.bar span{flex:1}
.cap{color:var(--mute);font-size:.95rem;margin:0 0 2.5rem}
h2{font-size:1.5rem;letter-spacing:-.02em;margin:0 0 1rem}
.repos{border-top:1px solid var(--line)}
.repo{display:grid;grid-template-columns:1fr auto;gap:.2rem 1.5rem;padding:1.15rem .75rem;border-bottom:1px solid var(--line);color:inherit;text-decoration:none}
.repo:hover,.repo:focus-visible{background:var(--row)}
.repo:focus-visible,.btn:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.name{font-size:1.35rem;font-weight:600;letter-spacing:-.015em;overflow-wrap:anywhere}
.desc{grid-column:1;color:var(--mute);margin:0}
.lang{grid-column:2;grid-row:1;display:flex;align-items:center;gap:.5rem;align-self:center;font-size:.95rem;white-space:nowrap}
.dot{width:.8rem;height:.8rem;border-radius:50%;display:inline-block}
.stars{grid-column:2;grid-row:2;color:var(--mute);font-size:.9rem;justify-self:end}
.btn{display:inline-block;margin-top:2rem;padding:.8rem 1.4rem;border-radius:999px;background:var(--accent);color:var(--bg);font-weight:600;text-decoration:none}
.btn:hover{filter:brightness(1.1)}
footer{margin-top:3rem;color:var(--mute);font-size:.9rem}
@media (max-width:520px){.repo{grid-template-columns:1fr}.lang,.stars{grid-column:1;grid-row:auto;justify-self:start}}
</style>
</head>
<body>
<main>
  <h1>Juan José Charry Naranjo</h1>
  <p class="role">Analista de sistemas senior. Desarrollo de software y marketing digital.</p>
  <p class="meta">GCA Technologies S.A. · Cali, Colombia</p>

  <div class="bar" role="img" aria-label="Lenguajes de los repositorios: Assembly, HTML, Papyrus, Python, C++, Python">
    <span style="background:#6E4C13" title="Assembly"></span>
    <span style="background:#E34C26" title="HTML"></span>
    <span style="background:#6600cc" title="Papyrus"></span>
    <span style="background:#3572A5" title="Python"></span>
    <span style="background:#f34b7d" title="C++"></span>
    <span style="background:#3572A5" title="Python"></span>
  </div>
  <p class="cap">Cinco lenguajes en los repositorios destacados: de Assembly a Python.</p>

  <h2>Repositorio de Proyectos</h2>
  <div class="repos">
    <a class="repo" href="https://charryjj.github.io/Proyectos/">
      <span class="name">Proyectos</span>
      <span class="lang"><i class="dot" style="background:#6E4C13"></i>Ver ahora</span>
      <p class="desc">Repositorio principal con proyectos académicos, desarrollos personales y prácticos de ingeniería de software y programación.</p>
    </a>
  </div>

  <a class="btn" href="https://github.com/CharryJJ?tab=repositories">Ver los 8 repositorios en GitHub</a>
  <footer>Perfil: github.com/CharryJJ</footer>
</main>
</body>
</html>
