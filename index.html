<!DOCTYPE html>  
  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">  
<title>Color Fun! 🎨</title>  
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;700;900&display=swap" rel="stylesheet">  
<style>  
  *{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}  
  :root{--bg:#fff9f0;--panel:#fff3e0;--shadow:rgba(0,0,0,.13)}  
  body{font-family:'Nunito',sans-serif;background:var(--bg);min-height:100vh;display:flex;flex-direction:column;overflow:hidden;touch-action:manipulation}  
  header{background:linear-gradient(135deg,#ff6b9d,#ff9a3c);padding:10px 16px 8px;display:flex;align-items:center;justify-content:space-between;box-shadow:0 4px 12px rgba(255,107,157,.35);flex-shrink:0;z-index:10}  
  header h1{font-family:'Fredoka One',cursive;font-size:1.6rem;color:#fff;text-shadow:2px 2px 0 rgba(0,0,0,.12)}  
  .star-count{background:rgba(255,255,255,.25);border-radius:30px;padding:4px 12px;color:#fff;font-weight:900;font-size:1rem;display:flex;align-items:center;gap:4px}  
  .scene-bar{display:flex;gap:8px;padding:10px 14px;overflow-x:auto;background:var(--panel);border-bottom:3px solid #ffe0b2;flex-shrink:0;scrollbar-width:none}  
  .scene-bar::-webkit-scrollbar{display:none}  
  .scene-btn{flex-shrink:0;background:#fff;border:3px solid #ffd54f;border-radius:14px;padding:6px 14px;font-family:'Fredoka One',cursive;font-size:.85rem;cursor:pointer;transition:transform .15s,background .15s;white-space:nowrap;color:#555}  
  .scene-btn.active{background:linear-gradient(135deg,#ffd54f,#ffb300);border-color:#fb8c00;color:#fff;transform:scale(1.08);box-shadow:0 3px 8px rgba(255,152,0,.4)}  
  main{flex:1;display:flex;flex-direction:column;overflow:hidden;position:relative}  
  .canvas-wrap{flex:1;display:flex;align-items:center;justify-content:center;padding:10px;overflow:hidden}  
  svg.drawing{width:100%;max-height:100%;border-radius:18px;box-shadow:0 6px 24px var(--shadow);background:#fff;touch-action:none}  
  svg .region{cursor:pointer;transition:filter .1s}  
  svg .region:active{filter:brightness(.86)}  
  .num-label{font-family:'Fredoka One',cursive;font-size:9.5px;fill:#222;pointer-events:none;user-select:none;paint-order:stroke;stroke:#fff;stroke-width:3px}  
  .celebrate{position:absolute;inset:0;pointer-events:none;display:flex;align-items:center;justify-content:center;opacity:0;transition:opacity .4s;z-index:20}  
  .celebrate.show{opacity:1}  
  .celebrate-text{font-family:'Fredoka One',cursive;font-size:2.8rem;color:#fff;background:linear-gradient(135deg,#ff6b9d,#ff9a3c);padding:18px 32px;border-radius:28px;box-shadow:0 8px 32px rgba(255,107,157,.5);text-align:center;animation:pop .4s cubic-bezier(.36,1.56,.64,1)}  
  @keyframes pop{0%{transform:scale(.4)}100%{transform:scale(1)}}  
  .confetti-wrap{position:absolute;inset:0;overflow:hidden;pointer-events:none}  
  .confetti-piece{position:absolute;width:10px;height:12px;border-radius:3px;animation:fall 1.6s ease-in forwards}  
  @keyframes fall{0%{transform:translateY(-20px) rotate(0deg);opacity:1}100%{transform:translateY(110vh) rotate(720deg);opacity:0}}  
  .palette-wrap{background:var(--panel);border-top:3px solid #ffe0b2;padding:10px 14px 14px;flex-shrink:0}  
  .palette-label{font-family:'Fredoka One',cursive;font-size:.78rem;color:#aaa;margin-bottom:7px;letter-spacing:.5px}  
  .palette{display:flex;gap:8px;overflow-x:auto;scrollbar-width:none;padding-bottom:2px}  
  .palette::-webkit-scrollbar{display:none}  
  .color-swatch{flex-shrink:0;width:46px;height:46px;border-radius:50%;border:4px solid transparent;cursor:pointer;transition:transform .15s,box-shadow .15s;position:relative;box-shadow:0 2px 6px rgba(0,0,0,.18)}  
  .color-swatch.active{border-color:#222;transform:scale(1.22);box-shadow:0 4px 14px rgba(0,0,0,.35)}  
  .color-swatch .swatch-num{position:absolute;bottom:-18px;left:50%;transform:translateX(-50%);font-family:'Fredoka One',cursive;font-size:.72rem;color:#666;white-space:nowrap}  
  .palette-row{display:flex;align-items:flex-end;gap:8px}  
  .eraser-btn{flex-shrink:0;width:46px;height:46px;border-radius:50%;border:4px solid transparent;cursor:pointer;background:#f5f5f5;font-size:1.4rem;display:flex;align-items:center;justify-content:center;box-shadow:0 2px 6px rgba(0,0,0,.14);transition:transform .15s;position:relative}  
  .eraser-btn.active{border-color:#222;transform:scale(1.22)}  
  .eraser-btn .swatch-num{position:absolute;bottom:-18px;left:50%;transform:translateX(-50%);font-family:'Fredoka One',cursive;font-size:.72rem;color:#666}  
  .controls-row{display:flex;justify-content:center;margin-top:14px}  
  .reset-btn{background:linear-gradient(135deg,#ef5350,#e53935);color:#fff;border:none;border-radius:30px;padding:10px 28px;font-family:'Fredoka One',cursive;font-size:1rem;cursor:pointer;box-shadow:0 4px 12px rgba(229,57,53,.35);transition:transform .15s}  
  .reset-btn:active{transform:scale(.95)}  
</style>  
</head>  
<body>  
<header>  
  <h1>🎨 Color Fun!</h1>  
  <div class="star-count" id="starCount">⭐ 0</div>  
</header>  
<div class="scene-bar" id="sceneBar"></div>  
<main>  
  <div class="canvas-wrap">  
    <svg class="drawing" id="drawingSvg" viewBox="0 0 320 260" xmlns="http://www.w3.org/2000/svg"></svg>  
  </div>  
  <div class="celebrate" id="celebrate">  
    <div class="confetti-wrap" id="confettiWrap"></div>  
    <div class="celebrate-text">🎉 Amazing!<br>You did it! ⭐</div>  
  </div>  
  <div class="palette-wrap">  
    <div class="palette-label">TAP A COLOR • THEN TAP THE PICTURE!</div>  
    <div class="palette-row">  
      <div class="palette" id="palette"></div>  
      <div class="eraser-btn active" id="eraserBtn">🩹<span class="swatch-num">Erase</span></div>  
    </div>  
    <div class="controls-row">  
      <button class="reset-btn" id="resetBtn">🔄 Start Over</button>  
    </div>  
  </div>  
</main>  
<script>  
const PALETTE=[  
  {id:1, hex:'#E53935',name:'Red'},  
  {id:2, hex:'#FF8C00',name:'Orange'},  
  {id:3, hex:'#FFD700',name:'Yellow'},  
  {id:4, hex:'#43A047',name:'Green'},  
  {id:5, hex:'#1E88E5',name:'Blue'},  
  {id:6, hex:'#8E24AA',name:'Purple'},  
  {id:7, hex:'#F06292',name:'Pink'},  
  {id:8, hex:'#6D4C41',name:'Brown'},  
  {id:9, hex:'#546E7A',name:'Gray'},  
  {id:10,hex:'#FFFFFF',name:'White'},  
  {id:11,hex:'#FFF9C4',name:'Cream'},  
  {id:12,hex:'#80CBC4',name:'Teal'},  
  {id:13,hex:'#FFCCBC',name:'Peach'},  
  {id:14,hex:'#B3E5FC',name:'LtBlue'},  
  {id:15,hex:'#D32F2F',name:'DkRed'},  
  {id:16,hex:'#1565C0',name:'DkBlue'},  
];  
const SW=2.8;  
  
/* **══════════════════════════════════════════════════════════════════════**  
ALL 10 SCENES  
**══════════════════════════════════════════════════════════════════════** */  
const SCENES=[  
  
// **─────────────────────────────────────────────────────────**  
// 1. HOUSE WITH TREE AND WAGON  
// **─────────────────────────────────────────────────────────**  
{name:‘House’,emoji:‘🏠’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:14, path:‘M0,0 H320 V175 H0 Z’},  
{id:‘grass’,correct:4, cx:160,cy:218,path:‘M0,172 H320 V260 H0 Z’},  
{id:‘path’, correct:11,cx:160,cy:238,path:‘M128,260 Q145,215 142,190 Q150,185 160,185 Q170,185 178,190 Q175,215 192,260 Z’},  
// house walls  
{id:‘wall’, correct:11,cx:155,cy:178,path:‘M68,200 H248 V138 H68 Z’},  
{id:‘door’, correct:8, cx:155,cy:186,path:‘M138,200 H172 V168 Q155,160 138,168 Z’},  
{id:‘knob’, correct:3, cx:168,cy:184,path:‘M165,184 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
// windows  
{id:‘win1’, correct:14,cx:100,cy:168,path:‘M84,158 H116 Q120,158 120,162 V180 Q120,184 116,184 H84 Q80,184 80,180 V162 Q80,158 84,158 Z’},  
{id:‘win1c’,correct:5, cx:100,cy:170,path:‘M82,158 H118 V172 H82 Z’},  
{id:‘win2’, correct:14,cx:212,cy:168,path:‘M196,158 H228 Q232,158 232,162 V180 Q232,184 228,184 H196 Q192,184 192,180 V162 Q192,158 196,158 Z’},  
{id:‘win2c’,correct:5, cx:212,cy:170,path:‘M194,158 H230 V172 H194 Z’},  
// roof  
{id:‘roof’, correct:1, cx:158,cy:125,path:‘M50,140 L158,82 L270,140 Z’},  
{id:‘rfedge’,correct:15,cx:158,cy:140,path:‘M50,140 H270 V144 H50 Z’},  
{id:‘chimney’,correct:9,cx:218,cy:100,path:‘M208,138 H228 V100 H208 Z’},  
{id:‘chimtop’,correct:9,cx:218,cy:97, path:‘M204,100 H232 V96 H204 Z’},  
{id:‘smoke1’,correct:10,cx:218,cy:82, path:‘M210,92 a8,7 0 1,0 16,0 a8,7 0 1,0 -16,0’},  
{id:‘smoke2’,correct:10,cx:224,cy:70, path:‘M218,74 a6,6 0 1,0 12,0 a6,6 0 1,0 -12,0’},  
// big oak tree  
{id:‘trunk’, correct:8, cx:284,cy:196,path:‘M278,210 Q276,185 279,170 Q283,162 288,162 Q293,162 296,170 Q299,185 297,210 Z’},  
{id:‘tfol3’, correct:4, cx:288,cy:168,path:‘M260,174 Q274,146 288,136 Q302,146 316,174 Z’},  
{id:‘tfol2’, correct:4, cx:288,cy:152,path:‘M264,162 Q276,128 288,118 Q300,128 312,162 Z’},  
{id:‘tfol1’, correct:4, cx:288,cy:138,path:‘M270,150 Q280,120 288,112 Q296,120 306,150 Z’},  
{id:‘tapp1’, correct:4, cx:270,cy:162,path:‘M256,168 Q264,148 274,160 Z’},  
{id:‘tapp2’, correct:4, cx:306,cy:162,path:‘M302,160 Q312,148 320,168 Z’},  
// wagon  
{id:‘wbody’,correct:2, cx:52,cy:196, path:‘M18,178 H86 Q90,178 90,182 V204 Q90,208 86,208 H18 Q14,208 14,204 V182 Q14,178 18,178 Z’},  
{id:‘wside’,correct:2, cx:52,cy:185, path:‘M14,182 H90 V190 H14 Z’},  
{id:‘whandle’,correct:9,cx:8,cy:185, path:‘M14,185 Q6,178 2,172 Q4,170 7,170 Q11,174 14,180 Z’},  
{id:‘wplank1’,correct:8,cx:34,cy:196,path:‘M30,190 H34 V208 H30 Z’},  
{id:‘wplank2’,correct:8,cx:52,cy:196,path:‘M50,190 H54 V208 H50 Z’},  
{id:‘wplank3’,correct:8,cx:70,cy:196,path:‘M68,190 H72 V208 H68 Z’},  
{id:‘whl1’, correct:9, cx:28,cy:212, path:‘M18,212 a10,10 0 1,0 20,0 a10,10 0 1,0 -20,0’},  
{id:‘whl1h’,correct:11,cx:28,cy:212, path:‘M24,212 a4,4 0 1,0 8,0 a4,4 0 1,0 -8,0’},  
{id:‘whl2’, correct:9, cx:76,cy:212, path:‘M66,212 a10,10 0 1,0 20,0 a10,10 0 1,0 -20,0’},  
{id:‘whl2h’,correct:11,cx:76,cy:212, path:‘M72,212 a4,4 0 1,0 8,0 a4,4 0 1,0 -8,0’},  
// sun + clouds  
{id:‘sun’,  correct:3, cx:38,cy:36,  path:‘M22,36 a16,16 0 1,0 32,0 a16,16 0 1,0 -32,0’},  
{id:‘sface1’,correct:8,cx:32,cy:32,  path:‘M29,32 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘sface2’,correct:8,cx:44,cy:32,  path:‘M41,32 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘sfacem’,correct:2,cx:38,cy:40,  path:‘M33,39 Q38,45 43,39’},  
{id:‘cl1’,  correct:10,cx:168,cy:36, path:‘M140,48 Q140,34 152,32 Q156,22 168,24 Q176,16 186,22 Q196,18 200,30 Q212,28 210,44 Q210,52 198,52 H150 Q140,52 140,48 Z’},  
{id:‘cl2’,  correct:10,cx:262,cy:54, path:‘M240,64 Q240,52 250,50 Q254,40 264,42 Q272,36 280,42 Q288,40 290,50 Q298,52 296,64 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 2. RAINBOW AND CLOUDS  
// **─────────────────────────────────────────────────────────**  
{name:‘Rainbow’,emoji:‘🌈’,regions:[  
{id:‘sky’,  correct:14,cx:280,cy:16, path:‘M0,0 H320 V260 H0 Z’},  
{id:‘grass’,correct:4, cx:160,cy:238,path:‘M0,215 Q80,200 160,210 Q240,200 320,215 V260 H0 Z’},  
// rainbow arcs (7 colours, back to front so they layer correctly)  
{id:‘arc1’, correct:6, cx:160,cy:115,path:‘M14,175 Q14,62 160,56 Q306,62 306,175 Q290,175 282,166 Q282,90 160,84 Q38,90 38,166 Z’},  
{id:‘arc2’, correct:5, cx:160,cy:118,path:‘M38,175 Q38,76 160,70 Q282,76 282,175 Q266,175 258,166 Q258,100 160,94 Q62,100 62,166 Z’},  
{id:‘arc3’, correct:4, cx:160,cy:122,path:‘M62,175 Q62,88 160,82 Q258,88 258,175 Q244,175 236,166 Q236,108 160,102 Q84,108 84,166 Z’},  
{id:‘arc4’, correct:3, cx:160,cy:126,path:‘M84,175 Q84,100 160,94 Q236,100 236,175 Q222,175 214,166 Q214,118 160,112 Q106,118 106,166 Z’},  
{id:‘arc5’, correct:2, cx:160,cy:130,path:‘M106,175 Q106,112 160,106 Q214,112 214,175 Q200,175 192,166 Q192,128 160,122 Q128,128 128,166 Z’},  
{id:‘arc6’, correct:1, cx:160,cy:134,path:‘M128,175 Q128,122 160,116 Q192,122 192,175 Q178,175 170,166 Q170,138 160,132 Q150,138 150,166 Z’},  
{id:‘arc7’, correct:3, cx:160,cy:138,path:‘M150,175 Q150,134 160,128 Q170,134 170,175 Z’},  
// ground strip + flowers  
{id:‘hill1’,correct:12,cx:80,cy:225, path:‘M0,215 Q80,200 160,210 Q120,230 0,235 Z’},  
{id:‘hill2’,correct:12,cx:240,cy:225,path:‘M160,210 Q240,200 320,215 V235 Q200,232 160,210 Z’},  
// flowers row  
{id:‘fl1p’, correct:7, cx:32,cy:222, path:‘M26,218 Q20,212 26,208 Q32,212 38,208 Q44,212 38,218 Q32,224 26,218 Z’},  
{id:‘fl1c’, correct:3, cx:32,cy:214, path:‘M29,214 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘fl2p’, correct:1, cx:72,cy:220, path:‘M66,216 Q60,210 66,206 Q72,210 78,206 Q84,210 78,216 Q72,222 66,216 Z’},  
{id:‘fl2c’, correct:3, cx:72,cy:212, path:‘M69,212 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘fl3p’, correct:6, cx:240,cy:220,path:‘M234,216 Q228,210 234,206 Q240,210 246,206 Q252,210 246,216 Q240,222 234,216 Z’},  
{id:‘fl3c’, correct:3, cx:240,cy:212,path:‘M237,212 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘fl4p’, correct:3, cx:288,cy:222,path:‘M282,218 Q276,212 282,208 Q288,212 294,208 Q300,212 294,218 Q288,224 282,218 Z’},  
{id:‘fl4c’, correct:2, cx:288,cy:214,path:‘M285,214 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
// big fluffy clouds  
{id:‘cll1’, correct:10,cx:60,cy:58,  path:‘M18,72 Q18,54 30,50 Q32,38 48,40 Q54,28 68,32 Q80,26 88,36 Q100,32 102,46 Q114,48 110,64 Q110,74 96,74 H28 Q18,74 18,72 Z’},  
{id:‘cll2’, correct:10,cx:260,cy:44, path:‘M226,58 Q226,40 238,36 Q240,24 256,26 Q262,14 278,18 Q292,12 300,24 Q312,20 314,36 Q326,38 322,56 Q322,66 308,66 H234 Q226,66 226,58 Z’},  
// little birds  
{id:‘brd1’, correct:9, cx:128,cy:30, path:‘M120,30 Q125,24 130,28 Q135,24 140,30 Q135,32 130,30 Z’},  
{id:‘brd2’, correct:9, cx:180,cy:18, path:‘M172,18 Q177,12 182,16 Q187,12 192,18 Q187,20 182,18 Z’},  
{id:‘brd3’, correct:9, cx:200,cy:40, path:‘M193,40 Q197,35 201,38 Q205,35 209,40 Q205,42 201,40 Z’},  
// pot of gold  
{id:‘pot’,  correct:3, cx:62,cy:188, path:‘M42,172 Q42,162 62,158 Q82,162 82,172 Q86,200 62,204 Q38,200 42,172 Z’},  
{id:‘potbrim’,correct:8,cx:62,cy:162,path:‘M36,162 H88 Q90,158 62,154 Q34,158 36,162 Z’},  
{id:‘coin1’,correct:3, cx:54,cy:178, path:‘M50,178 a5,4 0 1,0 10,0 a5,4 0 1,0 -10,0’},  
{id:‘coin2’,correct:3, cx:68,cy:185, path:‘M64,185 a5,4 0 1,0 10,0 a5,4 0 1,0 -10,0’},  
{id:‘shine1’,correct:11,cx:54,cy:177,path:‘M52,175 a2,2 0 1,0 4,0 a2,2 0 1,0 -4,0’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 3. LAKE WITH DUCKS AND SUNSHINE  
// **─────────────────────────────────────────────────────────**  
{name:‘Lake’,emoji:‘🦆’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:16, path:‘M0,0 H320 V165 H0 Z’},  
{id:‘hill1’,correct:4, cx:60,cy:155, path:‘M0,130 Q60,100 130,130 Q80,165 0,168 Z’},  
{id:‘hill2’,correct:4, cx:260,cy:155,path:‘M190,130 Q250,100 320,130 V168 Q240,165 190,130 Z’},  
{id:‘grass’,correct:4, cx:160,cy:240,path:‘M0,165 H320 V260 H0 Z’},  
// lake  
{id:‘lake’, correct:5, cx:160,cy:192,path:‘M28,210 Q80,165 160,162 Q240,165 292,210 Q260,240 160,244 Q60,240 28,210 Z’},  
{id:‘lakeshine1’,correct:14,cx:100,cy:192,path:‘M80,188 Q95,184 110,190’},  
{id:‘lakeshine2’,correct:14,cx:200,cy:198,path:‘M185,194 Q200,190 215,196’},  
{id:‘lakeshine3’,correct:14,cx:150,cy:210,path:‘M136,207 Q150,203 164,209’},  
// reeds left  
{id:‘reed1s’,correct:4,cx:44,cy:188,  path:‘M42,210 Q41,190 43,174 Q45,170 47,174 Q48,190 47,210 Z’},  
{id:‘reed1t’,correct:8,cx:44,cy:170,  path:‘M40,174 Q44,162 47,170 Q50,162 54,174 Q50,178 44,178 Z’},  
{id:‘reed2s’,correct:4,cx:56,cy:188,  path:‘M54,208 Q53,192 55,178 Q57,174 59,178 Q60,192 59,208 Z’},  
{id:‘reed2t’,correct:8,cx:56,cy:175,  path:‘M52,178 Q56,165 59,175 Q62,165 66,178 Q62,182 56,182 Z’},  
// reeds right  
{id:‘reed3s’,correct:4,cx:268,cy:190, path:‘M266,210 Q265,190 267,176 Q269,172 271,176 Q272,190 271,210 Z’},  
{id:‘reed3t’,correct:8,cx:268,cy:172, path:‘M264,176 Q268,162 271,174 Q274,162 278,176 Q274,180 268,180 Z’},  
{id:‘reed4s’,correct:4,cx:280,cy:188, path:‘M278,208 Q277,190 279,178 Q281,174 283,178 Q284,190 283,208 Z’},  
{id:‘reed4t’,correct:8,cx:280,cy:175, path:‘M276,178 Q280,165 283,176 Q286,165 290,178 Q286,182 280,182 Z’},  
// lily pads  
{id:‘lily1’,correct:4, cx:120,cy:220, path:‘M106,220 Q106,210 120,207 Q134,210 134,220 Q134,228 120,228 Q106,228 106,220 Z’},  
{id:‘lfl1’, correct:7, cx:120,cy:214, path:‘M116,214 Q120,208 124,214’},  
{id:‘lily2’,correct:4, cx:200,cy:228, path:‘M186,228 Q186,218 200,215 Q214,218 214,228 Q214,236 200,236 Q186,236 186,228 Z’},  
{id:‘lfl2’, correct:7, cx:200,cy:222, path:‘M196,222 Q200,216 204,222’},  
// DUCK 1 (left, big)  
{id:‘dbody1’,correct:10,cx:100,cy:198,path:‘M74,202 Q72,192 80,188 Q96,182 114,186 Q122,190 120,200 Q114,212 96,214 Q78,212 74,202 Z’},  
{id:‘dhead1’,correct:10,cx:118,cy:185,path:‘M108,192 Q106,180 116,176 Q128,174 132,182 Q132,190 122,194 Z’},  
{id:‘dbill1’,correct:2, cx:136,cy:183,path:‘M130,182 Q138,178 140,184 Q136,188 130,186 Z’},  
{id:‘deye1’, correct:8, cx:122,cy:181,path:‘M119,181 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘dwing1’,correct:14,cx:94,cy:198, path:‘M80,196 Q90,188 106,196 Q96,204 80,200 Z’},  
{id:‘dtail1’,correct:9, cx:76,cy:196, path:‘M74,194 Q66,190 62,196 Q66,202 74,204 Z’},  
// DUCK 2 (right, smaller, heading other way)  
{id:‘dbody2’,correct:11,cx:216,cy:205,path:‘M192,208 Q190,198 200,194 Q214,188 228,192 Q236,198 232,208 Q226,218 210,220 Q194,218 192,208 Z’},  
{id:‘dhead2’,correct:11,cx:194,cy:197,path:‘M192,204 Q188,192 196,188 Q206,186 210,194 Q210,202 200,206 Z’},  
{id:‘dbill2’,correct:2, cx:186,cy:192,path:‘M192,192 Q184,188 182,194 Q186,198 192,196 Z’},  
{id:‘deye2’, correct:8, cx:196,cy:192,path:‘M193,192 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘dwing2’,correct:14,cx:220,cy:206,path:‘M210,204 Q220,196 234,204 Q226,212 210,210 Z’},  
// sun  
{id:‘sun’,  correct:3, cx:272,cy:42,  path:‘M254,42 a18,18 0 1,0 36,0 a18,18 0 1,0 -36,0’},  
{id:‘sr1’,  correct:3, cx:272,cy:16,  path:‘M269,20 L267,8 L272,4 L277,8 L275,20 Z’},  
{id:‘sr2’,  correct:3, cx:296,cy:22,  path:‘M291,26 L300,16 L305,21 L303,28 L291,30 Z’},  
{id:‘sr3’,  correct:3, cx:305,cy:46,  path:‘M301,43 L316,41 L318,47 L316,53 L301,51 Z’},  
{id:‘sr4’,  correct:3, cx:296,cy:70,  path:‘M291,66 L303,72 L300,80 L295,80 L291,68 Z’},  
{id:‘sr5’,  correct:3, cx:272,cy:78,  path:‘M269,74 L267,88 L272,91 L277,88 L275,74 Z’},  
{id:‘sr6’,  correct:3, cx:248,cy:70,  path:‘M253,66 L241,72 L244,80 L249,80 L253,68 Z’},  
{id:‘sr7’,  correct:3, cx:239,cy:46,  path:‘M243,43 L228,41 L226,47 L228,53 L243,51 Z’},  
{id:‘sr8’,  correct:3, cx:248,cy:22,  path:‘M253,26 L244,16 L239,21 L241,28 L253,30 Z’},  
{id:‘sface1’,correct:8,cx:264,cy:38,  path:‘M261,38 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘sface2’,correct:8,cx:280,cy:38,  path:‘M277,38 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘sfacem’,correct:2,cx:272,cy:46,  path:‘M266,45 Q272,52 278,45’},  
// clouds  
{id:‘cl1’,  correct:10,cx:74,cy:36,   path:‘M42,48 Q42,32 56,30 Q60,20 74,22 Q82,14 92,20 Q102,16 106,28 Q118,26 116,44 Q116,54 102,54 H54 Q42,54 42,48 Z’},  
{id:‘cl2’,  correct:10,cx:166,cy:26,  path:‘M142,36 Q142,24 152,22 Q156,12 166,14 Q174,8 182,14 Q190,10 192,20 Q200,22 198,34 Q198,40 188,40 H150 Q142,40 142,36 Z’},  
// fish in lake  
{id:‘fish’, correct:2, cx:152,cy:232, path:‘M136,232 Q148,226 160,232 Q152,238 136,232 Z’},  
{id:‘ftail’,correct:1, cx:132,cy:232, path:‘M136,228 Q128,224 126,232 Q128,238 136,236 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 4. CUTE PUPPY DOG  
// **─────────────────────────────────────────────────────────**  
{name:‘Puppy’,emoji:‘🐶’,regions:[  
{id:‘bg’,   correct:11,cx:290,cy:15,  path:‘M0,0 H320 V260 H0 Z’},  
{id:‘floor’,correct:12,cx:160,cy:242, path:‘M0,215 H320 V260 H0 Z’},  
{id:‘mat’,  correct:8, cx:160,cy:230, path:‘M60,218 Q160,210 260,218 Q260,248 160,250 Q60,248 60,218 Z’},  
// body  
{id:‘body’, correct:13,cx:160,cy:185, path:‘M64,224 Q60,178 74,152 Q100,124 160,120 Q220,124 246,152 Q260,178 256,224 Z’},  
{id:‘belly’,correct:10,cx:160,cy:196, path:‘M108,196 Q160,175 212,196 Q208,225 160,232 Q112,225 108,196 Z’},  
// tail  
{id:‘tail’, correct:13,cx:268,cy:186, path:‘M254,214 Q292,196 296,162 Q298,138 280,134 Q264,132 266,155 Q268,175 252,196 Z’},  
{id:‘tailtp’,correct:10,cx:280,cy:132,path:‘M272,134 a10,10 0 1,0 20,0 a10,10 0 1,0 -20,0’},  
// hind legs  
{id:‘hlegL’,correct:13,cx:90,cy:234,  path:‘M76,215 Q70,228 74,243 Q84,252 96,248 Q106,240 102,226 Q96,215 76,215 Z’},  
{id:‘hlegR’,correct:13,cx:230,cy:234, path:‘M244,215 Q250,228 246,243 Q236,252 224,248 Q214,240 218,226 Q224,215 244,215 Z’},  
// front paws  
{id:‘pawFL’,correct:13,cx:108,cy:232, path:‘M96,218 Q90,230 94,244 Q104,252 116,248 Q124,238 118,224 Q112,218 96,218 Z’},  
{id:‘pawFR’,correct:13,cx:212,cy:232, path:‘M224,218 Q230,230 226,244 Q216,252 204,248 Q196,238 202,224 Q208,218 224,218 Z’},  
// neck + head  
{id:‘neck’, correct:13,cx:160,cy:124, path:‘M140,120 Q132,104 140,90 Q160,80 180,90 Q188,104 180,120 Z’},  
{id:‘head’, correct:13,cx:160,cy:68,  path:‘M96,86 Q92,44 160,34 Q228,44 224,86 Q214,108 160,114 Q106,108 96,86 Z’},  
// big floppy ears  
{id:‘earL’, correct:8, cx:94,cy:72,   path:‘M100,92 Q80,80 68,58 Q62,40 72,32 Q86,26 96,38 Q108,56 108,82 Z’},  
{id:‘earLi’,correct:13,cx:90,cy:66,   path:‘M102,88 Q84,76 74,56 Q70,44 76,38 Q88,34 96,46 Q106,62 106,82 Z’},  
{id:‘earR’, correct:8, cx:226,cy:72,  path:‘M220,92 Q240,80 252,58 Q258,40 248,32 Q234,26 224,38 Q212,56 212,82 Z’},  
{id:‘earRi’,correct:13,cx:230,cy:66,  path:‘M218,88 Q236,76 246,56 Q250,44 244,38 Q232,34 224,46 Q214,62 214,82 Z’},  
// eyebrow patches  
{id:‘brow1’,correct:8, cx:132,cy:58,  path:‘M118,54 Q130,46 142,56 Q138,62 126,62 Q114,60 118,54 Z’},  
{id:‘brow2’,correct:8, cx:188,cy:58,  path:‘M178,54 Q190,46 202,56 Q206,60 194,62 Q182,62 178,54 Z’},  
// eyes  
{id:‘eyeL’, correct:10,cx:132,cy:72,  path:‘M116,72 a16,13 0 1,0 32,0 a16,13 0 1,0 -32,0’},  
{id:‘eyeR’, correct:10,cx:188,cy:72,  path:‘M172,72 a16,13 0 1,0 32,0 a16,13 0 1,0 -32,0’},  
{id:‘pupL’, correct:16,cx:132,cy:74,  path:‘M121,74 a11,11 0 1,0 22,0 a11,11 0 1,0 -22,0’},  
{id:‘pupR’, correct:16,cx:188,cy:74,  path:‘M177,74 a11,11 0 1,0 22,0 a11,11 0 1,0 -22,0’},  
{id:‘hlL’,  correct:10,cx:127,cy:69,  path:‘M124,69 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘hlR’,  correct:10,cx:183,cy:69,  path:‘M180,69 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
// snout + nose  
{id:‘snout’,correct:11,cx:160,cy:92,  path:‘M132,88 Q132,76 160,72 Q188,76 188,88 Q186,100 160,104 Q134,100 132,88 Z’},  
{id:‘nose’, correct:8, cx:160,cy:82,  path:‘M148,80 Q148,74 160,72 Q172,74 172,80 Q168,86 160,86 Q152,86 148,80 Z’},  
{id:‘nleft’,correct:9, cx:152,cy:83,  path:‘M150,80 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘nright’,correct:9,cx:168,cy:83,  path:‘M166,80 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘mthL’, correct:8, cx:148,cy:98,  path:‘M160,96 Q150,106 140,104’},  
{id:‘mthR’, correct:8, cx:172,cy:98,  path:‘M160,96 Q170,106 180,104’},  
// tongue  
{id:‘tongue’,correct:1,cx:160,cy:104, path:‘M148,100 Q148,112 160,116 Q172,112 172,100 Z’},  
// blush  
{id:‘blshL’,correct:7, cx:110,cy:96,  path:‘M99,96 a12,8 0 1,0 24,0 a12,8 0 1,0 -24,0’},  
{id:‘blshR’,correct:7, cx:210,cy:96,  path:‘M199,96 a12,8 0 1,0 24,0 a12,8 0 1,0 -24,0’},  
// collar + bone tag  
{id:‘collar’,correct:1,cx:160,cy:120, path:‘M128,112 Q160,124 192,112 Q192,122 160,128 Q128,122 128,112 Z’},  
{id:‘bone’, correct:10,cx:160,cy:126, path:‘M152,122 Q150,126 154,128 Q158,130 160,128 Q162,130 166,128 Q170,126 168,122 Q164,120 160,122 Q156,120 152,122 Z’},  
// spots on body  
{id:‘spot1’,correct:8, cx:126,cy:160, path:‘M116,158 Q118,150 128,152 Q134,158 128,166 Q118,166 116,158 Z’},  
{id:‘spot2’,correct:8, cx:196,cy:152, path:‘M188,150 Q192,142 200,146 Q204,154 198,162 Q190,160 188,150 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 5. OCEAN SCENE  
// **─────────────────────────────────────────────────────────**  
{name:‘Ocean’,emoji:‘🌊’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:20,  path:‘M0,0 H320 V140 H0 Z’},  
// ocean layers  
{id:‘sea3’, correct:16,cx:160,cy:168, path:‘M0,148 Q80,135 160,142 Q240,135 320,148 V200 Q240,188 160,195 Q80,188 0,200 Z’},  
{id:‘sea2’, correct:5, cx:160,cy:200, path:‘M0,195 Q80,182 160,190 Q240,182 320,195 V230 Q240,218 160,225 Q80,218 0,230 Z’},  
{id:‘sea1’, correct:12,cx:160,cy:232, path:‘M0,225 Q80,212 160,220 Q240,212 320,225 V260 H0 Z’},  
// wave crests  
{id:‘wv1’,  correct:10,cx:70,cy:142,  path:‘M14,148 Q30,136 50,142 Q70,148 90,142 Q70,152 50,150 Q30,152 14,148 Z’},  
{id:‘wv2’,  correct:10,cx:200,cy:138, path:‘M160,142 Q180,130 200,136 Q220,142 240,136 Q220,148 200,146 Q180,148 160,142 Z’},  
{id:‘wv3’,  correct:10,cx:80,cy:198,  path:‘M40,202 Q60,190 80,196 Q100,202 120,196 Q100,208 80,206 Q60,208 40,202 Z’},  
{id:‘wv4’,  correct:10,cx:230,cy:224, path:‘M200,228 Q220,216 240,222 Q260,228 280,222 Q260,234 240,232 Q220,234 200,228 Z’},  
// sun + rays  
{id:‘sun’,  correct:3, cx:54,cy:48,   path:‘M32,48 a22,22 0 1,0 44,0 a22,22 0 1,0 -44,0’},  
{id:‘sr1’,  correct:2, cx:54,cy:16,   path:‘M51,20 L49,7 L54,4 L59,7 L57,20 Z’},  
{id:‘sr2’,  correct:2, cx:80,cy:23,   path:‘M75,27 L84,17 L89,22 L87,29 L75,31 Z’},  
{id:‘sr3’,  correct:2, cx:89,cy:48,   path:‘M85,45 L99,43 L101,48 L99,53 L85,51 Z’},  
{id:‘sr4’,  correct:2, cx:80,cy:73,   path:‘M75,69 L87,75 L84,83 L79,83 L75,71 Z’},  
{id:‘sr5’,  correct:2, cx:54,cy:82,   path:‘M51,76 L49,91 L54,94 L59,91 L57,76 Z’},  
{id:‘sr6’,  correct:2, cx:28,cy:73,   path:‘M33,69 L21,75 L24,83 L29,83 L33,71 Z’},  
{id:‘sr7’,  correct:2, cx:19,cy:48,   path:‘M23,45 L9,43 L7,48 L9,53 L23,51 Z’},  
{id:‘sr8’,  correct:2, cx:28,cy:23,   path:‘M33,27 L24,17 L19,22 L21,29 L33,31 Z’},  
{id:‘sface1’,correct:8,cx:47,cy:44,   path:‘M44,44 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘sface2’,correct:8,cx:61,cy:44,   path:‘M58,44 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘sfacem’,correct:2,cx:54,cy:52,   path:‘M48,51 Q54,58 60,51’},  
// clouds  
{id:‘cl1’,  correct:10,cx:174,cy:34,  path:‘M146,46 Q146,30 158,28 Q162,16 176,18 Q184,10 194,16 Q204,12 208,24 Q220,22 218,40 Q218,50 204,50 H156 Q146,50 146,46 Z’},  
{id:‘cl2’,  correct:10,cx:280,cy:60,  path:‘M256,70 Q256,56 266,54 Q270,44 280,46 Q288,38 296,46 Q304,42 306,54 Q316,56 314,70 Z’},  
// sailboat  
{id:‘hull’, correct:1, cx:230,cy:148, path:‘M192,144 H268 Q272,144 274,150 Q268,158 230,160 Q192,158 186,150 Q188,144 192,144 Z’},  
{id:‘mast’, correct:9, cx:230,cy:120, path:‘M228,144 H232 V90 H228 Z’},  
{id:‘sail1’,correct:10,cx:218,cy:116, path:‘M228,144 Q210,128 212,96 Q220,100 228,120 Z’},  
{id:‘sail2’,correct:14,cx:242,cy:116, path:‘M232,144 Q250,128 248,96 Q240,100 232,120 Z’},  
{id:‘flag’, correct:1, cx:238,cy:89,  path:‘M232,90 L244,86 L240,94 Z’},  
{id:‘window’,correct:5,cx:230,cy:152, path:‘M224,148 H236 Q238,148 238,150 V156 H224 Z’},  
// FISH under water (shown via slight transparency effect — use lighter blues)  
{id:‘fish1b’,correct:2, cx:110,cy:215,path:‘M90,215 Q106,208 122,215 Q110,224 90,218 Z’},  
{id:‘fish1f’,correct:1, cx:86,cy:216, path:‘M90,211 Q80,206 76,215 Q80,222 90,220 Z’},  
{id:‘fish2b’,correct:3, cx:200,cy:205,path:‘M184,205 Q198,198 212,205 Q200,214 184,208 Z’},  
{id:‘fish2f’,correct:2, cx:216,cy:206,path:‘M212,201 Q222,196 226,205 Q222,212 212,210 Z’},  
// seagulls  
{id:‘gull1’,correct:9, cx:120,cy:86,  path:‘M110,86 Q116,80 122,84 Q128,80 134,86 Q128,88 122,86 Z’},  
{id:‘gull2’,correct:9, cx:156,cy:72,  path:‘M147,72 Q152,66 157,70 Q162,66 167,72 Q162,74 157,72 Z’},  
{id:‘gull3’,correct:9, cx:246,cy:92,  path:‘M238,92 Q243,86 248,90 Q253,86 258,92 Q253,94 248,92 Z’},  
// lighthouse  
{id:‘ltbase’,correct:9,cx:298,cy:148, path:‘M284,158 H310 Q314,158 314,150 V130 H282 V150 Q282,158 284,158 Z’},  
{id:‘ltstripe1’,correct:1,cx:298,cy:138,path:‘M282,134 H314 V142 H282 Z’},  
{id:‘lttop’,correct:9, cx:298,cy:126, path:‘M284,130 H312 Q312,122 298,116 Q284,122 284,130 Z’},  
{id:‘ltlight’,correct:3,cx:298,cy:114,path:‘M290,116 a8,8 0 1,0 16,0 a8,8 0 1,0 -16,0’},  
{id:‘ltdoor’,correct:8,cx:298,cy:152, path:‘M293,158 H303 V146 Q298,142 293,146 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 6. FARM SCENE  
// **─────────────────────────────────────────────────────────**  
{name:‘Farm’,emoji:‘🚜’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:18,  path:‘M0,0 H320 V165 H0 Z’},  
{id:‘field’,correct:4, cx:160,cy:215, path:‘M0,160 H320 V260 H0 Z’},  
{id:‘dirt’, correct:8, cx:160,cy:240, path:‘M0,225 H320 V260 H0 Z’},  
// furrow rows  
{id:‘row1’, correct:8, cx:160,cy:230, path:‘M0,226 Q80,222 160,226 Q240,222 320,226 V230 Q240,226 160,230 Q80,226 0,230 Z’},  
{id:‘row2’, correct:8, cx:160,cy:240, path:‘M0,236 Q80,232 160,236 Q240,232 320,236 V240 Q240,236 160,240 Q80,236 0,240 Z’},  
{id:‘row3’, correct:8, cx:160,cy:250, path:‘M0,246 Q80,242 160,246 Q240,242 320,246 V250 Q240,246 160,250 Q80,246 0,250 Z’},  
// BARN  
{id:‘bwall’,correct:1, cx:96,cy:175,  path:‘M30,208 H162 V148 H30 Z’},  
{id:‘bdoor’,correct:8, cx:96,cy:192,  path:‘M76,208 H116 V175 H76 Z’},  
{id:‘bdlatch’,correct:3,cx:115,cy:190,path:‘M113,188 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘bwin’, correct:14,cx:46,cy:168,  path:‘M36,162 H58 Q62,162 62,167 V182 Q62,186 58,186 H36 Q32,186 32,182 V167 Q32,162 36,162 Z’},  
{id:‘bwinc’,correct:5, cx:46,cy:172,  path:‘M34,162 H60 V175 H34 Z’},  
{id:‘bwin2’,correct:14,cx:146,cy:168, path:‘M136,162 H158 Q162,162 162,167 V182 Q162,186 158,186 H136 Q132,186 132,182 V167 Q132,162 136,162 Z’},  
{id:‘bwin2c’,correct:5,cx:146,cy:172, path:‘M134,162 H160 V175 H134 Z’},  
{id:‘broof’,correct:15,cx:96,cy:132,  path:‘M14,150 L96,100 L178,150 Z’},  
{id:‘broke’,correct:9, cx:96,cy:150,  path:‘M14,150 H178 V155 H14 Z’},  
// silo  
{id:‘silo’, correct:9, cx:152,cy:132, path:‘M138,208 H166 V124 H138 Z’},  
{id:‘silot’,correct:9, cx:152,cy:118, path:‘M136,124 Q136,108 152,104 Q168,108 168,124 Z’},  
{id:‘silow1’,correct:14,cx:152,cy:148,path:‘M138,144 H166 V154 H138 Z’},  
{id:‘silow2’,correct:14,cx:152,cy:164,path:‘M138,160 H166 V170 H138 Z’},  
// fence  
{id:‘fn1’,  correct:10,cx:200,cy:192, path:‘M185,174 H191 V210 H185 Z’},  
{id:‘fn2’,  correct:10,cx:220,cy:192, path:‘M215,174 H221 V210 H215 Z’},  
{id:‘fn3’,  correct:10,cx:240,cy:192, path:‘M245,174 H251 V210 H245 Z’},  
{id:‘fn4’,  correct:10,cx:260,cy:192, path:‘M275,174 H281 V210 H275 Z’},  
{id:‘fnr1’, correct:10,cx:232,cy:184, path:‘M185,180 H282 V186 H185 Z’},  
{id:‘fnr2’, correct:10,cx:232,cy:198, path:‘M185,194 H282 V200 H185 Z’},  
// TRACTOR  
{id:‘tbody’,correct:4, cx:240,cy:218, path:‘M200,204 H272 Q280,204 282,212 V228 Q282,236 272,236 H200 Q192,236 192,228 V212 Q192,204 200,204 Z’},  
{id:‘tcab’, correct:4, cx:256,cy:200, path:‘M238,204 H276 Q282,204 282,196 V186 Q282,180 276,180 H252 Q242,180 238,188 Z’},  
{id:‘twin’, correct:14,cx:264,cy:192, path:‘M254,202 H276 Q280,202 280,198 V188 Q280,184 276,184 H254 Z’},  
{id:‘texhst’,correct:9,cx:240,cy:176, path:‘M238,180 H244 V170 H240 Q238,170 238,180 Z’},  
{id:‘tsmoke’,correct:9,cx:242,cy:164, path:‘M236,170 a6,5 0 1,0 12,0 a6,5 0 1,0 -12,0’},  
{id:‘twh1’, correct:9, cx:212,cy:234, path:‘M194,234 a18,18 0 1,0 36,0 a18,18 0 1,0 -36,0’},  
{id:‘twh1r’,correct:8, cx:212,cy:234, path:‘M204,234 a8,8 0 1,0 16,0 a8,8 0 1,0 -16,0’},  
{id:‘twh1c’,correct:3, cx:212,cy:234, path:‘M209,234 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘twh2’, correct:9, cx:262,cy:234, path:‘M249,234 a13,13 0 1,0 26,0 a13,13 0 1,0 -26,0’},  
{id:‘twh2r’,correct:8, cx:262,cy:234, path:‘M257,234 a5,5 0 1,0 10,0 a5,5 0 1,0 -10,0’},  
// COW in field  
{id:‘cbody’,correct:10,cx:296,cy:182, path:‘M276,196 Q272,178 280,168 Q294,158 310,164 Q322,172 318,188 Q314,202 296,206 Q278,202 276,196 Z’},  
{id:‘cspot1’,correct:8,cx:298,cy:176, path:‘M290,172 Q294,164 304,168 Q308,174 302,180 Q294,180 290,172 Z’},  
{id:‘chead’,correct:10,cx:314,cy:164, path:‘M308,170 Q306,158 314,154 Q322,152 326,160 Q328,170 318,172 Z’},  
{id:‘csnout’,correct:13,cx:320,cy:168,path:‘M314,164 Q314,170 320,172 Q326,170 326,164 Z’},  
{id:‘ceye’, correct:8, cx:316,cy:159, path:‘M313,159 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘cear’, correct:10,cx:308,cy:153, path:‘M306,158 L302,148 L314,154 Z’},  
{id:‘cleg1’,correct:10,cx:284,cy:205, path:‘M280,200 Q278,208 280,216 Q284,220 288,218 Q290,210 290,202 Z’},  
{id:‘cleg2’,correct:10,cx:302,cy:208, path:‘M298,204 Q296,212 298,220 Q302,224 306,222 Q308,214 308,206 Z’},  
{id:‘ctail’,correct:8, cx:276,cy:182, path:‘M276,192 Q266,188 264,178 Q266,172 270,178 Q272,186 276,192 Z’},  
// sun + clouds  
{id:‘sun’,  correct:3, cx:36,cy:36,   path:‘M18,36 a18,18 0 1,0 36,0 a18,18 0 1,0 -36,0’},  
{id:‘srf1’, correct:2, cx:36,cy:10,   path:‘M33,14 L31,4 L36,1 L41,4 L39,14 Z’},  
{id:‘srf2’, correct:2, cx:58,cy:17,   path:‘M53,22 L62,12 L67,17 L65,24 L53,26 Z’},  
{id:‘srf3’, correct:2, cx:64,cy:36,   path:‘M60,33 L74,31 L76,36 L74,41 L60,39 Z’},  
{id:‘srf4’, correct:2, cx:58,cy:55,   path:‘M53,50 L65,56 L62,64 L57,64 L53,52 Z’},  
{id:‘srf5’, correct:2, cx:36,cy:62,   path:‘M33,56 L31,70 L36,73 L41,70 L39,56 Z’},  
{id:‘srf6’, correct:2, cx:14,cy:55,   path:‘M19,50 L7,56 L10,64 L15,64 L19,52 Z’},  
{id:‘srf7’, correct:2, cx:8, cy:36,   path:‘M12,33 L-2,31 L-4,36 L-2,41 L12,39 Z’},  
{id:‘srf8’, correct:2, cx:14,cy:17,   path:‘M19,22 L10,12 L5,17 L7,24 L19,26 Z’},  
{id:‘cl1’,  correct:10,cx:160,cy:30,  path:‘M132,42 Q132,26 144,24 Q148,12 162,14 Q170,6 180,12 Q192,8 196,22 Q208,20 206,38 Q206,48 192,48 H144 Q132,48 132,42 Z’},  
{id:‘cl2’,  correct:10,cx:258,cy:40,  path:‘M234,52 Q234,38 244,36 Q248,24 260,26 Q268,18 276,26 Q284,22 286,34 Q296,36 294,52 Z’},  
// crops  
{id:‘crop1’,correct:4, cx:190,cy:218, path:‘M186,214 Q188,206 190,200 Q192,206 194,214 Z’},  
{id:‘crop2’,correct:4, cx:200,cy:218, path:‘M196,214 Q198,206 200,200 Q202,206 204,214 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 7. AIRPLANE  
// **─────────────────────────────────────────────────────────**  
{name:‘Airplane’,emoji:‘✈️’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:130, path:‘M0,0 H320 V260 H0 Z’},  
// clouds background  
{id:‘cl1’,  correct:10,cx:52,cy:48,   path:‘M18,62 Q18,44 32,42 Q36,28 52,32 Q60,20 72,26 Q84,22 88,36 Q102,32 100,52 Q100,64 84,64 H32 Q18,64 18,62 Z’},  
{id:‘cl2’,  correct:10,cx:252,cy:70,  path:‘M218,82 Q218,64 232,62 Q236,48 252,52 Q260,40 272,46 Q284,42 288,56 Q302,52 300,72 Q300,84 284,84 H232 Q218,84 218,82 Z’},  
{id:‘cl3’,  correct:10,cx:144,cy:196, path:‘M106,210 Q106,192 120,190 Q124,176 140,180 Q148,168 162,176 Q176,168 184,180 Q196,176 200,190 Q214,192 210,212 Q210,222 194,222 H118 Q106,222 106,210 Z’},  
{id:‘cl4’,  correct:10,cx:42,cy:188,  path:‘M14,198 Q14,184 24,182 Q28,170 42,174 Q50,164 60,172 Q68,164 76,172 Q84,168 88,182 Q100,184 96,202 Q96,212 80,212 H24 Q14,212 14,198 Z’},  
// AIRPLANE BODY  
{id:‘fuselage’,correct:10,cx:164,cy:128,path:‘M40,128 Q40,116 50,112 H230 Q248,112 260,124 Q270,134 268,144 Q258,154 240,152 H50 Q40,144 40,128 Z’},  
{id:‘nose’, correct:14,cx:272,cy:130, path:‘M260,124 Q278,118 292,128 Q292,136 276,140 Q262,142 260,138 Z’},  
{id:‘tailbody’,correct:9,cx:42,cy:128,path:‘M40,116 H52 V144 H40 Z’},  
// windows row  
{id:‘win1’, correct:14,cx:100,cy:126, path:‘M90,120 H112 Q116,120 116,124 V134 Q116,138 112,138 H90 Q86,138 86,134 V124 Q86,120 90,120 Z’},  
{id:‘win2’, correct:14,cx:134,cy:126, path:‘M124,120 H146 Q150,120 150,124 V134 Q150,138 146,138 H124 Q120,138 120,134 V124 Q120,120 124,120 Z’},  
{id:‘win3’, correct:14,cx:168,cy:126, path:‘M158,120 H180 Q184,120 184,124 V134 Q184,138 180,138 H158 Q154,138 154,134 V124 Q154,120 158,120 Z’},  
{id:‘win4’, correct:14,cx:202,cy:126, path:‘M192,120 H214 Q218,120 218,124 V134 Q218,138 214,138 H192 Q188,138 188,134 V124 Q188,120 192,120 Z’},  
{id:‘win5’, correct:14,cx:236,cy:126, path:‘M226,120 H244 Q248,120 248,124 V134 Q248,138 244,138 H226 Q222,138 222,134 V124 Q222,120 226,120 Z’},  
// cockpit window  
{id:‘cockpit’,correct:5,cx:268,cy:128,path:‘M262,122 Q274,116 286,126 Q288,132 278,138 Q264,140 260,136 Z’},  
// main wings  
{id:‘wingR’,correct:5, cx:164,cy:170, path:‘M90,152 Q130,152 180,152 Q200,180 210,210 Q190,214 175,210 Q152,185 130,170 Q110,175 90,172 Z’},  
{id:‘wingL’,correct:5, cx:164,cy:92,  path:‘M90,112 Q110,110 130,98 Q152,80 175,56 Q190,52 210,56 Q200,88 180,112 Q130,112 90,112 Z’},  
{id:‘wingR_stripe’,correct:16,cx:178,cy:188,path:‘M165,165 Q180,180 192,204 Q188,208 184,206 Q172,184 162,168 Z’},  
{id:‘wingL_stripe’,correct:16,cx:178,cy:78, path:‘M162,98 Q172,82 184,60 Q188,58 192,62 Q180,86 165,104 Z’},  
// tail fin (vertical)  
{id:‘vtail’,correct:5, cx:46,cy:102,  path:‘M40,112 Q40,90 50,78 Q62,70 72,78 Q72,96 60,112 Z’},  
{id:‘vtailstr’,correct:16,cx:56,cy:96,path:‘M44,108 Q48,90 56,80 Q62,80 58,92 Q52,104 46,108 Z’},  
// horizontal tail fins  
{id:‘htailR’,correct:5,cx:46,cy:152,  path:‘M40,144 Q48,144 72,152 Q80,164 68,170 Q56,170 44,162 Z’},  
{id:‘htailL’,correct:5,cx:46,cy:112,  path:‘M40,120 Q48,118 64,114 Q76,110 76,120 Q68,130 44,132 Z’},  
// airline stripe  
{id:‘stripe1’,correct:1,cx:154,cy:152,path:‘M50,148 H260 V154 H50 Z’},  
{id:‘stripe2’,correct:1,cx:154,cy:112,path:‘M50,110 H240 V116 H50 Z’},  
// engine pods  
{id:‘eng1’, correct:9, cx:144,cy:168, path:‘M116,162 H172 Q180,162 182,168 Q182,176 174,178 H114 Q108,176 108,170 Q108,162 116,162 Z’},  
{id:‘eng1n’,correct:9, cx:184,cy:170, path:‘M180,166 H188 Q194,166 194,170 Q194,174 188,174 H180 Z’},  
{id:‘eng2’, correct:9, cx:144,cy:98,  path:‘M116,92 H172 Q180,92 182,98 Q182,106 174,108 H114 Q108,106 108,100 Q108,92 116,92 Z’},  
{id:‘eng2n’,correct:9, cx:184,cy:100, path:‘M180,96 H188 Q194,96 194,100 Q194,104 188,104 H180 Z’},  
// contrail  
{id:‘trail1’,correct:10,cx:18,cy:122, path:‘M4,120 Q14,118 24,122 Q14,126 4,124 Z’},  
{id:‘trail2’,correct:10,cx:10,cy:132, path:‘M0,130 Q10,128 20,132 Q10,136 0,134 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 8. BEACH SCENE  
// **─────────────────────────────────────────────────────────**  
{name:‘Beach’,emoji:‘🏖️’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:28,  path:‘M0,0 H320 V140 H0 Z’},  
{id:‘sea’,  correct:5, cx:160,cy:152, path:‘M0,130 H320 V185 H0 Z’},  
{id:‘seahorizon’,correct:12,cx:160,cy:132,path:‘M0,128 Q80,118 160,124 Q240,118 320,128 V136 Q240,126 160,132 Q80,126 0,136 Z’},  
{id:‘sand’, correct:3, cx:160,cy:218, path:‘M0,182 Q80,170 160,176 Q240,170 320,182 V260 H0 Z’},  
{id:‘sandwave’,correct:11,cx:160,cy:184,path:‘M0,180 Q80,168 160,174 Q240,168 320,180 V186 Q240,174 160,180 Q80,174 0,186 Z’},  
// sun  
{id:‘sun’,  correct:3, cx:270,cy:48,  path:‘M252,48 a18,18 0 1,0 36,0 a18,18 0 1,0 -36,0’},  
{id:‘sr1’,  correct:2, cx:270,cy:20,  path:‘M267,24 L265,10 L270,7 L275,10 L273,24 Z’},  
{id:‘sr2’,  correct:2, cx:296,cy:27,  path:‘M291,31 L302,20 L307,25 L305,32 L291,34 Z’},  
{id:‘sr3’,  correct:2, cx:304,cy:52,  path:‘M300,49 L316,47 L318,52 L316,57 L300,55 Z’},  
{id:‘sr4’,  correct:2, cx:296,cy:76,  path:‘M291,72 L305,78 L302,86 L297,86 L291,74 Z’},  
{id:‘sr5’,  correct:2, cx:270,cy:82,  path:‘M267,76 L265,92 L270,95 L275,92 L273,76 Z’},  
{id:‘sr6’,  correct:2, cx:244,cy:76,  path:‘M249,72 L237,78 L240,86 L245,86 L249,74 Z’},  
{id:‘sr7’,  correct:2, cx:236,cy:52,  path:‘M240,49 L224,47 L222,52 L224,57 L240,55 Z’},  
{id:‘sr8’,  correct:2, cx:244,cy:27,  path:‘M249,31 L238,20 L233,25 L235,32 L249,34 Z’},  
// clouds  
{id:‘cl1’,  correct:10,cx:78,cy:36,   path:‘M44,50 Q44,32 58,30 Q62,18 78,22 Q86,12 98,18 Q110,14 114,28 Q128,24 126,46 Q126,58 110,58 H58 Q44,58 44,50 Z’},  
{id:‘cl2’,  correct:10,cx:168,cy:24,  path:‘M140,34 Q140,20 152,18 Q156,6 168,10 Q176,2 186,8 Q196,4 200,16 Q212,14 210,30 Q210,40 194,40 H152 Q140,40 140,34 Z’},  
// BEACH UMBRELLA  
{id:‘upole’,correct:8, cx:116,cy:196, path:‘M113,178 H119 V240 H113 Z’},  
{id:‘ucone’,correct:1, cx:116,cy:165, path:‘M68,180 Q92,148 116,140 Q140,148 164,180 Z’},  
{id:‘ustripe1’,correct:10,cx:90,cy:162,path:‘M76,176 Q88,154 98,148 Q100,154 90,170 Z’},  
{id:‘ustripe2’,correct:10,cx:134,cy:162,path:‘M132,148 Q142,154 156,176 Q148,172 138,156 Z’},  
{id:‘ucap’, correct:9, cx:116,cy:138, path:‘M110,140 a6,6 0 1,0 12,0 a6,6 0 1,0 -12,0’},  
// BEACH TOWEL  
{id:‘towel’,correct:1, cx:96,cy:218,  path:‘M46,208 H146 Q150,208 150,214 V228 Q150,232 146,232 H46 Q42,232 42,228 V214 Q42,208 46,208 Z’},  
{id:‘towstr1’,correct:10,cx:72,cy:220,path:‘M64,208 H74 V232 H64 Z’},  
{id:‘towstr2’,correct:10,cx:96,cy:220,path:‘M90,208 H100 V232 H90 Z’},  
{id:‘towstr3’,correct:10,cx:122,cy:220,path:‘M116,208 H126 V232 H116 Z’},  
// SANDCASTLE  
{id:‘scast_base’,correct:3,cx:226,cy:212,path:‘M190,224 H262 Q266,224 266,218 V206 Q266,200 262,200 H190 Q186,200 186,206 V218 Q186,224 190,224 Z’},  
{id:‘scast_t1’,correct:3,cx:202,cy:196,path:‘M192,200 H214 V190 H192 Z’},  
{id:‘scast_t2’,correct:3,cx:226,cy:192,path:‘M216,200 H236 V184 H216 Z’},  
{id:‘scast_t3’,correct:3,cx:250,cy:196,path:‘M238,200 H260 V190 H238 Z’},  
{id:‘scast_flag’,correct:1,cx:226,cy:179,path:‘M224,184 L236,178 L232,188 Z’},  
{id:‘scast_win1’,correct:14,cx:204,cy:212,path:‘M198,206 H210 Q212,206 212,210 V218 H198 Z’},  
{id:‘scast_win2’,correct:14,cx:248,cy:212,path:‘M242,206 H254 Q256,206 256,210 V218 H242 Z’},  
{id:‘scast_door’,correct:8,cx:226,cy:214,path:‘M220,224 H232 V212 Q226,208 220,212 Z’},  
// BALL  
{id:‘ball’, correct:1, cx:172,cy:210, path:‘M156,210 a16,16 0 1,0 32,0 a16,16 0 1,0 -32,0’},  
{id:‘ball_s1’,correct:10,cx:172,cy:210,path:‘M162,202 Q172,196 182,202 Q178,212 172,214 Q166,212 162,202 Z’},  
{id:‘ball_s2’,correct:3,cx:172,cy:218,path:‘M162,214 Q166,220 172,222 Q178,220 182,214 Q178,208 172,210 Q166,208 162,214 Z’},  
// seagulls  
{id:‘gull1’,correct:9, cx:48,cy:108,  path:‘M40,108 Q45,102 50,106 Q55,102 60,108 Q55,110 50,108 Z’},  
{id:‘gull2’,correct:9, cx:96,cy:92,   path:‘M88,92 Q93,86 98,90 Q103,86 108,92 Q103,94 98,92 Z’},  
{id:‘gull3’,correct:9, cx:200,cy:108, path:‘M192,108 Q197,102 202,106 Q207,102 212,108 Q207,110 202,108 Z’},  
// starfish  
{id:‘star’, correct:1, cx:62,cy:200,  path:‘M62,192 L64,198 L70,198 L65,202 L67,208 L62,204 L57,208 L59,202 L54,198 L60,198 Z’},  
// shell  
{id:‘shell’,correct:2, cx:148,cy:238, path:‘M140,240 Q140,230 148,226 Q156,230 156,240 Z’},  
{id:‘shellr’,correct:13,cx:148,cy:234,path:‘M142,234 Q145,228 148,230 Q151,228 154,234 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 9. RACE CAR  
// **─────────────────────────────────────────────────────────**  
{name:‘Race Car’,emoji:‘🏎️’,regions:[  
{id:‘bg’,   correct:9, cx:270,cy:130, path:‘M0,0 H320 V260 H0 Z’},  
// track  
{id:‘track’,correct:8, cx:160,cy:210, path:‘M0,185 H320 V260 H0 Z’},  
{id:‘trk_stripe’,correct:10,cx:160,cy:216,path:‘M0,212 H320 V220 H0 Z’},  
{id:‘trk_dashes’,correct:3,cx:160,cy:210, path:‘M20,206 H60 V214 H20 Z’},  
{id:‘trk_dashes2’,correct:3,cx:130,cy:210,path:‘M110,206 H150 V214 H110 Z’},  
{id:‘trk_dashes3’,correct:3,cx:220,cy:210,path:‘M200,206 H240 V214 H200 Z’},  
{id:‘trk_dashes4’,correct:3,cx:290,cy:210,path:‘M270,206 H310 V214 H270 Z’},  
// crowd stands  
{id:‘stand’,correct:12,cx:160,cy:78,  path:‘M0,30 H320 V150 H0 Z’},  
{id:‘rows1’,correct:9, cx:160,cy:50,  path:‘M0,30 H320 V60 H0 Z’},  
{id:‘rows2’,correct:9, cx:160,cy:80,  path:‘M0,70 H320 V90 H0 Z’},  
{id:‘rows3’,correct:9, cx:160,cy:110, path:‘M0,100 H320 V120 H0 Z’},  
// crowd dots  
…Array.from({length:20},(_,i)=>({  
id:`cd${i}`,correct:[1,3,4,5,6,7][i%6],cx:12+i*15,cy:42+Math.floor(i/8)*30,  
path:`M${9+i*15},${39+Math.floor(i/8)*30} a4,4 0 1,0 8,0 a4,4 0 1,0 -8,0`  
})),  
// checkered flags  
{id:‘flg1base’,correct:9,cx:22,cy:163,  path:‘M18,152 H26 V186 H18 Z’},  
{id:‘flg1’,    correct:10,cx:34,cy:156, path:‘M26,152 H44 V168 H26 Z’},  
{id:‘flg1b1’,  correct:8, cx:30,cy:156, path:‘M26,152 H34 V160 H26 Z’},  
{id:‘flg1b2’,  correct:8, cx:40,cy:160, path:‘M34,160 H42 V168 H34 Z’},  
{id:‘flg2base’,correct:9,cx:298,cy:163, path:‘M294,152 H302 V186 H294 Z’},  
{id:‘flg2’,    correct:10,cx:286,cy:156,path:‘M276,152 H294 V168 H276 Z’},  
{id:‘flg2b1’,  correct:8, cx:280,cy:156,path:‘M276,152 H284 V160 H276 Z’},  
{id:‘flg2b2’,  correct:8, cx:290,cy:160,path:‘M284,160 H292 V168 H284 Z’},  
// RACE CAR BODY  
{id:‘carbody’,correct:1, cx:160,cy:183, path:‘M52,193 Q52,174 64,170 H256 Q268,174 268,193 Z’},  
{id:‘cockpit’,correct:15,cx:154,cy:165, path:‘M96,170 Q100,148 120,140 H190 Q210,140 216,160 Q210,170 96,170 Z’},  
{id:‘windshield’,correct:14,cx:160,cy:156,path:‘M104,170 Q108,150 126,143 H196 Q212,146 214,165 Q210,168 104,170 Z’},  
{id:‘spoiler’,correct:15,cx:70,cy:164,  path:‘M52,172 Q52,156 68,154 Q82,154 84,166 Q76,172 52,172 Z’},  
{id:‘spoiler_rod’,correct:9,cx:70,cy:158,path:‘M66,154 H74 V168 H66 Z’},  
// side details  
{id:‘sideL’,correct:15,cx:76,cy:184,   path:‘M56,176 H100 V190 H56 Z’},  
{id:‘sideR’,correct:15,cx:244,cy:184,  path:‘M220,176 H264 V190 H220 Z’},  
{id:‘num1’, correct:10,cx:88,cy:183,   path:‘M82,178 H94 Q98,178 98,182 V186 Q98,190 94,190 H82 Q78,190 78,186 V182 Q78,178 82,178 Z’},  
{id:‘num2’, correct:10,cx:232,cy:183,  path:‘M226,178 H238 Q242,178 242,182 V186 Q242,190 238,190 H226 Q222,190 222,186 V182 Q222,178 226,178 Z’},  
// number on cockpit  
{id:‘num3’, correct:3, cx:155,cy:158,  path:‘M143,152 H166 Q170,152 170,156 V162 Q170,166 166,166 H143 Q139,166 139,162 V156 Q139,152 143,152 Z’},  
// exhaust  
{id:‘exh1’, correct:9, cx:244,cy:167,  path:‘M238,163 H250 Q254,163 254,167 Q254,171 250,171 H238 Q234,171 234,167 Q234,163 238,163 Z’},  
{id:‘exh2’, correct:9, cx:258,cy:165,  path:‘M252,163 H264 Q268,163 268,166 Q268,170 264,170 H252 Z’},  
{id:‘exhaust_flame’,correct:3,cx:270,cy:166,path:‘M268,161 Q278,166 268,172 Q264,168 268,161 Z’},  
// wheels  
{id:‘wh1’,  correct:8, cx:96,cy:196,   path:‘M72,196 a24,24 0 1,0 48,0 a24,24 0 1,0 -48,0’},  
{id:‘wh1r’, correct:9, cx:96,cy:196,   path:‘M82,196 a14,14 0 1,0 28,0 a14,14 0 1,0 -28,0’},  
{id:‘wh1c’, correct:10,cx:96,cy:196,   path:‘M91,196 a5,5 0 1,0 10,0 a5,5 0 1,0 -10,0’},  
{id:‘wh1sp1’,correct:9,cx:84,cy:188,   path:‘M82,184 L86,188 L82,192 Z’},  
{id:‘wh1sp2’,correct:9,cx:108,cy:188,  path:‘M106,184 L110,188 L106,192 Z’},  
{id:‘wh1sp3’,correct:9,cx:96,cy:182,   path:‘M92,180 L96,184 L100,180 Z’},  
{id:‘wh1sp4’,correct:9,cx:96,cy:210,   path:‘M92,208 L96,212 L100,208 Z’},  
{id:‘wh2’,  correct:8, cx:224,cy:196,  path:‘M200,196 a24,24 0 1,0 48,0 a24,24 0 1,0 -48,0’},  
{id:‘wh2r’, correct:9, cx:224,cy:196,  path:‘M210,196 a14,14 0 1,0 28,0 a14,14 0 1,0 -28,0’},  
{id:‘wh2c’, correct:10,cx:224,cy:196,  path:‘M219,196 a5,5 0 1,0 10,0 a5,5 0 1,0 -10,0’},  
{id:‘wh2sp1’,correct:9,cx:212,cy:188,  path:‘M210,184 L214,188 L210,192 Z’},  
{id:‘wh2sp2’,correct:9,cx:236,cy:188,  path:‘M234,184 L238,188 L234,192 Z’},  
{id:‘wh2sp3’,correct:9,cx:224,cy:182,  path:‘M220,180 L224,184 L228,180 Z’},  
{id:‘wh2sp4’,correct:9,cx:224,cy:210,  path:‘M220,208 L224,212 L228,208 Z’},  
// front air intake  
{id:‘intake’,correct:16,cx:256,cy:184, path:‘M252,178 H262 Q266,178 266,182 V188 Q266,192 262,192 H252 Q248,192 248,188 V182 Q248,178 252,178 Z’},  
// headlight  
{id:‘hlight’,correct:3, cx:260,cy:174, path:‘M254,170 H266 Q270,170 270,174 V178 Q270,182 266,182 H254 Q250,182 250,178 V174 Q250,170 254,170 Z’},  
]},  
  
// **─────────────────────────────────────────────────────────**  
// 10. FIRE TRUCK  
// **─────────────────────────────────────────────────────────**  
{name:‘Fire Truck’,emoji:‘🚒’,regions:[  
{id:‘sky’,  correct:14,cx:270,cy:28,  path:‘M0,0 H320 V140 H0 Z’},  
{id:‘road’, correct:9, cx:160,cy:200, path:‘M0,155 H320 V260 H0 Z’},  
{id:‘roadline’,correct:10,cx:160,cy:210,path:‘M20,206 H80 V214 H20 Z’},  
{id:‘roadline2’,correct:10,cx:200,cy:210,path:‘M160,206 H220 V214 H160 Z’},  
{id:‘roadline3’,correct:10,cx:280,cy:210,path:‘M250,206 H310 V214 H250 Z’},  
{id:‘curb’, correct:8, cx:160,cy:157, path:‘M0,153 H320 V162 H0 Z’},  
{id:‘sidewalk’,correct:11,cx:160,cy:150,path:‘M0,140 H320 V154 H0 Z’},  
// clouds + sun  
{id:‘sun’,  correct:3, cx:36,cy:36,   path:‘M20,36 a16,16 0 1,0 32,0 a16,16 0 1,0 -32,0’},  
{id:‘cl1’,  correct:10,cx:130,cy:36,  path:‘M100,48 Q100,32 112,30 Q116,18 130,22 Q138,12 150,18 Q162,14 166,28 Q178,24 176,44 Q176,56 160,56 H114 Q100,56 100,48 Z’},  
{id:‘cl2’,  correct:10,cx:246,cy:28,  path:‘M218,38 Q218,24 228,22 Q232,10 244,14 Q252,6 260,12 Q270,8 272,22 Q282,22 280,38 Q280,48 266,48 H228 Q218,48 218,38 Z’},  
// building in bg  
{id:‘bldg1’,correct:9, cx:288,cy:88,  path:‘M262,140 H314 V40 H262 Z’},  
{id:‘bldw1’,correct:14,cx:274,cy:60,  path:‘M268,54 H280 Q282,54 282,58 V70 Q282,74 280,74 H268 Q266,74 266,70 V58 Q266,54 268,54 Z’},  
{id:‘bldw2’,correct:14,cx:300,cy:60,  path:‘M294,54 H306 Q308,54 308,58 V70 Q308,74 306,74 H294 Q292,74 292,70 V58 Q292,54 294,54 Z’},  
{id:‘bldw3’,correct:14,cx:274,cy:90,  path:‘M268,84 H280 Q282,84 282,88 V100 Q282,104 280,104 H268 Q266,104 266,100 V88 Q266,84 268,84 Z’},  
{id:‘bldw4’,correct:14,cx:300,cy:90,  path:‘M294,84 H306 Q308,84 308,88 V100 Q308,104 306,104 H294 Q292,104 292,100 V88 Q292,84 294,84 Z’},  
// FIRE TRUCK MAIN BODY  
{id:‘tbody’,correct:1, cx:140,cy:186, path:‘M18,198 H256 Q264,198 264,190 V165 Q264,158 256,158 H18 Q10,158 10,166 V190 Q10,198 18,198 Z’},  
// cab  
{id:‘tcab’, correct:15,cx:228,cy:175, path:‘M200,158 H262 Q274,158 276,167 V190 Q276,198 264,198 H200 Z’},  
{id:‘twindshield’,correct:14,cx:250,cy:170,path:‘M210,162 H268 Q276,162 276,170 V184 Q272,188 210,188 Z’},  
{id:‘twin1’,correct:5, cx:218,cy:172, path:‘M210,165 H228 Q230,165 230,170 V180 Q230,184 228,184 H210 Z’},  
{id:‘twin2’,correct:5, cx:256,cy:170, path:‘M238,162 H272 Q276,162 276,168 V182 Q272,186 238,184 Z’},  
// cab details - door  
{id:‘tdoor’,correct:15,cx:200,cy:180, path:‘M190,160 H212 Q214,160 214,165 V196 H190 Z’},  
{id:‘tdhand’,correct:9,cx:213,cy:180, path:‘M211,177 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
// ladder on roof  
{id:‘ldrside1’,correct:9,cx:90,cy:153,path:‘M18,150 H182 V156 H18 Z’},  
{id:‘ldrside2’,correct:9,cx:90,cy:160,path:‘M18,157 H182 V163 H18 Z’},  
…Array.from({length:9},(_,i)=>({  
id:`ldrrung${i}`,correct:9,cx:32+i*18,cy:156,  
path:`M${28+i*18},150 H${36+i*18} V163 H${28+i*18} Z`  
})),  
// hose reel on truck side  
{id:‘hose_reel’,correct:9,cx:60,cy:180,path:‘M44,172 a18,14 0 1,0 36,0 a18,14 0 1,0 -36,0’},  
{id:‘hose_hub’, correct:1,cx:60,cy:180,path:‘M54,180 a6,5 0 1,0 12,0 a6,5 0 1,0 -12,0’},  
{id:‘hose_out’, correct:9,cx:80,cy:186,path:‘M78,178 Q86,182 88,190 Q90,196 86,198 Q82,198 80,192 Q80,186 78,178 Z’},  
// side compartments  
{id:‘comp1’,correct:15,cx:108,cy:180, path:‘M92,165 H124 Q126,165 126,170 V194 H92 Z’},  
{id:‘comp1d’,correct:9,cx:108,cy:181, path:‘M106,178 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
{id:‘comp2’,correct:15,cx:148,cy:180, path:‘M132,165 H164 Q166,165 166,170 V194 H132 Z’},  
{id:‘comp2d’,correct:9,cx:148,cy:181, path:‘M146,178 a3,3 0 1,0 6,0 a3,3 0 1,0 -6,0’},  
// emergency lights bar on roof  
{id:‘lightbar’,correct:9,cx:234,cy:156,path:‘M208,152 H260 Q264,152 264,156 V162 Q264,166 260,166 H208 Q204,166 204,162 V156 Q204,152 208,152 Z’},  
{id:‘lred1’,correct:1, cx:218,cy:158, path:‘M212,154 H226 Q228,154 228,158 V162 Q228,166 226,166 H212 Q210,166 210,162 V158 Q210,154 212,154 Z’},  
{id:‘lblue1’,correct:5,cx:234,cy:158, path:‘M228,154 H242 Q244,154 244,158 V162 Q244,166 242,166 H228 Q226,166 226,162 V158 Q226,154 228,154 Z’},  
{id:‘lred2’,correct:1, cx:250,cy:158, path:‘M244,154 H258 Q260,154 260,158 V162 Q260,166 258,166 H244 Q242,166 242,162 V158 Q242,154 244,154 Z’},  
// front grille + headlights  
{id:‘grille’,correct:9,cx:268,cy:183, path:‘M264,170 H278 Q282,170 282,175 V195 Q282,200 278,200 H264 Z’},  
{id:‘grille_h’,correct:9,cx:272,cy:175,path:‘M264,171 H280 V178 H264 Z’},  
{id:‘grille_h2’,correct:9,cx:272,cy:184,path:‘M264,181 H280 V188 H264 Z’},  
{id:‘headlight’,correct:3,cx:272,cy:168,path:‘M264,163 H280 Q284,163 284,168 V174 Q284,178 280,178 H264 Q260,178 260,174 V168 Q260,163 264,163 Z’},  
{id:‘bumper’,correct:9,cx:272,cy:198, path:‘M260,196 H282 Q286,196 286,200 V204 Q286,208 282,208 H260 Q256,208 256,204 V200 Q256,196 260,196 Z’},  
// wheels  
{id:‘wh1’,  correct:8, cx:72,cy:210,  path:‘M50,210 a22,22 0 1,0 44,0 a22,22 0 1,0 -44,0’},  
{id:‘wh1r’, correct:9, cx:72,cy:210,  path:‘M60,210 a12,12 0 1,0 24,0 a12,12 0 1,0 -24,0’},  
{id:‘wh1c’, correct:10,cx:72,cy:210,  path:‘M68,210 a4,4 0 1,0 8,0 a4,4 0 1,0 -8,0’},  
{id:‘wh2’,  correct:8, cx:178,cy:210, path:‘M156,210 a22,22 0 1,0 44,0 a22,22 0 1,0 -44,0’},  
{id:‘wh2r’, correct:9, cx:178,cy:210, path:‘M166,210 a12,12 0 1,0 24,0 a12,12 0 1,0 -24,0’},  
{id:‘wh2c’, correct:10,cx:178,cy:210, path:‘M174,210 a4,4 0 1,0 8,0 a4,4 0 1,0 -8,0’},  
{id:‘wh3’,  correct:8, cx:246,cy:210, path:‘M226,210 a20,20 0 1,0 40,0 a20,20 0 1,0 -40,0’},  
{id:‘wh3r’, correct:9, cx:246,cy:210, path:‘M236,210 a10,10 0 1,0 20,0 a10,10 0 1,0 -20,0’},  
{id:‘wh3c’, correct:10,cx:246,cy:210, path:‘M242,210 a4,4 0 1,0 8,0 a4,4 0 1,0 -8,0’},  
// siren on top  
{id:‘siren’,correct:1, cx:220,cy:150, path:‘M212,153 Q212,146 220,142 Q228,146 228,153 Z’},  
]},  
  
];// end SCENES  
  
/* **──────────────────** runtime **──────────────────** */  
let selectedColor=null, currentScene=0, stars=0;  
const filled={};  
  
function init(){  
buildSceneBar(); buildPalette(); loadScene(0);  
document.getElementById(‘resetBtn’).addEventListener(‘click’,resetScene);  
}  
function buildSceneBar(){  
const bar=document.getElementById(‘sceneBar’);  
SCENES.forEach((s,i)=>{  
const btn=document.createElement(‘button’);  
btn.className=‘scene-btn’+(i===0?’ active’:’’);  
btn.textContent=s.emoji+’ ‘+s.name;  
btn.addEventListener(‘click’,()=>loadScene(i));  
bar.appendChild(btn);  
});  
}  
function buildPalette(){  
const pal=document.getElementById(‘palette’);  
PALETTE.forEach(c=>{  
const sw=document.createElement(‘div’);  
sw.className=‘color-swatch’;  
sw.style.background=c.hex;  
if(c.hex===’#FFFFFF’) sw.style.outline=‘2px solid #ccc’;  
sw.dataset.id=c.id;  
sw.innerHTML=`<span class="swatch-num">${c.id}</span>`;  
sw.addEventListener(‘click’,()=>selectColor(c));  
pal.appendChild(sw);  
});  
document.getElementById(‘eraserBtn’).addEventListener(‘click’,()=>selectColor(null));  
}  
function selectColor(c){  
selectedColor=c;  
document.querySelectorAll(’.color-swatch’).forEach(el=>el.classList.toggle(‘active’,el.dataset.id==c?.id));  
document.getElementById(‘eraserBtn’).classList.toggle(‘active’,c===null);  
}  
function loadScene(idx){  
currentScene=idx;  
document.querySelectorAll(’.scene-btn’).forEach((b,i)=>b.classList.toggle(‘active’,i===idx));  
if(!filled[idx]) filled[idx]={};  
renderScene();  
}  
function renderScene(){  
const svg=document.getElementById(‘drawingSvg’);  
svg.innerHTML=’’;  
const scene=SCENES[currentScene], state=filled[currentScene];  
scene.regions.forEach(r=>{  
const el=document.createElementNS(‘http://www.w3.org/2000/svg’,‘path’);  
el.setAttribute(‘d’,r.path);  
el.classList.add(‘region’);  
const fc=state[r.id];  
el.setAttribute(‘fill’,fc||’#e8e8e8’);  
el.setAttribute(‘stroke’,’#1a1a1a’);  
el.setAttribute(‘stroke-width’,SW);  
el.setAttribute(‘stroke-linejoin’,‘round’);  
el.setAttribute(‘stroke-linecap’,‘round’);  
if(fc) el.classList.add(‘filled’);  
el.addEventListener(‘click’,()=>paintRegion(r));  
el.addEventListener(‘touchend’,e=>{e.preventDefault();paintRegion(r);});  
svg.appendChild(el);  
if(!fc){  
const txt=document.createElementNS(‘http://www.w3.org/2000/svg’,‘text’);  
txt.setAttribute(‘x’,r.cx); txt.setAttribute(‘y’,r.cy);  
txt.setAttribute(‘text-anchor’,‘middle’);  
txt.setAttribute(‘dominant-baseline’,‘middle’);  
txt.classList.add(‘num-label’);  
txt.textContent=r.correct;  
svg.appendChild(txt);  
}  
});  
}  
function paintRegion(r){  
const state=filled[currentScene];  
if(selectedColor===null) delete state[r.id];  
else state[r.id]=selectedColor.hex;  
renderScene(); checkCompletion();  
}  
function checkCompletion(){  
if(SCENES[currentScene].regions.every(r=>filled[currentScene][r.id])) celebrate();  
}  
function resetScene(){ filled[currentScene]={}; renderScene(); }  
function celebrate(){  
stars++;  
document.getElementById(‘starCount’).textContent=‘⭐ ‘+stars;  
const c=document.getElementById(‘celebrate’);  
c.classList.add(‘show’); spawnConfetti();  
setTimeout(()=>c.classList.remove(‘show’),3200);  
}  
const CC=[’#E53935’,’#FF8C00’,’#FFD700’,’#43A047’,’#1E88E5’,’#8E24AA’,’#F06292’];  
function spawnConfetti(){  
const wrap=document.getElementById(‘confettiWrap’);  
wrap.innerHTML=’’;  
for(let i=0;i<70;i++){  
const p=document.createElement(‘div’);  
p.className=‘confetti-piece’;  
p.style.left=Math.random()*100+’%’;  
p.style.background=CC[Math.floor(Math.random()*CC.length)];  
p.style.animationDelay=(Math.random()*.9)+‘s’;  
p.style.animationDuration=(1.2+Math.random()*.8)+‘s’;  
p.style.transform=`rotate(${Math.random()*360}deg)`;  
wrap.appendChild(p);  
}  
}  
init();  
</script>  
  
</body>  
</html>  
