<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Calificaciones · Trimestre</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg:         #0f1117;
    --surface:    #181c27;
    --surface2:   #1f2535;
    --border:     #262d40;
    --text:       #e2e8f0;
    --muted:      #64748b;
    --accent:     #6366f1;
    --accent-dim: rgba(99,102,241,.15);
    --green:      #22c55e;
    --yellow:     #eab308;
    --red:        #ef4444;
    --red-dim:    rgba(239,68,68,.14);
  }

  html { font-size: 15px; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', system-ui, sans-serif;
    min-height: 100vh;
    padding: 2rem 1.5rem 4rem;
    line-height: 1.5;
  }

  /* ── Header ── */
  .header {
    max-width: 1100px;
    margin: 0 auto 2rem;
    display: flex;
    align-items: flex-end;
    justify-content: space-between;
    gap: 1rem;
    flex-wrap: wrap;
  }
  .header-title { line-height: 1.2; }
  .header-eyebrow {
    font-size: .7rem;
    letter-spacing: .14em;
    text-transform: uppercase;
    color: var(--accent);
    font-weight: 600;
    margin-bottom: .35rem;
  }
  .header-title h1 {
    font-size: 1.75rem;
    font-weight: 700;
    color: var(--text);
  }
  .header-title h1 span {
    color: var(--accent);
  }
  .header-meta {
    font-size: .8rem;
    color: var(--muted);
    margin-top: .25rem;
  }
  .badge {
    background: var(--accent-dim);
    color: var(--accent);
    border: 1px solid rgba(99,102,241,.3);
    border-radius: 999px;
    padding: .2rem .75rem;
    font-size: .7rem;
    font-weight: 600;
    letter-spacing: .06em;
    text-transform: uppercase;
    align-self: flex-start;
  }

  /* ── Stat Cards ── */
  .stats-grid {
    max-width: 1100px;
    margin: 0 auto 1.75rem;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
  }
  .stat-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1.25rem 1.5rem;
    position: relative;
    overflow: hidden;
    transition: border-color .2s;
  }
  .stat-card::before {
    content: '';
    position: absolute;
    inset: 0;
    border-radius: 10px;
    background: linear-gradient(135deg, rgba(99,102,241,.06), transparent 60%);
    pointer-events: none;
  }
  .stat-card:hover { border-color: rgba(99,102,241,.4); }
  .stat-label {
    font-size: .7rem;
    font-weight: 600;
    letter-spacing: .1em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: .6rem;
  }
  .stat-value {
    font-family: 'JetBrains Mono', monospace;
    font-size: 2.2rem;
    font-weight: 500;
    line-height: 1;
    color: var(--text);
  }
  .stat-value.green { color: var(--green); }
  .stat-value.yellow { color: var(--yellow); }
  .stat-value.red { color: var(--red); }
  .stat-sub {
    margin-top: .45rem;
    font-size: .78rem;
    color: var(--muted);
  }
  .stat-icon {
    position: absolute;
    right: 1.25rem;
    top: 1.1rem;
    font-size: 1.4rem;
    opacity: .18;
  }

  /* ── Search ── */
  .toolbar {
    max-width: 1100px;
    margin: 0 auto 1.1rem;
    display: flex;
    align-items: center;
    gap: .75rem;
    flex-wrap: wrap;
  }
  .search-wrap {
    position: relative;
    flex: 1;
    min-width: 200px;
    max-width: 360px;
  }
  .search-icon {
    position: absolute;
    left: .85rem;
    top: 50%;
    transform: translateY(-50%);
    color: var(--muted);
    pointer-events: none;
    font-size: .95rem;
  }
  .search-input {
    width: 100%;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    color: var(--text);
    font-family: inherit;
    font-size: .88rem;
    padding: .6rem .9rem .6rem 2.3rem;
    outline: none;
    transition: border-color .2s, box-shadow .2s;
  }
  .search-input::placeholder { color: var(--muted); }
  .search-input:focus {
    border-color: var(--accent);
    box-shadow: 0 0 0 3px rgba(99,102,241,.15);
  }
  .result-count {
    font-size: .78rem;
    color: var(--muted);
    margin-left: auto;
  }

  /* ── Table ── */
  .table-wrap {
    max-width: 1100px;
    margin: 0 auto;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    overflow: hidden;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: .84rem;
  }
  thead tr {
    background: var(--surface2);
    border-bottom: 1px solid var(--border);
  }
  th {
    padding: .75rem 1rem;
    text-align: left;
    font-size: .7rem;
    font-weight: 600;
    letter-spacing: .09em;
    text-transform: uppercase;
    color: var(--muted);
    white-space: nowrap;
    cursor: pointer;
    user-select: none;
    transition: color .15s;
  }
  th:hover { color: var(--text); }
  th.sorted { color: var(--accent); }
  .sort-arrow {
    display: inline-block;
    margin-left: .3rem;
    opacity: .4;
    font-style: normal;
    font-size: .75rem;
    transition: opacity .15s;
  }
  th.sorted .sort-arrow { opacity: 1; color: var(--accent); }

  tbody tr {
    border-bottom: 1px solid var(--border);
    transition: background .12s;
  }
  tbody tr:last-child { border-bottom: none; }
  tbody tr:hover { background: rgba(99,102,241,.05); }

  td {
    padding: .7rem 1rem;
    color: var(--text);
    vertical-align: middle;
  }
  td.mono {
    font-family: 'JetBrains Mono', monospace;
    font-size: .82rem;
    text-align: center;
  }
  td.dash { color: var(--muted); text-align: center; }

  .materia-cell { font-weight: 500; font-size: .83rem; }
  .materia-cell span {
    display: block;
    font-size: .7rem;
    color: var(--muted);
    font-weight: 400;
    margin-top: .1rem;
  }

  /* Score badges */
  .score {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 2rem;
    height: 2rem;
    border-radius: 6px;
    font-family: 'JetBrains Mono', monospace;
    font-size: .82rem;
    font-weight: 500;
  }
  .score-low  { background: var(--red-dim); color: var(--red); }
  .score-mid  { background: rgba(234,179,8,.12); color: var(--yellow); }
  .score-high { background: rgba(34,197,94,.1); color: var(--green); }
  .score-max  { background: rgba(99,102,241,.15); color: var(--accent); }

  /* Alert row highlight */
  .alert-cell { background: var(--red-dim) !important; }

  /* Asistencia bar */
  .asist-wrap { display: flex; align-items: center; gap: .5rem; }
  .asist-bar-bg {
    flex: 1;
    height: 4px;
    background: var(--border);
    border-radius: 99px;
    overflow: hidden;
    min-width: 50px;
  }
  .asist-bar-fill {
    height: 100%;
    border-radius: 99px;
    transition: width .4s ease;
  }
  .asist-pct { font-size: .7rem; color: var(--muted); white-space: nowrap; }

  /* Empty state */
  .empty-row td {
    text-align: center;
    padding: 3rem;
    color: var(--muted);
    font-size: .9rem;
  }

  /* Scrollbar */
  ::-webkit-scrollbar { width: 6px; height: 6px; }
  ::-webkit-scrollbar-track { background: transparent; }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 99px; }

  @media (max-width: 768px) {
    body { padding: 1.25rem .75rem 3rem; }
    .header-title h1 { font-size: 1.35rem; }
    .stat-value { font-size: 1.75rem; }
    th, td { padding: .6rem .65rem; font-size: .78rem; }
    .score { width: 1.7rem; height: 1.7rem; font-size: .75rem; }
  }
</style>
</head>
<body>

<header class="header">
  <div class="header-title">
    <div class="header-eyebrow">Boletín académico</div>
    <h1>Mis <span>Calificaciones</span></h1>
    <div class="header-meta">Primer trimestre · 12 materias</div>
  </div>
  <div class="badge">2025</div>
</header>

<div class="stats-grid" id="statsGrid"></div>

<div class="toolbar">
  <div class="search-wrap">
    <span class="search-icon">🔍</span>
    <input class="search-input" type="text" id="searchInput" placeholder="Buscar materia…" autocomplete="off">
  </div>
  <div class="result-count" id="resultCount"></div>
</div>

<div class="table-wrap">
  <table>
    <thead>
      <tr id="tableHead"></tr>
    </thead>
    <tbody id="tableBody"></tbody>
  </table>
</div>

<script>
const DATA = [
  { materia: "LENGUA Y LITERATURA III", inasistencias: 2, clases: 35, diagnostico: 7, calificacion: 7, ev_integradora: 3, nota_trimestral: 6, recuperacion: 7 },
  { materia: "LENGUA EXTRANJERA III", inasistencias: 3, clases: 34, diagnostico: 8, calificacion: 6, ev_integradora: 6, nota_trimestral: 7, recuperacion: "" },
  { materia: "MATEMATICA III", inasistencias: 0, clases: 44, diagnostico: 6, calificacion: 7, ev_integradora: 7, nota_trimestral: 7, recuperacion: "" },
  { materia: "HISTORIA III", inasistencias: 0, clases: 18, diagnostico: 8, calificacion: 10, ev_integradora: 10, nota_trimestral: 9, recuperacion: "" },
  { materia: "GEOGRAFIA III", inasistencias: 0, clases: 32, diagnostico: 10, calificacion: 9, ev_integradora: 6, nota_trimestral: 8, recuperacion: "" },
  { materia: "BIOLOGIA III", inasistencias: 0, clases: 10, diagnostico: 9, calificacion: 9, ev_integradora: 9, nota_trimestral: 9, recuperacion: "" },
  { materia: "CONSTRUCCION DE CIUDADANIA", inasistencias: 0, clases: 23, diagnostico: 8, calificacion: 9, ev_integradora: 10, nota_trimestral: 9, recuperacion: "" },
  { materia: "QUIMICA II", inasistencias: 2, clases: 35, diagnostico: 10, calificacion: 10, ev_integradora: 8, nota_trimestral: 9, recuperacion: "" },
  { materia: "ED. ARTISTICA III", inasistencias: 1, clases: 20, diagnostico: 10, calificacion: 10, ev_integradora: 10, nota_trimestral: 10, recuperacion: "" },
  { materia: "ED. TECNOLOGICA II", inasistencias: 0, clases: 24, diagnostico: 8, calificacion: 8, ev_integradora: 8, nota_trimestral: 8, recuperacion: "" },
  { materia: "ED. FISICA III", inasistencias: 0, clases: 6, diagnostico: 7, calificacion: 10, ev_integradora: 6, nota_trimestral: 8, recuperacion: "" },
  { materia: "FORMACION ETICA III / RELIGION", inasistencias: 0, clases: 9, diagnostico: 7, calificacion: 6, ev_integradora: 6, nota_trimestral: 6, recuperacion: "" }
];

const COLS = [
  { key: 'materia',        label: 'Materia',         sortable: true,  type: 'materia'  },
  { key: 'inasistencias',  label: 'Inasist.',        sortable: true,  type: 'asist'    },
  { key: 'diagnostico',    label: 'Diagnóstico',     sortable: true,  type: 'score'    },
  { key: 'calificacion',   label: 'Calificación',    sortable: true,  type: 'score'    },
  { key: 'ev_integradora', label: 'Ev. Integradora', sortable: true,  type: 'score-alert' },
  { key: 'nota_trimestral',label: 'Nota Trimestral', sortable: true,  type: 'score-alert' },
  { key: 'recuperacion',   label: 'Recuperación',    sortable: false, type: 'score'    },
];

let sortCol = null, sortDir = 1, filterText = '';

// ── Stats ──────────────────────────────────────────────
function buildStats() {
  const notas = DATA.map(d => d.nota_trimestral).filter(n => n !== "");
  const avg = (notas.reduce((a,b) => a+b, 0) / notas.length).toFixed(2);
  const totalInasist = DATA.reduce((a,d) => a + d.inasistencias, 0);
  const best = DATA.reduce((a,b) => b.nota_trimestral > a.nota_trimestral ? b : a);
  const avgNum = parseFloat(avg);
  const avgClass = avgNum >= 8 ? 'green' : avgNum >= 6 ? 'yellow' : 'red';
  const inasistClass = totalInasist === 0 ? 'green' : totalInasist <= 3 ? 'yellow' : 'red';

  const cards = [
    { label: 'Promedio trimestral', value: avg, cls: avgClass, sub: 'sobre todas las materias', icon: '📊' },
    { label: 'Total inasistencias', value: totalInasist, cls: inasistClass, sub: `en ${DATA.length} materias`, icon: '📅' },
    { label: 'Mejor rendimiento', value: best.nota_trimestral, cls: 'green', sub: best.materia.split(' ').slice(0,2).join(' ').toLowerCase().replace(/\b\w/g,c=>c.toUpperCase()), icon: '🏆' },
  ];

  document.getElementById('statsGrid').innerHTML = cards.map(c => `
    <div class="stat-card">
      <div class="stat-icon">${c.icon}</div>
      <div class="stat-label">${c.label}</div>
      <div class="stat-value ${c.cls}">${c.value}</div>
      <div class="stat-sub">${c.sub}</div>
    </div>`).join('');
}

// ── Score badge ──────────────────────────────────────
function scoreBadge(val) {
  if (val === "" || val == null) return `<span style="color:var(--muted)">—</span>`;
  const n = Number(val);
  const cls = n === 10 ? 'score-max' : n >= 8 ? 'score-high' : n >= 6 ? 'score-mid' : 'score-low';
  return `<span class="score ${cls}">${n}</span>`;
}

// ── Table head ────────────────────────────────────────
function buildHead() {
  document.getElementById('tableHead').innerHTML = COLS.map((c,i) => {
    const sorted = sortCol === i;
    const arrow = c.sortable ? `<i class="sort-arrow">${sorted ? (sortDir===1?'↓':'↑') : '↕'}</i>` : '';
    return `<th class="${sorted?'sorted':''}" ${c.sortable?`onclick="sort(${i})"`:''}>${c.label}${arrow}</th>`;
  }).join('');
}

// ── Asistencia mini bar ───────────────────────────────
function asistCell(row) {
  const pct = Math.round(((row.clases - row.inasistencias) / row.clases) * 100);
  const color = pct === 100 ? 'var(--green)' : pct >= 90 ? 'var(--yellow)' : 'var(--red)';
  return `<div class="asist-wrap">
    <span class="mono" style="min-width:1.2rem;text-align:right">${row.inasistencias}</span>
    <div class="asist-bar-bg"><div class="asist-bar-fill" style="width:${pct}%;background:${color}"></div></div>
    <span class="asist-pct">${pct}%</span>
  </div>`;
}

// ── Filter + Sort ─────────────────────────────────────
function getRows() {
  let rows = [...DATA];
  if (filterText) {
    const q = filterText.toLowerCase();
    rows = rows.filter(r => r.materia.toLowerCase().includes(q));
  }
  if (sortCol !== null) {
    const key = COLS[sortCol].key;
    rows.sort((a,b) => {
      const av = a[key], bv = b[key];
      if (av === "" || av == null) return 1;
      if (bv === "" || bv == null) return -1;
      return typeof av === 'number'
        ? (av - bv) * sortDir
        : String(av).localeCompare(String(bv), 'es') * sortDir;
    });
  }
  return rows;
}

// ── Render ────────────────────────────────────────────
function render() {
  buildHead();
  const rows = getRows();
  const tbody = document.getElementById('tableBody');
  document.getElementById('resultCount').textContent =
    rows.length === DATA.length ? `${DATA.length} materias` : `${rows.length} de ${DATA.length}`;

  if (!rows.length) {
    tbody.innerHTML = `<tr class="empty-row"><td colspan="${COLS.length}">No se encontraron materias para "<strong>${filterText}</strong>"</td></tr>`;
    return;
  }

  tbody.innerHTML = rows.map(row => {
    const cells = COLS.map(c => {
      if (c.type === 'materia') {
        const parts = row.materia.split(' ');
        const roman = parts[parts.length-1];
        const name = parts.slice(0,-1).join(' ');
        return `<td><div class="materia-cell">${name} <span>${roman}</span></div></td>`;
      }
      if (c.type === 'asist') return `<td>${asistCell(row)}</td>`;
      const val = row[c.key];
      const isAlert = c.type === 'score-alert' && val !== "" && Number(val) < 6;
      const content = (val === "" || val == null) ? `<span style="color:var(--muted)">—</span>` : scoreBadge(val);
      return `<td class="mono${isAlert ? ' alert-cell' : ''}">${content}</td>`;
    }).join('');
    return `<tr>${cells}</tr>`;
  }).join('');
}

function sort(i) {
  if (!COLS[i].sortable) return;
  if (sortCol === i) sortDir *= -1;
  else { sortCol = i; sortDir = -1; }
  render();
}

document.getElementById('searchInput').addEventListener('input', e => {
  filterText = e.target.value.trim();
  render();
});

buildStats();
render();
</script>
</body>
</html>
