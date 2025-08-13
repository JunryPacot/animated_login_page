
├── index.html
├── script.js
└── style.css


/index.html:
--------------------------------------------------------------------------------
  1 | <!DOCTYPE html>
  2 | <html lang="en" >
  3 | <head>
  4 |   <meta charset="UTF-8">
  5 |   <title>Animated login form</title>
  6 |   <link rel="stylesheet" href="style.css">
  7 | 
  8 | </head>
  9 | <body>
 10 | 
 11 | <div class="container">
 12 |         <div class="form-container">
 13 |             <label class="form-row">
 14 |                 <input autocomplete="one-time-code" type="text" id="name" name="name" placeholder="name" required>
 15 |             </label>
 16 |             <label class="form-row">
 17 |                 <input autocomplete="one-time-code" type="email" id="email" name="email" placeholder="e-mail" required >
 18 |             </label>
 19 |             <label class="form-row">
 20 |                 <input type="checkbox" id="subscribe" name="subscribe"> agree to whatever
 21 |             </label>
 22 |             <div class="form-row">
 23 |                 <input type="submit" value="submit">
 24 |             </div>
 25 |         </div>
 26 |     
 27 |         <svg viewBox="0 0 1000 1000" stroke-linecap="round" stroke-linejoin="round">
 28 |     
 29 |             <rect x="710" y="527" width="16" height="47" rx="10" ry="10"></rect>
 30 |     
 31 |             <g class="grabbing-hand">
 32 |                 <path d="M48.89,54.39c-3.51.76-15.72,3-22.83-.68a14,14,0,0,0-6.41-1.52h0A3.79,3.79,0,0,1,17,51.09a3.7,3.7,0,0,1-1.1-2.64V27.75A3.75,3.75,0,0,1,19.63,24H24.1"/>
 33 |                 <path class="grabbing-hand-finger-open" d="M57.05,29.76l24.82,0a4.07,4.07,0,0,0,4.11-4h0a4.07,4.07,0,0,0-4-4.11L48.69,21.3"/>
 34 |                 <path class="grabbing-hand-finger-open" d="M59.34,37.74l28.81.61a4.06,4.06,0,0,0,4.14-4h0a4.06,4.06,0,0,0-4-4.15L57,29.64"/>
 35 |                 <path class="grabbing-hand-finger-open" d="M57.13,45.9l26.94.78a4.07,4.07,0,0,0,4.15-4h0a4.07,4.07,0,0,0-4-4.14l-24.84-.8"/>
 36 |                 <path class="grabbing-hand-finger-open" d="M48.89,54.39l27.82.36a4.06,4.06,0,0,0,4.2-3.93h0A4.06,4.06,0,0,0,77,46.62l-19.88-.78"/>
 37 |                 <path class="grabbing-hand-finger-open" d="M40.78,28c5.75-5.85,12.66-22,10.5-25.88-2.25-4.09-6,.1-14.73,8.66C30.84,16.36,30.91,17.1,24.32,24"/>
 38 |             </g>
 39 |     
 40 |             <g class="pull-system">
 41 |                 <line class="checkbox-pull-line" x1="0" y1="0" x2="0" y2="0"/>
 42 |                 <g class="checkbox-pull-circle">
 43 |                     <circle cx="0" cy="0" r="10"/>
 44 |                     <circle cx="0" cy="0" r="4" fill="#000000"/>
 45 |                 </g>
 46 |                 <circle class="submit-btn-circle" cx="0" cy="0" r="3" stroke="none" fill="#000" />
 47 |                 <path class="submit-btn-connector" d=""></path>
 48 |             </g>
 49 |     
 50 |             <g class="spray-hand-container">
 51 |                 <g class="pushing-hand">
 52 |                     <circle cx="18" cy="0" r="5" fill="#000000"/>
 53 |                     <circle cx="18" cy="-70" r="5" fill="#000000"/>
 54 |                     <path d="M18,-70 v70" stroke-width="4"/>
 55 |                     <g>
 56 |                         <path d="M25.3,32.9V60.2a4.2,4.2,0,0,0,4.2,4.2h0a4.2,4.2,0,0,0,4.2-4.2V26.7"/>
 57 |                         <rect x="3.9" y="18.4" width="8.4" height="21.47" rx="3.7" transform="translate(10.2 -1) rotate(19.4)"/>
 58 |                         <path d="M20.9,24a3.4,3.4,0,0,0-1.7-1.1h0a4.2,4.2,0,0,0-5.4,2.5L9.1,38.8a4.3,4.3,0,0,0,2.6,5.4h0a4.3,4.3,0,0,0,5.4-2.6l1.8-5.1"/>
 59 |                         <path d="M18.4,37.9,17.3,43a4.2,4.2,0,0,0,3.4,4.9h0a4.3,4.3,0,0,0,4.5-2.3"/>
 60 |                         <path fill="white" d="M29,16.8c-6.4,5-15,13.2-12.8,17.8s6,.7,15.8-6.7c6.4-4.8,7.4-12.6.5-19.2V4.2A3.8,3.8,0,0,0,28.7.5H8A3.5,3.5,0,0,0,5.4,1.6,3.7,3.7,0,0,0,4.3,4.2V8.7"/>
 61 |                         <path d="M4.3,8.7c-5.8,6.4-3.6,20-2.2,24.8"/>
 62 |                     </g>
 63 |                 </g>
 64 |                 <g class="sprayer">
 65 |                     <g class="sprayer-head">
 66 |                         <defs>
 67 |                             <radialGradient id="grad1" cx="50%" cy="50%" r="50%" fx="100%" fy="50%">
 68 |                                 <stop offset="0%" stop-color="#777777" stop-opacity="0"/>
 69 |                                 <stop offset="100%" stop-color="#777777" stop-opacity="1"/>
 70 |                             </radialGradient>
 71 |                         </defs>
 72 |                         <rect x="82.39" y="19.85" width="13.06" height="16.79" rx="1.46"/>
 73 |                         <rect x="74.55" y="22.56" width="7.84" height="6.1" rx="1.13"/>
 74 |     
 75 |                         <line class="spray-line" stroke="#777777" stroke-dasharray="8 5" x1="22.4" y1="14.76" x2="74.27" y2="25.2" />
 76 |                         <line class="spray-line" stroke="#777777" stroke-dasharray="8 5" x1="21.51" y1="21.12" x2="74.27" y2="25.2" />
 77 |                         <line class="spray-line" stroke="#777777" stroke-dasharray="8 5" x1="21.44" y1="28.26" x2="74.27" y2="25.2" />
 78 |                         <line class="spray-line" stroke="#777777" stroke-dasharray="8 5" x1="22.37" y1="35.54" x2="74.27" y2="25.2" />
 79 |                         <line class="spray-line" stroke="#777777" stroke-dasharray="8 5" x1="24.21" y1="42.36" x2="74.27" y2="25.2" />
 80 |                         <line class="spray-line" stroke="#777777" stroke-dasharray="8 5" x1="24.31" y1="7.78" x2="74.27" y2="25.2" />
 81 |     
 82 |                         <circle fill="url(#grad1)" stroke="none" class="spray-bubble" cx="25.43" cy="12.97" r="12.47" />
 83 |                         <circle fill="url(#grad1)" stroke="none" class="spray-bubble" cx="15.6" cy="25.43" r="15.1" />
 84 |                         <circle fill="url(#grad1)" stroke="none" class="spray-bubble" cx="33.24" cy="37.13" r="9.21" />
 85 |                         <circle fill="url(#grad1)" stroke="none" class="spray-bubble" cx="35.92" cy="19.5" r="11.89" />
 86 |                         <circle fill="url(#grad1)" stroke="none" class="spray-bubble" cx="18.82" cy="34.45" r="11.89" />
 87 |                     </g>
 88 |                     <path d="M89,42h0a21.3,21.3,0,0,1,21.3,21.3v56.48a5.06,5.06,0,0,1-5.06,5.06H72.6a5.06,5.06,0,0,1-5.06-5.06V63.4A21.45,21.45,0,0,1,89,42Z" fill="#fff"/>
 89 |                     <rect x="78.3" y="36.64" width="21.24" height="6.15" rx="1.93" fill="#fff"/>
 90 |                     <rect x="76.33" y="71.46" width="33.96" height="23.23" fill="#cccccc"/>
 91 |                 </g>
 92 |             </g>
 93 |     
 94 |             <g>
 95 |                 <line class="gear-connector" x1="0" x2="0" y1="0" y2="0"/>
 96 |                 <g class="gears">
 97 |                 </g>
 98 |             </g>
 99 |     
100 |             <g class="grabbing-hand">
101 |                 <g fill="#ffffff">
102 |                     <rect class="grabbing-hand-finger-closed" x="44.79" y="13.38" width="8.42" height="22.15" rx="3.67" transform="translate(20.57 71.26) rotate(-85.25)"/>
103 |                     <rect class="grabbing-hand-finger-closed" x="44.08" y="39.17" width="8.42" height="21.47" rx="3.67" transform="translate(-5.44 93.9) rotate(-85.25)"/>
104 |                     <rect class="grabbing-hand-finger-closed" x="45.68" y="30.71" width="8.42" height="22.57" rx="3.67" transform="matrix(0.08, -1, 1, 0.08, 3.91, 88.24)"/>
105 |                     <rect class="grabbing-hand-finger-closed" x="44.98" y="22.21" width="8.42" height="22.57" rx="3.67" transform="matrix(0.08, -1, 1, 0.08, 11.74, 79.74)"/>
106 |                     <path class="grabbing-hand-finger-closed" d="M32.18,27.42c5,6.46,13.22,15.06,17.76,12.81,4.18-2.07.69-6-6.66-15.74C38.46,18.1,30.69,17.1,24.1,24"/>
107 |                 </g>
108 |             </g>
109 |     
110 |             <g class="spiral-container">
111 |                 <path stroke-width=".8" class="spiral-path" d=""/>
112 |             </g>
113 |     
114 |             <g class="weight-big-container">
115 |                 <line x1="14" x2="60" y1="14" y2="14"></line>
116 |                 <line x1="14" x2="60" y1="14" y2="55"></line>
117 |                 <circle cx="14" cy="14" r="5" fill="#000000" stroke="none"/>
118 |     
119 |                 <g class="weight-big" stroke="none">
120 |                     <path d="M25.5,16.7c.2-.6.5-1.3.7-2C31.1,3.1,23.2,0,14.3,0S-1.6,4.2,2.4,14.7a22.5,22.5,0,0,1,.8,2.4A14.4,14.4,0,0,0,0,26.2c0,8,6.5,11.6,14.5,11.6S29,34.2,29,26.2A14.6,14.6,0,0,0,25.5,16.7ZM14.4,5c5.6,0,9.3,1.9,7.1,8.5a13.5,13.5,0,0,0-7-1.8,14.6,14.6,0,0,0-7.2,1.9C5.5,7.5,8.8,5,14.4,5Z" fill="#231f20"/>
121 |                     <path d="M15.1,15.6l-1.8-.2a9.2,9.2,0,0,0-9.1,9.2,6.2,6.2,0,0,0,.2,1.9A13.3,13.3,0,0,1,15.1,15.6Z" fill="#fff"/>
122 |                 </g>
123 |             </g>
124 |     
125 |     
126 |             <g class="scales-container">
127 |     
128 |                 <defs>
129 |                     <marker
130 |                             id="ball"
131 |                             viewBox="0 0 10 10"
132 |                             refX="5"
133 |                             refY="5"
134 |                             markerUnits="strokeWidth"
135 |                             markerWidth="5"
136 |                             markerHeight="5"
137 |                             orient="auto">
138 |                         <circle cx="5" cy="5" r="3" fill="#000"/>
139 |                     </marker>
140 |                 </defs>
141 |     
142 |     
143 |                 <rect x="10" y="-19" width="30" height="90" rx="15" ry="15" stroke-width="10" stroke="#ccc" />
144 |                 <rect class="timing-chain" x="10" y="-19" width="30" height="90" rx="15" ry="15" stroke="#fff" />
145 |     
146 |                 <rect x="-31" y="-19" width="30" height="144" rx="15" ry="15" stroke-width="10" stroke="#ccc"/>
147 |                 <rect class="timing-chain" x="-31" y="-19" width="30" height="144" rx="15" ry="15" stroke="#fff"/>
148 |     
149 |                 <g class="reels-connector">
150 |                     <rect x="-8" y="3.2" width="25" height="10" rx="5" ry="5" />
151 |                     <circle cx="-1" cy="8.5" r="3" fill="#000" stroke="none"/>
152 |                     <circle cx="9.9" cy="8.5" r="3" fill="#000" stroke="none"/>
153 |                 </g>
154 |     
155 |                 <g class="car-weight-connector">
156 |                     <rect x="-36" y="97" width="10" height="95" rx="5" ry="5" />
157 |                     <circle cx="-31" cy="103" r="3" fill="#000" stroke="none"/>
158 |                     <circle cx="-31" cy="186" r="3" fill="#000" stroke="none"/>
159 |                 </g>
160 |     
161 |     
162 |                 <line class="scales-moving-line" x1="147.6" y1="30.52" x2="40" y2="12" stroke-width="2" marker-start="url(#ball)" marker-end="url(#ball)"/>
163 |                 <path fill="#000000" d="M102.45,30.68,92,20.26c-9.89,9.9-9.89,10.47-9.89,10.47Z" />
164 |     
165 |             </g>
166 |     
167 |             <g class="car-container">
168 |                 <g>
169 |                     <g class="car">
170 |                         <circle cx="17" cy="88" r="5" />
171 |                         <circle cx="17" cy="88" r="2" fill="#000" />
172 |                         <circle cx="32" cy="88" r="5" />
173 |                         <circle cx="32" cy="88" r="2" fill="#000" />
174 |     
175 |                         <path d="M10,65 h30 l-5,15 h-20 l-5,-15 " fill="#000" />
176 |                     </g>
177 |     
178 |                     <line x1="-51" y1="95" x2="145" y2="95"/>
179 |                 </g>
180 |             </g>
181 |     
182 |         </svg>
183 |     </div>
184 |     <script src="https://unpkg.com/gsap@3/dist/gsap.min.js"></script>
185 | 
186 |   <script  src="script.js"></script>
187 | 
188 | </body>
189 | </html>
190 | 


--------------------------------------------------------------------------------
/script.js:
--------------------------------------------------------------------------------
  1 | const containerEl = document.querySelector('.container');
  2 | const checkboxEl = document.querySelector('.form-container .form-row input[type="checkbox"]');
  3 | const nameEl = document.querySelector('.form-container .form-row input[name="name"]');
  4 | const emailEl = document.querySelector('.form-container .form-row input[name="email"]');
  5 | const submitBtn = document.querySelector('.form-container .form-row input[type="submit"]');
  6 | 
  7 | const sprayer = document.querySelector('.sprayer');
  8 | const sprayHandContainer = document.querySelector('.spray-hand-container');
  9 | const sprayLines = Array.from(document.querySelectorAll('.spray-line'));
 10 | const sprayBubbles = Array.from(document.querySelectorAll('.spray-bubble'));
 11 | 
 12 | const pushingHand = document.querySelector('.pushing-hand');
 13 | const sprayerHead = document.querySelector('.sprayer-head');
 14 | const gearsContainer = document.querySelector('svg .gears');
 15 | const gearConnector = document.querySelector('.gear-connector');
 16 | 
 17 | const pullSystemContainer = document.querySelector('.pull-system');
 18 | 
 19 | const checkboxPullLine = document.querySelector('.checkbox-pull-line');
 20 | const checkboxPullCircle = document.querySelector('.checkbox-pull-circle');
 21 | const btnPullLine = document.querySelector('.submit-btn-connector');
 22 | const btnHandlerCircle = document.querySelector('.submit-btn-circle');
 23 | 
 24 | const spiralContainer = document.querySelector('.spiral-container');
 25 | const weightBigContainer = document.querySelector('.weight-big-container');
 26 | 
 27 | const scalesContainer = document.querySelector('.scales-container');
 28 | const scalesLine = document.querySelector('.scales-moving-line');
 29 | const weightBig = document.querySelector('.weight-big');
 30 | const spiralPath = document.querySelector('.spiral-path');
 31 | 
 32 | const carContainer = document.querySelector('.car-container');
 33 | const car = document.querySelector('.car');
 34 | const carInclineWrapper = document.querySelector('.car-container g');
 35 | const timingChains = Array.from(document.querySelectorAll('.timing-chain'));
 36 | const reelsConnector = document.querySelector('.reels-connector');
 37 | const carWeightConnector = document.querySelector('.car-weight-connector');
 38 | 
 39 | const grabbingHand = document.querySelectorAll('.grabbing-hand');
 40 | const grabbingHandOpenFingers = Array.from(document.querySelectorAll('.grabbing-hand-finger-open'));
 41 | const grabbingHandClosedFingers = Array.from(document.querySelectorAll('.grabbing-hand-finger-closed'));
 42 | 
 43 | 
 44 | layoutPreparation();
 45 | scaleToFit();
 46 | window.onresize = scaleToFit;
 47 | 
 48 | function scaleToFit() {
 49 |     const h = 800;
 50 | 
 51 |     if (window.innerHeight < h) {
 52 |         gsap.set(containerEl, {
 53 |             scale: window.innerHeight / h,
 54 |             transformOrigin: "50% 75%"
 55 |         })
 56 |     }
 57 | 
 58 | }
 59 | 
 60 | 
 61 | let sprayRepeatCounter = 0;
 62 | const state = {
 63 |     handClosed: false,
 64 |     sumbitBtnOnPlace: false,
 65 |     sumbitBtnTextOpacity: 0,
 66 |     pullProgress: 0
 67 | }
 68 | let nameValid = false;
 69 | let emailValid = false;
 70 | 
 71 | const emailTl = createEmailTl();
 72 | const gearsTls = createGearsTimelines();
 73 | createPullingTimeline(state.handClosed, checkboxEl.checked);
 74 | 
 75 | 
 76 | checkboxEl.addEventListener('change', () => {
 77 |     createPullingTimeline(state.handClosed, checkboxEl.checked);
 78 | })
 79 | 
 80 | nameEl.addEventListener('input', () => {
 81 |     nameValid = nameEl.value.length > 3;
 82 |     if (nameValid) {
 83 |         nameEl.classList.add("valid");
 84 |         gearsTls.forEach(tl => {
 85 |             if (tl.paused()) {
 86 |                 tl.play();
 87 |                 gsap.fromTo(tl, {
 88 |                     timeScale: 0
 89 |                 }, {
 90 |                     timeScale: 1
 91 |                 })
 92 |             }
 93 |         })
 94 |     } else {
 95 |         nameEl.classList.remove("valid");
 96 |         gearsTls.forEach(tl => {
 97 |             if (!tl.paused()) {
 98 |                 gsap.to(tl, {
 99 |                     timeScale: 0,
100 |                     onComplete: () => {
101 |                         tl.pause();
102 |                     }
103 |                 })
104 |             }
105 |         })
106 |         sprayRepeatCounter = 0;
107 |         gsap.to(submitBtn, {
108 |             duration: .3,
109 |             color: "rgba(0, 0, 0, " + 0 + ")"
110 |         })
111 |     }
112 | })
113 | 
114 | emailEl.addEventListener('input', () => {
115 |     const emailRegex = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
116 |     emailValid = emailRegex.test(emailEl.value);
117 |     if (emailValid) {
118 |         emailTl.play();
119 |         emailEl.classList.add("valid");
120 |     } else {
121 |         emailTl.reverse();
122 |         emailEl.classList.remove("valid");
123 |     }
124 | })
125 | 
126 | submitBtn.addEventListener('click', () => {
127 |     if (emailValid && checkboxEl.checked && nameValid && sprayRepeatCounter > 1) {
128 |         gsap.to("svg > *", {
129 |             duration: .1,
130 |             opacity: 0,
131 |             stagger: {
132 |                 each: 0.03,
133 |                 from: 'random',
134 |                 ease: 'none',
135 |             }
136 |         })
137 |         gsap.to(".form-row", {
138 |             delay: .4,
139 |             duration: .1,
140 |             opacity: 0,
141 |             stagger: .1
142 |         })
143 |     }
144 | })
145 | 
146 | 
147 | function layoutPreparation() {
148 |     gsap.set(pullSystemContainer, {
149 |         x: 375,
150 |         y: 646
151 |     })
152 |     gsap.set(sprayHandContainer, {
153 |         x: 700,
154 |         y: 621
155 |     })
156 |     gsap.set(sprayer, {
157 |         x: -59.5,
158 |         y: 53
159 |     })
160 |     gsap.set(carContainer, {
161 |         x: 190,
162 |         y: 802,
163 |     })
164 |     gsap.set(scalesContainer, {
165 |         x: 170,
166 |         y: 710,
167 |     })
168 |     gsap.set(grabbingHand, {
169 |         x: 297,
170 |         y: 830
171 |     })
172 |     gsap.set(grabbingHandClosedFingers, {
173 |         opacity: 0
174 |     })
175 |     gsap.set(spiralContainer, {
176 |         x: 305,
177 |         y: 435,
178 |         svgOrigin: "14 14",
179 |         scaleX: -1,
180 |     })
181 |     gsap.set(weightBigContainer, {
182 |         x: 305,
183 |         y: 435,
184 |     })
185 |     gsap.set(submitBtn, {
186 |         color: "rgba(0, 0, 0, " + 0 + ")"
187 |     })
188 |     gsap.set([sprayLines, sprayBubbles], {
189 |         opacity: 0
190 |     })
191 |     gsap.set(timingChains[0], {
192 |         attr: {
193 |             "stroke-width": "5",
194 |             "stroke-dasharray": "0 12",
195 |         }
196 |     })
197 |     gsap.set(timingChains[1], {
198 |         attr: {
199 |             "stroke-width": "5",
200 |             "stroke-dasharray": "0 12",
201 |         }
202 |     })
203 |     gsap.set(checkboxPullLine, {
204 |         attr: {
205 |             y1: -105,
206 |             y2: 44
207 |         }
208 |     });
209 |     gsap.set(submitBtn, {
210 |         transformOrigin: "100% 0%",
211 |         rotation: -90
212 |     })
213 |     gsap.set(checkboxPullCircle, {
214 |         y: 44
215 |     });
216 | }
217 | 
218 | function updateSpiralPath(centerX, centerY, radius, coils, points, offset) {
219 |     let path = "";
220 |    
