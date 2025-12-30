# Ex-paineladminroblox
Seja bem vindo 
:root{
  --bg:#f7f7fb;
  --card:#ffffff;
  --text:#222;
  --accent:#2563eb;
  --muted:#555;
  --maxw:1100px;
  --radius:10px;
}

*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0;
  font-family:system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  color:var(--text);
  background:linear-gradient(180deg, var(--bg), #fff);
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  line-height:1.5;
}

.container{
  width:90%;
  max-width:var(--maxw);
  margin:0 auto;
}

/* Header */
.site-header{
  background:transparent;
  padding:18px 0;
}
.site-header .brand{display:inline-block;margin:0;color:var(--accent)}
.site-header nav{float:right}
.site-header nav a{margin-left:16px;text-decoration:none;color:var(--muted)}

/* Hero */
.hero{
  padding:64px 0;
  text-align:center;
}
.hero h2{font-size:2.1rem;margin:0 0 8px}
.hero p{color:var(--muted);margin:0 0 18px}
.btn{
  display:inline-block;
  background:var(--accent);
  color:#fff;
  padding:10px 16px;
  border-radius:8px;
  text-decoration:none;
}

/* Sections */
.section{padding:36px 0}
.cards{display:flex;gap:16px;flex-wrap:wrap;margin-top:16px}
.card{
  background:var(--card);
  padding:18px;
  border-radius:var(--radius);
  box-shadow:0 6px 18px rgba(0,0,0,0.06);
  flex:1 1 220px;
}

/* Form */
form{display:grid;gap:10px;max-width:560px}
label{display:flex;flex-direction:column;font-size:0.95rem;color:var(--muted)}
input,textarea{
  padding:10px;border-radius:8px;border:1px solid #e6e6ef;background:#fff;
  margin-top:6px;font-size:1rem;
}
.form-result{margin-top:8px;color:green}

/* Footer */
.site-footer{padding:20px 0;text-align:center;font-size:0.9rem;color:var(--muted)}

/* Responsive */
@media (max-width:700px){
  .site-header nav{float:none;text-align:right;margin-top:8px}
  .cards{flex-direction:column}
}
