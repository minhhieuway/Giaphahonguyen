# Giaphahonguyen[index.html.html](https://github.com/user-attachments/files/23775229/index.html.html)
<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Gia phả — Trình chỉnh sửa (Admin)</title>
  <style>
    :root{--bg:#f5f7fb;--card:#fff;--accent:#2b6cb0}
    body{font-family:Inter, Arial, Helvetica, sans-serif;margin:0;background:var(--bg);color:#111}
    header{background:var(--accent);color:#fff;padding:14px 18px;display:flex;align-items:center;justify-content:space-between}
    header h1{margin:0;font-size:18px}
    .wrap{padding:18px;max-width:1100px;margin:18px auto}
    .toolbar{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:12px}
    button, input, select{font-size:14px}
    .panel{background:var(--card);padding:12px;border-radius:10px;box-shadow:0 6px 18px rgba(16,24,40,0.06)}
    .tree{margin-top:16px;display:flex;flex-direction:column;gap:12px;align-items:center}
    .generation{display:flex;gap:12px;align-items:flex-start}
    .node{min-width:160px;max-width:220px;padding:10px;border-radius:8px;box-shadow:0 4px 10px rgba(16,24,40,0.05);cursor:default}
    .node .name{font-weight:700}
    .node .meta{font-size:12px;margin-top:6px}
    .controls{display:flex;gap:6px;margin-left:6px}
    .small{padding:6px 8px}
    .row{display:flex;gap:12px;align-items:center}
    .right{margin-left:auto}
    .modal{position:fixed;inset:0;background:rgba(0,0,0,0.45);display:flex;align-items:center;justify-content:center}
    .modal .box{background:#fff;padding:16px;border-radius:10px;width:420px;max-width:95%}
    label{display:block;margin:8px 0 4px;font-size:13px}
    input[type=text],input[type=number],select{width:100%;padding:8px;border-radius:6px;border:1px solid #ddd}
    .flex{display:flex;gap:8px;align-items:center}
    footer{font-size:13px;color:#666;margin-top:12px;text-align:center}
    .link-like{color:var(--accent);text-decoration:underline;cursor:pointer}
    .hint{font-size:12px;color:#666}
    .gen-title{font-size:14px;font-weight:600;margin-bottom:8px}
  </style>
</head>
<body>
  <header>
    <h1>Gia phả gia đình — Xem & Chỉnh sửa (Admin)</h1>
    <div>
      <span id="status">Chế độ: <strong id="mode">Chỉ xem</strong></span>
    </div>
  </header>

  <div class="wrap">
    <div class="toolbar panel">
      <div class="row">
        <button id="btn-admin" class="small">Đăng nhập Admin</button>
        <button id="btn-add" class="small" disabled>Thêm người (cùng đời)</button>
        <button id="btn-add-child" class="small" disabled>Thêm con</button>
        <button id="btn-export" class="small">Xuất JSON</button>
        <button id="btn-import" class="small">Nhập JSON</button>
        <button id="btn-shareurl" class="small">Tạo link chia sẻ</button>
        <div style="margin-left:12px">
          <label class="hint">Font chung:</label>
          <select id="fontSelect"><option value="Inter, Arial">Inter</option><option value="Georgia, serif">Georgia</option><option value="Tahoma, Arial">Tahoma</option><option value="Courier New, monospace">Mono</option></select>
        </div>
        <div class="right hint">Lưu tự động (localStorage). Đăng nhập admin để sửa, xóa, gắn link Facebook.</div>
      </div>
    </div>

    <div id="treePanel" class="panel">
      <div class="gen-title">Cây gia phả (tối đa 5 đời hiển thị)</div>
      <div id="tree" class="tree"></div>
      <div class="hint" style="margin-top:8px">Mỗi ô có thể gắn link Facebook. Chọn ô để chỉnh sửa.</div>
    </div>

    <div style="margin-top:12px" class="panel">
      <div style="display:flex;gap:12px;align-items:center">
        <div>
          <label>Thay đổi font chữ của ô:</label>
          <input id="nodeFont" placeholder="ví dụ: 14px Arial" />
        </div>
        <div>
          <label>Màu chữ mặc định:</label>
          <input id="defaultTextColor" type="color" value="#111111" />
        </div>
        <div>
          <label>Màu nền ô mặc định:</label>
          <input id="defaultBgColor" type="color" value="#ffffff" />
        </div>
        <div class="right"><button id="applyStyle" class="small">Áp dụng cho tất cả</button></div>
      </div>
    </div>

    <footer class="panel">
      <div>Gợi ý hosting: Đưa file này (index.html) lên GitHub Pages hoặc Netlify để có 1 link cố định. Xem hướng dẫn ngắn bên dưới.</div>
    </footer>

    <div id="modal" style="display:none" class="modal">
      <div class="box">
        <div id="modalTitle" style="font-weight:700">Chỉnh sửa người</div>
        <label>Tên</label>
        <input id="m_name" />
        <label>Năm sinh</label>
        <input id="m_birth" type="number" />
        <label>Năm mất (nếu có)</label>
        <input id="m_death" type="number" />
        <label>Facebook URL (ví dụ https://facebook.com/abc)</label>
        <input id="m_fb" type="text" />
        <label>Màu nền ô</label>
        <input id="m_bg" type="color" />
        <label>Màu chữ</label>
        <input id="m_color" type="color" />
        <label>Font (vd: 14px Arial)</label>
        <input id="m_font" type="text" />
        <div style="display:flex;justify-content:flex-end;margin-top:12px;gap:8px">
          <button id="m_delete" class="small" style="background:#fff">Xóa</button>
          <button id="m_cancel" class="small">Hủy</button>
          <button id="m_save" class="small">Lưu</button>
        </div>
      </div>
    </div>

    <div id="adminLogin" style="display:none" class="modal">
      <div class="box">
        <div style="font-weight:700">Đăng nhập Admin</div>
        <label>Mật khẩu Admin</label>
        <input id="adminPass" type="password" />
        <div style="display:flex;justify-content:flex-end;margin-top:12px;gap:8px">
          <button id="adminCancel" class="small">Hủy</button>
          <button id="adminOk" class="small">Đăng nhập</button>
        </div>
        <div class="hint" style="margin-top:10px">Mật khẩu mặc định: <strong>admin123</strong>. Thay đổi trong mã nguồn (biến ADMIN_PASSWORD).</div>
      </div>
    </div>

  </div>

  <script>
    /*********** CẤU HÌNH ***********/
    const ADMIN_PASSWORD = 'admin123'; // thay đổi khi deploy
    const MAX_GEN = 5;
    /*********** DỮ LIỆU MẪU (nếu localStorage rỗng) ***********/
    const SAMPLE = {
      people: [
        {id:'p1', name:'Ông A', birth:1940, death:2010, parent:null, bg:'#fff', color:'#111', font:'14px Inter, Arial', fb:''},
        {id:'p2', name:'Bà B', birth:1945, death:2015, parent:'p1', bg:'#fff', color:'#111', font:'14px Inter, Arial', fb:''},
        {id:'p3', name:'Con C', birth:1970, death:'', parent:'p2', bg:'#fff', color:'#111', font:'14px Inter, Arial', fb:''},
        {id:'p4', name:'Con D', birth:1973, death:'', parent:'p2', bg:'#fff', color:'#111', font:'14px Inter, Arial', fb:''},
        {id:'p5', name:'Thế hệ sau E', birth:1998, death:'', parent:'p3', bg:'#fff', color:'#111', font:'14px Inter, Arial', fb:''},
      ]
    };

    /*********** TRẠNG THÁI  ***********/
    let DATA = null;
    let IS_ADMIN = false;
    let selectedNodeId = null;

    function saveToStorage(){ localStorage.setItem('giapha_v1', JSON.stringify(DATA)); }
    function loadFromStorage(){ const v = localStorage.getItem('giapha_v1'); if(v) return JSON.parse(v); return JSON.parse(JSON.stringify(SAMPLE)); }

    function init(){ DATA = loadFromStorage(); renderTree(); document.getElementById('fontSelect').addEventListener('change', e=>{document.body.style.fontFamily = e.target.value});
      document.getElementById('btn-admin').addEventListener('click', showAdminLogin);
      document.getElementById('btn-add').addEventListener('click', ()=>openModalForNew(null));
      document.getElementById('btn-add-child').addEventListener('click', ()=>{ if(!selectedNodeId) return alert('Chọn 1 người làm cha/mẹ trước'); openModalForNew(selectedNodeId); });
      document.getElementById('btn-export').addEventListener('click', ()=>{ const blob = new Blob([JSON.stringify(DATA,null,2)],{type:'application/json'}); const url = URL.createObjectURL(blob); const a=document.createElement('a'); a.href=url; a.download='giapha.json'; a.click(); URL.revokeObjectURL(url); });
      document.getElementById('btn-import').addEventListener('click', ()=>{ const inp = document.createElement('input'); inp.type='file'; inp.accept='.json'; inp.onchange = e=>{ const f = e.target.files[0]; const r=new FileReader(); r.onload = ()=>{ try{ DATA = JSON.parse(r.result); saveToStorage(); renderTree(); alert('Đã nhập và lưu'); }catch(err){ alert('File không hợp lệ') } }; r.readAsText(f); }; inp.click(); });
      document.getElementById('btn-shareurl').addEventListener('click', createShareURL);
      document.getElementById('applyStyle').addEventListener('click', applyGlobalStyle);

      // modal buttons
      document.getElementById('m_cancel').addEventListener('click', closeModal);
      document.getElementById('m_save').addEventListener('click', saveModal);
      document.getElementById('m_delete').addEventListener('click', deleteSelected);

      // admin modal
      document.getElementById('adminCancel').addEventListener('click', ()=>document.getElementById('adminLogin').style.display='none');
      document.getElementById('adminOk').addEventListener('click', ()=>{ const p = document.getElementById('adminPass').value; if(p===ADMIN_PASSWORD){ setAdmin(true); document.getElementById('adminLogin').style.display='none'; document.getElementById('adminPass').value=''; } else alert('Sai mật khẩu'); });

      // click outside to close modals
      document.getElementById('modal').addEventListener('click', (e)=>{ if(e.target===document.getElementById('modal')) closeModal(); });
      document.getElementById('adminLogin').addEventListener('click', (e)=>{ if(e.target===document.getElementById('adminLogin')) document.getElementById('adminLogin').style.display='none'; });
    }

    function setAdmin(state){ IS_ADMIN = state; document.getElementById('mode').innerText = state ? 'Admin' : 'Chỉ xem'; document.getElementById('btn-add').disabled = !state; document.getElementById('btn-add-child').disabled = !state; document.getElementById('btn-admin').innerText = state? 'Đăng xuất Admin' : 'Đăng nhập Admin'; if(!state){ selectedNodeId=null; } else { document.getElementById('btn-admin').addEventListener('click', logoutAdminOnce); }
    }
    function logoutAdminOnce(){ if(!IS_ADMIN) return; IS_ADMIN=false; document.getElementById('mode').innerText='Chỉ xem'; document.getElementById('btn-add').disabled=true; document.getElementById('btn-add-child').disabled=true; document.getElementById('btn-admin').innerText='Đăng nhập Admin'; }

    function showAdminLogin(){ if(IS_ADMIN){ logoutAdminOnce(); return;} document.getElementById('adminLogin').style.display='flex'; }

    function renderTree(){ const tree = document.getElementById('tree'); tree.innerHTML='';
      // build generations: start from root ancestors (parent==null), then children, up to MAX_GEN
      let gens = [];
      let current = DATA.people.filter(p=>p.parent==null);
      gens.push(current);
      for(let i=1;i<MAX_GEN;i++){
        const prev = gens[i-1]||[];
        let next = [];
        prev.forEach(p=>{ const children = DATA.people.filter(x=>x.parent===p.id); next.push(...children); });
        gens.push(next);
      }
      gens.forEach((gen, idx)=>{
        const row = document.createElement('div'); row.className='generation';
        if(gen.length===0){ const empty = document.createElement('div'); empty.className='hint'; empty.style.padding='10px'; empty.innerText='Không có người ở đời này'; row.appendChild(empty); }
        gen.forEach(person=>{
          const n = document.createElement('div'); n.className='node'; n.style.background = person.bg || '#fff'; n.style.color = person.color || '#111'; n.style.font = person.font || '14px Inter, Arial';
          n.innerHTML = `<div class='name'>${escapeHtml(person.name)}</div><div class='meta'>${person.birth || ''}${person.death? ' – '+person.death: ''}</div>`;
          if(person.fb) n.style.cursor='pointer';
          n.addEventListener('click', (e)=>{ e.stopPropagation(); if(IS_ADMIN) { selectedNodeId = person.id; openModal(person.id); } else { if(person.fb) window.open(person.fb,'_blank'); } });
          // selected highlight
          if(selectedNodeId===person.id) n.style.boxShadow='0 0 0 3px rgba(43,108,176,0.12)';
          row.appendChild(n);
        });
        tree.appendChild(row);
      });
    }

    function openModal(id){ const modal = document.getElementById('modal'); modal.style.display='flex'; document.getElementById('m_delete').style.display = id ? 'inline-block':'none'; document.getElementById('modalTitle').innerText = id ? 'Chỉnh sửa người':'Thêm người mới'; if(id){ const p = DATA.people.find(x=>x.id===id); document.getElementById('m_name').value = p.name||''; document.getElementById('m_birth').value = p.birth||''; document.getElementById('m_death').value = p.death||''; document.getElementById('m_fb').value = p.fb||''; document.getElementById('m_bg').value = p.bg||'#ffffff'; document.getElementById('m_color').value = p.color||'#111111'; document.getElementById('m_font').value = p.font||''; } else { document.getElementById('m_name').value=''; document.getElementById('m_birth').value=''; document.getElementById('m_death').value=''; document.getElementById('m_fb').value=''; document.getElementById('m_bg').value='#ffffff'; document.getElementById('m_color').value='#111111'; document.getElementById('m_font').value='14px Inter, Arial'; }
      // store temporary current editing id
      modal.dataset.editId = id||'';
    }
    function closeModal(){ document.getElementById('modal').style.display='none'; document.getElementById('modal').dataset.editId=''; }

    function openModalForNew(parentId){ selectedNodeId = null; openModal(null); document.getElementById('modal').dataset.newParent = parentId||''; }

    function saveModal(){ const id = document.getElementById('modal').dataset.editId; const newParent = document.getElementById('modal').dataset.newParent; const name = document.getElementById('m_name').value.trim(); if(!name) return alert('Nhập tên'); const birth = document.getElementById('m_birth').value; const death = document.getElementById('m_death').value; const fb = document.getElementById('m_fb').value.trim(); const bg = document.getElementById('m_bg').value; const color = document.getElementById('m_color').value; const font = document.getElementById('m_font').value;
      if(id){ const p = DATA.people.find(x=>x.id===id); p.name=name; p.birth=birth; p.death=death; p.fb=fb; p.bg=bg; p.color=color; p.font=font; }
      else { const nid = 'p'+(Date.now().toString(36)); DATA.people.push({id:nid,name, birth, death, parent: newParent||null, fb, bg, color, font}); document.getElementById('modal').dataset.newParent=''; }
      saveToStorage(); closeModal(); renderTree(); }

    function deleteSelected(){ if(!confirm('Bạn có chắc muốn xóa người này? (hành động không thể hoàn tác)')) return; const id = document.getElementById('modal').dataset.editId; if(!id) return; // also remove descendants
      const toRemove = new Set(); function collect(x){ toRemove.add(x); DATA.people.filter(p=>p.parent===x).forEach(c=>collect(c.id)); }
      collect(id);
      DATA.people = DATA.people.filter(p=>!toRemove.has(p.id)); saveToStorage(); closeModal(); renderTree(); }

    function applyGlobalStyle(){ const font = document.getElementById('nodeFont').value; const txt = document.getElementById('defaultTextColor').value; const bg = document.getElementById('defaultBgColor').value; DATA.people.forEach(p=>{ if(font) p.font = font; p.color = txt; p.bg = bg; }); saveToStorage(); renderTree(); alert('Đã áp dụng'); }

    function createShareURL(){ // put data into URL-safe base64
      const json = JSON.stringify(DATA);
      const b64 = btoa(unescape(encodeURIComponent(json)));
      const url = location.origin + location.pathname + '?data=' + encodeURIComponent(b64);
      copyText(url);
      alert('Link chia sẻ đã được copy vào clipboard. Bạn có thể dán và gửi cho người khác.');
    }

    function copyText(t){ navigator.clipboard?.writeText(t).catch(()=>{ const ta=document.createElement('textarea'); ta.value=t; document.body.appendChild(ta); ta.select(); document.execCommand('copy'); ta.remove(); }); }

    // on load, check if URL has data param. If so, load that as DATA (view-only). Otherwise load from storage.
    window.addEventListener('DOMContentLoaded', ()=>{
      const params = new URLSearchParams(location.search);
      if(params.has('data')){
        try{ const b = params.get('data'); const json = decodeURIComponent(atob(b)); DATA = JSON.parse(json); // share link is view-only by default
          setAdmin(false);
        }catch(e){ alert('Không đọc được tham số data'); DATA = loadFromStorage(); }
      } else { init(); }
      // ensure init always called
      if(!DATA) init(); renderTree();
      // keyboard shortcuts
      document.addEventListener('keydown', (e)=>{ if(e.key==='Escape'){ closeModal(); document.getElementById('adminLogin').style.display='none'; } });
    });

    function escapeHtml(s){ if(!s) return ''; return s.replace(/[&<>"']/g, function(c){ return {'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]; }); }

    init();
  </script>
</body>
</html>
