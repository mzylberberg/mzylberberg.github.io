<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Mya Zylberberg | GRC &amp; Product, Cybersecurity</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Special+Elite&family=Instrument+Sans:wght@400;500;600&family=Caveat:wght@600&display=swap" rel="stylesheet">
<style>
:root{--cork:#B58757;--cork2:#A47749;--room:#2A211B;--paper:#F6F1E3;--folder:#E4C98E;--ink:#25201A;--muted:#5C5346;--red:#C0262D;--tape:#E9DE9C;--blue:#2B4A7A;
--type:"Special Elite","Courier New",monospace;--body:"Instrument Sans","Helvetica Neue",Arial,sans-serif;--hand:"Caveat","Comic Sans MS",cursive;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--cork:#8F6741;--cork2:#815B37;--room:#14100D}}
:root[data-theme="dark"]{--cork:#8F6741;--cork2:#815B37;--room:#14100D}
html{height:100%;scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--room);color:var(--ink);font:400 1rem/1.55 var(--body)}
a{color:var(--blue)}
:focus-visible{outline:3px solid var(--red);outline-offset:3px}
.wrap{max-width:1100px;margin:0 auto;padding:0 20px}
header.top{display:flex;flex-wrap:wrap;gap:12px;justify-content:space-between;align-items:center;padding:18px 0;color:#F6F1E3;font-family:var(--type)}
header.top nav{display:flex;gap:8px}
.tab{font:inherit;background:transparent;color:#F6F1E3;border:1px solid #F6F1E366;padding:7px 14px;border-radius:4px;cursor:pointer}
.tab[aria-pressed="true"]{background:#F6F1E3;color:#25201A}
.board{background:var(--cork);background-image:radial-gradient(var(--cork2) 1.2px,transparent 1.6px),radial-gradient(#00000014 1px,transparent 1.5px);background-size:9px 9px,13px 13px;background-position:0 0,4px 5px;border:12px solid #5A3C22;border-radius:6px;box-shadow:inset 0 0 40px #0006;padding:40px 28px 44px;position:relative}
.stamp{display:inline-block;font:400 .85rem var(--type);color:var(--red);border:2px solid var(--red);padding:2px 10px;transform:rotate(-3deg);background:#F6F1E3cc}
h1{font:400 clamp(2.1rem,5.5vw,3.6rem)/1.05 var(--type);margin:12px 0 10px;color:#FFF8E6;text-shadow:0 2px 0 #0005}
.intro{max-width:34em;color:#FFF8E6;font-size:1.1rem;text-shadow:0 1px 0 #0006;margin:0 0 34px}
.paper{background:var(--paper);box-shadow:0 6px 14px #0005;position:relative;padding:20px 18px 18px}
.paper::before{content:"";position:absolute;top:-9px;left:50%;width:18px;height:18px;margin-left:-9px;border-radius:50%;background:radial-gradient(circle at 35% 35%,#FF8A80,var(--red) 60%,#7A1015);box-shadow:0 3px 4px #0006;z-index:2}
.cases{display:grid;grid-template-columns:repeat(3,1fr);gap:28px;position:relative;margin-bottom:26px}
.cases svg{position:absolute;left:0;top:-8px;width:100%;height:60px;pointer-events:none;z-index:3;overflow:visible}
.case:nth-child(2){transform:rotate(-1.4deg)}.case:nth-child(3){transform:rotate(1.2deg)}.case:nth-child(4){transform:rotate(-.8deg)}
.case small{font:400 .8rem var(--type);color:var(--red)}
.case h2{font:400 1.3rem/1.15 var(--type);margin:6px 0 8px}
.case p{margin:0 0 14px;color:var(--muted);font-size:.95rem}
.btn{font:600 .92rem var(--body);background:var(--ink);color:var(--paper);border:0;padding:9px 14px;border-radius:4px;cursor:pointer;text-decoration:none;display:inline-block}
.btn.ghost{background:transparent;color:var(--ink);border:1.5px solid var(--ink)}
.btn[aria-expanded="true"]{background:var(--red)}
.note{font:600 1.25rem/1.1 var(--hand);color:#3A2E22;background:#FFF1A8;display:inline-block;padding:10px 14px;box-shadow:0 5px 10px #0004;transform:rotate(2deg);margin-top:10px}
.locker{display:grid;grid-template-columns:1fr 1.5fr;gap:28px;align-items:start;margin-top:30px}
.folder{background:var(--folder);box-shadow:0 6px 14px #0005;padding:20px 18px;position:relative}
.folder::before{content:"EVIDENCE LOCKER";position:absolute;top:-14px;left:12px;background:var(--folder);font:400 .8rem var(--type);padding:2px 12px;border-radius:5px 5px 0 0}
.folder h3,.paper h3{font:400 1.15rem var(--type);margin:0 0 10px}
.tags{display:flex;flex-wrap:wrap;gap:8px;padding:0;margin:0;list-style:none}
.tags a{display:block;background:var(--paper);border:1px dashed #8A7A5A;padding:6px 10px;text-decoration:none;color:var(--ink);font-size:.9rem}
.tags a:hover{border-color:var(--red);color:var(--red)}
.demo{background:var(--paper);margin-top:30px;padding:26px 22px;box-shadow:0 8px 18px #0006;border-top:6px solid var(--red)}
.demo[hidden],[hidden]{display:none!important}
.demo h3{font:400 1.4rem var(--type);margin:0 0 4px}
.sub{color:var(--muted);margin:0 0 18px;font-size:.95rem}
.row{display:grid;grid-template-columns:1fr 1fr;gap:24px}
fieldset{border:0;padding:0;margin:0}
legend{font:400 .95rem var(--type);margin-bottom:8px}
label.chk{display:flex;gap:10px;align-items:center;padding:7px 0;cursor:pointer}
label.chk input{width:18px;height:18px;accent-color:var(--red)}
.verdict{border:2px solid var(--ink);padding:14px;background:#fff8}
.verdict b{font:400 1.3rem var(--type);display:block}
.pills{display:flex;gap:6px;margin:14px 0 8px;flex-wrap:wrap}
.pill{font:500 .88rem var(--body);border:1.5px solid var(--ink);background:transparent;padding:5px 12px;border-radius:99px;cursor:pointer;color:var(--ink)}
.pill[aria-pressed="true"],.pill[aria-selected="true"]{background:var(--ink);color:var(--paper)}
.chat{border:1.5px solid var(--ink);background:#fff9;min-height:150px;padding:12px;display:flex;flex-direction:column;gap:8px}
.msg{padding:8px 12px;border-radius:8px;max-width:90%}
.u{background:var(--ink);color:var(--paper);align-self:flex-end}.a{background:#EADFC4}
.meta{font-size:.82rem;color:var(--muted);display:block;margin-top:4px}
.ask{display:flex;gap:8px;margin-top:10px}
.ask input{flex:1;font:inherit;padding:9px 10px;border:1.5px solid var(--ink);background:#fff}
.ba{display:inline-flex;border:1.5px solid var(--ink);border-radius:4px;overflow:hidden;margin-bottom:14px}
.ba button{font:600 .9rem var(--body);border:0;background:transparent;padding:8px 16px;cursor:pointer;color:var(--ink)}
.ba button[aria-pressed="true"]{background:var(--ink);color:var(--paper)}
.honors{padding:36px 28px;background:var(--paper);box-shadow:0 8px 18px #0006;border-top:6px solid var(--red)}
.honors h2{font:400 1.8rem var(--type);margin:0 0 16px}
.honors ul{padding-left:20px;line-height:1.9}
footer{color:#F6F1E3bb;padding:22px 0 40px;font-family:var(--type);font-size:.9rem}
footer a{color:#FFE9A8}
@media (max-width:860px){
  .cases{grid-template-columns:1fr}.cases svg{display:none}.case,.case:nth-child(n){transform:none}
  .locker,.row{grid-template-columns:1fr}.board{padding:34px 16px}
}
@media (prefers-reduced-motion:no-preference){.stamp{animation:thud .5s ease-out}@keyframes thud{from{transform:rotate(-3deg) scale(1.8);opacity:0}}}
</style>
</head>
<body>
<div class="wrap">
<header class="top">
  <span>MZ / CASE FILES</span>
  <nav aria-label="Pages"><button class="tab" data-view="board" aria-pressed="true">Case files</button><button class="tab" data-view="honors" aria-pressed="false">Honors</button></nav>
</header>

<main id="board-view">
<div class="board">
  <span class="stamp">OPEN FILE</span>
  <h1>Mya Zylberberg</h1>
  <p class="intro">M.S. Cybersecurity. I build products and run audits with a security mindset, and I explain risk to executives, engineers and users. Open any case file to try the work yourself.</p>

  <div class="cases">
    <svg viewBox="0 0 100 60" preserveAspectRatio="none" aria-hidden="true"><path d="M16.7 8 Q33 48 50 8 T83.3 8" fill="none" stroke="#C0262D" stroke-width="2.2" vector-effect="non-scaling-stroke"/></svg>
    <article class="paper case">
      <small>CASE 01 · PRODUCT</small><h2>Siena VISTA website</h2>
      <p>Turned a marketing site into a user-centered product, from research to accessibility audit and KPIs.</p>
      <button class="btn" data-open="d1" aria-expanded="false">Open case file</button>
    </article>
    <article class="paper case">
      <small>CASE 02 · SECURITY</small><h2>MFA enforcement</h2>
      <p>One policy, three stories: the same MFA decision explained to executives, engineers and product owners.</p>
      <button class="btn" data-open="d2" aria-expanded="false">Open case file</button>
    </article>
    <article class="paper case">
      <small>CASE 03 · AI + ACCESSIBILITY</small><h2>Accessible AI resource helper</h2>
      <p>A mock AI feature that shows the full user flow, with accessibility built in.</p>
      <button class="btn" data-open="d3" aria-expanded="false">Open case file</button>
    </article>
  </div>

  <!-- DEMO 1 -->
  <section class="demo" id="d1" hidden aria-label="Siena VISTA case file">
    <h3>Marketing site to product</h3>
    <p class="sub">Switch the lens, then select a work area to see what I did.</p>
    <div class="ba" role="group" aria-label="Lens"><button data-lens="0" aria-pressed="true">Before: marketing</button><button data-lens="1" aria-pressed="false">After: product</button></div>
    <p id="lens-text" class="verdict" style="margin:0 0 14px"></p>
    <div class="pills" id="work-pills"></div>
    <p id="work-text" class="verdict" aria-live="polite" style="margin:0 0 14px"></p>
    <a class="btn" href="https://github.com/mzylberberg/siena-vista-website-product-optimization">View project and walkthrough</a>
  </section>

  <!-- DEMO 2 -->
  <section class="demo" id="d2" hidden aria-label="MFA enforcement case file">
    <h3>MFA enforcement, risk-adaptive</h3>
    <p class="sub">An illustrative policy model. Check the conditions of a sign-in and read the decision for each audience.</p>
    <div class="row">
      <fieldset><legend>Sign-in conditions</legend>
        <label class="chk"><input type="checkbox" data-w="2"> New or unmanaged device</label>
        <label class="chk"><input type="checkbox" data-w="2"> Unfamiliar location</label>
        <label class="chk"><input type="checkbox" data-w="3"> Admin or privileged account</label>
        <label class="chk"><input type="checkbox" data-w="3"> Sensitive data (HR, finance)</label>
        <label class="chk"><input type="checkbox" data-w="1"> Outside normal hours</label>
      </fieldset>
      <div>
        <div class="verdict"><b id="mfa-d">Allow</b><span id="mfa-s"></span></div>
        <div class="pills" role="tablist" aria-label="Audience">
          <button class="pill" role="tab" data-a="exec" aria-selected="true">Executive</button>
          <button class="pill" role="tab" data-a="tech" aria-selected="false">Technical</button>
          <button class="pill" role="tab" data-a="prod" aria-selected="false">Product</button>
        </div>
        <p id="mfa-brief" aria-live="polite" style="margin:0"></p>
      </div>
    </div>
    <p style="margin:18px 0 0"><a class="btn" href="https://github.com/mzylberberg/mfa-enforcement-technical-content">View project</a></p>
  </section>

  <!-- DEMO 3 -->
  <section class="demo" id="d3" hidden aria-label="Accessible AI resource helper case file">
    <h3>Accessible AI resource helper</h3>
    <p class="sub">Mock response logic, as in the project. Ask a question or pick one.</p>
    <div class="chat" id="chat" aria-live="polite"><div class="msg a">Hi, I can point you to resources. What do you need?</div></div>
    <div class="pills" id="chips"></div>
    <form class="ask" id="ask"><label class="sr" for="q" style="position:absolute;left:-9999px">Your question</label><input id="q" placeholder="Type a question" autocomplete="off"><button class="btn">Ask</button></form>
    <p style="margin:18px 0 0"><a class="btn" href="https://github.com/mzylberberg/accessible-ai-resource-helper">View project</a></p>
  </section>

  <div class="locker">
    <div class="folder">
      <h3>Resume</h3>
      <p style="margin:0 0 16px"><a class="btn" href="https://github.com/mzylberberg/mzylberberg/blob/main/resumes/Mya_Zylberberg_Cybersecurity_General.pdf">Open resume (PDF)</a></p>
      <span class="note">Open to GRC and product roles</span>
    </div>
    <div class="folder">
      <h3>Certifications</h3>
      <ul class="tags">
        <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/certificates/CompTIA%20Security+%20ce%20certificate.pdf">CompTIA Security+</a></li>
        <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/certificates/Belkasoft%20Completion%20-%20Mya%20Zylberberg%20-%202024-03-26.pdf">Belkasoft Android Forensics</a></li>
        <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/certificates/Contracting%20Fundamentals%20-%20Mya%20Zylberberg.pdf">Contracting Fundamentals</a></li>
        <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/certificates/enterprise-design-thinking-practitioner.png">IBM Enterprise Design Thinking Practitioner</a></li>
        <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/certificates/watson-analytics-level-1.png">IBM Watson Analytics Level 1</a></li>
        <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/certificates/working-in-a-digital-world-professional-skills.png">IBM Working in a Digital World</a></li>
      </ul>
    </div>
  </div>
  <p style="color:#FFF8E6;margin:26px 0 0;font-family:var(--type)">More evidence: <a style="color:#FFE9A8" href="https://github.com/mzylberberg/mzylberberg/blob/main/Agriculture%20Industry%20Mock%20Risk%20Assessment.pdf">agriculture risk assessment</a> · <a style="color:#FFE9A8" href="https://github.com/mzylberberg/governance-tool">governance tool</a></p>
</div>
</main>

<main id="honors-view" hidden>
  <div class="honors">
    <h2>Honors and awards</h2>
    <ul>
      <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/honors/Outstanding%20Academic%20Award.jpg">Outstanding Academic Award (4.0), 2024</a></li>
      <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/honors/Certificate%20of%20Appreciation%20DEI.jpg">Diversity, Equity, &amp; Inclusion Appreciation Award, 2024</a></li>
      <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/honors/Spellman%20Scholar.jpg">Dr. Seth Spellman Jr. Award, 2023</a></li>
      <li><a href="https://github.com/mzylberberg/mzylberberg/blob/main/honors/STEP%20Summer%20Institute%20Certificate.jpg">STEP Summer Institute Certificate, 2023</a></li>
      <li><a href="https://local3ibew.org/news/73rd-annual-jib-scholarship-breakfast">JIB 73rd Annual Scholarship Award</a></li>
    </ul>
  </div>
</main>

<footer>
  <a href="https://github.com/mzylberberg">GitHub</a> · <a href="https://www.linkedin.com/in/mya-zylberberg">LinkedIn</a>
</footer>
</div>

<script>
var $=function(s,r){return(r||document).querySelector(s)},$$=function(s,r){return Array.prototype.slice.call((r||document).querySelectorAll(s))};
/* views */
$$('.tab').forEach(function(t){t.onclick=function(){var h=t.dataset.view==='honors';
  $('#board-view').hidden=h;$('#honors-view').hidden=!h;
  $$('.tab').forEach(function(x){x.setAttribute('aria-pressed',x===t)});window.scrollTo(0,0)}});
/* case files: one open at a time */
$$('[data-open]').forEach(function(b){b.onclick=function(){var id=b.dataset.open,was=!$('#'+id).hidden;
  $$('.demo').forEach(function(d){d.hidden=true});$$('[data-open]').forEach(function(x){x.setAttribute('aria-expanded','false')});
  if(!was){var d=$('#'+id);d.hidden=false;b.setAttribute('aria-expanded','true');d.scrollIntoView({behavior:'smooth',block:'start'})}}});
/* demo 1 */
var lens=['Built to describe the program and attract interest. Content was organised around what the university wanted to say.','Built around what visitors need to get done. Content, navigation and success measures follow user needs.'];
var work={'User research':'Learn who uses the site and what they are trying to do before changing anything.','Pain-point analysis':'Turn research into a ranked list of where visitors get stuck.','Content strategy':'Rewrite and reorganise content around tasks, in plain language.','SEO optimization':'Make the right pages findable for the questions people actually search.','Accessibility auditing':'Check pages against accessibility standards so more people can use them.','Website governance':'Set owners, review cycles and standards so quality lasts.','KPI development':'Define the measures that show whether the site is helping users.'};
$('#lens-text').textContent=lens[0];
$$('[data-lens]').forEach(function(b){b.onclick=function(){$('#lens-text').textContent=lens[+b.dataset.lens];$$('[data-lens]').forEach(function(x){x.setAttribute('aria-pressed',x===b)})}});
Object.keys(work).forEach(function(k,i){var p=document.createElement('button');p.className='pill';p.textContent=k;p.setAttribute('aria-pressed','false');
  p.onclick=function(){$('#work-text').textContent=work[k];$$('#work-pills .pill').forEach(function(x){x.setAttribute('aria-pressed',x===p)})};$('#work-pills').appendChild(p)});
$('#work-text').textContent='Select a work area above.';
/* demo 2 */
var aud='exec',dec=[
 {t:'Allow',s:'Low risk. Normal sign-in.',e:'Low-risk sign-ins stay fast, so staff are not slowed down where the risk does not justify it.',k:'Policy: risk score 0-1 → allow with standard session. Log the event.',p:'No added friction. Most daily sign-ins should land here.'},
 {t:'Step-up MFA',s:'Medium risk. Ask for a second factor.',e:'Extra verification appears only when the situation looks unusual, which cuts account-takeover risk at modest cost.',k:'Policy: risk score 2-4 → require MFA with number matching. Re-evaluate on session change.',p:'One extra prompt. Tell users why it appeared so it does not feel random.'},
 {t:'Phishing-resistant MFA',s:'High risk. Require a security key or passkey.',e:'Privileged or sensitive access gets the strongest control, matching the higher impact if it is compromised.',k:'Policy: risk score 5-7 → require FIDO2 or passkey. Alert the security team.',p:'Higher friction, so offer a clear fallback path and support contact.'},
 {t:'Block and review',s:'Very high risk. Access paused for approval.',e:'The combination of signals is too risky to allow on its own, so a person reviews it before access is granted.',k:'Policy: risk score 8+ → deny, open a review ticket, notify the account owner.',p:'Show a clear message and next step. An unexplained block is the fastest way to lose trust.'}];
function mfa(){var s=0;$$('#d2 input').forEach(function(c){if(c.checked)s+=+c.dataset.w});var d=dec[s>=8?3:s>=5?2:s>=2?1:0];
 $('#mfa-d').textContent=d.t+' (score '+s+')';$('#mfa-s').textContent=d.s;$('#mfa-brief').textContent=aud==='exec'?d.e:aud==='tech'?d.k:d.p}
$$('#d2 input').forEach(function(c){c.onchange=mfa});
$$('[data-a]').forEach(function(b){b.onclick=function(){aud=b.dataset.a;$$('[data-a]').forEach(function(x){x.setAttribute('aria-selected',x===b)});mfa()}});mfa();
/* demo 3 */
var qa=[['Find housing help','Here are three housing resources near you. Each one lists its phone number, hours and whether it offers language support.'],['Request an accommodation','You can request an accommodation in writing. Here is a short template and who to send it to.'],['Explain this in plain language','Sure. Paste the text and I will rewrite it at a simpler reading level and list the key steps.']];
function say(q){var c=$('#chat'),u=document.createElement('div');u.className='msg u';u.textContent=q;c.appendChild(u);
 var r=qa.filter(function(x){return q.toLowerCase().indexOf(x[0].split(' ')[0].toLowerCase())>-1})[0];
 setTimeout(function(){var a=document.createElement('div');a.className='msg a';
  a.textContent=r?r[1]:'I am a mock helper, so I only know a few topics. Try one of the suggestions below.';
  var m=document.createElement('span');m.className='meta';m.textContent='Plain language · announced to screen readers';a.appendChild(m);c.appendChild(a)},500)}
qa.forEach(function(x){var b=document.createElement('button');b.className='pill';b.textContent=x[0];b.onclick=function(){say(x[0])};$('#chips').appendChild(b)});
$('#ask').onsubmit=function(e){e.preventDefault();var v=$('#q').value.trim();if(v){say(v);$('#q').value=''}};
</script>
</body>
</html>
