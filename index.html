<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Absensi Angkringan Modern</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#8B4513">
<style>
  :root{
    --bg: #f0f0f5;
    --card: #ffffff;
    --text: #1c1c1e;
    --muted: rgba(28,28,30,0.6);

    --accent-gradient: linear-gradient(135deg,#8B4513 0%, #D2691E 100%);
    --accent-start: #8B4513;
    --accent-end: #D2691E;

    --accent-red: #ff4d4d;
    --accent-green: #4CAF50;
    --accent-orange: #FFC107;

    --soft-shadow: 0 6px 20px rgba(16,24,40,0.08);
    font-family: Inter, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  }

  *{box-sizing:border-box}
  body{
    margin:0;
    background:var(--bg);
    color:var(--text);
    display:flex;
    justify-content:center;
    padding:18px;
    min-height:100vh;
    background-size:cover;
    background-attachment:fixed;
  }
  .app{ width:100%; max-width:920px; margin:0 auto; }

  .banner{
    border-radius:14px;
    padding:22px;
    color:white;
    background: var(--accent-gradient);
    box-shadow: var(--soft-shadow);
    display:flex;
    justify-content:space-between;
    gap:12px;
    align-items:center;
    margin-bottom:16px;
  }
  .banner h1{ margin:0; font-size:20px; letter-spacing:0.4px; }
  .banner .sub{ font-size:13px; opacity:0.95 }

  .grid{ display:grid; gap:12px; grid-template-columns: repeat(auto-fit,minmax(160px,1fr)); margin-bottom:16px; }
  .card-action{
    background:var(--card);
    border-radius:12px;
    padding:14px;
    font-weight:700;
    text-align:center;
    cursor:pointer;
    transition: transform .14s ease, box-shadow .14s ease;
    box-shadow: 0 6px 14px rgba(16,24,40,0.04);
    user-select:none;
  }
  .card-action:active{
    transform: translateY(2px) scale(.995);
    box-shadow: 0 0 18px rgba(139,69,19,0.18);
  }
  .card-action.small{ padding:10px; font-weight:600; }

  /* tombol utama lebih besar */
  .big-action{
    grid-column: 1 / -1;
    font-size: 18px;
    font-weight: 800;
    padding: 22px;
    color: white;
    background: var(--accent-gradient);
    border: none;
    box-shadow: 0 6px 16px rgba(139,69,19,0.4);
  }
  .big-action:active{
    transform: scale(0.97);
    box-shadow: 0 0 18px rgba(139,69,19,0.4);
  }

  .section-row{ display:flex; justify-content:space-between; align-items:center; gap:12px; margin:12px 0; }
  .section-title{ color:var(--accent-start); font-weight:800; cursor:pointer; }

  #riwayat{ margin-bottom:24px; }
  .riwayat-item{
    background:var(--card);
    border-radius:10px;
    padding:12px;
    box-shadow: 0 6px 12px rgba(16,24,40,0.04);
    margin-bottom:10px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:12px;
  }
  .riwayat-item .meta{ color:var(--muted); font-size:13px; }
  .btn-icon{ background:none; border:none; cursor:pointer; font-size:16px; }

  #overlay{
    display:none;
    position:fixed; inset:0;
    z-index:2000;
    background: rgba(255,255,255,0.96);
    padding:20px;
    overflow:auto;
  }
  .overlay-inner{ max-width:820px; margin:0 auto; }
  .list-item{
    background:var(--card);
    padding:12px;
    border-radius:10px;
    margin-bottom:8px;
    cursor:pointer;
    display:flex; justify-content:space-between; align-items:center;
    box-shadow: 0 4px 10px rgba(16,24,40,0.04);
  }
  .batal-btn-overlay{
    margin-top:12px;
    background:var(--accent-red);
    color:white;
    padding:12px;
    border-radius:10px;
    text-align:center;
    cursor:pointer;
    font-weight:700;
  }

  table{ width:100%; border-collapse:collapse; margin-top:12px; background:transparent;}
  table th, table td{ padding:8px 10px; text-align:left; border-bottom:1px solid #f0f0f0; font-size:14px; }

  #toast{
    visibility:hidden;
    position:fixed; left:50%; transform:translateX(-50%);
    bottom:26px; z-index:3000; background:#222; color:#fff; padding:12px 18px; border-radius:10px;
    box-shadow: 0 6px 24px rgba(0,0,0,0.18);
  }
  #toast.show{ visibility:visible; animation: fadein .3s, fadeout .3s 2.5s; }
  @keyframes fadein{ from{ opacity:0; transform:translate(-50%,8px)} to{opacity:1; transform:translate(-50%,0)}}
  @keyframes fadeout{ to{ opacity:0} }

  @media (max-width:520px){
    .banner{ flex-direction:column; align-items:flex-start; gap:6px; }
  }

  .muted{ color:var(--muted); font-size:13px; }
  .pill{ background:rgba(0,0,0,0.06); padding:6px 8px; border-radius:8px; font-size:13px; }

  .dark-body{ background:#121214 !important; color:#eaeaea !important; }
  .dark-card{ background:#1f1f22 !important; color:#eaeaea !important; box-shadow:none !important; }

  /* small form elements */
  label{ display:block; margin-top:8px; font-weight:600; }
  input[type="text"], input[type="date"], input[type="time"], select, textarea{
    width:100%; padding:8px; border-radius:8px; border:1px solid #ddd; margin-top:6px; font-size:14px;
  }
  .row{ display:flex; gap:8px; }
  .col{ flex:1; }

  .day-box{ background:var(--card); padding:10px; border-radius:8px; margin-bottom:8px; box-shadow: 0 3px 8px rgba(16,24,40,0.03); }
  .small-muted{ font-size:12px; color:var(--muted); }
</style>
</head>
<body>
  <div class="app">
    <div class="banner">
      <div>
        <h1>ABSENSI ANGKRINGAN</h1>
        <div class="sub">Absen bebas — bisa kapan saja</div>
      </div>
      <div style="text-align:right">
        <div id="status-ringkas" class="pill">Memuat status...</div>
        <div style="height:6px"></div>
        <div class="muted" style="font-size:12px">Pengaturan: <span id="current-theme">Default</span></div>
      </div>
    </div>

    <div class="grid">
      <div class="card-action big-action" onclick="mulaiAbsen()">👋 Absen Sekarang</div>
      <div class="card-action" onclick="mulaiAbsenTanggalLain()">🗓️ Absen Tanggal Lain</div>
      <div class="card-action" onclick="mulaiGantikan()">🔁 Gantikan</div>
      <div class="card-action" onclick="tampilkanRanking()">🏆 Statistik Total</div>
      <div class="card-action" onclick="tampilkanLaporanBulanan()">🧾 Laporan Bulanan</div>
      <div class="card-action" onclick="tampilkanStatus()">📋 Status</div>
      <div class="card-action" onclick="tampilkanPengaturan()">⚙️ Pengaturan</div>
      <!-- reset data moved to laporan -->
    </div>

    <div class="section-row">
      <div class="section-title" onclick="mulaiFilterRiwayat()">Riwayat Absensi (<span id="filter-status">Semua</span>)</div>
      <div style="display:flex; gap:8px; align-items:center">
        <select id="sort-riwayat" onchange="tampilkan()" class="pill">
          <option value="terbaru">Terbaru</option>
          <option value="terlama">Terlama</option>
          <option value="nama_asc">Nama (A-Z)</option>
        </select>
        <button class="card-action small" onclick="tampilkanLaporanBulanan()">Lihat Laporan</button>
      </div>
    </div>

    <div id="riwayat"></div>
  </div>

  <div id="overlay"><div class="overlay-inner"></div></div>
  <div id="toast"></div>

<script>
// ===================== Storage keys & defaults =====================
const STORAGE_ABSENSI = 'absensi';
const STORAGE_KARYAWAN = 'karyawan';
const STORAGE_THEME = 'theme';
const STORAGE_BG = 'backgroundImage';
const STORAGE_JADWAL = 'jadwalMingguan';

// initial data (karyawan default)
let data = JSON.parse(localStorage.getItem(STORAGE_ABSENSI) || '[]');
let karyawan = JSON.parse(localStorage.getItem(STORAGE_KARYAWAN) || '["Lala","Zaki","Kemi","Haris","Izzul","Fawaz"]');

// Jadwal mingguan: user requested manual setup -> start from saved or empty days
let jadwalMingguan = JSON.parse(localStorage.getItem(STORAGE_JADWAL) || 'null');
if(!jadwalMingguan){
  jadwalMingguan = {
    "Senin": [],
    "Selasa": [],
    "Rabu": [],
    "Kamis": [],
    "Jumat": [],
    "Sabtu": [],
    "Minggu": []
  };
  localStorage.setItem(STORAGE_JADWAL, JSON.stringify(jadwalMingguan));
}

let mode = null;
let pengganti = null;
let filterAktif = "Semua";
let savedTheme = localStorage.getItem(STORAGE_THEME) || 'default';
let savedBg = localStorage.getItem(STORAGE_BG) || null;

// ===================== Utilities =====================
function todayDate(){ return new Date().toISOString().slice(0,10); }
function nowTime(){ return new Date().toLocaleTimeString('id-ID',{hour12:false,hour:'2-digit',minute:'2-digit'}); }
function showToast(msg){ const t=document.getElementById('toast'); t.textContent=msg; t.className='show'; setTimeout(()=>t.className='',(3000)); }
function tutupOverlay(){ document.getElementById('overlay').style.display='none'; document.querySelector('#overlay .overlay-inner').innerHTML=''; mode=null; pengganti=null; }

// ===================== Render Riwayat =====================
function tampilkan(){
  const wrap = document.getElementById('riwayat');
  wrap.innerHTML = '';
  document.getElementById('filter-status').textContent = filterAktif;

  let arr = data.slice();
  if(filterAktif !== 'Semua'){
    arr = arr.filter(d => (d.jenis === 'Absen' && d.nama === filterAktif) || (d.jenis === 'Gantikan' && (d.pengganti === filterAktif || d.digantikan === filterAktif)));
  }

  const sort = document.getElementById('sort-riwayat').value;
  arr.sort((a,b)=>{
    const ta = new Date((a.tanggal||'1970-01-01') + 'T' + (a.waktu||'00:00')).getTime();
    const tb = new Date((b.tanggal||'1970-01-01') + 'T' + (b.waktu||'00:00')).getTime();
    if(sort === 'terbaru') return tb - ta;
    if(sort === 'terlama') return ta - tb;
    if(sort === 'nama_asc') return (a.nama||a.pengganti||'').localeCompare(b.nama||b.pengganti||'');
    return tb - ta;
  });

  if(arr.length === 0){
    wrap.innerHTML = '<p class="muted" style="text-align:center">Belum ada riwayat untuk filter ini.</p>';
    updateStatusRingkas();
    return;
  }

  arr.forEach(entry => {
    const box = document.createElement('div'); box.className = 'riwayat-item';
    const left = document.createElement('div');
    if(entry.jenis === 'Absen'){
      left.innerHTML = `<strong>${entry.nama}</strong> <div class="small-muted">(Absen)</div><div class="meta">${entry.tanggal} • ${entry.waktu}</div>`;
    } else {
      left.innerHTML = `<strong>${entry.pengganti}</strong> <div class="small-muted">ganti ${entry.digantikan}</div><div class="meta">${entry.tanggal} • ${entry.waktu}</div>`;
    }
    const right = document.createElement('div');
    const del = document.createElement('button'); del.className='btn-icon'; del.innerText='❌'; del.title='Hapus entri';
    del.onclick = ()=>hapusRiwayat(entry);
    right.appendChild(del);
    box.appendChild(left); box.appendChild(right);
    wrap.appendChild(box);
  });

  updateStatusRingkas();
}

function hapusRiwayat(obj){
  if(!confirm('Yakin menghapus entri ini?')) return;
  data = data.filter(d => JSON.stringify(d) !== JSON.stringify(obj));
  localStorage.setItem(STORAGE_ABSENSI, JSON.stringify(data));
  tampilkan();
  showToast('Entri dihapus');
}

// ===================== Absen =====================
function absen(nama, tanggal, waktu){
  // prevent duplicate same person same date
  if(data.some(d => d.jenis === 'Absen' && d.nama === nama && d.tanggal === tanggal)){
    showToast(`${nama} sudah terdaftar hadir pada ${tanggal}`);
    return;
  }
  const entry = { jenis: 'Absen', nama, tanggal, waktu };
  data.push(entry);
  localStorage.setItem(STORAGE_ABSENSI, JSON.stringify(data));
  tampilkan();
  showToast(`${nama} berhasil absen`);
}

function mulaiAbsen(){
  mode = 'absen';
  const hadirHariIni = data.filter(d => d.tanggal === todayDate() && d.jenis === 'Absen').map(d => d.nama);
  tampilOverlayPilih(karyawan, '👋 Pilih Karyawan yang Absen', hadirHariIni);
}

function mulaiAbsenTanggalLain(){
  mode = 'absenLain';
  const ovInner = document.querySelector('#overlay .overlay-inner');
  ovInner.innerHTML = `
    <h3>🗓️ Absen Tanggal & Waktu Lain</h3>
    <label>Pilih Karyawan:</label>
    <select id="absen-lain-nama">${karyawan.map(n=>`<option value="${n}">${n}</option>`).join('')}</select>
    <label>Tanggal (maks hari ini):</label>
    <input type="date" id="absen-lain-tgl" max="${todayDate()}" value="${todayDate()}">
    <label>Waktu:</label>
    <input type="time" id="absen-lain-wkt" value="${nowTime()}">
    <div style="margin-top:12px"><button class="card-action" id="simpan-absen-lain">Simpan Absen</button></div>
  `;
  document.getElementById('simpan-absen-lain').onclick = ()=>{
    const nama = document.getElementById('absen-lain-nama').value;
    const tgl = document.getElementById('absen-lain-tgl').value;
    const wkt = document.getElementById('absen-lain-wkt').value;
    if(!nama || !tgl || !wkt){ showToast('Lengkapi data absen'); return; }
    absen(nama, tgl, wkt);
    tutupOverlay();
  };
  const b = document.createElement('div'); b.className='batal-btn-overlay'; b.innerText='Batal'; b.onclick=tutupOverlay;
  ovInner.appendChild(b);
  document.getElementById('overlay').style.display = 'block';
}

function tampilOverlayPilih(list, judul, hadirList = []){
  const ovInner = document.querySelector('#overlay .overlay-inner');
  ovInner.innerHTML = `<h3>${judul}</h3>`;
  list.forEach(name=>{
    const el = document.createElement('div'); el.className='list-item';
    const sudah = hadirList.includes(name);
    el.innerHTML = `<div>${name}</div><div class="muted">${sudah ? 'Sudah' : 'Pilih'}</div>`;
    if(!sudah) el.onclick = ()=>pilihNama(name);
    else { el.style.cursor='not-allowed'; el.style.opacity=0.6; }
    ovInner.appendChild(el);
  });
  const b = document.createElement('div'); b.className='batal-btn-overlay'; b.innerText='Batal'; b.onclick=tutupOverlay;
  ovInner.appendChild(b);
  document.getElementById('overlay').style.display = 'block';
}

function pilihNama(nama){
  if(mode === 'absen'){
    absen(nama, todayDate(), nowTime());
  } else if(mode === 'gantikan1'){
    pengganti = nama;
    mode = 'gantikan2';
    // show list excluding pengganti
    const others = karyawan.filter(k => k !== pengganti);
    tampilOverlayPilih(others, `🔁 ${pengganti} menggantikan siapa?`);
    return; // don't tutupOverlay yet, we show next overlay
  } else if(mode === 'gantikan2'){
    // should not happen here, because we handle in pilihNama when mode was gantikan1 --> gantikan called from choose
    gantikan(pengganti, nama);
  }
  tutupOverlay();
}

// ===================== Gantikan (rapikan alur) =====================
function mulaiGantikan(){
  mode = 'gantikan1';
  tampilOverlayPilih(karyawan, '🔁 Siapa yang Menggantikan?');
}

function gantikan(penggantiNama, digantikanNama){
  if(!penggantiNama || !digantikanNama){ showToast('Pilihan pengganti/digantikan tidak valid'); return; }
  data.push({ jenis: 'Gantikan', pengganti: penggantiNama, digantikan: digantikanNama, tanggal: todayDate(), waktu: nowTime() });
  localStorage.setItem(STORAGE_ABSENSI, JSON.stringify(data));
  tampilkan();
  showToast(`${penggantiNama} menggantikan ${digantikanNama}`);
  tutupOverlay();
}

// modify pilihNama to handle gantikan2 selection: override earlier function to call gantikan in this flow
// We already implement: when mode 'gantikan1' -> store pengganti & show next; when user picks next name, pilihNama executes else branch for mode 'gantikan1' after pengganti set.


// ===================== Reset Data MOVED -> will be used in laporan area =====================
function resetAllData(){
  if(!confirm('Yakin menghapus semua data absensi?')) return;
  data = [];
  localStorage.removeItem(STORAGE_ABSENSI);
  tampilkan();
  showToast('Semua data absensi dihapus');
}

// ===================== Laporan Bulanan (dengan Export + Reset) =====================
function tampilkanLaporanBulanan(){
  const ovInner = document.querySelector('#overlay .overlay-inner');
  const now = new Date();
  let options = '';
  for(let i=0;i<12;i++){
    const d = new Date(now.getFullYear(), now.getMonth()-i, 1);
    const val = `${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,'0')}`;
    options += `<option value="${val}" ${i===0?'selected':''}>${d.toLocaleDateString('id-ID',{month:'long', year:'numeric'})}</option>`;
  }
  ovInner.innerHTML = `
    <h3>🧾 Laporan Bulanan</h3>
    <label>Pilih Bulan:</label>
    <select id="lap-bulan">${options}</select>
    <div id="hasil-laporan" style="margin-top:12px"></div>
    <div style="display:flex; gap:8px; margin-top:12px">
      <button class="card-action" id="export-csv">⬇️ Ekspor CSV Bulan Ini</button>
      <button class="card-action" id="reset-data-small" style="background:#ffcccb; color:#000">⚠️ Reset Data</button>
    </div>
  `;
  document.getElementById('export-csv').onclick = eksportCSVFromLaporan;
  document.getElementById('reset-data-small').onclick = ()=>{
    if(confirm('Reset semua data absensi?')){
      resetAllData();
      tutupOverlay();
    }
  };
  // show
  document.getElementById('overlay').style.display = 'block';
  prosesLaporanBulanan();
}

function prosesLaporanBulanan(){
  const sel = document.getElementById('lap-bulan');
  if(!sel) return;
  const val = sel.value; const [y,m] = val.split('-'); const prefix = `${y}-${m}`;
  const dataBulan = data.filter(d => d.tanggal && d.tanggal.startsWith(prefix));
  // stats
  const stats = {};
  karyawan.forEach(k => stats[k] = { hadir:0, menggantikan:0, digantikan:0 });
  dataBulan.forEach(d=>{
    if(d.jenis === 'Absen' && stats[d.nama]) stats[d.nama].hadir++;
    if(d.jenis === 'Gantikan'){
      if(stats[d.pengganti]) stats[d.pengganti].menggantikan++;
      if(stats[d.digantikan]) stats[d.digantikan].digantikan++;
    }
  });
  const hasil = document.getElementById('hasil-laporan');
  if(dataBulan.length === 0){
    hasil.innerHTML = `<p class="muted">Tidak ada data untuk bulan ini.</p>`;
    return;
  }
  let html = `<table><thead><tr><th>Nama</th><th>Hadir</th><th>Ganti</th><th>Diganti</th></tr></thead><tbody>`;
  karyawan.forEach(k=>{
    const s = stats[k];
    html += `<tr><td>${k}</td><td>${s.hadir}</td><td>${s.menggantikan}</td><td>${s.digantikan}</td></tr>`;
  });
  html += `</tbody></table>`;
  hasil.innerHTML = html;
}

function eksportCSVFromLaporan(){
  const sel = document.getElementById('lap-bulan');
  if(!sel){ showToast('Pilih bulan dulu'); return; }
  const prefix = sel.value;
  const dataBulan = data.filter(d => d.tanggal && d.tanggal.startsWith(prefix));
  if(dataBulan.length === 0){ showToast('Tidak ada data untuk diekspor'); return; }
  let csv = 'Jenis,Tanggal,Waktu,Nama/Pengganti,Digantikan\n';
  dataBulan.forEach(d=>{
    if(d.jenis === 'Absen') csv += `Absen,${d.tanggal},${d.waktu},${d.nama},\n`;
    else csv += `Gantikan,${d.tanggal},${d.waktu},${d.pengganti},${d.digantikan}\n`;
  });
  const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a'); a.href = url; a.download = `laporan_absensi_${prefix}.csv`; document.body.appendChild(a); a.click(); document.body.removeChild(a); URL.revokeObjectURL(url);
  showToast('CSV diunduh');
}

// ===================== Statistik / Ranking =====================
function tampilkanRanking(){
  const stats = {};
  karyawan.forEach(k => stats[k] = { hadir:0, menggantikan:0, digantikan:0 });
  data.forEach(d=>{
    if(d.jenis === 'Absen' && stats[d.nama]) stats[d.nama].hadir++;
    if(d.jenis === 'Gantikan'){
      if(stats[d.pengganti]) stats[d.pengganti].menggantikan++;
      if(stats[d.digantikan]) stats[d.digantikan].digantikan++;
    }
  });
  const order = [...karyawan].sort((a,b) => stats[b].hadir - stats[a].hadir);
  const ovInner = document.querySelector('#overlay .overlay-inner');
  ovInner.innerHTML = `<h3>🏆 Statistik Total Kehadiran</h3>`;
  order.forEach((k,i)=>{
    const s = stats[k];
    const div = document.createElement('div'); div.className='list-item';
    div.innerHTML = `<div><strong>${i<3 ? (i===0?'🥇':i===1?'🥈':'🥉') : '#'+(i+1)} ${k}</strong><div class="muted">Hadir:${s.hadir} • Ganti:${s.menggantikan} • Diganti:${s.digantikan}</div></div>`;
    ovInner.appendChild(div);
  });
  const b=document.createElement('div'); b.className='batal-btn-overlay'; b.innerText='Tutup'; b.onclick=tutupOverlay; ovInner.appendChild(b);
  document.getElementById('overlay').style.display = 'block';
}

// ===================== Status: tampilkan jadwal mingguan + hadir hari ini =====================
function tampilkanStatus(){
  const ovInner = document.querySelector('#overlay .overlay-inner');
  ovInner.innerHTML = `<h3>📋 Status Hari Ini (${todayDate()})</h3>`;
  const hariIndex = new Date().getDay(); // 0 Sun .. 6 Sat
  const days = ["Minggu","Senin","Selasa","Rabu","Kamis","Jumat","Sabtu"];
  const todayName = days[hariIndex];
  const scheduled = jadwalMingguan[todayName] || [];
  const hadir = [...new Set(data.filter(d => d.tanggal === todayDate() && d.jenis === 'Absen').map(d=>d.nama))];
  const pengg = data.filter(d => d.tanggal === todayDate() && d.jenis === 'Gantikan');

  // scheduled
  const sBox = document.createElement('div'); sBox.className='day-box';
  sBox.innerHTML = `<strong>Jadwal (${todayName})</strong><div class="muted small-muted">${scheduled.length? scheduled.join(', ') : 'Tidak ada jadwal untuk hari ini'}</div>`;
  ovInner.appendChild(sBox);

  // hadir
  const hBox = document.createElement('div'); hBox.className='day-box';
  hBox.innerHTML = `<strong>Yang hadir hari ini</strong><div class="muted small-muted">${hadir.length? hadir.join(', ') : 'Belum ada yang absen'}</div>`;
  ovInner.appendChild(hBox);

  // penggantian
  if(pengg.length){
    const gBox = document.createElement('div'); gBox.className='day-box';
    gBox.innerHTML = `<strong>Penggantian hari ini</strong><div class="muted small-muted">${pengg.map(p=>`${p.pengganti}→${p.digantikan}`).join(' • ')}</div>`;
    ovInner.appendChild(gBox);
  }

  const b=document.createElement('div'); b.className='batal-btn-overlay'; b.innerText='Tutup'; b.onclick=tutupOverlay; ovInner.appendChild(b);
  document.getElementById('overlay').style.display='block';
}

function updateStatusRingkas(){
  const ring = document.getElementById('status-ringkas');
  const hadirToday = new Set(data.filter(d => d.tanggal === todayDate() && (d.jenis === 'Absen' || d.jenis === 'Gantikan')).map(d => d.nama || d.pengganti));
  ring.textContent = `Status Hari Ini: ${hadirToday.size} hadir`;
}

// ===================== Filter Riwayat =====================
function mulaiFilterRiwayat(){
  const ovInner = document.querySelector('#overlay .overlay-inner');
  ovInner.innerHTML = `<h3>🔎 Filter Riwayat</h3>`;
  const opsi = ['Semua', ...karyawan];
  opsi.forEach(name=>{
    const el = document.createElement('div'); el.className='list-item';
    el.innerHTML = `<div>${name}</div><div class="muted">Pilih</div>`;
    el.onclick = ()=>{ filterRiwayat(name); };
    ovInner.appendChild(el);
  });
  const b=document.createElement('div'); b.className='batal-btn-overlay'; b.innerText='Tutup'; b.onclick=tutupOverlay; ovInner.appendChild(b);
  document.getElementById('overlay').style.display = 'block';
}

function filterRiwayat(n){
  filterAktif = (n === 'Semua') ? 'Semua' : n;
  tampilkan();
  tutupOverlay();
}

// ===================== Pengaturan (Tema + Jadwal Mingguan + Manage Karyawan) =====================
function applyThemeAndBg(){
  document.getElementById('current-theme').textContent = savedTheme.charAt(0).toUpperCase() + savedTheme.slice(1);
  if(savedTheme === 'gelap'){
    document.body.classList.add('dark-body');
    document.querySelectorAll('.card-action, .riwayat-item, .list-item, .day-box').forEach(el=> el.classList.add('dark-card'));
  } else {
    document.body.classList.remove('dark-body');
    document.querySelectorAll('.card-action, .riwayat-item, .list-item, .day-box').forEach(el=> el.classList.remove('dark-card'));
  }
  if(savedBg){
    document.body.style.backgroundImage = `url('${savedBg}')`;
  } else {
    document.body.style.backgroundImage = '';
  }
}

function tampilkanPengaturan(){
  const ovInner = document.querySelector('#overlay .overlay-inner');
  ovInner.innerHTML = `<h3>⚙️ Pengaturan</h3>
    <div style="display:flex; gap:12px; flex-wrap:wrap;">
      <div style="flex:1; min-width:260px;">
        <h4>Theme & Background</h4>
        <label>Pilih Tema:</label>
        <select id="tema-select"><option value="default">Default</option><option value="gelap">Gelap</option><option value="terang">Terang</option></select>
        <label style="margin-top:8px">Upload Foto Latar (opsional):</label>
        <input type="file" id="bg-upload" accept="image/*">
        <div style="display:flex; gap:8px; margin-top:8px;">
          <button class="card-action" id="save-theme-btn">Simpan</button>
          <button class="card-action" id="reset-theme-btn">Reset</button>
        </div>
      </div>

      <div style="flex:1; min-width:300px;">
        <h4>Kelola Karyawan</h4>
        <div class="muted small-muted">Tambah karyawan baru (akan muncul di pilihan absen & jadwal)</div>
        <div style="display:flex; gap:8px; margin-top:8px;">
          <input type="text" id="new-karyawan-name" placeholder="Nama baru">
          <button class="card-action" id="add-karyawan-btn">Tambah</button>
        </div>
        <div id="karyawan-list" style="margin-top:8px;"></div>
      </div>
    </div>

    <hr style="margin:12px 0">

    <h4>Jadwal Mingguan (atur siapa seharusnya absen setiap hari)</h4>
    <div id="jadwal-editor"></div>

    <div style="margin-top:12px; display:flex; gap:8px;">
      <button class="card-action" id="save-jadwal-btn">Simpan Jadwal</button>
      <button class="card-action" id="reset-jadwal-btn" style="background:#ffd6a5; color:#000">Reset Jadwal</button>
    </div>
  `;

  // set theme select
  document.getElementById('tema-select').value = savedTheme;

  // populate karyawan list (with delete)
  function renderKaryawanList(){
    const container = document.getElementById('karyawan-list');
    container.innerHTML = '';
    karyawan.forEach((k, idx)=>{
      const div = document.createElement('div'); div.className='list-item';
      div.innerHTML = `<div>${k}</div><div style="display:flex; gap:6px"><button class="card-action small" onclick="editKaryawanName(${idx})">Edit</button><button class="card-action small" style="background:#ffb3b3" onclick="removeKaryawan(${idx})">Hapus</button></div>`;
      container.appendChild(div);
    });
  }
  window.editKaryawanName = function(index){
    const newName = prompt('Ubah nama karyawan:', karyawan[index]);
    if(newName && newName.trim()){
      const old = karyawan[index];
      karyawan[index] = newName.trim();
      // update any jadwal entries and data references? We'll keep historical data names as-is (not replaced) to avoid altering past records
      localStorage.setItem(STORAGE_KARYAWAN, JSON.stringify(karyawan));
      renderKaryawanList();
      showToast('Nama karyawan diperbarui (catatan: riwayat lama tetap tidak berubah)');
    }
  };
  window.removeKaryawan = function(index){
    if(!confirm('Hapus karyawan dari daftar? (riwayat lama tidak akan diubah)')) return;
    const removed = karyawan.splice(index,1)[0];
    localStorage.setItem(STORAGE_KARYAWAN, JSON.stringify(karyawan));
    renderKaryawanList();
    showToast(removed+' dihapus dari daftar');
  };
  document.getElementById('add-karyawan-btn').onclick = ()=>{
    const v = document.getElementById('new-karyawan-name').value.trim();
    if(!v){ showToast('Masukkan nama'); return; }
    if(karyawan.includes(v)){ showToast('Nama sudah ada'); return; }
    karyawan.push(v); localStorage.setItem(STORAGE_KARYAWAN, JSON.stringify(karyawan));
    document.getElementById('new-karyawan-name').value='';
    renderKaryawanList(); renderJadwalEditor(); showToast('Karyawan ditambahkan');
  };
  renderKaryawanList();

  // render jadwal editor
  function renderJadwalEditor(){
    const ed = document.getElementById('jadwal-editor');
    ed.innerHTML = '';
    const daysOrder = ["Senin","Selasa","Rabu","Kamis","Jumat","Sabtu","Minggu"];
    daysOrder.forEach(day=>{
      const box = document.createElement('div'); box.className='day-box';
      box.innerHTML = `<strong>${day}</strong><div class="small-muted">Centang karyawan yang dijadwalkan</div>`;
      const list = document.createElement('div'); list.style.marginTop='8px';
      karyawan.forEach(k=>{
        const id = `chk_${day}_${k}`;
        const chk = document.createElement('div'); chk.style.marginBottom='6px';
        chk.innerHTML = `<label><input type="checkbox" id="${id}" ${ (jadwalMingguan[day] || []).includes(k) ? 'checked' : '' }> ${k}</label>`;
        list.appendChild(chk);
      });
      // quick add input for day
      const addRow = document.createElement('div'); addRow.style.marginTop='8px';
      addRow.innerHTML = `<input type="text" id="add_${day}" placeholder="Tambah nama ke ${day} (jika belum ada di daftar)"><button class="card-action small" id="btnadd_${day}">Tambah</button>`;
      box.appendChild(list); box.appendChild(addRow);
      ed.appendChild(box);

      // add button action
      document.addEventListener('click', function handler(e){
        if(e.target && e.target.id === `btnadd_${day}`){
          const val = document.getElementById(`add_${day}`).value.trim();
          if(!val){ showToast('Masukkan nama'); return; }
          // add to karyawan if not exists
          if(!karyawan.includes(val)){ karyawan.push(val); localStorage.setItem(STORAGE_KARYAWAN, JSON.stringify(karyawan)); showToast('Karyawan baru ditambahkan'); }
          // add to jadwalMingguan day
          if(!jadwalMingguan[day].includes(val)) jadwalMingguan[day].push(val);
          renderJadwalEditor(); renderKaryawanList(); 
        }
      });
    });
  }
  // render functions accessible
  window.renderJadwalEditor = renderJadwalEditor;
  window.renderKaryawanList = renderKaryawanList;
  renderJadwalEditor();

  // save theme
  document.getElementById('save-theme-btn').onclick = ()=>{
    const sel = document.getElementById('tema-select').value;
    savedTheme = sel; localStorage.setItem(STORAGE_THEME, savedTheme);
    const file = document.getElementById('bg-upload').files[0];
    if(file){
      const reader = new FileReader();
      reader.onload = (e)=>{
        savedBg = e.target.result; localStorage.setItem(STORAGE_BG, savedBg); applyThemeAndBg(); showToast('Tema & background disimpan');
      };
      reader.readAsDataURL(file);
    } else {
      // remove bg if none selected
      localStorage.removeItem(STORAGE_BG); savedBg = null; localStorage.setItem(STORAGE_THEME, savedTheme); applyThemeAndBg(); showToast('Tema disimpan');
    }
    document.getElementById('current-theme').textContent = savedTheme;
  };

  document.getElementById('reset-theme-btn').onclick = ()=>{
    if(confirm('Reset tema & background ke default?')){
      savedTheme = 'default'; savedBg = null;
      localStorage.removeItem(STORAGE_THEME); localStorage.removeItem(STORAGE_BG);
      applyThemeAndBg(); showToast('Tampilan dikembalikan ke default');
    }
  };

  // save jadwal
  document.getElementById('save-jadwal-btn').onclick = ()=>{
    const daysOrder = ["Senin","Selasa","Rabu","Kamis","Jumat","Sabtu","Minggu"];
    daysOrder.forEach(day=>{
      const selected = [];
      karyawan.forEach(k=>{
        const id = `chk_${day}_${k}`;
        const el = document.getElementById(id);
        if(el && el.checked) selected.push(k);
      });
      jadwalMingguan[day] = selected;
    });
    localStorage.setItem(STORAGE_JADWAL, JSON.stringify(jadwalMingguan));
    localStorage.setItem(STORAGE_KARYAWAN, JSON.stringify(karyawan));
    showToast('Jadwal mingguan disimpan');
    applyThemeAndBg(); renderJadwalEditor(); renderKaryawanList();
  };

  document.getElementById('reset-jadwal-btn').onclick = ()=>{
    if(confirm('Reset semua jadwal mingguan ke kosong?')){
      ["Senin","Selasa","Rabu","Kamis","Jumat","Sabtu","Minggu"].forEach(d=>jadwalMingguan[d]=[]);
      localStorage.setItem(STORAGE_JADWAL, JSON.stringify(jadwalMingguan));
      renderJadwalEditor(); showToast('Jadwal dikosongkan');
    }
  };
}

// ===================== Init =====================
applyThemeAndBg();
tampilkan();
updateStatusRingkas();

// PWA: try register service worker if exists
if('serviceWorker' in navigator){
  navigator.serviceWorker.register('service-worker.js').then(()=>console.log('SW registered')).catch(()=>{/* ignore */});
}

// Expose some functions globally for inline handlers (if necessary)
window.tampilkan = tampilkan;
window.tampilkanLaporanBulanan = tampilkanLaporanBulanan;
window.tampilkanRanking = tampilkanRanking;
window.tampilkanStatus = tampilkanStatus;
window.tampilkanPengaturan = tampilkanPengaturan;
window.mulaiAbsen = mulaiAbsen;
window.mulaiAbsenTanggalLain = mulaiAbsenTanggalLain;
window.mulaiGantikan = mulaiGantikan;
window.mulaiFilterRiwayat = mulaiFilterRiwayat;
</script>
</body>
</html>