# Finrendax
[index.html](https://github.com/user-attachments/files/32621212/index.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#05070A">
<title>FinRendax — Educação Financeira & Renda Extra</title>
<meta name="description" content="A FinRendax organiza suas finanças e ensina renda extra real, com metodologia prática e acesso vitalício por um pagamento único.">
<!-- Anti-clickjacking (o cabeçalho X-Frame-Options/frame-ancestors do servidor é a defesa principal) -->
<script>if(self!==top){document.documentElement.style.display='none';try{top.location=self.location}catch(e){}}</script>
<!-- SEGURANÇA: política de conteúdo (espelha o cabeçalho enviado pelo servidor em public/_headers) -->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self' 'unsafe-inline' https://unpkg.com https://cdnjs.cloudflare.com https://cdn.jsdelivr.net https://www.googletagmanager.com https://connect.facebook.net; style-src 'self' 'unsafe-inline' https://fonts.googleapis.com; font-src 'self' https://fonts.gstatic.com data:; img-src 'self' data: https://www.facebook.com https://www.google-analytics.com https://www.googletagmanager.com; connect-src 'self' https://api.emailjs.com https://*.google-analytics.com https://*.analytics.google.com https://www.googletagmanager.com https://www.facebook.com https://connect.facebook.net; frame-src 'none'; object-src 'none'; base-uri 'self'; form-action 'self'">
<meta name="referrer" content="strict-origin-when-cross-origin">
<meta name="color-scheme" content="dark">
<link rel="canonical" href="https://SEU-DOMINIO.com.br/">
<meta property="og:type" content="website">
<meta property="og:locale" content="pt_BR">
<meta property="og:site_name" content="FinRendax">
<meta property="og:title" content="FinRendax — Educação Financeira & Renda Extra">
<meta property="og:description" content="Organize suas finanças e aprenda renda extra real. Acesso vitalício por pagamento único.">
<meta property="og:url" content="https://SEU-DOMINIO.com.br/">
<meta name="twitter:card" content="summary">
<script type="application/ld+json">{"@context":"https://schema.org","@type":"Organization","name":"FinRendax","url":"https://SEU-DOMINIO.com.br/","email":"finrendax@gmail.com","description":"Educação financeira e renda extra com acesso vitalício."}</script>

<!-- CONFIGURAÇÃO -->
<script>
window.FRX_CONFIG = {
  company: {
    legalName: 'Vitor Hugo Nogueira Sousa',
    cnpj: 'pessoa física, sem CNPJ — atua como profissional autônomo',
    address: 'Presidente Prudente, SP — endereço completo disponível mediante solicitação ao encarregado',
    dpoName: 'Vitor Hugo Nogueira Sousa',
    dpoEmail: 'finrendax@gmail.com'
  },
  checkoutHosts: ['pay.kiwify.com.br', 'kiwify.com.br'],
  opsKeyHash: 'e50d1a1824a68e78e450f9835cb2cd5960ddee92557090ab35219298b97c9b71',       // senha do painel de agentes (SHA-256). Vazio = painel desativado para o público. Gere abrindo o site com ?ops=setup
  ga4Id: '',            // ex.: 'G-XXXXXXXXXX' — só carrega depois do consentimento de estatísticas
  metaPixelId: '',      // ex.: '123456789012345' — só carrega depois do consentimento de marketing
  emailjs: { publicKey: 'SUA_PUBLIC_KEY_AQUI', serviceId: 'SEU_SERVICE_ID', templateId: 'SEU_TEMPLATE_ID', guideLink: 'https://seusite.com/downloads/guia-finrendax.pdf' }
};
</script>

<!-- FONTES: carregadas sem bloquear a primeira pintura -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="preload" as="style" href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,400..800;1,400..800&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Space+Mono:wght@400;700&display=swap" onload="this.onload=null;this.rel='stylesheet'">
<noscript><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,400..800;1,400..800&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Space+Mono:wght@400;700&display=swap"></noscript>
<!-- Ícones (versão fixa, não bloqueia a renderização). Three.js e EmailJS são carregados sob demanda. -->
<script src="https://unpkg.com/lucide@0.454.0/dist/umd/lucide.min.js" defer></script>
<style>
/* ============================================================
   FINRENDAX — DESIGN SYSTEM 3D (ULTRA PREMIUM)
============================================================ */
@property --ang{syntax:'<angle>';initial-value:0deg;inherits:false;}
:root{
  --ink:        #05070A;
  --ink-2:      #0B0E14;
  --ink-3:      #121722;
  --paper:      #FAF7F2;
  --paper-2:    #EDE6DA;
  --wine:       #A32E3E;
  --wine-deep:  #6E1523;
  --wine-soft:  rgba(163, 46, 62, 0.16);
  --bronze:     #D9A043;
  --bronze-soft:rgba(217, 160, 67, 0.18);
  --ink-txt:    #F8F9FA;
  --ink-muted:  #94A3B8;
  --paper-txt:  #0F172A;
  --paper-muted:#64748B;
  --line-dark:  rgba(255, 255, 255, 0.08);
  --line-paper: rgba(15, 23, 42, 0.08);
  --shadow-lg:  0 25px 50px -12px rgba(0, 0, 0, 0.7);
  --shadow-md:  0 12px 24px -6px rgba(0, 0, 0, 0.5);
  --shadow-glow: 0 0 35px rgba(163, 46, 62, 0.25);
  --ease: cubic-bezier(0.16, 1, 0.3, 1);
  --serif: 'Fraunces', Georgia, serif;
  --sans: 'Plus Jakarta Sans', 'Inter', -apple-system, sans-serif;
  --mono: 'Space Mono', monospace;
}
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{
  font-family:var(--sans);
  background:var(--ink);
  color:var(--ink-txt);
  line-height:1.6;
  overflow-x:hidden;
  padding-bottom:78px;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  background-image: radial-gradient(circle at 50% -20%, rgba(163,46,62,0.18), transparent 75%);
}
body.menu-open{overflow:hidden;}
::selection{background:var(--wine);color:#fff;}
a{color:inherit;}
img{max-width:100%;display:block;}
button{font-family:inherit;}
:focus-visible{outline:2px solid var(--bronze);outline-offset:3px;}
.wrap{max-width:1200px;margin:0 auto;padding:0 6%;}
.grain::before{
  content:"";position:absolute;inset:0;pointer-events:none;opacity:.4;
  background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.8' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.05'/%3E%3C/svg%3E");
}

/* ============================================================
   CAMADAS DE FUNDO: 3D + AURORA + CURSOR
============================================================ */
#bg3d{position:fixed;inset:0;width:100%;height:100%;z-index:0;pointer-events:none;opacity:.9;}
.aurora{position:fixed;inset:0;z-index:0;pointer-events:none;overflow:hidden;}
.aurora i{position:absolute;border-radius:50%;filter:blur(90px);opacity:.5;will-change:transform;}
.aurora i:nth-child(1){width:520px;height:520px;left:-140px;top:8%;background:radial-gradient(circle,rgba(163,46,62,.55),transparent 70%);animation:drift1 22s ease-in-out infinite alternate;}
.aurora i:nth-child(2){width:460px;height:460px;right:-120px;top:38%;background:radial-gradient(circle,rgba(217,160,67,.30),transparent 70%);animation:drift2 26s ease-in-out infinite alternate;}
.aurora i:nth-child(3){width:600px;height:600px;left:30%;bottom:-260px;background:radial-gradient(circle,rgba(110,21,35,.6),transparent 70%);animation:drift1 30s ease-in-out infinite alternate-reverse;}
@keyframes drift1{from{transform:translate3d(0,0,0) scale(1)}to{transform:translate3d(80px,60px,0) scale(1.15)}}
@keyframes drift2{from{transform:translate3d(0,0,0) scale(1)}to{transform:translate3d(-90px,-50px,0) scale(1.2)}}
.cursor-glow{
  position:fixed;left:0;top:0;width:520px;height:520px;margin:-260px 0 0 -260px;border-radius:50%;
  background:radial-gradient(circle,rgba(217,160,67,.11),transparent 65%);
  pointer-events:none;z-index:0;transform:translate3d(-999px,-999px,0);will-change:transform;
}
@media (hover:none){.cursor-glow{display:none;}}
.page-section,footer,.stats-strip{position:relative;z-index:1;}
.scroll-progress{
  position:fixed;top:0;left:0;right:0;height:3px;z-index:1100;transform-origin:0 50%;transform:scaleX(0);
  background:linear-gradient(90deg,var(--wine),var(--bronze),#fff3d6);
  box-shadow:0 0 12px rgba(217,160,67,.7);
}

/* ---------- Nav ---------- */
nav{
  position:sticky;top:0;z-index:1000;
  background:rgba(5, 7, 10, 0.72);
  backdrop-filter:blur(22px) saturate(140%);-webkit-backdrop-filter:blur(22px) saturate(140%);
  border-bottom:1px solid var(--line-dark);
  padding:16px 6%;display:flex;align-items:center;justify-content:space-between;gap:20px;
  transition:padding .4s var(--ease), background .4s var(--ease), box-shadow .4s var(--ease);
}
nav.scrolled{padding:10px 6%;background:rgba(5,7,10,.9);box-shadow:0 10px 30px rgba(0,0,0,.45);}
.brand{display:flex;align-items:center;gap:11px;text-decoration:none;cursor:pointer;}
.brand-mark{
  width:38px;height:38px;border-radius:10px;
  background:linear-gradient(135deg,var(--wine),var(--wine-deep));
  display:flex;align-items:center;justify-content:center;
  font-family:var(--serif);font-weight:700;font-size:1.1rem;color:var(--paper);
  box-shadow:0 0 20px rgba(163,46,62,0.5), inset 0 1px 0 rgba(255,255,255,.25);
  border:1px solid rgba(255,255,255,0.15);
  transition:transform .6s var(--ease);
}
.brand:hover .brand-mark{transform:rotateY(360deg);}
.brand-word{font-family:var(--serif);font-weight:600;font-size:1.32rem;letter-spacing:-.02em;color:var(--ink-txt);}
.brand-word em{font-style:normal;color:var(--bronze);}
.nav-links{display:flex;gap:6px;list-style:none;align-items:center;}
.nav-links a{
  text-decoration:none;color:var(--ink-muted);font-size:.88rem;font-weight:500;
  padding:8px 16px;border-radius:10px;cursor:pointer;transition:all .3s var(--ease);
  display:flex;align-items:center;gap:8px;border:1px solid transparent;
}
.nav-links a .idx{font-family:var(--mono);font-size:.68rem;opacity:.55;transition:color .3s;}
.nav-links a:hover{color:var(--ink-txt);background:rgba(255,255,255,0.04);border-color:var(--line-dark);}
.nav-links a.active{color:var(--ink-txt);background:var(--wine-soft);border-color:rgba(163,46,62,0.3);}
.nav-links a.active .idx{color:var(--bronze);opacity:1;}
.nav-right{display:flex;align-items:center;gap:12px;}
.nav-cta{
  display:inline-flex;align-items:center;gap:8px;
  background:linear-gradient(135deg, #D9A043, #B37E2A);
  color:#0B0E13;
  padding:10px 22px;border-radius:10px;font-weight:700;font-size:.85rem;text-decoration:none;
  border:none;cursor:pointer;transition:all .3s var(--ease);white-space:nowrap;
  box-shadow:0 4px 15px rgba(217,160,67,0.25);
  position:relative;overflow:hidden;
}
.nav-cta::after {
  content: '';position: absolute;top: -50%;left: -50%;width: 200%;height: 200%;
  background: linear-gradient(60deg, transparent, rgba(255,255,255,0.3), transparent);
  transform: rotate(30deg);animation: shimmer 4s infinite;
}
@keyframes shimmer {
  0% { transform: translateX(-100%) rotate(30deg); }
  20%, 100% { transform: translateX(100%) rotate(30deg); }
}
.nav-cta:hover{transform:translateY(-2px);box-shadow:0 8px 25px rgba(217,160,67,0.4);filter:brightness(1.08);}
.btn-icon-only { padding: 12px 18px !important; }

/* ---------- Botão Hambúrguer (todas as telas) ---------- */
.menu-toggle{
  display:flex;
  background:rgba(255,255,255,0.04);
  border:1px solid var(--line-dark);
  color:var(--ink-txt);
  padding:10px;border-radius:12px;cursor:pointer;
  align-items:center;justify-content:center;
  transition:all .3s var(--ease);
  min-width:46px;min-height:46px;position:relative;
}
.menu-toggle:hover{background:var(--wine-soft);border-color:rgba(163,46,62,.5);}
.burger{width:20px;height:14px;position:relative;display:block;}
.burger span{position:absolute;left:0;height:2px;width:100%;background:currentColor;border-radius:2px;transition:transform .5s var(--ease), top .5s var(--ease), opacity .3s, width .4s var(--ease);}
.burger span:nth-child(1){top:0;}
.burger span:nth-child(2){top:6px;width:68%;}
.burger span:nth-child(3){top:12px;}
.menu-toggle:hover .burger span:nth-child(2){width:100%;}
.menu-toggle[aria-expanded="true"] .burger span:nth-child(1){top:6px;transform:rotate(45deg);}
.menu-toggle[aria-expanded="true"] .burger span:nth-child(2){opacity:0;transform:translateX(12px);}
.menu-toggle[aria-expanded="true"] .burger span:nth-child(3){top:6px;transform:rotate(-45deg);}

/* ---------- Menu em tela cheia ---------- */
.mobile-nav{
  position:fixed;inset:0;z-index:998;
  display:flex;flex-direction:column;justify-content:center;
  padding:110px 7% 100px;
  background:
    radial-gradient(circle at 85% 8%, rgba(163,46,62,.42), transparent 55%),
    radial-gradient(circle at 10% 100%, rgba(217,160,67,.16), transparent 50%),
    rgba(5,7,10,.97);
  backdrop-filter:blur(26px);-webkit-backdrop-filter:blur(26px);
  clip-path:circle(0px at calc(100% - 7% - 23px) 36px);
  visibility:hidden;
  transition:clip-path .8s var(--ease), visibility 0s .8s;
  perspective:1200px;overflow-y:auto;
}
.mobile-nav.open{
  clip-path:circle(160% at calc(100% - 7% - 23px) 36px);
  visibility:visible;transition:clip-path 1s var(--ease), visibility 0s;
}
.menu-inner{max-width:880px;width:100%;margin:0 auto;}
.menu-kicker{font-family:var(--mono);font-size:.72rem;letter-spacing:.18em;text-transform:uppercase;color:var(--bronze);margin-bottom:18px;opacity:0;transition:opacity .6s .2s;}
.mobile-nav.open .menu-kicker{opacity:1;}
.mobile-nav a.menu-link{
  display:flex;align-items:baseline;gap:20px;
  text-decoration:none;cursor:pointer;
  padding:clamp(10px,2.2vh,20px) 4px;
  border-bottom:1px solid var(--line-dark);
  color:var(--ink-txt);
  font-family:var(--serif);font-weight:500;font-size:clamp(2rem,6.4vw,3.8rem);letter-spacing:-.03em;line-height:1.05;
  opacity:0;transform:translate3d(0,46px,0) rotateX(-45deg);transform-origin:50% 0;
  transition:opacity .7s var(--ease), transform .9s var(--ease), color .3s, padding .4s var(--ease);
  position:relative;background:none;border-radius:0;min-height:44px;
}
.mobile-nav.open a.menu-link{opacity:1;transform:none;transition-delay:calc(.22s + var(--i) * .09s), calc(.22s + var(--i) * .09s), 0s, 0s;}
.mobile-nav a.menu-link .idx{font-family:var(--mono);font-size:.8rem;color:var(--bronze);font-weight:400;letter-spacing:0;min-width:34px;}
.mobile-nav a.menu-link .sub{margin-left:auto;font-family:var(--sans);font-size:.85rem;color:var(--ink-muted);letter-spacing:0;font-weight:500;text-align:right;}
.mobile-nav a.menu-link .arr{width:0;opacity:0;overflow:hidden;color:var(--bronze);transition:width .4s var(--ease), opacity .3s;display:flex;align-items:center;}
.mobile-nav a.menu-link:hover,.mobile-nav a.menu-link.active{color:var(--bronze);padding-left:18px;}
.mobile-nav a.menu-link:hover .arr,.mobile-nav a.menu-link.active .arr{width:40px;opacity:1;}
.mobile-nav a.menu-link.active{border-bottom-color:rgba(217,160,67,.5);}
.menu-foot{display:flex;gap:18px;align-items:center;flex-wrap:wrap;margin-top:34px;opacity:0;transform:translateY(20px);transition:opacity .7s .6s, transform .8s .6s var(--ease);}
.mobile-nav.open .menu-foot{opacity:1;transform:none;}
.menu-foot .mail{font-family:var(--mono);font-size:.78rem;color:var(--ink-muted);}
body.menu-open .bottom-bar{transform:translateY(110%);}

/* ---------- Sections ---------- */
.page-section{display:none;}
.page-section.active{display:block;animation:sect-in .7s var(--ease);}
@keyframes sect-in{from{opacity:0;transform:translate3d(0,22px,0)}to{opacity:1;transform:translate3d(0,0,0)}}
.reveal{opacity:0;transform:translate3d(0,36px,0) scale(.985);transition:opacity .9s var(--ease),transform .9s var(--ease);will-change:transform,opacity;}
.reveal.visible{opacity:1;transform:translate3d(0,0,0) scale(1);}
@keyframes child-in{from{opacity:0;translate:0 44px;}to{opacity:1;translate:0 0;}}
.reveal.visible .card,.reveal.visible .feat-row,.reveal.visible .stat{animation:child-in .9s var(--ease) backwards;animation-delay:calc(var(--i,0) * 90ms);}
.eyebrow{
  display:inline-flex;align-items:center;gap:10px;
  font-family:var(--mono);font-size:.75rem;letter-spacing:.15em;text-transform:uppercase;
  color:var(--bronze);margin-bottom:20px;font-weight:700;
}
.eyebrow::before{content:"";width:24px;height:2px;background:var(--bronze);display:inline-block;border-radius:2px;transform-origin:left;}
.reveal.visible .eyebrow::before,.reveal.visible.eyebrow::before{animation:line-grow 1s var(--ease) backwards .2s;}
@keyframes line-grow{from{transform:scaleX(0)}to{transform:scaleX(1)}}
.section-head{max-width:700px;margin:0 auto 50px;text-align:center;padding:0 20px;}
.section-head.left{text-align:left;margin:0 0 50px;}
.section-title{font-family:var(--serif);font-weight:600;font-size:clamp(2rem,4vw,3.1rem);letter-spacing:-.025em;line-height:1.15;color:var(--ink-txt);margin-bottom:16px;}
.section-title i{font-style:italic;color:var(--bronze);font-weight:400;}
.section-sub{color:var(--ink-muted);font-size:1.08rem;max-width:620px;margin:0 auto;font-weight:400;}
.section-head.left .section-sub{margin:0;}
.hairline{height:1px;background:linear-gradient(90deg, transparent, var(--line-dark), transparent);border:none;max-width:1200px;margin:0 auto;}

/* Título palavra a palavra */
.w{display:inline-block;overflow:hidden;vertical-align:bottom;padding-bottom:.14em;margin-bottom:-.14em;}
.wi{display:inline-block;transform:translate3d(0,110%,0) rotateX(-60deg);transform-origin:50% 100%;opacity:0;transition:transform 1s var(--ease), opacity .8s var(--ease);transition-delay:calc(var(--wd,0) * 60ms + 120ms);}
.reveal.visible .wi,.hero h1.in .wi,.section-title.in .wi{transform:none;opacity:1;}
.hero h1 i,.section-title i{background:linear-gradient(100deg,#D9A043,#fff0c9 45%,#D9A043 70%);background-size:220% 100%;-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;animation:gold-sheen 6s linear infinite;}
.hero h1 i .wi,.section-title i .wi{-webkit-text-fill-color:transparent;}
@keyframes gold-sheen{from{background-position:0% 0}to{background-position:220% 0}}

/* ---------- Buttons & Inputs ---------- */
.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:10px;
  padding:16px 32px;border-radius:12px;font-weight:700;font-size:.98rem;
  text-decoration:none;border:none;cursor:pointer;
  transition:transform .35s var(--ease), box-shadow .35s var(--ease), filter .3s, background .3s, border-color .3s;
  position:relative;overflow:hidden;white-space:nowrap;min-height:48px;
  transform:translate3d(var(--bx,0px),calc(var(--by,0px) + var(--hy,0px)),0);
}
.btn:hover{--hy:-3px;}
.btn::after{content:"";position:absolute;top:0;left:-120%;width:60%;height:100%;background:linear-gradient(100deg,transparent,rgba(255,255,255,.35),transparent);transform:skewX(-20deg);transition:left .8s var(--ease);pointer-events:none;}
.btn:hover::after{left:140%;}
.btn-wine{
  background:linear-gradient(135deg,var(--wine),var(--wine-deep));
  color:#fff;
  box-shadow:0 10px 28px -5px rgba(163,46,62,0.5), inset 0 1px 0 rgba(255,255,255,.2);
  border:1px solid rgba(255,255,255,0.15);
}
.btn-wine:hover{box-shadow:0 18px 35px -5px rgba(163,46,62,0.7), inset 0 1px 0 rgba(255,255,255,.25);filter:brightness(1.1);}
.btn-bronze{
  background:linear-gradient(135deg,#D9A043,#B37E2A);
  color:#0B0E13;
  box-shadow:0 10px 28px -5px rgba(217,160,67,0.4), inset 0 1px 0 rgba(255,255,255,.35);
  border:1px solid rgba(255,255,255,0.2);
}
.btn-bronze:hover{box-shadow:0 18px 35px -5px rgba(217,160,67,0.6);filter:brightness(1.08);}
.btn-ghost{background:rgba(255,255,255,0.03);border:1px solid var(--line-dark);color:var(--ink-txt);}
.btn-ghost:hover{background:rgba(255,255,255,0.08);border-color:rgba(255,255,255,0.25);}
.btn-block{width:100%;}
.btn-pulse{animation:btn-pulse 2.8s ease-in-out infinite;}
@keyframes btn-pulse{0%,100%{box-shadow:0 10px 28px -5px rgba(163,46,62,.5),0 0 0 0 rgba(163,46,62,.45)}50%{box-shadow:0 10px 28px -5px rgba(163,46,62,.5),0 0 0 14px rgba(163,46,62,0)}}
.btn svg,.nav-cta svg,.bb-btn svg{width:18px;height:18px;flex-shrink:0;transition:transform .35s var(--ease);}
.btn:hover svg{transform:translateX(4px);}

/* ---------- Badges Hero ---------- */
.hero-badges-group { display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px; }
.hero-badge-tag {
  display: inline-flex;align-items: center;gap: 6px;
  background: rgba(217, 160, 67, 0.12);border: 1px solid rgba(217, 160, 67, 0.3);
  color: var(--bronze);font-size: 0.78rem;font-weight: 700;padding: 6px 14px;border-radius: 20px;
  text-transform: uppercase;letter-spacing: 0.05em;backdrop-filter:blur(8px);
}
.hero-badge-tag svg{width:13px;height:13px;}
/* ---------- Captura no Pop-up (Exit-Intent) ---------- */
.hero-lead-form { display: flex; flex-direction: column; gap: 12px; max-width: 100%; }
.hero-input {
  width: 100%;background: rgba(11, 14, 20, 0.8);border: 1px solid var(--line-dark);
  border-radius: 12px;padding: 16px 20px;color: var(--ink-txt);font-family: var(--sans);
  font-size: .95rem;outline: none;transition: all .3s var(--ease);
}
.hero-input:focus { border-color: var(--bronze); box-shadow: 0 0 15px rgba(217,160,67,0.2); }
.hero-lead-success {
  display: none;background: rgba(74,222,128,0.1);border: 1px solid rgba(74,222,128,0.3);
  color: #4ADE80;padding: 16px 20px;border-radius: 12px;font-size: .95rem;font-weight: 600;text-align: center;
}
/* ---------- Modal Exit-Intent Pop-up ---------- */
.exit-modal {
  display: none;position: fixed;inset: 0;z-index: 10000;
  background: rgba(0, 0, 0, 0.85);backdrop-filter: blur(14px);
  align-items: center;justify-content: center;padding: 20px;
}
.exit-modal-content {
  background: var(--ink-2);border: 1px solid rgba(217, 160, 67, 0.4);border-radius: 24px;
  max-width: 480px;width: 100%;padding: 36px 30px;position: relative;
  box-shadow: var(--shadow-lg), 0 0 40px rgba(217, 160, 67, 0.15);
  animation: modalPop .5s var(--ease);
}
@keyframes modalPop {
  from { opacity: 0; transform: perspective(900px) rotateX(-14deg) scale(0.92) translateY(24px); }
  to { opacity: 1; transform: perspective(900px) rotateX(0) scale(1) translateY(0); }
}
.exit-modal-close {
  position: absolute;top: 16px;right: 16px;background: rgba(255,255,255,0.05);
  border: 1px solid var(--line-dark);color: var(--ink-muted);width: 32px;height: 32px;
  border-radius: 50%;cursor: pointer;display: flex;align-items: center;justify-content: center;transition: all .2s;
}
.exit-modal-close:hover { background: var(--wine); color: #fff; }

/* ---------- Hero Layout (mais curto e limpo) ---------- */
.hero{padding:64px 0 56px;position:relative;}
.hero-grid{display:grid;grid-template-columns:1.08fr .92fr;gap:60px;align-items:center;}
.hero h1{font-family:var(--serif);font-weight:600;font-size:clamp(2.5rem,5.2vw,4rem);line-height:1.08;letter-spacing:-.03em;margin-bottom:22px;}
.hero h1 i{font-style:italic;font-weight:400;}
.hero p{color:var(--ink-muted);font-size:1.12rem;max-width:540px;margin-bottom:24px;line-height:1.65;}
.hero-trust{display:flex;gap:20px;flex-wrap:wrap;font-family:var(--mono);font-size:.75rem;color:var(--ink-muted);letter-spacing:.02em;margin-top:20px;}
.hero-trust span{display:flex;align-items:center;gap:8px;}
.hero-trust svg{color:var(--bronze);width:15px;height:15px;}
.hero-link{color:var(--bronze);text-decoration:underline;text-underline-offset:3px;transition:color .3s;}
.hero-link:hover{color:#fff;}

/* Palco 3D do painel */
.hero-visual{position:relative;padding:26px 0;}
.tilt-3d{
  position:relative;transform-style:preserve-3d;
  transform:perspective(1100px) rotateX(var(--rx,0deg)) rotateY(var(--ry,0deg));
  transition:transform .3s ease-out;will-change:transform;
}
.tilt-3d.idle{animation:idle-float 7s ease-in-out infinite;}
@keyframes idle-float{0%,100%{transform:perspective(1100px) rotateX(3deg) rotateY(-5deg) translateY(0)}50%{transform:perspective(1100px) rotateX(-2deg) rotateY(5deg) translateY(-12px)}}
.prospectus{
  background:var(--paper);color:var(--paper-txt);border-radius:24px;padding:42px 36px;
  box-shadow:0 40px 80px -20px rgba(0,0,0,.8), 0 0 60px rgba(163,46,62,.18);position:relative;border:1px solid rgba(255,255,255,0.4);
  overflow:hidden;
}
.prospectus::before{content:"";position:absolute;inset:12px;border:1px solid rgba(20,16,12,0.12);border-radius:16px;pointer-events:none;}
.prospectus::after{content:"";position:absolute;inset:0;background:radial-gradient(circle at var(--mx,30%) var(--my,0%),rgba(255,255,255,.55),transparent 55%);mix-blend-mode:soft-light;pointer-events:none;opacity:.9;}
.prospectus-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:24px;font-family:var(--mono);font-size:.7rem;letter-spacing:.08em;text-transform:uppercase;color:var(--paper-muted);gap:10px;}
.live-dot{display:inline-flex;align-items:center;gap:6px;color:var(--wine);font-weight:700;white-space:nowrap;}
.live-dot i{width:7px;height:7px;border-radius:50%;background:var(--wine);display:inline-block;animation:pulse 1.6s infinite;}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.3;transform:scale(1.2)}}
.prospectus-serial{font-family:var(--serif);font-size:1.4rem;font-weight:600;margin-bottom:28px;letter-spacing:-.01em;}
.metric-row{display:flex;justify-content:space-between;align-items:flex-end;padding:18px 0;border-top:1px solid var(--line-paper);}
.metric-row:last-of-type{border-bottom:1px solid var(--line-paper);}
.metric-label{font-size:.8rem;color:var(--paper-muted);margin-bottom:4px;font-weight:500;}
.metric-value{font-family:var(--serif);font-size:1.65rem;font-weight:700;}
.metric-delta{font-family:var(--mono);font-size:.8rem;color:#15803D;font-weight:700;}
.spark{width:100%;height:64px;margin-top:14px;display:block;overflow:visible;}
.spark-line{fill:none;stroke:var(--wine);stroke-width:2.5;stroke-linecap:round;stroke-dasharray:520;stroke-dashoffset:520;animation:draw-line 2.6s var(--ease) .6s forwards;vector-effect:non-scaling-stroke;}
.spark-area{opacity:0;animation:fade-in 1.4s ease 1.6s forwards;}
.spark-dot{fill:var(--wine);opacity:0;animation:fade-in .5s ease 2.9s forwards;}
@keyframes draw-line{to{stroke-dashoffset:0}}
@keyframes fade-in{to{opacity:1}}
.prospectus-stamp{
  margin-top:20px;display:flex;justify-content:space-between;align-items:center;
  font-family:var(--mono);font-size:.7rem;color:var(--paper-muted);gap:10px;flex-wrap:wrap;
}
.prospectus-stamp b{color:var(--wine);font-weight:700;}
.panel-link{display:inline-flex;align-items:center;gap:6px;margin-top:14px;font-size:.8rem;font-weight:700;color:var(--wine);text-decoration:none;cursor:pointer;position:relative;z-index:2;}
.panel-link svg{width:14px;height:14px;transition:transform .3s var(--ease);}
.panel-link:hover svg{transform:translateX(4px);}
/* Chips flutuantes em profundidade */
.chip{
  position:absolute;z-index:3;display:inline-flex;align-items:center;gap:8px;
  background:rgba(11,14,20,.85);border:1px solid rgba(217,160,67,.4);color:var(--ink-txt);
  padding:9px 16px;border-radius:40px;font-size:.76rem;font-weight:700;backdrop-filter:blur(12px);
  box-shadow:0 18px 40px rgba(0,0,0,.55), 0 0 24px rgba(217,160,67,.15);white-space:nowrap;
}
.chip svg{width:15px;height:15px;color:var(--bronze);}
.chip-a{top:-8px;left:-34px;transform:translateZ(90px);animation:chip-float 6s ease-in-out infinite;}
.chip-b{bottom:-6px;right:-22px;transform:translateZ(110px);animation:chip-float 7s ease-in-out -2s infinite;}
@keyframes chip-float{0%,100%{translate:0 0}50%{translate:0 -10px}}

/* ---------- Stats ---------- */
.stats-strip{background:linear-gradient(180deg,rgba(11,14,20,.78),rgba(11,14,20,.92));backdrop-filter:blur(14px);border-top:1px solid var(--line-dark);border-bottom:1px solid var(--line-dark);padding:52px 0;}
.stats-strip::before{content:"";position:absolute;left:0;right:0;top:0;height:1px;background:linear-gradient(90deg,transparent,var(--bronze),transparent);opacity:.6;}
.stats-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:28px;text-align:center;}
.stat{position:relative;}
.stat b{display:block;font-family:var(--serif);font-size:2.6rem;font-weight:700;color:var(--paper);margin-bottom:4px;letter-spacing:-.02em;background:linear-gradient(180deg,#fff,#e6d3a8);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;font-variant-numeric:tabular-nums;}
.stat span{font-size:.8rem;color:var(--ink-muted);text-transform:uppercase;letter-spacing:.08em;font-weight:600;}

/* ---------- Cards 3D ---------- */
.section-pad{padding:96px 0;}
.grid-4{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:24px;}
.grid-3{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:26px;}
.grid-2{display:grid;grid-template-columns:repeat(auto-fit,minmax(330px,1fr));gap:28px;}
.card{
  background:linear-gradient(160deg,rgba(18,23,34,.75),rgba(11,14,20,.65));border:1px solid var(--line-dark);border-radius:20px;padding:36px 30px;
  transition:transform .35s var(--ease), border-color .4s, box-shadow .4s, background .4s;backdrop-filter:blur(12px);position:relative;overflow:hidden;
  transform:perspective(900px) rotateX(var(--rx,0deg)) rotateY(var(--ry,0deg)) translateY(var(--ty,0px));
}
.card::before{content:"";position:absolute;inset:0;background:radial-gradient(360px circle at var(--mx,50%) var(--my,50%),rgba(217,160,67,.14),transparent 45%);opacity:0;transition:opacity .35s;pointer-events:none;}
.card::after{content:"";position:absolute;left:0;top:0;height:2px;width:100%;background:linear-gradient(90deg,transparent,var(--bronze),transparent);transform:scaleX(0);transition:transform .6s var(--ease);}
.card:hover{--ty:-8px;border-color:rgba(163,46,62,0.5);box-shadow:var(--shadow-md), var(--shadow-glow);background:var(--ink-3);}
.card:hover::before{opacity:1;}
.card:hover::after{transform:scaleX(1);}
.card-icon{
  width:50px;height:50px;border-radius:14px;background:var(--wine-soft);border:1px solid rgba(163,46,62,0.3);
  display:flex;align-items:center;justify-content:center;color:#F4A2A9;margin-bottom:24px;transition:transform .5s var(--ease), background .3s;
  box-shadow:inset 0 1px 0 rgba(255,255,255,.12);
}
.card-icon svg{width:24px;height:24px;}
.card:hover .card-icon{transform:translateZ(30px) scale(1.12) rotate(-6deg);background:rgba(163,46,62,.3);}
.card h3{font-family:var(--serif);font-size:1.3rem;font-weight:600;margin-bottom:12px;letter-spacing:-.01em;}
.card p{color:var(--ink-muted);font-size:.95rem;line-height:1.7;}
.card .num{position:absolute;top:22px;right:26px;font-family:var(--serif);font-weight:700;font-size:2.6rem;line-height:1;color:rgba(255,255,255,.05);transition:color .4s;}
.card:hover .num{color:rgba(217,160,67,.22);}

/* ---------- Carousel Touch ---------- */
.carousel-wrap{max-width:720px;margin:0 auto;position:relative;}
.carousel-view{overflow:hidden;border-radius:24px;box-shadow:var(--shadow-lg), 0 0 60px rgba(163,46,62,.12);touch-action: pan-y;}
.carousel-track{display:flex;transition:transform .8s var(--ease);will-change: transform;}
.t-card{
  min-width:100%;background:var(--paper);color:var(--paper-txt);padding:54px 48px;text-align:center;box-sizing:border-box;
  position:relative;overflow:hidden;
}
.t-card::before{content:"";position:absolute;width:280px;height:280px;right:-90px;top:-90px;border-radius:50%;background:radial-gradient(circle,rgba(163,46,62,.14),transparent 70%);}
.t-card .quote-mark{font-family:var(--serif);font-size:4.6rem;color:var(--wine-soft);line-height:1;margin-bottom:0;}
.t-stars{display:flex;justify-content:center;gap:4px;margin-bottom:20px;color:var(--bronze);}
.t-stars svg{width:16px;height:16px;}
.t-text{font-family:var(--serif);font-size:1.35rem;font-style:italic;line-height:1.6;color:var(--paper-txt);margin-bottom:28px;position:relative;}
.t-author{font-weight:700;font-size:1rem;}
.t-role{font-size:.8rem;color:var(--paper-muted);font-family:var(--mono);margin-top:4px;font-weight:500;}
.carousel-nav{position:absolute;top:50%;transform:translateY(-50%);width:46px;height:46px;border-radius:50%;
  background:var(--ink-2);border:1px solid var(--line-dark);display:flex;align-items:center;justify-content:center;
  cursor:pointer;color:var(--ink-txt);transition:all .3s var(--ease);z-index:5;box-shadow:var(--shadow-md);}
.carousel-nav:hover{background:var(--wine);border-color:var(--wine);transform:translateY(-50%) scale(1.1);}
.carousel-nav.prev{left:-23px;}
.carousel-nav.next{right:-23px;}
.dots{display:flex;justify-content:center;gap:8px;margin-top:26px;}
.section-paper .dot{background:rgba(15,23,42,.18);}
.dot{width:10px;height:10px;border-radius:50%;background:rgba(255,255,255,0.2);cursor:pointer;transition:all .4s var(--ease);}
.dot.active,.section-paper .dot.active{width:30px;border-radius:10px;background:var(--wine);}

/* ---------- Pricing ---------- */
.pricing-wrap{max-width:620px;margin:0 auto;text-align:center;}
.pricing-card{
  color:var(--paper-txt);border-radius:26px;padding:54px 46px 44px;position:relative;
  box-shadow:var(--shadow-lg), 0 0 70px rgba(217,160,67,0.22);
  border:2px solid transparent;
  background:linear-gradient(var(--paper),var(--paper)) padding-box, conic-gradient(from var(--ang),var(--wine),var(--bronze),#fff3d6,var(--bronze),var(--wine)) border-box;
  animation:spin-ang 7s linear infinite;
  transform:perspective(1100px) rotateX(var(--rx,0deg)) rotateY(var(--ry,0deg));
  transition:transform .3s ease-out;
}
@keyframes spin-ang{to{--ang:360deg}}
.pricing-badge{
  position:absolute;top:-16px;left:50%;transform:translateX(-50%);
  background:linear-gradient(135deg, var(--wine), var(--wine-deep));color:#fff;font-size:.72rem;font-weight:800;letter-spacing:.1em;text-transform:uppercase;
  padding:8px 22px;border-radius:30px;box-shadow:0 8px 20px rgba(163,46,62,0.4);border:1px solid rgba(255,255,255,0.2);
}
.price-sub{color:var(--paper-muted);font-size:.98rem;margin-bottom:20px;font-weight:500;}
.price-line{display:flex;align-items:baseline;justify-content:center;gap:14px;margin-bottom:10px;}
.price-old{font-family:var(--mono);font-size:1.4rem;color:#94A3B8;text-decoration:line-through;}
.price-new{font-family:var(--serif);font-size:4.6rem;font-weight:800;letter-spacing:-.03em;background:linear-gradient(180deg,#6E1523,#A32E3E);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;}
.price-terms{font-size:.88rem;color:var(--paper-muted);margin-bottom:36px;}
.included-title{text-align:left;font-weight:800;font-size:.85rem;text-transform:uppercase;letter-spacing:.1em;margin-bottom:20px;color:var(--paper-txt);}
.included-list{list-style:none;text-align:left;margin-bottom:36px;}
.included-list li{display:flex;align-items:center;gap:14px;margin-bottom:16px;font-size:1rem;font-weight:600;}
.included-list li svg{color:#fff;background:var(--wine);border-radius:50%;padding:3px;width:22px;height:22px;flex-shrink:0;}
.reveal.visible .included-list li{animation:child-in .8s var(--ease) backwards;animation-delay:calc(var(--i,0) * 80ms + 300ms);}
.sec-badges{display:flex;justify-content:center;gap:22px;margin-top:24px;font-size:.8rem;color:var(--paper-muted);flex-wrap:wrap;font-weight:500;}
.sec-badges span{display:flex;align-items:center;gap:6px;}
.sec-badges svg{width:16px;height:16px;}

/* ---------- FAQ ---------- */
.faq-wrap{max-width:780px;margin:0 auto;}
.faq-item{background:rgba(11,14,20,.8);border:1px solid var(--line-dark);border-radius:14px;margin-bottom:12px;overflow:hidden;transition:all .4s var(--ease);backdrop-filter:blur(10px);}
.faq-item:hover{border-color:rgba(255,255,255,.18);}
.faq-item.active{border-color:rgba(163,46,62,0.6);box-shadow:0 8px 30px rgba(163,46,62,.18);background:var(--ink-3);}
.faq-q{padding:22px 26px;display:flex;justify-content:space-between;align-items:center;cursor:pointer;font-weight:600;font-size:1rem;min-height:48px;gap:14px;}
.faq-a{max-height:0;overflow:hidden;transition:max-height .5s var(--ease),padding .3s;padding:0 26px;color:var(--ink-muted);font-size:.95rem;line-height:1.7;}
.faq-item.active .faq-a{max-height:280px;padding:0 26px 22px;}
.faq-icon{transition:transform .4s var(--ease);flex-shrink:0;color:var(--bronze);width:19px;height:19px;}
.faq-item.active .faq-icon{transform:rotate(135deg);}

/* ---------- CTA Band ---------- */
.cta-band{
  background:linear-gradient(145deg, var(--wine-deep), #2A080E, #4a0f1a);background-size:200% 200%;animation:band-shift 12s ease-in-out infinite alternate;
  border-radius:26px;padding:76px 36px;text-align:center;
  position:relative;overflow:hidden;border:1px solid rgba(255,255,255,.12);
  box-shadow:var(--shadow-lg), var(--shadow-glow);
}
@keyframes band-shift{from{background-position:0% 0%}to{background-position:100% 100%}}
.cta-band::after{content:"";position:absolute;inset:0;background:radial-gradient(circle at 80% 0%, rgba(217,160,67,.24), transparent 60%);pointer-events:none;}
.cta-band::before{content:"";position:absolute;width:340px;height:340px;left:-120px;bottom:-160px;border-radius:50%;border:1px solid rgba(217,160,67,.25);box-shadow:0 0 0 40px rgba(217,160,67,.05),0 0 0 90px rgba(217,160,67,.03);animation:ring-spin 18s linear infinite;pointer-events:none;}
@keyframes ring-spin{to{transform:rotate(360deg) scale(1.05)}}
.cta-band h2{font-family:var(--serif);font-size:clamp(2rem,4.2vw,2.9rem);font-weight:600;margin-bottom:16px;position:relative;letter-spacing:-.025em;line-height:1.2;}
.cta-band h2 i{font-style:italic;color:var(--bronze);font-weight:400;}
.cta-band p{color:rgba(248,249,250,.8);max-width:580px;margin:0 auto 32px;position:relative;font-size:1.06rem;font-weight:400;}
.cta-band .btn{position:relative;z-index:2;}
.cta-band .guarantees{display:flex;justify-content:center;gap:24px;margin-top:28px;flex-wrap:wrap;font-family:var(--mono);font-size:.75rem;color:rgba(248,249,250,.65);position:relative;letter-spacing:.05em;}

/* ---------- Story ---------- */
.story{display:grid;grid-template-columns:360px 1fr;gap:60px;align-items:center;max-width:1080px;margin:0 auto;}
.story-frame{position:relative;border-radius:22px;overflow:hidden;box-shadow:var(--shadow-lg), 0 0 50px rgba(217,160,67,.12);border:1px solid var(--line-dark);background:var(--ink-2);}
.story-frame img{width:100%;height:440px;object-fit:cover;object-position:center;transition:transform .8s var(--ease);}
.story-frame:hover img{transform:scale(1.06);}
.story-frame::after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,transparent 60%,rgba(5,7,10,.6));pointer-events:none;}
.story-frame-wrap{position:relative;}
.story-frame-wrap::before{content:"";position:absolute;inset:-14px 14px 14px -14px;border:1px solid rgba(217,160,67,.35);border-radius:24px;z-index:-1;}
.story h3{font-family:var(--serif);font-weight:600;font-size:2.1rem;letter-spacing:-.02em;margin-bottom:18px;}
.story p{color:var(--ink-muted);margin-bottom:16px;line-height:1.75;font-size:1rem;}
.story-sign{font-family:var(--serif);font-style:italic;font-size:1.1rem;color:var(--paper);margin-top:10px;font-weight:500;}

/* ---------- Paper Section ---------- */
.section-paper{background:var(--paper);color:var(--paper-txt);position:relative;overflow:hidden;}
.section-paper::after{content:"";position:absolute;width:520px;height:520px;right:-160px;top:-180px;border-radius:50%;background:radial-gradient(circle,rgba(163,46,62,.12),transparent 70%);pointer-events:none;}
.section-paper .eyebrow{color:var(--wine);}
.section-paper .eyebrow::before{background:var(--wine);}
.section-paper .section-title{color:var(--paper-txt);}
.section-paper .section-sub{color:var(--paper-muted);}
.section-paper .card{background:#ffffff;border-color:var(--line-paper);box-shadow:0 10px 30px rgba(0,0,0,0.03);}
.section-paper .card:hover{background:#ffffff;border-color:var(--wine);box-shadow:0 20px 40px rgba(163,46,62,0.12);}
.section-paper .card h3{color:var(--paper-txt);}
.section-paper .card p{color:var(--paper-muted);}
.section-paper .card-icon{background:var(--wine-soft);color:var(--wine);}

/* ---------- Feature Rows ---------- */
.feat-row{display:flex;align-items:flex-start;gap:18px;background:rgba(11, 14, 20, 0.65);border:1px solid var(--line-dark);border-radius:16px;padding:24px;backdrop-filter:blur(12px);transition:transform .35s var(--ease),border-color .3s,box-shadow .3s;
  transform:perspective(900px) rotateX(var(--rx,0deg)) rotateY(var(--ry,0deg)) translateY(var(--ty,0px));}
.feat-row:hover{--ty:-4px;border-color:rgba(217,160,67,0.45);box-shadow:0 16px 36px rgba(0,0,0,.4);}
.feat-row .ic{width:44px;height:44px;border-radius:11px;background:var(--bronze-soft);color:var(--bronze);display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:transform .5s var(--ease);}
.feat-row:hover .ic{transform:rotateY(180deg);}
.feat-row .ic svg{width:22px;height:22px;}
.feat-row h4{font-size:.98rem;font-weight:700;margin-bottom:4px;}
.feat-row p{font-size:.86rem;color:var(--ink-muted);}

/* ============================================================
   ABA EDUCAÇÃO — SIMULADOR
============================================================ */
.sim-stage{
  display:grid;grid-template-columns:.85fr 1.15fr;gap:0;max-width:1080px;margin:0 auto 70px;
  border-radius:28px;overflow:hidden;border:1px solid rgba(217,160,67,.28);
  box-shadow:var(--shadow-lg), 0 0 70px rgba(217,160,67,.10);
  background:rgba(11,14,20,.72);backdrop-filter:blur(16px);position:relative;
}
.sim-controls-panel{padding:44px 38px;border-right:1px solid var(--line-dark);background:linear-gradient(160deg,rgba(163,46,62,.12),transparent 60%);}
.sim-controls-panel h3{font-family:var(--serif);font-size:1.5rem;font-weight:600;margin-bottom:6px;letter-spacing:-.01em;}
.sim-controls-panel .lead{color:var(--ink-muted);font-size:.9rem;margin-bottom:28px;}
.sim-field{margin-bottom:26px;}
.sim-field label{display:flex;justify-content:space-between;align-items:center;font-size:.82rem;font-weight:700;color:var(--ink-txt);margin-bottom:10px;}
.sim-field label small{font-family:var(--mono);font-weight:400;color:var(--ink-muted);font-size:.7rem;}
.sim-num{
  width:100%;background:rgba(5,7,10,.7);border:1px solid var(--line-dark);border-radius:12px;padding:13px 16px;
  color:var(--ink-txt);font-family:var(--mono);font-size:1rem;outline:none;transition:border-color .3s, box-shadow .3s;min-height:46px;
}
.sim-num:focus{border-color:var(--bronze);box-shadow:0 0 16px rgba(217,160,67,.22);}
input[type=range].sim-range{-webkit-appearance:none;appearance:none;width:100%;height:6px;border-radius:6px;margin-top:14px;outline:none;cursor:pointer;
  background:linear-gradient(90deg,var(--bronze) var(--fill,20%),rgba(255,255,255,.12) var(--fill,20%));}
input[type=range].sim-range::-webkit-slider-thumb{-webkit-appearance:none;width:22px;height:22px;border-radius:50%;background:radial-gradient(circle at 35% 30%,#fff3d6,#D9A043 55%,#8a5a12);border:2px solid #fff;box-shadow:0 4px 12px rgba(0,0,0,.6),0 0 0 6px rgba(217,160,67,.18);transition:transform .2s;}
input[type=range].sim-range::-webkit-slider-thumb:hover{transform:scale(1.15);}
input[type=range].sim-range::-moz-range-thumb{width:20px;height:20px;border-radius:50%;background:#D9A043;border:2px solid #fff;box-shadow:0 4px 12px rgba(0,0,0,.6);}
.sim-note{font-size:.72rem;color:var(--ink-muted);line-height:1.5;margin-top:6px;font-family:var(--mono);}
.sim-result-panel{padding:44px 38px;display:flex;flex-direction:column;position:relative;}
.sim-result-label{font-size:.82rem;color:var(--ink-muted);font-weight:600;margin-bottom:6px;}
.sim-result-total{font-family:var(--serif);font-weight:700;font-size:clamp(2.2rem,5vw,3.5rem);letter-spacing:-.03em;line-height:1.05;background:linear-gradient(100deg,#fff,#D9A043);-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;font-variant-numeric:tabular-nums;}
.sim-delta{display:inline-block;margin-top:8px;font-family:var(--mono);font-size:.8rem;font-weight:700;color:#4ADE80;}
.sim-breakdown{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin:24px 0 8px;}
.sim-mini{background:rgba(255,255,255,.04);border:1px solid var(--line-dark);border-radius:14px;padding:14px 16px;}
.sim-mini span{display:block;font-size:.72rem;color:var(--ink-muted);font-weight:600;margin-bottom:2px;}
.sim-mini b{font-family:var(--serif);font-size:1.2rem;font-variant-numeric:tabular-nums;}
.sim-mini.gain b{color:#4ADE80;}
.sim-chart{width:100%;height:auto;margin-top:auto;display:block;overflow:visible;}
.sim-legend{display:flex;gap:18px;font-size:.72rem;color:var(--ink-muted);margin-top:10px;font-family:var(--mono);}
.sim-legend i{display:inline-block;width:14px;height:3px;border-radius:2px;margin-right:6px;vertical-align:middle;}
.sim-cta{margin-top:22px;}

/* ---------- Bottom Bar ---------- */
.bottom-bar{
  position:fixed;bottom:0;left:0;right:0;z-index:999;
  background:rgba(5, 7, 10, 0.86);backdrop-filter:blur(18px);-webkit-backdrop-filter:blur(18px);
  border-top:1px solid var(--line-dark);
  padding:14px 6%;display:flex;justify-content:space-between;align-items:center;gap:16px;
  box-shadow:0 -10px 25px rgba(0,0,0,0.5);transition:transform .6s var(--ease);
}
.bb-label{font-family:var(--mono);font-size:.7rem;color:var(--ink-muted);text-transform:uppercase;letter-spacing:.08em;}
.bb-price{font-family:var(--serif);font-size:1.38rem;font-weight:700;}
.bb-price s{font-family:var(--mono);font-size:.85rem;color:#64748B;font-weight:400;margin-right:8px;}
.bb-btn{background:linear-gradient(135deg, var(--wine), var(--wine-deep));color:#fff;padding:12px 24px;border-radius:10px;font-weight:700;font-size:.88rem;text-decoration:none;display:inline-flex;align-items:center;gap:8px;transition:all .3s var(--ease);white-space:nowrap;box-shadow:0 4px 15px rgba(163,46,62,0.3);animation:btn-pulse 2.8s ease-in-out infinite;}
.bb-btn:hover{transform:translateY(-2px);box-shadow:0 8px 20px rgba(163,46,62,0.5);filter:brightness(1.1);}

/* ---------- Footer ---------- */
footer{background:#020304;border-top:1px solid var(--line-dark);padding:72px 6% 36px;margin-top:100px;}
footer::before{content:"";position:absolute;left:0;right:0;top:0;height:1px;background:linear-gradient(90deg,transparent,var(--wine),var(--bronze),var(--wine),transparent);}
.footer-grid{display:flex;flex-wrap:wrap;justify-content:space-between;gap:48px;margin-bottom:48px;}
.footer-col h4{font-size:.78rem;text-transform:uppercase;letter-spacing:.12em;color:var(--ink-muted);margin-bottom:18px;font-weight:700;}
.footer-col ul{list-style:none;}
.footer-col ul li{margin-bottom:12px;}
.footer-col ul li a{color:var(--ink-muted);text-decoration:none;font-size:.9rem;cursor:pointer;transition:color .2s, padding .3s var(--ease);font-weight:500;}
.footer-col ul li a:hover{color:var(--paper);padding-left:4px;}
.footer-brand p{color:var(--ink-muted);font-size:.9rem;max-width:290px;margin-top:16px;line-height:1.65;}
.footer-socials{display:flex;gap:12px;}
.footer-socials a{width:40px;height:40px;border-radius:10px;border:1px solid var(--line-dark);display:flex;align-items:center;justify-content:center;color:var(--ink-muted);text-decoration:none;transition:all .3s var(--ease);background:rgba(255,255,255,0.02);}
.footer-socials a svg{width:18px;height:18px;}
.footer-socials a:hover{background:var(--wine);border-color:var(--wine);color:#fff;transform:translateY(-3px) rotate(-4deg);}
.footer-bottom{border-top:1px solid var(--line-dark);padding-top:28px;display:flex;justify-content:space-between;flex-wrap:wrap;gap:14px;font-size:.8rem;color:var(--ink-muted);}
/* Modal Legal Flutuante */
.legal-modal {
  display:none; position:fixed; inset:0; z-index:9999;
  background:rgba(0,0,0,0.85); backdrop-filter:blur(12px);
  align-items:center; justify-content:center; padding:20px;
}
.legal-modal-content {
  background:var(--ink-2); border:1px solid var(--line-dark);
  border-radius:20px; max-width:650px; width:100%; max-height:80vh;
  overflow-y:auto; padding:32px; color:var(--ink-txt); position:relative;
  animation:modalPop .5s var(--ease);
}
.legal-modal-close {
  position:absolute; top:20px; right:20px; background:none;
  border:none; color:var(--ink-muted); cursor:pointer; font-size:1.2rem; padding:6px;
}

/* ---------- Responsive ---------- */
@media (max-width:980px){
  .hero-grid{grid-template-columns:1fr;gap:50px;}
  .story{grid-template-columns:1fr;text-align:left;}
  .story-frame img{height:340px;}
  .sim-stage{grid-template-columns:1fr;}
  .sim-controls-panel{border-right:none;border-bottom:1px solid var(--line-dark);}
  .chip-a{left:-6px;}
  .chip-b{right:-6px;}
}
@media (max-width:860px){ .nav-links{display:none;} }
@media (max-width:768px){
  body{padding-bottom:92px;}
  .wrap{padding:0 5%;}
  nav{padding:14px 5%;justify-content:space-between;}
  .brand-word{font-size:1.15rem;}
  .nav-cta{display:none;}
  .hero{padding:36px 0 26px;}
  .hero h1{font-size:2.2rem;}
  .hero p{font-size:1rem;}
  .prospectus{padding:28px 22px;}
  .metric-value{font-size:1.4rem;}
  .stats-strip{padding:36px 0;}
  .stats-grid{grid-template-columns:repeat(2,1fr);gap:22px;}
  .stat b{font-size:2rem;}
  .section-pad{padding:60px 0;}
  .grid-4, .grid-3, .grid-2{grid-template-columns:1fr;gap:18px;}
  .t-card{padding:36px 24px;}
  .t-text{font-size:1.1rem;}
  .carousel-nav{display:none;}
  .price-new{font-size:3.5rem;}
  .pricing-card{padding:36px 22px 28px;}
  .cta-band{padding:46px 24px;}
  .cta-band h2{font-size:1.85rem;}
  .faq-q{padding:18px 20px;font-size:.95rem;}
  .faq-a{padding:0 20px;}
  .faq-item.active .faq-a{padding:0 20px 18px;}
  .bottom-bar{padding:12px 5%;}
  .bb-price{font-size:1.2rem;}
  .bb-btn{padding:10px 18px;font-size:.82rem;}
  footer{padding:48px 5% 28px;margin-top:60px;}
  .footer-grid{gap:32px;}
  .footer-bottom{flex-direction:column;gap:10px;}
  .mobile-nav{padding:96px 6% 90px;}
  .mobile-nav a.menu-link .sub{display:none;}
  .sim-controls-panel,.sim-result-panel{padding:30px 22px;}
  .chip{font-size:.7rem;padding:7px 12px;}
  #bg3d{opacity:.6;}
}
@media (prefers-reduced-motion: reduce){
  *,*::before,*::after{animation-duration:.01ms !important;animation-iteration-count:1 !important;transition-duration:.01ms !important;scroll-behavior:auto !important;}
  .reveal,.wi{opacity:1 !important;transform:none !important;}
  .spark-line{stroke-dashoffset:0;}
  .spark-area,.spark-dot{opacity:1;}
}

/* ============================================================
   SUAVIDADE E DESEMPENHO — mesmo visual 3D, menos custo de GPU/CPU
============================================================ */
.aurora i{filter:none;}
.card,.feat-row,.faq-item,.stats-strip,.sim-stage,.hero-badge-tag,.chip,.mobile-nav,.exit-modal,.legal-modal{backdrop-filter:none;-webkit-backdrop-filter:none;}
nav{backdrop-filter:blur(10px) saturate(130%);-webkit-backdrop-filter:blur(10px) saturate(130%);}
.bottom-bar{backdrop-filter:blur(10px);-webkit-backdrop-filter:blur(10px);}
.card{background:linear-gradient(160deg,rgba(18,23,34,.92),rgba(11,14,20,.88));}
.feat-row{background:rgba(11,14,20,.86);}
.faq-item{background:rgba(11,14,20,.92);}
.stats-strip{background:linear-gradient(180deg,rgba(11,14,20,.92),rgba(11,14,20,.97));}
.sim-stage{background:rgba(11,14,20,.92);}
.chip{background:rgba(11,14,20,.95);}
.exit-modal,.legal-modal{background:rgba(0,0,0,.9);}
.reveal{will-change:auto;transform:translate3d(0,26px,0);}
.reveal.visible{transform:translate3d(0,0,0);}
.frx-off,.frx-off::before,.frx-off::after{animation-play-state:paused !important;}
html.perf-medium .aurora i,html.perf-medium .pricing-card,html.perf-medium .cta-band{animation:none !important;}
html.perf-low .aurora i,html.perf-low .btn-pulse,html.perf-low .bb-btn,html.perf-low .tilt-3d.idle,html.perf-low .chip,html.perf-low .live-dot i,html.perf-low .cta-band,html.perf-low .pricing-card,html.perf-low .nav-cta::after{animation:none !important;}
html.perf-low .cursor-glow{display:none;}
html.perf-low #bg3d{opacity:.55;}

/* Acessibilidade e formulário de lead */
.skip-link{position:fixed;left:12px;top:-60px;z-index:20000;background:var(--wine);color:#fff;padding:10px 16px;border-radius:10px;font-weight:700;text-decoration:none;transition:top .2s;}
.skip-link:focus{top:12px;}
.hero-consent{display:flex;gap:10px;align-items:flex-start;font-size:.78rem;line-height:1.45;color:var(--ink-muted);text-align:left;}
.hero-consent input{margin-top:3px;width:18px;height:18px;flex:none;accent-color:var(--wine);}
.hero-consent a{color:var(--bronze);}
.hp-field{position:absolute;left:-9999px;width:1px;height:1px;overflow:hidden;}
.hero-lead-error{display:none;color:#ff9a9a;font-size:.82rem;margin-top:10px;}
.hero-lead-error.show{display:block;}
.cta-checkout[aria-disabled="true"]{opacity:.5;pointer-events:none;}
noscript .ns-box{position:fixed;left:0;right:0;top:0;z-index:99999;background:#6E1523;color:#fff;padding:12px 16px;text-align:center;font:600 14px system-ui;}

/* ---------- Tela de erro / 404 interna (sem dados técnicos para o visitante) ---------- */
#erro{min-height:calc(100vh - 140px);}
.er-stage{display:grid;grid-template-columns:1.05fr .95fr;gap:40px;align-items:center;padding-top:70px;padding-bottom:40px;}
.er-copy h1{font:500 clamp(2.3rem,5.4vw,3.9rem)/1.04 var(--serif);letter-spacing:-.02em;margin-bottom:18px;}
.er-copy h1 span{display:block;color:var(--ink-muted);font-style:italic;font-weight:400;}
.er-copy p.er-lead{color:#c3cbd6;font-size:1.05rem;max-width:46ch;margin-bottom:26px;}
.er-actions{display:flex;flex-wrap:wrap;gap:12px;}
.er-ref{margin-top:22px;font:400 .76rem var(--mono);color:var(--ink-muted);}
.er-coin-wrap{position:relative;justify-self:center;width:min(380px,74vw);aspect-ratio:1;perspective:1100px;display:grid;place-items:center;}
.er-coin{--th:15px;position:relative;width:76%;aspect-ratio:1;transform-style:preserve-3d;transform:rotateX(8deg);}
.er-bob,.er-swing{position:absolute;inset:0;transform-style:preserve-3d;}
.er-bob{animation:er-bob 3.5s ease-in-out infinite alternate;}
.er-swing{animation:er-swing 7s ease-in-out infinite alternate;}
@keyframes er-swing{from{transform:rotateY(-36deg)}to{transform:rotateY(36deg)}}
@keyframes er-bob{from{transform:translateY(-5px)}to{transform:translateY(7px)}}
.er-slab,.er-face{position:absolute;inset:0;border-radius:50%;}
.er-slab{background:conic-gradient(from 20deg,#8a5a12,#e6b458,#a8731d,#f3ce82,#8a5a12,#d9a043,#a8731d,#8a5a12);}
.er-face{display:grid;place-items:center;backface-visibility:hidden;background:radial-gradient(circle at 32% 26%,#fbe3a6 0%,transparent 42%),conic-gradient(from 200deg,#c48a25,#f6d488,#b47a1c,#ecc167,#c48a25);box-shadow:inset 0 0 0 9px rgba(120,76,10,.55),inset 0 0 0 11px rgba(255,232,170,.55),inset 0 0 0 26px rgba(120,76,10,.16),inset 0 0 40px rgba(90,52,4,.5);}
.er-front{transform:translateZ(calc(var(--th) + 1px));}
.er-back{transform:rotateY(180deg) translateZ(calc(var(--th) + 1px));}
.er-face b{font:800 clamp(2.6rem,9.6vw,4.6rem)/1 var(--serif);letter-spacing:-.03em;color:#6b430c;text-shadow:0 1.5px 0 rgba(255,238,196,.85),0 -1px 0 rgba(60,32,0,.4);}
.er-shadow{position:absolute;left:18%;right:18%;bottom:6%;height:7%;border-radius:50%;background:radial-gradient(closest-side,rgba(0,0,0,.65),transparent);animation:er-sh 3.5s ease-in-out infinite alternate;}
@keyframes er-sh{from{transform:scaleX(1.05);opacity:.9}to{transform:scaleX(.86);opacity:.6}}
html.perf-low .er-bob,html.perf-low .er-swing,html.perf-low .er-shadow{animation:none;}
@media (prefers-reduced-motion:reduce){.er-bob,.er-swing,.er-shadow{animation:none}.er-swing{transform:rotateY(-22deg)}}
@media (max-width:860px){.er-stage{grid-template-columns:1fr;gap:6px;padding-top:30px;}.er-coin-wrap{order:-1;width:min(250px,64vw);}.er-actions .btn{flex:1 1 200px;}}
</style>
</head>
<body>
<noscript><div class="ns-box">Este site precisa de JavaScript para funcionar. Ative-o no navegador ou fale com a gente: finrendax@gmail.com</div></noscript>
<a class="skip-link" href="#main">Pular para o conteúdo</a>
<!-- CAMADAS DE FUNDO -->
<canvas id="bg3d" aria-hidden="true"></canvas>
<div class="aurora" aria-hidden="true"><i></i><i></i><i></i></div>
<div class="cursor-glow" id="cursorGlow" aria-hidden="true"></div>
<div class="scroll-progress" id="scrollProgress" aria-hidden="true"></div>

<!-- NAV -->
<nav id="mainNav">
  <a href="#" class="brand" onclick="showTab('recursos'); return false;">
    <span class="brand-mark">F</span>
    <span class="brand-word">FinRend<em>ax</em></span>
  </a>
  <ul class="nav-links">
    <li><a id="nav-recursos" class="active" onclick="showTab('recursos')"><span class="idx">§01</span>Recursos</a></li>
    <li><a id="nav-quem-somos" onclick="showTab('quem-somos')"><span class="idx">§02</span>Quem Somos</a></li>
    <li><a id="nav-servicos" onclick="showTab('servicos')"><span class="idx">§03</span>Serviços</a></li>
    <li><a id="nav-educacao" onclick="showTab('educacao')"><span class="idx">§04</span>Educação</a></li>
  </ul>
  <div class="nav-right">
    <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="nav-cta cta-checkout btn-icon-only" aria-label="Garantir acesso">
      <i data-lucide="arrow-right" size="18"></i>
    </a>
    <button class="menu-toggle" id="menuToggle" aria-label="Abrir Menu de Navegação" aria-expanded="false" aria-controls="mobileNav">
      <span class="burger"><span></span><span></span><span></span></span>
    </button>
  </div>
</nav>

<!-- MENU HAMBÚRGUER EM TELA CHEIA -->
<div class="mobile-nav" id="mobileNav">
  <div class="menu-inner">
    <div class="menu-kicker">Navegação</div>
    <a id="mob-recursos" class="menu-link active" style="--i:0" onclick="showTab('recursos')"><span class="idx">§01</span>Recursos<span class="sub">Início</span><span class="arr"><i data-lucide="arrow-right"></i></span></a>
    <a id="mob-quem-somos" class="menu-link" style="--i:1" onclick="showTab('quem-somos')"><span class="idx">§02</span>Quem Somos<span class="sub">Nossa história e missão</span><span class="arr"><i data-lucide="arrow-right"></i></span></a>
    <a id="mob-servicos" class="menu-link" style="--i:2" onclick="showTab('servicos')"><span class="idx">§03</span>Serviços<span class="sub">Ferramentas e conteúdos</span><span class="arr"><i data-lucide="arrow-right"></i></span></a>
    <a id="mob-educacao" class="menu-link" style="--i:3" onclick="showTab('educacao')"><span class="idx">§04</span>Educação<span class="sub">Simulador e aprendizado</span><span class="arr"><i data-lucide="arrow-right"></i></span></a>
    <div class="menu-foot">
      <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-bronze cta-checkout">
        Garantir acesso por R$ 27 <i data-lucide="arrow-right" size="16"></i>
      </a>
      <span class="mail">finrendax@gmail.com</span>
    </div>
  </div>
</div>

<!-- TELA DE ERRO / 404 (interna: nenhuma informação técnica é mostrada ao visitante) -->
<div id="erro" class="page-section" role="alert">
  <div class="wrap er-stage">
    <div class="er-copy">
      <h1 id="erTitle">Essa página não rendeu.<span>Mas o seu dinheiro pode.</span></h1>
      <p class="er-lead" id="erLead">O endereço que você abriu não existe ou mudou de lugar. Nada de errado com você nem com a sua compra, só com o caminho.</p>
      <div class="er-actions">
        <a href="#" class="btn btn-wine" onclick="leaveError(); return false;">Voltar ao início</a>
        <a href="mailto:finrendax@gmail.com" id="erMail" class="btn btn-ghost" style="border:1px solid rgba(255,255,255,.2);color:var(--ink-txt);background:transparent;">Falar com a gente</a>
      </div>
      <p class="er-ref" id="erRef"></p>
    </div>
    <div class="er-coin-wrap" aria-hidden="true">
      <div class="er-coin"><div class="er-bob"><div class="er-swing" id="erSwing">
        <div class="er-face er-front"><b id="erCode">404</b></div>
        <div class="er-face er-back"><b>F</b></div>
      </div></div></div>
      <div class="er-shadow"></div>
    </div>
  </div>
</div>

<span id="main" tabindex="-1"></span>
<!-- ABA 1 — RECURSOS -->
<div id="recursos" class="page-section active">
  <section class="hero">
    <div class="wrap hero-grid">
      <div class="reveal visible">
        <div class="hero-badges-group">
          <span class="hero-badge-tag"><i data-lucide="zap" size="13"></i> Acesso Vitalício</span>
          <span class="hero-badge-tag"><i data-lucide="check-circle" size="13"></i> Sem Assinaturas</span>
        </div>
        <h1>Domine suas finanças com <i>método</i>, não com sorte.</h1>
        <p>Organize seu dinheiro, elimine dívidas e aprenda a construir uma renda extra real com nossa metodologia prática de aplicação imediata.</p>

        <!-- BOTAO DE COMPRA DIRETA NA HERO -->
        <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-wine btn-pulse cta-checkout" style="font-size:1.1rem; padding:18px 36px; margin-bottom:15px; width:100%; max-width:420px;">
          Garantir Acesso Vitalício por R$ 27 <i data-lucide="arrow-right" size="18"></i>
        </a>

        <div class="hero-trust">
          <span><i data-lucide="shield-check"></i> Pagamento 100% seguro</span>
          <span><i data-lucide="rotate-ccw"></i> 7 dias de garantia</span>
        </div>
      </div>

      <!-- EXTRATO 3D -->
      <div class="hero-visual reveal">
        <div class="tilt-3d idle" data-tilt-stage="8">
          <div class="chip chip-a"><i data-lucide="shield-check"></i> Pagamento 100% seguro</div>
          <div class="prospectus">
            <div class="prospectus-top">
              <span>Extrato · Plataforma FinRendax</span>
              <span class="live-dot"><i></i> em tempo real</span>
            </div>
            <div class="prospectus-serial">Painel do Aluno</div>
            <div class="metric-row">
              <div>
                <div class="metric-label">Renda extra construída no mês</div>
                <div class="metric-value" id="calcIncome">R$ 3.771,14</div>
              </div>
              <div class="metric-delta" id="calcDelta">↑ 24%</div>
            </div>
            <div class="metric-row">
              <div>
                <div class="metric-label">Módulos concluídos</div>
                <div class="metric-value">6 de 8</div>
              </div>
              <div class="metric-delta">↑ progresso</div>
            </div>
            <svg class="spark" viewBox="0 0 300 64" preserveAspectRatio="none" aria-hidden="true">
              <defs><linearGradient id="spg" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#A32E3E" stop-opacity=".32"/><stop offset="1" stop-color="#A32E3E" stop-opacity="0"/></linearGradient></defs>
              <path class="spark-area" fill="url(#spg)" d="M0 56 C30 52 50 54 80 42 S130 38 160 28 S220 20 250 11 S285 7 300 4 L300 64 L0 64Z"/>
              <path class="spark-line" d="M0 56 C30 52 50 54 80 42 S130 38 160 28 S220 20 250 11 S285 7 300 4"/>
              <circle class="spark-dot" cx="299" cy="4" r="3.5"/>
            </svg>
            <div class="prospectus-stamp">
              <span>Acesso <b>vitalício</b></span>
              <span>Emitido para: Aluno FinRendax</span>
            </div>
            <a class="panel-link" onclick="showTab('educacao')">Testar o simulador de investimentos <i data-lucide="arrow-right"></i></a>
          </div>
          <div class="chip chip-b"><i data-lucide="rotate-ccw"></i> 7 dias de garantia</div>
        </div>
      </div>
    </div>
  </section>

  <section class="stats-strip">
    <div class="wrap stats-grid reveal">
      <div class="stat"><b data-count="4.8" data-dec="1" data-suf="/5">4,8/5</b><span>Avaliação média</span></div>
      <div class="stat"><b data-count="10">10</b><span>Módulos exclusivos</span></div>
      <div class="stat"><b data-count="20">20</b><span>Videoaulas práticas</span></div>
      <div class="stat"><b>Vitalício</b><span>Acesso permanente</span></div>
    </div>
  </section>

  <section class="section-pad">
    <div class="wrap">
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Diagnóstico</div>
        <h2 class="section-title">Nós sabemos como é</h2>
        <p class="section-sub">Estes são os desafios que mais ouvimos — e exatamente como ajudamos você a superar cada um.</p>
      </div>
      <div class="grid-4 reveal">
        <div class="card">
          <div class="card-icon"><i data-lucide="book-open"></i></div>
          <h3>Não sabe por onde começar</h3>
          <p>Ninguém te ensinou sobre dinheiro na escola. Começamos do absoluto zero, sem termos complicados e no seu ritmo.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="wallet"></i></div>
          <h3>O salário acaba antes do mês</h3>
          <p>Aprenda a organizar gastos, cortar o que pesa e fazer sobrar dinheiro todo mês — sem sofrimento.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="line-chart"></i></div>
          <h3>Quer investir, mas tem receio</h3>
          <p>O mercado parece outro mundo. Mostramos o caminho para investir com segurança e confiança, sem complicações.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="trending-up"></i></div>
          <h3>Em busca de renda extra</h3>
          <p>Descubra formas reais de ganhar além do salário e dar o primeiro passo rumo à sua independência.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="section-pad section-paper grain" style="position:relative;">
    <div class="wrap" style="position:relative;">
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Prova social</div>
        <h2 class="section-title">Quem já mudou de patamar</h2>
        <p class="section-sub">Histórias reais de alunos que decidiram sair do zero e agir.</p>
      </div>
      <div class="carousel-wrap reveal" id="testimonialSlider">
        <button class="carousel-nav prev" onclick="prevSlide()" aria-label="Depoimento anterior"><i data-lucide="chevron-left"></i></button>
        <button class="carousel-nav next" onclick="nextSlide()" aria-label="Próximo depoimento"><i data-lucide="chevron-right"></i></button>
        <div class="carousel-view">
          <div class="carousel-track" id="carouselTrack">
            <div class="t-card">
              <div class="quote-mark">&ldquo;</div>
              <div class="t-stars">
                <i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i>
              </div>
              <p class="t-text">Eu achava que investir era só para quem já tinha muito dinheiro. Com o FinRendax organizei minhas dívidas e fiz meus primeiros investimentos em menos de um mês.</p>
              <div class="t-author">Mariana Costa</div>
              <div class="t-role">Aluna FinRendax</div>
            </div>
            <div class="t-card">
              <div class="quote-mark">&ldquo;</div>
              <div class="t-stars">
                <i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="none" stroke="#D9A043" size="16"></i>
              </div>
              <p class="t-text">O módulo de Renda Extra me ensinou formas reais de monetizar meu tempo livre. Já no primeiro mês comecei a ter um dinheiro extra todo mês.</p>
              <div class="t-author">Rafael Oliveira</div>
              <div class="t-role">Aluno FinRendax</div>
            </div>
            <div class="t-card">
              <div class="quote-mark">&ldquo;</div>
              <div class="t-stars">
                <i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i>
              </div>
              <p class="t-text">As planilhas e aulas são extremamente didáticas. Ninguém complica nada. Foi o melhor investimento que fiz em mim mesma neste ano.</p>
              <div class="t-author">Camila Silva</div>
              <div class="t-role">Aluna FinRendax</div>
            </div>
            <div class="t-card">
              <div class="quote-mark">&ldquo;</div>
              <div class="t-stars">
                <i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i>
              </div>
              <p class="t-text">Consegui finalmente montar minha reserva de emergência e sair do zero. A metodologia é direta e fácil de acompanhar no dia a dia.</p>
              <div class="t-author">Lucas Mendes</div>
              <div class="t-role">Aluno FinRendax</div>
            </div>
            <div class="t-card">
              <div class="quote-mark">&ldquo;</div>
              <div class="t-stars">
                <i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="#D9A043" size="16"></i><i data-lucide="star" fill="none" stroke="#D9A043" size="16"></i>
              </div>
              <p class="t-text">Sempre tive medo de taxas e investimentos errados. A plataforma me deu a clareza e a segurança que eu precisava para fazer o dinheiro trabalhar para mim.</p>
              <div class="t-author">Beatriz Rocha</div>
              <div class="t-role">Aluna FinRendax</div>
            </div>
          </div>
        </div>
        <div class="dots" id="dotsContainer">
          <div class="dot active" onclick="goToSlide(0)"></div>
          <div class="dot" onclick="goToSlide(1)"></div>
          <div class="dot" onclick="goToSlide(2)"></div>
          <div class="dot" onclick="goToSlide(3)"></div>
          <div class="dot" onclick="goToSlide(4)"></div>
        </div>
      </div>
      <p style="text-align:center; font-size:0.78rem; color:var(--ink-muted); max-width:560px; margin:18px auto 0;">Depoimentos de alunos reais, usados com autorização. Resultados individuais variam de pessoa para pessoa e dependem de esforço, contexto e disciplina — não representam garantia nem média típica de resultado.</p>
    </div>
  </section>

  <section class="section-pad" id="oferta">
    <div class="wrap pricing-wrap reveal">
      <div class="eyebrow" style="justify-content:center;color:#D9A043;">Oferta por tempo limitado</div>
      <h2 class="section-title">Preço de lançamento exclusivo</h2>
      <p class="section-sub" style="margin-bottom:38px;">Um único pagamento. Acesso para sempre.</p>
      <div class="pricing-card" data-tilt="4">
        <span class="pricing-badge">Economize R$40</span>
        <p class="price-sub">Acesso completo à plataforma FinRendax</p>
        <div class="price-line">
          <span class="price-old">R$67</span>
          <span class="price-new">R$27</span>
        </div>
        <p class="price-terms">Pagamento único · Sem mensalidade · Acesso vitalício</p>
        <div class="included-title">Tudo que está incluso</div>
        <ul class="included-list">
          <li style="--i:0"><i data-lucide="check" size="18"></i> Guia completo</li>
          <li style="--i:1"><i data-lucide="check" size="18"></i> Simulador de investimentos</li>
          <li style="--i:2"><i data-lucide="check" size="18"></i> Planilha financeira</li>
          <li style="--i:3"><i data-lucide="check" size="18"></i> Videoaulas</li>
          <li style="--i:4"><i data-lucide="check" size="18"></i> Jogos interativos</li>
          <li style="--i:5"><i data-lucide="check" size="18"></i> Análises de conceitos</li>
          <li style="--i:6"><i data-lucide="check" size="18"></i> Introdução à Renda Extra</li>
        </ul>
        <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-wine btn-block btn-pulse cta-checkout" id="ctaPricingBtn">
          Garantir meu acesso por R$27 <i data-lucide="arrow-right" size="18"></i>
        </a>
        <div class="sec-badges">
          <span><i data-lucide="shield-check" size="16"></i> Compra 100% segura</span>
          <span><i data-lucide="lock" size="16"></i> Criptografia SSL 256-bit</span>
        </div>
      </div>
    </div>
  </section>

  <section class="section-pad">
    <div class="wrap">
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Dúvidas frequentes</div>
        <h2 class="section-title">Perguntas Frequentes</h2>
      </div>
      <div class="faq-wrap reveal">
        <div class="faq-item">
          <div class="faq-q" onclick="toggleFaq(this)">Como recebo o meu acesso?<i data-lucide="plus" class="faq-icon" size="19"></i></div>
          <div class="faq-a">Logo após a aprovação do pagamento, você recebe um e-mail com todos os dados de acesso à plataforma FinRendax.</div>
        </div>
        <div class="faq-item">
          <div class="faq-q" onclick="toggleFaq(this)">Preciso pagar mensalidade?<i data-lucide="plus" class="faq-icon" size="19"></i></div>
          <div class="faq-a">Não. O FinRendax tem pagamento único de R$27. Você compra uma vez e tem acesso vitalício ao conteúdo e às atualizações.</div>
        </div>
        <div class="faq-item">
          <div class="faq-q" onclick="toggleFaq(this)">Serve para quem não entende nada de dinheiro?<i data-lucide="plus" class="faq-icon" size="19"></i></div>
          <div class="faq-a">Com certeza. Todo o material foi desenhado para iniciantes, com linguagem simples e sem termos difíceis.</div>
        </div>
        <div class="faq-item">
          <div class="faq-q" onclick="toggleFaq(this)">E se eu não gostar? Tem garantia?<i data-lucide="plus" class="faq-icon" size="19"></i></div>
          <div class="faq-a">Sim. Você tem 7 dias de garantia incondicional — se algo não for para você, devolvemos 100% do valor, sem burocracia.</div>
        </div>
      </div>
    </div>
  </section>

  <section class="section-pad" style="padding-top:10px;">
    <div class="wrap reveal">
      <div class="cta-band">
        <h2>Não deixe pra depois o que pode mudar sua vida <i>agora</i></h2>
        <p>Por apenas R$27 você tem acesso completo à plataforma FinRendax. Pagamento único, acesso vitalício.</p>
        <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-wine cta-checkout">
          Garantir meu acesso por R$27 <i data-lucide="arrow-right"></i>
        </a>
        <div class="guarantees">
          <span>100% SEGURO</span><span>ACESSO IMEDIATO</span><span>SEM MENSALIDADE</span>
        </div>
      </div>
    </div>
  </section>
</div>

<!-- ABA 2 — QUEM SOMOS -->
<div id="quem-somos" class="page-section">
  <section class="section-pad" style="padding-top:70px;">
    <div class="wrap">
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Institucional</div>
        <h2 class="section-title">Educação financeira,<br><i>acessível para todos</i></h2>
        <p class="section-sub">Nascemos para descomplicar o que a escola nunca ensinou — para você organizar suas finanças e criar uma renda extra.</p>
      </div>
      <div class="reveal" style="max-width:780px;margin:0 auto 60px;text-align:center;color:var(--ink-muted);font-size:1.08rem;line-height:1.85;">
        <p style="margin-bottom:20px;">A FinRendax surgiu de uma ideia simples: a maioria das pessoas nunca aprendeu sobre dinheiro na escola. Resultado — vivemos ansiosos com o salário, sem saber investir e sem reservas.</p>
        <p style="margin-bottom:20px;">Decidimos mudar isso criando um conteúdo direto, prático e sem termos complicados. Não importa se você tem 16 ou 50 anos: o momento certo de começar é agora.</p>
        <p>Já ajudamos milhares de pessoas a dar o primeiro passo — organizar gastos, aprender a gerar renda e investir com segurança. Nosso objetivo é ser o seu guia nessa jornada.</p>
      </div>

      <!-- DIFERENCIAIS -->
      <div class="section-head reveal" style="margin-top:60px;">
        <div class="eyebrow" style="justify-content:center">Diferenciais</div>
        <h2 class="section-title">Por que o FinRendax é diferente</h2>
      </div>
      <div class="grid-4 reveal" style="margin-bottom:70px;">
        <div class="feat-row">
          <div class="ic"><i data-lucide="zap"></i></div>
          <div><h4>Acesso imediato</h4><p>Receba seu login na hora após a confirmação.</p></div>
        </div>
        <div class="feat-row">
          <div class="ic"><i data-lucide="smartphone"></i></div>
          <div><h4>100% mobile &amp; PC</h4><p>Estude de onde estiver, em qualquer dispositivo.</p></div>
        </div>
        <div class="feat-row">
          <div class="ic"><i data-lucide="download"></i></div>
          <div><h4>Ferramentas prontas</h4><p>Planilhas e simuladores prontos para uso imediato.</p></div>
        </div>
        <div class="feat-row">
          <div class="ic"><i data-lucide="clock"></i></div>
          <div><h4>Sem mensalidades</h4><p>Pagamento único com acesso vitalício garantido.</p></div>
        </div>
      </div>
      <div class="grid-2 reveal" style="max-width:780px;margin:0 auto 70px;">
        <div class="card" style="text-align:center;">
          <div class="card-icon" style="margin:0 auto 24px;"><i data-lucide="target"></i></div>
          <h3>Missão</h3>
          <p>Tornar a educação financeira acessível, simples e prática para todos os brasileiros, independentemente da idade ou renda.</p>
        </div>
        <div class="card" style="text-align:center;">
          <div class="card-icon" style="margin:0 auto 24px;"><i data-lucide="eye"></i></div>
          <h3>Visão</h3>
          <p>Ser a plataforma de educação financeira mais recomendada e confiável do Brasil, forming gerações mais preparadas.</p>
        </div>
      </div>
      <div class="hairline" style="margin-bottom:70px;"></div>

      <!-- HISTÓRIA / FOTO DO FUNDADOR -->
      <div class="story reveal">
        <div class="story-frame-wrap">
          <div class="story-frame">
            <img src="WhatsApp Image 2026-09-24 at 15.01.07.jpeg" alt="Foto do Fundador" width="360">
          </div>
        </div>
        <div class="story-content">
          <div class="eyebrow">Quem está por trás</div>
          <h3>Uma história real, não teoria</h3>
          <p>Tudo começou quando eu decidi investir em mim mesmo, sem entender quase nada sobre como funciona. Errando, aprendendo e anotando cada passo, transformei a bagunça em método.</p>
          <p>Com o tempo, minha família passou a entender por que eu fazia aquilo e começou a pedir conselhos: onde guardar, como investir, até como fazer uma renda extra. Vi que aquilo que aprendi sozinho podia ajudar muita gente.</p>
          <p>Foi assim que nasceu a FinRendax — uma empresa dedicada a resolver essas dificuldades, para que você não precise passar pelo mesmo aperto que eu passei.</p>
          <div class="story-sign">— Fundador da FinRendax</div>
        </div>
      </div>
      <div class="section-head reveal" style="margin-top:90px;">
        <h2 class="section-title">Pronto para começar sua jornada?</h2>
        <p class="section-sub" style="margin-bottom:28px;">Conheça tudo o que está incluso no FinRendax.</p>
        <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-wine cta-checkout">Garantir meu acesso por R$ 27</a>
      </div>
    </div>
  </section>
</div>

<!-- ABA 3 — SERVIÇOS -->
<div id="servicos" class="page-section">
  <section class="section-pad" style="padding-top:70px;">
    <div class="wrap">
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Ecossistema</div>
        <h2 class="section-title">Tudo o que o FinRendax oferece</h2>
        <p class="section-sub">Ferramentas e conteúdos completos para você dominar suas finanças do zero e aprender a gerar renda extra.</p>
      </div>
      <div class="grid-3 reveal" style="margin-bottom:80px;">
        <div class="card">
          <div class="card-icon"><i data-lucide="book-open"></i></div>
          <h3>Guia completo</h3>
          <p>Do básico ao avançado: conceitos, estratégias e boas práticas de educação financeira e renda extra.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="calculator"></i></div>
          <h3>Simulador de investimentos</h3>
          <p>Teste cenários, compare estratégias e veja como seu dinheiro pode crescer ao longo do tempo.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="layout-grid"></i></div>
          <h3>Planilha financeira</h3>
          <p>Organize receitas, despesas e metas. Visualize sua saúde financeira com clareza total.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="video"></i></div>
          <h3>Videoaulas</h3>
          <p>Aulas teóricas e práticas para você aprender no seu próprio ritmo, quando quiser.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="gamepad-2"></i></div>
          <h3>Jogos interativos</h3>
          <p>Aprenda jogando: desafios, rankings e conquistas que tornam o aprendizado divertido.</p>
        </div>
        <div class="card">
          <div class="card-icon"><i data-lucide="bar-chart-2"></i></div>
          <h3>Análises de conceitos</h3>
          <p>Relatórios e análises que ajudam você a tomar decisões financeiras mais inteligentes.</p>
        </div>
      </div>
      <div class="reveal">
        <div class="cta-band">
          <h2>Não deixe pra depois o que pode mudar sua vida <i>agora</i></h2>
          <p>Por apenas R$27 você tem acesso completo à plataforma FinRendax. Pagamento único, acesso vitalício.</p>
          <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-wine cta-checkout">
            Garantir meu acesso por R$27 <i data-lucide="arrow-right"></i>
          </a>
          <div class="guarantees">
            <span>100% SEGURO</span><span>ACESSO IMEDIATO</span><span>SEM MENSALIDADE</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</div>

<!-- ABA 4 — EDUCAÇÃO (SIMULADOR + APRENDIZADO) -->
<div id="educacao" class="page-section">
  <section class="section-pad" style="padding-top:70px;">
    <div class="wrap">
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Educação</div>
        <h2 class="section-title">Simule, aprenda e <i>evolua</i> no seu ritmo</h2>
        <p class="section-sub">Teste cenários no simulador de investimentos e conheça os conteúdos que ensinam você a dominar suas finanças do zero.</p>
      </div>

      <!-- SIMULADOR DE INVESTIMENTOS (movido da página principal) -->
      <div class="sim-stage reveal">
        <div class="sim-controls-panel">
          <h3>Simulador de investimentos</h3>
          <p class="lead">Ajuste o aporte e o prazo e veja seu dinheiro crescer em tempo real.</p>
          <div class="sim-field">
            <label for="simAmount">Aporte mensal estimado <small>R$ / mês</small></label>
            <input type="number" id="simAmount" class="sim-num" value="300" min="0" step="10" placeholder="Aporte R$" oninput="syncFromNumber('amount'); updateSimulation(true)" aria-label="Valor do aporte em reais">
            <input type="range" id="simAmountRange" class="sim-range" min="50" max="5000" step="50" value="300" oninput="syncFromRange('amount'); updateSimulation(true)" aria-label="Ajustar aporte mensal">
          </div>
          <div class="sim-field">
            <label for="simMonths">Prazo <small>meses</small></label>
            <input type="number" id="simMonths" class="sim-num" value="12" min="1" max="600" step="1" placeholder="Meses" oninput="syncFromNumber('months'); updateSimulation(true)" aria-label="Quantidade de meses">
            <input type="range" id="simMonthsRange" class="sim-range" min="1" max="120" step="1" value="12" oninput="syncFromRange('months'); updateSimulation(true)" aria-label="Ajustar prazo em meses">
          </div>
          <p class="sim-note">Simulação ilustrativa com rentabilidade de 0,8% ao mês. Não é recomendação de investimento; resultados reais variam.</p>
        </div>
        <div class="sim-result-panel">
          <div class="sim-result-label">Valor projetado ao final do prazo</div>
          <div class="sim-result-total" id="simTotal">R$ 0,00</div>
          <span class="sim-delta" id="simDelta">↑ 12m proj.</span>
          <div class="sim-breakdown">
            <div class="sim-mini"><span>Total aportado</span><b id="simInvested">R$ 0,00</b></div>
            <div class="sim-mini gain"><span>Rendimento estimado</span><b id="simGain">R$ 0,00</b></div>
          </div>
          <svg class="sim-chart" id="simChart" viewBox="0 0 600 220" preserveAspectRatio="none" aria-label="Gráfico de crescimento do investimento" role="img">
            <defs>
              <linearGradient id="simArea" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#D9A043" stop-opacity=".45"/><stop offset="1" stop-color="#D9A043" stop-opacity="0"/></linearGradient>
            </defs>
            <line x1="0" y1="55" x2="600" y2="55" stroke="rgba(255,255,255,.06)"/>
            <line x1="0" y1="110" x2="600" y2="110" stroke="rgba(255,255,255,.06)"/>
            <line x1="0" y1="165" x2="600" y2="165" stroke="rgba(255,255,255,.06)"/>
            <path id="simAreaPath" fill="url(#simArea)" d=""/>
            <path id="simInvestedPath" fill="none" stroke="rgba(255,255,255,.4)" stroke-width="2" stroke-dasharray="6 6" vector-effect="non-scaling-stroke" d=""/>
            <path id="simLinePath" fill="none" stroke="#D9A043" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" vector-effect="non-scaling-stroke" d=""/>
          </svg>
          <div class="sim-legend"><span><i style="background:#D9A043"></i>Valor projetado</span><span><i style="background:rgba(255,255,255,.4)"></i>Total aportado</span></div>
          <p class="sim-note">Simulação ilustrativa com premissa didática de 0,8% ao mês. Não é promessa nem garantia de rentabilidade.</p>
          <p class="sim-note" id="simMarketNote" hidden></p>
          <div class="sim-cta">
            <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-bronze btn-block cta-checkout" id="ctaSimBtn">
              Garantir meu acesso por R$27 <i data-lucide="arrow-right" size="18"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- 4 PILARES DE APRENDIZADO -->
      <div class="section-head reveal">
        <div class="eyebrow" style="justify-content:center">Aprendizado</div>
        <h2 class="section-title">Como você aprende no FinRendax</h2>
      </div>
      <div class="grid-4 reveal" style="margin-bottom:80px;">
        <div class="card">
          <span class="num">01</span>
          <div class="card-icon"><i data-lucide="book-open"></i></div>
          <h3>Guia completo</h3>
          <p>Do básico ao avançado: conceitos, estratégias e boas práticas de educação financeira e renda extra.</p>
        </div>
        <div class="card">
          <span class="num">02</span>
          <div class="card-icon"><i data-lucide="video"></i></div>
          <h3>Videoaulas</h3>
          <p>Aulas teóricas e práticas para você aprender no seu próprio ritmo, quando quiser.</p>
        </div>
        <div class="card">
          <span class="num">03</span>
          <div class="card-icon"><i data-lucide="gamepad-2"></i></div>
          <h3>Jogos interativos</h3>
          <p>Aprenda jogando: desafios, rankings e conquistas que tornam o aprendizado divertido.</p>
        </div>
        <div class="card">
          <span class="num">04</span>
          <div class="card-icon"><i data-lucide="bar-chart-2"></i></div>
          <h3>Análises de conceitos</h3>
          <p>Relatórios e análises que ajudam você a tomar decisões financeiras mais inteligentes.</p>
        </div>
      </div>

      <div class="reveal">
        <div class="cta-band">
          <h2>Não deixe pra depois o que pode mudar sua vida <i>agora</i></h2>
          <p>Por apenas R$27 você tem acesso completo à plataforma FinRendax. Pagamento único, acesso vitalício.</p>
          <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="btn btn-wine cta-checkout">
            Garantir meu acesso por R$27 <i data-lucide="arrow-right"></i>
          </a>
          <div class="guarantees">
            <span>100% SEGURO</span><span>ACESSO IMEDIATO</span><span>SEM MENSALIDADE</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</div>

<!-- BOTTOM BAR (FIXA EM TODAS AS ABAS) -->
<div class="bottom-bar">
  <div>
    <div class="bb-label">Acesso vitalício</div>
    <div class="bb-price"><s>R$67</s> R$27</div>
  </div>
  <a href="https://pay.kiwify.com.br/SEU_LINK_AQUI" target="_blank" rel="noopener" class="bb-btn cta-checkout btn-icon-only" aria-label="Garantir acesso">
    <i data-lucide="arrow-right" size="18"></i>
  </a>
</div>

<!-- FOOTER -->
<footer>
  <div class="wrap">
    <div class="footer-grid">
      <div class="footer-brand" style="max-width:290px;">
        <a href="#" class="brand" onclick="showTab('recursos'); return false;">
          <span class="brand-mark">F</span>
          <span class="brand-word">FinRend<em>ax</em></span>
        </a>
        <p>Educação financeira acessível, prática e sem enrolação — para todos os brasileiros.</p>
      </div>
      <div class="footer-col">
        <h4>Navegação</h4>
        <ul>
          <li><a onclick="showTab('recursos')">Recursos</a></li>
          <li><a onclick="showTab('quem-somos')">Quem Somos</a></li>
          <li><a onclick="showTab('servicos')">Serviços</a></li>
          <li><a onclick="showTab('educacao')">Educação</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Legal</h4>
        <ul>
          <li><a onclick="openLegal('termos')">Termos de Uso</a></li>
          <li><a onclick="openLegal('privacidade')">Política de Privacidade</a></li>
          <li><a onclick="openLegal('garantia')">Garantia de Reembolso</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Conecte-se</h4>
        <div class="footer-socials">
          <a href="https://instagram.com/SEU_USUARIO" target="_blank" rel="noopener" aria-label="Perfil no Instagram" title="Instagram"><i data-lucide="instagram" size="18"></i></a>
          <a href="mailto:finrendax@gmail.com" aria-label="Enviar E-mail" title="Enviar E-mail"><i data-lucide="mail" size="18"></i></a>
        </div>
        <ul style="margin-top:16px;">
          <li><a href="https://instagram.com/SEU_USUARIO" target="_blank" rel="noopener">Instagram</a></li>
          <li><a href="mailto:finrendax@gmail.com">E-mail: finrendax@gmail.com</a></li>
        </ul>
      </div>
    </div>

    <div class="footer-bottom">
      <span>© 2026 FinRendax. Todos os direitos reservados. Conformidade com Padrões Internacionais de Proteção de Dados (LGPD/GDPR).</span>
      <span style="display:block; margin-top:10px; font-size:0.75rem; color:var(--ink-muted); line-height:1.5;">
        Aviso Legal: A FinRendax é uma empresa focada exclusivamente em educação financeira e sugestões metodológicas para geração de renda extra. Não oferecemos consultoria de investimentos individualizada, gestão de patrimônio ou recomendações diretas de ativos financeiros. Os resultados financeiros podem variar individualmente e dependem do esforço e execução de cada aluno.
      </span>
    </div>
  </div>
</footer>

<!-- MODAL LEGAL -->
<div id="legalModal" class="legal-modal" onclick="if(event.target===this) closeLegal();">
  <div class="legal-modal-content">
    <button class="legal-modal-close" onclick="closeLegal()" aria-label="Fechar janela modal">✕</button>
    <h3 id="modalTitle" style="font-family:var(--serif); margin-bottom:15px; font-size:1.5rem;"></h3>
    <div id="modalBody" style="font-size:0.9rem; color:var(--ink-muted); line-height:1.6;"></div>
  </div>
</div>

<script>
/*! FinRendax Ops v1.0 — segurança, LGPD e agentes de monitoramento (executa no navegador do visitante)
 *
 *  O que este arquivo faz:
 *   1. Guarda de segurança: proteção de links de checkout, detecção de injeção de código, bloqueio de envio de
 *      dados pessoais para destinos não autorizados, escuta de violações de CSP.
 *   2. LGPD: banner de consentimento granular, gate de cookies/pixels, Central de Privacidade, canal de direitos do titular.
 *   3. Agentes: 10 agentes com funções separadas, coordenados por um orquestrador que roda só quando a aba está visível e
 *      o navegador está ocioso (não interfere na fluidez). Painel de diagnóstico: ?ops=1 ou Alt+Shift+O.
 *
 *  Limite honesto: código no navegador só roda enquanto alguém está com o site aberto. O monitoramento 24h de verdade
 *  (certificado, cabeçalhos, disponibilidade, links) está em agents/watchdog.mjs, agendado no servidor.
 */
(function () {
  'use strict';
  var W = window, D = document;
  if (W.FRX && W.FRX.__ready) return;

  /* ============================================================
     CONFIGURAÇÃO (sobrescreva com window.FRX_CONFIG no index.html)
  ============================================================ */
  var DEFAULTS = {
    company: {
      name: 'FinRendax',
      legalName: 'Vitor Hugo Nogueira Sousa',
      cnpj: 'pessoa física, sem CNPJ — atua como profissional autônomo',
      address: 'Presidente Prudente, SP — endereço completo disponível mediante solicitação ao encarregado',
      dpoName: 'Vitor Hugo Nogueira Sousa',
      dpoEmail: 'finrendax@gmail.com'
    },
    policyVersion: '2026-09-20',
    checkoutHosts: ['pay.kiwify.com.br', 'kiwify.com.br'],
    scriptAllow: ['unpkg.com', 'cdnjs.cloudflare.com', 'cdn.jsdelivr.net', 'www.googletagmanager.com', 'connect.facebook.net'],
    egressAllow: ['api.emailjs.com', 'kiwify.com.br', 'google-analytics.com', 'analytics.google.com', 'googletagmanager.com', 'facebook.com', 'facebook.net'],
    ga4Id: '',
    metaPixelId: '',
    emailjs: { publicKey: 'SUA_PUBLIC_KEY_AQUI', serviceId: 'SEU_SERVICE_ID', templateId: 'SEU_TEMPLATE_ID', guideLink: '' },
    reportEndpoint: '',          /* opcional: URL HTTPS que recebe relatórios de incidentes críticos (sem dados pessoais) */
    marketDataUrl: '',
    opsKeyHash: '',              /* SHA-256 da senha do painel de agentes. Vazio = painel desativado para o público */
    leadRateLimit: { max: 3, windowMs: 3600000 }
  };
  function merge(a, b) {
    var o = {}, k;
    for (k in a) o[k] = a[k];
    for (k in (b || {})) o[k] = (a[k] && typeof a[k] === 'object' && !Array.isArray(a[k]) && typeof b[k] === 'object') ? merge(a[k], b[k]) : b[k];
    return o;
  }
  var CFG = merge(DEFAULTS, W.FRX_CONFIG);

  /* ============================================================
     NÚCLEO: log, eventos, storage seguro, utilidades
  ============================================================ */
  var FRX = { config: CFG, version: '1.0.0' };
  var DEBUG = /^(localhost|127\.|\[::1\])/.test(location.hostname) || location.protocol === 'file:';
  var unlocked = false;
  var LOG = [], listeners = {};
  function on(ev, fn) { (listeners[ev] = listeners[ev] || []).push(fn); }
  function emit(ev, p) { (listeners[ev] || []).forEach(function (f) { try { f(p); } catch (e) {} }); }
  function log(agent, sev, msg, data) {
    var e = { t: Date.now(), agent: agent, sev: sev, msg: String(msg).slice(0, 280) };
    if (data) e.data = data;
    LOG.push(e); if (LOG.length > 200) LOG.shift();
    if (DEBUG || unlocked) { if (sev === 'crit') console.error('[FRX·' + agent + ']', msg); else if (sev === 'warn') console.warn('[FRX·' + agent + ']', msg); }
    emit('log', e);
    if (sev === 'crit') report(e);
  }
  var store = {
    get: function (k) { try { return JSON.parse(localStorage.getItem('frx:' + k)); } catch (e) { return null; } },
    set: function (k, v) { try { localStorage.setItem('frx:' + k, JSON.stringify(v)); return true; } catch (e) { return false; } },
    del: function (k) { try { localStorage.removeItem('frx:' + k); } catch (e) {} }
  };
  var idle = W.requestIdleCallback ? function (f) { W.requestIdleCallback(f, { timeout: 2500 }); } : function (f) { setTimeout(f, 80); };
  function $(s, r) { return (r || D).querySelector(s); }
  function $$(s, r) { return Array.prototype.slice.call((r || D).querySelectorAll(s)); }
  function hostOf(u) { try { return new URL(u, location.href).hostname; } catch (e) { return ''; } }
  function inList(h, list) { return list.some(function (a) { return h === a || h.slice(-(a.length + 1)) === '.' + a; }); }
  function maskEmail(s) { return String(s).replace(/([^\s@])[^\s@]*@/g, '$1***@'); }
  function uid(n) { var a = new Uint8Array(n || 6); (W.crypto || {}).getRandomValues ? crypto.getRandomValues(a) : a.forEach(function (_, i) { a[i] = Math.random() * 255; }); return Array.prototype.map.call(a, function (b) { return ('0' + b.toString(16)).slice(-2); }).join('').toUpperCase(); }
  function loadScript(src) {
    return new Promise(function (res, rej) {
      var s = D.createElement('script'); s.src = src; s.async = true; s.onload = res; s.onerror = function () { rej(new Error('falha ao carregar ' + hostOf(src))); };
      D.head.appendChild(s);
    });
  }
  FRX.log = log; FRX.on = on; FRX.store = store; FRX.loadScript = loadScript; FRX.logs = function () { return LOG.slice(); };

  /* Relato opcional de incidentes críticos (sem dados pessoais) */
  var lastReport = 0;
  function report(e) {
    if (!CFG.reportEndpoint || Date.now() - lastReport < 30000) return;
    lastReport = Date.now();
    try {
      var body = JSON.stringify({ site: location.origin, agent: e.agent, msg: e.msg, t: e.t, ua: navigator.userAgent.slice(0, 120) });
      navigator.sendBeacon ? navigator.sendBeacon(CFG.reportEndpoint, body) : 0;
    } catch (x) {}
  }

  /* ============================================================
     DETECÇÃO DE DADOS PESSOAIS (usada pelo guarda de saída e pelos logs)
  ============================================================ */
  function validCPF(d) {
    d = d.replace(/\D/g, ''); if (d.length !== 11 || /^(\d)\1+$/.test(d)) return false;
    for (var t = 9; t < 11; t++) { var s = 0; for (var i = 0; i < t; i++) s += +d[i] * (t + 1 - i); if (((s * 10) % 11) % 10 !== +d[t]) return false; }
    return true;
  }
  function luhn(d) {
    d = d.replace(/\D/g, ''); if (d.length < 13 || d.length > 19) return false;
    var s = 0, alt = false; for (var i = d.length - 1; i >= 0; i--) { var n = +d[i]; if (alt) { n *= 2; if (n > 9) n -= 9; } s += n; alt = !alt; }
    return s % 10 === 0;
  }
  function hasPII(str) {
    str = String(str || '');
    if (/[^\s@/=&?"']+@[^\s@/=&?"']+\.[a-z]{2,}/i.test(str)) return 'e-mail';
    var m = str.match(/\b\d{3}\.?\d{3}\.?\d{3}-?\d{2}\b/g) || []; if (m.some(validCPF)) return 'CPF';
    m = str.match(/\b(?:\d[ -]?){13,19}\b/g) || []; if (m.some(luhn)) return 'cartão';
    return '';
  }
  FRX.hasPII = hasPII;

  /* ============================================================
     GUARDA DE SEGURANÇA
  ============================================================ */
  var SEC = { incidents: 0, blocked: 0, csp: 0, injected: 0, hijack: 0, egressBlocked: 0 };
  FRX.security = SEC;
  var checkoutOrig = new WeakMap();

  function hardenLinks(root) {
    $$('a[href]', root).forEach(function (a) {
      var h = a.getAttribute('href') || '';
      var isExternal = /^https?:/i.test(h) && hostOf(h) !== location.hostname;
      if (isExternal && !/noopener/.test(a.rel || '')) a.rel = ((a.rel || '') + ' noopener noreferrer').trim();
      if (a.classList.contains('cta-checkout') && !checkoutOrig.has(a)) {
        var ok = false;
        try { var u = new URL(h, location.href); ok = u.protocol === 'https:' && inList(u.hostname, CFG.checkoutHosts); } catch (e) {}
        if (!ok) { a.setAttribute('aria-disabled', 'true'); a.dataset.blocked = '1'; a.removeAttribute('href'); SEC.blocked++; log('Sentinela', 'crit', 'Link de checkout bloqueado (destino não autorizado): ' + h.slice(0, 60)); }
        else checkoutOrig.set(a, h);
      }
    });
  }

  function guardDOM() {
    var mo = new MutationObserver(function (list) {
      list.forEach(function (m) {
        if (m.type === 'attributes' && m.target.classList && m.target.classList.contains('cta-checkout') && m.attributeName === 'href') {
          var a = m.target, orig = checkoutOrig.get(a), cur = a.getAttribute('href') || '';
          if (orig && cur !== orig) {
            var okHost = false; try { okHost = inList(new URL(cur, location.href).hostname, CFG.checkoutHosts); } catch (e) {}
            if (!okHost) { a.setAttribute('href', orig); SEC.hijack++; SEC.incidents++; log('Sentinela', 'crit', 'Tentativa de alterar link de checkout revertida'); }
          }
        }
        m.addedNodes && m.addedNodes.forEach(function (n) {
          if (n.nodeType !== 1) return;
          var tag = n.tagName;
          if (tag === 'SCRIPT') {
            var src = n.getAttribute('src');
            if (src && !inList(hostOf(src), CFG.scriptAllow) && hostOf(src) !== location.hostname) { n.remove(); SEC.injected++; SEC.incidents++; log('Sentinela', 'crit', 'Script externo não autorizado removido: ' + hostOf(src)); }
            else if (!src && !n.dataset.frxOk && D.readyState === 'complete') { SEC.injected++; log('Sentinela', 'warn', 'Script inline adicionado após o carregamento'); }
          } else if (tag === 'IFRAME' || tag === 'OBJECT' || tag === 'EMBED') {
            if (!n.dataset.frxOk) { n.remove(); SEC.injected++; SEC.incidents++; log('Sentinela', 'crit', 'Elemento <' + tag.toLowerCase() + '> não autorizado removido'); }
          } else if (tag === 'FORM' && n.action && hostOf(n.action) !== location.hostname) {
            n.remove(); SEC.injected++; SEC.incidents++; log('Sentinela', 'crit', 'Formulário com destino externo removido');
          } else if (tag === 'A' || (n.querySelector && n.querySelector('a'))) hardenLinks(n.parentNode || n);
        });
      });
    });
    mo.observe(D.documentElement, { childList: true, subtree: true, attributes: true, attributeFilter: ['href'] });
  }

  function guardCSP() {
    D.addEventListener('securitypolicyviolation', function (e) {
      SEC.csp++;
      var blocked = String(e.blockedURI || '').split('?')[0].slice(0, 80);
      log('Sentinela', 'warn', 'CSP bloqueou (' + e.effectiveDirective + '): ' + (blocked || 'inline'));
    });
  }

  /* Bloqueio de vazamento: impede fetch/XHR/beacon com dado pessoal para destinos fora da lista */
  function guardEgress() {
    function allowed(h) { return h === location.hostname || inList(h, CFG.egressAllow); }
    function check(url, body, via) {
      var h = hostOf(url); if (!h || allowed(h)) return true;
      var kind = hasPII(String(url) + ' ' + (typeof body === 'string' ? body : ''));
      if (kind) { SEC.egressBlocked++; SEC.incidents++; log('Sentinela', 'crit', 'Envio de ' + kind + ' bloqueado para destino não autorizado (' + h + ' via ' + via + ')'); return false; }
      log('Rede', 'info', 'Requisição para destino fora da lista: ' + h);
      return true;
    }
    if (W.fetch) { var f0 = W.fetch; W.fetch = function (i, init) { var u = typeof i === 'string' ? i : (i && i.url) || ''; if (!check(u, init && init.body, 'fetch')) return Promise.reject(new TypeError('Bloqueado pelo guarda de saída FinRendax')); return f0.apply(this, arguments); }; }
    if (navigator.sendBeacon) { var b0 = navigator.sendBeacon.bind(navigator); navigator.sendBeacon = function (u, d) { return check(u, d, 'beacon') ? b0(u, d) : false; }; }
    var xo = XMLHttpRequest.prototype.open, xs = XMLHttpRequest.prototype.send;
    XMLHttpRequest.prototype.open = function (m, u) { this.__frxUrl = u; return xo.apply(this, arguments); };
    XMLHttpRequest.prototype.send = function (b) { if (!check(this.__frxUrl, b, 'xhr')) { try { this.abort(); } catch (e) {} return; } return xs.apply(this, arguments); };
  }

  function guardFrame() {
    try { if (W.top !== W.self) { W.top.location = W.self.location; } } catch (e) { D.documentElement.style.display = 'none'; log('Sentinela', 'crit', 'Página carregada dentro de outro site (clickjacking) — ocultada'); }
  }

  /* Limpa da URL parâmetros que carregam dado pessoal (evita vazar em histórico, referrer e analytics) */
  function scrubURL() {
    try {
      var u = new URL(location.href), dirty = false;
      u.searchParams.forEach(function (v, k) { if (hasPII(v) || /^(cpf|email|e-mail|senha|password|token|card|cartao)$/i.test(k)) { u.searchParams.delete(k); dirty = true; } });
      if (dirty) { history.replaceState(null, '', u.pathname + u.search + u.hash); log('Sentinela', 'warn', 'Parâmetros com dado pessoal removidos da URL'); }
    } catch (e) {}
  }

  guardFrame(); guardCSP(); guardEgress(); scrubURL();

  /* ============================================================
     CONSENTIMENTO (LGPD art. 7º I, 8º e 9º) — granular, revogável, com registro de prova
  ============================================================ */
  var CONSENT_KEY = 'consent';
  function gpc() { return navigator.globalPrivacyControl === true; }
  function getConsent() { var c = store.get(CONSENT_KEY); return c && c.v === CFG.policyVersion ? c : null; }
  function saveConsent(a, m, how) {
    var c = { v: CFG.policyVersion, ts: new Date().toISOString(), id: uid(6), analytics: !!a, marketing: !!m, how: how };
    store.set(CONSENT_KEY, c); applyConsent(c); emit('consent', c); return c;
  }
  var loaded = { ga: false, fb: false };
  function applyConsent(c) {
    if (c.analytics && CFG.ga4Id && !loaded.ga) {
      loaded.ga = true;
      W.dataLayer = W.dataLayer || []; W.gtag = function () { W.dataLayer.push(arguments); };
      W.gtag('js', new Date()); W.gtag('config', CFG.ga4Id, { anonymize_ip: true });
      loadScript('https://www.googletagmanager.com/gtag/js?id=' + encodeURIComponent(CFG.ga4Id)).catch(function (e) { log('Guardião LGPD', 'warn', e.message); });
    }
    if (c.marketing && CFG.metaPixelId && !loaded.fb) {
      loaded.fb = true;
      var q = W.fbq = function () { q.callMethod ? q.callMethod.apply(q, arguments) : q.queue.push(arguments); };
      W._fbq = q; q.push = q; q.loaded = true; q.version = '2.0'; q.queue = [];
      loadScript('https://connect.facebook.net/en_US/fbevents.js').catch(function (e) { log('Guardião LGPD', 'warn', e.message); });
      q('init', CFG.metaPixelId); q('track', 'PageView');
    }
    if (!c.analytics && CFG.ga4Id) W['ga-disable-' + CFG.ga4Id] = true;
    if (c.analytics && CFG.ga4Id) W['ga-disable-' + CFG.ga4Id] = false;
    if ((!c.analytics && loaded.ga) || (!c.marketing && loaded.fb)) log('Guardião LGPD', 'info', 'Consentimento revogado: recarregue a página para descarregar os scripts de terceiros');
  }
  FRX.consent = {
    get: getConsent,
    has: function (k) { var c = getConsent(); return !!(c && c[k]); },
    open: function () { showPrefs(); }
  };

  /* ============================================================
     TEXTOS LEGAIS (revisar com advogado antes de publicar)
  ============================================================ */
  function fill(s) {
    var c = CFG.company;
    return s.replace(/\{\{legalName\}\}/g, c.legalName).replace(/\{\{cnpj\}\}/g, c.cnpj).replace(/\{\{address\}\}/g, c.address)
      .replace(/\{\{dpoName\}\}/g, c.dpoName).replace(/\{\{dpoEmail\}\}/g, c.dpoEmail).replace(/\{\{version\}\}/g, CFG.policyVersion);
  }
  var LEGAL = {
    privacidade: { title: 'Política de Privacidade', html:
      '<p class="frx-meta">Versão {{version}} · Lei nº 13.709/2018 (LGPD) e, quando aplicável, GDPR</p>' +
      '<h4>1. Quem é o controlador</h4><p>{{legalName}} ({{cnpj}}), {{address}}. Encarregado pelo tratamento de dados (DPO): {{dpoName}} — <a href="mailto:{{dpoEmail}}">{{dpoEmail}}</a>.</p>' +
      '<h4>2. Dados que tratamos</h4><ul>' +
      '<li><b>E-mail</b>, quando você pede o guia gratuito.</li>' +
      '<li><b>Dados de compra</b> (nome, e-mail, CPF/CNPJ, telefone, pagamento): coletados diretamente pela Kiwify, operadora do checkout. Não armazenamos dados de cartão.</li>' +
      '<li><b>Dados de navegação</b> (páginas vistas, dispositivo, IP): somente se você autorizar estatísticas ou marketing.</li>' +
      '<li><b>Sua escolha de cookies</b>, guardada no seu próprio navegador como prova de consentimento.</li></ul>' +
      '<h4>3. Para que usamos e em qual base legal</h4>' +
      '<table><tr><th>Finalidade</th><th>Base legal (art. 7º)</th></tr>' +
      '<tr><td>Enviar o guia gratuito e conteúdos educativos</td><td>Consentimento (I)</td></tr>' +
      '<tr><td>Processar a compra e liberar o acesso</td><td>Execução de contrato (V)</td></tr>' +
      '<tr><td>Obrigações fiscais e contábeis</td><td>Obrigação legal (II)</td></tr>' +
      '<tr><td>Estatísticas de uso</td><td>Consentimento (I)</td></tr>' +
      '<tr><td>Anúncios e remarketing</td><td>Consentimento (I)</td></tr>' +
      '<tr><td>Segurança do site e prevenção a fraudes</td><td>Legítimo interesse (IX)</td></tr></table>' +
      '<h4>4. Com quem compartilhamos</h4><p>Kiwify (pagamento e entrega), EmailJS (envio de e-mails), provedor de hospedagem e, se você consentir, Google e Meta. Não vendemos dados pessoais. Alguns desses fornecedores operam fora do Brasil; a transferência internacional ocorre com as salvaguardas do art. 33 da LGPD.</p>' +
      '<h4>5. Por quanto tempo guardamos</h4><p>E-mail de lead: até você revogar o consentimento ou por até 24 meses sem interação. Dados fiscais: pelo prazo da legislação (em regra, 5 anos). Registro de consentimento: enquanto estiver no seu navegador.</p>' +
      '<h4>6. Seus direitos (art. 18)</h4><p>Confirmação de tratamento, acesso, correção, anonimização, bloqueio ou eliminação, portabilidade, informação sobre compartilhamento, informação sobre a possibilidade de não consentir e revogação do consentimento. Responderemos em até 15 dias (art. 19). Você também pode reclamar à ANPD (gov.br/anpd).</p>' +
      '<p><button class="frx-btn frx-inline" data-frx-open="direitos">Exercer meus direitos</button> <button class="frx-btn frx-inline" data-frx-open="cookies">Preferências de cookies</button></p>' +
      '<h4>7. Segurança</h4><p>Conexão criptografada (HTTPS/HSTS), política de segurança de conteúdo (CSP), minimização de dados, bloqueio de envio de dados pessoais a destinos não autorizados e monitoramento automatizado contínuo. Nenhum sistema é 100% seguro; em caso de incidente relevante, comunicaremos a ANPD e os titulares afetados (art. 48).</p>' +
      '<h4>8. Crianças e adolescentes</h4><p>Nosso conteúdo é voltado a maiores de 18 anos. Dados de menores só são tratados com consentimento específico de um dos pais ou responsável (art. 14).</p>' +
      '<h4>9. Mudanças</h4><p>Quando esta política mudar de forma relevante, pediremos seu consentimento novamente, se necessário.</p>' },
    termos: { title: 'Termos de Uso', html:
      '<p class="frx-meta">Versão {{version}}</p>' +
      '<h4>1. O que é a FinRendax</h4><p>Plataforma de educação financeira e renda extra oferecida por {{legalName}} (CNPJ {{cnpj}}). O conteúdo é exclusivamente educacional.</p>' +
      '<h4>2. Sem consultoria de investimentos</h4><p>Não somos analistas, consultores ou gestores de valores mobiliários. Nada aqui é recomendação individual de compra ou venda. O simulador usa premissas didáticas e não promete rentabilidade; rentabilidade passada não garante resultado futuro.</p>' +
      '<h4>3. Acesso</h4><p>O acesso é pessoal e intransferível. Compartilhar login ou redistribuir o material é proibido. “Vitalício” significa durante a existência da plataforma; em caso de encerramento, avisaremos com antecedência.</p>' +
      '<h4>4. Propriedade intelectual</h4><p>Textos, vídeos, planilhas e marca pertencem à FinRendax (Lei nº 9.610/1998). É permitido uso pessoal.</p>' +
      '<h4>5. Pagamento e reembolso</h4><p>Processados pela Kiwify. Veja a Garantia de Reembolso.</p>' +
      '<h4>6. Foro</h4><p>Aplica-se a lei brasileira. Consumidores podem propor ação no foro do seu domicílio (CDC, art. 101, I).</p>' },
    garantia: { title: 'Garantia de Reembolso', html:
      '<p>Você tem <b>7 dias corridos</b> após a compra para pedir reembolso de 100%, sem burocracia (direito de arrependimento, CDC art. 49).</p>' +
      '<p>Como pedir: pela área do comprador na Kiwify ou por e-mail para <a href="mailto:{{dpoEmail}}">{{dpoEmail}}</a>. O valor volta pela mesma forma de pagamento.</p>' },
    cookies: { title: 'Cookies e tecnologias similares', html:
      '<table><tr><th>Categoria</th><th>Uso</th><th>Consentimento</th></tr>' +
      '<tr><td>Essenciais</td><td>Segurança, funcionamento e guardar sua escolha de cookies</td><td>Não exige</td></tr>' +
      '<tr><td>Estatísticas</td><td>Entender quais páginas ajudam mais (Google Analytics, se ativado)</td><td>Opcional</td></tr>' +
      '<tr><td>Marketing</td><td>Medir anúncios e remarketing (Meta Pixel, se ativado)</td><td>Opcional</td></tr></table>' +
      '<p><button class="frx-btn frx-inline" data-frx-open="cookies-prefs">Alterar minhas preferências</button></p>' }
  };

  /* ============================================================
     UI: estilos, banner, preferências, direitos do titular, textos legais
  ============================================================ */
  function injectCSS() {
    var css =
      '.frx-consent{position:fixed;left:16px;bottom:96px;z-index:1500;width:min(440px,calc(100vw - 32px));background:rgba(11,14,20,.98);border:1px solid rgba(217,160,67,.3);border-radius:18px;padding:20px 20px 16px;box-shadow:0 24px 60px -12px rgba(0,0,0,.8);color:var(--ink-txt,#f8f9fa);font:500 .85rem/1.55 var(--sans,system-ui);animation:frxIn .5s var(--ease,ease) both}' +
      '.frx-consent h2{font:600 1.15rem var(--serif,Georgia);margin-bottom:6px}.frx-consent p{color:var(--ink-muted,#94a3b8)}.frx-consent a{color:var(--bronze,#d9a043)}' +
      '.frx-actions{display:flex;gap:8px;margin-top:14px;flex-wrap:wrap}.frx-actions .frx-btn{flex:1 1 130px}' +
      '.frx-btn{font:700 .8rem var(--sans,system-ui);padding:11px 14px;border-radius:10px;border:1px solid rgba(255,255,255,.18);background:transparent;color:#fff;cursor:pointer;transition:background .2s,border-color .2s}' +
      '.frx-btn:hover{background:rgba(255,255,255,.08)}.frx-btn.pri{background:var(--wine,#a32e3e);border-color:var(--wine,#a32e3e)}.frx-btn.pri:hover{background:var(--wine-deep,#6e1523)}' +
      '.frx-btn.frx-inline{display:inline-block;margin:4px 6px 4px 0;border-color:rgba(217,160,67,.4);color:var(--bronze,#d9a043)}' +
      '.frx-link{background:none;border:0;color:var(--ink-muted,#94a3b8);text-decoration:underline;cursor:pointer;font:600 .78rem var(--sans,system-ui);padding:8px 2px;width:100%;margin-top:4px}' +
      '.frx-modal{position:fixed;inset:0;z-index:10050;display:flex;align-items:center;justify-content:center;padding:16px;background:rgba(0,0,0,.72)}' +
      '.frx-box{background:var(--ink-2,#0b0e14);border:1px solid rgba(255,255,255,.1);border-radius:20px;padding:28px;max-width:560px;width:100%;max-height:88vh;overflow:auto;color:var(--ink-txt,#f8f9fa);font:500 .88rem/1.6 var(--sans,system-ui)}' +
      '.frx-box h3{font:600 1.45rem var(--serif,Georgia);margin-bottom:14px}.frx-box label{display:block;font-weight:700;margin:14px 0 6px;font-size:.8rem}' +
      '.frx-box input,.frx-box select,.frx-box textarea{width:100%;padding:12px 14px;border-radius:10px;border:1px solid rgba(255,255,255,.14);background:rgba(255,255,255,.04);color:#fff;font:inherit}' +
      '.frx-box input:focus,.frx-box select:focus,.frx-box textarea:focus{outline:none;border-color:var(--bronze,#d9a043)}.frx-box select option{color:#000}' +
      '.frx-row{display:flex;align-items:flex-start;justify-content:space-between;gap:14px;padding:14px 0;border-bottom:1px solid rgba(255,255,255,.08)}.frx-row b{display:block}.frx-row span{color:var(--ink-muted,#94a3b8);font-size:.8rem}' +
      '.frx-sw{position:relative;flex:none;width:46px;height:26px}.frx-sw input{position:absolute;opacity:0;inset:0;width:100%;height:100%;cursor:pointer;margin:0}.frx-sw i{position:absolute;inset:0;border-radius:26px;background:rgba(255,255,255,.16);transition:background .2s;pointer-events:none}.frx-sw i::after{content:"";position:absolute;left:3px;top:3px;width:20px;height:20px;border-radius:50%;background:#fff;transition:transform .2s}.frx-sw input:checked+i{background:var(--wine,#a32e3e)}.frx-sw input:checked+i::after{transform:translateX(20px)}.frx-sw input:disabled{cursor:not-allowed}.frx-sw input:disabled+i{opacity:.55}.frx-sw input:focus-visible+i{outline:2px solid var(--bronze,#d9a043);outline-offset:2px}' +
      '#modalBody h4{font:700 .95rem var(--sans);color:var(--ink-txt,#f8f9fa);margin:18px 0 6px}#modalBody ul{padding-left:18px}#modalBody li{margin:4px 0}#modalBody a{color:var(--bronze,#d9a043)}#modalBody .frx-meta{font:.72rem var(--mono,monospace);color:var(--ink-muted,#94a3b8)}' +
      '#modalBody table,.frx-box table{width:100%;border-collapse:collapse;margin:8px 0;font-size:.8rem}#modalBody th,#modalBody td{border-bottom:1px solid rgba(255,255,255,.1);padding:8px 6px;text-align:left;vertical-align:top}' +
      '.frx-ok{margin-top:14px;padding:12px 14px;border-radius:10px;background:rgba(217,160,67,.12);border:1px solid rgba(217,160,67,.35);font-family:var(--mono,monospace);font-size:.8rem}' +
      '.frx-toast{position:fixed;left:50%;top:14px;transform:translateX(-50%);z-index:10060;background:#1b0b10;border:1px solid var(--wine,#a32e3e);color:#fff;padding:10px 16px;border-radius:10px;font:600 .8rem var(--sans,system-ui)}' +
      '.frx-ops{position:fixed;right:12px;top:12px;bottom:12px;width:min(460px,calc(100vw - 24px));z-index:10100;background:rgba(5,7,10,.97);border:1px solid rgba(255,255,255,.14);border-radius:16px;overflow:auto;padding:16px;color:#e7ebf0;font:500 .78rem/1.5 var(--sans,system-ui);box-shadow:0 30px 80px rgba(0,0,0,.8)}' +
      '.frx-ops h3{font:600 1.05rem var(--serif,Georgia);display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}' +
      '.frx-vit{display:grid;grid-template-columns:repeat(4,1fr);gap:6px;margin-bottom:12px}.frx-vit div{background:rgba(255,255,255,.05);border-radius:8px;padding:6px 8px;font-family:var(--mono,monospace)}.frx-vit b{display:block;font-size:.95rem;color:var(--bronze,#d9a043)}.frx-vit span{font-size:.62rem;color:#94a3b8}' +
      '.frx-ag{border:1px solid rgba(255,255,255,.1);border-radius:12px;padding:10px 12px;margin-bottom:8px}.frx-ag header{display:flex;align-items:center;gap:8px}.frx-ag header b{flex:1}.frx-ag .role{color:#94a3b8;font-size:.72rem;margin:2px 0 4px}' +
      '.frx-dot{width:9px;height:9px;border-radius:50%;background:#64748b;flex:none}.frx-dot.ok{background:#3ecf8e}.frx-dot.info{background:#60a5fa}.frx-dot.warn{background:#f5b942}.frx-dot.crit{background:#ef4444}' +
      '.frx-ag ul{list-style:none;padding:0;margin:4px 0 0}.frx-ag li{font-size:.72rem;color:#cbd5e1;padding:1px 0}.frx-ag li.warn{color:#f5b942}.frx-ag li.crit{color:#ff8a8a}' +
      '@keyframes frxIn{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:none}}' +
      '@media(max-width:600px){.frx-consent{left:10px;right:10px;width:auto;bottom:86px;padding:14px 14px 10px;font-size:.78rem}.frx-consent h2{font-size:1rem}.frx-actions{margin-top:10px}.frx-actions .frx-btn{padding:9px 10px;font-size:.76rem}}@media(prefers-reduced-motion:reduce){.frx-consent{animation:none}}';
    var s = D.createElement('style'); s.textContent = css; D.head.appendChild(s);
  }

  function el(html) { var t = D.createElement('div'); t.innerHTML = html.trim(); return t.firstChild; }
  var lastFocus = null;
  function openModal(node) {
    lastFocus = D.activeElement; D.body.appendChild(node);
    var f = $('input:not([disabled]),button,select,textarea', node); f && f.focus();
    node.addEventListener('keydown', function (e) {
      if (e.key === 'Escape') closeModal(node);
      if (e.key === 'Tab') { var items = $$('a[href],button,input:not([disabled]),select,textarea', node); if (!items.length) return; var a = items[0], z = items[items.length - 1]; if (e.shiftKey && D.activeElement === a) { z.focus(); e.preventDefault(); } else if (!e.shiftKey && D.activeElement === z) { a.focus(); e.preventDefault(); } }
    });
    node.addEventListener('click', function (e) { if (e.target === node) closeModal(node); });
  }
  function closeModal(node) { node.remove(); lastFocus && lastFocus.focus && lastFocus.focus(); }

  var banner = null;
  function showBanner() {
    if (banner || getConsent()) return;
    banner = el('<div class="frx-consent" role="dialog" aria-labelledby="frxCT" aria-describedby="frxCD">' +
      '<h2 id="frxCT">Sua privacidade importa</h2>' +
      '<p id="frxCD">Usamos cookies essenciais para o site funcionar. Estatísticas e marketing só entram com a sua autorização (LGPD, art. 7º, I) e você pode mudar de ideia quando quiser. <a href="#" data-frx-open="privacidade">Política de Privacidade</a></p>' +
      '<div class="frx-actions"><button class="frx-btn" data-frx="reject">Recusar não essenciais</button><button class="frx-btn" data-frx="accept">Aceitar todos</button></div>' +
      '<button class="frx-link" data-frx="custom">Personalizar</button></div>');
    D.body.appendChild(banner);
    banner.addEventListener('click', function (e) {
      var b = e.target.closest('[data-frx]'); if (!b) return;
      var a = b.dataset.frx;
      if (a === 'accept') { saveConsent(true, true, 'banner:accept'); hideBanner(); }
      else if (a === 'reject') { saveConsent(false, false, 'banner:reject'); hideBanner(); }
      else if (a === 'custom') showPrefs();
    });
    emit('banner', true);
  }
  function hideBanner() { if (banner) { banner.remove(); banner = null; emit('banner', false); } }

  function showPrefs() {
    var c = getConsent() || { analytics: false, marketing: false };
    var m = el('<div class="frx-modal" role="dialog" aria-modal="true" aria-labelledby="frxPT"><div class="frx-box"><h3 id="frxPT">Preferências de privacidade</h3>' +
      '<div class="frx-row"><div><b>Essenciais</b><span>Segurança e funcionamento do site. Sempre ativos.</span></div><label class="frx-sw"><input type="checkbox" checked disabled aria-label="Cookies essenciais (sempre ativos)"><i></i></label></div>' +
      '<div class="frx-row"><div><b>Estatísticas</b><span>Ajudam a entender o que melhorar. Dados agregados.</span></div><label class="frx-sw"><input type="checkbox" id="frxAn"' + (c.analytics ? ' checked' : '') + ' aria-label="Cookies de estatísticas"><i></i></label></div>' +
      '<div class="frx-row"><div><b>Marketing</b><span>Medição de anúncios e remarketing.</span></div><label class="frx-sw"><input type="checkbox" id="frxMk"' + (c.marketing ? ' checked' : '') + ' aria-label="Cookies de marketing"><i></i></label></div>' +
      (gpc() ? '<p class="frx-meta" style="margin-top:10px;font-size:.75rem;color:#94a3b8">Detectamos o sinal Global Privacy Control no seu navegador e ele é respeitado: estatísticas e marketing começam desligados.</p>' : '') +
      '<div class="frx-actions" style="margin-top:18px"><button class="frx-btn" data-x="close">Cancelar</button><button class="frx-btn pri" data-x="save">Salvar preferências</button></div>' +
      '<p style="margin-top:12px;font-size:.75rem"><a href="#" data-frx-open="privacidade" style="color:#d9a043">Política de Privacidade</a> · <a href="#" data-frx-open="direitos" style="color:#d9a043">Direitos do titular</a></p></div></div>');
    m.addEventListener('click', function (e) {
      var x = e.target.closest('[data-x]'); if (!x) return;
      if (x.dataset.x === 'save') { saveConsent($('#frxAn', m).checked, $('#frxMk', m).checked, 'prefs'); hideBanner(); }
      closeModal(m);
    });
    openModal(m);
  }

  var DSAR_TYPES = ['Confirmação de que tratam meus dados', 'Acesso aos meus dados', 'Correção de dados incompletos ou desatualizados', 'Anonimização, bloqueio ou eliminação', 'Portabilidade dos dados', 'Informação sobre com quem compartilham meus dados', 'Revogação do consentimento', 'Oposição a um tratamento'];
  function showDSAR() {
    var m = el('<div class="frx-modal" role="dialog" aria-modal="true" aria-labelledby="frxDT"><form class="frx-box" novalidate><h3 id="frxDT">Direitos do titular (LGPD, art. 18)</h3>' +
      '<p style="color:#94a3b8">Preencha e enviaremos o pedido ao nosso Encarregado. Você recebe um protocolo para acompanhar. Prazo de resposta: até 15 dias.</p>' +
      '<label for="frxDe">Seu e-mail (o mesmo usado na FinRendax)</label><input id="frxDe" type="email" required autocomplete="email" maxlength="120">' +
      '<label for="frxDt">O que você quer?</label><select id="frxDt">' + DSAR_TYPES.map(function (t) { return '<option>' + t + '</option>'; }).join('') + '</select>' +
      '<label for="frxDd">Detalhes (opcional)</label><textarea id="frxDd" rows="3" maxlength="800"></textarea>' +
      '<p id="frxDerr" role="alert" style="color:#ff8a8a;margin-top:8px"></p><div id="frxDok"></div>' +
      '<div class="frx-actions" style="margin-top:14px"><button class="frx-btn" type="button" data-x="close">Fechar</button><button class="frx-btn pri" type="submit">Gerar pedido</button></div></form></div>');
    var form = $('form', m);
    form.addEventListener('submit', function (e) {
      e.preventDefault();
      var email = $('#frxDe', m).value.trim(), err = $('#frxDerr', m);
      if (!/^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/.test(email)) { err.textContent = 'Informe um e-mail válido.'; return; }
      err.textContent = '';
      var proto = 'FRX-' + new Date().toISOString().slice(0, 10).replace(/-/g, '') + '-' + uid(3);
      var tipo = $('#frxDt', m).value, det = $('#frxDd', m).value.replace(/[\u0000-\u001f]/g, ' ').slice(0, 800);
      var body = 'Protocolo: ' + proto + '\nSolicitante: ' + email + '\nTipo: ' + tipo + '\nDetalhes: ' + det + '\n\nPara sua segurança, podemos pedir uma confirmação de identidade antes de atender.';
      var a = D.createElement('a'); a.href = 'mailto:' + CFG.company.dpoEmail + '?subject=' + encodeURIComponent('Direitos do titular — ' + proto) + '&body=' + encodeURIComponent(body);
      a.click();
      $('#frxDok', m).innerHTML = '<div class="frx-ok">Protocolo <b>' + proto + '</b><br>Seu app de e-mail abriu com o pedido pronto. Envie para concluir. Guarde este protocolo.</div>';
      log('Guardião LGPD', 'info', 'Pedido de titular gerado (' + proto + ')');
    });
    m.addEventListener('click', function (e) { var x = e.target.closest('[data-x]'); if (x && x.dataset.x === 'close') closeModal(m); });
    openModal(m);
  }

  /* Textos legais dentro do modal original do site (#legalModal) */
  function openLegal(type) {
    if (type === 'direitos') return showDSAR();
    if (type === 'cookies-prefs') return showPrefs();
    var d = LEGAL[type]; if (!d) return;
    $('#modalTitle').textContent = d.title;
    $('#modalBody').innerHTML = fill(d.html);
    $('#legalModal').style.display = 'flex';
  }
  FRX.legal = { open: openLegal };

  D.addEventListener('click', function (e) {
    var t = e.target.closest && e.target.closest('[data-frx-open]'); if (!t) return;
    e.preventDefault();
    var w = t.dataset.frxOpen;
    if (w === 'cookies') return showPrefs();
    if (w === 'direitos') { var lm = $('#legalModal'); if (lm) lm.style.display = 'none'; return showDSAR(); }
    openLegal(w);
  });

  /* Rodapé: links de privacidade */
  function footerLinks() {
    var ul = $$('.footer-col ul').filter(function (u) { return /Termos/.test(u.textContent); })[0];
    if (!ul || ul.dataset.frx) return; ul.dataset.frx = '1';
    [['Direitos do titular (LGPD)', 'direitos'], ['Cookies e preferências', 'cookies-prefs'], ['Sobre cookies', 'cookies']].forEach(function (p) {
      var li = D.createElement('li'), a = D.createElement('a'); a.textContent = p[0]; a.setAttribute('role', 'button'); a.tabIndex = 0;
      a.addEventListener('click', function () { openLegal(p[1]); });
      a.addEventListener('keydown', function (e) { if (e.key === 'Enter' || e.key === ' ') { e.preventDefault(); openLegal(p[1]); } });
      li.appendChild(a); ul.appendChild(li);
    });
    var fb = $('.footer-bottom span'); if (fb) fb.textContent = '© ' + new Date().getFullYear() + ' FinRendax. Todos os direitos reservados. Tratamento de dados conforme a LGPD (Lei 13.709/2018).';
  }

  /* ============================================================
     FORMULÁRIO DE LEAD SEGURO (honeypot + tempo mínimo + limite + consentimento + validação)
  ============================================================ */
  var formStart = Date.now();
  FRX.submitLead = function (email, opts) {
    opts = opts || {};
    return new Promise(function (resolve) {
      var fail = function (code, msg) { resolve({ ok: false, code: code, msg: msg }); };
      if (opts.honeypot) { log('Sentinela', 'info', 'Envio de robô descartado (honeypot)'); return resolve({ ok: true, silent: true }); }
      if (Date.now() - formStart < 1500) return fail('fast', 'Aguarde um instante e tente de novo.');
      email = String(email || '').trim().toLowerCase();
      if (!/^[^\s@]{1,64}@[^\s@]{1,190}\.[^\s@]{2,}$/.test(email) || /[<>"'`\\]/.test(email)) return fail('email', 'Informe um e-mail válido.');
      if (!opts.consent) return fail('consent', 'Marque a caixa de autorização para receber o guia.');
      var rl = CFG.leadRateLimit, hist = (store.get('leadhist') || []).filter(function (t) { return Date.now() - t < rl.windowMs; });
      if (hist.length >= rl.max) return fail('rate', 'Muitas tentativas. Tente novamente mais tarde.');
      var E = CFG.emailjs;
      if (!E || /SUA_|SEU_/.test(E.publicKey + E.serviceId + E.templateId)) { log('Sentinela', 'warn', 'EmailJS não configurado: lead NÃO foi enviado'); return fail('config', 'O envio do guia está indisponível no momento. Fale com a gente pelo e-mail no rodapé.'); }
      hist.push(Date.now()); store.set('leadhist', hist);
      loadScript('https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js').then(function () {
        return W.emailjs.send(E.serviceId, E.templateId, { user_email: email, guide_link: E.guideLink || '', consent_id: (getConsent() || {}).id || '' }, E.publicKey);
      }).then(function () { log('Formulário', 'info', 'Lead enviado ' + maskEmail(email)); resolve({ ok: true }); },
        function (err) { log('Formulário', 'warn', 'Falha no envio do lead: ' + ((err && err.text) || (err && err.message) || 'erro')); fail('send', 'Não conseguimos enviar agora. Tente novamente em alguns minutos.'); });
    });
  };

  /* ============================================================
     RASTREIO DE FUNIL (usado pelo agente "Analista de Conversão")
     Só conta eventos na sessão do próprio visitante; nada é enviado
     a terceiros aqui — isso é decisão do Guardião LGPD/EmailJS.
  ============================================================ */
  var CONV = { checkoutClicks: 0, leadAttempts: 0, leadOk: 0, leadFail: 0, lastFailCode: '' };
  D.addEventListener('click', function (e) {
    var t = e.target.closest && e.target.closest('.cta-checkout');
    if (t) CONV.checkoutClicks++;
  }, true);
  var _submitLead = FRX.submitLead;
  FRX.submitLead = function (email, opts) {
    CONV.leadAttempts++;
    return _submitLead(email, opts).then(function (r) {
      if (r.ok && !r.silent) CONV.leadOk++;
      else if (!r.ok) { CONV.leadFail++; CONV.lastFailCode = r.code; }
      return r;
    });
  };

  /* ============================================================
     AGENTES
  ============================================================ */
  var AGENTS = [], STATE = {};
  var RANK = { ok: 0, info: 1, warn: 2, crit: 3 };
  function worst(fs) { return fs.reduce(function (a, f) { return RANK[f.sev] > RANK[a] ? f.sev : a; }, 'ok'); }
  function agent(def) { AGENTS.push(def); STATE[def.name] = { status: 'ok', findings: [], last: 0, runs: 0 }; }
  function runAgent(a) {
    return Promise.resolve().then(function () { return a.run(); }).then(function (fs) {
      fs = fs && fs.length ? fs : [{ sev: 'ok', msg: 'Tudo em ordem.' }];
      var s = STATE[a.name]; s.findings = fs; s.status = worst(fs); s.last = Date.now(); s.runs++;
      fs.forEach(function (f) { if (RANK[f.sev] >= 2) log(a.name, f.sev, f.msg); });
      emit('agent', a.name);
    }).catch(function (e) { var s = STATE[a.name]; s.status = 'crit'; s.findings = [{ sev: 'crit', msg: 'Agente falhou: ' + e.message }]; s.last = Date.now(); log(a.name, 'crit', 'Agente falhou: ' + e.message); });
  }
  function schedule(a, first) {
    var tick = function () { if (D.hidden) return setTimeout(tick, 5000); idle(function () { runAgent(a).then(function () { setTimeout(tick, a.every * (0.9 + Math.random() * 0.2)); }); }); };
    setTimeout(tick, first);
  }
  FRX.runAll = function () { return Promise.all(AGENTS.map(runAgent)); };
  FRX.state = function () { return STATE; };

  /* ---- Efeitos visuais adaptativos (lidos pelo cenário 3D) ---- */
  var mem = navigator.deviceMemory || 4, cores = navigator.hardwareConcurrency || 4;
  var conn = navigator.connection || {};
  var startLevel = 'high';
  if (W.matchMedia('(prefers-reduced-motion: reduce)').matches || conn.saveData || mem <= 2 || cores <= 2) startLevel = 'low';
  else if (W.innerWidth < 768 || mem <= 4) startLevel = 'medium';
  var FX = FRX.fx = { level: startLevel, skip: 0, dpr: 2 };
  function setLevel(l) {
    FX.level = l; FX.skip = l === 'high' ? 0 : l === 'medium' ? 1 : 2; FX.dpr = l === 'high' ? 1.75 : l === 'medium' ? 1.25 : 1;
    ['high', 'medium', 'low'].forEach(function (x) { D.documentElement.classList.toggle('perf-' + x, x === l); });
    emit('fx', l);
  }
  setLevel(startLevel);

  var VIT = { fps: 0, lcp: 0, cls: 0, inp: 0, longTasks: 0 };
  function observe(type, cb) { try { new PerformanceObserver(function (l) { l.getEntries().forEach(cb); }).observe({ type: type, buffered: true }); } catch (e) {} }
  observe('largest-contentful-paint', function (e) { VIT.lcp = Math.round(e.startTime); });
  observe('layout-shift', function (e) { if (!e.hadRecentInput) VIT.cls = +(VIT.cls + e.value).toFixed(3); });
  observe('longtask', function () { VIT.longTasks++; });
  try { new PerformanceObserver(function (l) { l.getEntries().forEach(function (e) { if (e.duration > VIT.inp) VIT.inp = Math.round(e.duration); }); }).observe({ type: 'event', durationThreshold: 40, buffered: true }); } catch (e) {}
  var lowStreak = 0, highStreak = 0;
  function sampleFPS(ms) {
    return new Promise(function (res) {
      var n = 0, t0 = performance.now(); (function f(t) { n++; if (t - t0 < ms) requestAnimationFrame(f); else res(n * 1000 / (t - t0)); })(t0);
    });
  }

  agent({ name: 'Maestro de Performance', role: 'Mede FPS e Core Web Vitals e ajusta a qualidade dos efeitos 3D sozinho.', every: 20000, run: function () {
    return sampleFPS(1800).then(function (fps) {
      VIT.fps = Math.round(fps); var out = [];
      if (fps < 24) { lowStreak++; highStreak = 0; } else if (fps > 52) { highStreak++; lowStreak = 0; } else { lowStreak = highStreak = 0; }
      if (lowStreak >= 2 && FX.level !== 'low') { var n = FX.level === 'high' ? 'medium' : 'low'; setLevel(n); lowStreak = 0; out.push({ sev: 'info', msg: 'FPS baixo (' + VIT.fps + '): efeitos reduzidos para "' + n + '".' }); }
      if (highStreak >= 6 && FX.level !== 'high' && startLevel === 'high') { setLevel(FX.level === 'low' ? 'medium' : 'high'); highStreak = 0; out.push({ sev: 'info', msg: 'Desempenho estável: efeitos restaurados para "' + FX.level + '".' }); }
      out.push({ sev: VIT.fps < 20 ? 'warn' : 'ok', msg: 'FPS ' + VIT.fps + ' · qualidade ' + FX.level });
      if (VIT.lcp > 4000) out.push({ sev: 'warn', msg: 'LCP alto: ' + VIT.lcp + ' ms (meta < 2500).' }); else if (VIT.lcp) out.push({ sev: 'ok', msg: 'LCP ' + VIT.lcp + ' ms' });
      if (VIT.cls > 0.25) out.push({ sev: 'warn', msg: 'CLS alto: ' + VIT.cls + ' (meta < 0.1).' });
      if (VIT.inp > 500) out.push({ sev: 'warn', msg: 'Interação lenta (INP ~' + VIT.inp + ' ms).' });
      return out;
    });
  } });

  agent({ name: 'Sentinela', role: 'Segurança: links de checkout, injeção de código, CSP, clickjacking, envio de dados.', every: 45000, run: function () {
    var out = [];
    hardenLinks(D);
    if (!$('meta[http-equiv="Content-Security-Policy"]')) out.push({ sev: 'warn', msg: 'CSP via <meta> ausente (confirme se o servidor envia o cabeçalho).' });
    var ph = $$('a[href*="SEU_"],a[href*="SUA_"]'); if (ph.length) out.push({ sev: 'crit', msg: ph.length + ' link(s) ainda com placeholder (ex.: SEU_LINK_AQUI) — compradores cairiam numa página quebrada.' });
    var mixed = performance.getEntriesByType('resource').filter(function (r) { return /^http:\/\//i.test(r.name) && location.protocol === 'https:'; });
    if (mixed.length) out.push({ sev: 'crit', msg: mixed.length + ' recurso(s) via HTTP (conteúdo misto).' });
    if (W.top !== W.self) out.push({ sev: 'crit', msg: 'Página dentro de iframe.' });
    if (SEC.incidents) out.push({ sev: 'crit', msg: SEC.incidents + ' incidente(s) nesta sessão (' + SEC.injected + ' injeções, ' + SEC.hijack + ' links revertidos, ' + SEC.egressBlocked + ' envios bloqueados).' });
    if (SEC.csp) out.push({ sev: 'info', msg: SEC.csp + ' bloqueio(s) de CSP nesta sessão.' });
    if (!out.length) out.push({ sev: 'ok', msg: 'Sem incidentes. ' + $$('.cta-checkout').length + ' links de checkout verificados.' });
    return out;
  } });

  agent({ name: 'Guardião LGPD', role: 'Privacidade: consentimento, cookies e scripts de terceiros só depois do "sim".', every: 60000, run: function () {
    var out = [], c = getConsent();
    if (!c && !banner) out.push({ sev: 'warn', msg: 'Sem consentimento registrado e banner não está visível.' });
    var cookies = D.cookie ? D.cookie.split(';').map(function (x) { return x.split('=')[0].trim(); }) : [];
    var an = cookies.filter(function (n) { return /^(_ga|_gid|_gat)/.test(n); }), mk = cookies.filter(function (n) { return /^(_fbp|_fbc|fr)$/.test(n); });
    if (an.length && !(c && c.analytics)) { an.forEach(function (n) { D.cookie = n + '=; Max-Age=0; path=/'; }); out.push({ sev: 'crit', msg: 'Cookies de estatística sem consentimento (' + an.join(', ') + ') — removidos.' }); }
    if (mk.length && !(c && c.marketing)) { mk.forEach(function (n) { D.cookie = n + '=; Max-Age=0; path=/'; }); out.push({ sev: 'crit', msg: 'Cookies de marketing sem consentimento (' + mk.join(', ') + ') — removidos.' }); }
    var tp = $$('script[src]').map(function (s) { return hostOf(s.src); });
    if (!(c && c.analytics) && tp.some(function (h) { return /googletagmanager|google-analytics/.test(h); })) out.push({ sev: 'crit', msg: 'Script do Google carregado sem consentimento.' });
    if (!(c && c.marketing) && tp.some(function (h) { return /facebook/.test(h); })) out.push({ sev: 'crit', msg: 'Script da Meta carregado sem consentimento.' });
    var keys = []; try { for (var i = 0; i < localStorage.length; i++) keys.push(localStorage.key(i)); } catch (e) {}
    var foreign = keys.filter(function (k) { return k.indexOf('frx:') !== 0; });
    if (foreign.length) out.push({ sev: 'info', msg: 'Chaves de armazenamento de terceiros: ' + foreign.slice(0, 4).join(', ') });
    var form = $('#heroLeadForm'); if (form && !$('input[type=checkbox][required]', form)) out.push({ sev: 'crit', msg: 'Formulário de captura sem caixa de consentimento.' });
    if (!/@/.test(CFG.company.dpoEmail)) out.push({ sev: 'crit', msg: 'Sem e-mail do Encarregado (DPO).' });
    if (/\[.*preencher.*\]/i.test(JSON.stringify(CFG.company))) out.push({ sev: 'warn', msg: 'Dados da empresa na Política de Privacidade ainda são placeholders (razão social, CNPJ, endereço, encarregado).' });
    if (c) out.push({ sev: 'ok', msg: 'Consentimento ' + (c.analytics ? 'estatística ' : '') + (c.marketing ? 'marketing ' : '') + (!c.analytics && !c.marketing ? 'somente essenciais ' : '') + '(versão ' + c.v + ')' });
    return out;
  } });

  agent({ name: 'Inspetor de Links e Recursos', role: 'Navegação interna, imagens e scripts que falharam, placeholders esquecidos.', every: 90000, run: function () {
    var out = [];
    var tabs = ['recursos', 'quem-somos', 'servicos', 'educacao'];
    $$('[onclick*="showTab("]').forEach(function (n) { var m = /showTab\('([^']+)'\)/.exec(n.getAttribute('onclick') || ''); if (m && tabs.indexOf(m[1]) < 0) out.push({ sev: 'crit', msg: 'Link aponta para aba inexistente: ' + m[1] }); });
    tabs.forEach(function (t) { if (!D.getElementById(t)) out.push({ sev: 'crit', msg: 'Aba ausente: #' + t }); });
    var broken = $$('img').filter(function (i) { return i.complete && i.naturalWidth === 0 && !/^data:/.test(i.currentSrc || i.src); });
    if (broken.length) out.push({ sev: 'warn', msg: broken.length + ' imagem(ns) não carregou: ' + broken.map(function (i) { return (i.getAttribute('src') || '').slice(0, 30); }).join(', ') });
    var ig = $$('a[href*="SEU_USUARIO"]'); if (ig.length) out.push({ sev: 'warn', msg: ig.length + ' link(s) de Instagram com placeholder (SEU_USUARIO).' });
    if (FRXfailed.length) out.push({ sev: 'warn', msg: 'Falha ao carregar: ' + FRXfailed.slice(-3).join(', ') });
    return out;
  } });
  var FRXfailed = [];
  D.addEventListener('error', function (e) { var t = e.target; if (t && t !== W && (t.tagName === 'IMG' || t.tagName === 'SCRIPT' || t.tagName === 'LINK')) { var u = t.src || t.href || ''; if (!/^data:/.test(u)) FRXfailed.push(hostOf(u) + ' ' + String(u).split('/').pop().slice(0, 30)); } }, true);

  agent({ name: 'Analista de Acessibilidade', role: 'WCAG: nomes acessíveis, rótulos, hierarquia de títulos, foco de teclado.', every: 120000, run: function () {
    var out = [];
    var noAlt = $$('img:not([alt])'); if (noAlt.length) out.push({ sev: 'warn', msg: noAlt.length + ' imagem(ns) sem alt.' });
    var noName = $$('a[href],button').filter(function (n) { return !(n.textContent.trim() || n.getAttribute('aria-label') || n.getAttribute('title') || n.querySelector('img[alt]')); }); if (noName.length) out.push({ sev: 'warn', msg: noName.length + ' link(s)/botão(ões) sem nome acessível.' });
    var noLabel = $$('input:not([type=hidden]):not([type=checkbox]),select,textarea').filter(function (i) { return !(i.getAttribute('aria-label') || i.getAttribute('aria-labelledby') || (i.id && $('label[for="' + i.id + '"]')) || i.closest('label')); }); if (noLabel.length) out.push({ sev: 'warn', msg: noLabel.length + ' campo(s) sem rótulo.' });
    var act = $('.page-section.active') || D; var h1 = $$('h1', act).length; if (h1 !== 1) out.push({ sev: 'info', msg: 'A aba ativa tem ' + h1 + ' <h1> (ideal: 1).' });
    var clickDiv = $$('a:not([href])[onclick]').filter(function (a) { return !a.hasAttribute('role') && !a.hasAttribute('tabindex'); }); if (clickDiv.length) out.push({ sev: 'warn', msg: clickDiv.length + ' link(s) só com clique, sem teclado (sem href/tabindex).' });
    if (!D.documentElement.lang) out.push({ sev: 'warn', msg: '<html> sem lang.' });
    if (!$('.skip-link')) out.push({ sev: 'info', msg: 'Sem link "pular para o conteúdo".' });
    return out;
  } });

  agent({ name: 'Curador de SEO e Conteúdo', role: 'Título, descrição, dados estruturados e atualização do conteúdo (ano, taxa de referência).', every: 180000, run: function () {
    var out = [], t = D.title || '', md = ($('meta[name=description]') || {}).content || '';
    if (t.length < 25 || t.length > 65) out.push({ sev: 'info', msg: 'Título com ' + t.length + ' caracteres (ideal 30–60).' });
    if (md.length < 70 || md.length > 165) out.push({ sev: 'info', msg: 'Descrição com ' + md.length + ' caracteres (ideal 70–160).' });
    if (!$('link[rel=canonical]')) out.push({ sev: 'warn', msg: 'Falta <link rel="canonical">.' });
    var ld = $('script[type="application/ld+json"]'); if (!ld) out.push({ sev: 'info', msg: 'Sem dados estruturados (JSON-LD).' }); else { try { JSON.parse(ld.textContent); } catch (e) { out.push({ sev: 'warn', msg: 'JSON-LD inválido.' }); } }
    if (/SEU-DOMINIO/.test((($('link[rel=canonical]') || {}).href) || '')) out.push({ sev: 'warn', msg: 'Domínio ainda é placeholder (SEU-DOMINIO). Rode: node agents/setup.mjs https://seudominio.com.br' });
    var y = new Date().getFullYear(), fb = $('.footer-bottom span'); if (fb && fb.textContent.indexOf('©') === 0 && fb.textContent.indexOf(String(y)) < 0) { fb.textContent = fb.textContent.replace(/© \d{4}/, '© ' + y); out.push({ sev: 'info', msg: 'Ano do rodapé atualizado para ' + y + '.' }); }
    return out;
  } });

  agent({ name: 'Radar de Mercado', role: 'Lê data/market.json (atualizado no servidor com dados do Banco Central) e mostra a taxa de referência no simulador.', every: 600000, run: function () {
    if (!CFG.marketDataUrl) return [{ sev: 'info', msg: 'Desativado (sem fonte de dados configurada).' }];
    return fetch(CFG.marketDataUrl, { cache: 'no-cache' }).then(function (r) { if (!r.ok) throw new Error('HTTP ' + r.status); return r.json(); }).then(function (d) {
      var note = D.getElementById('simMarketNote'); if (!note) return [{ sev: 'info', msg: 'Sem campo de nota no simulador.' }];
      if (!d || typeof d.selicMetaAA !== 'number' || !d.date) { note.hidden = true; return [{ sev: 'info', msg: 'market.json ainda sem dados (o agente do servidor ainda não rodou).' }]; }
      var age = (Date.now() - Date.parse(d.updatedAt || 0)) / 864e5;
      note.textContent = 'Referência de mercado: Selic meta ' + d.selicMetaAA.toFixed(2).replace('.', ',') + '% ao ano (Banco Central, ' + d.date + ').';
      note.hidden = false;
      return age > 10 ? [{ sev: 'warn', msg: 'Dados de mercado com ' + Math.round(age) + ' dias — o agente do servidor parou?' }] : [{ sev: 'ok', msg: 'Selic meta ' + d.selicMetaAA + '% a.a. (' + d.date + ')' }];
    }).catch(function (e) { var n = D.getElementById('simMarketNote'); if (n) n.hidden = true; return [{ sev: 'info', msg: 'Dados de mercado indisponíveis (' + e.message + ').' }]; });
  } });

  var offlineDebounce = null, offlineErrorActive = false, pingBusy = false;
  function goOffline() {
    if (offlineErrorActive) return;
    offlineErrorActive = true;
    log('Guarda de Rede', 'crit', 'Conexão perdida — encaminhando o visitante para a tela de erro.');
    fail('offline', 'Conexão de internet perdida');
  }
  function goOnline() {
    if (!offlineErrorActive) return;
    offlineErrorActive = false;
    log('Guarda de Rede', 'info', 'Conexão de volta — retornando o visitante ao site automaticamente.');
    if (typeof W.leaveError === 'function') W.leaveError();
  }
  /* Verificação ativa: o evento online/offline do navegador só reflete a interface de rede,
     não se o servidor de fato responde (ex.: wifi conectado mas sem internet real, ou site fora
     do ar). Fazemos um ping leve e real, do jeito que grandes empresas verificam conectividade. */
  function pingCheck() {
    if (pingBusy || location.protocol === 'file:') return; /* sem servidor real para checar em teste local */
    pingBusy = true;
    var ctrl = (typeof AbortController !== 'undefined') ? new AbortController() : null;
    var to = setTimeout(function () { if (ctrl) ctrl.abort(); }, 5000);
    fetch(location.pathname + '?frxping=' + Date.now(), { method: 'HEAD', cache: 'no-store', signal: ctrl && ctrl.signal })
      .then(function () { clearTimeout(to); pingBusy = false; goOnline(); })
      .catch(function () { clearTimeout(to); pingBusy = false; goOffline(); });
  }
  function net() {
    if (!navigator.onLine) {
      if (offlineDebounce || offlineErrorActive) return;
      offlineDebounce = setTimeout(function () { offlineDebounce = null; if (!navigator.onLine) goOffline(); }, 1200); /* pequena espera para não disparar em quedas de meio segundo */
      return;
    }
    if (offlineDebounce) { clearTimeout(offlineDebounce); offlineDebounce = null; }
    pingCheck(); /* confirma que a conexão voltou de verdade, não só a interface de rede */
  }
  W.addEventListener('online', net); W.addEventListener('offline', net);
  W.setInterval(pingCheck, 20000); /* checagem ativa periódica, igual grandes empresas fazem */
  agent({ name: 'Guarda de Rede', role: 'Conexão do visitante: leva à tela de erro personalizada se a internet cair (com checagem ativa real, não só o sinal do navegador) e traz de volta ao site sozinho assim que reconectar; também cuida de dependências externas (ícones, 3D) e destinos de saída fora da lista.', every: 60000, run: function () {
    net(); var out = [];
    if (!navigator.onLine) out.push({ sev: 'crit', msg: 'Visitante offline — tela de erro personalizada ativa.' });
    if (typeof W.lucide === 'undefined') out.push({ sev: 'warn', msg: 'Biblioteca de ícones (lucide) não carregou.' });
    if (typeof W.THREE === 'undefined' && FX.level !== 'off') out.push({ sev: 'info', msg: 'Cenário 3D ainda não carregou (ou foi desativado).' });
    if (conn.effectiveType && /(^|-)2g$/.test(conn.effectiveType)) out.push({ sev: 'info', msg: 'Conexão lenta (' + conn.effectiveType + ').' });
    var ext = LOG.filter(function (l) { return l.agent === 'Rede' && Date.now() - l.t < 3.6e6; }).length; if (ext) out.push({ sev: 'info', msg: ext + ' requisição(ões) para destinos fora da lista na última hora.' });
    return out;
  } });

  /* ---- Escrivão de Erros: captura, agrupa e decide quando levar o visitante à página 404/erro (sincronizado com o Guarda de Rede acima para quedas de conexão) ---- */
  var ERR = { recent: [], total: 0 };
  var errShown = false;
  function fail(code, detail) {
    if (errShown) return; errShown = true;
    log('Escrivão de Erros', 'crit', 'Tela de erro (' + code + '): ' + detail);
    try { W.dispatchEvent(new CustomEvent('frx:error', { detail: { code: code, ref: 'FRX-' + uid(3) } })); } catch (e) {}
    setTimeout(function () { errShown = false; }, 30000);
  }
  FRX.fail = fail;
  function onErr(kind, msg, src) {
    var own = !src || src.indexOf(location.origin) === 0 || src.indexOf('file:') === 0 || src === '';
    ERR.total++;
    if (!own) { log('Escrivão de Erros', 'info', 'Erro em script de terceiro ignorado: ' + hostOf(src)); return; }
    var now = Date.now(); ERR.recent = ERR.recent.filter(function (t) { return now - t < 10000; }); ERR.recent.push(now);
    log('Escrivão de Erros', 'warn', kind + ': ' + String(msg).slice(0, 140));
    if (ERR.recent.length >= 5) fail(500, 'Vários erros seguidos na página');
  }
  W.addEventListener('error', function (e) { if (e.target === W || !e.target) onErr('Erro de script', e.message, e.filename || ''); });
  W.addEventListener('unhandledrejection', function (e) { var r = e.reason; onErr('Promessa rejeitada', (r && r.message) || r, ''); });
  agent({ name: 'Escrivão de Erros', role: 'Captura erros de JavaScript, agrupa e leva o visitante à página de erro quando a página quebra de vez.', every: 30000, run: function () {
    var out = [];
    if (!D.getElementById('recursos') || !$('.page-section.active')) { out.push({ sev: 'crit', msg: 'Nenhuma aba ativa — conteúdo principal ausente.' }); fail(500, 'Conteúdo principal não carregou'); }
    if (ERR.total) out.push({ sev: ERR.total > 3 ? 'warn' : 'info', msg: ERR.total + ' erro(s) capturado(s) nesta sessão.' });
    return out;
  } });

  agent({ name: 'Analista de Conversão', role: 'Funil: botões de compra com link quebrado, cliques de checkout e taxa de sucesso do formulário de lead.', every: 45000, run: function () {
    var out = [];
    var broken = $$('.cta-checkout').filter(function (a) { return /SEU_LINK_AQUI/.test(a.getAttribute('href') || ''); });
    if (broken.length) out.push({ sev: 'crit', msg: broken.length + ' botão(ões) "Garantir acesso" ainda com link de checkout placeholder (SEU_LINK_AQUI) — ninguém consegue comprar. Troque pelo link real do Kiwify.' });
    if (CONV.checkoutClicks) out.push({ sev: 'info', msg: CONV.checkoutClicks + ' clique(s) em botão de checkout nesta sessão.' });
    if (CONV.leadAttempts) {
      var rate = Math.round((CONV.leadOk / CONV.leadAttempts) * 100);
      var sev = (CONV.leadFail && !CONV.leadOk) ? 'warn' : 'info';
      out.push({ sev: sev, msg: CONV.leadOk + '/' + CONV.leadAttempts + ' envio(s) de guia com sucesso (' + rate + '%)' + (CONV.lastFailCode ? '; última falha: ' + CONV.lastFailCode : '') + '.' });
    }
    return out;
  } });

  /* ---- Painel de diagnóstico (?ops=1 ou Alt+Shift+O) ---- */
  var panel = null;
  function ago(t) { if (!t) return 'nunca'; var s = Math.round((Date.now() - t) / 1000); return s < 60 ? s + 's' : Math.round(s / 60) + 'min'; }
  function esc(s) { return String(s).replace(/[&<>"']/g, function (c) { return { '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c]; }); }
  function renderPanel() {
    if (!panel) return;
    var h = '<h3>Central de Agentes <button class="frx-btn" data-o="close" aria-label="Fechar painel">✕</button></h3>' +
      '<div class="frx-vit"><div><b>' + VIT.fps + '</b><span>FPS</span></div><div><b>' + (VIT.lcp || '–') + '</b><span>LCP ms</span></div><div><b>' + VIT.cls + '</b><span>CLS</span></div><div><b>' + FX.level + '</b><span>efeitos</span></div></div>' +
      '<div class="frx-actions" style="margin:0 0 10px"><button class="frx-btn pri" data-o="run">Rodar todos agora</button><button class="frx-btn" data-o="copy">Copiar relatório</button></div>';
    AGENTS.forEach(function (a) {
      var s = STATE[a.name];
      h += '<section class="frx-ag"><header><i class="frx-dot ' + s.status + '"></i><b>' + esc(a.name) + '</b><span style="color:#94a3b8">' + ago(s.last) + '</span></header><div class="role">' + esc(a.role) + '</div><ul>' +
        s.findings.slice(0, 5).map(function (f) { return '<li class="' + f.sev + '">' + esc(f.msg) + '</li>'; }).join('') + '</ul></section>';
    });
    panel.innerHTML = h;
  }
  function togglePanel() {
    if (panel) { panel.remove(); panel = null; return; }
    panel = el('<aside class="frx-ops" role="complementary" aria-label="Central de agentes"></aside>');
    panel.addEventListener('click', function (e) {
      var b = e.target.closest('[data-o]'); if (!b) return;
      if (b.dataset.o === 'close') togglePanel();
      if (b.dataset.o === 'run') FRX.runAll().then(renderPanel);
      if (b.dataset.o === 'copy') { var txt = JSON.stringify({ at: new Date().toISOString(), vitals: VIT, agents: STATE, security: SEC }, null, 2); (navigator.clipboard ? navigator.clipboard.writeText(txt) : Promise.reject()).then(function () { b.textContent = 'Copiado ✓'; }, function () { b.textContent = 'Não foi possível copiar'; }); }
    });
    D.body.appendChild(panel); renderPanel();
  }
  function sha256js(msg) {
    var K = [], H = [], i, j, p = 2, isP = function (n) { for (var k = 2; k * k <= n; k++) if (n % k === 0) return false; return true; }, fr = function (x) { return ((x - Math.floor(x)) * 4294967296) | 0; };
    for (i = 0; K.length < 64; p++) if (isP(p)) { K.push(fr(Math.pow(p, 1 / 3))); if (H.length < 8) H.push(fr(Math.sqrt(p))); }
    var b = unescape(encodeURIComponent(msg)), l = b.length, w = [];
    for (i = 0; i < l; i++) w[i >> 2] |= b.charCodeAt(i) << (24 - (i % 4) * 8);
    w[l >> 2] |= 0x80 << (24 - (l % 4) * 8); w[(((l + 8) >> 6) << 4) + 15] = l * 8;
    for (i = 0; i < w.length; i++) w[i] = w[i] | 0;
    var R = function (x, n) { return (x >>> n) | (x << (32 - n)); };
    for (j = 0; j < w.length; j += 16) {
      var W2 = w.slice(j, j + 16), h = H.slice(0), a;
      for (i = 16; i < 64; i++) { var s0 = R(W2[i - 15], 7) ^ R(W2[i - 15], 18) ^ (W2[i - 15] >>> 3), s1 = R(W2[i - 2], 17) ^ R(W2[i - 2], 19) ^ (W2[i - 2] >>> 10); W2[i] = (W2[i - 16] + s0 + W2[i - 7] + s1) | 0; }
      for (i = 0; i < 64; i++) {
        var t1 = (h[7] + (R(h[4], 6) ^ R(h[4], 11) ^ R(h[4], 25)) + ((h[4] & h[5]) ^ (~h[4] & h[6])) + K[i] + W2[i]) | 0, t2 = ((R(h[0], 2) ^ R(h[0], 13) ^ R(h[0], 22)) + ((h[0] & h[1]) ^ (h[0] & h[2]) ^ (h[1] & h[2]))) | 0;
        h = [(t1 + t2) | 0, h[0], h[1], h[2], (h[3] + t1) | 0, h[4], h[5], h[6]];
      }
      for (i = 0; i < 8; i++) H[i] = (H[i] + h[i]) | 0;
    }
    return H.map(function (x) { return ('00000000' + (x >>> 0).toString(16)).slice(-8); }).join('');
  }
  function sha256(str) {
    if (W.crypto && crypto.subtle) return crypto.subtle.digest('SHA-256', new TextEncoder().encode(str)).then(function (b) { return Array.prototype.map.call(new Uint8Array(b), function (x) { return ('0' + x.toString(16)).slice(-2); }).join(''); });
    return Promise.resolve(sha256js(str));
  }
  var opsFails = 0;
  function requestOps() {
    if (panel) return togglePanel();
    var setup = /[?&]ops=setup/.test(location.search);
    if (!CFG.opsKeyHash && !setup) return;                       /* desativado: o público não vê nem sabe que existe */
    if (opsFails >= 5) return;
    var m = el('<div class="frx-modal" role="dialog" aria-modal="true" aria-label="Acesso restrito"><form class="frx-box" style="max-width:380px"><h3>' + (setup ? 'Criar senha do painel' : 'Acesso restrito') + '</h3>' +
      '<label for="frxPw">Senha</label><input id="frxPw" type="password" autocomplete="off" maxlength="80"><p id="frxPe" role="alert" style="margin-top:10px;color:#ff8a8a;word-break:break-all"></p>' +
      '<div class="frx-actions" style="margin-top:14px"><button class="frx-btn" type="button" data-x="close">Cancelar</button><button class="frx-btn pri" type="submit">' + (setup ? 'Gerar código' : 'Entrar') + '</button></div></form></div>');
    $('form', m).addEventListener('submit', function (e) {
      e.preventDefault(); var pw = $('#frxPw', m).value, out = $('#frxPe', m);
      sha256(pw).then(function (h) {
        if (setup) { out.style.color = '#d9a043'; out.textContent = 'Cole no FRX_CONFIG → opsKeyHash: ' + h; return; }
        if (h === CFG.opsKeyHash) { unlocked = true; closeModal(m); togglePanel(); }
        else { opsFails++; out.textContent = 'Senha incorreta.'; }
      }, function (er) { out.textContent = 'Indisponível: ' + er.message; });
    });
    m.addEventListener('click', function (e) { var x = e.target.closest('[data-x]'); if (x) closeModal(m); });
    openModal(m);
  }
  on('agent', renderPanel);
  D.addEventListener('keydown', function (e) { if (e.altKey && e.shiftKey && (e.code === 'KeyO')) { e.preventDefault(); requestOps(); } });

  /* ============================================================
     INICIALIZAÇÃO
  ============================================================ */
  function init() {
    injectCSS(); hardenLinks(D); guardDOM(); footerLinks();
    var c = getConsent();
    if (c) applyConsent(c);
    else { if (gpc()) log('Guardião LGPD', 'info', 'Sinal Global Privacy Control detectado: nenhum rastreador será ativado sem escolha explícita.'); setTimeout(showBanner, 900); }
    AGENTS.forEach(function (a, i) { schedule(a, 2500 + i * 1500); });
    if (/[?&]ops(=|&|$)/.test(location.search)) setTimeout(requestOps, 1200);
    var taps = 0, tapT = 0; $$('nav .brand').forEach(function (b) { b.addEventListener('click', function () { var n = Date.now(); taps = n - tapT < 1800 ? taps + 1 : 1; tapT = n; if (taps >= 5) { taps = 0; requestOps(); } }); });
    formStart = Date.now();
    log('Orquestrador', 'info', AGENTS.length + ' agentes ativos · efeitos "' + FX.level + '"');
  }
  if (D.readyState === 'loading') D.addEventListener('DOMContentLoaded', init); else init();
  /* Só o mínimo fica acessível pelo console do visitante; config, logs e estado dos agentes ficam dentro da função */
  W.FRX = Object.freeze({ __ready: true, fx: FX, on: on, legal: FRX.legal, consent: FRX.consent, submitLead: FRX.submitLead, fail: fail });
})();

</script>
<script>
document.addEventListener('DOMContentLoaded', () => { try { lucide.createIcons(); } catch(e) {} });
const prefersReduced = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

/* ============================================================
   TRACKING DE EVENTOS
============================================================ */
document.querySelectorAll('.cta-checkout').forEach(button => {
  button.addEventListener('click', function() {
    if (typeof fbq !== 'undefined') { fbq('track', 'InitiateCheckout'); }
    if (typeof gtag !== 'undefined') {
      gtag('event', 'begin_checkout', { 'event_category': 'ecommerce', 'event_label': 'Kiwify Checkout CTA' });
    }
  });
});

/* ============================================================
   TÍTULOS ANIMADOS PALAVRA A PALAVRA
============================================================ */
function splitWords(root){
  let idx = 0;
  (function walk(node){
    Array.from(node.childNodes).forEach(child=>{
      if(child.nodeType === 3){
        const parts = child.textContent.split(/(\s+)/);
        const frag = document.createDocumentFragment();
        parts.forEach(p=>{
          if(!p) return;
          if(/^\s+$/.test(p)){ frag.appendChild(document.createTextNode(' ')); return; }
          const w = document.createElement('span'); w.className = 'w';
          const wi = document.createElement('span'); wi.className = 'wi';
          wi.style.setProperty('--wd', idx++); wi.textContent = p;
          w.appendChild(wi); frag.appendChild(w);
        });
        node.replaceChild(frag, child);
      } else if(child.nodeType === 1 && child.tagName !== 'BR'){
        walk(child);
      }
    });
  })(root);
}
document.querySelectorAll('.hero h1, .section-title').forEach(splitWords);
/* Título do hero entra imediatamente */
requestAnimationFrame(()=>requestAnimationFrame(()=>{
  const h1 = document.querySelector('.hero h1'); if(h1) h1.classList.add('in');
}));
/* Títulos que não estão dentro de blocos .reveal */
document.querySelectorAll('.section-title').forEach(t=>{ if(!t.closest('.reveal')) t.classList.add('in'); });

/* ============================================================
   SIMULADOR DE INVESTIMENTOS (aba Educação)
============================================================ */
const simState = { total:0, invested:0, gain:0 };
const brl = v => v.toLocaleString('pt-BR', { style: 'currency', currency: 'BRL' });
const simRaf = {};
function tween(el, key, to){
  cancelAnimationFrame(simRaf[key]);
  const from = simState[key]; const t0 = performance.now(); const dur = prefersReduced ? 1 : 420;
  function step(now){
    const p = Math.min(1,(now-t0)/dur), e = 1 - Math.pow(1-p,3);
    const v = from + (to-from)*e; simState[key] = v;
    el.textContent = brl(v);
    if(p<1) simRaf[key] = requestAnimationFrame(step); else simState[key] = to;
  }
  simRaf[key] = requestAnimationFrame(step);
}
function setFill(range){
  const min = +range.min, max = +range.max, val = Math.min(Math.max(+range.value,min),max);
  range.style.setProperty('--fill', ((val-min)/(max-min)*100)+'%');
}
function syncFromNumber(which){
  const num = document.getElementById(which==='amount'?'simAmount':'simMonths');
  const rng = document.getElementById(which==='amount'?'simAmountRange':'simMonthsRange');
  rng.value = num.value; setFill(rng);
}
function syncFromRange(which){
  const num = document.getElementById(which==='amount'?'simAmount':'simMonths');
  const rng = document.getElementById(which==='amount'?'simAmountRange':'simMonthsRange');
  num.value = rng.value; setFill(rng);
}
function updateSimulation(fromUser) {
  const amount = Math.max(0, parseFloat(document.getElementById('simAmount').value) || 0);
  const months = Math.min(600, Math.max(0, Math.floor(parseFloat(document.getElementById('simMonths').value) || 0)));
  const rate = 0.008;
  let total = 0; const series = [0];
  for(let i = 0; i < months; i++) { total = (total + amount) * (1 + rate); series.push(total); }
  const invested = amount * months, gain = total - invested;

  tween(document.getElementById('simTotal'), 'total', total);
  tween(document.getElementById('simInvested'), 'invested', invested);
  tween(document.getElementById('simGain'), 'gain', gain);
  document.getElementById('simDelta').textContent = `↑ ${months}m proj.`;

  /* Gráfico */
  const W = 600, H = 220, pad = 14;
  const maxV = Math.max(total, invested, 1);
  const y = v => (H - (v / maxV) * (H - pad)).toFixed(1);
  const line = document.getElementById('simLinePath'), area = document.getElementById('simAreaPath'), inv = document.getElementById('simInvestedPath');
  if(months >= 1){
    const pts = series.map((v,i)=> `${((i/months)*W).toFixed(1)},${y(v)}`);
    line.setAttribute('d', 'M' + pts.join('L'));
    area.setAttribute('d', 'M' + pts.join('L') + `L${W},${H}L0,${H}Z`);
    inv.setAttribute('d', `M0,${H}L${W},${y(invested)}`);
  } else { line.setAttribute('d',''); area.setAttribute('d',''); inv.setAttribute('d',''); }

  /* Botões de CTA refletem o resultado (só troca o texto: não recria ícones nem varre o DOM) */
  const label = (fromUser && total > 0) ? `Quero alcançar ${brl(total)} por R$27` : `Garantir meu acesso por R$27`;
  ['ctaPricingBtn','ctaSimBtn'].forEach(id=>{
    const btn = document.getElementById(id);
    if(!btn || !(fromUser || id==='ctaSimBtn')) return;
    let tn = Array.from(btn.childNodes).find(n => n.nodeType === 3 && n.nodeValue.trim());
    if(!tn){ tn = document.createTextNode(''); btn.insertBefore(tn, btn.firstChild); }
    tn.nodeValue = label + ' ';
  });
}
setFill(document.getElementById('simAmountRange'));
setFill(document.getElementById('simMonthsRange'));
updateSimulation(false);

/* ============================================================
   MODAIS LEGAIS
============================================================ */
function openLegal(type) {
  if (window.FRX && FRX.legal) return FRX.legal.open(type);
  document.getElementById('modalTitle').textContent = 'Informações legais';
  document.getElementById('modalBody').textContent = 'Carregando… se esta mensagem persistir, escreva para finrendax@gmail.com.';
  document.getElementById('legalModal').style.display = 'flex';
}
function closeLegal() { document.getElementById('legalModal').style.display = 'none'; }

window.addEventListener('keydown', (e) => {
  if (e.key === 'Escape') { closeLegal(); closeMenu(); }
});

/* Submissão de Lead (Modal) — validação, consentimento, anti-robô e limite ficam em FRX.submitLead */
function handleHeroLead(e) {
  e.preventDefault();
  const btn = document.getElementById('submitBtn');
  const errBox = document.getElementById('heroLeadError');
  const showErr = (m) => { errBox.textContent = m; errBox.classList.add('show'); };
  errBox.classList.remove('show');
  if (!window.FRX) { showErr('Carregando… tente novamente em instantes.'); return; }
  btn.disabled = true;
  const original = btn.innerHTML;
  btn.textContent = 'Enviando...';
  FRX.submitLead(document.getElementById('heroEmail').value, {
    consent: document.getElementById('heroConsent').checked,
    honeypot: document.getElementById('heroWebsite').value
  }).then(r => {
    btn.disabled = false; btn.innerHTML = original;
    if (r.ok) {
      if (typeof fbq !== 'undefined') fbq('track', 'Lead');
      if (typeof gtag !== 'undefined') gtag('event', 'generate_lead', { 'event_category': 'engagement' });
      document.getElementById('heroLeadForm').style.display = 'none';
      document.getElementById('heroLeadSuccess').style.display = 'block';
    } else { showErr(r.msg); }
    try { lucide.createIcons(); } catch(_) {}
  });
}

/* ============================================================
   MENU HAMBÚRGUER
============================================================ */
const menuToggle = document.getElementById('menuToggle');
const mobileNav = document.getElementById('mobileNav');
function setMenu(open){
  mobileNav.classList.toggle('open', open);
  document.body.classList.toggle('menu-open', open);
  menuToggle.setAttribute('aria-expanded', open);
  menuToggle.setAttribute('aria-label', open ? 'Fechar Menu de Navegação' : 'Abrir Menu de Navegação');
}
function closeMenu(){ setMenu(false); }
menuToggle.addEventListener('click', () => setMenu(!mobileNav.classList.contains('open')));

/* ============================================================
   SPA TABS + ROTAS (#/servicos …) — botão voltar funciona; rota inválida vai para a página de erro
============================================================ */
let docHCache = 0, docHDirty = true;
/* ============================================================
   TELA DE ERRO INTERNA — mostra só o essencial (código amigável e uma referência aleatória)
============================================================ */
const ERRS = {
  404:['Essa página não rendeu.','Mas o seu dinheiro pode.','O endereço que você abriu não existe ou mudou de lugar. Nada de errado com você nem com a sua compra, só com o caminho.','Página não encontrada'],
  403:['Essa porta está fechada.','Mas há outras abertas.','Você não tem permissão para abrir este endereço. Se acha que deveria ter, fale com a gente.','Acesso não permitido'],
  500:['Algo travou do nosso lado.','Já dá para tentar de novo.','Aconteceu um erro inesperado ao carregar a página. Os dados da sua compra ficam na Kiwify e não são afetados por isso.','Erro inesperado'],
  503:['Estamos em manutenção rápida.','Volte em instantes.','O site está temporariamente indisponível. Tente novamente daqui a pouco.','Site indisponível'],
  offline:['Sua conexão caiu.','Mas a gente espera por você.','Parece que a internet ficou instável ou saiu do ar agora. Assim que ela voltar, esta página volta sozinha para o site — não precisa fazer nada.','Sem conexão']
};
let erroBuilt = false;
const baseTitle = document.title;
function showError(code, ref){
  const c = ERRS[code] || ERRS[404];
  if(!erroBuilt){
    const sw = document.getElementById('erSwing'), first = sw.firstChild, N = 15;
    for(let i=0;i<N;i++){ const d = document.createElement('div'); d.className='er-slab'; d.style.transform = `translateZ(${(i-(N-1)/2)*2}px)`; sw.insertBefore(d, first); }
    erroBuilt = true;
  }
  ref = ref || ('FRX-' + Math.random().toString(16).slice(2,8).toUpperCase());
  const t = document.getElementById('erTitle'); t.firstChild.nodeValue = c[0]; t.querySelector('span').textContent = c[1];
  document.getElementById('erLead').textContent = c[2];
  document.getElementById('erCode').textContent = code === 'offline' ? 'OFF' : (ERRS[code] ? code : 404);
  document.getElementById('erRef').textContent = 'Código de referência: ' + ref;
  document.getElementById('erMail').href = 'mailto:finrendax@gmail.com?subject=' + encodeURIComponent('Problema no site — ' + ref);
  document.querySelectorAll('.page-section').forEach(x=>x.classList.remove('active'));
  document.querySelectorAll('.nav-links a,.mobile-nav a.menu-link').forEach(l=>l.classList.remove('active'));
  document.getElementById('erro').classList.add('active');
  document.title = c[3] + ' — FinRendax';
  closeMenu();
  window.scrollTo({top:0, behavior:'auto'});
  docHDirty = true;
}
function leaveError(){ document.title = baseTitle; showTab('recursos'); }
window.addEventListener('frx:error', e => showError(e.detail.code, e.detail.ref));

const TABS = ['recursos','quem-somos','servicos','educacao'];
function showTab(tabId, fromRoute){
  if(!TABS.includes(tabId)){
    showError(404);
    return;
  }
  document.querySelectorAll('.page-section').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.nav-links a').forEach(l=>l.classList.remove('active'));
  const navEl = document.getElementById('nav-'+tabId);
  if(navEl) navEl.classList.add('active');
  document.querySelectorAll('.mobile-nav a.menu-link').forEach(l=>l.classList.remove('active'));
  const mobEl = document.getElementById('mob-'+tabId);
  if(mobEl) mobEl.classList.add('active');
  document.getElementById(tabId).classList.add('active');
  if(document.title !== baseTitle) document.title = baseTitle;
  closeMenu();
  if(!fromRoute){ const h = '#/'+tabId; if(location.hash !== h) { try { history.pushState({tab:tabId}, '', h); } catch(e) {} } }
  /* rolagem longa em conteúdo pesado trava: só anima quando o trajeto é curto */
  const far = window.scrollY > window.innerHeight * 2;
  window.scrollTo({top:0, behavior: (far || prefersReduced) ? 'auto' : 'smooth'});
  requestAnimationFrame(observeReveals);
  docHDirty = true;
}
function routeFromHash(){
  const m = /^#\/(.*)$/.exec(location.hash);
  if(!m) return;
  const id = decodeURIComponent(m[1] || 'recursos');
  const cur = document.querySelector('.page-section.active');
  if(!cur || cur.id !== id) showTab(id, true);
}
window.addEventListener('popstate', routeFromHash);
window.addEventListener('hashchange', routeFromHash);
routeFromHash();
if(location.protocol !== 'file:' && !/(\/|\/index\.html)$/.test(location.pathname)) showError(404);

/* FAQ */
function toggleFaq(el){
  const item = el.parentElement;
  const active = item.classList.contains('active');
  document.querySelectorAll('.faq-item').forEach(i=>i.classList.remove('active'));
  if(!active) item.classList.add('active');
}

/* Carrossel */
let currentSlide = 0;
const totalSlides = 5;
const track = document.getElementById('carouselTrack');
const dots = document.querySelectorAll('.dot');
let autoTimer;
function updateSlide(){
  track.style.transform = `translate3d(-${currentSlide*100}%, 0, 0)`;
  dots.forEach((d,i)=>d.classList.toggle('active', i===currentSlide));
}
function nextSlide(){ currentSlide=(currentSlide+1)%totalSlides; updateSlide(); resetTimer(); }
function prevSlide(){ currentSlide=(currentSlide-1+totalSlides)%totalSlides; updateSlide(); resetTimer(); }
function goToSlide(i){ currentSlide=i; updateSlide(); resetTimer(); }
function startTimer(){ clearInterval(autoTimer); autoTimer = setInterval(nextSlide, 5500); }
function resetTimer(){ clearInterval(autoTimer); startTimer(); }
startTimer();
const sliderEl = document.getElementById('testimonialSlider');
sliderEl.addEventListener('mouseenter', ()=>clearInterval(autoTimer));
sliderEl.addEventListener('mouseleave', startTimer);
document.addEventListener('visibilitychange', ()=>{ document.hidden ? clearInterval(autoTimer) : startTimer(); });
new IntersectionObserver(([en])=>{ en.isIntersecting ? startTimer() : clearInterval(autoTimer); }, {threshold:0.2}).observe(sliderEl);
let touchStartX = 0;
sliderEl.addEventListener('touchstart', e=>{ touchStartX = e.touches[0].clientX; }, {passive:true});
sliderEl.addEventListener('touchend', e=>{
  const dx = e.changedTouches[0].clientX - touchStartX;
  if(dx > 40) prevSlide();
  if(dx < -40) nextSlide();
}, {passive:true});

/* ============================================================
   CONTADORES ANIMADOS
============================================================ */
function runCount(el){
  if(el.dataset.done) return; el.dataset.done = '1';
  const to = parseFloat(el.dataset.count), dec = parseInt(el.dataset.dec||'0',10), suf = el.dataset.suf || '';
  const fmt = v => v.toFixed(dec).replace('.',',') + suf;
  if(prefersReduced){ el.textContent = fmt(to); return; }
  const t0 = performance.now(), dur = 1600;
  (function step(now){
    const p = Math.min(1,(now-t0)/dur), e = 1 - Math.pow(1-p,4);
    el.textContent = fmt(to*e);
    if(p<1) requestAnimationFrame(step);
  })(t0);
}

/* ============================================================
   SCROLL REVEAL (com stagger nos filhos)
============================================================ */
function observeReveals(){
  const els = document.querySelectorAll('.page-section.active .reveal:not(.visible)');
  els.forEach(el=>{
    el.querySelectorAll('.card,.feat-row,.stat').forEach((c,i)=>c.style.setProperty('--i', i));
  });
  const io = new IntersectionObserver((entries)=>{
    entries.forEach(entry=>{
      if(entry.isIntersecting){
        entry.target.classList.add('visible');
        entry.target.querySelectorAll('[data-count]').forEach(runCount);
        io.unobserve(entry.target);
      }
    });
  }, {threshold:0.12, rootMargin:'0px 0px -60px 0px'});
  els.forEach(el=>io.observe(el));
  /* contadores já visíveis (ex.: hero) */
  document.querySelectorAll('.page-section.active .reveal.visible [data-count]').forEach(runCount);
}
observeReveals();

/* ============================================================
   TILT 3D + SPOTLIGHT + BOTÕES MAGNÉTICOS
============================================================ */
const canHover = window.matchMedia('(hover:hover) and (pointer:fine)').matches;
if(canHover && !prefersReduced){
  function bindTilt(el, max){
    let raf = 0, cx = 0, cy = 0;
    const apply = () => {
      raf = 0;
      const r = el.getBoundingClientRect();
      const px = (cx - r.left)/r.width, py = (cy - r.top)/r.height;
      el.classList.remove('idle');
      el.style.setProperty('--ry', ((px-.5)*max*2).toFixed(2)+'deg');
      el.style.setProperty('--rx', ((.5-py)*max*2).toFixed(2)+'deg');
      el.style.setProperty('--mx', (px*100).toFixed(1)+'%');
      el.style.setProperty('--my', (py*100).toFixed(1)+'%');
    };
    el.addEventListener('pointermove', e=>{
      if(window.FRX && FRX.fx.level === 'low') return;
      cx = e.clientX; cy = e.clientY;
      if(!raf) raf = requestAnimationFrame(apply);
    }, {passive:true});
    el.addEventListener('pointerleave', ()=>{
      cancelAnimationFrame(raf); raf = 0;
      el.style.setProperty('--rx','0deg'); el.style.setProperty('--ry','0deg');
    });
  }
  document.querySelectorAll('.card').forEach(el=>bindTilt(el,5));
  document.querySelectorAll('.feat-row').forEach(el=>bindTilt(el,4));
  document.querySelectorAll('[data-tilt]').forEach(el=>bindTilt(el, parseFloat(el.dataset.tilt)||5));
  document.querySelectorAll('[data-tilt-stage]').forEach(el=>bindTilt(el, parseFloat(el.dataset.tiltStage)||8));

  /* Botões magnéticos */
  document.querySelectorAll('.btn').forEach(b=>{
    b.addEventListener('pointermove', e=>{
      const r = b.getBoundingClientRect();
      b.style.setProperty('--bx', ((e.clientX-(r.left+r.width/2))*.14).toFixed(1)+'px');
      b.style.setProperty('--by', ((e.clientY-(r.top+r.height/2))*.22).toFixed(1)+'px');
    });
    b.addEventListener('pointerleave', ()=>{ b.style.setProperty('--bx','0px'); b.style.setProperty('--by','0px'); });
  });

  /* Brilho que segue o cursor */
  const glow = document.getElementById('cursorGlow');
  let gx = 0, gy = 0, gTick = false;
  window.addEventListener('pointermove', e=>{
    gx = e.clientX; gy = e.clientY;
    if(!gTick){ gTick = true; requestAnimationFrame(()=>{ glow.style.transform = `translate3d(${gx}px,${gy}px,0)`; gTick = false; }); }
  }, {passive:true});
} else {
  document.querySelectorAll('.tilt-3d').forEach(el=>el.classList.remove('idle'));
}

/* ============================================================
   PROGRESSO DE SCROLL + NAV COMPACTA
============================================================ */
const progressEl = document.getElementById('scrollProgress');
const mainNav = document.getElementById('mainNav');
let scrollTick = false;
function docMax(){ if(docHDirty){ docHCache = document.documentElement.scrollHeight - innerHeight; docHDirty = false; } return docHCache; }
window.addEventListener('resize', ()=>{ docHDirty = true; }, {passive:true});
window.addEventListener('load', ()=>{ docHDirty = true; });
setInterval(()=>{ docHDirty = true; }, 1500);
let navScrolled = false;
function onScroll(){
  const h = docMax();
  progressEl.style.transform = `scaleX(${h > 0 ? Math.min(1, scrollY / h) : 0})`;
  const sc = scrollY > 30;
  if(sc !== navScrolled){ navScrolled = sc; mainNav.classList.toggle('scrolled', sc); }
  scrollTick = false;
}
window.addEventListener('scroll', ()=>{ if(!scrollTick){ scrollTick = true; requestAnimationFrame(onScroll); } }, {passive:true});
onScroll();

/* ============================================================
   CENÁRIO 3D DE FUNDO (Three.js)
   Moedas douradas, forma metálica e partículas com parallax
============================================================ */
window.__initScene = function initScene(){
  if(typeof THREE === 'undefined') return;
  const canvas = document.getElementById('bg3d');
  let renderer;
  const FX = (window.FRX && FRX.fx) || { level:'high', skip:0, dpr:1.75 };
  const isMobile = innerWidth < 768;
  const hq = FX.level === 'high' && !isMobile;
  try { renderer = new THREE.WebGLRenderer({ canvas, alpha:true, antialias:hq, powerPreference:'low-power' }); }
  catch(e){ canvas.style.display = 'none'; return; }
  const setDPR = () => renderer.setPixelRatio(Math.min(devicePixelRatio || 1, FX.dpr || 1.5));
  setDPR();
  if(window.FRX) FRX.on('fx', ()=>{ setDPR(); resize(); });
  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(50, 1, 0.1, 100);
  camera.position.set(0, 0, 10);

  scene.add(new THREE.AmbientLight(0xffffff, 0.55));
  const key = new THREE.DirectionalLight(0xffd79a, 1.5); key.position.set(5, 6, 6); scene.add(key);
  const rim = new THREE.PointLight(0xa32e3e, 2.4, 40); rim.position.set(-7, -3, 4); scene.add(rim);
  const fill = new THREE.PointLight(0xd9a043, 1.2, 30); fill.position.set(6, -4, 3); scene.add(fill);

  const world = new THREE.Group(); scene.add(world);
  const mobScale = isMobile ? 0.62 : 1;

  /* Estrutura em fio (ícosaedro) + nó metálico */
  const ico = new THREE.Mesh(
    new THREE.IcosahedronGeometry(2.7, 1),
    new THREE.MeshBasicMaterial({ color: 0xa32e3e, wireframe: true, transparent: true, opacity: 0.32 })
  );
  ico.position.set(isMobile ? 2.4 : 5.2, 0.8, -4);
  ico.scale.setScalar(mobScale);
  world.add(ico);

  const knot = new THREE.Mesh(
    new THREE.TorusKnotGeometry(0.95, 0.3, hq ? 160 : 96, hq ? 18 : 10),
    new THREE.MeshStandardMaterial({ color: 0x8e2434, metalness: 0.75, roughness: 0.28, transparent: true, opacity: 0.9 })
  );
  knot.position.copy(ico.position); knot.scale.setScalar(mobScale);
  world.add(knot);

  /* Moedas */
  const coinGeo = new THREE.CylinderGeometry(0.5, 0.5, 0.09, hq ? 56 : 32);
  const ringGeo = new THREE.TorusGeometry(0.37, 0.028, 10, 48);
  const goldMat = new THREE.MeshStandardMaterial({ color: 0xd9a043, metalness: 0.85, roughness: 0.28 });
  const darkGold = new THREE.MeshStandardMaterial({ color: 0x9b6a1c, metalness: 0.8, roughness: 0.4 });
  const coins = [];
  const coinCount = hq ? 11 : 6;
  for(let i = 0; i < coinCount; i++){
    const g = new THREE.Group();
    const body = new THREE.Mesh(coinGeo, goldMat);
    body.rotation.x = Math.PI / 2;
    const r1 = new THREE.Mesh(ringGeo, darkGold); r1.position.z = 0.05;
    const r2 = new THREE.Mesh(ringGeo, darkGold); r2.position.z = -0.05;
    g.add(body, r1, r2);
    const side = i % 2 === 0 ? 1 : -1;
    const spreadX = isMobile ? 2.6 : 4.2;
    g.position.set(side * (spreadX + Math.random() * (isMobile ? 1.6 : 4)), (Math.random() - 0.5) * 9, -5 + Math.random() * 5);
    const s = (0.55 + Math.random() * 0.7) * mobScale; g.scale.setScalar(s);
    g.userData = { spin: 0.4 + Math.random() * 0.9, bob: 0.4 + Math.random() * 0.6, phase: Math.random() * 6.28, baseY: g.position.y, tilt: Math.random() * 1.2 };
    g.rotation.x = g.userData.tilt;
    coins.push(g); world.add(g);
  }

  /* Partículas */
  const pCount = hq ? 320 : 140;
  const pos = new Float32Array(pCount * 3);
  for(let i = 0; i < pCount; i++){
    pos[i*3] = (Math.random() - 0.5) * 26; pos[i*3+1] = (Math.random() - 0.5) * 16; pos[i*3+2] = -8 + Math.random() * 10;
  }
  const pGeo = new THREE.BufferGeometry(); pGeo.setAttribute('position', new THREE.BufferAttribute(pos, 3));
  const points = new THREE.Points(pGeo, new THREE.PointsMaterial({ color: 0xd9a043, size: 0.045, transparent: true, opacity: 0.7, depthWrite: false }));
  world.add(points);

  function resize(){
    const w = innerWidth, h = innerHeight;
    renderer.setSize(w, h, false);
    camera.aspect = w / h; camera.updateProjectionMatrix();
  }
  resize();
  let rzT = 0; window.addEventListener('resize', ()=>{ clearTimeout(rzT); rzT = setTimeout(resize, 150); });

  let mx = 0, my = 0, tx = 0, ty = 0, sy = 0, running = true;
  window.addEventListener('pointermove', e=>{ tx = (e.clientX / innerWidth - .5); ty = (e.clientY / innerHeight - .5); }, {passive:true});
  let looping = false, frame = 0;
  document.addEventListener('visibilitychange', ()=>{ running = !document.hidden; if(running && !looping) loop(); });

  const clock = new THREE.Clock();
  function loop(){
    if(!running){ looping = false; return; }
    looping = true;
    requestAnimationFrame(loop);
    frame++;
    if(FX.skip && (frame % (FX.skip + 1))) return;   /* qualidade adaptativa: pula quadros em máquinas lentas */
    const t = clock.getElapsedTime();
    const speed = prefersReduced ? 0.15 : 1;
    mx += (tx - mx) * 0.05; my += (ty - my) * 0.05;
    sy += ((window.scrollY || 0) - sy) * 0.08;

    ico.rotation.x = t * 0.12 * speed; ico.rotation.y = t * 0.18 * speed;
    knot.rotation.x = t * 0.28 * speed; knot.rotation.y = t * 0.2 * speed;
    coins.forEach(c=>{
      const d = c.userData;
      c.rotation.y = t * d.spin * speed;
      c.position.y = d.baseY + Math.sin(t * d.bob + d.phase) * 0.35 * speed;
    });
    points.rotation.y = t * 0.02 * speed;

    world.position.y = Math.min(sy * 0.0026, 5);
    world.rotation.y = mx * 0.35; world.rotation.x = my * 0.18;
    camera.position.x = mx * 0.8; camera.position.y = -my * 0.5;
    camera.lookAt(0, 0, 0);
    renderer.render(scene, camera);
  }
  loop();
};

/* Cenário 3D e demais efeitos pesados só começam depois que a página está interativa */
(function(){
  const start = () => {
    if(window.THREE){ window.__initScene(); return; }
    const sc = document.createElement('script');
    sc.src = 'https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js'; sc.async = true;
    sc.onload = () => { try { window.__initScene(); } catch(e) { console.warn('Cenário 3D indisponível', e); } };
    sc.onerror = () => { const c = document.getElementById('bg3d'); if(c) c.style.display = 'none'; };
    document.head.appendChild(sc);
  };
  const go = () => ('requestIdleCallback' in window) ? requestIdleCallback(start, {timeout:2500}) : setTimeout(start, 600);
  if(document.readyState === 'complete') go(); else window.addEventListener('load', go, {once:true});
  /* pausa animações infinitas fora da tela */
  if('IntersectionObserver' in window){
    const io = new IntersectionObserver(es => es.forEach(e => e.target.classList.toggle('frx-off', !e.isIntersecting)), {rootMargin:'80px'});
    document.querySelectorAll('.pricing-card,.btn-pulse,.cta-band,.tilt-3d.idle').forEach(n => io.observe(n));
  }
})();
</script>
</body>
</html>
