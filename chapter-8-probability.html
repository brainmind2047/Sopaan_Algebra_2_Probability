<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Probability</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}

  .theory{display:flex;flex-direction:column;gap:16px;padding-bottom:40px;}
  .hub{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .hub{grid-template-columns:repeat(3,1fr);} }
  .hub-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:8px;}
  .hub-card h3{font-family:'Fraunces',serif;font-size:18px;margin:0;color:var(--accent-text);}
  .hub-card p{margin:0;font-size:14px;color:var(--ink-soft);line-height:1.5;}
  .hub-btns{display:flex;flex-wrap:wrap;gap:8px;margin-top:auto;}
  .hub-btn{min-height:40px;border:1.5px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:8px 12px;font:600 14px 'Source Sans 3',sans-serif;cursor:pointer;text-align:left;}
  .hub-btn:hover{border-color:var(--gold);}
  .hub-btn.primary{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .note{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:18px;scroll-margin-top:120px;}
  .note h2{font-family:'Fraunces',serif;font-size:22px;margin:0 0 4px;color:var(--ink);}
  .note .lt{font-size:13.5px;color:var(--ink-soft);margin:0 0 12px;}
  .note .lt b{color:var(--accent-text);}
  .note h4{font:700 15px 'Source Sans 3',sans-serif;margin:16px 0 6px;color:var(--accent-text);}
  .note p,.note li{font-size:15.5px;line-height:1.6;}
  .note ul{padding-left:20px;margin:6px 0;}
  .keybox{background:var(--gold-soft);border-left:4px solid var(--gold);border-radius:8px;padding:10px 12px;margin:10px 0;font-size:15px;line-height:1.6;}
  .keybox b{color:var(--ink);}
  .ex{background:var(--paper-2);border-radius:10px;padding:12px;margin:10px 0;}
  .ex .exh{font-family:'Fraunces',serif;font-weight:700;color:var(--accent-text);margin-bottom:4px;}
  .ex .exl{font-size:15px;line-height:1.7;}
  .ttab{width:100%;border-collapse:collapse;font-size:14.5px;margin:8px 0;}
  .ttab th,.ttab td{border:1px solid var(--rule);padding:7px 8px;text-align:left;vertical-align:top;}
  .ttab th{background:var(--paper-2);}
  .tscroll{overflow-x:auto;}
  .mono{font-family:'IBM Plex Mono',monospace;font-size:.92em;}
  @media (max-width:480px){ .ttab{font-size:13.5px;} .ttab th,.ttab td{padding:6px;} }
  .note .figsvg{max-width:100%;height:auto;display:block;margin:8px auto;}

</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest">BM</div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">Grade 11 Algebra 2 · Chapter 8</div>
  <div class="chapter-title">Probability</div>
  <div class="chapter-sub">Theory Notes · Learning-Target Practice · Chapter Test</div><div class="chapter-credit">Follows the lesson structure of Big Ideas Math Algebra 2, Chapter 8</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series · Grade 11 Algebra 2 · Chapter 8<br>Lessons and learning targets follow <i>Big Ideas Math Algebra 2</i>, Chapter 8 (Big Ideas Learning). Theory notes, questions and worked solutions are written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).toLowerCase().replace(/\s+/g,'').replace(/^[a-z]\(x\)=/i,'').replace(/^y=/i,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/⁴/g,'^4').replace(/⁵/g,'^5').replace(/⁶/g,'^6').replace(/⁷/g,'^7').replace(/⁸/g,'^8').replace(/⁹/g,'^9').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[], absDepth=0;
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if(ch==='|'){ var pv=toks[toks.length-1]; var opn=(absDepth===0)||!pv||('+-*/^(['.indexOf(pv.k)>=0); if(opn){ absDepth++; toks.push({k:'['}); } else { absDepth--; toks.push({k:']'}); } i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')'||b.k===']') && (a.k==='n'||a.k==='v'||a.k==='('||a.k==='[')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    if(t.k==='['){ var m=parseE(); if(!peek()||peek().k!==']') throw 0; p++; return function(e){ return Math.abs(m(e)); }; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(\d+)(?: |\+|-)(\d+)\/(\d+)$/))){ if(+m[3]===0) return null; return {v:+m[1]+m[2]/m[3],form:'mixed',w:+m[1],n:+m[2],d:+m[3]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ if(/\d/.test(a)) return norm(a)===norm(input); var w=wordsNorm(a); return w!=='' && w===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    var alt=String(input).replace(/\/\s*(\d+(?:\.\d+)?)\s*([a-zA-Z(])/g,'/$1*$2'); if(alt!==String(input) && exprEqual(alt,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null){ if(Math.abs(n1-n2)<1e-3) return true; return (accept||[]).some(function(a){ var n3=parseNum(a); return n3!==null && Math.abs(n1-n3)<1e-3; }); }
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var THEORY = "<div class=\"hub\"><div class=\"hub-card\"><h3>📖 Theory notes</h3><p>Explained notes for each lesson, with key ideas, rules, diagrams and worked examples.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-jump=\"n81\">8.1 notes</button><button class=\"hub-btn\" data-jump=\"n82\">8.2 notes</button><button class=\"hub-btn\" data-jump=\"n83\">8.3 notes</button><button class=\"hub-btn\" data-jump=\"n84\">8.4 notes</button><button class=\"hub-btn\" data-jump=\"n85\">8.5 notes</button><button class=\"hub-btn\" data-jump=\"n86\">8.6 notes</button><button class=\"hub-btn\" data-jump=\"n87\">8.7 notes</button></div></div><div class=\"hub-card\"><h3>🎯 Learning-target practice</h3><p>One practice sheet for each learning target: multiple-choice questions, then step-by-step fill-in-the-blank questions.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s1\">LT 8.1 · Sample spaces and probability</button><button class=\"hub-btn\" data-go=\"s2\">LT 8.2 · Two-way tables and probability</button><button class=\"hub-btn\" data-go=\"s3\">LT 8.3 · Conditional probability</button><button class=\"hub-btn\" data-go=\"s4\">LT 8.4 · Independent and dependent events</button><button class=\"hub-btn\" data-go=\"s5\">LT 8.5 · Probability of disjoint and overlapping events</button><button class=\"hub-btn\" data-go=\"s6\">LT 8.6 · Permutations and combinations</button><button class=\"hub-btn\" data-go=\"s7\">LT 8.7 · Binomial distribution</button></div></div><div class=\"hub-card\"><h3>📝 Chapter test</h3><p>A mixed test covering the whole chapter. Try it in Quiz mode for an exam-style score and answer key.</p><div class=\"hub-btns\"><button class=\"hub-btn primary\" data-go=\"s8\">Start the chapter test</button></div></div></div><section class=\"note\" id=\"n81\"><h2>8.1 Sample spaces and probability</h2><p class=\"lt\"><b>Learning target:</b> Find sample spaces and probabilities of events.</p><h4>Outcomes, events and sample spaces</h4><p>A <b>probability experiment</b> is an action with results you cannot predict for certain, such as rolling a die. Each possible result is an <b>outcome</b>. The set of all possible outcomes is the <b>sample space</b>. An <b>event</b> is a collection of one or more outcomes.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Experiment</th><th>Sample space</th><th>Number of outcomes</th></tr><tr><td>Flip a coin</td><td class=\"mono\">H, T</td><td>2</td></tr><tr><td>Roll a die</td><td class=\"mono\">1, 2, 3, 4, 5, 6</td><td>6</td></tr><tr><td>Flip a coin and roll a die</td><td class=\"mono\">H1, H2, …, H6, T1, …, T6</td><td>2 × 6 = 12</td></tr><tr><td>Flip three coins</td><td class=\"mono\">HHH, HHT, HTH, THH, HTT, THT, TTH, TTT</td><td>2 × 2 × 2 = 8</td></tr></table></div><p>When one stage has m outcomes and a second stage has n outcomes, the combined experiment has <b>m × n</b> outcomes. A table or a tree diagram helps you list them without missing any.</p><h4>Theoretical probability</h4><p>When all outcomes are <b>equally likely</b>, the theoretical probability of an event A is</p><p class=\"mono\" style=\"text-align:center\">P(A) = (number of favourable outcomes) ÷ (total number of outcomes)</p><p>Every probability lies between 0 (impossible) and 1 (certain). It may be written as a fraction, a decimal or a percent.</p><p>The <b>complement</b> of A, written <span class=\"mono\">Ā</span> (read “not A”), is every outcome that is <i>not</i> in A. Because A and Ā together make up the whole sample space,</p><p class=\"mono\" style=\"text-align:center\">P(Ā) = 1 − P(A)</p><div class=\"keybox\"><b>Use the complement for “not” and “at least” questions.</b> It is often quicker to count what you do <i>not</i> want and subtract from 1.</div><p>The table shows all 36 equally likely sums when two dice are rolled. The six sums of 7 are in bold.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>+</th><th>1</th><th>2</th><th>3</th><th>4</th><th>5</th><th>6</th></tr><tr><th>1</th><td>2</td><td>3</td><td>4</td><td>5</td><td>6</td><td><b>7</b></td></tr><tr><th>2</th><td>3</td><td>4</td><td>5</td><td>6</td><td><b>7</b></td><td>8</td></tr><tr><th>3</th><td>4</td><td>5</td><td>6</td><td><b>7</b></td><td>8</td><td>9</td></tr><tr><th>4</th><td>5</td><td>6</td><td><b>7</b></td><td>8</td><td>9</td><td>10</td></tr><tr><th>5</th><td>6</td><td><b>7</b></td><td>8</td><td>9</td><td>10</td><td>11</td></tr><tr><th>6</th><td><b>7</b></td><td>8</td><td>9</td><td>10</td><td>11</td><td>12</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Two dice</div><div class=\"exl\">Two dice are rolled. Find P(sum = 7) and P(sum ≠ 7).<br>The sample space has 6 × 6 = 36 outcomes. A sum of 7 happens 6 ways: (1,6), (2,5), (3,4), (4,3), (5,2), (6,1).<br>P(sum = 7) = 6/36 = <b>1/6</b>. By the complement rule, P(sum ≠ 7) = 1 − 1/6 = <b>5/6</b>.</div></div><h4>Geometric probability</h4><p>When a point is chosen at random in a region, the probability of landing in part of it is a ratio of <b>lengths</b> or <b>areas</b>:</p><p class=\"mono\" style=\"text-align:center\">P = (area of the favourable region) ÷ (area of the whole region)</p><svg class=\"figsvg\" viewBox=\"0 0 240 200\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"120.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">Square board with a circle</text><rect x=\"40.0\" y=\"24\" width=\"160\" height=\"160\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.6\"/><circle cx=\"120.0\" cy=\"104.0\" r=\"20.0\" style=\"fill:var(--accent-text);fill-opacity:.5;stroke:var(--accent-text);stroke-width:1.6\"/></svg><div class=\"ex\"><div class=\"exh\">Worked example 2 · Dartboard</div><div class=\"exl\">A dart lands at a random point on a square board of side 40 cm. A circle of radius 10 cm is painted in the middle.<br>Area of circle = π × 10² = 100π ≈ 314.2 cm². Area of board = 40² = 1600 cm².<br>P(dart lands in the circle) = 100π ÷ 1600 = π/16 ≈ <b>0.196</b>.</div></div><h4>Experimental probability</h4><p>When you actually carry out an experiment, the <b>experimental probability</b> of an event is</p><p class=\"mono\" style=\"text-align:center\">P(event) = (number of successes) ÷ (number of trials)</p><p>With a small number of trials the experimental probability can be far from the theoretical one. As the number of trials grows, it usually gets closer (the <b>law of large numbers</b>).</p><div class=\"ex\"><div class=\"exh\">Worked example 3 · Spinner experiment</div><div class=\"exl\">A spinner with 4 equal sections (one red) is spun 200 times and lands on red 46 times.<br>Experimental P(red) = 46 ÷ 200 = <b>0.23</b>. Theoretical P(red) = 1/4 = 0.25.<br>Expected number of reds in 200 spins = 0.25 × 200 = 50; the result 46 is close.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 4 · Making a prediction</div><div class=\"exl\">A quality check finds 12 faulty chargers in a sample of 400.<br>Experimental P(faulty) = 12 ÷ 400 = 0.03.<br>In a shipment of 5000 chargers, expect about 0.03 × 5000 = <b>150</b> faulty ones.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s1\">Practise LT 8.1 →</button></div></section><section class=\"note\" id=\"n82\"><h2>8.2 Two-way tables and probability</h2><p class=\"lt\"><b>Learning target:</b> Use two-way tables to represent data and find probabilities.</p><h4>Reading a two-way table</h4><p>A <b>two-way table</b> shows data about two categories for the same group. Each entry inside the table is a <b>joint frequency</b>; the row and column totals at the edges are <b>marginal frequencies</b>.</p><p>Survey of 200 students: do they live within 3 km of school, and do they own a bicycle?</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th></th><th>Bicycle</th><th>No bicycle</th><th>Total</th></tr><tr><th>Within 3 km</th><td>56</td><td>34</td><td><b>90</b></td></tr><tr><th>Further away</th><td>24</td><td>86</td><td><b>110</b></td></tr><tr><th>Total</th><td><b>80</b></td><td><b>120</b></td><td><b>200</b></td></tr></table></div><h4>Relative frequencies</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Type</th><th>How to find it</th><th>Example</th></tr><tr><td>Joint relative frequency</td><td>joint frequency ÷ grand total</td><td>near and bicycle: 56 ÷ 200 = 0.28</td></tr><tr><td>Marginal relative frequency</td><td>row or column total ÷ grand total</td><td>bicycle: 80 ÷ 200 = 0.40</td></tr><tr><td>Conditional relative frequency</td><td>joint frequency ÷ the total of its <b>row</b> or <b>column</b></td><td>bicycle, given near: 56 ÷ 90 ≈ 0.622</td></tr></table></div><div class=\"keybox\"><b>Choose the right total.</b> “Of the students who live near, what fraction own a bicycle?” divides by the <i>near</i> row total (90), not by 200 and not by the bicycle total (80).</div><p>A conditional relative frequency is a probability: if a student who lives near school is picked at random, the probability that the student owns a bicycle is 56/90 ≈ 0.622.</p><div class=\"ex\"><div class=\"exh\">Worked example 1 · Completing a table</div><div class=\"exl\">120 café customers: 75 ordered tea. 45 tea drinkers and 20 others also ordered a snack.<br>Tea, no snack: 75 − 45 = 30. Not tea: 120 − 75 = 45; not tea, no snack: 45 − 20 = 25.<br>Snack total: 45 + 20 = 65; no snack total: 30 + 25 = 55. Check: 65 + 55 = 120 ✓</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Joint and marginal relative frequencies</div><div class=\"exl\">From the bicycle table: P(further away and no bicycle) = 86 ÷ 200 = <b>0.43</b>.<br>P(further away) = 110 ÷ 200 = <b>0.55</b> (a marginal relative frequency).</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Conditional relative frequencies and a conclusion</div><div class=\"exl\">Of the bicycle owners, the fraction who live near: 56 ÷ 80 = <b>0.70</b>.<br>Of the students who live further away, the fraction with a bicycle: 24 ÷ 110 ≈ 0.218.<br>Near students own bicycles far more often (0.622 against 0.218), so distance and bicycle ownership appear to be related.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s2\">Practise LT 8.2 →</button></div></section><section class=\"note\" id=\"n83\"><h2>8.3 Conditional probability</h2><p class=\"lt\"><b>Learning target:</b> Find and use conditional probabilities.</p><h4>What “given” means</h4><p>The <b>conditional probability</b> of B given A, written <span class=\"mono\">P(B | A)</span>, is the probability that B occurs <i>when we already know</i> that A has occurred. Knowing A shrinks the sample space to the outcomes in A.</p><p class=\"mono\" style=\"text-align:center\">P(B | A) = P(A and B) ÷ P(A)</p><p>Multiplying out gives a useful rearrangement: <span class=\"mono\">P(A and B) = P(A) · P(B | A)</span>.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Information you have</th><th>Method</th></tr><tr><td>a list of equally likely outcomes</td><td>count outcomes of B <i>inside</i> A, divide by the number of outcomes in A</td></tr><tr><td>a two-way table</td><td>joint frequency ÷ the total of the given row or column</td></tr><tr><td>P(A) and P(A and B)</td><td>use the formula P(B | A) = P(A and B) ÷ P(A)</td></tr></table></div><div class=\"keybox\"><b>P(B | A) and P(A | B) are usually different.</b> P(king | face card) = 4/12, but P(face card | king) = 4/4 = 1.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Reduced sample space</div><div class=\"exl\">A die is rolled. Given that the number is even, what is the probability it is a 6?<br>Given even, the sample space is {2, 4, 6}: 3 outcomes. One of them is 6.<br>P(6 | even) = <b>1/3</b> (compare P(6) = 1/6 without the extra information).</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · Using the formula</div><div class=\"exl\">60% of students take the bus to school; 24% take the bus <i>and</i> eat breakfast at school.<br>P(breakfast | bus) = 0.24 ÷ 0.60 = <b>0.4</b>. So 40% of bus riders eat breakfast at school.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · A medical test</div><div class=\"exl\">200 people are tested. 40 have a condition: 38 test positive, 2 negative. 160 do not: 16 test positive, 144 negative.<br>P(positive | condition) = 38 ÷ 40 = 0.95. P(negative | no condition) = 144 ÷ 160 = 0.9.<br>But P(condition | positive) = 38 ÷ (38 + 16) = 38 ÷ 54 ≈ <b>0.704</b>: about 30% of positive results are false alarms.</div></div><h4>Making decisions</h4><p>Conditional probabilities let you compare options fairly, because each is measured against its own total.</p><div class=\"ex\"><div class=\"exh\">Worked example 4 · Choosing a courier</div><div class=\"exl\">Courier A delivered 135 of 150 parcels on time; courier B delivered 84 of 90 on time.<br>P(on time | A) = 135 ÷ 150 = 0.9. P(on time | B) = 84 ÷ 90 ≈ 0.933.<br>B has the higher on-time probability, even though A delivered more parcels on time in total.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s3\">Practise LT 8.3 →</button></div></section><section class=\"note\" id=\"n84\"><h2>8.4 Independent and dependent events</h2><p class=\"lt\"><b>Learning target:</b> Understand and find probabilities of independent and dependent events.</p><h4>Independent and dependent</h4><p>Two events are <b>independent</b> when the occurrence of one does <i>not</i> change the probability of the other. Otherwise they are <b>dependent</b>.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Events</th><th>Rule for P(A and B)</th><th>Typical situations</th></tr><tr><td>Independent</td><td class=\"mono\">P(A)&nbsp;·&nbsp;P(B)</td><td>rolling dice, flipping coins, drawing <b>with</b> replacement</td></tr><tr><td>Dependent</td><td class=\"mono\">P(A)&nbsp;·&nbsp;P(B&nbsp;|&nbsp;A)</td><td>drawing <b>without</b> replacement, choosing people one after another</td></tr></table></div><p><b>Testing for independence.</b> A and B are independent exactly when <span class=\"mono\">P(A and B) = P(A) · P(B)</span>, or equivalently when <span class=\"mono\">P(B | A) = P(B)</span>.</p><div class=\"keybox\"><b>Without replacement, the second draw changes.</b> After one red is taken from 4 red and 6 blue, only 3 red remain out of 9, so P(red second | red first) = 3/9, not 4/10.</div><p>Tree diagram for drawing two counters without replacement from a bag of 4 red (R) and 6 blue (B). Multiply along a path to get the probability of that path.</p><svg class=\"figsvg\" viewBox=\"0 0 330 210\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line x1=\"14.0\" y1=\"105.0\" x2=\"106.0\" y2=\"54.6\" style=\"stroke:var(--ink-soft);stroke-width:1.5\"/><line x1=\"14.0\" y1=\"105.0\" x2=\"106.0\" y2=\"155.4\" style=\"stroke:var(--ink-soft);stroke-width:1.5\"/><circle cx=\"14\" cy=\"105.0\" r=\"3.5\" style=\"fill:var(--ink)\"/><text x=\"120.0\" y=\"54.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">R</text><text x=\"120.0\" y=\"155.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">B</text><text x=\"57.0\" y=\"69.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">4/10</text><text x=\"57.0\" y=\"140.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">6/10</text><line x1=\"134.0\" y1=\"54.6\" x2=\"212.0\" y2=\"29.4\" style=\"stroke:var(--ink-soft);stroke-width:1.5\"/><text x=\"226.0\" y=\"29.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">R</text><text x=\"173.0\" y=\"33.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">3/9</text><text x=\"242.0\" y=\"29.4\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 12px 'Source Sans 3',sans-serif\">RR: 12/90</text><line x1=\"134.0\" y1=\"54.6\" x2=\"212.0\" y2=\"79.8\" style=\"stroke:var(--ink-soft);stroke-width:1.5\"/><text x=\"226.0\" y=\"79.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">B</text><text x=\"173.0\" y=\"76.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">6/9</text><text x=\"242.0\" y=\"79.8\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 12px 'Source Sans 3',sans-serif\">RB: 24/90</text><line x1=\"134.0\" y1=\"155.4\" x2=\"212.0\" y2=\"130.2\" style=\"stroke:var(--ink-soft);stroke-width:1.5\"/><text x=\"226.0\" y=\"130.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">R</text><text x=\"173.0\" y=\"133.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">4/9</text><text x=\"242.0\" y=\"130.2\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 12px 'Source Sans 3',sans-serif\">BR: 24/90</text><line x1=\"134.0\" y1=\"155.4\" x2=\"212.0\" y2=\"180.6\" style=\"stroke:var(--ink-soft);stroke-width:1.5\"/><text x=\"226.0\" y=\"180.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">B</text><text x=\"173.0\" y=\"177.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">5/9</text><text x=\"242.0\" y=\"180.6\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 12px 'Source Sans 3',sans-serif\">BB: 30/90</text></svg><div class=\"ex\"><div class=\"exh\">Worked example 1 · Independent events</div><div class=\"exl\">Flip a coin and roll a die. P(heads and 6) = P(heads) · P(6) = ½ × 1/6 = <b>1/12</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · With and without replacement</div><div class=\"exl\">Bag: 4 red, 6 blue. Draw two counters.<br>With replacement: P(both red) = 4/10 × 4/10 = 16/100 = <b>0.16</b>.<br>Without replacement: P(both red) = 4/10 × 3/9 = 12/90 = <b>2/15</b> ≈ 0.133.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Testing a two-way table</div><div class=\"exl\">In the bicycle survey (8.2): P(bicycle) = 80/200 = 0.40, but P(bicycle | near) = 56/90 ≈ 0.622.<br>Knowing that a student lives near changes the probability, so the events are <b>dependent</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 4 · Independent weather events</div><div class=\"exl\">P(rain Saturday) = 0.3, P(rain Sunday) = 0.4, independent.<br>P(both days) = 0.3 × 0.4 = 0.12. P(neither) = 0.7 × 0.6 = 0.42.<br>P(at least one rainy day) = 1 − 0.42 = <b>0.58</b>.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s4\">Practise LT 8.4 →</button></div></section><section class=\"note\" id=\"n85\"><h2>8.5 Probability of disjoint and overlapping events</h2><p class=\"lt\"><b>Learning target:</b> Find probabilities of disjoint and overlapping events.</p><h4>Compound events</h4><p>A <b>compound event</b> combines two or more events with “and” or “or”. Two events are <b>disjoint</b> (or <b>mutually exclusive</b>) if they have no outcomes in common, so they cannot happen together. Events that share at least one outcome are <b>overlapping</b>.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Events</th><th>P(A or B)</th><th>Example with one die</th></tr><tr><td>Disjoint</td><td class=\"mono\">P(A)&nbsp;+&nbsp;P(B)</td><td>“2” or “odd”: 1/6 + 3/6 = 4/6</td></tr><tr><td>Overlapping</td><td class=\"mono\">P(A)&nbsp;+&nbsp;P(B) −&nbsp;P(A&nbsp;and&nbsp;B)</td><td>“even” or “more than 3”: 3/6 + 3/6 − 2/6 = 4/6</td></tr></table></div><div class=\"keybox\"><b>Do not count the overlap twice.</b> When you add P(A) and P(B), the outcomes in both A and B have been counted twice, so subtract P(A and B) once. For disjoint events P(A and B) = 0, so nothing is subtracted.</div><p>A Venn diagram shows the overlap clearly. Of 30 students, 15 play football, 12 play basketball and 5 play both.</p><svg class=\"figsvg\" viewBox=\"0 0 300 190\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"150.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">30 students</text><rect x=\"8\" y=\"22\" width=\"284\" height=\"160\" rx=\"8\" style=\"fill:none;stroke:var(--ink-soft);stroke-width:1.3\"/><circle cx=\"114.0\" cy=\"106.0\" r=\"58\" style=\"fill:var(--accent-text);fill-opacity:.12;stroke:var(--accent-text);stroke-width:2\"/><circle cx=\"186.0\" cy=\"106.0\" r=\"58\" style=\"fill:var(--danger);fill-opacity:.12;stroke:var(--danger);stroke-width:2\"/><text x=\"82.1\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">Football</text><text x=\"217.9\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">Basketball</text><text x=\"85.0\" y=\"106.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">10</text><text x=\"150.0\" y=\"106.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">5</text><text x=\"215.0\" y=\"106.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">7</text><text x=\"282.0\" y=\"170.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">8</text></svg><div class=\"ex\"><div class=\"exh\">Worked example 1 · Reading the Venn diagram</div><div class=\"exl\">Football only: 15 − 5 = 10. Basketball only: 12 − 5 = 7. Neither: 30 − 10 − 5 − 7 = 8.<br>P(football or basketball) = 15/30 + 12/30 − 5/30 = 22/30 = <b>11/15</b>.<br>P(neither) = 8/30 = 4/15, and 11/15 + 4/15 = 1 ✓</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · A deck of cards</div><div class=\"exl\">One card is drawn from a standard 52-card deck. Find P(king or heart).<br>P(king) = 4/52, P(heart) = 13/52, P(king of hearts) = 1/52.<br>P(king or heart) = (4 + 13 − 1)/52 = 16/52 = <b>4/13</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · Finding a missing probability</div><div class=\"exl\">P(A or B) = 0.9, P(A) = 0.6 and P(A and B) = 0.25. Find P(B).<br>0.9 = 0.6 + P(B) − 0.25, so P(B) = 0.9 − 0.6 + 0.25 = <b>0.55</b>.</div></div><h4>Using more than one rule</h4><p>Real problems often need the complement rule, the multiplication rule and the addition rule together.</p><div class=\"ex\"><div class=\"exh\">Worked example 4 · Two backup alarms</div><div class=\"exl\">Two independent smoke alarms each work with probability 0.9.<br>P(both fail) = 0.1 × 0.1 = 0.01, so P(at least one works) = 1 − 0.01 = <b>0.99</b>.<br>P(exactly one works) = 0.9 × 0.1 + 0.1 × 0.9 = 0.18 (two disjoint cases added).</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s5\">Practise LT 8.5 →</button></div></section><section class=\"note\" id=\"n86\"><h2>8.6 Permutations and combinations</h2><p class=\"lt\"><b>Learning target:</b> Count permutations and combinations.</p><h4>The Fundamental Counting Principle</h4><p>If one choice can be made in m ways and a second choice in n ways, the two choices together can be made in <b>m × n</b> ways. This extends to any number of choices.</p><p>The number of ways to arrange n different objects in a line is <b>n factorial</b>: <span class=\"mono\">n! = n × (n − 1) × … × 2 × 1</span> (and 0! = 1). For example 5! = 120.</p><h4>Permutations and combinations</h4><div class=\"tscroll\"><table class=\"ttab\"><tr><th></th><th>Permutation</th><th>Combination</th></tr><tr><td>Order</td><td><b>matters</b> (first, second, … are different)</td><td><b>does not matter</b> (a group or selection)</td></tr><tr><td>Formula</td><td class=\"mono\">ₙPᵣ = n! ÷ (n − r)!</td><td class=\"mono\">ₙCᵣ = n! ÷ (r! · (n − r)!)</td></tr><tr><td>Example</td><td>President, VP, secretary from 10: ₁₀P₃ = 10 × 9 × 8 = 720</td><td>Committee of 3 from 10: ₁₀C₃ = 720 ÷ 3! = 120</td></tr></table></div><div class=\"keybox\"><b>Ask: does swapping two chosen items give a new result?</b> If yes (positions, rankings, passwords), use a permutation. If no (teams, handfuls, pizza toppings), use a combination. Each group of r items can be ordered in r! ways, so ₙCᵣ = ₙPᵣ ÷ r!.</div><div class=\"ex\"><div class=\"exh\">Worked example 1 · Counting with the principle</div><div class=\"exl\">A code has 2 letters followed by 3 digits. Letters and digits may repeat.<br>Number of codes = 26 × 26 × 10 × 10 × 10 = <b>676 000</b>.<br>If the two letters must be different: 26 × 25 × 1000 = 650 000.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · A permutation</div><div class=\"exl\">In how many ways can gold, silver and bronze be awarded among 12 runners?<br>Order matters: ₁₂P₃ = 12 × 11 × 10 = <b>1320</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · A combination</div><div class=\"exl\">In how many ways can 4 students be chosen from 9 for a quiz team?<br>₉C₄ = (9 × 8 × 7 × 6) ÷ (4 × 3 × 2 × 1) = 3024 ÷ 24 = <b>126</b>.</div></div><h4>Probability with counting</h4><p>P(event) = (number of favourable selections) ÷ (total number of selections), with both counted the same way.</p><div class=\"ex\"><div class=\"exh\">Worked example 4 · Choosing a group at random</div><div class=\"exl\">A class has 8 boys and 7 girls. 4 students are chosen at random. Find P(2 boys and 2 girls).<br>Total selections: ₁₅C₄ = 1365. Favourable: ₈C₂ × ₇C₂ = 28 × 21 = 588.<br>P = 588 ÷ 1365 = 28/65 ≈ <b>0.431</b>.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s6\">Practise LT 8.6 →</button></div></section><section class=\"note\" id=\"n87\"><h2>8.7 Binomial distribution</h2><p class=\"lt\"><b>Learning target:</b> Understand binomial distributions.</p><h4>Probability distributions</h4><p>A <b>random variable</b> X assigns a number to each outcome of an experiment. A <b>probability distribution</b> gives the probability of each value of X, as a table, a formula or a histogram. The probabilities are all between 0 and 1, and they <b>add up to 1</b>.</p><p>Example: X = number of heads when 3 coins are flipped. Of the 8 outcomes, 1 has 0 heads, 3 have 1, 3 have 2 and 1 has 3.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>X</th><td>0</td><td>1</td><td>2</td><td>3</td></tr><tr><th>P(X)</th><td>1/8</td><td>3/8</td><td>3/8</td><td>1/8</td></tr></table></div><svg class=\"figsvg\" viewBox=\"0 0 320 210\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"160.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">Number of heads in 3 flips</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"176.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0</text><line x1=\"38\" y1=\"138.0\" x2=\"310\" y2=\"138.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"138.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.1</text><line x1=\"38\" y1=\"100.0\" x2=\"310\" y2=\"100.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"100.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.2</text><line x1=\"38\" y1=\"62.0\" x2=\"310\" y2=\"62.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"62.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.3</text><line x1=\"38\" y1=\"24.0\" x2=\"310\" y2=\"24.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"24.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.4</text><rect x=\"41.0\" y=\"128.5\" width=\"62.0\" height=\"47.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"72.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">0</text><text x=\"72.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.125</text><rect x=\"109.0\" y=\"33.5\" width=\"62.0\" height=\"142.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"140.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">1</text><text x=\"140.0\" y=\"25.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.375</text><rect x=\"177.0\" y=\"33.5\" width=\"62.0\" height=\"142.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"208.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">2</text><text x=\"208.0\" y=\"25.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.375</text><rect x=\"245.0\" y=\"128.5\" width=\"62.0\" height=\"47.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"276.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">3</text><text x=\"276.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.125</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"38\" y1=\"176.0\" x2=\"38\" y2=\"24.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"174.0\" y=\"202.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">heads</text><text x=\"6.0\" y=\"100.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11px 'Source Sans 3',sans-serif\">P</text></svg><h4>Binomial experiments</h4><p>An experiment is <b>binomial</b> when</p><ul><li>there is a fixed number n of trials,</li><li>the trials are independent,</li><li>each trial has only two outcomes, success or failure, and</li><li>the probability p of success is the same for every trial.</li></ul><p>The probability of exactly k successes in n trials is</p><p class=\"mono\" style=\"text-align:center\">P(k) = ₙCₖ · pᵏ · (1 − p)ⁿ⁻ᵏ</p><p>ₙCₖ counts the ways to place the k successes among the n trials; pᵏ(1 − p)ⁿ⁻ᵏ is the probability of any one such arrangement.</p><div class=\"keybox\"><b>“At least” and “at most” need several values.</b> P(at least 4 out of 5) = P(4) + P(5). For “at least one”, use the complement: 1 − P(0).</div><svg class=\"figsvg\" viewBox=\"0 0 320 210\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"160.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">Binomial: n = 5, p = 0.7</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"176.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0</text><line x1=\"38\" y1=\"138.0\" x2=\"310\" y2=\"138.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"138.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.1</text><line x1=\"38\" y1=\"100.0\" x2=\"310\" y2=\"100.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"100.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.2</text><line x1=\"38\" y1=\"62.0\" x2=\"310\" y2=\"62.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"62.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.3</text><line x1=\"38\" y1=\"24.0\" x2=\"310\" y2=\"24.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"24.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.4</text><rect x=\"41.0\" y=\"175.1\" width=\"39.3\" height=\"0.9\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"60.7\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">0</text><text x=\"60.7\" y=\"167.1\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.002</text><rect x=\"86.3\" y=\"165.2\" width=\"39.3\" height=\"10.8\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"106.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">1</text><text x=\"106.0\" y=\"157.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.028</text><rect x=\"131.7\" y=\"125.7\" width=\"39.3\" height=\"50.3\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"151.3\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">2</text><text x=\"151.3\" y=\"117.7\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.132</text><rect x=\"177.0\" y=\"58.7\" width=\"39.3\" height=\"117.3\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"196.7\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">3</text><text x=\"196.7\" y=\"50.7\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.309</text><rect x=\"222.3\" y=\"39.1\" width=\"39.3\" height=\"136.9\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"242.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">4</text><text x=\"242.0\" y=\"31.1\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.360</text><rect x=\"267.7\" y=\"112.1\" width=\"39.3\" height=\"63.9\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"287.3\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">5</text><text x=\"287.3\" y=\"104.1\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 10px 'Source Sans 3',sans-serif\">0.168</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"38\" y1=\"176.0\" x2=\"38\" y2=\"24.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"174.0\" y=\"202.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">number of successes k</text><text x=\"6.0\" y=\"100.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11px 'Source Sans 3',sans-serif\">P</text></svg><div class=\"ex\"><div class=\"exh\">Worked example 1 · Exactly k successes</div><div class=\"exl\">A player makes 70% of free throws. She takes 5. Find P(exactly 4).<br>n = 5, p = 0.7, k = 4: P(4) = ₅C₄ · 0.7⁴ · 0.3¹ = 5 × 0.2401 × 0.3 = <b>0.360</b> (to 3 d.p.).</div></div><div class=\"ex\"><div class=\"exh\">Worked example 2 · At least</div><div class=\"exl\">P(5) = 0.7⁵ ≈ 0.168. P(at least 4) = 0.360 + 0.168 = <b>0.528</b>.<br>The histogram above shows that 4 is the most likely number of successes.</div></div><div class=\"ex\"><div class=\"exh\">Worked example 3 · At least one</div><div class=\"exl\">20% of phone users in a town use a certain network. 8 users are chosen at random.<br>P(none use it) = 0.8⁸ ≈ 0.168. P(at least one uses it) = 1 − 0.168 = <b>0.832</b>.</div></div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s7\">Practise LT 8.7 →</button></div></section><section class=\"note\" id=\"nsum\"><h2>Chapter checklist</h2><ul><li>I can list a sample space and find theoretical, geometric and experimental probabilities.</li><li>I can complete a two-way table and find joint, marginal and conditional relative frequencies.</li><li>I can find P(B | A) from a list, a table or the formula, and use it to compare options.</li><li>I can decide whether events are independent and find P(A and B) with or without replacement.</li><li>I can find P(A or B) for disjoint and overlapping events, and combine probability rules.</li><li>I can count with the Fundamental Counting Principle, permutations and combinations.</li><li>I can build a probability distribution and use the binomial formula.</li></ul><div class=\"hub-btns\" style=\"margin-top:10px\"><button class=\"hub-btn primary\" data-go=\"s8\">Take the chapter test →</button></div></section>";
var SECTIONS = [{"id": "s1", "label": "LT 8.1", "sub": "Sample spaces and probability — find sample spaces and probabilities of events", "slides": [{"kind": "mcq", "text": "Three coins are flipped. How many outcomes are in the sample space?", "opts": ["6", "8", "9", "3"], "correct": 1, "tag": "", "sol": "Each coin has 2 outcomes, so there are 2 × 2 × 2 = 8 outcomes: HHH, HHT, HTH, THH, HTT, THT, TTH, TTT."}, {"kind": "mcq", "text": "Two dice are rolled. What is the probability that the sum is 8?", "opts": ["{1/6}", "{1/9}", "{5/36}", "{2/9}"], "correct": 2, "tag": "", "sol": "Sums of 8: (2,6), (3,5), (4,4), (5,3), (6,2), which is 5 of the 36 equally likely outcomes. P = 5/36."}, {"kind": "mcq", "text": "For an event A, P(A) = 0.35. What is P(not A)?", "opts": ["0.53", "0.35", "1.35", "0.65"], "correct": 3, "tag": "", "sol": "Complement rule: P(Ā) = 1 − P(A) = 1 − 0.35 = 0.65."}, {"kind": "mcq", "text": "A bag holds 5 red, 3 blue and 4 green marbles. One is picked at random. What is P(not green)?", "opts": ["{1/3}", "{2/3}", "{3/4}", "{5/12}"], "correct": 1, "tag": "", "sol": "Not green means red or blue: 5 + 3 = 8 of the 12 marbles. P = 8/12 = 2/3. (Or 1 − 4/12 = 2/3.)"}, {"kind": "mcq", "text": "A cricketer hits the stumps with 18 of 25 throws in practice. What is the experimental probability of a hit?", "opts": ["0.18", "0.25", "0.72", "0.28"], "correct": 2, "tag": "", "sol": "Experimental probability = successes ÷ trials = 18 ÷ 25 = 0.72."}, {"kind": "mcq", "text": "A dart lands at a random point on a square board of side 20 cm. A circle of radius 5 cm is drawn in the middle. About what is the probability of landing in the circle?", "opts": ["0.196", "0.25", "0.785", "0.0625"], "correct": 0, "tag": "", "sol": "P = area of circle ÷ area of square = π × 5² ÷ 20² = 25π ÷ 400 ≈ 0.196."}, {"kind": "mcq", "text": "A fair die is rolled 600 times. About how many times do you expect a 5?", "opts": ["60", "120", "500", "100"], "correct": 3, "tag": "", "sol": "P(5) = 1/6, so expect about 600 × 1/6 = 100 fives."}, {"kind": "mcq", "text": "A factory finds 12 faulty phone chargers in a sample of 400. About how many faulty chargers should it expect in a shipment of 5000?", "opts": ["120", "150", "480", "60"], "correct": 1, "tag": "", "sol": "Experimental P(faulty) = 12 ÷ 400 = 0.03. Expected number = 0.03 × 5000 = 150."}, {"kind": "blank", "p": "A coin is flipped and a fair die is rolled.", "tag": "", "marks": "", "flat": [{"t": "The sample space has __B1__ outcomes.", "a": {"B1": "12"}}, {"t": "P(heads and an even number) = __B1__ (fraction or decimal)", "a": {"B1": "1/4"}, "accept": ["0.25"]}, {"t": "P(tails and a number greater than 4) = __B1__", "a": {"B1": "1/6"}}, {"t": "P(not (heads and an even number)) = __B1__", "a": {"B1": "3/4"}, "accept": ["0.75"]}], "sol": "2 × 6 = 12 outcomes.\nHeads with 2, 4 or 6: 3 of 12 = 1/4.\nTails with 5 or 6: 2 of 12 = 1/6.\nComplement: 1 − 1/4 = 3/4."}, {"kind": "blank", "p": "Two fair dice are rolled.", "tag": "", "marks": "", "flat": [{"t": "Number of outcomes: __B1__", "a": {"B1": "36"}}, {"t": "Number of ways to get a sum of 9: __B1__", "a": {"B1": "4"}}, {"t": "P(sum = 9) = __B1__", "a": {"B1": "1/9"}}, {"t": "P(sum ≠ 9) = __B1__", "a": {"B1": "8/9"}}], "sol": "6 × 6 = 36.\n(3,6), (4,5), (5,4), (6,3).\n4/36 = 1/9.\n1 − 1/9 = 8/9."}, {"kind": "blank", "p": "A circular dartboard has radius 30 cm. The bullseye is a circle of radius 6 cm at its centre. A dart hits the board at a random point.", "tag": "", "marks": "", "flat": [{"t": "Area of bullseye ÷ area of board = 36π ÷ __B1__π", "a": {"B1": "900"}}, {"t": "P(bullseye) = __B1__ (decimal)", "a": {"B1": "0.04"}}, {"t": "P(not bullseye) = __B1__", "a": {"B1": "0.96"}}], "sol": "Areas: π × 6² = 36π and π × 30² = 900π.\n36 ÷ 900 = 0.04.\n1 − 0.04 = 0.96."}, {"kind": "blank", "p": "A spinner has 4 equal sections: red, blue, green, yellow. It is spun 80 times and lands on blue 26 times.", "tag": "", "marks": "", "flat": [{"t": "Experimental P(blue) = __B1__ (decimal)", "a": {"B1": "0.325"}}, {"t": "Theoretical P(blue) = __B1__ (decimal)", "a": {"B1": "0.25"}}, {"t": "Expected number of blues in 80 spins: __B1__", "a": {"B1": "20"}}], "sol": "26 ÷ 80 = 0.325.\n1 of 4 equal sections: 0.25.\n0.25 × 80 = 20. With more spins the experimental value should move closer to 0.25."}, {"kind": "blank", "p": "A letter is picked at random from the word PROBABILITY (11 letters).", "tag": "", "marks": "", "flat": [{"t": "P(B) = __B1__", "a": {"B1": "2/11"}}, {"t": "P(a vowel: A, E, I, O or U) = __B1__", "a": {"B1": "4/11"}}, {"t": "P(not I) = __B1__", "a": {"B1": "9/11"}}], "sol": "There are two Bs: 2/11.\nO, A, I, I are vowels: 4/11.\nThere are two Is, so 1 − 2/11 = 9/11."}]}, {"id": "s2", "label": "LT 8.2", "sub": "Two-way tables and probability — use two-way tables to represent data and find probabilities", "slides": [{"kind": "mcq", "text": "A survey of 250 people: under 30 — 70 watch cricket, 50 do not; 30 and over — 90 watch cricket, 40 do not. How many people aged 30 and over watch cricket?", "opts": ["70", "90", "130", "160"], "correct": 1, "tag": "", "sol": "Read the joint frequency in the row '30 and over' and the column 'watch cricket': 90."}, {"kind": "mcq", "text": "Using the same survey (250 people; under 30: 70 watch, 50 do not; 30+: 90 watch, 40 do not), what is the joint relative frequency of 'under 30 and does not watch'?", "opts": ["0.2", "0.5", "0.42", "0.56"], "correct": 0, "tag": "", "sol": "Joint relative frequency = joint frequency ÷ grand total = 50 ÷ 250 = 0.2."}, {"kind": "mcq", "text": "In the same survey, what is the marginal relative frequency of people who watch cricket?", "opts": ["0.36", "0.56", "0.64", "0.9"], "correct": 2, "tag": "", "sol": "Watch cricket total = 70 + 90 = 160. Marginal relative frequency = 160 ÷ 250 = 0.64."}, {"kind": "mcq", "text": "In the same survey, what is the conditional relative frequency that a person watches cricket, given that the person is under 30?", "opts": ["0.28", "0.4375", "0.48", "0.583"], "correct": 3, "tag": "", "sol": "Divide by the under-30 row total: 70 ÷ (70 + 50) = 70 ÷ 120 ≈ 0.583."}, {"kind": "mcq", "text": "In the same survey, what fraction of the cricket watchers are under 30?", "opts": ["{7/16}", "{7/12}", "{7/25}", "{9/16}"], "correct": 0, "tag": "", "sol": "Given 'watches cricket', divide by that column total: 70 ÷ 160 = 7/16."}, {"kind": "mcq", "text": "A conditional relative frequency is found by dividing a joint frequency by", "opts": ["the grand total", "a row total or a column total", "another joint frequency", "the number of categories"], "correct": 1, "tag": "", "sol": "Conditional relative frequencies compare a joint frequency with the total of its own row or column."}, {"kind": "mcq", "text": "A table of 100 students: 38 own a pet. Of the students who own a pet, 21 are in Grade 11. How many students own a pet and are NOT in Grade 11?", "opts": ["21", "62", "17", "79"], "correct": 2, "tag": "", "sol": "Pet owners total 38; subtract the 21 in Grade 11: 38 − 21 = 17."}, {"kind": "mcq", "text": "In the cricket survey (under 30: 70 watch, 50 do not; 30+: 90 watch, 40 do not), which statement is supported?", "opts": ["People under 30 are more likely to watch cricket.", "People 30 and over are more likely to watch cricket.", "Both age groups are equally likely to watch.", "Nobody under 30 watches cricket."], "correct": 1, "tag": "", "sol": "P(watch | under 30) = 70/120 ≈ 0.583; P(watch | 30+) = 90/130 ≈ 0.692. The 30+ group is more likely to watch."}, {"kind": "blank", "p": "Complete the two-way table for 150 students.\nPlays an instrument: Grade 10 → 28, Grade 11 → ?, Total → 60\nNo instrument: Grade 10 → ?, Grade 11 → ?, Total → ?\nTotal: Grade 10 → 70, Grade 11 → ?, Total → 150", "tag": "", "marks": "", "flat": [{"t": "Grade 11 students who play an instrument: __B1__", "a": {"B1": "32"}}, {"t": "Grade 10 students with no instrument: __B1__", "a": {"B1": "42"}}, {"t": "Total Grade 11 students: __B1__; Grade 11 with no instrument: __B2__", "a": {"B1": "80", "B2": "48"}}, {"t": "Total with no instrument: __B1__", "a": {"B1": "90"}}], "sol": "60 − 28 = 32.\n70 − 28 = 42.\n150 − 70 = 80; 80 − 32 = 48.\n150 − 60 = 90 (check: 42 + 48 = 90 ✓)."}, {"kind": "blank", "p": "200 students: within 3 km of school — 56 own a bicycle, 34 do not; further away — 24 own a bicycle, 86 do not.", "tag": "", "marks": "", "flat": [{"t": "Joint relative frequency of 'near and bicycle' = __B1__", "a": {"B1": "0.28"}}, {"t": "Marginal relative frequency of 'bicycle' = __B1__", "a": {"B1": "0.4"}}, {"t": "Marginal relative frequency of 'further away' = __B1__", "a": {"B1": "0.55"}}], "sol": "56 ÷ 200 = 0.28.\n(56 + 24) ÷ 200 = 80 ÷ 200 = 0.4.\n(24 + 86) ÷ 200 = 110 ÷ 200 = 0.55."}, {"kind": "blank", "p": "Use the same bicycle survey (near: 56 bike, 34 no bike; further: 24 bike, 86 no bike).", "tag": "", "marks": "", "flat": [{"t": "P(bicycle | near) = 56 ÷ __B1__", "a": {"B1": "90"}}, {"t": "P(bicycle | near) = __B1__ (3 decimal places)", "a": {"B1": "0.622"}}, {"t": "P(near | bicycle) = __B1__", "a": {"B1": "0.7"}}, {"t": "Bicycle owners are more likely to live __B1__ (near / further away).", "a": {"B1": "near"}, "expr": "words"}], "sol": "Given 'near', divide by the near row total 56 + 34 = 90.\n56 ÷ 90 ≈ 0.622.\n56 ÷ 80 = 0.7.\n70% of bicycle owners live near."}, {"kind": "blank", "p": "Of 120 café customers, 75 ordered tea. 45 of the tea drinkers ordered a snack, and 20 of the others ordered a snack.", "tag": "", "marks": "", "flat": [{"t": "Tea, no snack: __B1__", "a": {"B1": "30"}}, {"t": "Not tea: __B1__; not tea, no snack: __B2__", "a": {"B1": "45", "B2": "25"}}, {"t": "Total who ordered a snack: __B1__", "a": {"B1": "65"}}], "sol": "75 − 45 = 30.\n120 − 75 = 45; 45 − 20 = 25.\n45 + 20 = 65."}, {"kind": "blank", "p": "Use the café table (tea: 45 snack, 30 no snack; not tea: 20 snack, 25 no snack).", "tag": "", "marks": "", "flat": [{"t": "P(snack | tea) = __B1__", "a": {"B1": "0.6"}}, {"t": "P(snack | not tea) = __B1__ (3 decimal places)", "a": {"B1": "0.444"}}, {"t": "A snack is more likely with a customer who orders __B1__ (tea / not tea).", "a": {"B1": "tea"}, "expr": "words"}], "sol": "45 ÷ 75 = 0.6.\n20 ÷ 45 ≈ 0.444.\n0.6 > 0.444."}]}, {"id": "s3", "label": "LT 8.3", "sub": "Conditional probability — find and use conditional probabilities", "slides": [{"kind": "mcq", "text": "P(A) = 0.5 and P(A and B) = 0.2. What is P(B | A)?", "opts": ["0.1", "0.4", "0.7", "2.5"], "correct": 1, "tag": "", "sol": "P(B | A) = P(A and B) ÷ P(A) = 0.2 ÷ 0.5 = 0.4."}, {"kind": "mcq", "text": "A die is rolled. Given that the number is odd, what is the probability that it is less than 4?", "opts": ["{1/3}", "{1/2}", "{2/3}", "{1/6}"], "correct": 2, "tag": "", "sol": "Given odd, the sample space is {1, 3, 5}. Two of these (1 and 3) are less than 4. P = 2/3."}, {"kind": "mcq", "text": "What does P(B | A) mean?", "opts": ["the probability of A given B", "the probability of both A and B", "the probability of B given that A has occurred", "the probability of A or B"], "correct": 2, "tag": "", "sol": "The bar is read 'given': P(B | A) is the probability of B when A is known to have occurred."}, {"kind": "mcq", "text": "In a survey, 30+ age group: 90 watch cricket and 40 do not. For a random person aged 30+, what is P(watches cricket)?", "opts": ["0.36", "0.563", "0.9", "0.692"], "correct": 3, "tag": "", "sol": "Given 30+, divide by that row total: 90 ÷ 130 ≈ 0.692."}, {"kind": "mcq", "text": "P(A) = 0.6 and P(B | A) = 0.3. What is P(A and B)?", "opts": ["0.18", "0.5", "0.9", "0.3"], "correct": 0, "tag": "", "sol": "P(A and B) = P(A) · P(B | A) = 0.6 × 0.3 = 0.18."}, {"kind": "mcq", "text": "Two dice are rolled. Given that the first die shows 4, what is the probability that the sum is at least 9?", "opts": ["{1/6}", "{1/3}", "{5/18}", "{1/2}"], "correct": 1, "tag": "", "sol": "The second die must be 5 or 6: 2 of 6 outcomes. P = 2/6 = 1/3."}, {"kind": "mcq", "text": "A card is drawn from a standard deck. Given that it is a face card (J, Q or K), what is the probability that it is a king?", "opts": ["{1/13}", "{4/13}", "{1/12}", "{1/3}"], "correct": 3, "tag": "", "sol": "There are 12 face cards and 4 of them are kings. P(king | face card) = 4/12 = 1/3."}, {"kind": "mcq", "text": "A batter scored 50 or more in 12 of 30 home matches and in 6 of 20 away matches. Given that a match is away, what is the probability that she scores 50 or more?", "opts": ["0.3", "0.4", "0.36", "0.18"], "correct": 0, "tag": "", "sol": "Only away matches count: 6 ÷ 20 = 0.3."}, {"kind": "blank", "p": "P(A) = 0.45, P(B) = 0.3 and P(A and B) = 0.18.", "tag": "", "marks": "", "flat": [{"t": "P(B | A) = 0.18 ÷ 0.45 = __B1__", "a": {"B1": "0.4"}}, {"t": "P(A | B) = 0.18 ÷ __B1__ = __B2__", "a": {"B1": "0.3", "B2": "0.6"}}], "sol": "P(B | A) = P(A and B) ÷ P(A) = 0.4.\nP(A | B) = P(A and B) ÷ P(B) = 0.18 ÷ 0.3 = 0.6."}, {"kind": "blank", "p": "200 people are tested for a condition. With the condition: 38 test positive, 2 test negative. Without it: 16 test positive, 144 test negative.", "tag": "", "marks": "", "flat": [{"t": "P(positive | has condition) = __B1__", "a": {"B1": "0.95"}}, {"t": "P(negative | no condition) = __B1__", "a": {"B1": "0.9"}}, {"t": "Total who test positive: __B1__", "a": {"B1": "54"}}, {"t": "P(has condition | positive) = __B1__ (3 decimal places)", "a": {"B1": "0.704"}}], "sol": "38 ÷ 40 = 0.95.\n144 ÷ 160 = 0.9.\n38 + 16 = 54.\n38 ÷ 54 ≈ 0.704."}, {"kind": "blank", "p": "A card is picked at random from 20 cards numbered 1 to 20.", "tag": "", "marks": "", "flat": [{"t": "Given that the number is even, there are __B1__ possible cards.", "a": {"B1": "10"}}, {"t": "P(multiple of 3 | even) = __B1__", "a": {"B1": "0.3"}}, {"t": "P(even | multiple of 3) = __B1__", "a": {"B1": "0.5"}}], "sol": "2, 4, …, 20: 10 cards.\nEven multiples of 3: 6, 12, 18. 3 ÷ 10 = 0.3.\nMultiples of 3: 3, 6, 9, 12, 15, 18 (6 cards); 3 are even: 3 ÷ 6 = 0.5."}, {"kind": "blank", "p": "Courier A delivered 135 of 150 parcels on time. Courier B delivered 84 of 90 parcels on time.", "tag": "", "marks": "", "flat": [{"t": "P(on time | A) = __B1__", "a": {"B1": "0.9"}}, {"t": "P(on time | B) = __B1__ (3 decimal places)", "a": {"B1": "0.933"}}, {"t": "The more reliable courier is __B1__ (A / B).", "a": {"B1": "B"}, "expr": "words", "accept": ["courier b"]}], "sol": "135 ÷ 150 = 0.9.\n84 ÷ 90 ≈ 0.933.\nB has the higher conditional probability of being on time."}, {"kind": "blank", "p": "In a class, 70% of students passed the first test and 49% passed both tests.", "tag": "", "marks": "", "flat": [{"t": "P(pass second | passed first) = 0.49 ÷ __B1__", "a": {"B1": "0.7"}}, {"t": "P(pass second | passed first) = __B1__", "a": {"B1": "0.7"}}, {"t": "Of 40 students who passed the first test, about __B1__ passed the second.", "a": {"B1": "28"}}], "sol": "Divide by P(passed first) = 0.7.\n0.49 ÷ 0.7 = 0.7.\n0.7 × 40 = 28."}]}, {"id": "s4", "label": "LT 8.4", "sub": "Independent and dependent events — understand and find probabilities of independent and dependent events", "slides": [{"kind": "mcq", "text": "Which pair of events is independent?", "opts": ["drawing two cards one after the other without replacement", "rolling a die twice", "choosing two students for a team, one after the other", "taking two socks from a drawer without putting the first back"], "correct": 1, "tag": "", "sol": "The result of the first roll does not change the probabilities for the second roll. The other three are 'without replacement', so the second choice depends on the first."}, {"kind": "mcq", "text": "A and B are independent, P(A) = 0.3 and P(B) = 0.5. What is P(A and B)?", "opts": ["0.8", "0.2", "0.15", "0.35"], "correct": 2, "tag": "", "sol": "Independent: P(A and B) = P(A) · P(B) = 0.3 × 0.5 = 0.15."}, {"kind": "mcq", "text": "A bag has 3 red and 5 green counters. Two are drawn without replacement. What is P(both green)?", "opts": ["{25/64}", "{5/14}", "{5/16}", "{15/56}"], "correct": 1, "tag": "", "sol": "P = 5/8 × 4/7 = 20/56 = 5/14 (after one green is taken, 4 of the remaining 7 are green)."}, {"kind": "mcq", "text": "The same bag (3 red, 5 green). Two counters are drawn WITH replacement. What is P(both green)?", "opts": ["{5/14}", "{5/8}", "{15/64}", "{25/64}"], "correct": 3, "tag": "", "sol": "With replacement the draws are independent: 5/8 × 5/8 = 25/64."}, {"kind": "mcq", "text": "P(A) = 0.4, P(B) = 0.5 and P(A and B) = 0.2. Are A and B independent?", "opts": ["Yes, because P(A and B) = P(A) · P(B)", "No, because P(A and B) ≠ P(A) + P(B)", "No, because P(A) ≠ P(B)", "Yes, because P(A) + P(B) < 1"], "correct": 0, "tag": "", "sol": "0.4 × 0.5 = 0.2 = P(A and B), so the events are independent."}, {"kind": "mcq", "text": "A fair die is rolled three times. What is the probability of three 6s?", "opts": ["{1/18}", "{1/36}", "{1/216}", "{3/216}"], "correct": 2, "tag": "", "sol": "The rolls are independent: 1/6 × 1/6 × 1/6 = 1/216."}, {"kind": "mcq", "text": "P(A) = 0.6 and P(B | A) = 0.25. What is P(A and B)?", "opts": ["0.85", "0.35", "2.4", "0.15"], "correct": 3, "tag": "", "sol": "P(A and B) = P(A) · P(B | A) = 0.6 × 0.25 = 0.15."}, {"kind": "mcq", "text": "If P(B | A) = P(B), then events A and B are", "opts": ["dependent", "independent", "disjoint", "complements"], "correct": 1, "tag": "", "sol": "Knowing A does not change the probability of B, which is the definition of independence."}, {"kind": "blank", "p": "A coin is flipped and a spinner with 5 equal sections numbered 1 to 5 is spun.", "tag": "", "marks": "", "flat": [{"t": "P(heads) = __B1__", "a": {"B1": "0.5"}}, {"t": "P(odd number) = __B1__", "a": {"B1": "0.6"}}, {"t": "P(heads and odd) = __B1__", "a": {"B1": "0.3"}}], "sol": "½ = 0.5.\n1, 3, 5: 3/5 = 0.6.\nIndependent: 0.5 × 0.6 = 0.3."}, {"kind": "blank", "p": "A box has 7 good bulbs and 3 faulty bulbs. Two bulbs are taken out without replacement.", "tag": "", "marks": "", "flat": [{"t": "P(first is faulty) = __B1__", "a": {"B1": "3/10"}, "accept": ["0.3"]}, {"t": "P(second is faulty | first is faulty) = __B1__", "a": {"B1": "2/9"}}, {"t": "P(both faulty) = __B1__", "a": {"B1": "1/15"}}, {"t": "These events are __B1__ (independent / dependent).", "a": {"B1": "dependent"}, "expr": "words"}], "sol": "3 of 10 are faulty.\nAfter one faulty bulb is removed, 2 of the 9 left are faulty.\n3/10 × 2/9 = 6/90 = 1/15.\nThe first draw changes the second probability."}, {"kind": "blank", "p": "In a class of 100 students, 40 study music, 50 play a sport, and 20 do both.", "tag": "", "marks": "", "flat": [{"t": "P(music) × P(sport) = __B1__", "a": {"B1": "0.2"}}, {"t": "P(music and sport) = __B1__", "a": {"B1": "0.2"}}, {"t": "So studying music and playing a sport are __B1__ (independent / dependent).", "a": {"B1": "independent"}, "expr": "words"}], "sol": "0.4 × 0.5 = 0.2.\n20 ÷ 100 = 0.2.\nThe two values are equal, so the events are independent."}, {"kind": "blank", "p": "For events A and B, P(A) = 0.5, P(B) = 0.3 and P(A and B) = 0.2.", "tag": "", "marks": "", "flat": [{"t": "P(A) · P(B) = __B1__", "a": {"B1": "0.15"}}, {"t": "A and B are __B1__ (independent / dependent).", "a": {"B1": "dependent"}, "expr": "words"}, {"t": "P(B | A) = __B1__", "a": {"B1": "0.4"}}], "sol": "0.5 × 0.3 = 0.15.\n0.2 ≠ 0.15, so they are dependent.\n0.2 ÷ 0.5 = 0.4, which is not equal to P(B) = 0.3."}, {"kind": "blank", "p": "P(rain on Saturday) = 0.3 and P(rain on Sunday) = 0.4. Assume the days are independent.", "tag": "", "marks": "", "flat": [{"t": "P(rain both days) = __B1__", "a": {"B1": "0.12"}}, {"t": "P(no rain either day) = __B1__", "a": {"B1": "0.42"}}, {"t": "P(rain on at least one day) = __B1__", "a": {"B1": "0.58"}}], "sol": "0.3 × 0.4 = 0.12.\n0.7 × 0.6 = 0.42.\n1 − 0.42 = 0.58."}]}, {"id": "s5", "label": "LT 8.5", "sub": "Probability of disjoint and overlapping events — find probabilities of disjoint and overlapping events", "slides": [{"kind": "mcq", "text": "A die is rolled. Which two events are disjoint?", "opts": ["rolling an even number and rolling a number greater than 3", "rolling a 2 and rolling an odd number", "rolling a prime and rolling an odd number", "rolling less than 5 and rolling more than 2"], "correct": 1, "tag": "", "sol": "2 is not odd, so 'rolling a 2' and 'rolling an odd number' share no outcomes. Each other pair shares at least one outcome (e.g. 4, 3 or 5, 3 or 4)."}, {"kind": "mcq", "text": "A and B are disjoint, P(A) = 0.35 and P(B) = 0.4. What is P(A or B)?", "opts": ["0.14", "0.75", "0.05", "0.61"], "correct": 1, "tag": "", "sol": "Disjoint: P(A or B) = P(A) + P(B) = 0.35 + 0.4 = 0.75."}, {"kind": "mcq", "text": "P(A) = 0.6, P(B) = 0.3 and P(A and B) = 0.1. What is P(A or B)?", "opts": ["0.9", "1.0", "0.18", "0.8"], "correct": 3, "tag": "", "sol": "Overlapping: P(A or B) = 0.6 + 0.3 − 0.1 = 0.8."}, {"kind": "mcq", "text": "A card is drawn from a standard 52-card deck. What is P(queen or club)?", "opts": ["{17/52}", "{4/13}", "{1/52}", "{1/4}"], "correct": 1, "tag": "", "sol": "P(queen) + P(club) − P(queen of clubs) = 4/52 + 13/52 − 1/52 = 16/52 = 4/13."}, {"kind": "mcq", "text": "A die is rolled. What is P(even or a multiple of 3)?", "opts": ["{5/6}", "{1/6}", "{2/3}", "{1/2}"], "correct": 2, "tag": "", "sol": "Even: 2, 4, 6. Multiple of 3: 3, 6. Together: 2, 3, 4, 6, so 4/6 = 2/3. (3/6 + 2/6 − 1/6 = 4/6.)"}, {"kind": "mcq", "text": "P(A or B) = 0.7, P(A) = 0.45 and P(B) = 0.4. What is P(A and B)?", "opts": ["0.15", "0.25", "0.18", "1.15"], "correct": 0, "tag": "", "sol": "0.7 = 0.45 + 0.4 − P(A and B), so P(A and B) = 0.85 − 0.7 = 0.15."}, {"kind": "mcq", "text": "Of 40 people, 22 drink tea, 15 drink coffee and 8 drink both. One person is chosen at random. What is P(tea or coffee)?", "opts": ["0.925", "0.725", "0.55", "0.2"], "correct": 1, "tag": "", "sol": "22 + 15 − 8 = 29 people drink tea or coffee. P = 29 ÷ 40 = 0.725."}, {"kind": "mcq", "text": "If A and B are disjoint, then P(A and B) is", "opts": ["P(A) · P(B)", "1", "P(A) + P(B)", "0"], "correct": 3, "tag": "", "sol": "Disjoint events cannot happen together, so P(A and B) = 0."}, {"kind": "blank", "p": "Of 50 students, 28 take Hindi, 20 take French and 9 take both.", "tag": "", "marks": "", "flat": [{"t": "Hindi only: __B1__; French only: __B2__", "a": {"B1": "19", "B2": "11"}}, {"t": "P(Hindi or French) = __B1__", "a": {"B1": "0.78"}}, {"t": "P(neither) = __B1__", "a": {"B1": "0.22"}}], "sol": "28 − 9 = 19; 20 − 9 = 11.\n(28 + 20 − 9) ÷ 50 = 39 ÷ 50 = 0.78.\n1 − 0.78 = 0.22 (11 students).", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 190\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"150.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">50 students</text><rect x=\"8\" y=\"22\" width=\"284\" height=\"160\" rx=\"8\" style=\"fill:none;stroke:var(--ink-soft);stroke-width:1.3\"/><circle cx=\"114.0\" cy=\"106.0\" r=\"58\" style=\"fill:var(--accent-text);fill-opacity:.12;stroke:var(--accent-text);stroke-width:2\"/><circle cx=\"186.0\" cy=\"106.0\" r=\"58\" style=\"fill:var(--danger);fill-opacity:.12;stroke:var(--danger);stroke-width:2\"/><text x=\"82.1\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--accent-text);font:700 12px 'Source Sans 3',sans-serif\">Hindi</text><text x=\"217.9\" y=\"41.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--danger);font:700 12px 'Source Sans 3',sans-serif\">French</text><text x=\"85.0\" y=\"106.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">?</text><text x=\"150.0\" y=\"106.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">9</text><text x=\"215.0\" y=\"106.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">?</text><text x=\"282.0\" y=\"170.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 14px 'Source Sans 3',sans-serif\">?</text></svg>"}, {"kind": "blank", "p": "Two dice are rolled.", "tag": "", "marks": "", "flat": [{"t": "P(sum = 7) = __B1__", "a": {"B1": "1/6"}}, {"t": "P(sum = 11) = __B1__", "a": {"B1": "1/18"}}, {"t": "These events are __B1__ (disjoint / overlapping).", "a": {"B1": "disjoint"}, "expr": "words"}, {"t": "P(sum = 7 or sum = 11) = __B1__", "a": {"B1": "2/9"}}], "sol": "6/36 = 1/6.\n(5,6) and (6,5): 2/36 = 1/18.\nA single roll cannot have both sums.\n6/36 + 2/36 = 8/36 = 2/9."}, {"kind": "blank", "p": "A card is drawn from a standard 52-card deck.", "tag": "", "marks": "", "flat": [{"t": "Number of red cards: __B1__; number of face cards (J, Q, K): __B2__", "a": {"B1": "26", "B2": "12"}}, {"t": "Number of red face cards: __B1__", "a": {"B1": "6"}}, {"t": "P(red or face card) = __B1__", "a": {"B1": "8/13"}}], "sol": "Hearts and diamonds: 26. 3 face cards in each of 4 suits: 12.\n3 hearts + 3 diamonds = 6.\n(26 + 12 − 6) ÷ 52 = 32/52 = 8/13."}, {"kind": "blank", "p": "P(A or B) = 0.9, P(A) = 0.6 and P(A and B) = 0.25.", "tag": "", "marks": "", "flat": [{"t": "0.9 = 0.6 + P(B) − __B1__", "a": {"B1": "0.25"}}, {"t": "P(B) = __B1__", "a": {"B1": "0.55"}}, {"t": "P(A only) = P(A) − P(A and B) = __B1__", "a": {"B1": "0.35"}}], "sol": "Use P(A or B) = P(A) + P(B) − P(A and B).\nP(B) = 0.9 − 0.6 + 0.25 = 0.55.\n0.6 − 0.25 = 0.35."}, {"kind": "blank", "p": "A house has two independent smoke alarms. Each works with probability 0.9.", "tag": "", "marks": "", "flat": [{"t": "P(both fail) = __B1__", "a": {"B1": "0.01"}}, {"t": "P(at least one works) = __B1__", "a": {"B1": "0.99"}}, {"t": "P(exactly one works) = __B1__", "a": {"B1": "0.18"}}], "sol": "0.1 × 0.1 = 0.01.\nComplement: 1 − 0.01 = 0.99.\nDisjoint cases: 0.9 × 0.1 + 0.1 × 0.9 = 0.18."}]}, {"id": "s6", "label": "LT 8.6", "sub": "Permutations and combinations — count permutations and combinations", "slides": [{"kind": "mcq", "text": "What is the value of 6!?", "opts": ["36", "120", "720", "21"], "correct": 2, "tag": "", "sol": "6! = 6 × 5 × 4 × 3 × 2 × 1 = 720."}, {"kind": "mcq", "text": "What is ₈P₃?", "opts": ["56", "336", "24", "512"], "correct": 1, "tag": "", "sol": "₈P₃ = 8 × 7 × 6 = 336."}, {"kind": "mcq", "text": "What is ₉C₄?", "opts": ["3024", "36", "126", "24"], "correct": 2, "tag": "", "sol": "₉C₄ = (9 × 8 × 7 × 6) ÷ 4! = 3024 ÷ 24 = 126."}, {"kind": "mcq", "text": "Which situation is counted with a combination?", "opts": ["arranging books on a shelf", "choosing 4 toppings for a pizza", "awarding 1st, 2nd and 3rd prizes", "making a 4-digit PIN"], "correct": 1, "tag": "", "sol": "The order of pizza toppings does not matter, so it is a combination. The others depend on order."}, {"kind": "mcq", "text": "In how many ways can gold, silver and bronze medals be awarded among 12 runners?", "opts": ["220", "36", "1728", "1320"], "correct": 3, "tag": "", "sol": "Order matters: ₁₂P₃ = 12 × 11 × 10 = 1320."}, {"kind": "mcq", "text": "How many different 3-person committees can be chosen from 7 people?", "opts": ["35", "210", "21", "343"], "correct": 0, "tag": "", "sol": "₇C₃ = (7 × 6 × 5) ÷ 3! = 210 ÷ 6 = 35."}, {"kind": "mcq", "text": "Five friends line up in a random order. What is the probability that Asha is first and Ravi is second?", "opts": ["{1/5}", "{1/10}", "{2/5}", "{1/20}"], "correct": 3, "tag": "", "sol": "Favourable orders: the other 3 friends fill the last 3 places in 3! = 6 ways. Total orders: 5! = 120. P = 6/120 = 1/20."}, {"kind": "mcq", "text": "Six marbles are numbered 1 to 6. Two are picked at random. What is the probability of picking marbles 1 and 2?", "opts": ["{1/15}", "{1/30}", "{1/6}", "{1/36}"], "correct": 0, "tag": "", "sol": "There are ₆C₂ = 15 equally likely pairs, and only one of them is {1, 2}. P = 1/15."}, {"kind": "blank", "p": "Arrange the letters of the word MATHS (all different).", "tag": "", "marks": "", "flat": [{"t": "Number of arrangements: __B1__", "a": {"B1": "120"}}, {"t": "Number of arrangements that start with M: __B1__", "a": {"B1": "24"}}, {"t": "P(a random arrangement starts with M) = __B1__", "a": {"B1": "1/5"}, "accept": ["0.2"]}], "sol": "5! = 120.\nM is fixed; the other 4 letters: 4! = 24.\n24 ÷ 120 = 1/5."}, {"kind": "blank", "p": "A club of 10 members chooses a president, a secretary, a treasurer and a coach (4 different posts).", "tag": "", "marks": "", "flat": [{"t": "₁₀P₄ = 10 × 9 × 8 × __B1__", "a": {"B1": "7"}}, {"t": "₁₀P₄ = __B1__", "a": {"B1": "5040"}}], "sol": "Four factors starting at 10.\n10 × 9 × 8 × 7 = 5040."}, {"kind": "blank", "p": "The same club instead chooses 4 members to form a team (no posts).", "tag": "", "marks": "", "flat": [{"t": "Each team of 4 can be ordered in 4! = __B1__ ways.", "a": {"B1": "24"}}, {"t": "₁₀C₄ = 5040 ÷ 24 = __B1__", "a": {"B1": "210"}}], "sol": "4! = 24.\nDivide the permutations by 4!: 210."}, {"kind": "blank", "p": "A class has 8 boys and 7 girls. Four students are chosen at random.", "tag": "", "marks": "", "flat": [{"t": "Total number of groups: ₁₅C₄ = __B1__", "a": {"B1": "1365"}}, {"t": "Groups with 2 boys and 2 girls: ₈C₂ × ₇C₂ = __B1__ × __B2__", "a": {"B1": "28", "B2": "21"}}, {"t": "P(2 boys and 2 girls) = __B1__ (3 decimal places)", "a": {"B1": "0.431"}}], "sol": "(15 × 14 × 13 × 12) ÷ 24 = 1365.\n₈C₂ = 28 and ₇C₂ = 21, giving 588 groups.\n588 ÷ 1365 ≈ 0.431."}, {"kind": "blank", "p": "A code has 2 letters (A–Z) followed by 3 digits (0–9).", "tag": "", "marks": "", "flat": [{"t": "Number of codes if letters and digits may repeat: __B1__", "a": {"B1": "676000"}}, {"t": "Number of codes if the two letters must be different: __B1__", "a": {"B1": "650000"}}], "sol": "26 × 26 × 10 × 10 × 10 = 676 000.\n26 × 25 × 1000 = 650 000."}]}, {"id": "s7", "label": "LT 8.7", "sub": "Binomial distribution — understand binomial distributions", "slides": [{"kind": "mcq", "text": "Which is NOT a binomial experiment?", "opts": ["flipping a coin 10 times and counting heads", "rolling a die 6 times and counting 5s", "drawing 3 cards without replacement and counting hearts", "asking 20 randomly chosen voters (from a huge city) yes/no and counting yes"], "correct": 2, "tag": "", "sol": "Without replacement the probability of a heart changes from draw to draw, so the trials are not independent with a constant p."}, {"kind": "mcq", "text": "A fair coin is flipped 4 times. What is the probability of exactly 2 heads?", "opts": ["0.25", "0.5", "0.375", "0.0625"], "correct": 2, "tag": "", "sol": "P(2) = ₄C₂ (0.5)²(0.5)² = 6 × 0.0625 = 0.375."}, {"kind": "mcq", "text": "n = 3 and p = 0.2. What is P(0 successes)?", "opts": ["0.008", "0.512", "0.2", "0.8"], "correct": 1, "tag": "", "sol": "P(0) = (1 − 0.2)³ = 0.8³ = 0.512."}, {"kind": "mcq", "text": "A probability distribution has P(X = 0) = 0.1, P(X = 1) = 0.3, P(X = 3) = 0.2, and X can also be 2. What is P(X = 2)?", "opts": ["0.2", "0.3", "0.6", "0.4"], "correct": 3, "tag": "", "sol": "The probabilities add to 1: 1 − (0.1 + 0.3 + 0.2) = 0.4."}, {"kind": "mcq", "text": "For the distribution P(X = 0) = 0.1, P(X = 1) = 0.3, P(X = 2) = 0.4, P(X = 3) = 0.2, what is the most likely value of X?", "opts": ["2", "1", "3", "0"], "correct": 0, "tag": "", "sol": "The largest probability is 0.4, at X = 2."}, {"kind": "mcq", "text": "In P(k) = ₙCₖ · pᵏ · (1 − p)ⁿ⁻ᵏ, what does n stand for?", "opts": ["the number of successes", "the probability of success", "the number of trials", "the number of failures"], "correct": 2, "tag": "", "sol": "n is the fixed number of independent trials; k is the number of successes."}, {"kind": "mcq", "text": "A fair coin is flipped 6 times. About what is the probability of 6 heads?", "opts": ["0.5", "0.0156", "0.167", "0.0833"], "correct": 1, "tag": "", "sol": "P(6) = 0.5⁶ = 1/64 ≈ 0.0156."}, {"kind": "mcq", "text": "Each ticket wins with probability 0.1. You buy 4 tickets (independent). About what is P(at least one wins)?", "opts": ["0.4", "0.656", "0.0001", "0.344"], "correct": 3, "tag": "", "sol": "P(none) = 0.9⁴ = 0.6561. P(at least one) = 1 − 0.6561 ≈ 0.344."}, {"kind": "blank", "p": "Three fair coins are flipped. X is the number of heads.", "tag": "", "marks": "", "flat": [{"t": "P(X = 0) = __B1__", "a": {"B1": "0.125"}}, {"t": "P(X = 1) = __B1__", "a": {"B1": "0.375"}}, {"t": "P(X = 2) = __B1__ and P(X = 3) = __B2__", "a": {"B1": "0.375", "B2": "0.125"}}, {"t": "Sum of all four probabilities: __B1__", "a": {"B1": "1"}}], "sol": "Only TTT: 1/8 = 0.125.\nHTT, THT, TTH: 3/8 = 0.375.\n3/8 = 0.375 and 1/8 = 0.125.\nA probability distribution always adds to 1.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 210\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"160.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">Number of heads in 3 flips</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"176.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0</text><line x1=\"38\" y1=\"138.0\" x2=\"310\" y2=\"138.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"138.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.1</text><line x1=\"38\" y1=\"100.0\" x2=\"310\" y2=\"100.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"100.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.2</text><line x1=\"38\" y1=\"62.0\" x2=\"310\" y2=\"62.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"62.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.3</text><line x1=\"38\" y1=\"24.0\" x2=\"310\" y2=\"24.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"24.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.4</text><rect x=\"41.0\" y=\"128.5\" width=\"62.0\" height=\"47.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"72.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">0</text><rect x=\"109.0\" y=\"33.5\" width=\"62.0\" height=\"142.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"140.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">1</text><rect x=\"177.0\" y=\"33.5\" width=\"62.0\" height=\"142.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"208.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">2</text><rect x=\"245.0\" y=\"128.5\" width=\"62.0\" height=\"47.5\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"276.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">3</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"38\" y1=\"176.0\" x2=\"38\" y2=\"24.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"174.0\" y=\"202.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">heads</text><text x=\"6.0\" y=\"100.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11px 'Source Sans 3',sans-serif\">P</text></svg>"}, {"kind": "blank", "p": "A player makes 70% of her free throws. She takes 5 shots. Find P(exactly 4 made).", "tag": "", "marks": "", "flat": [{"t": "n = __B1__, p = __B2__, k = 4", "a": {"B1": "5", "B2": "0.7"}}, {"t": "₅C₄ = __B1__", "a": {"B1": "5"}}, {"t": "0.7⁴ = __B1__", "a": {"B1": "0.2401"}}, {"t": "P(4) = 5 × 0.2401 × 0.3 = __B1__ (3 decimal places)", "a": {"B1": "0.360"}}], "sol": "5 trials, success probability 0.7.\nThere are 5 ways to choose which 4 shots go in.\n0.7⁴ = 0.2401.\n5 × 0.2401 × 0.3 = 0.36015 ≈ 0.360."}, {"kind": "blank", "p": "The same player takes 5 shots (p = 0.7).", "tag": "", "marks": "", "flat": [{"t": "P(5 made) = 0.7⁵ = __B1__ (3 decimal places)", "a": {"B1": "0.168"}}, {"t": "P(at least 4 made) = __B1__ (3 decimal places)", "a": {"B1": "0.528"}}, {"t": "P(at most 3 made) = __B1__ (3 decimal places)", "a": {"B1": "0.472"}}], "sol": "0.7⁵ = 0.16807 ≈ 0.168.\nP(4) + P(5) = 0.36015 + 0.16807 ≈ 0.528.\nComplement: 1 − 0.528 = 0.472.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 210\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text x=\"160.0\" y=\"11.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 12px 'Source Sans 3',sans-serif\">Binomial: n = 5, p = 0.7</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"176.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0</text><line x1=\"38\" y1=\"138.0\" x2=\"310\" y2=\"138.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"138.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.1</text><line x1=\"38\" y1=\"100.0\" x2=\"310\" y2=\"100.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"100.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.2</text><line x1=\"38\" y1=\"62.0\" x2=\"310\" y2=\"62.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"62.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.3</text><line x1=\"38\" y1=\"24.0\" x2=\"310\" y2=\"24.0\" style=\"stroke:var(--rule);stroke-width:.8\"/><text x=\"33.0\" y=\"24.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 10px 'Source Sans 3',sans-serif\">0.4</text><rect x=\"41.0\" y=\"175.1\" width=\"39.3\" height=\"0.9\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"60.7\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">0</text><rect x=\"86.3\" y=\"165.2\" width=\"39.3\" height=\"10.8\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"106.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">1</text><rect x=\"131.7\" y=\"125.7\" width=\"39.3\" height=\"50.3\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"151.3\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">2</text><rect x=\"177.0\" y=\"58.7\" width=\"39.3\" height=\"117.3\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"196.7\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">3</text><rect x=\"222.3\" y=\"39.1\" width=\"39.3\" height=\"136.9\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"242.0\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">4</text><rect x=\"267.7\" y=\"112.1\" width=\"39.3\" height=\"63.9\" style=\"fill:var(--accent-text);fill-opacity:.55;stroke:var(--accent-text);stroke-width:1.2\"/><text x=\"287.3\" y=\"187.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">5</text><line x1=\"38\" y1=\"176.0\" x2=\"310\" y2=\"176.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><line x1=\"38\" y1=\"176.0\" x2=\"38\" y2=\"24.0\" style=\"stroke:var(--ink-soft);stroke-width:1.3\"/><text x=\"174.0\" y=\"202.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">number of successes k</text><text x=\"6.0\" y=\"100.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 11px 'Source Sans 3',sans-serif\">P</text></svg>"}, {"kind": "blank", "p": "20% of phone users in a town use a certain network. 8 users are chosen at random.", "tag": "", "marks": "", "flat": [{"t": "P(none use it) = 0.8⁸ = __B1__ (3 decimal places)", "a": {"B1": "0.168"}}, {"t": "P(at least one uses it) = __B1__", "a": {"B1": "0.832"}}, {"t": "P(exactly one uses it) = 8 × 0.2 × 0.8⁷ = __B1__ (3 decimal places)", "a": {"B1": "0.336"}}], "sol": "0.8⁸ ≈ 0.1678.\n1 − 0.168 = 0.832.\n₈C₁ = 8; 8 × 0.2 × 0.2097 ≈ 0.336."}, {"kind": "blank", "p": "A fair die is rolled twice. X is the number of 6s.", "tag": "", "marks": "", "flat": [{"t": "P(X = 0) = __B1__", "a": {"B1": "25/36"}}, {"t": "P(X = 1) = __B1__", "a": {"B1": "10/36"}, "accept": ["5/18"]}, {"t": "P(X = 2) = __B1__", "a": {"B1": "1/36"}}], "sol": "(5/6)² = 25/36.\n₂C₁ × 1/6 × 5/6 = 10/36.\n(1/6)² = 1/36. Check: 25 + 10 + 1 = 36 ✓"}]}, {"id": "s8", "label": "Chapter test", "sub": "Chapter 8 test — all learning targets, mixed", "slides": [{"kind": "mcq", "text": "A spinner has 3 equal sections and a coin is flipped. How many outcomes are in the sample space?", "opts": ["5", "6", "8", "9"], "correct": 1, "tag": "", "sol": "3 × 2 = 6 outcomes."}, {"kind": "mcq", "text": "A number from 1 to 30 is chosen at random. What is P(the number is a multiple of 4)?", "opts": ["{7/30}", "{4/30}", "{1/4}", "{8/30}"], "correct": 0, "tag": "", "sol": "Multiples of 4 up to 30: 4, 8, …, 28, which is 7 numbers. P = 7/30."}, {"kind": "mcq", "text": "A goalkeeper saved 27 of 45 penalties. What is the experimental probability of a save?", "opts": ["0.27", "0.45", "0.4", "0.6"], "correct": 3, "tag": "", "sol": "27 ÷ 45 = 0.6."}, {"kind": "mcq", "text": "In a survey of 80 people, 48 prefer tea. Of the tea drinkers, 30 are women. What is P(woman | prefers tea)?", "opts": ["0.375", "0.625", "0.6", "0.3"], "correct": 1, "tag": "", "sol": "Given 'prefers tea', divide by 48: 30 ÷ 48 = 0.625."}, {"kind": "mcq", "text": "P(A) = 0.8 and P(A and B) = 0.2. What is P(B | A)?", "opts": ["0.16", "1.0", "0.25", "4"], "correct": 2, "tag": "", "sol": "0.2 ÷ 0.8 = 0.25."}, {"kind": "mcq", "text": "A and B are independent with P(A) = 0.2 and P(B) = 0.7. What is P(A and B)?", "opts": ["0.14", "0.9", "0.5", "0.35"], "correct": 0, "tag": "", "sol": "0.2 × 0.7 = 0.14."}, {"kind": "mcq", "text": "A drawer has 6 black and 4 white socks. Two are taken without replacement. What is P(both white)?", "opts": ["{4/25}", "{2/15}", "{1/5}", "{1/15}"], "correct": 1, "tag": "", "sol": "Without replacement: 4/10 × 3/9 = 12/90 = 2/15."}, {"kind": "mcq", "text": "P(A) = 0.5, P(B) = 0.45 and P(A and B) = 0.2. What is P(A or B)?", "opts": ["0.95", "0.225", "0.75", "0.7"], "correct": 2, "tag": "", "sol": "0.5 + 0.45 − 0.2 = 0.75."}, {"kind": "mcq", "text": "A die is rolled. What is P(1 or 6)?", "opts": ["{1/36}", "{1/6}", "{1/2}", "{1/3}"], "correct": 3, "tag": "", "sol": "Disjoint: 1/6 + 1/6 = 2/6 = 1/3."}, {"kind": "mcq", "text": "How many ways can 7 students stand in a line?", "opts": ["49", "5040", "720", "28"], "correct": 1, "tag": "", "sol": "7! = 5040."}, {"kind": "mcq", "text": "A teacher chooses 3 of 12 poems to read, in any order. How many choices are there?", "opts": ["220", "1320", "36", "1728"], "correct": 0, "tag": "", "sol": "Order does not matter: ₁₂C₃ = 1320 ÷ 6 = 220."}, {"kind": "mcq", "text": "A fair coin is flipped 5 times. What is P(exactly 1 head)?", "opts": ["{1/32}", "{1/5}", "{5/32}", "{10/32}"], "correct": 2, "tag": "", "sol": "₅C₁ (½)⁵ = 5/32."}, {"kind": "blank", "p": "Two dice are rolled.", "tag": "", "marks": "", "flat": [{"t": "Number of ways to get a sum of 10: __B1__", "a": {"B1": "3"}}, {"t": "P(sum = 10) = __B1__", "a": {"B1": "1/12"}}, {"t": "P(sum is less than 10) = __B1__", "a": {"B1": "5/6"}}], "sol": "(4,6), (5,5), (6,4).\n3/36 = 1/12.\nSums of 10, 11, 12: 3 + 2 + 1 = 6 ways. P(< 10) = 1 − 6/36 = 5/6."}, {"kind": "blank", "p": "300 customers: online and satisfied 120, online and not satisfied 30; in store and satisfied 90, in store and not satisfied 60.", "tag": "", "marks": "", "flat": [{"t": "Marginal relative frequency of 'satisfied' = __B1__", "a": {"B1": "0.7"}}, {"t": "P(satisfied | online) = __B1__", "a": {"B1": "0.8"}}, {"t": "P(satisfied | in store) = __B1__", "a": {"B1": "0.6"}}, {"t": "Being satisfied and shopping online are __B1__ (independent / dependent).", "a": {"B1": "dependent"}, "expr": "words"}], "sol": "(120 + 90) ÷ 300 = 0.7.\n120 ÷ 150 = 0.8.\n90 ÷ 150 = 0.6.\nP(satisfied | online) = 0.8 ≠ 0.7 = P(satisfied)."}, {"kind": "blank", "p": "A bag has 5 red and 3 yellow balls. Two are drawn one after the other.", "tag": "", "marks": "", "flat": [{"t": "With replacement: P(both red) = __B1__", "a": {"B1": "25/64"}}, {"t": "Without replacement: P(both red) = __B1__", "a": {"B1": "5/14"}}, {"t": "Without replacement: P(one of each colour) = __B1__", "a": {"B1": "15/28"}}], "sol": "5/8 × 5/8 = 25/64.\n5/8 × 4/7 = 20/56 = 5/14.\nRY or YR: 5/8 × 3/7 + 3/8 × 5/7 = 30/56 = 15/28."}, {"kind": "blank", "p": "Of 60 students, 35 like maths, 25 like science and 12 like both.", "tag": "", "marks": "", "flat": [{"t": "Number who like maths or science: __B1__", "a": {"B1": "48"}}, {"t": "P(maths or science) = __B1__", "a": {"B1": "0.8"}}, {"t": "P(neither) = __B1__", "a": {"B1": "0.2"}}], "sol": "35 + 25 − 12 = 48.\n48 ÷ 60 = 0.8.\n1 − 0.8 = 0.2."}, {"kind": "blank", "p": "A 4-digit PIN uses the digits 0–9.", "tag": "", "marks": "", "flat": [{"t": "Number of PINs if digits may repeat: __B1__", "a": {"B1": "10000"}}, {"t": "Number of PINs with no repeated digit: ₁₀P₄ = __B1__", "a": {"B1": "5040"}}, {"t": "P(a random PIN has no repeated digit) = __B1__", "a": {"B1": "0.504"}}], "sol": "10⁴ = 10 000.\n10 × 9 × 8 × 7 = 5040.\n5040 ÷ 10 000 = 0.504."}, {"kind": "blank", "p": "A seed germinates with probability 0.9. Six seeds are planted.", "tag": "", "marks": "", "flat": [{"t": "P(all 6 germinate) = 0.9⁶ = __B1__ (3 decimal places)", "a": {"B1": "0.531"}}, {"t": "P(exactly 5 germinate) = 6 × 0.9⁵ × 0.1 = __B1__ (3 decimal places)", "a": {"B1": "0.354"}}, {"t": "P(at least 5 germinate) = __B1__ (3 decimal places)", "a": {"B1": "0.886"}}], "sol": "0.9⁶ = 0.531441 ≈ 0.531.\n6 × 0.59049 × 0.1 = 0.354294 ≈ 0.354.\n0.531441 + 0.354294 = 0.885735 ≈ 0.886."}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-a2-ch8';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Probability</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = '<button class="tab-btn'+(activeTab==='theory'?' active':'')+'" data-tab="theory">Theory<span class="tab-count">notes</span></button>' + TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('');
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d','e','f'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — revisit it anytime from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+(item.status!=='unanswered'?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick); activeTab='theory';
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };


/* ================= theory tab ================= */
function renderTheory(){
  var wrap=document.getElementById('wrap');
  wrap.innerHTML='<div class="theory">'+THEORY+'</div>';
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Theory — notes, key ideas and worked examples';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
  wrap.querySelectorAll('[data-jump]').forEach(function(b){ b.addEventListener('click',function(){ var t=document.getElementById(b.dataset.jump); if(t) t.scrollIntoView({behavior:'smooth',block:'start'}); }); });
}
var _rsTheory = renderSlide;
renderSlide = function(){
  if(activeTab==='theory'){ renderTheory(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  document.querySelector('.slide-progress').style.display='';
  document.querySelector('.navbar').style.display='';
  document.getElementById('paletteFab').style.display='';
  _rsTheory();
};

renderLogin();
})();
</script>
</body>
</html>
