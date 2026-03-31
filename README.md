[INDEX.html](https://github.com/user-attachments/files/26366937/INDEX.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Libertario Coffee Roasters — Análisis Marzo 2026</title>
<style>
:root{
  --bg:#1a1a1a;--bg2:#242424;--bg3:#2e2e2e;
  --txt:#e8e6df;--txt2:#a0a09a;--txt3:#55554f;
  --brd:rgba(255,255,255,.08);--brd2:rgba(255,255,255,.15);
  --G:#1D9E75;--Gbg:rgba(29,158,117,.15);--Gtxt:#4fd4a8;
  --R:#E24B4A;--Rbg:rgba(226,75,74,.15);--Rtxt:#f08080;
  --B:#3B8BD4;--Bbg:rgba(59,139,212,.15);--Btxt:#7db8e8;
  --A:#EF9F27;--Abg:rgba(239,159,39,.15);--Atxt:#f5c06a;
  --rad:8px;--radL:12px;
}
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:var(--bg);color:var(--txt);padding:1.5rem;min-height:100vh;}
h1{font-size:17px;font-weight:600;margin-bottom:3px;}
.sub{font-size:12px;color:var(--txt2);margin-bottom:1.4rem;}
.tabs{display:flex;gap:6px;margin-bottom:1rem;flex-wrap:wrap;}
.tab{padding:5px 14px;font-size:12px;border:.5px solid var(--brd2);border-radius:20px;cursor:pointer;background:transparent;color:var(--txt2);transition:all .15s;white-space:nowrap;}
.tab:hover{background:var(--bg2);color:var(--txt);}
.tab.active{background:var(--bg3);color:var(--txt);border-color:rgba(255,255,255,.3);}
.kgrid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:10px;margin-bottom:1.2rem;}
.kpi{background:var(--bg2);border-radius:var(--rad);padding:.8rem 1rem;border:.5px solid var(--brd);}
.kl{font-size:10px;color:var(--txt2);margin-bottom:3px;text-transform:uppercase;letter-spacing:.04em;}
.kv{font-size:18px;font-weight:600;color:var(--txt);line-height:1.2;}
.ks{font-size:11px;color:var(--txt3);margin-top:3px;}
.sec{font-size:10px;font-weight:600;color:var(--txt2);text-transform:uppercase;letter-spacing:.06em;margin:1.2rem 0 .5rem;}
.tbl{width:100%;font-size:12px;border-collapse:collapse;}
.tbl th{font-weight:500;color:var(--txt2);text-align:left;padding:5px 6px 5px 0;border-bottom:.5px solid var(--brd);font-size:10px;text-transform:uppercase;white-space:nowrap;}
.tbl td{padding:6px 6px 6px 0;border-bottom:.5px solid var(--brd);color:var(--txt);vertical-align:middle;}
.tbl tr:last-child td{border-bottom:none;}
.tbl tr.ft td{border-top:1px solid var(--brd2);font-weight:600;border-bottom:none;}
.badge{display:inline-flex;align-items:center;font-size:10px;padding:2px 7px;border-radius:20px;font-weight:600;white-space:nowrap;}
.bG{background:var(--Gbg);color:var(--Gtxt);}
.bR{background:var(--Rbg);color:var(--Rtxt);}
.bB{background:var(--Bbg);color:var(--Btxt);}
.bA{background:var(--Abg);color:var(--Atxt);}
.cw{position:relative;width:100%;}
.ley{display:flex;gap:14px;margin:5px 0 4px;font-size:11px;color:var(--txt2);flex-wrap:wrap;}
.ley span{display:flex;align-items:center;gap:4px;}
.ley i{width:10px;height:10px;border-radius:2px;display:inline-block;}
.nota{background:var(--bg2);border:.5px solid var(--brd);border-radius:var(--rad);padding:.7rem 1rem;font-size:12px;color:var(--txt2);line-height:1.6;margin-bottom:1rem;}
.nota strong{color:var(--txt);}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:14px;}
.bV{border:.5px solid rgba(239,159,39,.25);border-radius:var(--radL);padding:1rem;}
.bN{border:.5px solid rgba(59,139,212,.25);border-radius:var(--radL);padding:1rem;}
.ins{border-left:3px solid var(--B);padding:.7rem 1rem;margin-bottom:10px;border-radius:0 var(--rad) var(--rad) 0;background:var(--bg2);}
.insG{border-left-color:var(--G);}
.insA{border-left-color:var(--A);}
.insR{border-left-color:var(--R);}
.it{font-size:13px;font-weight:600;color:var(--txt);margin-bottom:4px;}
.ic{font-size:12px;color:var(--txt2);line-height:1.65;}
.ic strong{color:var(--txt);}
.dot{width:8px;height:8px;border-radius:50%;display:inline-block;margin-right:5px;flex-shrink:0;vertical-align:middle;}
.num-big{font-size:32px;font-weight:700;color:var(--txt);}
.num-label{font-size:11px;color:var(--txt2);margin-top:2px;}
@media(max-width:600px){.kgrid{grid-template-columns:1fr 1fr;}.g2{grid-template-columns:1fr;}}
</style>
</head>
<body>

<style>
.nl-section{margin-bottom:1.8rem}
.nl-title{font-size:10px;font-weight:700;color:var(--txt2);text-transform:uppercase;letter-spacing:.07em;margin:0 0 .6rem;display:flex;align-items:center;gap:8px}
.nl-title::after{content:'';flex:1;height:.5px;background:var(--brd2)}

/* FÓRMULA PRINCIPAL */
.nl-formula{
  display:flex;align-items:center;gap:0;
  background:var(--bg2);border:.5px solid var(--brd2);
  border-radius:var(--radL);overflow:hidden;margin-bottom:1rem;
}
.nl-f-block{
  flex:1;padding:1rem 1.2rem;text-align:center;
  display:flex;flex-direction:column;align-items:center;justify-content:center;
}
.nl-f-block.nl-f-ventas{background:rgba(29,158,117,.1);border-right:.5px solid rgba(29,158,117,.3)}
.nl-f-block.nl-f-txn{background:rgba(59,139,212,.08);border-right:none}
.nl-f-block.nl-f-ticket{background:rgba(239,159,39,.08)}
.nl-f-op{font-size:22px;font-weight:300;color:var(--txt3);padding:0 .2rem;flex-shrink:0;align-self:center}
.nl-f-label{font-size:9px;font-weight:700;text-transform:uppercase;letter-spacing:.06em;margin-bottom:4px}
.nl-f-val{font-size:28px;font-weight:800;line-height:1}
.nl-f-sub{font-size:11px;margin-top:4px}
.nl-f-ventas .nl-f-label{color:var(--Gtxt)}
.nl-f-ventas .nl-f-val{color:var(--Gtxt)}
.nl-f-ventas .nl-f-sub{color:rgba(79,212,168,.6)}
.nl-f-txn .nl-f-label{color:var(--Btxt)}
.nl-f-txn .nl-f-val{color:var(--Btxt)}
.nl-f-txn .nl-f-sub{color:rgba(125,184,232,.6)}
.nl-f-ticket .nl-f-label{color:var(--Atxt)}
.nl-f-ticket .nl-f-val{color:var(--Atxt)}
.nl-f-ticket .nl-f-sub{color:rgba(245,192,106,.6)}

/* STATUS strip */
.nl-status{display:flex;gap:8px;margin-bottom:1.2rem;flex-wrap:wrap}
.nl-status-item{
  flex:1;min-width:160px;
  background:var(--bg2);border-radius:var(--rad);
  padding:.6rem 1rem;border:.5px solid var(--brd);
  display:flex;align-items:center;gap:10px;
}
.nl-status-icon{font-size:18px;flex-shrink:0}
.nl-status-body{}
.nl-status-lbl{font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em}
.nl-status-val{font-size:13px;font-weight:700;margin-top:1px}
.nl-status-sub{font-size:10px;color:var(--txt3);margin-top:1px}

/* TABLA SEMANAL */
.sw-wrap{overflow-x:auto}
.sw-tbl{width:100%;font-size:12px;border-collapse:collapse;min-width:900px}
.sw-tbl th{font-size:10px;font-weight:600;color:var(--txt2);text-align:left;padding:5px 8px 5px 0;border-bottom:.5px solid var(--brd2);text-transform:uppercase;letter-spacing:.04em;white-space:nowrap}
.sw-tbl td{padding:8px 8px 8px 0;border-bottom:.5px solid var(--brd);vertical-align:top}
.sw-tbl tr:last-child td{border-bottom:none}
.sw-week{font-weight:600;color:var(--txt);font-size:12px;white-space:nowrap}
.sw-sub{font-size:10px;color:var(--txt3);margin-top:2px}
.sw-val{font-weight:600;color:var(--txt);font-size:13px}
.sw-chg{font-size:10px;margin-top:2px}
.sw-up{color:var(--Gtxt)}.sw-dn{color:var(--Rtxt)}.sw-neu{color:var(--txt3)}
.sw-ins{font-size:11px;color:var(--txt2);line-height:1.5;max-width:175px}
.sw-ins strong{color:var(--txt);font-weight:600}
.sw-act{font-size:11px;line-height:1.5;max-width:160px}
.sw-res{font-size:11px;line-height:1.5;max-width:145px;color:var(--txt3)}
.sw-res strong{color:var(--txt);font-weight:600}

/* FOCO */
.nl-foco{background:var(--bg2);border:.5px solid rgba(59,139,212,.35);border-radius:var(--radL);padding:1rem 1.2rem;display:flex;gap:1.2rem;align-items:flex-start;flex-wrap:wrap}
.nl-foco-tag{background:var(--Bbg);color:var(--Btxt);font-size:10px;font-weight:700;padding:2px 10px;border-radius:20px;text-transform:uppercase;letter-spacing:.05em;white-space:nowrap;align-self:flex-start;margin-top:2px}
.nl-foco-body{flex:1;min-width:200px}
.nl-foco-title{font-size:14px;font-weight:700;color:var(--txt);margin-bottom:4px}
.nl-foco-desc{font-size:12px;color:var(--txt2);line-height:1.6}
.nl-foco-desc strong{color:var(--txt)}
.nl-foco-metas{margin-top:.6rem;display:flex;gap:8px;flex-wrap:wrap}
.nl-meta{background:var(--bg3);border:.5px solid var(--brd);border-radius:var(--rad);padding:.4rem .8rem;font-size:11px;color:var(--txt2)}
.nl-meta strong{color:var(--Btxt);font-weight:700}
.nl-meta-open{border-color:rgba(226,75,74,.4)!important;background:rgba(226,75,74,.08)!important}
.nl-meta-open strong{color:var(--Rtxt)!important}

/* BADGES */
.nl-bG{background:var(--Gbg);color:var(--Gtxt)}
.nl-bR{background:var(--Rbg);color:var(--Rtxt)}
.nl-bB{background:var(--Bbg);color:var(--Btxt)}
.nl-bA{background:var(--Abg);color:var(--Atxt)}
.nl-badge{display:inline-flex;align-items:center;font-size:10px;padding:2px 7px;border-radius:20px;font-weight:600;white-space:nowrap}

.nl-disclaimer{font-size:11px;color:var(--txt3);background:var(--bg2);border:.5px solid var(--brd);border-radius:var(--rad);padding:.55rem .9rem;margin-bottom:1rem;line-height:1.6}
.nl-disclaimer strong{color:var(--txt2)}
.nl-divider{height:1px;background:var(--brd2);margin:2rem 0 1.6rem;position:relative}
.nl-divider::before{content:'· REPORTE MENSUAL DETALLADO ·';position:absolute;top:-8px;left:50%;transform:translateX(-50%);background:var(--bg);padding:0 10px;font-size:9px;font-weight:700;color:var(--txt3);letter-spacing:.07em;white-space:nowrap}
@media(max-width:640px){.nl-formula{flex-direction:column}.nl-f-op{transform:rotate(90deg)}.nl-status{flex-direction:column}}
</style>

<div class="nl-section">

  <!-- ENCABEZADO -->
  <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;margin-bottom:1.1rem;">
    <div>
      <div style="font-size:16px;font-weight:700;color:var(--txt);">Libertario Coffee Roasters</div>
      <div style="font-size:12px;color:var(--txt2);margin-top:2px;">Panel de decisión &middot; Semana 30 mar &ndash; 5 abr 2026</div>
    </div>
    <span class="nl-badge nl-bG">Menú nuevo activo</span>
  </div>

  <!-- FÓRMULA CENTRAL -->
  <div class="nl-title">La fórmula del negocio</div>
  <div class="nl-formula">
    <div class="nl-f-block nl-f-ventas">
      <div class="nl-f-label">Ventas netas</div>
      <div class="nl-f-val">₡12.3M</div>
      <div class="nl-f-sub">marzo al 27 &middot; 18 días</div>
    </div>
    <div class="nl-f-op">=</div>
    <div class="nl-f-block nl-f-txn">
      <div class="nl-f-label">Transacciones</div>
      <div class="nl-f-val">994</div>
      <div class="nl-f-sub">órdenes POS &middot; el número más importante</div>
    </div>
    <div class="nl-f-op">&times;</div>
    <div class="nl-f-block nl-f-ticket">
      <div class="nl-f-label">Ticket promedio</div>
      <div class="nl-f-val">₡12,374</div>
      <div class="nl-f-sub">2.7 ítems por orden &middot; ya subió ✔</div>
    </div>
  </div>

  <!-- STATUS: qué está resuelto y qué hay que trabajar -->
  <div class="nl-status">
    <div class="nl-status-item" style="border-color:rgba(29,158,117,.35);background:rgba(29,158,117,.06);">
      <div class="nl-status-icon">&#10003;</div>
      <div class="nl-status-body">
        <div class="nl-status-lbl" style="color:var(--Gtxt)">Ticket &mdash; resuelto</div>
        <div class="nl-status-val" style="color:var(--Gtxt)">₡12,374 promedio</div>
        <div class="nl-status-sub">Subió +23% con el nuevo menú. Mantener.</div>
      </div>
    </div>
    <div class="nl-status-item" style="border-color:rgba(59,139,212,.4);background:rgba(59,139,212,.07);">
      <div class="nl-status-icon">&#8594;</div>
      <div class="nl-status-body">
        <div class="nl-status-lbl" style="color:var(--Btxt)">Transacciones &mdash; el foco ahora</div>
        <div class="nl-status-val" style="color:var(--Btxt)">55 por día promedio</div>
        <div class="nl-status-sub">Más transacciones = más ventas. Acá está la palanca.</div>
      </div>
    </div>
    <div class="nl-status-item" style="border-color:rgba(226,75,74,.3);background:rgba(226,75,74,.05);">
      <div class="nl-status-icon">&#63;</div>
      <div class="nl-status-body">
        <div class="nl-status-lbl" style="color:var(--Rtxt)">Viernes 27 &mdash; investigar</div>
        <div class="nl-status-val" style="color:var(--Rtxt)">30 txn (&minus;41%)</div>
        <div class="nl-status-sub">Causa desconocida. Monitorear viernes 3 abr.</div>
      </div>
    </div>
    <div class="nl-status-item">
      <div class="nl-status-icon">&#8635;</div>
      <div class="nl-status-body">
        <div class="nl-status-lbl">Recurrencia</div>
        <div class="nl-status-val">41.5% retornan</div>
        <div class="nl-status-sub">Más recurrencia = más transacciones. Meta: 45%.</div>
      </div>
    </div>
  </div>

  <!-- NOTA METODOLÓGICA -->
  <div class="nl-disclaimer">
    <strong>Sobre los datos:</strong> Transacciones POS = el dato más confiable. WiFi (Fiweex) = tendencia de tráfico, no conteo exacto &mdash; no todos los clientes se conectan al WiFi. Usalo para ver si el tráfico sube o baja semana a semana.
  </div>

  <!-- TABLA SEMANAL -->
  <div class="nl-title">Semana a Semana &middot; Dato &rarr; Acción &rarr; Resultado</div>
  <div class="sw-wrap">
    <table class="sw-tbl">
      <thead>
        <tr>
          <th>Semana</th>
          <th>Transacciones<br><span style="font-weight:400;color:var(--txt3)">la palanca</span></th>
          <th>Ticket prom.<br><span style="font-weight:400;color:var(--txt3)">₡ neto</span></th>
          <th>Ítems/<br>Ticket</th>
          <th>WiFi<br><span style="font-weight:400;color:var(--txt3)">tendencia</span></th>
          <th>Recurrentes<br><span style="font-weight:400;color:var(--txt3)">Fiweex</span></th>
          <th>Insight</th>
          <th>Acción</th>
          <th style="color:var(--Gtxt)">Resultado<br><span style="font-weight:400;color:var(--txt3)">¿funcionó?</span></th>
        </tr>
      </thead>
      <tbody>

        <!-- SEM 1 -->
        <tr>
          <td>
            <div class="sw-week">Mar 9&ndash;15</div>
            <div class="sw-sub">Menú anterior &middot; 6 días</div>
          </td>
          <td>
            <div class="sw-val">343</div>
            <div class="sw-chg sw-neu">&mdash; base &middot; 57/día</div>
          </td>
          <td>
            <div class="sw-val">₡7,940</div>
            <div class="sw-chg sw-neu">&mdash; base</div>
          </td>
          <td>
            <div class="sw-val">2.6</div>
            <div class="sw-chg sw-neu">&mdash; base</div>
          </td>
          <td>
            <div class="sw-val">~135</div>
            <div class="sw-chg sw-neu">estimado</div>
          </td>
          <td>
            <div class="sw-val">~35%</div>
            <div class="sw-chg sw-neu">estimado</div>
          </td>
          <td class="sw-ins">
            <strong>Línea de base.</strong> Sáb+Dom = 55% de ventas (189 txn). Días entre semana más débiles.
          </td>
          <td class="sw-act">
            <span class="nl-badge nl-bB" style="margin-bottom:4px;">Completada</span><br>
            Lanzar nuevo menú el mié 18 para subir ticket.
          </td>
          <td class="sw-res">
            <span class="nl-badge nl-bG" style="margin-bottom:4px;">Funcionó</span><br>
            <strong>Ticket +23%</strong> la semana siguiente. Ítems/ticket subió a 2.8.
          </td>
        </tr>

        <!-- SEM 2 -->
        <tr>
          <td>
            <div class="sw-week">Mar 16&ndash;22</div>
            <div class="sw-sub">Sem 1 menú nuevo &middot; 7 días</div>
          </td>
          <td>
            <div class="sw-val">367</div>
            <div class="sw-chg sw-up">&#8593; +7% vs sem ant. &middot; 52/día</div>
          </td>
          <td>
            <div class="sw-val">₡9,748</div>
            <div class="sw-chg sw-up">&#8593; +23% vs sem ant.</div>
          </td>
          <td>
            <div class="sw-val">2.8</div>
            <div class="sw-chg sw-up">&#8593; +9% vs sem ant.</div>
          </td>
          <td>
            <div class="sw-val">154</div>
            <div class="sw-chg sw-up">&#8593; +14%</div>
          </td>
          <td>
            <div class="sw-val">~35%</div>
            <div class="sw-chg sw-neu">&asymp; igual</div>
          </td>
          <td class="sw-ins">
            <strong>El menú funcionó.</strong> Ticket subió pero las transacciones entre semana aún débiles. Dom 22: 83 txn, mejor día del mes.
          </td>
          <td class="sw-act">
            <span class="nl-badge nl-bA" style="margin-bottom:4px;">En tienda</span><br>
            Sugerencias y combos en mostrador. Meta ítems/ticket: 3.0.
          </td>
          <td class="sw-res">
            <span class="nl-badge" style="background:rgba(255,255,255,.08);color:var(--txt3);margin-bottom:4px;">Pendiente</span><br>
            ¿Llegaron a 3.0 ítems/ticket? Verificar al cerrar sem 3 con POS.
          </td>
        </tr>

        <!-- SEM 3 -->
        <tr style="background:rgba(255,255,255,.018);">
          <td>
            <div class="sw-week">Mar 23&ndash;29</div>
            <div class="sw-sub">Sem 2 menú nuevo &middot; 5 días POS*</div>
          </td>
          <td>
            <div class="sw-val">235 *</div>
            <div class="sw-chg sw-neu">sin Sáb/Dom POS &middot; 47/día</div>
          </td>
          <td>
            <div class="sw-val">₡8,932</div>
            <div class="sw-chg sw-dn">&#8595; &minus;8% (parcial)</div>
          </td>
          <td>
            <div class="sw-val">2.8</div>
            <div class="sw-chg sw-neu">&rarr; igual</div>
          </td>
          <td>
            <div class="sw-val">140</div>
            <div class="sw-chg sw-dn">&#8595; &minus;9%</div>
          </td>
          <td>
            <div class="sw-val">41.5%</div>
            <div class="sw-chg sw-up">&#8593; +6.5pp &mdash; buena señal</div>
          </td>
          <td class="sw-ins">
            <strong>Vie 27 cayó fuerte:</strong> 30 txn y 8 WiFi (&minus;41% vs Vie 20). No es un insight &mdash; es una pregunta sin respuesta todavía.
          </td>
          <td class="sw-act">
            <span class="nl-badge nl-bR" style="margin-bottom:4px;">Investigar</span><br>
            ¿Menos gente en la zona? ¿Operación? ¿Staff? Hablar con equipo.
          </td>
          <td class="sw-res">
            <span class="nl-badge nl-bR" style="margin-bottom:4px;">Abierto</span><br>
            Causa sin confirmar. Observar <strong>viernes 3 abr</strong> para comparar.
          </td>
        </tr>

        <!-- SEM 4: HOY -->
        <tr style="background:rgba(59,139,212,.05);outline:.5px solid rgba(59,139,212,.25);outline-offset:-1px;">
          <td>
            <div class="sw-week" style="color:var(--Btxt);">Mar 30 &ndash; Abr 5</div>
            <div class="sw-sub" style="color:var(--Btxt);opacity:.7;">HOY &middot; En curso (día 1)</div>
          </td>
          <td>
            <div class="sw-val">&mdash;</div>
            <div class="sw-chg sw-neu">pendiente POS hoy</div>
          </td>
          <td>
            <div class="sw-val">&mdash;</div>
            <div class="sw-chg sw-neu">pendiente</div>
          </td>
          <td>
            <div class="sw-val">&mdash;</div>
            <div class="sw-chg sw-neu">pendiente</div>
          </td>
          <td>
            <div class="sw-val">31</div>
            <div class="sw-chg sw-up">&#8593; +24% vs lun 23</div>
          </td>
          <td>
            <div class="sw-val">38.7%</div>
            <div class="sw-chg sw-neu">12 de 31 ya retornaron</div>
          </td>
          <td class="sw-ins">
            <strong>Lunes arrancó bien.</strong> 31 WiFi, mejor que lun 23. La recurrencia sigue activa. Resta ver txn del POS.
          </td>
          <td class="sw-act">
            <span class="nl-badge nl-bG" style="margin-bottom:4px;">Ejecutar</span><br>
            1. Equipo invita a volver en caja.<br>
            2. Fidelidad activa.<br>
            3. Monitorear vie 3 abr.
          </td>
          <td class="sw-res">
            <span class="nl-badge" style="background:rgba(255,255,255,.08);color:var(--txt3);margin-bottom:4px;">Sem que viene</span><br>
            Medir: ¿Txn subió? ¿Recurrentes llegaron al 45%? ¿Qué pasó el viernes?
          </td>
        </tr>

      </tbody>
      <tfoot>
        <tr>
          <td colspan="9" style="padding-top:8px;font-size:10px;color:var(--txt3);border-top:.5px solid var(--brd2);">
            * Sem 3 sin datos POS de Sáb 28 y Dom 29 &rarr; ticket y txn subestimados. WiFi = tendencia de tráfico, no conteo exacto de personas.
          </td>
        </tr>
      </tfoot>
    </table>
  </div>

  <!-- FOCO DE LA SEMANA -->
  <div class="nl-title" style="margin-top:1.4rem;">Foco esta semana &middot; 30 Mar &ndash; 5 Abr</div>
  <div class="nl-foco">
    <div class="nl-foco-tag">Transacciones</div>
    <div class="nl-foco-body">
      <div class="nl-foco-title">Subir la cantidad de órdenes por día</div>
      <div class="nl-foco-desc">
        El ticket ya subió &mdash; esa parte está hecha. La palanca ahora es <strong>cuántas veces compra la gente</strong>.
        Más recurrencia = más transacciones. Más transacciones = más ventas. Así de simple.
        <br><br>
        <strong>En práctica esta semana:</strong> el equipo invita a volver en cada caja, activás el programa de fidelidad,
        y el viernes 3 de abril lo mirás con lupa para entender si el problema del 27 se repite o fue puntual.
      </div>
      <div class="nl-foco-metas">
        <div class="nl-meta">Meta txn/día: <strong>&ge; 60</strong></div>
        <div class="nl-meta">Meta recurrentes: <strong>&ge; 45%</strong></div>
        <div class="nl-meta">Mantener ticket: <strong>&ge; ₡9,500</strong></div>
        <div class="nl-meta nl-meta-open">Abierto: <strong>causa Vie 27</strong></div>
      </div>
    </div>
  </div>

  <!-- CALENDARIO -->
  <div class="nl-title" style="margin-top:1.4rem;">Un foco por semana &middot; Abril 2026</div>
  <div style="display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:8px;">
    <div style="background:rgba(59,139,212,.12);border:.5px solid rgba(59,139,212,.35);border-radius:var(--rad);padding:.75rem 1rem;">
      <div style="font-size:10px;font-weight:700;color:var(--Btxt);text-transform:uppercase;letter-spacing:.04em;margin-bottom:4px;">Sem 1 &middot; 30 Mar &larr; HOY</div>
      <div style="font-size:13px;font-weight:700;color:var(--txt);">Transacciones</div>
      <div style="font-size:11px;color:var(--txt2);margin-top:4px;">Fidelidad en tienda. Recurrencia &rarr; más órdenes.</div>
    </div>
    <div style="background:var(--bg2);border:.5px solid var(--brd);border-radius:var(--rad);padding:.75rem 1rem;">
      <div style="font-size:10px;font-weight:700;color:var(--txt3);text-transform:uppercase;letter-spacing:.04em;margin-bottom:4px;">Sem 2 &middot; 6 Abr</div>
      <div style="font-size:13px;font-weight:700;color:var(--txt);">Ítems/Ticket</div>
      <div style="font-size:11px;color:var(--txt2);margin-top:4px;">Combos y sugerencias. Meta: 3.0 ítems.</div>
    </div>
    <div style="background:var(--bg2);border:.5px solid var(--brd);border-radius:var(--rad);padding:.75rem 1rem;">
      <div style="font-size:10px;font-weight:700;color:var(--txt3);text-transform:uppercase;letter-spacing:.04em;margin-bottom:4px;">Sem 3 &middot; 13 Abr</div>
      <div style="font-size:13px;font-weight:700;color:var(--txt);">Días entre semana</div>
      <div style="font-size:11px;color:var(--txt2);margin-top:4px;">Subir lunes&ndash;jueves. Hoy son los más débiles.</div>
    </div>
    <div style="background:var(--bg2);border:.5px solid var(--brd);border-radius:var(--rad);padding:.75rem 1rem;">
      <div style="font-size:10px;font-weight:700;color:var(--txt3);text-transform:uppercase;letter-spacing:.04em;margin-bottom:4px;">Sem 4 &middot; 20 Abr</div>
      <div style="font-size:13px;font-weight:700;color:var(--txt);">Revisión</div>
      <div style="font-size:11px;color:var(--txt2);margin-top:4px;">¿Qué movi&oacute; la aguja? Ajustar para mayo.</div>
    </div>
  </div>

</div>
<div class="nl-divider"></div>
<h1>Libertario Coffee Roasters</h1>
<p class="sub">Análisis operativo · Marzo 2026 · Nuevo menú lanzado el miércoles 18 de marzo</p>
<div class="kgrid" id="kg"></div>

<!-- PRESUPUESTO -->
<div id="bloque-ppto" style="background:var(--bg2);border:.5px solid var(--brd);border-radius:var(--radL);padding:1.1rem 1.2rem;margin-bottom:1.2rem;"></div>
<div class="tabs">
  <button class="tab active" onclick="sw('tendencia',this)">Tendencia</button>
  <button class="tab" onclick="sw('categorias',this)">Categorías</button>
  <button class="tab" onclick="sw('comparativa',this)">Menú viejo vs nuevo</button>
  <button class="tab" onclick="sw('adopcion',this)">Adopción</button>
  <button class="tab" onclick="sw('productos',this)">Productos nuevos</button>
  <button class="tab" onclick="sw('semanas',this)">Evolución menú nuevo</button>
  <button class="tab" onclick="sw('tipodias',this)">Por tipo de día</button>
  <button class="tab" onclick="sw('conclusiones',this)">Conclusiones</button>
</div>
<div id="panel-tendencia"></div>
<div id="panel-categorias"  style="display:none;"></div>
<div id="panel-comparativa" style="display:none;"></div>
<div id="panel-adopcion"    style="display:none;"></div>
<div id="panel-productos"   style="display:none;"></div>
<div id="panel-semanas"     style="display:none;"></div>
<div id="panel-tipodias"   style="display:none;"></div>
<div id="panel-conclusiones"style="display:none;"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<script>
const gc='rgba(255,255,255,.06)',tc='#a0a09a';
const fmt=n=>Math.round(n).toLocaleString('es-CR');
const fk=n=>'₡'+fmt(Math.round(n/1000))+'k';

// ── DATOS AUDITADOS ──────────────────────────────────────────────────────────
// bruto = Session Total (con impuestos)
// neto  = Tax excluded base (lo tuyo)
// Nota: algunos días tienen ítems "Not Categorized" (Cajas Mágicas) que van en neto pero no en bev/coc/fil
const DIAS=[
  {d:'Lun 9', dow:'Lun',v:true, txn:41,bruto:364320, neto:301807,items:96, bevU:56,cocU:39,filU:1, bevB:176100,cocB:123919,filB:1789},
  {d:'Mar 10',dow:'Mar',v:true, txn:24,bruto:170700, neto:139644,items:56, bevU:38,cocU:17,filU:1, bevB:88993, cocB:48862, filB:1789},
  {d:'Jue 12',dow:'Jue',v:true, txn:39,bruto:382600, neto:319576,items:88, bevU:51,cocU:27,filU:10,bevB:189738,cocB:96748, filB:33090},
  {d:'Vie 13',dow:'Vie',v:true, txn:50,bruto:490360, neto:403084,items:126,bevU:69,cocU:49,filU:8, bevB:191409,cocB:187366,filB:24309},
  {d:'Sáb 14',dow:'Sáb',v:true, txn:98,bruto:982035, neto:808007,items:264,bevU:131,cocU:116,filU:17,bevB:370418,cocB:394012,filB:43577},
  {d:'Dom 15',dow:'Dom',v:true, txn:91,bruto:913222, neto:751618,items:249,bevU:124,cocU:111,filU:14,bevB:346724,cocB:363268,filB:41626},
  {d:'Lun 16',dow:'Lun',v:true, txn:68,bruto:726975, neto:599181,items:185,bevU:109,cocU:66,filU:9, bevB:330990,cocB:238760,filB:29460},
  {d:'Mar 17',dow:'Mar',v:true, txn:41,bruto:474200, neto:395169,items:115,bevU:65,cocU:38,filU:7, bevB:230321,cocB:142764,filB:15447},
  {d:'Mié 18',dow:'Mié',v:false,txn:35,bruto:527600, neto:439534,items:112,bevU:54,cocU:53,filU:5, bevB:220603,cocB:200720,filB:18211,nv:32},
  {d:'Jue 19',dow:'Jue',v:false,txn:29,bruto:331404, neto:271700,items:92, bevU:50,cocU:38,filU:4, bevB:133039,cocB:128255,filB:10407,nv:23},
  {d:'Vie 20',dow:'Vie',v:false,txn:51,bruto:521451, neto:431722,items:124,bevU:68,cocU:51,filU:5, bevB:232005,cocB:187034,filB:12683,nv:27},
  {d:'Sáb 21',dow:'Sáb',v:false,txn:60,bruto:703343, neto:577094,items:174,bevU:87,cocU:77,filU:9, bevB:249730,cocB:296687,filB:29350,nv:47},
  {d:'Dom 22',dow:'Dom',v:false,txn:83,bruto:1038342,neto:863329,items:238,bevU:141,cocU:88,filU:9, bevB:504419,cocB:333650,filB:25260,nv:39},
  {d:'Lun 23',dow:'Lun',v:false,txn:55,bruto:705330, neto:585163,items:167,bevU:102,cocU:60,filU:2, bevB:334614,cocB:238374,filB:5447,nv:28},
  {d:'Mar 24',dow:'Mar',v:false,txn:60,bruto:613883, neto:502289,items:161,bevU:84,cocU:71,filU:6, bevB:215597,cocB:269457,filB:17235,nv:25},
  {d:'Mié 25',dow:'Mié',v:false,txn:53,bruto:593399, neto:488529,items:144,bevU:70,cocU:65,filU:8, bevB:213116,cocB:249207,filB:24878,nv:35},
  {d:'Jue 26', dow:'Jue',v:false,txn:37,bruto:381332, neto:313296,items:95, bevU:45,cocU:39,filU:11,bevB:139684,cocB:140685,filB:32927,nv:22},
  {d:'Vie 27', dow:'Vie',v:false,txn:30,bruto:373217, neto:310848,items:91, bevU:53,cocU:35,filU:3, bevB:181695,cocB:123056,filB:6097, nv:25},
];

// Productos nuevos con ventas reales (7 días menú nuevo)
const PRODS=[
  {n:'Tostadas Francesas',           c:'Cocina', q:[1,2,2,10,2,1,5,3,3,2]},
  {n:'Cacerola Huevos Cremosos',     c:'Cocina', q:[4,1,3,4,2,5,2,2,5,0]},
  {n:'Cacerola Ranchera',            c:'Cocina', q:[6,1,2,2,3,2,6,1,1,2]},
  {n:'Waffle de Frutas',             c:'Cocina', q:[0,1,1,2,3,4,1,0,0,0]},
  {n:'Waffle de Chocolate',          c:'Cocina', q:[1,2,2,4,3,2,1,1,0,0]},
  {n:'Cacerola Libertario',          c:'Cocina', q:[3,1,2,3,0,1,5,3,3,1]},
  {n:'Rollo de Canela',              c:'Cocina', q:[0,1,0,3,2,4,1,1,0,1]},
  {n:'Mango Matcha',                 c:'Bebidas',q:[1,0,1,1,5,3,2,0,0,1]},
  {n:'Croissant Crumble Manzana',    c:'Cocina', q:[4,0,1,0,4,0,2,0,0,0]},
  {n:'Almojábana',                   c:'Cocina', q:[2,3,6,1,0,0,2,3,1,2]},
  {n:'Croissant de Crema',           c:'Cocina', q:[0,2,0,4,1,3,0,2,0,1]},
  {n:'Croissant de Desayuno',        c:'Cocina', q:[0,1,2,3,1,0,1,0,1,0]},
  {n:'Sandwich Pollo al Pesto',      c:'Cocina', q:[0,0,1,3,3,2,2,4,0,1]},
  {n:'Sandwich Grill Cheese',        c:'Cocina', q:[0,1,0,2,2,2,2,3,1,3]},
  {n:'Chia Pudding',                 c:'Cocina', q:[0,1,1,2,0,0,4,0,0,0]},
  {n:'Bowl de Falafel',              c:'Cocina', q:[3,0,0,0,2,1,1,1,1,1]},
  {n:'Cacerola Benedictinos',        c:'Cocina', q:[4,2,1,1,2,0,4,1,2,1]},
  {n:'Bowl de Avena',                c:'Cocina', q:[2,0,1,0,2,2,2,0,0,1]},
  {n:'Profiterol',                   c:'Cocina', q:[0,3,0,1,1,0,0,0,1,2]},
  {n:'Queque de Amapola',            c:'Cocina', q:[0,0,0,0,1,1,1,0,0,0]},
  {n:'Bowl Almuerzo',                c:'Cocina', q:[1,0,0,1,0,0,1,2,0,1]},
  {n:'Crocante Alemán',              c:'Cocina', q:[0,1,1,0,0,0,0,1,0,0]},
  {n:'Amber Brew',                   c:'Bebidas',q:[2,1,1,0,0,2,1,0,1,2]},
  {n:'Soda Frutos Amarillos',        c:'Bebidas',q:[0,0,2,1,0,0,3,0,0,0]},
  {n:'Cheesecake Libertario',        c:'Cocina', q:[0,1,0,0,1,0,1,1,0,1]},
  {n:'Sandwich Jamón Serrano',       c:'Cocina', q:[0,0,1,0,0,2,2,1,0,0]},
].map(p=>({...p,total:p.q.reduce((a,b)=>a+b,0)})).sort((a,b)=>b.total-a.total);

const VIE=DIAS.filter(d=>d.v), NUE=DIAS.filter(d=>!d.v);

// ── PRESUPUESTO DINÁMICO ──────────────────────────────────────────────────────
(function buildPpto(){
  const PPTO=18000000;
  const acum=DIAS.reduce((a,d)=>a+d.bruto,0);
  const netoAcum=DIAS.reduce((a,d)=>a+d.neto,0);
  const pctAcum=(acum/PPTO*100).toFixed(1);

  // Medianas por tipo de día
  const mediana=arr=>{const s=[...arr].sort((a,b)=>a-b);const m=s.length;return m%2===0?(s[m/2-1]+s[m/2])/2:s[Math.floor(m/2)];};
  const EDS=['Lun','Mar','Mié','Jue','Vie'];
  const medEnt=mediana(DIAS.filter(d=>EDS.includes(d.dow)).map(d=>d.bruto));
  const medSab=mediana(DIAS.filter(d=>d.dow==='Sáb').map(d=>d.bruto));
  const medDom=mediana(DIAS.filter(d=>d.dow==='Dom').map(d=>d.bruto));

  // Días restantes: Sáb 28, Dom 29, Lun 30, Mar 31
  const restantes=[
    {d:'Sáb 28',med:medSab, tipo:'Sábado'},
    {d:'Dom 29',med:medDom, tipo:'Domingo'},
    {d:'Lun 30',med:medEnt, tipo:'Entre semana'},
    {d:'Mar 31',med:medEnt, tipo:'Entre semana'},
  ];
  const proyRest=restantes.reduce((a,r)=>a+r.med,0);
  const proyTotal=acum+proyRest;
  const pctProy=(proyTotal/PPTO*100).toFixed(1);
  const falta=PPTO-acum;
  const esFav=proyTotal>=PPTO;
  const projColor=esFav?'var(--Gtxt)':'var(--Atxt)';
  const projBg=esFav?'var(--Gbg)':'var(--Abg)';

  document.getElementById('bloque-ppto').innerHTML=`
    <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:12px;margin-bottom:.9rem;">
      <div>
        <div style="font-size:10px;font-weight:600;color:var(--txt2);text-transform:uppercase;letter-spacing:.06em;margin-bottom:3px;">Presupuesto marzo 2026</div>
        <div style="font-size:13px;color:var(--txt2);">${DIAS.length} días registrados de 31 · 1 día off (Mar 11)</div>
      </div>
      <div style="text-align:right;">
        <div style="font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em;">Proyección basada en medianas reales</div>
        <div style="font-size:20px;font-weight:700;color:${projColor};">₡${fmt(proyTotal)} <span style="font-size:12px;background:${projBg};color:${projColor};padding:2px 8px;border-radius:20px;font-weight:600;">${pctProy}% del ppto</span></div>
      </div>
    </div>

    <div style="display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:10px;margin-bottom:1rem;">
      <div style="background:var(--bg3);border-radius:var(--rad);padding:.7rem .9rem;">
        <div style="font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em;margin-bottom:3px;">Bruto acumulado</div>
        <div style="font-size:17px;font-weight:700;color:var(--txt);">₡${fmt(acum)}</div>
        <div style="font-size:11px;color:var(--txt3);margin-top:2px;">${pctAcum}% del presupuesto</div>
      </div>
      <div style="background:var(--bg3);border-radius:var(--rad);padding:.7rem .9rem;">
        <div style="font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em;margin-bottom:3px;">Neto acumulado</div>
        <div style="font-size:17px;font-weight:700;color:var(--txt);">₡${fmt(netoAcum)}</div>
        <div style="font-size:11px;color:var(--txt3);margin-top:2px;">lo que es del negocio</div>
      </div>
      <div style="background:var(--bg3);border-radius:var(--rad);padding:.7rem .9rem;">
        <div style="font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em;margin-bottom:3px;">Falta para el ppto</div>
        <div style="font-size:17px;font-weight:700;color:var(--Atxt);">₡${fmt(falta)}</div>
        <div style="font-size:11px;color:var(--txt3);margin-top:2px;">en ${restantes.length} días restantes</div>
      </div>
      <div style="background:var(--bg3);border-radius:var(--rad);padding:.7rem .9rem;">
        <div style="font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em;margin-bottom:6px;">Meta diaria · operaciones</div>
        <div style="font-size:20px;font-weight:700;color:var(--txt);">₡580,645<span style="font-size:11px;font-weight:400;color:var(--txt2);margin-left:4px;">/ día</span></div>
        <div style="height:.5px;background:var(--brd);margin:6px 0;"></div>
        <div style="font-size:11px;color:var(--txt2);margin-bottom:3px;">Días que la cumplieron</div>
        <div style="font-size:14px;font-weight:700;">
          <span style="color:var(--Gtxt);">${DIAS.filter(d=>d.bruto>=580645).length}</span>
          <span style="font-size:11px;font-weight:400;color:var(--txt3);"> de ${DIAS.length} días registrados</span>
        </div>
        <div style="font-size:10px;color:var(--txt3);margin-top:3px;">4 días restantes · expectativa: ₡${fmt(580645*4)}</div>
      </div>
    </div>

    <div style="margin-bottom:6px;display:flex;justify-content:space-between;align-items:center;">
      <span style="font-size:11px;color:var(--txt2);">₡0</span>
      <span style="font-size:11px;font-weight:600;color:var(--txt);">₡${fmt(acum)} <span style="color:var(--txt2);font-weight:400;">acumulado de</span> ₡${fmt(PPTO)}</span>
      <span style="font-size:11px;color:var(--txt2);">₡${fmt(PPTO)}</span>
    </div>
    <div style="background:rgba(255,255,255,.08);border-radius:6px;height:10px;overflow:hidden;position:relative;">
      <div style="height:10px;border-radius:6px;width:${pctAcum}%;background:linear-gradient(90deg,#1D9E75,#3B8BD4);"></div>
    </div>
    <div style="display:flex;justify-content:space-between;margin-top:5px;">
      <span style="font-size:11px;color:var(--Btxt);font-weight:600;">${pctAcum}% completado</span>
      <span style="font-size:11px;color:var(--txt2);">Proyección con medianas reales: <strong style="color:${projColor};">₡${fmt(proyTotal)}</strong> — ${esFav?'alcanza el presupuesto ✓':'por debajo del presupuesto'}</span>
    </div>`;
})();
const vB=VIE.reduce((a,d)=>a+d.bruto,0), nB=NUE.reduce((a,d)=>a+d.bruto,0);
const vN=VIE.reduce((a,d)=>a+d.neto,0),  nN=NUE.reduce((a,d)=>a+d.neto,0);
const vT=VIE.reduce((a,d)=>a+d.txn,0),   nT=NUE.reduce((a,d)=>a+d.txn,0);
const vTkt=vB/vT, nTkt=nB/nT;
const tktD=((nTkt-vTkt)/vTkt*100).toFixed(1);
const vPD=vB/VIE.length, nPD=nB/NUE.length;
const pdD=((nPD-vPD)/vPD*100).toFixed(1);

// KPIs globales
document.getElementById('kg').innerHTML=[
  {l:'Ticket bruto — menú viejo',   v:'₡'+fmt(vTkt), s:'Promedio por transacción · 8 días'},
  {l:'Ticket bruto — menú nuevo',   v:'₡'+fmt(nTkt), s:(tktD>0?'+':'')+tktD+'% vs menú viejo', badge:'bG', bt:'+'+tktD+'%'},
  {l:'Bruto promedio por día — viejo', v:'₡'+fmt(vPD), s:'Lo que entró a caja en promedio cada día'},
  {l:'Bruto promedio por día — nuevo', v:'₡'+fmt(nPD), s:(pdD>0?'+':'')+pdD+'% vs menú viejo', badge:'bG', bt:'+'+pdD+'%'},
].map(k=>`<div class="kpi"><div class="kl">${k.l}</div><div class="kv">${k.v} ${k.badge?`<span class="badge ${k.badge}">${k.bt}</span>`:''}</div><div class="ks">${k.s}</div></div>`).join('');

// ── TENDENCIA ────────────────────────────────────────────────────────────────
function buildTendencia(){
  const el=document.getElementById('panel-tendencia');
  el.innerHTML=`
    <div class="nota">
      <strong>Bruto</strong> = todo lo que entró a caja ese día (incluye impuestos) &nbsp;·&nbsp;
      <strong>Neto</strong> = lo que es del negocio (sin impuestos) &nbsp;·&nbsp;
      Barras opacas = menú viejo &nbsp;·&nbsp; Barras sólidas = menú nuevo
    </div>
    <div class="ley">
      <span><i style="background:rgba(59,139,212,.35)"></i>Bruto — menú viejo</span>
      <span><i style="background:#3B8BD4"></i>Bruto — menú nuevo</span>
      <span><i style="background:rgba(29,158,117,.3)"></i>Neto — menú viejo</span>
      <span><i style="background:#1D9E75"></i>Neto — menú nuevo</span>
    </div>
    <div class="cw" style="height:240px;"><canvas id="c-bn"></canvas></div>
    <div class="sec" style="margin-top:1rem;">Ticket bruto por transacción · cuánto gastó cada cliente en promedio</div>
    <div class="ley">
      <span><i style="background:rgba(239,159,39,.8)"></i>Menú viejo</span>
      <span><i style="background:#3B8BD4"></i>Menú nuevo</span>
      <span><i style="background:rgba(255,255,255,.2)"></i>Promedio menú viejo</span>
    </div>
    <div class="cw" style="height:190px;"><canvas id="c-tkt"></canvas></div>
    <div class="sec" style="margin-top:1.2rem;">Detalle día a día</div>
    <table class="tbl">
      <tr>
        <th>Día</th><th>Menú</th>
        <th style="text-align:right">Bruto (entra a caja)</th>
        <th style="text-align:right">Neto (del negocio)</th>
        <th style="text-align:right">Transacciones</th>
        <th style="text-align:right">Ticket bruto/cliente</th>
      </tr>
      ${DIAS.map(d=>`<tr>
        <td style="font-weight:600;">${d.d}</td>
        <td>${d.v?'<span class="badge bA">Viejo</span>':'<span class="badge bB">Nuevo</span>'}</td>
        <td style="text-align:right;font-weight:600;">₡${fmt(d.bruto)}</td>
        <td style="text-align:right;">₡${fmt(d.neto)}</td>
        <td style="text-align:right;">${d.txn}</td>
        <td style="text-align:right;">₡${fmt(d.bruto/d.txn)}</td>
      </tr>`).join('')}
    </table>`;

  new Chart(document.getElementById('c-bn'),{type:'bar',data:{labels:DIAS.map(d=>d.d),datasets:[
    {label:'Bruto',data:DIAS.map(d=>d.bruto),backgroundColor:DIAS.map(d=>d.v?'rgba(59,139,212,.35)':'#3B8BD4'),borderRadius:4},
    {label:'Neto', data:DIAS.map(d=>d.neto), backgroundColor:DIAS.map(d=>d.v?'rgba(29,158,117,.3)':'#1D9E75'),borderRadius:4},
  ]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{mode:'index',intersect:false,callbacks:{label:c=>c.dataset.label+': ₡'+fmt(c.raw)}}},scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:10}}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});

  new Chart(document.getElementById('c-tkt'),{type:'line',data:{labels:DIAS.map(d=>d.d),datasets:[
    {label:'Menú viejo',data:[...VIE.map(d=>Math.round(d.bruto/d.txn)),...new Array(NUE.length).fill(null)],borderColor:'rgba(239,159,39,.85)',pointBackgroundColor:'rgba(239,159,39,.85)',pointRadius:5,borderWidth:2,tension:.3,fill:false},
    {label:'Menú nuevo',data:[...new Array(VIE.length).fill(null),...NUE.map(d=>Math.round(d.bruto/d.txn))],borderColor:'#3B8BD4',pointBackgroundColor:'#3B8BD4',pointRadius:5,borderWidth:2,tension:.3,fill:false},
    {label:'Prom. viejo',data:DIAS.map(()=>Math.round(vTkt)),borderColor:'rgba(255,255,255,.15)',borderDash:[5,5],pointRadius:0,borderWidth:1.5,fill:false},
  ]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{mode:'index',intersect:false,callbacks:{label:c=>c.dataset.label+': ₡'+fmt(c.raw)}}},scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:10}}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});
}

// ── CATEGORÍAS ───────────────────────────────────────────────────────────────
function buildCategorias(){
  const el=document.getElementById('panel-categorias');
  const vbev=VIE.reduce((a,d)=>a+d.bevB,0),vcoc=VIE.reduce((a,d)=>a+d.cocB,0),vfil=VIE.reduce((a,d)=>a+d.filB,0);
  const nbev=NUE.reduce((a,d)=>a+d.bevB,0),ncoc=NUE.reduce((a,d)=>a+d.cocB,0),nfil=NUE.reduce((a,d)=>a+d.filB,0);
  const vT2=vbev+vcoc+vfil, nT2=nbev+ncoc+nfil;
  const chg=(a,b)=>{const p=((b-a)/a*100).toFixed(0);return `<span class="badge ${b>a?'bG':'bR'}">${p>0?'+':''}${p}%</span>`;};
  const totB=vbev+nbev,totC=vcoc+ncoc,totF=vfil+nfil,gran=totB+totC+totF;

  el.innerHTML=`
    <div class="nota">Bebidas incluye todas las bebidas calientes, frías y especiales. Cocina incluye todos los platos, postres y snacks. Filtrado/Retail incluye filtrados preparados y bolsas de café para llevar.</div>
    <div class="g2" style="margin-bottom:1.2rem;">
      <div>
        <div class="sec" style="margin-top:0">Mix de ingresos — 18 días totales</div>
        <div class="cw" style="height:200px;"><canvas id="c-donut"></canvas></div>
      </div>
      <div>
        <div class="sec" style="margin-top:0">Ítems vendidos por categoría — día a día</div>
        <div class="cw" style="height:200px;"><canvas id="c-cat"></canvas></div>
      </div>
    </div>

    <div class="sec">Menú viejo · 9–17 Mar · 8 días (Mar 11 = día de capacitación)</div>
    <table class="tbl" style="margin-bottom:1.4rem;">
      <tr><th>Categoría</th>${VIE.map(d=>`<th style="text-align:right;font-size:9px;">${d.d}</th>`).join('')}<th style="text-align:right">Total uds</th><th style="text-align:right">Bruto total</th><th style="text-align:right">% del período</th></tr>
      ${[{l:'Bebidas',c:'#3B8BD4',u:VIE.map(d=>d.bevU),b:VIE.map(d=>d.bevB),tU:VIE.reduce((a,d)=>a+d.bevU,0),tB:vbev},
         {l:'Cocina', c:'#1D9E75',u:VIE.map(d=>d.cocU),b:VIE.map(d=>d.cocB),tU:VIE.reduce((a,d)=>a+d.cocU,0),tB:vcoc},
         {l:'Filtrado/Retail',c:'#EF9F27',u:VIE.map(d=>d.filU),b:VIE.map(d=>d.filB),tU:VIE.reduce((a,d)=>a+d.filU,0),tB:vfil},
      ].map(r=>`<tr>
        <td><span class="dot" style="background:${r.c}"></span><strong>${r.l}</strong></td>
        ${r.u.map((u,i)=>`<td style="text-align:right"><div style="font-weight:500;">${u}</div><div style="font-size:10px;color:var(--txt2);">${fk(r.b[i])}</div></td>`).join('')}
        <td style="text-align:right;font-weight:600;">${r.tU}</td>
        <td style="text-align:right;font-weight:600;">₡${fmt(r.tB)}</td>
        <td style="text-align:right;">${(r.tB/vT2*100).toFixed(1)}%</td>
      </tr>`).join('')}
      <tr class="ft"><td>Total</td>${VIE.map(d=>`<td style="text-align:right"><div>${d.items}</div><div style="font-size:10px;color:var(--txt2);">${fk(d.bruto)}</div></td>`).join('')}<td style="text-align:right">${VIE.reduce((a,d)=>a+d.items,0)}</td><td style="text-align:right">₡${fmt(vT2)}</td><td style="text-align:right">100%</td></tr>
    </table>

    <div class="sec">Menú nuevo · 18–27 Mar · 10 días</div>
    <table class="tbl" style="margin-bottom:1.4rem;">
      <tr><th>Categoría</th>${NUE.map(d=>`<th style="text-align:right;font-size:9px;">${d.d}</th>`).join('')}<th style="text-align:right">Total uds</th><th style="text-align:right">Bruto total</th><th style="text-align:right">% del período</th></tr>
      ${[{l:'Bebidas',c:'#3B8BD4',u:NUE.map(d=>d.bevU),b:NUE.map(d=>d.bevB),tU:NUE.reduce((a,d)=>a+d.bevU,0),tB:nbev},
         {l:'Cocina', c:'#1D9E75',u:NUE.map(d=>d.cocU),b:NUE.map(d=>d.cocB),tU:NUE.reduce((a,d)=>a+d.cocU,0),tB:ncoc},
         {l:'Filtrado/Retail',c:'#EF9F27',u:NUE.map(d=>d.filU),b:NUE.map(d=>d.filB),tU:NUE.reduce((a,d)=>a+d.filU,0),tB:nfil},
      ].map(r=>`<tr>
        <td><span class="dot" style="background:${r.c}"></span><strong>${r.l}</strong></td>
        ${r.u.map((u,i)=>`<td style="text-align:right"><div style="font-weight:500;">${u}</div><div style="font-size:10px;color:var(--txt2);">${fk(r.b[i])}</div></td>`).join('')}
        <td style="text-align:right;font-weight:600;">${r.tU}</td>
        <td style="text-align:right;font-weight:600;">₡${fmt(r.tB)}</td>
        <td style="text-align:right;">${(r.tB/nT2*100).toFixed(1)}%</td>
      </tr>`).join('')}
      <tr class="ft"><td>Total</td>${NUE.map(d=>`<td style="text-align:right"><div>${d.items}</div><div style="font-size:10px;color:var(--txt2);">${fk(d.bruto)}</div></td>`).join('')}<td style="text-align:right">${NUE.reduce((a,d)=>a+d.items,0)}</td><td style="text-align:right">₡${fmt(nT2)}</td><td style="text-align:right">100%</td></tr>
    </table>

    <div class="sec">Cambio entre menús — bruto promedio por día por categoría</div>
    <table class="tbl">
      <tr><th>Categoría</th><th style="text-align:right">Bruto/día — menú viejo</th><th style="text-align:right">Bruto/día — menú nuevo</th><th style="text-align:right">Cambio</th><th style="text-align:right">Mix viejo</th><th style="text-align:right">Mix nuevo</th></tr>
      ${[{l:'Bebidas',c:'#3B8BD4',vB2:vbev,nB2:nbev},{l:'Cocina',c:'#1D9E75',vB2:vcoc,nB2:ncoc},{l:'Filtrado/Retail',c:'#EF9F27',vB2:vfil,nB2:nfil}].map(r=>`<tr>
        <td><span class="dot" style="background:${r.c}"></span><strong>${r.l}</strong></td>
        <td style="text-align:right;">₡${fmt(r.vB2/VIE.length)}</td>
        <td style="text-align:right;font-weight:600;">₡${fmt(r.nB2/NUE.length)}</td>
        <td style="text-align:right;">${chg(r.vB2/VIE.length,r.nB2/NUE.length)}</td>
        <td style="text-align:right;">${(r.vB2/vT2*100).toFixed(1)}%</td>
        <td style="text-align:right;font-weight:600;">${(r.nB2/nT2*100).toFixed(1)}%</td>
      </tr>`).join('')}
    </table>`;

  new Chart(document.getElementById('c-donut'),{type:'doughnut',data:{labels:['Bebidas','Cocina','Filtrado/Retail'],datasets:[{data:[totB,totC,totF],backgroundColor:['#3B8BD4','#1D9E75','#EF9F27'],borderWidth:0}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{position:'bottom',labels:{color:tc,font:{size:11},padding:12,boxWidth:10}},tooltip:{callbacks:{label:c=>'₡'+fmt(c.raw)+' — '+(c.raw/gran*100).toFixed(1)+'%'}}}}});
  new Chart(document.getElementById('c-cat'),{type:'bar',data:{labels:DIAS.map(d=>d.d),datasets:[
    {label:'Bebidas', data:DIAS.map(d=>d.bevU),backgroundColor:DIAS.map(d=>d.v?'rgba(59,139,212,.35)':'#3B8BD4'),borderRadius:3,stack:'s'},
    {label:'Cocina',  data:DIAS.map(d=>d.cocU),backgroundColor:DIAS.map(d=>d.v?'rgba(29,158,117,.3)':'#1D9E75'),borderRadius:3,stack:'s'},
    {label:'Filtrado',data:DIAS.map(d=>d.filU),backgroundColor:DIAS.map(d=>d.v?'rgba(239,159,39,.3)':'#EF9F27'),borderRadius:3,stack:'s'},
  ]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{mode:'index',intersect:false}},scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:10}}},y:{stacked:true,grid:{color:gc},ticks:{color:tc,font:{size:10}}}}}});
}

// ── COMPARATIVA ──────────────────────────────────────────────────────────────
function buildComparativa(){
  const el=document.getElementById('panel-comparativa');
  const PARES=[
    {dow:'Lunes', vie:DIAS[6],nue:DIAS[13]},
    {dow:'Martes',vie:DIAS[7],nue:DIAS[14]},
    {dow:'Jueves',vie:DIAS[2],nue:DIAS[9]},
    {dow:'Viernes',vie:DIAS[3],nue:DIAS[10]},
    {dow:'Sábado',vie:DIAS[4],nue:DIAS[11]},
    {dow:'Domingo',vie:DIAS[5],nue:DIAS[12]},
  ];
  const chg=(a,b)=>{const p=((b-a)/a*100).toFixed(0);return `<span class="badge ${+p>0?'bG':'bR'}">${+p>0?'+':''}${p}%</span>`;};

  el.innerHTML=`
    <div class="nota">La comparativa más justa: el mismo día de semana enfrentado entre menú viejo y menú nuevo. Elimina el efecto natural de que los fines de semana venden más.</div>
    <div class="g2" style="margin-bottom:1.2rem;">
      <div class="bV">
        <div style="font-size:10px;font-weight:600;color:var(--Atxt);text-transform:uppercase;letter-spacing:.06em;margin-bottom:.6rem;">Menú viejo · 9–17 Mar · 8 días</div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;">
          <div class="kpi"><div class="kl">Bruto total</div><div class="kv" style="font-size:15px;">₡${fmt(vB)}</div></div>
          <div class="kpi"><div class="kl">Neto total</div><div class="kv" style="font-size:15px;">₡${fmt(vN)}</div></div>
          <div class="kpi"><div class="kl">Bruto promedio/día</div><div class="kv" style="font-size:15px;">₡${fmt(vPD)}</div></div>
          <div class="kpi"><div class="kl">Ticket bruto/cliente</div><div class="kv" style="font-size:15px;">₡${fmt(vTkt)}</div></div>
          <div class="kpi"><div class="kl">Clientes/día</div><div class="kv" style="font-size:15px;">${Math.round(vT/VIE.length)}</div></div>
          <div class="kpi"><div class="kl">Ítems/cliente</div><div class="kv" style="font-size:15px;">${(VIE.reduce((a,d)=>a+d.items,0)/vT).toFixed(1)}</div></div>
        </div>
      </div>
      <div class="bN">
        <div style="font-size:10px;font-weight:600;color:var(--Btxt);text-transform:uppercase;letter-spacing:.06em;margin-bottom:.6rem;">Menú nuevo · 18–27 Mar · 10 días</div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;">
          <div class="kpi"><div class="kl">Bruto total</div><div class="kv" style="font-size:15px;">₡${fmt(nB)}</div><div class="ks"><span class="badge bA">1 día menos</span></div></div>
          <div class="kpi"><div class="kl">Neto total</div><div class="kv" style="font-size:15px;">₡${fmt(nN)}</div></div>
          <div class="kpi"><div class="kl">Bruto promedio/día</div><div class="kv" style="font-size:15px;">₡${fmt(nPD)}</div><div class="ks"><span class="badge bG">+${pdD}%</span></div></div>
          <div class="kpi"><div class="kl">Ticket bruto/cliente</div><div class="kv" style="font-size:15px;">₡${fmt(nTkt)}</div><div class="ks"><span class="badge bG">+${tktD}%</span></div></div>
          <div class="kpi"><div class="kl">Clientes/día</div><div class="kv" style="font-size:15px;">${Math.round(nT/NUE.length)}</div><div class="ks"><span class="badge ${nT/NUE.length>vT/VIE.length?'bG':'bR'}">${((nT/NUE.length-vT/VIE.length)/(vT/VIE.length)*100).toFixed(0)}%</span></div></div>
          <div class="kpi"><div class="kl">Ítems/cliente</div><div class="kv" style="font-size:15px;">${(NUE.reduce((a,d)=>a+d.items,0)/nT).toFixed(1)}</div></div>
        </div>
      </div>
    </div>
    <div class="ley"><span><i style="background:rgba(239,159,39,.7)"></i>Menú viejo</span><span><i style="background:#3B8BD4"></i>Menú nuevo</span></div>
    <div class="sec" style="margin-top:.5rem;">Ticket bruto por cliente — mismo día de semana</div>
    <div class="cw" style="height:200px;"><canvas id="c-ptkt"></canvas></div>
    <div class="sec" style="margin-top:.8rem;">Bruto total del día — mismo día de semana</div>
    <div class="cw" style="height:200px;"><canvas id="c-pbru"></canvas></div>
    <div class="sec" style="margin-top:.8rem;">Detalle</div>
    <table class="tbl">
      <tr><th>Día</th><th>Fecha viejo</th><th style="text-align:right">Clientes</th><th style="text-align:right">Bruto</th><th style="text-align:right">Ticket</th><th>Fecha nuevo</th><th style="text-align:right">Clientes</th><th style="text-align:right">Bruto</th><th style="text-align:right">Ticket</th><th style="text-align:right">Δ ticket</th><th style="text-align:right">Δ bruto</th></tr>
      ${PARES.map(p=>{const tV=p.vie.bruto/p.vie.txn,tN=p.nue.bruto/p.nue.txn,dT=((tN-tV)/tV*100).toFixed(0),dB=((p.nue.bruto-p.vie.bruto)/p.vie.bruto*100).toFixed(0);return `<tr>
        <td style="font-weight:600;">${p.dow}</td>
        <td style="color:var(--txt2);">${p.vie.d}</td><td style="text-align:right;">${p.vie.txn}</td><td style="text-align:right;">₡${fmt(p.vie.bruto)}</td><td style="text-align:right;">₡${fmt(tV)}</td>
        <td style="color:var(--txt2);">${p.nue.d}</td><td style="text-align:right;">${p.nue.txn}</td><td style="text-align:right;font-weight:600;">₡${fmt(p.nue.bruto)}</td><td style="text-align:right;font-weight:600;">₡${fmt(tN)}</td>
        <td style="text-align:right;">${chg(tV,tN)}</td><td style="text-align:right;">${chg(p.vie.bruto,p.nue.bruto)}</td>
      </tr>`;}).join('')}
    </table>`;

  new Chart(document.getElementById('c-ptkt'),{type:'bar',data:{labels:PARES.map(p=>p.dow),datasets:[{label:'Menú viejo',data:PARES.map(p=>Math.round(p.vie.bruto/p.vie.txn)),backgroundColor:'rgba(239,159,39,.7)',borderRadius:4},{label:'Menú nuevo',data:PARES.map(p=>Math.round(p.nue.bruto/p.nue.txn)),backgroundColor:'#3B8BD4',borderRadius:4}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.dataset.label+': ₡'+fmt(c.raw)+' por cliente'}}},scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:12}}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});
  new Chart(document.getElementById('c-pbru'),{type:'bar',data:{labels:PARES.map(p=>p.dow),datasets:[{label:'Menú viejo',data:PARES.map(p=>p.vie.bruto),backgroundColor:'rgba(239,159,39,.7)',borderRadius:4},{label:'Menú nuevo',data:PARES.map(p=>p.nue.bruto),backgroundColor:'#3B8BD4',borderRadius:4}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.dataset.label+': ₡'+fmt(c.raw)}}},scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:12}}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});
}

// ── ADOPCIÓN ─────────────────────────────────────────────────────────────────
function buildAdopcion(){
  const el=document.getElementById('panel-adopcion');
  // Total productos en menú nuevo con ventas registradas
  const totalMenuNuevo=42;
  const pct=NUE.map(d=>(d.nv/d.items*100).toFixed(1));
  const totalNV=NUE.reduce((a,d)=>a+d.nv,0);
  const totalItems=NUE.reduce((a,d)=>a+d.items,0);

  el.innerHTML=`
    <div class="nota">
      <strong>¿Qué mide la adopción?</strong> De cada 100 ítems que se vendieron en un día, cuántos eran productos del menú nuevo.
      Si el día 1 arrancó en 28% y la semana siguiente sigue subiendo, el cliente está conociendo y eligiendo activamente el nuevo menú.
    </div>

    <div style="display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:10px;margin-bottom:1.2rem;">
      <div class="kpi" style="text-align:center;">
        <div class="num-big" style="color:var(--Btxt);">${(totalNV/totalItems*100).toFixed(1)}%</div>
        <div class="num-label">adopción promedio<br>en los 10 días del menú nuevo</div>
      </div>
      <div class="kpi" style="text-align:center;">
        <div class="num-big">${totalNV}</div>
        <div class="num-label">ítems nuevos vendidos<br>de ${totalItems} totales</div>
      </div>
      <div class="kpi" style="text-align:center;">
        <div class="num-big" style="color:var(--Gtxt);">${Math.max(...NUE.map(d=>+(d.nv/d.items*100).toFixed(1)))}%</div>
        <div class="num-label">pico de adopción<br>${NUE[NUE.map(d=>+(d.nv/d.items*100).toFixed(1)).indexOf(Math.max(...NUE.map(d=>+(d.nv/d.items*100).toFixed(1))))].d}</div>
      </div>
    </div>

    <div class="ley"><span><i style="background:#3B8BD4"></i>% de ítems nuevos sobre el total vendido ese día</span></div>
    <div class="cw" style="height:210px;"><canvas id="c-adop"></canvas></div>

    <div class="sec" style="margin-top:1rem;">Desglose día a día</div>
    <table class="tbl">
      <tr>
        <th>Día</th>
        <th style="text-align:right">Total ítems vendidos</th>
        <th style="text-align:right">Ítems del menú nuevo</th>
        <th style="text-align:right">% adopción</th>
        <th style="text-align:right">Clientes</th>
        <th style="text-align:right">Ítems nuevos por cliente</th>
      </tr>
      ${NUE.map((d,i)=>`<tr>
        <td style="font-weight:600;">${d.d}</td>
        <td style="text-align:right;">${d.items}</td>
        <td style="text-align:right;font-weight:600;">${d.nv}</td>
        <td style="text-align:right;"><span class="badge ${parseFloat(pct[i])>=25?'bG':parseFloat(pct[i])>=18?'bB':'bA'}">${pct[i]}%</span></td>
        <td style="text-align:right;">${d.txn}</td>
        <td style="text-align:right;">${(d.nv/d.txn).toFixed(1)}</td>
      </tr>`).join('')}
      <tr class="ft">
        <td>Total</td>
        <td style="text-align:right;">${totalItems}</td>
        <td style="text-align:right;">${totalNV}</td>
        <td style="text-align:right;"><span class="badge bB">${(totalNV/totalItems*100).toFixed(1)}%</span></td>
        <td style="text-align:right;">${nT}</td>
        <td style="text-align:right;">${(totalNV/nT).toFixed(1)}</td>
      </tr>
    </table>`;

  new Chart(document.getElementById('c-adop'),{type:'bar',data:{labels:NUE.map(d=>d.d),datasets:[
    {label:'% adopción',data:pct.map(v=>parseFloat(v)),backgroundColor:NUE.map((_,i)=>parseFloat(pct[i])>=25?'#1D9E75':parseFloat(pct[i])>=18?'#3B8BD4':'rgba(59,139,212,.5)'),borderRadius:5},
  ]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.raw.toFixed(1)+'% de los ítems vendidos ese día son del menú nuevo'}}},scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:12}}},y:{grid:{color:gc},max:35,ticks:{color:tc,font:{size:11},callback:v=>v+'%'},title:{display:true,text:'% de ítems del menú nuevo sobre total del día',color:tc,font:{size:10}}}}}});
}

// ── PRODUCTOS NUEVOS ─────────────────────────────────────────────────────────
function buildProductos(){
  const el=document.getElementById('panel-productos');
  const iDia=NUE.map(d=>d.items), max=PRODS[0].total;
  const dias7=['Mié 18','Jue 19','Vie 20','Sáb 21','Dom 22','Lun 23','Mar 24','Mié 25','Jue 26','Vie 27'];
  const tend=q=>{const s=q.reduce((a,b)=>a+b,0);if(s===0)return '';const i=(q[0]+q[1])/2+.01,f=(q[q.length-2]+q[q.length-1])/2;return f>i*1.5?'<span class="badge bG">↑ Acelerando</span>':f>i*1.1?'<span class="badge bB">↑ Subiendo</span>':f<i*.6&&i>1?'<span class="badge bR">↓ Bajando</span>':'<span class="badge bA">→ Estable</span>';};

  el.innerHTML=`
    <div class="nota">Solo se muestran los productos del menú nuevo que tuvieron ventas en los primeros 10 días. Ordenados de mayor a menor venta total.</div>

    <div class="sec">Ventas totales por producto · 10 días</div>
    <div style="font-size:11px;color:var(--txt2);margin-bottom:.5rem;">
      <span style="color:#1D9E75;font-weight:600;">■ Acelerando / Subiendo</span> &nbsp;·&nbsp;
      <span style="color:var(--Atxt);font-weight:600;">■ Estable</span> &nbsp;·&nbsp;
      <span style="color:var(--Rtxt);font-weight:600;">■ Bajando</span>
    </div>
    <div class="cw" style="height:${PRODS.length*34+40}px;"><canvas id="c-prod-bar"></canvas></div>

    <div class="sec" style="margin-top:1.2rem;">Detalle por día</div>
    <table class="tbl">
      <tr>
        <th style="width:28%">Producto</th><th>Cat.</th>
        ${dias7.map(c=>`<th style="text-align:right;font-size:9px;">${c}</th>`).join('')}
        <th style="text-align:right;">Total</th>
        <th style="width:50px;"></th>
        <th>Tendencia</th>
      </tr>
      ${PRODS.map(p=>`<tr>
        <td style="font-weight:600;font-size:12px;">${p.n}</td>
        <td style="font-size:11px;color:var(--txt2);">${p.c}</td>
        ${p.q.map((v,i)=>`<td style="text-align:right;">${v>0
          ?`<div style="font-weight:${v>=5?'700':'400'};color:${v>=5?'var(--Gtxt)':'var(--txt)'};">${v}</div>
             <div style="font-size:9px;color:${(v/iDia[i]*100)>=4?'var(--Gtxt)':'var(--txt3)'};">${(v/iDia[i]*100).toFixed(1)}%</div>`
          :'<span style="color:var(--txt3);">—</span>'}</td>`).join('')}
        <td style="text-align:right;font-weight:700;">${p.total}</td>
        <td><div style="background:rgba(255,255,255,.08);border-radius:4px;height:4px;"><div style="height:4px;border-radius:4px;width:${(p.total/max*100).toFixed(0)}%;background:#3B8BD4;"></div></div></td>
        <td>${tend(p.q)}</td>
      </tr>`).join('')}
      <tr class="ft">
        <td colspan="2">Total ítems nuevos</td>
        ${NUE.map(d=>`<td style="text-align:right;">${d.nv}<div style="font-size:9px;font-weight:400;color:var(--txt2);">${(d.nv/d.items*100).toFixed(1)}%</div></td>`).join('')}
        <td style="text-align:right;">${NUE.reduce((a,d)=>a+d.nv,0)}</td>
        <td colspan="2"></td>
      </tr>
    </table>`;

  // Color por tendencia
  const tendCol=q=>{const s=q.reduce((a,b)=>a+b,0);if(s===0)return '#888';const i=(q[0]+q[1])/2+.01,f=(q[q.length-2]+q[q.length-1])/2;return f>i*1.1?'#1D9E75':f<i*.6&&i>1?'#E24B4A':'#EF9F27';};

  new Chart(document.getElementById('c-prod-bar'),{
    type:'bar',
    data:{
      labels:PRODS.map(p=>p.n),
      datasets:[{
        data:PRODS.map(p=>p.total),
        backgroundColor:PRODS.map(p=>tendCol(p.q)),
        borderRadius:3,
      }]
    },
    options:{
      indexAxis:'y',
      responsive:true,maintainAspectRatio:false,
      plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.raw+' unidades en 10 días'}}},
      scales:{
        x:{grid:{color:gc},ticks:{color:tc,font:{size:10}}},
        y:{grid:{color:gc},ticks:{color:tc,font:{size:11}},autoSkip:false},
      }
    }
  });
}

// ── CONCLUSIONES ─────────────────────────────────────────────────────────────
function buildConclusiones(){
  const el=document.getElementById('panel-conclusiones');
  const tktD15=DIAS[5].bruto/DIAS[5].txn, tktD22=DIAS[12].bruto/DIAS[12].txn;
  const totalNV=NUE.reduce((a,d)=>a+d.nv,0), totalIt=NUE.reduce((a,d)=>a+d.items,0);
  const tostadas=PRODS.find(p=>p.n==='Tostadas Francesas');
  const ranchera=PRODS.find(p=>p.n==='Cacerola Ranchera');
  const mango=PRODS.find(p=>p.n==='Mango Matcha');
  const sandwich=PRODS.find(p=>p.n==='Sandwich Pollo al Pesto');
  const grill=PRODS.find(p=>p.n==='Sandwich Grill Cheese');

  // Mix cocina dinámico
  const vCocPct=(VIE.reduce((a,d)=>a+d.cocB,0)/(VIE.reduce((a,d)=>a+d.bevB+d.cocB+d.filB,0))*100).toFixed(1);
  const nCocPct=(NUE.reduce((a,d)=>a+d.cocB,0)/(NUE.reduce((a,d)=>a+d.bevB+d.cocB+d.filB,0))*100).toFixed(1);

  // Meta cumplida
  const META=580645;
  const diasMeta=NUE.filter(d=>d.bruto>=META).length;

  // Mejor día menú nuevo
  const mejorDia=NUE.reduce((a,d)=>d.bruto>a.bruto?d:a,NUE[0]);

  el.innerHTML=`
    <div style="margin-bottom:1rem;">
      <div style="font-size:13px;color:var(--txt2);line-height:1.7;">
        Lo que los datos de los 18 días de marzo confirman — 8 días menú viejo, 10 días menú nuevo.
      </div>
    </div>

    <div class="ins insG">
      <div class="it">El ticket bruto subió +${tktD}% por visita — de ₡${fmt(vTkt)} a ₡${fmt(nTkt)}</div>
      <div class="ic">
        Cada cliente genera <strong>₡${fmt(nTkt-vTkt)} más</strong> en promedio con el menú nuevo.
        Esto incluye el efecto combinado del cambio de menú y ajuste de precios.
        En 10 días eso representa <strong>₡${fmt(Math.round((nTkt-vTkt)*nT))}</strong> adicionales vs lo que hubiera generado al ticket anterior.
      </div>
    </div>

    <div class="ins insG">
      <div class="it">El bruto promedio por día subió +${pdD}% — de ₡${fmt(vPD)} a ₡${fmt(nPD)}</div>
      <div class="ic">
        Menú viejo: <strong>₡${fmt(vPD)}</strong>/día (8 días). Menú nuevo: <strong>₡${fmt(nPD)}</strong>/día (10 días).
        De 10 días del menú nuevo, <strong>${diasMeta} superaron la meta operativa de ₡${fmt(META)}</strong>.
      </div>
    </div>

    <div class="ins insG">
      <div class="it">El ${mejorDia.d} fue el mejor día del menú nuevo — ₡${fmt(mejorDia.bruto)}</div>
      <div class="ic">
        ${mejorDia.txn} clientes · ticket promedio ₡${fmt(Math.round(mejorDia.bruto/mejorDia.txn))} · ${mejorDia.items} ítems vendidos.<br>
        Dom 15 (menú viejo): <strong>₡${fmt(DIAS[5].bruto)}</strong> · ${DIAS[5].txn} clientes · ticket ₡${fmt(Math.round(tktD15))}.
        <strong>+${((mejorDia.bruto-DIAS[5].bruto)/DIAS[5].bruto*100).toFixed(0)}% de bruto</strong> vs el mejor domingo del menú viejo.
      </div>
    </div>

    <div class="ins insG">
      <div class="it">Cocina pasó del ${vCocPct}% al ${nCocPct}% del bruto — gana peso en el negocio</div>
      <div class="ic">
        Con el menú viejo, cocina era el <strong>${vCocPct}%</strong> del bruto (₡${fmt(VIE.reduce((a,d)=>a+d.cocB,0))}).
        Con el menú nuevo subió a <strong>${nCocPct}%</strong> (₡${fmt(NUE.reduce((a,d)=>a+d.cocB,0))}).
        Las cacerolas, sándwiches y tostadas están jalando más peso dentro del negocio.
      </div>
    </div>

    <div class="ins insG">
      <div class="it">Tostadas Francesas y Cacerola Ranchera — los productos ancla del menú nuevo</div>
      <div class="ic">
        <strong>Tostadas Francesas</strong>: ${tostadas.total} unidades en 10 días · presentes todos los días · pico de 10 el sáb 21.<br>
        <strong>Cacerola Ranchera</strong>: ${ranchera.total} unidades · consistente toda la quincena.<br>
        Son los dos productos con mayor regularidad y tracción del menú nuevo.
      </div>
    </div>

    <div class="ins insG">
      <div class="it">Sándwiches — tracción creciente en la segunda semana</div>
      <div class="ic">
        <strong>Sandwich Pollo al Pesto</strong>: ${sandwich.total} unidades en 10 días, con sus mejores días en la segunda semana.<br>
        <strong>Sandwich Grill Cheese</strong>: ${grill.total} unidades · estable y consistente todos los días registrados.<br>
        Los sándwiches están consolidándose como opción de almuerzo del menú nuevo.
      </div>
    </div>

    <div class="ins insA">
      <div class="it">Mango Matcha — la bebida nueva con más tracción, pero aún hay espacio</div>
      <div class="ic">
        Con <strong>${mango.total} unidades en 10 días</strong> es la bebida nueva más vendida.
        Arranció lento y se estabilizó — todavía sin un pico claro. Vale explorar si falta visibilidad en el menú o si el equipo lo está ofreciendo activamente.
      </div>
    </div>`;
}

// ── EVOLUCIÓN MENÚ NUEVO ─────────────────────────────────────────────────────
function buildSemanas(){
  const el=document.getElementById('panel-semanas');
  const META=580645;
  // NUE = 10 días del menú nuevo (índices 0-9)
  const labels=NUE.map((d,i)=>`Día ${i+1}\n${d.d}`);
  const colBar=NUE.map(d=>d.bruto>=META?'#1D9E75':'#3B8BD4');

  // KPIs comparando primera mitad vs segunda mitad
  const M1=NUE.slice(0,5), M2=NUE.slice(5,10);
  const avg=arr=>arr.reduce((a,d)=>a+d.bruto,0)/arr.length;
  const avgTkt=arr=>arr.reduce((a,d)=>a+d.bruto/d.txn,0)/arr.length;
  const chg=(a,b)=>{const p=((b-a)/a*100).toFixed(0);return `<span class="badge ${+p>=0?'bG':'bR'}">${+p>0?'+':''}${p}%</span>`;};

  el.innerHTML=`
    <div class="nota">
      Evolución del menú nuevo desde el lanzamiento — día 1 (Mié 18) al día 10 (Vie 27).
      Barras en <span style="color:#1D9E75;font-weight:600;">verde</span> = días que superaron la meta de ₡${fmt(META)}.
    </div>

    <div style="display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:10px;margin-bottom:1rem;">
      <div class="kpi"><div class="kl">Bruto total menú nuevo</div><div class="kv">₡${fmt(NUE.reduce((a,d)=>a+d.bruto,0))}</div><div class="ks">10 días</div></div>
      <div class="kpi"><div class="kl">Días sobre la meta</div><div class="kv" style="color:var(--Gtxt);">${NUE.filter(d=>d.bruto>=META).length} <span style="font-size:13px;color:var(--txt2);">de 10</span></div></div>
      <div class="kpi"><div class="kl">Días 1–5 · bruto/día</div><div class="kv">₡${fmt(avg(M1))}</div><div class="ks">primeros 5 días</div></div>
      <div class="kpi"><div class="kl">Días 6–10 · bruto/día</div><div class="kv">₡${fmt(avg(M2))}</div><div class="ks">${chg(avg(M1),avg(M2))} vs días 1–5</div></div>
    </div>

    <div class="sec">Bruto por día · línea de meta ₡${fmt(META)}</div>
    <div class="cw" style="height:220px;"><canvas id="c-ev-bruto"></canvas></div>

    <div class="sec" style="margin-top:1rem;">Ticket bruto/cliente · evolución</div>
    <div class="cw" style="height:180px;"><canvas id="c-ev-tkt"></canvas></div>

    <div class="sec" style="margin-top:1rem;">Detalle día a día</div>
    <table class="tbl">
      <tr><th>#</th><th>Día</th><th style="text-align:right">Bruto</th><th style="text-align:right">vs meta</th><th style="text-align:right">Neto</th><th style="text-align:right">Txn</th><th style="text-align:right">Ticket</th><th style="text-align:right">Ítems</th></tr>
      ${NUE.map((d,i)=>{
        const diff=d.bruto-META;
        const col=diff>=0?'var(--Gtxt)':'var(--Rtxt)';
        return `<tr>
          <td style="color:var(--txt3);">${i+1}</td>
          <td style="font-weight:600;">${d.d}</td>
          <td style="text-align:right;font-weight:600;">₡${fmt(d.bruto)}</td>
          <td style="text-align:right;color:${col};">${diff>=0?'+':''}₡${fmt(diff)}</td>
          <td style="text-align:right;">₡${fmt(d.neto)}</td>
          <td style="text-align:right;">${d.txn}</td>
          <td style="text-align:right;">₡${fmt(Math.round(d.bruto/d.txn))}</td>
          <td style="text-align:right;">${d.items}</td>
        </tr>`;
      }).join('')}
    </table>`;

  new Chart(document.getElementById('c-ev-bruto'),{type:'bar',
    data:{labels:NUE.map((d,i)=>`Día ${i+1} · ${d.d}`),
      datasets:[
        {label:'Bruto',data:NUE.map(d=>d.bruto),backgroundColor:colBar,borderRadius:4},
        {type:'line',label:'Meta',data:NUE.map(()=>META),borderColor:'rgba(239,159,39,.6)',borderDash:[5,4],borderWidth:1.5,pointRadius:0,fill:false},
      ]},
    options:{responsive:true,maintainAspectRatio:false,
      plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.dataset.label==='Meta'?'Meta: ₡'+fmt(c.raw):'Bruto: ₡'+fmt(c.raw)}}},
      scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:10},maxRotation:0}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});

  new Chart(document.getElementById('c-ev-tkt'),{type:'line',
    data:{labels:NUE.map((d,i)=>`Día ${i+1}`),
      datasets:[{
        label:'Ticket bruto/cliente',
        data:NUE.map(d=>Math.round(d.bruto/d.txn)),
        borderColor:'#3B8BD4',backgroundColor:'rgba(59,139,212,.08)',
        pointBackgroundColor:NUE.map(d=>d.bruto>=META?'#1D9E75':'#3B8BD4'),
        pointRadius:5,borderWidth:2,tension:.3,fill:true,
      }]},
    options:{responsive:true,maintainAspectRatio:false,
      plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>'₡'+fmt(c.raw)+' por cliente'}}},
      scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:10}}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});
}


// ── POR TIPO DE DÍA ──────────────────────────────────────────────────────────
function buildTipoDias(){
  const el=document.getElementById('panel-tipodias');
  const EDS=['Lun','Mar','Mié','Jue','Vie'];
  const ents=DIAS.filter(d=>EDS.includes(d.dow));
  const sabs=DIAS.filter(d=>d.dow==='Sáb');
  const doms=DIAS.filter(d=>d.dow==='Dom');

  const stats=arr=>{
    if(!arr.length) return null;
    const bs=arr.map(d=>d.bruto).sort((a,b)=>a-b);
    const avg=bs.reduce((a,b)=>a+b,0)/bs.length;
    const min=bs[0], max=bs[bs.length-1];
    const med=bs.length%2===0?(bs[bs.length/2-1]+bs[bs.length/2])/2:bs[Math.floor(bs.length/2)];
    const avgTkt=arr.reduce((a,d)=>a+d.bruto/d.txn,0)/arr.length;
    const avgTxn=arr.reduce((a,d)=>a+d.txn,0)/arr.length;
    const avgItems=arr.reduce((a,d)=>a+d.items,0)/arr.length;
    return {avg,min,max,med,avgTkt,avgTxn,avgItems,n:arr.length,dias:arr};
  };

  const G=[
    {label:'Entre semana',sub:'Lun – Vie',color:'#3B8BD4',bgc:'rgba(59,139,212,.15)',s:stats(ents)},
    {label:'Sábado',       sub:'Solo sábados',color:'#EF9F27',bgc:'rgba(239,159,39,.15)',s:stats(sabs)},
    {label:'Domingo',      sub:'Solo domingos',color:'#1D9E75',bgc:'rgba(29,158,117,.15)',s:stats(doms)},
  ];

  const card=g=>`
    <div style="border:.5px solid var(--brd);border-radius:var(--radL);padding:1rem;background:var(--bg2);">
      <div style="display:flex;align-items:center;gap:8px;margin-bottom:.9rem;">
        <div style="width:10px;height:10px;border-radius:50%;background:${g.color};flex-shrink:0;"></div>
        <div>
          <div style="font-weight:600;font-size:13px;color:var(--txt);">${g.label}</div>
          <div style="font-size:11px;color:var(--txt2);">${g.sub} · ${g.s.n} días registrados</div>
        </div>
      </div>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:.8rem;">
        <div class="kpi"><div class="kl">Promedio bruto</div><div class="kv" style="font-size:15px;color:${g.color};">₡${fmt(g.s.avg)}</div></div>
        <div class="kpi"><div class="kl">Mediana bruto</div><div class="kv" style="font-size:15px;">₡${fmt(g.s.med)}</div><div class="ks">sin distorsión de picos</div></div>
        <div class="kpi"><div class="kl">Día más bajo</div><div class="kv" style="font-size:15px;color:var(--Rtxt);">₡${fmt(g.s.min)}</div></div>
        <div class="kpi"><div class="kl">Día más alto</div><div class="kv" style="font-size:15px;color:var(--Gtxt);">₡${fmt(g.s.max)}</div></div>
        <div class="kpi"><div class="kl">Ticket promedio</div><div class="kv" style="font-size:15px;">₡${fmt(g.s.avgTkt)}</div></div>
        <div class="kpi"><div class="kl">Clientes / día</div><div class="kv" style="font-size:15px;">${Math.round(g.s.avgTxn)}</div></div>
      </div>
      <div style="font-size:10px;color:var(--txt2);text-transform:uppercase;letter-spacing:.04em;margin-bottom:5px;">Cada día registrado</div>
      <div style="display:flex;flex-direction:column;gap:4px;">
        ${g.s.dias.map(d=>{
          const pct=(d.bruto/g.s.max*100).toFixed(0);
          const col=d.bruto>=g.s.avg?g.color:'rgba(255,255,255,.25)';
          return `<div style="display:flex;align-items:center;gap:8px;">
            <div style="font-size:11px;color:var(--txt2);width:38px;flex-shrink:0;">${d.d}</div>
            <div style="flex:1;background:rgba(255,255,255,.06);border-radius:3px;height:14px;overflow:hidden;">
              <div style="width:${pct}%;height:14px;border-radius:3px;background:${col};display:flex;align-items:center;padding-left:5px;min-width:2px;"></div>
            </div>
            <div style="font-size:11px;font-weight:600;color:${d.bruto>=g.s.avg?g.color:'var(--txt2)'};width:72px;text-align:right;">₡${fmt(d.bruto)}</div>
            <div style="font-size:10px;color:var(--txt3);width:40px;text-align:right;">${d.txn} txn</div>
          </div>`;
        }).join('')}
      </div>
      <div style="margin-top:.8rem;padding-top:.6rem;border-top:.5px solid var(--brd);font-size:11px;color:var(--txt2);">
        Rango real: <strong style="color:var(--txt);">₡${fmt(g.s.min)}</strong> – <strong style="color:var(--txt);">₡${fmt(g.s.max)}</strong>
        &nbsp;·&nbsp; Brecha: <strong style="color:${g.color};">₡${fmt(g.s.max-g.s.min)}</strong>
        &nbsp;·&nbsp; Diferencia promedio/mediana: <strong style="color:var(--txt);">₡${fmt(Math.abs(g.s.avg-g.s.med))}</strong>
      </div>
    </div>`;

  el.innerHTML=`
    <div class="nota">
      El <strong>promedio</strong> puede distorsionarse si un día fue excepcionalmente alto o bajo.
      La <strong>mediana</strong> representa el día "del medio" real — más útil para entender qué esperar en un día típico.
      Las barras muestran cada día en contexto: <span style="color:#3B8BD4;">coloreado</span> = sobre el promedio del grupo, gris = bajo el promedio.
    </div>

    <div style="display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px;margin-bottom:1.2rem;">
      ${G.map(g=>card(g)).join('')}
    </div>

    <div class="sec">Comparación entre grupos — bruto por tipo de día</div>
    <div class="ley">
      <span><i style="background:#3B8BD4"></i>Entre semana</span>
      <span><i style="background:#EF9F27"></i>Sábado</span>
      <span><i style="background:#1D9E75"></i>Domingo</span>
    </div>
    <div class="cw" style="height:220px;"><canvas id="c-td-comp"></canvas></div>

    <div class="sec" style="margin-top:1rem;">Tabla resumen</div>
    <table class="tbl">
      <tr><th>Tipo de día</th><th style="text-align:right">Días</th><th style="text-align:right">Prom. bruto</th><th style="text-align:right">Mediana</th><th style="text-align:right">Mínimo</th><th style="text-align:right">Máximo</th><th style="text-align:right">Ticket prom.</th><th style="text-align:right">Clientes/día</th></tr>
      ${G.map(g=>`<tr>
        <td><span class="dot" style="background:${g.color}"></span><strong>${g.label}</strong></td>
        <td style="text-align:right;">${g.s.n}</td>
        <td style="text-align:right;font-weight:600;color:${g.color};">₡${fmt(g.s.avg)}</td>
        <td style="text-align:right;">₡${fmt(g.s.med)}</td>
        <td style="text-align:right;color:var(--Rtxt);">₡${fmt(g.s.min)}</td>
        <td style="text-align:right;color:var(--Gtxt);">₡${fmt(g.s.max)}</td>
        <td style="text-align:right;">₡${fmt(g.s.avgTkt)}</td>
        <td style="text-align:right;">${Math.round(g.s.avgTxn)}</td>
      </tr>`).join('')}
    </table>`;

  new Chart(document.getElementById('c-td-comp'),{type:'bar',
    data:{
      labels:['Promedio','Mediana','Mínimo','Máximo'],
      datasets:G.map(g=>({
        label:g.label,
        data:[Math.round(g.s.avg),Math.round(g.s.med),g.s.min,g.s.max],
        backgroundColor:g.color,
        borderRadius:4,
      }))
    },
    options:{responsive:true,maintainAspectRatio:false,
      plugins:{legend:{position:'bottom',labels:{color:tc,font:{size:11},boxWidth:10}},
        tooltip:{callbacks:{label:c=>c.dataset.label+': ₡'+fmt(c.raw)}}},
      scales:{x:{grid:{color:gc},ticks:{color:tc,font:{size:11}}},y:{grid:{color:gc},ticks:{color:tc,font:{size:10},callback:v=>'₡'+fmt(v/1000)+'k'}}}}});
}

// ── TABS ─────────────────────────────────────────────────────────────────────
const built={tendencia:false,categorias:false,comparativa:false,adopcion:false,productos:false,semanas:false,tipodias:false,conclusiones:false};
function sw(tab,el){
  Object.keys(built).forEach(p=>document.getElementById('panel-'+p).style.display=p===tab?'':'none');
  document.querySelectorAll('.tab').forEach(b=>b.classList.remove('active'));
  if(el)el.classList.add('active');
  if(!built[tab]){
    ({tendencia:buildTendencia,categorias:buildCategorias,comparativa:buildComparativa,adopcion:buildAdopcion,productos:buildProductos,semanas:buildSemanas,tipodias:buildTipoDias,conclusiones:buildConclusiones})[tab]();
    built[tab]=true;
  }
}
buildTendencia(); built.tendencia=true;
</script>
</body>
</html>
