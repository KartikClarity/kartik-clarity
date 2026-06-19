<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Founder Revenue Platform™</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

:root{
  --bg:#070A12;
  --panel:rgba(255,255,255,0.04);
  --stroke:rgba(255,255,255,0.08);
  --text:#EAF0FF;
  --muted:rgba(234,240,255,0.6);
  --accent:#7C5CFF;
  --accent2:#00E5A8;
}

*{margin:0;padding:0;box-sizing:border-box;font-family:Inter;}

body{
  background:
    radial-gradient(1200px 600px at 20% 0%, rgba(124,92,255,0.25), transparent),
    radial-gradient(900px 500px at 80% 10%, rgba(0,229,168,0.12), transparent),
    var(--bg);
  color:var(--text);
  padding:40px;
}

.container{
  max-width:1100px;
  margin:auto;
}

/* TOP NAV */
.nav{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-bottom:30px;
}

.logo{
  font-weight:700;
  letter-spacing:-0.5px;
}

.pill{
  padding:6px 12px;
  border:1px solid var(--stroke);
  border-radius:999px;
  color:var(--muted);
  font-size:12px;
}

/* HERO */
.hero{
  padding:60px;
  border:1px solid var(--stroke);
  border-radius:24px;
  background:linear-gradient(145deg, rgba(255,255,255,0.06), rgba(255,255,255,0.02));
  backdrop-filter: blur(20px);
  position:relative;
  overflow:hidden;
}

.hero:before{
  content:"";
  position:absolute;
  width:600px;height:600px;
  background:radial-gradient(circle, rgba(124,92,255,0.25), transparent 60%);
  top:-200px;right:-200px;
}

h1{
  font-size:44px;
  letter-spacing:-1.5px;
  line-height:1.1;
}

.sub{
  margin-top:14px;
  color:var(--muted);
  max-width:600px;
  line-height:1.6;
}

.cta{
  margin-top:26px;
  display:flex;
  gap:12px;
}

button{
  padding:12px 16px;
  border-radius:12px;
  border:none;
  cursor:pointer;
  font-weight:600;
}

.primary{
  background:var(--accent);
  color:white;
}

.secondary{
  background:transparent;
  border:1px solid var(--stroke);
  color:var(--text);
}

/* GRID */
.grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:16px;
  margin-top:28px;
}

.card{
  padding:18px;
  border-radius:18px;
  background:var(--panel);
  border:1px solid var(--stroke);
  transition:0.25s ease;
}

.card:hover{
  transform:translateY(-4px);
  border-color:rgba(124,92,255,0.5);
}

.value{
  font-size:28px;
  font-weight:700;
  letter-spacing:-1px;
}

.label{
  color:var(--muted);
  margin-top:6px;
  font-size:13px;
}

/* LOWER SECTION */
.section{
  margin-top:35px;
}

.title{
  font-size:14px;
  letter-spacing:1px;
  color:var(--muted);
  margin-bottom:12px;
}

.list{
  display:flex;
  flex-direction:column;
  gap:10px;
}

.item{
  padding:14px;
  border-radius:14px;
  background:rgba(255,255,255,0.03);
  border:1px solid var(--stroke);
  font-size:14px;
  line-height:1.4;
}

.bad{
  border-left:3px solid #ff4d4d;
}

.good{
  border-left:3px solid var(--accent2);
}

</style>
</head>

<body>

<div class="container">

  <div class="nav">
    <div class="logo">Founder Revenue Platform™</div>
    <div class="pill">System Status: Active</div>
  </div>

  <div class="hero">

    <h1>Detect Revenue Leakage Before It Becomes Loss.</h1>

    <div class="sub">
      A precision-built system that identifies hidden funnel inefficiencies,
      outbound decay, and conversion leaks — then converts them into recovery actions.
    </div>

    <div class="cta">
      <button class="primary">Run Full Audit</button>
      <button class="secondary">View System Map</button>
    </div>

    <div class="grid">

      <div class="card">
        <div class="value">$236K</div>
        <div class="label">Revenue at Risk</div>
      </div>

      <div class="card">
        <div class="value">5</div>
        <div class="label">Active Leak Vectors</div>
      </div>

      <div class="card">
        <div class="value">24m</div>
        <div class="label">Recovery Time</div>
      </div>

    </div>

  </div>

  <div class="section">
    <div class="title">CRITICAL SYSTEM INSIGHTS</div>

    <div class="list">

      <div class="item bad">
        CRM follow-up decay detected → leads not re-engaged after 48h window
      </div>

      <div class="item bad">
        Outbound message variance too high → inconsistent response rate across segments
      </div>

      <div class="item good">
        Pricing structure stable → no immediate monetization leakage detected
      </div>

    </div>

  </div>

</div>

</body>
</html>
