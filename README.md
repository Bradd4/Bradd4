- 👋 Hi, I’m @Bradd4
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
function(){"use strict";var t=Object.freeze({__proto__:null,get queue(){return Ta},get start(){return Na},get stop(){return _a},get track(){return Ea}}),e=Object.freeze({__proto__:null,get clone(){return Za},get compute(){return Ka},get data(){return Xa},get keys(){return Pa},get reset(){return Qa},get start(){return Ja},get stop(){return tr},get trigger(){return Ga},get update(){return $a}}),n=Object.freeze({__proto__:null,get check(){return or},get compute(){return cr},get data(){return Ya},get start(){return ir},get stop(){return sr},get trigger(){return ur}}),a=Object.freeze({__proto__:null,get compute(){return vr},get data(){return lr},get log(){return pr},get reset(){return gr},get start(){return fr},get stop(){return hr},get updates(){return dr}}),r=Object.freeze({__proto__:null,get callbacks(){return br},get clear(){return xr},get consent(){return Sr},get data(){return mr},get id(){return Or},get metadata(){return Er},get save(){return Mr},get start(){return wr},get stop(){return kr}}),i=Object.freeze({__proto__:null,get data(){return Lr},get envelope(){return Hr},get start(){return zr},get stop(){return Rr}}),o={projectId:null,delay:1e3,lean:!1,track:!0,content:!0,drop:[],mask:[],unmask:[],regions:[],cookies:[],fraud:!0,checksum:[],report:null,upload:null,fallback:null,upgrade:null,action:null,dob:null};function u(t){return window.Zone&&"__symbol__"in window.Zone?window.Zone.__symbol__(t):t}var c=0;function s(t){void 0===t&&(t=null);var e=t&&t.timeStamp>0?t.timeStamp:performance.now();return Math.max(Math.round(e-c),0)}var l="0.7.10";function d(t,e){void 0===e&&(e=null);for(var n,a=5381,r=a,i=0;i<t.length;i+=2){if(a=(a<<5)+a^t.charCodeAt(i),i+1<t.length)r=(r<<5)+r^t.charCodeAt(i+1)}return n=Math.abs(a+11579*r),(e?n%Math.pow(2,e):n).toString(36)}var f=/\S/gi,h=!0,p=null,v=null,g=null;function m(t,e,n,a){if(void 0===a&&(a=!1),t)switch(n){case 0:return t;case 1:switch(e){case"*T":case"value":case"placeholder":case"click":return function(t){var e=-1,n=0,a=!1,r=!1,i=!1,o=null;O();for(var u=0;u<t.length;u++){var c=t.charCodeAt(u);if(a=a||c>=48&&c<=57,r=r||64===c,i=9===c||10===c||13===c||32===c,0===u||u===t.length-1||i){if(a||r){null===o&&(o=t.split(""));var s=t.substring(e+1,i?u:u+1);s=h&&null!==g?s.match(g)?s:k(s,"▪","▫"):w(s),o.splice(e+1-n,s.length,s),n+=s.length-1}i&&(a=!1,r=!1,e=u)}}return o?o.join(""):t}(t);case"input":case"change":return E(t)}return t;case 2:case 3:switch(e){case"*T":case"data-":return a?y(t):w(t);case"src":case"srcset":case"title":case"alt":return 3===n?"":t;case"value":case"click":case"input":case"change":return E(t);case"placeholder":return w(t)}break;case 4:switch(e){case"*T":case"data-":return a?y(t):w(t);case"value":case"input":case"click":case"change":return Array(5).join("•");case"checksum":return""}break;case 5:switch(e){case"*T":case"data-":return k(t,"▪","▫");case"value":case"input":case"click":case"change":return Array(5).join("•");case"checksum":case"src":case"srcset":case"alt":case"title":return""}}return t}function b(t,e){if(void 0===e&&(e=!1),e)return"".concat("https://").concat("Electron");var n=o.drop;if(n&&n.length>0&&t&&t.indexOf("?")>0){var a=t.split("?"),r=a[0],i=a[1];return r+"?"+i.split("&").map((function(t){return n.some((function(e){return 0===t.indexOf("".concat(e,"="))}))?"".concat(t.split("=")[0],"=").concat("*na*"):t})).join("&")}return t}function y(t){var e=t.trim();if(e.length>0){var n=e[0],a=t.indexOf(n),r=t.substr(0,a),i=t.substr(a+e.length);return"".concat(r).concat(e.length.toString(36)).concat(i)}return t}function w(t){return t.replace(f,"•")}function k(t,e,n){return O(),t?t.replace(v,e).replace(p,n):t}function E(t){for(var e=5*(Math.floor(t.length/5)+1),n="",a=0;a<e;a++)n+=a>0&&a%5==0?" ":"•";return n}function O(){if(h&&null===p)try{p=new RegExp("\\p{N}","gu"),v=new RegExp("\\p{L}","gu"),g=new RegExp("\\p{Sc}","gu")}catch(t){h=!1}}var S=null,x=null,M=!1;function N(){M&&(S={time:s(),event:4,data:{visible:x.visible,docWidth:x.docWidth,docHeight:x.docHeight,screenWidth:x.screenWidth,screenHeight:x.screenHeight,scrollX:x.scrollX,scrollY:x.scrollY,pointerX:x.pointerX,pointerY:x.pointerY,activityTime:x.activityTime}}),x=x||{visible:1,docWidth:0,docHeight:0,screenWidth:0,screenHeight:0,scrollX:0,scrollY:0,pointerX:0,pointerY:0,activityTime:0}}function T(t,e,n){switch(t){case 8:x.docWidth=e,x.docHeight=n;break;case 
<!---
Bradd4/Bradd4 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
