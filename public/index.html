<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Censo Hospitalar · CRER</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500;600&family=Fraunces:ital,wght@0,300;0,700;0,900;1,300&family=DM+Sans:wght@300;400;500;600&display=swap');
:root {
  --ink:#0f1117;--paper:#f7f4ef;--cream:#ede9e2;--rule:#d4cfc6;
  --blue:#1c3d6e;--blue2:#2d5fa0;--red:#b83232;--green:#1a6b3c;--amber:#b86a00;--white:#ffffff;
  --mono:'IBM Plex Mono',monospace;--display:'Fraunces',serif;--body:'DM Sans',sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}html,body{height:100%}
body{font-family:var(--body);background:var(--paper);color:var(--ink);min-height:100vh}
.header{background:var(--blue);color:var(--white);padding:0 40px;height:72px;display:flex;align-items:center;justify-content:space-between;border-bottom:3px solid var(--red);position:sticky;top:0;z-index:200}
.header-brand{display:flex;align-items:center;gap:16px}
.header-logo{width:36px;height:36px;background:var(--red);border-radius:6px;display:flex;align-items:center;justify-content:center;font-family:var(--mono);font-size:14px;font-weight:600;color:white;flex-shrink:0}
.header-title{font-family:var(--display);font-size:20px;font-weight:700;letter-spacing:-.3px}
.header-sub{font-family:var(--mono);font-size:10px;color:rgba(255,255,255,.5);letter-spacing:1px;text-transform:uppercase;margin-top:2px}
.header-meta{font-family:var(--mono);font-size:11px;color:rgba(255,255,255,.45);text-align:right;line-height:1.8}
#uploadScreen{min-height:calc(100vh - 75px);display:flex;align-items:center;justify-content:center;padding:40px}
.upload-card{background:var(--white);border:2px dashed var(--rule);border-radius:16px;padding:64px 80px;text-align:center;max-width:560px;width:100%;transition:border-color .2s,box-shadow .2s}
.upload-card.drag-over{border-color:var(--blue2);box-shadow:0 0 0 4px rgba(44,95,160,.1)}
.upload-icon{width:72px;height:72px;background:var(--cream);border-radius:50%;display:flex;align-items:center;justify-content:center;margin:0 auto 24px;font-size:28px;transition:transform .2s}
.upload-card:hover .upload-icon{transform:scale(1.08)}
.upload-title{font-family:var(--display);font-size:26px;font-weight:700;margin-bottom:10px}
.upload-desc{font-size:14px;color:#777;line-height:1.6;margin-bottom:28px}
.upload-btn{display:inline-block;background:var(--blue);color:white;font-family:var(--mono);font-size:13px;font-weight:500;padding:12px 28px;border-radius:8px;cursor:pointer;border:none;transition:background .15s,transform .1s;letter-spacing:.3px}
.upload-btn:hover{background:var(--blue2);transform:translateY(-1px)}
.upload-formats{font-family:var(--mono);font-size:11px;color:#aaa;margin-top:18px;letter-spacing:.5px}
#fileInput{display:none}
#loadingScreen{display:none;min-height:calc(100vh - 75px);align-items:center;justify-content:center;flex-direction:column;gap:24px}
.loader-ring{width:60px;height:60px;border:4px solid var(--cream);border-top-color:var(--blue);border-radius:50%;animation:spin .9s linear infinite}
@keyframes spin{to{transform:rotate(360deg)}}
.loader-text{font-family:var(--mono);font-size:13px;color:var(--blue);letter-spacing:.5px}
.loader-step{font-size:12px;color:#aaa;font-family:var(--mono);margin-top:-12px}
#dashboard{display:none}
.stat-bar{background:var(--blue);color:white;padding:0 40px;display:flex;align-items:stretch;border-bottom:1px solid rgba(255,255,255,.1);overflow-x:auto}
.stat-item{padding:18px 28px;border-right:1px solid rgba(255,255,255,.1);flex-shrink:0}
.stat-item:last-child{border-right:none;margin-left:auto}
.stat-num{font-family:var(--display);font-size:32px;font-weight:900;line-height:1}
.stat-lbl{font-family:var(--mono);font-size:10px;color:rgba(255,255,255,.5);text-transform:uppercase;letter-spacing:.8px;margin-top:4px}
.stat-item.action{display:flex;align-items:center}
.new-upload-btn{font-family:var(--mono);font-size:11px;padding:8px 16px;background:rgba(255,255,255,.12);color:white;border:1px solid rgba(255,255,255,.2);border-radius:6px;cursor:pointer;transition:background .15s;white-space:nowrap}
.new-upload-btn:hover{background:rgba(255,255,255,.22)}
.controls{background:var(--white);border-bottom:1px solid var(--rule);padding:14px 40px;display:flex;gap:12px;align-items:center;flex-wrap:wrap;position:sticky;top:72px;z-index:100;box-shadow:0 2px 8px rgba(0,0,0,.04)}
.ctrl-label{font-family:var(--mono);font-size:10px;color:#aaa;text-transform:uppercase;letter-spacing:.8px}
.ctrl-input,.ctrl-select{font-family:var(--body);font-size:13px;padding:7px 12px;border:1.5px solid var(--rule);border-radius:6px;background:var(--paper);color:var(--ink);outline:none;transition:border-color .15s}
.ctrl-input:focus,.ctrl-select:focus{border-color:var(--blue2)}
.ctrl-input{min-width:200px}
.results-count{margin-left:auto;font-family:var(--mono);font-size:11px;color:#aaa}
.content{padding:28px 40px 60px}
.no-results{text-align:center;padding:80px 40px;font-family:var(--display);font-size:22px;color:#ccc;font-style:italic}
.doctor-block{margin-bottom:20px;border-radius:10px;overflow:hidden;border:1.5px solid var(--rule);background:var(--white);box-shadow:0 1px 3px rgba(0,0,0,.04);transition:box-shadow .15s}
.doctor-block:hover{box-shadow:0 4px 16px rgba(0,0,0,.07)}
.doctor-header{padding:14px 20px;background:var(--blue);display:flex;align-items:center;gap:12px;cursor:pointer;user-select:none;flex-wrap:wrap}
.doc-name{font-family:var(--display);font-size:16px;font-weight:700;color:white;flex:1}
.unit-chips{display:flex;gap:5px;flex-wrap:wrap}
.unit-chip{font-family:var(--mono);font-size:10px;padding:2px 8px;background:rgba(255,255,255,.14);color:rgba(255,255,255,.8);border-radius:3px}
.pac-count{font-family:var(--mono);font-size:12px;background:var(--red);color:white;padding:3px 10px;border-radius:20px;font-weight:600;flex-shrink:0}
.toggle-icon{color:rgba(255,255,255,.6);font-size:11px;transition:transform .2s;flex-shrink:0}
.doctor-block.collapsed .toggle-icon{transform:rotate(-90deg)}
.doctor-block.collapsed .table-wrap{display:none}
.table-wrap{overflow-x:auto}
table{width:100%;border-collapse:collapse;font-size:13px}
thead tr{background:#f5f3f0;border-bottom:2px solid var(--rule)}
th{font-family:var(--mono);font-size:10px;font-weight:600;color:#888;text-transform:uppercase;letter-spacing:.7px;padding:10px 16px;text-align:left;white-space:nowrap}
td{padding:10px 16px;border-bottom:1px solid #f0ece6;vertical-align:middle}
tr:last-child td{border-bottom:none}
tr:hover td{background:#faf8f5}
.leito-badge{font-family:var(--mono);font-size:11px;background:#e8f0f8;color:var(--blue);padding:3px 8px;border-radius:4px;white-space:nowrap;font-weight:500}
.atend-code{font-family:var(--mono);font-size:11px;color:#bbb}
.pac-name{font-weight:500;color:var(--ink)}
.date-mono{font-family:var(--mono);font-size:12px;color:#888}
.dias-pill{font-family:var(--mono);font-size:12px;font-weight:600;padding:3px 10px;border-radius:20px;white-space:nowrap;display:inline-block}
.d-low{background:#e8f5e9;color:var(--green)}
.d-mid{background:#fff8e1;color:var(--amber)}
.d-high{background:#fce4ec;color:var(--red)}
.unit-pill{font-family:var(--mono);font-size:10px;padding:2px 8px;border-radius:20px;background:#f0edf8;color:#5533aa;white-space:nowrap;font-weight:500}
.error-card{background:#fff5f5;border:1.5px solid #f5c6c6;border-radius:10px;padding:24px 28px;margin:32px 0;color:var(--red);font-size:14px;line-height:1.6}
.error-card strong{display:block;margin-bottom:6px;font-size:15px}
@media(max-width:640px){.header,.stat-bar,.controls,.content{padding-left:16px;padding-right:16px}.upload-card{padding:40px 24px}.ctrl-input{min-width:140px}}
</style>
</head>
<body>
<header class="header">
  <div class="header-brand">
    <div class="header-logo">RH</div>
    <div>
      <div class="header-title">Censo Hospitalar · CRER</div>
      <div class="header-sub">Centro Estadual de Reabilitação e Readaptação</div>
    </div>
  </div>
  <div class="header-meta" id="headerMeta">Carregue o PDF do censo para começar</div>
</header>
<div id="uploadScreen">
  <div class="upload-card" id="dropZone">
    <div class="upload-icon">📄</div>
    <div class="upload-title">Carregar Censo</div>
    <div class="upload-desc">Arraste o PDF do censo aqui<br>ou clique para selecionar o arquivo.</div>
    <label for="fileInput" class="upload-btn">Selecionar PDF</label>
    <input type="file" id="fileInput" accept=".pdf">
    <div class="upload-formats">SOULMV · R_CENSO.pdf · Apenas PDF</div>
  </div>
</div>
<div id="loadingScreen">
  <div class="loader-ring"></div>
  <div class="loader-text">Analisando o documento...</div>
  <div class="loader-step" id="loaderStep">Enviando para processamento</div>
</div>
<div id="dashboard">
  <div class="stat-bar">
    <div class="stat-item"><div class="stat-num" id="sPacientes">–</div><div class="stat-lbl">Pacientes</div></div>
    <div class="stat-item"><div class="stat-num" id="sMedicos">–</div><div class="stat-lbl">Médicos</div></div>
    <div class="stat-item"><div class="stat-num" id="sDias">–</div><div class="stat-lbl">Dias médio</div></div>
    <div class="stat-item"><div class="stat-num" id="sData">–</div><div class="stat-lbl">Data censo</div></div>
    <div class="stat-item action"><button class="new-upload-btn" onclick="resetApp()">⟳ Novo PDF</button></div>
  </div>
  <div class="controls">
    <span class="ctrl-label">Buscar</span>
    <input class="ctrl-input" id="searchInput" type="text" placeholder="Paciente ou médico..." oninput="filterRender()">
    <span class="ctrl-label">Unidade</span>
    <select class="ctrl-select" id="unitSelect" onchange="filterRender()"><option value="">Todas</option></select>
    <span class="ctrl-label">Dias</span>
    <select class="ctrl-select" id="diasSelect" onchange="filterRender()">
      <option value="">Todos</option>
      <option value="low">0–7 dias</option>
      <option value="mid">8–30 dias</option>
      <option value="high">+30 dias</option>
    </select>
    <span class="results-count" id="resultsCount"></span>
  </div>
  <div class="content" id="tableContent"></div>
</div>
<script>
let allPatients=[];
const dropZone=document.getElementById('dropZone');
dropZone.addEventListener('dragover',e=>{e.preventDefault();dropZone.classList.add('drag-over')});
dropZone.addEventListener('dragleave',()=>dropZone.classList.remove('drag-over'));
dropZone.addEventListener('drop',e=>{e.preventDefault();dropZone.classList.remove('drag-over');const f=e.dataTransfer.files[0];if(f&&f.type==='application/pdf')processFile(f);else alert('Por favor, selecione um arquivo PDF.')});
document.getElementById('fileInput').addEventListener('change',e=>{if(e.target.files[0])processFile(e.target.files[0])});
function show(id){['uploadScreen','loadingScreen','dashboard'].forEach(s=>{document.getElementById(s).style.display=s===id?(id==='loadingScreen'?'flex':'block'):'none'})}
async function processFile(file){
  show('loadingScreen');
  document.getElementById('loaderStep').textContent='Enviando PDF para o servidor...';
  try{
    const fd=new FormData();fd.append('pdf',file);
    document.getElementById('loaderStep').textContent='Claude analisando o documento...';
    const res=await fetch('/api/processar',{method:'POST',body:fd});
    const dados=await res.json();
    if(!res.ok)throw new Error(dados.erro||'Erro no servidor');
    document.getElementById('loaderStep').textContent='Montando dashboard...';
    buildDashboard(dados);
  }catch(err){
    show('dashboard');
    document.getElementById('tableContent').innerHTML=`<div class="error-card"><strong>Erro ao processar o documento</strong>${err.message}<br><br><a href="#" onclick="resetApp();return false;" style="color:var(--blue);">← Tentar novamente</a></div>`;
    document.getElementById('sPacientes').textContent='!';
  }
}
function buildDashboard(data){
  allPatients=data.pacientes||[];
  const units=[...new Set(allPatients.map(p=>p.unidade))].sort();
  const us=document.getElementById('unitSelect');
  us.innerHTML='<option value="">Todas</option>';
  units.forEach(u=>{const o=document.createElement('option');o.value=u;o.textContent=u;us.appendChild(o)});
  document.getElementById('headerMeta').textContent=`Censo: ${data.dataCenso||'–'}  ·  ${allPatients.length} pacientes filtrados`;
  document.getElementById('sData').textContent=data.dataCenso||'–';
  show('dashboard');filterRender();
}
function filterRender(){
  const search=(document.getElementById('searchInput').value||'').toLowerCase();
  const unit=document.getElementById('unitSelect').value;
  const diasF=document.getElementById('diasSelect').value;
  const filtered=allPatients.filter(p=>{
    const ms=!search||p.paciente.toLowerCase().includes(search)||(p.medico||'').toLowerCase().includes(search);
    const mu=!unit||p.unidade===unit;
    const md=!diasF||(diasF==='low'&&p.dias<=7)||(diasF==='mid'&&p.dias>7&&p.dias<=30)||(diasF==='high'&&p.dias>30);
    return ms&&mu&&md;
  });
  const byDoc={};
  filtered.forEach(p=>{const k=p.medico||'Sem médico';if(!byDoc[k])byDoc[k]=[];byDoc[k].push(p)});
  const td=filtered.reduce((a,p)=>a+(p.dias||0),0);
  document.getElementById('sPacientes').textContent=filtered.length;
  document.getElementById('sMedicos').textContent=Object.keys(byDoc).length;
  document.getElementById('sDias').textContent=filtered.length?Math.round(td/filtered.length):0;
  document.getElementById('resultsCount').textContent=`${filtered.length} paciente${filtered.length!==1?'s':''} · ${Object.keys(byDoc).length} médico${Object.keys(byDoc).length!==1?'s':''}`;
  const container=document.getElementById('tableContent');
  container.innerHTML='';
  if(!Object.keys(byDoc).length){container.innerHTML='<div class="no-results">Nenhum paciente encontrado com esses filtros.</div>';return}
  Object.keys(byDoc).sort().forEach(med=>{
    const pacs=byDoc[med];
    const units=[...new Set(pacs.map(p=>p.unidade))];
    const block=document.createElement('div');
    block.className='doctor-block';
    block.innerHTML=`<div class="doctor-header" onclick="this.closest('.doctor-block').classList.toggle('collapsed')"><div class="doc-name">${med}</div><div class="unit-chips">${units.map(u=>`<span class="unit-chip">${u}</span>`).join('')}</div><span class="pac-count">${pacs.length} pac.</span><span class="toggle-icon">▾</span></div><div class="table-wrap"><table><thead><tr><th>Leito</th><th>Atendimento</th><th>Paciente</th><th>Internação</th><th>Dias</th><th>Unidade</th></tr></thead><tbody>${pacs.map(p=>`<tr><td><span class="leito-badge">${p.leito||'–'}</span></td><td><span class="atend-code">${p.atendimento||'–'}</span></td><td class="pac-name">${abreviarNome(p.paciente)}</td><td class="date-mono">${p.dtIntern||'–'}</td><td><span class="dias-pill ${diasClass(p.dias)}">${p.dias??'–'}d</span></td><td><span class="unit-pill">${p.unidade||'–'}</span></td></tr>`).join('')}</tbody></table></div>`;
    container.appendChild(block);
  });
}
function abreviarNome(nome){if(!nome)return'–';const p=nome.trim().split(/\s+/);if(p.length===1)return p[0];return p[0]+' '+p.slice(1).map(x=>x[0].toUpperCase()+'.').join(' ')}
function diasClass(d){if(d==null)return'';if(d<=7)return'd-low';if(d<=30)return'd-mid';return'd-high'}
function resetApp(){allPatients=[];document.getElementById('fileInput').value='';document.getElementById('searchInput').value='';document.getElementById('diasSelect').value='';show('uploadScreen')}
show('uploadScreen');
</script>
</body>
</html>
