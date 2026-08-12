<!doctype html><html><head><meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1"><title>Gavin OS</title><style>
*{box-sizing:border-box}body{margin:0;background:#17131f;color:white;font:20px Arial;overflow:hidden}.s{display:none;width:100vw;height:100vh;padding:45px 65px}.on{display:block}.brand{font-size:30px;font-weight:bold}.brand span{opacity:.5}.head{display:flex;justify-content:space-between}h1{font-size:42px;font-weight:normal;margin:65px 0 25px}.apps{display:flex;gap:22px}.app,.row{background:#292332;border:3px solid transparent;border-radius:14px;padding:22px}.app{width:190px;height:140px}.sel{border-color:white!important;transform:scale(1.04)}.icon{font-size:42px}.name{margin-top:12px}.list{width:500px}.item{padding:15px;border-radius:6px}.item.sel{background:white;color:#222}.sw{display:inline-block;width:90px;height:65px;border:4px solid transparent;border-radius:10px;margin:7px}.row{max-width:700px;margin:10px 0;display:flex;justify-content:space-between}.foot{position:absolute;bottom:25px;opacity:.55}
</style></head><body>
<section id="setup" class="s on"><div class="brand">GAVIN OS <span>• Language</span></div><div style="text-align:center;margin-top:15vh"><h1>Let's get started</h1><div id="langs" class="list" style="margin:auto"></div></div></section>
<section id="home" class="s"><div class="head"><div class="brand">GAVIN OS <span>Home</span></div><div id="clock"></div></div><h1 id="homeTitle">Home</h1><div id="apps" class="apps"></div><div class="foot">← → Navigate • Enter Open • Home = Home</div></section>
<section id="settings" class="s"><div class="brand">GAVIN OS <span>Settings</span></div><h1>Settings</h1><div id="settingsList"></div><div class="foot">↑ ↓ Select • Enter Open • Home = Home</div></section>
<section id="language" class="s"><div class="brand">GAVIN OS <span>Language</span></div><h1>Choose language</h1><div id="languageList" class="list"></div></section>
<section id="wallpaper" class="s"><div class="brand">GAVIN OS <span>Wallpaper</span></div><h1>Wallpaper</h1><div id="colors"></div></section>
<section id="music" class="s"><div class="brand">GAVIN OS <span>Background music</span></div><h1>Background music</h1><div id="musicList" class="list"></div><div class="foot">Enter = select • Home = Home</div></section>
<script>
const L=[["English","Home","Settings","Language","Wallpaper","Background music"],["Español","Inicio","Configuración","Idioma","Fondo","Música de fondo"],["Français","Accueil","Paramètres","Langue","Fond","Musique de fond"],["Deutsch","Startseite","Einstellungen","Sprache","Hintergrund","Hintergrundmusik"]];
const C=[["Purple","#17131f"],["Red","#241010"],["Blue","#0d1726"],["Green","#0d2117"],["Orange","#26170d"],["Pink","#24101d"],["Teal","#0b2020"],["Dark","#090909"],["Yellow","#211d08"]];
const M=["Off","Retro Arcade","Rainy Pixel","Classic TV","Night Drive"];
let li=0,ai=0,si=0,ci=0,mi=0,screen="setup",lang=+localStorage.gavinLang||0,color=+localStorage.gavinColor||0,music=+localStorage.gavinMusic||0;
function S(x){document.querySelectorAll(".s").forEach(e=>e.classList.remove("on"));document.getElementById(x).classList.add("on");screen=x}
function H(a,i){a.forEach((e,n)=>e.classList.toggle("sel",n==i))}
function home(){S("home");ai=0;H([...document.querySelectorAll(".app")],0)}
function draw(){
 document.documentElement.style.setProperty("--bg",C[color][1]);document.body.style.background=C[color][1];
 document.getElementById("langs").innerHTML=L.map((x,i)=>`<div class="item ${i==li?"sel":""}">${x[0]}</div>`).join("");
 document.getElementById("languageList").innerHTML=L.map((x,i)=>`<div class="item ${i==li?"sel":""}">${x[0]}</div>`).join("");
 document.getElementById("homeTitle").textContent=L[lang][1];
 document.getElementById("apps").innerHTML=["▶️ YouTube","🎵 Spotify","🌐 Google","⚙️ "+L[lang][2]].map((x,i)=>`<div class="app ${i==ai?"sel":""}"><div class="icon">${x.slice(0,2)}</div><div class="name">${x.slice(2)}</div></div>`).join("");
 document.getElementById("settingsList").innerHTML=[[L[lang][3],L[lang][0]],[L[lang][4],C[color][0]],[L[lang][5],M[music]]].map((x,i)=>`<div class="row ${i==si?"sel":""}"><span>${x[0]}</span><span>${x[1]}</span></div>`).join("");
 document.getElementById("colors").innerHTML=C.map((x,i)=>`<span class="sw ${i==ci?"sel":""}" style="background:${x[1]}"></span>`).join("");
 document.getElementById("musicList").innerHTML=M.map((x,i)=>`<div class="item ${i==mi?"sel":""}">${x}</div>`).join("");
}
function app(){if(ai==0)open("https://www.youtube.com/");if(ai==1)open("https://open.spotify.com/");if(ai==2)open("https://www.google.com/");if(ai==3){si=0;S("settings")}}
document.onkeydown=e=>{
 if(e.key=="Home"){e.preventDefault();home();draw();return}
 if(screen=="setup"){if(e.key=="ArrowDown")li=Math.min(3,li+1);if(e.key=="ArrowUp")li=Math.max(0,li-1);if(e.key=="Enter"){lang=li;localStorage.gavinLang=lang;home()}draw();return}
 if(screen=="home"){if(e.key=="ArrowRight")ai=Math.min(3,ai+1);if(e.key=="ArrowLeft")ai=Math.max(0,ai-1);if(e.key=="Enter")app();draw();return}
 if(screen=="settings"){if(e.key=="ArrowDown")si=Math.min(2,si+1);if(e.key=="ArrowUp")si=Math.max(0,si-1);if(e.key=="Enter"){if(si==0){li=lang;S("language")}else if(si==1){ci=color;S("wallpaper")}else{mi=music;S("music")}}draw();return}
 if(screen=="language"){if(e.key=="ArrowDown")li=Math.min(3,li+1);if(e.key=="ArrowUp")li=Math.max(0,li-1);if(e.key=="Enter"){lang=li;localStorage.gavinLang=lang;S("settings")}draw();return}
 if(screen=="wallpaper"){if(e.key=="ArrowRight")ci=Math.min(C.length-1,ci+1);if(e.key=="ArrowLeft")ci=Math.max(0,ci-1);if(e.key=="Enter"){color=ci;localStorage.gavinColor=color}draw();return}
 if(screen=="music"){if(e.key=="ArrowDown")mi=Math.min(M.length-1,mi+1);if(e.key=="ArrowUp")mi=Math.max(0,mi-1);if(e.key=="Enter"){music=mi;localStorage.gavinMusic=music}draw();return}
};
setInterval(()=>clock.textContent=new Date().toLocaleTimeString([],{hour:"numeric",minute:"2-digit"}),1000);draw();
</script></body></html>
