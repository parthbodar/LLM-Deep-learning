(function(){'use strict';var n;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ca(this);function u(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ia(aa(this))}})}return a});
function ia(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ja(a){return a.raw=a}
function ka(a,b){a.raw=b;return a}
function v(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function la(a){if(!(a instanceof Array)){a=v(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ma(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var oa=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ma(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||oa});
var pa=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},qa=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=pa(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ra;
if(typeof Object.setPrototypeOf=="function")ra=Object.setPrototypeOf;else{var sa;a:{var ta={a:!0},ua={};try{ua.__proto__=ta;sa=ua.a;break a}catch(a){}sa=!1}ra=sa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var wa=ra;
function y(a,b){a.prototype=pa(b.prototype);a.prototype.constructor=a;if(wa)wa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Ba=b.prototype}
function xa(){this.A=!1;this.m=null;this.i=void 0;this.h=1;this.v=this.l=0;this.P=this.j=null}
function ya(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
xa.prototype.H=function(a){this.i=a};
function za(a,b){a.j={exception:b,kd:!0};a.h=a.l||a.v}
xa.prototype.return=function(a){this.j={return:a};this.h=this.v};
xa.prototype.yield=function(a,b){this.h=b;return{value:a}};
xa.prototype.B=function(a){this.h=a};
function Aa(a,b,c){a.l=b;c!=void 0&&(a.v=c)}
function Ba(a){a.l=0;var b=a.j.exception;a.j=null;return b}
function Ca(a){var b=a.P.splice(0)[0];(b=a.j=a.j||b)?b.kd?a.h=a.l||a.v:b.B!=void 0&&a.v<b.B?(a.h=b.B,a.j=null):a.h=a.v:a.h=0}
function Da(a){this.h=new xa;this.i=a}
function Ea(a,b){ya(a.h);var c=a.h.m;if(c)return Fa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ga(a)}
function Fa(a,b,c,d){try{var e=b.call(a.h.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.A=!1,e;var f=e.value}catch(g){return a.h.m=null,za(a.h,g),Ga(a)}a.h.m=null;d.call(a.h,f);return Ga(a)}
function Ga(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.A=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,za(a.h,c)}a.h.A=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.kd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ha(a){this.next=function(b){ya(a.h);a.h.m?b=Fa(a,a.h.m.next,b,a.h.H):(a.h.H(b),b=Ga(a));return b};
this.throw=function(b){ya(a.h);a.h.m?b=Fa(a,a.h.m["throw"],b,a.h.H):(za(a.h,b),b=Ga(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ia(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function z(a){return Ia(new Ha(new Da(a)))}
function A(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return qa});
u("Reflect.setPrototypeOf",function(a){return a?a:wa?function(b,c){try{return wa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.A=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.v()})}this.h.push(g)};
var e=fa.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.v=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.da),reject:g(this.v)}};
b.prototype.da=function(g){if(g===this)this.v(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ia(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.ba(g):this.m(g)}};
b.prototype.ba=function(g){var h=void 0;try{h=g.then}catch(k){this.v(k);return}typeof h=="function"?this.xa(h,g):this.m(g)};
b.prototype.v=function(g){this.H(2,g)};
b.prototype.m=function(g){this.H(1,g)};
b.prototype.H=function(g,h){if(this.h!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;this.h===2&&this.ga();this.P()};
b.prototype.ga=function(){var g=this;e(function(){if(g.W()){var h=fa.console;typeof h!=="undefined"&&h.error(g.j)}},1)};
b.prototype.W=function(){if(this.A)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.P=function(){if(this.i!=null){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ia=function(g){var h=this.l();g.Zb(h.resolve,h.reject)};
b.prototype.xa=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,t){return typeof r=="function"?function(w){try{l(r(w))}catch(x){m(x)}}:t}
var l,m,p=new b(function(r,t){l=r;m=t});
this.Zb(k(g,l),k(h,m));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Zb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;this.i==null?f.i(k):this.i.push(k);this.A=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=v(g),m=l.next();!m.done;m=l.next())d(m.value).Zb(h,k)})};
b.all=function(g){var h=v(g),k=h.next();return k.done?d([]):new b(function(l,m){function p(w){return function(x){r[w]=x;t--;t==0&&l(r)}}
var r=[],t=0;do r.push(void 0),t++,d(k.value).Zb(p(r.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||wa});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=v(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!ma(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ma(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ma(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ma(k,g)&&ma(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ma(k,g)&&ma(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ia(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&ma(h[0],l))for(h=0;h<m.length;h++){var p=m[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:m,index:h,entry:p}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=v(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(v([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ja(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
function Ma(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Ma(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Ma(this,function(b){return b})}});
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=v(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(v([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
u("Array.prototype.values",function(a){return a?a:function(){return Ma(this,function(b,c){return c})}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ma(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ja(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ma(b,d)&&c.push([d,b[d]]);return c}});
u("globalThis",function(a){return a||fa});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Na=Na||{},B=this||self;function D(a,b,c){a=a.split(".");c=c||B;a[0]in c||typeof c.execScript=="undefined"||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Oa(a){var b=E("CLOSURE_FLAGS");a=b&&b[a];return a!=null?a:!1}
function E(a,b){a=a.split(".");b=b||B;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function Pa(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Qa(a){var b=Pa(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Ra(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Sa(a){return Object.prototype.hasOwnProperty.call(a,Ta)&&a[Ta]||(a[Ta]=++Ua)}
var Ta="closure_uid_"+(Math.random()*1E9>>>0),Ua=0;function Va(a,b,c){return a.call.apply(a.bind,arguments)}
function Wa(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Xa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Va:Wa;return Xa.apply(null,arguments)}
function Ya(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Za(){return Date.now()}
function $a(a,b){function c(){}
c.prototype=b.prototype;a.Ba=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function ab(a){return a}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
$a(bb,Error);bb.prototype.name="CustomError";function cb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;var db=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};var eb;function fb(){if(eb===void 0){var a=null,b=B.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:ab,createScript:ab,createScriptURL:ab})}catch(c){B.console&&B.console.error(c.message)}eb=a}else eb=a}return eb}
;function gb(a,b){this.h=a===hb&&b||""}
gb.prototype.toString=function(){return this.h};
function ib(a){return new gb(hb,a)}
var hb={};ib("");function jb(a){this.h=a}
jb.prototype.toString=function(){return this.h+""};
function kb(a){if(a instanceof jb&&a.constructor===jb)return a.h;Pa(a);return"type_error:TrustedResourceUrl"}
var lb={};function mb(a){var b=fb();a=b?b.createScriptURL(a):a;return new jb(a,lb)}
;/*

 SPDX-License-Identifier: Apache-2.0
*/
var nb=ja([""]),ob=ka(["\x00"],["\\0"]),pb=ka(["\n"],["\\n"]),qb=ka(["\x00"],["\\u0000"]);function rb(a){return a.toString().indexOf("`")===-1}
rb(function(a){return a(nb)})||rb(function(a){return a(ob)})||rb(function(a){return a(pb)})||rb(function(a){return a(qb)});function sb(a){this.h=a}
sb.prototype.toString=function(){return this.h};
var tb=new sb("about:invalid#zClosurez");function ub(a){this.qe=a}
function vb(a){return new ub(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var wb=[vb("data"),vb("http"),vb("https"),vb("mailto"),vb("ftp"),new ub(function(a){return/^[^:]*([/?#]|$)/.test(a)})],xb=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function yb(a){if(a instanceof sb)if(a instanceof sb)a=a.h;else throw Error("");else a=xb.test(a)?a:void 0;return a}
;function zb(a,b){b=yb(b);b!==void 0&&(a.href=b)}
;function Ab(){this.h=Bb[0].toLowerCase()}
Ab.prototype.toString=function(){return this.h};var Cb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Db=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e=typeof a==="string"?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Eb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Fb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Gb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Db(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Hb(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Ib(a,b){b=Cb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Jb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Qa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Kb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function Lb(a){var b=Mb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function Nb(a){for(var b in a)return!1;return!0}
function Ob(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function Pb(a){return a!==null&&"privembed"in a?a.privembed:!1}
function Qb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function Rb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function Sb(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=Sb(a[c]);return b}
var Tb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function Ub(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Tb.length;f++)c=Tb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function Vb(a){this.h=a}
Vb.prototype.toString=function(){return this.h.toString()};function Wb(a){var b="true".toString(),c=[new Ab];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof Ab)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Xb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;var Yb="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Zb(a,b){if(b instanceof jb)a.href=kb(b).toString();else{if(Yb.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=yb(b);if(b===void 0)return;a.href=b}a.rel="stylesheet"}
;function $b(a){var b,c;return(a=(c=(b=a.document).querySelector)==null?void 0:c.call(b,"script[nonce]"))?a.nonce||a.getAttribute("nonce")||"":""}
;function ac(a){this.h=a}
ac.prototype.toString=function(){return this.h.toString()};function bc(a){var b=$b(a.ownerDocument&&a.ownerDocument.defaultView||window);b&&a.setAttribute("nonce",b)}
function cc(a,b){if(b instanceof ac)b=b.h;else throw Error("");a.textContent=b;bc(a)}
function dc(a,b){a.src=kb(b);bc(a)}
;function ec(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function fc(a){var b=E("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||B.$googDebugFname||b}catch(g){e="Not available",c=!0}b=hc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,ic[c])c=ic[c];else{c=String(c);if(!ic[c]){var f=/function\s+([^\(]+)/m.exec(c);ic[c]=f?f[1]:"[Anonymous]"}c=ic[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function hc(a,b){b||(b={});b[jc(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[jc(a)]&&(c+="\nCaused by: ",a.stack&&a.stack.indexOf(a.toString())==0||(c+=typeof a==="string"?a:a.message+"\n"),c+=hc(a,b));return c}
function jc(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var ic={};function kc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var lc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function mc(a){return a?decodeURI(a):a}
function nc(a,b){return b.match(lc)[a]||null}
function oc(a){return mc(nc(3,a))}
function pc(a){var b=a.match(lc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function qc(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function rc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)rc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function sc(a){var b=[],c;for(c in a)rc(c,a[c],b);return b.join("&")}
function tc(a,b){b=sc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function uc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var vc=/#|$/,wc=/[?&]($|#)/;function xc(a,b){for(var c=a.search(vc),d=0,e,f=[];(e=uc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(wc,"$1")}
;function yc(a){this.h=a}
;function zc(a,b,c){this.l=a;this.j=b;this.fields=c||[];this.h=new Map}
n=zc.prototype;n.Ld=function(a){var b=A.apply(1,arguments),c=this.yc(b);c?c.push(new yc(a)):this.xd(a,b)};
n.xd=function(a){var b=this.Tc(A.apply(1,arguments));this.h.set(b,[new yc(a)])};
n.yc=function(){var a=this.Tc(A.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
n.de=function(){var a=this.yc(A.apply(0,arguments));return a&&a.length?a[0]:void 0};
n.clear=function(){this.h.clear()};
n.Tc=function(){var a=A.apply(0,arguments);return a?a.join(","):"key"};function Ac(a,b){zc.call(this,a,3,b)}
y(Ac,zc);Ac.prototype.i=function(a){var b=A.apply(1,arguments),c=0,d=this.de(b);d&&(c=d.h);this.xd(c+a,b)};function Bc(a,b){zc.call(this,a,2,b)}
y(Bc,zc);Bc.prototype.record=function(a){this.Ld(a,A.apply(1,arguments))};function Cc(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function Dc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Qa(d)?Dc.apply(null,d):Cc(d)}}
;function G(){this.V=this.V;this.v=this.v}
G.prototype.V=!1;G.prototype.dispose=function(){this.V||(this.V=!0,this.U())};
function Ec(a,b){a.addOnDisposeCallback(Ya(Cc,b))}
G.prototype.addOnDisposeCallback=function(a,b){this.V?b!==void 0?a.call(b):a():(this.v||(this.v=[]),this.v.push(b!==void 0?Xa(a,b):a))};
G.prototype.U=function(){if(this.v)for(;this.v.length;)this.v.shift()()};function Fc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Fc.prototype.stopPropagation=function(){this.j=!0};
Fc.prototype.preventDefault=function(){this.defaultPrevented=!0};var Gc=function(){if(!B.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
B.addEventListener("test",c,b);B.removeEventListener("test",c,b)}catch(d){}return a}();var Hc=Oa(610401301),Ic=Oa(188588736);function Jc(){var a=B.navigator;return a&&(a=a.userAgent)?a:""}
var Kc,Lc=B.navigator;Kc=Lc?Lc.userAgentData||null:null;function Mc(a){return Hc?Kc?Kc.brands.some(function(b){return(b=b.brand)&&b.indexOf(a)!=-1}):!1:!1}
function H(a){return Jc().indexOf(a)!=-1}
;function Nc(){return Hc?!!Kc&&Kc.brands.length>0:!1}
function Oc(){return Nc()?!1:H("Opera")}
function Pc(){return H("Firefox")||H("FxiOS")}
function Qc(){return Nc()?Mc("Chromium"):(H("Chrome")||H("CriOS"))&&!(Nc()?0:H("Edge"))||H("Silk")}
;function Rc(){return Hc?!!Kc&&!!Kc.platform:!1}
function Sc(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;function Tc(a){Tc[" "](a);return a}
Tc[" "]=function(){};var Uc=Oc(),Vc=Nc()?!1:H("Trident")||H("MSIE"),Wc=H("Edge"),Xc=H("Gecko")&&!(Jc().toLowerCase().indexOf("webkit")!=-1&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),Yc=Jc().toLowerCase().indexOf("webkit")!=-1&&!H("Edge");Yc&&H("Mobile");Rc()||H("Macintosh");Rc()||H("Windows");(Rc()?Kc.platform==="Linux":H("Linux"))||Rc()||H("CrOS");var Zc=Rc()?Kc.platform==="Android":H("Android");Sc();H("iPad");H("iPod");Sc()||H("iPad")||H("iPod");Jc().toLowerCase().indexOf("kaios");function $c(a,b){Fc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
$a($c,Fc);var ad={2:"touch",3:"pen",4:"mouse"};
$c.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Xc){a:{try{Tc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=typeof a.pointerType==="string"?a.pointerType:ad[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&$c.Ba.preventDefault.call(this)};
$c.prototype.stopPropagation=function(){$c.Ba.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
$c.prototype.preventDefault=function(){$c.Ba.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var bd="closure_listenable_"+(Math.random()*1E6|0);var cd=0;function dd(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.fc=e;this.key=++cd;this.Pb=this.Yb=!1}
function ed(a){a.Pb=!0;a.listener=null;a.proxy=null;a.src=null;a.fc=null}
;function fd(a){this.src=a;this.listeners={};this.h=0}
fd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=gd(a,b,d,e);g>-1?(b=a[g],c||(b.Yb=!1)):(b=new dd(b,this.src,f,!!d,e),b.Yb=c,a.push(b));return b};
fd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=gd(e,b,c,d);return b>-1?(ed(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function hd(a,b){var c=b.type;c in a.listeners&&Ib(a.listeners[c],b)&&(ed(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function gd(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Pb&&f.listener==b&&f.capture==!!c&&f.fc==d)return e}return-1}
;var id="closure_lm_"+(Math.random()*1E6|0),jd={},kd=0;function ld(a,b,c,d,e){if(d&&d.once)md(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)ld(a,b[f],c,d,e);else c=nd(c),a&&a[bd]?a.listen(b,c,Ra(d)?!!d.capture:!!d,e):od(a,b,c,!1,d,e)}
function od(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ra(e)?!!e.capture:!!e,h=pd(a);h||(a[id]=h=new fd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=qd();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Gc||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(rd(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");kd++}}
function qd(){function a(c){return b.call(a.src,a.listener,c)}
var b=sd;return a}
function md(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)md(a,b[f],c,d,e);else c=nd(c),a&&a[bd]?a.h.add(String(b),c,!0,Ra(d)?!!d.capture:!!d,e):od(a,b,c,!0,d,e)}
function td(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)td(a,b[f],c,d,e);else(d=Ra(d)?!!d.capture:!!d,c=nd(c),a&&a[bd])?a.h.remove(String(b),c,d,e):a&&(a=pd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=gd(b,c,d,e)),(c=a>-1?b[a]:null)&&ud(c))}
function ud(a){if(typeof a!=="number"&&a&&!a.Pb){var b=a.src;if(b&&b[bd])hd(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(rd(c),d):b.addListener&&b.removeListener&&b.removeListener(d);kd--;(c=pd(b))?(hd(c,a),c.h==0&&(c.src=null,b[id]=null)):ed(a)}}}
function rd(a){return a in jd?jd[a]:jd[a]="on"+a}
function sd(a,b){if(a.Pb)a=!0;else{b=new $c(b,this);var c=a.listener,d=a.fc||a.src;a.Yb&&ud(a);a=c.call(d,b)}return a}
function pd(a){a=a[id];return a instanceof fd?a:null}
var vd="__closure_events_fn_"+(Math.random()*1E9>>>0);function nd(a){if(typeof a==="function")return a;a[vd]||(a[vd]=function(b){return a.handleEvent(b)});
return a[vd]}
;function wd(){G.call(this);this.h=new fd(this);this.Za=this;this.ga=null}
$a(wd,G);wd.prototype[bd]=!0;n=wd.prototype;n.addEventListener=function(a,b,c,d){ld(this,a,b,c,d)};
n.removeEventListener=function(a,b,c,d){td(this,a,b,c,d)};
function xd(a,b){var c=a.ga;if(c){var d=[];for(var e=1;c;c=c.ga)d.push(c),++e}a=a.Za;c=b.type||b;typeof b==="string"?b=new Fc(b,a):b instanceof Fc?b.target=b.target||a:(e=b,b=new Fc(c,a),Ub(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=yd(g,c,!0,b)&&e}b.j||(g=b.h=a,e=yd(g,c,!0,b)&&e,b.j||(e=yd(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=yd(g,c,!1,b)&&e}
n.U=function(){wd.Ba.U.call(this);this.removeAllListeners();this.ga=null};
n.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
n.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,ed(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function yd(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Pb&&g.capture==c){var h=g.listener,k=g.fc||g.src;g.Yb&&hd(a.h,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;function zd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
zd.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Ad(a,b){a.l(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function Bd(){}
function Cd(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Dd(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
n=Dd.prototype;n.clone=function(){return new Dd(this.x,this.y)};
n.equals=function(a){return a instanceof Dd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
n.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
n.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
n.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
n.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function Ed(a,b){this.width=a;this.height=b}
n=Ed.prototype;n.clone=function(){return new Ed(this.width,this.height)};
n.aspectRatio=function(){return this.width/this.height};
n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
n.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function Fd(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function Gd(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function Hd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Id;function Jd(){var a=B.MessageChannel;typeof a==="undefined"&&typeof window!=="undefined"&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=Gd("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h=f.location.protocol=="file:"?"*":f.location.protocol+"//"+f.location.host;e=Xa(function(k){if((h=="*"||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if(typeof a!=="undefined"){var b=new a,c={},d=c;b.port1.onmessage=function(){if(c.next!==void 0){c=c.next;var e=c.Xc;c.Xc=null;e()}};
return function(e){d.next={Xc:e};d=d.next;b.port2.postMessage(0)}}return function(e){B.setTimeout(e,0)}}
;function Kd(a){B.setTimeout(function(){throw a;},0)}
;function Ld(){this.i=this.h=null}
Ld.prototype.add=function(a,b){var c=Md.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Ld.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Md=new zd(function(){return new Nd},function(a){return a.reset()});
function Nd(){this.next=this.scope=this.h=null}
Nd.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Nd.prototype.reset=function(){this.next=this.scope=this.h=null};var Od,Pd=!1,Qd=new Ld;function Rd(a,b){Od||Sd();Pd||(Od(),Pd=!0);Qd.add(a,b)}
function Sd(){if(B.Promise&&B.Promise.resolve){var a=B.Promise.resolve(void 0);Od=function(){a.then(Td)}}else Od=function(){var b=Td;
typeof B.setImmediate!=="function"||B.Window&&B.Window.prototype&&B.Window.prototype.setImmediate==B.setImmediate?(Id||(Id=Jd()),Id(b)):B.setImmediate(b)}}
function Td(){for(var a;a=Qd.remove();){try{a.h.call(a.scope)}catch(b){Kd(b)}Ad(Md,a)}Pd=!1}
;function Ud(a){this.h=0;this.A=void 0;this.l=this.i=this.j=null;this.v=this.m=!1;if(a!=Bd)try{var b=this;a.call(void 0,function(c){Vd(b,2,c)},function(c){Vd(b,3,c)})}catch(c){Vd(this,3,c)}}
function Wd(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
Wd.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Xd=new zd(function(){return new Wd},function(a){a.reset()});
function Yd(a,b,c){var d=Xd.get();d.i=a;d.h=b;d.context=c;return d}
function Zd(a){return new Ud(function(b,c){c(a)})}
Ud.prototype.then=function(a,b,c){return $d(this,typeof a==="function"?a:null,typeof b==="function"?b:null,c)};
Ud.prototype.$goog_Thenable=!0;n=Ud.prototype;n.qc=function(a,b){return $d(this,null,a,b)};
n.catch=Ud.prototype.qc;n.cancel=function(a){if(this.h==0){var b=new ae(a);Rd(function(){be(this,b)},this)}};
function be(a,b){if(a.h==0)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.h==0&&d==1?be(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):ce(c),de(c,e,3,b)))}a.j=null}else Vd(a,3,b)}
function ee(a,b){a.i||a.h!=2&&a.h!=3||fe(a);a.l?a.l.next=b:a.i=b;a.l=b}
function $d(a,b,c,d){var e=Yd(null,null,null);e.child=new Ud(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof ae?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;ee(a,e);return e.child}
n.jf=function(a){this.h=0;Vd(this,2,a)};
n.kf=function(a){this.h=0;Vd(this,3,a)};
function Vd(a,b,c){if(a.h==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.jf,f=a.kf;if(d instanceof Ud){ee(d,Yd(e||Bd,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ra(d))try{var k=d.then;if(typeof k==="function"){ge(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.A=c,a.h=b,a.j=null,fe(a),b!=3||c instanceof ae||he(a,c))}}
function ge(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function fe(a){a.m||(a.m=!0,Rd(a.Xd,a))}
function ce(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
n.Xd=function(){for(var a;a=ce(this);)de(this,a,this.h,this.A);this.m=!1};
function de(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.v;a=a.j)a.v=!1;if(b.child)b.child.j=null,ie(b,c,d);else try{b.j?b.i.call(b.context):ie(b,c,d)}catch(e){je.call(null,e)}Ad(Xd,b)}
function ie(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function he(a,b){a.v=!0;Rd(function(){a.v&&je.call(null,b)})}
var je=Kd;function ae(a){bb.call(this,a)}
$a(ae,bb);ae.prototype.name="cancel";function ke(a,b){wd.call(this);this.j=a||1;this.i=b||B;this.l=Xa(this.ff,this);this.m=Za()}
$a(ke,wd);n=ke.prototype;n.enabled=!1;n.Fa=null;n.setInterval=function(a){this.j=a;this.Fa&&this.enabled?(this.stop(),this.start()):this.Fa&&this.stop()};
n.ff=function(){if(this.enabled){var a=Za()-this.m;a>0&&a<this.j*.8?this.Fa=this.i.setTimeout(this.l,this.j-a):(this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null),xd(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
n.start=function(){this.enabled=!0;this.Fa||(this.Fa=this.i.setTimeout(this.l,this.j),this.m=Za())};
n.stop=function(){this.enabled=!1;this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null)};
n.U=function(){ke.Ba.U.call(this);this.stop();delete this.i};
function le(a,b,c){if(typeof a==="function")c&&(a=Xa(a,c));else if(a&&typeof a.handleEvent=="function")a=Xa(a.handleEvent,a);else throw Error("Invalid listener argument");return Number(b)>2147483647?-1:B.setTimeout(a,b||0)}
;function me(a){G.call(this);this.H=a;this.j=0;this.l=100;this.m=!1;this.i=new Map;this.A=new Set;this.flushInterval=3E4;this.h=new ke(this.flushInterval);this.h.listen("tick",this.Aa,!1,this);Ec(this,this.h)}
y(me,G);n=me.prototype;n.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function ne(a){a.h.enabled||a.h.start();a.j++;a.j>=a.l&&a.Aa()}
n.Aa=function(){var a=this.i.values();a=[].concat(la(a)).filter(function(b){return b.h.size});
a.length&&this.H.flush(a,this.m);oe(a);this.j=0;this.h.enabled&&this.h.stop()};
n.Ra=function(a){var b=A.apply(1,arguments);this.i.has(a)||this.i.set(a,new Ac(a,b))};
n.Eb=function(a){var b=A.apply(1,arguments);this.i.has(a)||this.i.set(a,new Bc(a,b))};
function pe(a,b){return a.A.has(b)?void 0:a.i.get(b)}
n.Ab=function(a){this.Jd(a,1,A.apply(1,arguments))};
n.Jd=function(a,b){var c=A.apply(2,arguments),d=pe(this,a);d&&d instanceof Ac&&(d.i(b,c),ne(this))};
n.record=function(a,b){var c=A.apply(2,arguments),d=pe(this,a);d&&d instanceof Bc&&(d.record(b,c),ne(this))};
function oe(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function qe(a){this.h=a;this.h.Ra("/client_streamz/bg/fic",{G:3,F:"ke"})}
function re(a){this.h=a;this.h.Ra("/client_streamz/bg/fiec",{G:3,F:"rk"},{G:3,F:"ke"},{G:2,F:"ec"})}
function se(a){this.h=a;this.h.Eb("/client_streamz/bg/fil",{G:3,F:"rk"},{G:3,F:"ke"})}
se.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fil",a,b,c)};
function te(a){this.h=a;this.h.Ra("/client_streamz/bg/fcc",{G:2,F:"ph"},{G:3,F:"ke"})}
function ue(a){this.h=a;this.h.Eb("/client_streamz/bg/fcd",{G:2,F:"ph"},{G:3,F:"ke"})}
ue.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fcd",a,b,c)};
function ve(a){this.h=a;this.h.Ra("/client_streamz/bg/fsc",{G:3,F:"rk"},{G:3,F:"ke"})}
function we(a){this.h=a;this.h.Eb("/client_streamz/bg/fsl",{G:3,F:"rk"},{G:3,F:"ke"})}
we.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fsl",a,b,c)};
function xe(a){this.h=a;this.h.Eb("/client_streamz/bg/wrl",{G:3,F:"mn"},{G:2,F:"ac"},{G:2,F:"sc"},{G:3,F:"rk"},{G:3,F:"mk"})}
xe.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function ye(a){this.h=a;this.h.Eb("/client_streamz/bg/el",{G:3,F:"en"},{G:3,F:"bk"},{G:3,F:"rk"},{G:3,F:"mk"})}
ye.prototype.record=function(a,b,c,d,e){this.h.record("/client_streamz/bg/el",a,b,c,d,e)};
function ze(a){this.h=a;this.h.Ra("/client_streamz/bg/cec",{G:2,F:"ec"},{G:3,F:"bk"},{G:3,F:"rk"},{G:3,F:"mk"})}
function Ae(a){this.h=a;this.h.Ra("/client_streamz/bg/po/csc",{G:2,F:"cs"},{G:3,F:"rk"},{G:3,F:"mk"})}
function Be(a){this.h=a;this.h.Ra("/client_streamz/bg/po/ctav",{G:3,F:"av"},{G:3,F:"rk"},{G:3,F:"mk"})}
function Ce(a){this.h=a;this.h.Ra("/client_streamz/bg/po/cwsc",{G:3,F:"su"},{G:3,F:"rk"},{G:3,F:"mk"})}
;Pc();var De=Sc()||H("iPod"),Ee=H("iPad");!H("Android")||Qc()||Pc()||Oc()||H("Silk");Qc();var Fe=H("Safari")&&!(Qc()||(Nc()?0:H("Coast"))||Oc()||(Nc()?0:H("Edge"))||(Nc()?Mc("Microsoft Edge"):H("Edg/"))||(Nc()?Mc("Opera"):H("OPR"))||Pc()||H("Silk")||H("Android"))&&!(Sc()||H("iPad")||H("iPod"));var Ge={},He=null;function Ie(a,b){Qa(a);b===void 0&&(b=0);Je();b=Ge[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function Ke(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;Le(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function Le(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=He[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
Je();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function Je(){if(!He){He={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));Ge[c]=d;for(var e=0;e<d.length;e++){var f=d[e];He[f]===void 0&&(He[f]=e)}}}}
;var Me=typeof Uint8Array!=="undefined",Ne=!Vc&&typeof btoa==="function";function Oe(a){if(!Ne)return Ie(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var Pe=/[-_.]/g,Qe={"-":"+",_:"/",".":"="};function Re(a){return Qe[a]||""}
function Se(a){return Me&&a!=null&&a instanceof Uint8Array}
var Te={};var Ue;function Ve(a){if(a!==Te)throw Error("illegal external caller");}
function We(a,b){Ve(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
We.prototype.sizeBytes=function(){Ve(Te);var a=this.h;if(a!=null&&!Se(a))if(typeof a==="string")if(Ne){Pe.test(a)&&(a=a.replace(Pe,Re));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=Ke(a);else Pa(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};function Xe(){return typeof BigInt==="function"}
;var Ye=0,Ze=0;function $e(a){var b=a<0;a=Math.abs(a);var c=a>>>0;a=Math.floor((a-c)/4294967296);b&&(c=v(af(c,a)),b=c.next().value,a=c.next().value,c=b);Ye=c>>>0;Ze=a>>>0}
function bf(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else Xe()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=Math.floor(a/1E7),a%=1E7),c>=1E7&&(b+=Math.floor(c/1E7),c%=1E7),c=b+cf(c)+cf(a));return c}
function cf(a){a=String(a);return"0000000".slice(a.length)+a}
function df(){var a=Ye,b=Ze;b&2147483648?Xe()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=v(af(a,b)),a=b.next().value,b=b.next().value,a="-"+bf(a,b)):a=bf(a,b);return a}
function af(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function ef(a){return Array.prototype.slice.call(a)}
;var ff=typeof Symbol==="function"&&typeof Symbol()==="symbol";function gf(a){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?Symbol():a}
var hf=gf(),jf=gf("0di"),kf=gf("2ex");Math.max.apply(Math,la(Object.values({vg:1,tg:2,sg:4,yg:8,xg:16,wg:32,Af:64,Ag:128,rg:256,qg:512,ug:1024,Ff:2048,zg:4096,Gf:8192})));var lf=ff?function(a,b){a[hf]|=b}:function(a,b){a.Ua!==void 0?a.Ua|=b:Object.defineProperties(a,{Ua:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function mf(a,b,c){return c?a|b:a&~b}
var nf=ff?function(a){return a[hf]|0}:function(a){return a.Ua|0},of=ff?function(a){return a[hf]}:function(a){return a.Ua},pf=hf?function(a,b){a[hf]=b;
return a}:function(a,b){a.Ua!==void 0?a.Ua=b:Object.defineProperties(a,{Ua:{value:b,
configurable:!0,writable:!0,enumerable:!1}});return a};
function qf(a){lf(a,34);return a}
function rf(a,b){pf(b,(a|0)&-14591)}
function sf(a,b){pf(b,(a|34)&-14557)}
function tf(a){a=a>>14&1023;return a===0?536870912:a}
;var uf={},vf={};function wf(a){return!(!a||typeof a!=="object"||a.se!==vf)}
function xf(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
var yf;function zf(a,b,c){if(!Array.isArray(a)||a.length)return!1;var d=nf(a);if(d&1)return!0;if(!(b&&(Array.isArray(b)?b.includes(c):b.has(c))))return!1;pf(a,d|1);return!0}
var Af,Bf=[];pf(Bf,55);Af=Object.freeze(Bf);function Cf(a){if(a&2)throw Error();}
function Df(a,b,c){this.j=0;this.h=a;this.i=b;this.thisArg=c}
Df.prototype.next=function(){if(this.j<this.h.length){var a=this.h[this.j++];return{done:!1,value:this.i?this.i.call(this.thisArg,a):a}}return{done:!0,value:void 0}};
Df.prototype[Symbol.iterator]=function(){return new Df(this.h,this.i,this.thisArg)};
function Ef(){}
Object.freeze(new function(){});
Object.freeze(new Ef);var Ff=Object.freeze(new Ef);var Gf;function Hf(a){a=Error(a);ec(a,"warning");return a}
;function If(a){return a.displayName||a.name||"unknown type name"}
function Jf(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+Pa(a)+": "+a);return a}
var Kf=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function Lf(a){var b=typeof a;return b==="number"?Number.isFinite(a):b!=="string"?!1:Kf.test(a)}
function Mf(a){if(typeof a!=="number")throw Hf("int32");if(!Number.isFinite(a))throw Hf("int32");return a|0}
function Nf(a){return a==null?a:Mf(a)}
function Of(a){if(a==null)return a;if(typeof a==="string"){if(!a)return;a=+a}if(typeof a==="number")return Number.isFinite(a)?a|0:void 0}
function Pf(a){if(a!=null){var b=!!b;if(!Lf(a))throw Hf("int64");a=typeof a==="string"?Qf(a):b?Rf(a):Sf(a)}return a}
function Tf(a){return a[0]==="-"?a.length<20?!0:a.length===20&&Number(a.substring(0,7))>-922337:a.length<19?!0:a.length===19&&Number(a.substring(0,6))<922337}
function Sf(a){Lf(a);a=Math.trunc(a);if(!Number.isSafeInteger(a)){$e(a);var b=Ye,c=Ze;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);b=c*4294967296+(b>>>0);a=a?-b:b}return a}
function Rf(a){Lf(a);a=Math.trunc(a);if(Number.isSafeInteger(a))a=String(a);else{var b=String(a);Tf(b)?a=b:($e(a),a=df())}return a}
function Qf(a){Lf(a);var b=Math.trunc(Number(a));if(Number.isSafeInteger(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));a.indexOf(".");if(!Tf(a)){if(a.length<16)$e(Number(a));else if(Xe())a=BigInt(a),Ye=Number(a&BigInt(4294967295))>>>0,Ze=Number(a>>BigInt(32)&BigInt(4294967295));else{b=+(a[0]==="-");Ze=Ye=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),Ze*=1E6,Ye=Ye*1E6+d,Ye>=4294967296&&(Ze+=Math.trunc(Ye/4294967296),Ze>>>=0,Ye>>>=0);b&&(b=v(af(Ye,Ze)),
a=b.next().value,b=b.next().value,Ye=a,Ze=b)}a=df()}return a}
function Uf(a){if(typeof a!=="string")throw Error();return a}
function Vf(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Wf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+If(b)+" but got "+(a&&If(a.constructor)));}
function Xf(a,b,c,d){if(a!=null&&typeof a==="object"&&a.Fc===uf)return a;if(!Array.isArray(a))return c?d&2?(a=b[jf])?b=a:(a=new b,qf(a.D),b=b[jf]=a):b=new b:b=void 0,b;var e=c=nf(a);e===0&&(e|=d&32);e|=d&2;e!==c&&pf(a,e);return new b(a)}
;var Yf;function Zf(a,b){nf(b);Yf=b;a=new a(b);Yf=void 0;return a}
function I(a,b,c){a==null&&(a=Yf);Yf=void 0;if(a==null){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-16760833|(b&1023)<<14)}else{if(!Array.isArray(a))throw Error("narr");d=nf(a);if(d&2048)throw Error("farr");if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error("mid");a:{c=a;var e=c.length;if(e){var f=e-1;if(xf(c[f])){d|=256;b=f-(+!!(d&512)-1);if(b>=1024)throw Error("pvtlmt");d=d&-16760833|(b&1023)<<14;break a}}if(b){b=Math.max(b,e-(+!!(d&512)-1));if(b>1024)throw Error("spvt");d=d&-16760833|(b&1023)<<
14}}}pf(a,d);return a}
;var $f=function(){try{var a=function(){return qa(Map,[],this.constructor)};
y(a,Map);Tc(new a);return!1}catch(b){return!0}}();
function ag(){this.h=new Map}
n=ag.prototype;n.get=function(a){return this.h.get(a)};
n.set=function(a,b){this.h.set(a,b);this.size=this.h.size;return this};
n.delete=function(a){a=this.h.delete(a);this.size=this.h.size;return a};
n.clear=function(){this.h.clear();this.size=this.h.size};
n.has=function(a){return this.h.has(a)};
n.entries=function(){return this.h.entries()};
n.keys=function(){return this.h.keys()};
n.values=function(){return this.h.values()};
n.forEach=function(a,b){return this.h.forEach(a,b)};
ag.prototype[Symbol.iterator]=function(){return this.entries()};
var bg=function(){function a(){return qa(Map,[],this.constructor)}
if($f)return Object.setPrototypeOf(ag.prototype,Map.prototype),Object.defineProperties(ag.prototype,{size:{value:0,configurable:!0,enumerable:!0,writable:!0}}),ag;y(a,Map);return a}();
function cg(a){return a}
function dg(a,b,c,d){c=c===void 0?cg:c;d=d===void 0?cg:d;var e=bg.call(this)||this;var f=nf(a);f|=64;pf(a,f);e.Ub=f;e.sc=b;e.Kb=c;e.Qc=e.sc?eg:d;for(var g=0;g<a.length;g++){var h=a[g],k=c(h[0],!1,!0),l=h[1];b?l===void 0&&(l=null):l=d(h[1],!1,!0,void 0,void 0,f);bg.prototype.set.call(e,k,l)}return e}
y(dg,bg);function fg(a){if(a.Ub&2)throw Error("Cannot mutate an immutable Map");}
function gg(a,b){b=b===void 0?hg:b;if(a.size!==0)return ig(a,b)}
function ig(a,b){b=b===void 0?hg:b;var c=[];a=bg.prototype.entries.call(a);for(var d;!(d=a.next()).done;)d=d.value,d[0]=b(d[0]),d[1]=b(d[1]),c.push(d);return c}
n=dg.prototype;n.clear=function(){fg(this);bg.prototype.clear.call(this)};
n.delete=function(a){fg(this);return bg.prototype.delete.call(this,this.Kb(a,!0,!1))};
n.entries=function(){var a=Array.from(bg.prototype.keys.call(this));return new Df(a,jg,this)};
n.keys=function(){return bg.prototype.keys.call(this)};
n.values=function(){var a=Array.from(bg.prototype.keys.call(this));return new Df(a,dg.prototype.get,this)};
n.forEach=function(a,b){var c=this;bg.prototype.forEach.call(this,function(d,e){a.call(b,c.get(e),e,c)})};
n.set=function(a,b){fg(this);a=this.Kb(a,!0,!1);return a==null?this:b==null?(bg.prototype.delete.call(this,a),this):bg.prototype.set.call(this,a,this.Qc(b,!0,!0,this.sc,!1,this.Ub))};
n.has=function(a){return bg.prototype.has.call(this,this.Kb(a,!1,!1))};
n.get=function(a){a=this.Kb(a,!1,!1);var b=bg.prototype.get.call(this,a);if(b!==void 0){var c=this.sc;return c?(c=this.Qc(b,!1,!0,c,this.Fg,this.Ub),c!==b&&bg.prototype.set.call(this,a,c),c):b}};
dg.prototype[Symbol.iterator]=function(){return this.entries()};
dg.prototype.toJSON=void 0;dg.prototype.se=vf;function eg(a,b,c,d,e,f){b&&Wf(a,d);a=Xf(a,d,c,f);e&&(a=kg(a));f&2&&nf(a.D);return a}
function hg(a){return a}
function jg(a){return[a,this.get(a)]}
;function lg(a,b){return mg(b)}
function mg(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a)if(Array.isArray(a)){if(zf(a,void 0,0))return}else{if(Se(a))return Oe(a);if(a instanceof We){var b=a.h;return b==null?"":typeof b==="string"?b:a.h=Oe(b)}if(a instanceof dg)return gg(a)}}return a}
;function ng(a,b,c){a=ef(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function og(a,b,c,d,e){if(a!=null){if(Array.isArray(a))a=zf(a,void 0,0)?void 0:e&&nf(a)&2?a:pg(a,b,c,d!==void 0,e);else if(xf(a)){var f={},g;for(g in a)f[g]=og(a[g],b,c,d,e);a=f}else a=b(a,d);return a}}
function pg(a,b,c,d,e){var f=d||c?nf(a):0;d=d?!!(f&32):void 0;a=ef(a);for(var g=0;g<a.length;g++)a[g]=og(a[g],b,c,d,e);c&&c(f,a);return a}
function qg(a){return og(a,rg,void 0,void 0,!1)}
function rg(a){return a.Fc===uf?a.toJSON():a instanceof dg?gg(a,qg):mg(a)}
;function sg(a,b,c){c=c===void 0?sf:c;if(a!=null){if(Me&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=nf(a);d&2||(b&&(b=d===0||!!(d&32)&&!(d&64||!(d&16))),a=b?pf(a,(d|34)&-12293):pg(a,sg,d&4?sf:c,!0,!0));return a}a.Fc===uf?(c=a.D,d=of(c),a=d&2?a:Zf(a.constructor,tg(c,d,!0))):a instanceof dg&&!(a.Ub&2)&&(c=qf(ig(a,sg)),a=new dg(c,a.sc,a.Kb,a.Qc));return a}}
function tg(a,b,c){var d=c||b&2?sf:rf,e=!!(b&32);a=ng(a,b,function(f){return sg(f,e,d)});
lf(a,32|(c?2:0));return a}
function kg(a){var b=a.D,c=of(b);return c&2?Zf(a.constructor,tg(b,c,!1)):a}
;function ug(a,b){a=a.D;return vg(a,of(a),b)}
function wg(a,b,c,d){b=d+(+!!(b&512)-1);if(!(b<0||b>=a.length||b>=c))return a[b]}
function vg(a,b,c,d){if(c===-1)return null;var e=tf(b);if(c>=e){if(b&256)return a[a.length-1][c]}else{var f=a.length;if(d&&b&256&&(d=a[f-1][c],d!=null)){if(wg(a,b,e,c)&&kf!=null){var g;a=(g=Gf)!=null?g:Gf={};g=a[kf]||0;g>=4||(a[kf]=g+1,g=Error(),ec(g,"incident"),Kd(g))}return d}return wg(a,b,e,c)}}
function J(a,b,c){var d=a.D,e=of(d);Cf(e);xg(d,e,b,c);return a}
function xg(a,b,c,d,e){xf(d);var f=tf(b);if(c>=f||e){var g=b;if(b&256)e=a[a.length-1];else{if(d==null)return g;e=a[f+(+!!(b&512)-1)]={};g|=256}e[c]=d;c<f&&(a[c+(+!!(b&512)-1)]=void 0);g!==b&&pf(a,g);return g}a[c+(+!!(b&512)-1)]=d;b&256&&(a=a[a.length-1],c in a&&delete a[c]);return b}
function yg(a){return zg(a,Ag,11,!1)!==void 0}
function Bg(a){return!!(2&a)&&!!(4&a)||!!(2048&a)}
function Cg(a,b,c){var d=a.D,e=of(d);Cf(e);if(b==null)return xg(d,e,3),a;if(!Array.isArray(b))throw Hf();var f=nf(b),g=f,h=!!(2&f)||Object.isFrozen(b),k=!h&&(void 0===Ff||!1);if(!(4&f))for(f=21,h&&(b=ef(b),g=0,f=Dg(f,e),f=Eg(f,e,!0)),h=0;h<b.length;h++)b[h]=c(b[h]);k&&(b=ef(b),g=0,f=Dg(f,e),f=Eg(f,e,!0));f!==g&&pf(b,f);xg(d,e,3,b);return a}
function Fg(a,b,c,d){a=a.D;var e=of(a);Cf(e);if(d!=null){c.includes(b);var f=e;var g=c.Oc||(c.Oc=gf("o_"+c[0])),h=a[g];if(h!=null)h&&vg(a,f,h)==null?(Gg(g,a,0),f=0):f=h;else{h=0;for(var k=c.length-1;k>=0;k--){var l=c[k];h===0&&vg(a,f,l)!=null?h=l:h!==0&&(f=xg(a,f,l))}Gg(g,a,h);f=h}f!==b&&(f&&(e=xg(a,e,f)),Gg(c.Oc||(c.Oc=gf("o_"+c[0])),a,b))}xg(a,e,b,d)}
function Gg(a,b,c){ff||a in b?b[a]=c:Object.defineProperty(b,a,{value:c,writable:!0})}
function zg(a,b,c,d){a=a.D;var e=of(a),f=vg(a,e,c,d);b=Xf(f,b,!1,e);b!==f&&b!=null&&xg(a,e,c,b,d);return b}
function Hg(a,b,c,d){d=d===void 0?!1:d;b=zg(a,b,c,d);if(b==null)return b;a=a.D;var e=of(a);if(!(e&2)){var f=kg(b);f!==b&&(b=f,xg(a,e,c,b,d))}return b}
function Ig(a,b,c,d){d!=null?Wf(d,b):d=void 0;return J(a,c,d)}
function Jg(a,b,c,d){var e=a.D,f=of(e);Cf(f);if(d==null)return xg(e,f,c),a;if(!Array.isArray(d))throw Hf();for(var g=nf(d),h=g,k=!!(2&g)||!!(2048&g),l=k||Object.isFrozen(d),m=!l&&(void 0===Ff||!1),p=!0,r=!0,t=0;t<d.length;t++){var w=d[t];Wf(w,b);k||(w=!!(nf(w.D)&2),p&&(p=!w),r&&(r=w))}k||(g=mf(g,5,!0),g=mf(g,8,p),g=mf(g,16,r));if(m||l&&g!==h)d=ef(d),h=0,g=Dg(g,f),g=Eg(g,f,!0);g!==h&&pf(d,g);xg(e,f,c,d);return a}
function Dg(a,b){a=mf(a,2,!!(2&b));a=mf(a,32,!0);return a=mf(a,2048,!1)}
function Eg(a,b,c){32&b&&c||(a=mf(a,32,!1));return a}
function Kg(a,b){a=ug(a,b);var c;a==null?c=a:Lf(a)?typeof a==="number"?c=Sf(a):c=Qf(a):c=void 0;return c}
function Lg(a){a=ug(a,1);var b=b===void 0?!1:b;b=a==null?a:Lf(a)?typeof a==="string"?Qf(a):b?Rf(a):Sf(a):void 0;return b}
function Mg(a){var b=0;b=b===void 0?0:b;a=ug(a,1);a=a==null?a:Number.isFinite(a)?a|0:void 0;return a!=null?a:b}
function Ng(a,b,c){return J(a,b,Vf(c))}
function Og(a,b,c){if(c!=null){if(!Number.isFinite(c))throw Hf("enum");c|=0}return J(a,b,c)}
;function L(a,b,c){this.D=I(a,b,c)}
n=L.prototype;n.toJSON=function(){if(yf)var a=Pg(this,this.D,!1);else a=pg(this.D,rg,void 0,void 0,!1),a=Pg(this,a,!0);return a};
n.serialize=function(){yf=!0;try{return JSON.stringify(this.toJSON(),lg)}finally{yf=!1}};
function Sg(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");lf(b,32);return Zf(a,b)}
n.clone=function(){var a=this.D,b=of(a);return Zf(this.constructor,tg(a,b,!1))};
n.Fc=uf;n.toString=function(){return Pg(this,this.D,!1).toString()};
function Pg(a,b,c){var d=Ic?void 0:a.constructor.Qa;var e=of(c?a.D:b);a=b.length;if(!a)return b;var f;if(xf(c=b[a-1])){a:{var g=c;var h={},k=!1,l;for(l in g){var m=g[l];if(Array.isArray(m)){var p=m;if(zf(m,d,+l)||wf(m)&&m.size===0)m=null;m!=p&&(k=!0)}m!=null?h[l]=m:k=!0}if(k){for(var r in h){g=h;break a}g=null}}g!=c&&(f=!0);a--}for(l=+!!(e&512)-1;a>0;a--){r=a-1;c=b[r];r-=l;if(!(c==null||zf(c,d,r)||wf(c)&&c.size===0))break;var t=!0}if(!f&&!t)return b;b=Array.prototype.slice.call(b,0,a);g&&b.push(g);
return b}
;Object.freeze({});function Tg(a){a.Lg=!0;return a}
;function Ug(a){this.D=I(a)}
y(Ug,L);Ug.Qa=[1,2,3,4];var Vg={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);a>0;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function Wg(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=Xg(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;g>=12;g-=12,h+=12)c+=Yg(a,h),d+=Yg(a,h+4),e+=Yg(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return Vg.toString(e)}
function Xg(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function Yg(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;function Zg(a){this.D=I(a)}
y(Zg,L);var $g=[1,2,3];function ah(a){this.D=I(a)}
y(ah,L);var bh=[1,2,3];function ch(a){this.D=I(a)}
y(ch,L);ch.Qa=[1];function dh(a){this.D=I(a)}
y(dh,L);dh.Qa=[3,6,4];function eh(a){this.D=I(a)}
y(eh,L);eh.Qa=[1];function fh(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function gh(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(p){for(var r=g,t=0;t<64;t+=4)r[t/4]=p[t]<<24|p[t+1]<<16|p[t+2]<<8|p[t+3];for(t=16;t<80;t++)p=r[t-3]^r[t-8]^r[t-14]^r[t-16],r[t]=(p<<1|p>>>31)&4294967295;p=e[0];var w=e[1],x=e[2],C=e[3],F=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var K=C^w&(x^C);var N=1518500249}else K=w^x^C,N=1859775393;else t<60?(K=w&x|C&(w|x),N=2400959708):(K=w^x^C,N=3395469782);K=((p<<5|p>>>27)&4294967295)+K+F+N+r[t]&4294967295;F=C;C=x;x=(w<<30|w>>>2)&4294967295;w=p;p=K}e[0]=e[0]+p&4294967295;e[1]=e[1]+w&4294967295;e[2]=
e[2]+x&4294967295;e[3]=e[3]+C&4294967295;e[4]=e[4]+F&4294967295}
function c(p,r){if(typeof p==="string"){p=unescape(encodeURIComponent(p));for(var t=[],w=0,x=p.length;w<x;++w)t.push(p.charCodeAt(w));p=t}r||(r=p.length);t=0;if(l==0)for(;t+64<r;)b(p.slice(t,t+64)),t+=64,m+=64;for(;t<r;)if(f[l++]=p[t++],m++,l==64)for(l=0,b(f);t+64<r;)b(p.slice(t,t+64)),t+=64,m+=64}
function d(){var p=[],r=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=r&255,r>>>=8;b(f);for(t=r=0;t<5;t++)for(var w=24;w>=0;w-=8)p[r++]=e[t]>>w&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Td:function(){for(var p=d(),r="",t=0;t<p.length;t++)r+="0123456789ABCDEF".charAt(Math.floor(p[t]/16))+"0123456789ABCDEF".charAt(p[t]%16);return r}}}
;function hh(a,b,c){var d=String(B.location.href);return d&&a&&b?[b,ih(fh(d),a,c||null)].join(" "):null}
function ih(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Db(d,function(h){e.push(h)}),jh(e.join(" "));
var f=[],g=[];Db(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Db(d,function(h){e.push(h)});
a=jh(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function jh(a){var b=gh();b.update(a);return b.Td().toLowerCase()}
;var kh={};function lh(a){this.h=a||{cookie:""}}
n=lh.prototype;n.isEnabled=function(){if(!B.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Nb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
n.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.Me;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Nb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
n.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=db(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
n.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Nb:0,path:b,domain:c});return d};
n.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=db(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var mh=new lh(typeof document=="undefined"?null:document);function nh(a){return!!kh.FPA_SAMESITE_PHASE2_MOD||!(a===void 0||!a)}
function oh(a){a=a===void 0?!1:a;var b=B.__SAPISID||B.__APISID||B.__3PSAPISID||B.__OVERRIDE_SID;nh(a)&&(b=b||B.__1PSAPISID);if(b)return!0;if(typeof document!=="undefined"){var c=new lh(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID");nh(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function ph(a,b,c,d){(a=B[a])||typeof document==="undefined"||(a=(new lh(document)).get(b));return a?hh(a,c,d):null}
function qh(a,b){b=b===void 0?!1:b;var c=fh(String(B.location.href)),d=[];if(oh(b)){c=c.indexOf("https:")==0||c.indexOf("chrome-extension:")==0||c.indexOf("moz-extension:")==0;var e=c?B.__SAPISID:B.__APISID;e||typeof document==="undefined"||(e=new lh(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?hh(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&nh(b)&&((b=ph("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=ph("__3PSAPISID","__Secure-3PAPISID",
"SAPISID3PHASH",a))&&d.push(a))}return d.length==0?null:d.join(" ")}
;function rh(a){this.D=I(a)}
y(rh,L);rh.Qa=[2];function sh(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return Za()};
this.i=this.h()}
sh.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
sh.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
sh.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
sh.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function th(a){this.D=I(a)}
y(th,L);function uh(a){this.D=I(a)}
y(uh,L);function vh(a){this.h=this.i=this.j=a}
vh.prototype.reset=function(){this.h=this.i=this.j};
vh.prototype.getValue=function(){return this.i};function wh(a){this.D=I(a)}
y(wh,L);wh.prototype.ec=function(){return Mg(this)};function xh(a){this.D=I(a)}
y(xh,L);function yh(a){this.D=I(a)}
y(yh,L);function zh(a,b){Jg(a,xh,1,b)}
yh.Qa=[1];function Ag(a){this.D=I(a)}
y(Ag,L);var Ah=["platform","platformVersion","architecture","model","uaFullVersion"],Bh=new yh,Ch=null;function Dh(a,b){b=b===void 0?Ah:b;if(!Ch){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new xh;f=Ng(f,1,e.brand);return Ng(f,2,e.version)});
zh(J(Bh,2,Jf(a.mobile)),c);Ch=a.getHighEntropyValues(b)}var d=new Set(b);return Ch.then(function(e){var f=Bh.clone();d.has("platform")&&Ng(f,3,e.platform);d.has("platformVersion")&&Ng(f,4,e.platformVersion);d.has("architecture")&&Ng(f,5,e.architecture);d.has("model")&&Ng(f,6,e.model);d.has("uaFullVersion")&&Ng(f,7,e.uaFullVersion);return f}).catch(function(){return Bh.clone()})}
;function Eh(a){this.D=I(a)}
y(Eh,L);function Fh(a){this.D=I(a,4)}
y(Fh,L);function Gh(a){this.D=I(a,35)}
y(Gh,L);Gh.Qa=[3,20,27];function Hh(a){this.D=I(a,19)}
y(Hh,L);Hh.prototype.Qb=function(a){return Og(this,2,a)};
Hh.Qa=[3,5];function Ih(a){this.D=I(a,8)}
y(Ih,L);var Jh=function(a){return function(b){return Sg(a,b)}}(Ih);
Ih.Qa=[5,6,7];function Kh(a){this.D=I(a)}
y(Kh,L);var Lh;Lh=new function(a,b){this.h=a;this.ctor=b;this.isRepeated=0;this.i=Hg;this.defaultValue=void 0}(175237375,Kh);function Mh(a){G.call(this);var b=this;this.componentId="";this.j=[];this.da="";this.pageId=null;this.ga=this.W=-1;this.experimentIds=null;this.P=this.m=0;this.ia=1;this.timeoutMillis=0;this.logSource=a.logSource;this.Jb=a.Jb||function(){};
this.i=new Nh(a.logSource,a.eb);this.network=a.network;this.yb=a.yb||null;this.bufferSize=1E3;this.A=a.lf||null;this.sessionIndex=a.sessionIndex||null;this.Hb=a.Hb||!1;this.logger=null;this.withCredentials=!a.bd;this.eb=a.eb||!1;this.H=typeof URLSearchParams!=="undefined"&&!!(new URL(Oh())).searchParams&&!!(new URL(Oh())).searchParams.set;var c=Og(new Eh,1,1);Ph(this.i,c);this.l=new vh(1E4);a=Qh(this,a.Uc);this.h=new sh(this.l.getValue(),a);this.ba=new sh(6E5,a);this.Hb||this.ba.start();this.eb||
(document.addEventListener("visibilitychange",function(){document.visibilityState==="hidden"&&b.xc()}),document.addEventListener("pagehide",this.xc.bind(this)))}
y(Mh,G);function Qh(a,b){return a.H?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
n=Mh.prototype;n.U=function(){this.xc();this.h.stop();this.ba.stop();G.prototype.U.call(this)};
n.log=function(a){if(this.H){a=a.clone();var b=this.ia++;a=J(a,21,Pf(b));this.componentId&&Ng(a,26,this.componentId);if(Lg(a)==null){var c=Date.now();b=a;c=Number.isFinite(c)?c.toString():"0";J(b,1,Pf(c))}Kg(a,15)==null&&J(a,15,Pf((new Date).getTimezoneOffset()*60));this.experimentIds&&(b=a,c=this.experimentIds.clone(),Ig(b,rh,16,c));b=this.j.length-this.bufferSize+1;b>0&&(this.j.splice(0,b),this.m+=b);this.j.push(a);this.Hb||this.h.enabled||this.h.start()}};
n.flush=function(a,b){var c=this;if(this.j.length===0)a&&a();else{var d=Date.now();if(this.ga>d&&this.W<d)b&&b("throttled");else{this.network&&(typeof this.network.ec==="function"?Rh(this.i,this.network.ec()):Rh(this.i,0));var e=Sh(this.i,this.j,this.m,this.P,this.yb);d={};var f=this.Jb();f&&(d.Authorization=f);this.A||(this.A=Oh());try{var g=(new URL(this.A)).toString()}catch(k){g=(new URL(this.A,window.location.origin)).toString()}g=new URL(g);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,
g.searchParams.set("authuser",this.sessionIndex));this.pageId&&(Object.defineProperty(d,"X-Goog-PageId",{value:this.pageId}),g.searchParams.set("pageId",this.pageId));if(f&&this.da===f)b&&b("stale-auth-token");else{this.j=[];this.h.enabled&&this.h.stop();this.m=0;var h=e.serialize();d={url:g.toString(),body:h,Dg:1,td:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis};g=function(k){c.l.reset();c.h.setInterval(c.l.getValue());if(k){var l=null;try{var m=JSON.stringify(JSON.parse(k.replace(")]}'\n",
"")));l=Jh(m)}catch(r){}if(l){k=Number;m="-1";m=m===void 0?"0":m;var p=Lg(l);k=k(p!=null?p:m);k>0&&(c.W=Date.now(),c.ga=c.W+k);l=Lh.ctor?Lh.i(l,Lh.ctor,Lh.h,!0):Lh.i(l,Lh.h,null,!0);if(k=l===null?void 0:l)l=-1,l=l===void 0?0:l,k=Of(ug(k,1)),l=k!=null?k:l,l!==-1&&(c.l=new vh(l<1?1:l),c.h.setInterval(c.l.getValue()))}}a&&a();c.P=0};
h=function(k,l){var m=e.D;var p=of(m),r=p,t=!(2&p),w=!!(2&r);p=w?1:2;t&&(t=!w);w=vg(m,r,3);w=Array.isArray(w)?w:Af;var x=nf(w),C=!!(4&x);if(!C){var F=x;F===0&&(F=Dg(F,r));F=mf(F,1,!0);x=w;var K=r,N=!!(2&F);N&&(K=mf(K,2,!0));for(var S=!N,da=!0,va=0,P=0;va<x.length;va++){var ea=Xf(x[va],Gh,!1,K);if(ea instanceof Gh){if(!N){var na=!!(nf(ea.D)&2);S&&(S=!na);da&&(da=na)}x[P++]=ea}}P<va&&(x.length=P);F=mf(F,4,!0);F=mf(F,16,da);F=mf(F,8,S);pf(x,F);N&&Object.freeze(x);x=F}if(t&&!(8&x||!w.length&&(p===1||
p===4&&32&x))){Bg(x)&&(w=ef(w),x=Dg(x,r),r=xg(m,r,3,w));t=w;for(F=0;F<t.length;F++)K=t[F],N=kg(K),K!==N&&(t[F]=N);x=mf(x,8,!0);x=mf(x,16,!t.length);pf(t,x)}Bg(x)||(t=x,(F=p===1||p===4&&!!(32&x))?(K=!!(32&x),x=mf(x,!w.length||16&x&&(!C||K)?2:2048,!0)):x=Eg(x,r,!1),x!==t&&pf(w,x),F&&Object.freeze(w));p===2&&Bg(x)&&(w=ef(w),x=Dg(x,r),x=Eg(x,r,!1),pf(w,x),xg(m,r,3,w));m=w;r=Kg(e,14);p=c.l;p.h=Math.min(3E5,p.h*2);p.i=Math.min(3E5,p.h+Math.round((Math.random()-.5)*.2*p.h));c.h.setInterval(c.l.getValue());
k===401&&f&&(c.da=f);r&&(c.m+=r);l===void 0&&(l=c.isRetryable(k));l&&(c.j=m.concat(c.j),c.Hb||c.h.enabled||c.h.start());b&&b("net-send-failed",k);++c.P};
c.network&&c.network.send(d,g,h)}}}};
n.xc=function(){Th(this.i,!0);this.flush();Th(this.i,!1)};
n.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function Oh(){return"https://play.google.com/log?format=json&hasfast=true"}
function Nh(a,b){this.eb=b=b===void 0?!1:b;this.i=this.locale=null;this.h=new Hh;Number.isInteger(a)&&this.h.Qb(a);b||(this.locale=document.documentElement.getAttribute("lang"));Ph(this,new Eh)}
Nh.prototype.Qb=function(a){this.h.Qb(a);return this};
function Ph(a,b){Ig(a.h,Eh,1,b);Mg(b)||Og(b,1,1);if(!a.eb){b=Uh(a);var c=c===void 0?"":c;var d=ug(b,5);d=d==null||typeof d==="string"?d:void 0;(d!=null?d:c)||Ng(b,5,a.locale)}a.i&&(c=Uh(a),Hg(c,yh,9)||Ig(c,yh,9,a.i))}
function Rh(a,b){yg(Vh(a))&&(a=Wh(a),Og(a,1,b))}
function Th(a,b){yg(Vh(a))&&(a=Wh(a),J(a,2,Jf(b)))}
function Vh(a){return Hg(a.h,Eh,1)}
function Xh(a){var b=b===void 0?Ah:b;var c=a.eb?void 0:window;c?Dh(c,b).then(function(d){a.i=d;d=Uh(a);Ig(d,yh,9,a.i);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function Uh(a){a=Vh(a);var b=Hg(a,Ag,11);b||(b=new Ag,Ig(a,Ag,11,b));return b}
function Wh(a){a=Uh(a);var b=Hg(a,wh,10);b||(b=new wh,J(b,2,Jf(!1)),Ig(a,wh,10,b));return b}
function Sh(a,b,c,d,e){var f=0,g=0;c=c===void 0?0:c;f=f===void 0?0:f;g=g===void 0?0:g;d=d===void 0?0:d;if(yg(Vh(a))){var h=Wh(a);J(h,3,Nf(d))}yg(Vh(a))&&(d=Wh(a),J(d,4,Nf(f)));yg(Vh(a))&&(f=Wh(a),J(f,5,Nf(g)));a=a.h.clone();g=Date.now().toString();a=J(a,4,Pf(g));b=b.slice();b=Jg(a,Gh,3,b);e&&(a=new th,e=J(a,13,Nf(e)),a=new uh,e=Ig(a,th,2,e),a=new Fh,e=Ig(a,uh,1,e),e=Og(e,2,9),Ig(b,Fh,18,e));c&&J(b,14,Pf(c));return b}
;function Yh(){this.Kd=typeof AbortController!=="undefined"}
Yh.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,p,r,t;return z(function(w){switch(w.h){case 1:return f=(e=d.Kd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,Aa(w,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.td)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),w.yield(fetch(a.url,g),5);case 5:h=w.i;if(h.status!==200){(k=c)==null||k(h.status);w.B(3);break}if((l=b)==null){w.B(7);break}return w.yield(h.text(),8);case 8:l(w.i);case 7:case 3:w.P=[w.j];w.l=0;w.v=0;clearTimeout(f);Ca(w);break;case 2:m=Ba(w);switch((p=m)==null?void 0:p.name){case "AbortError":(r=c)==null||r(408);break;default:(t=c)==null||t(400)}w.B(3)}})};
Yh.prototype.ec=function(){return 4};function Zh(a,b){G.call(this);this.logSource=a;this.sessionIndex=b;this.j="https://play.google.com/log?format=json&hasfast=true";this.h=null;this.l=!1;this.network=null;this.componentId="";this.pageId=this.i=this.yb=null}
y(Zh,G);Zh.prototype.bd=function(){this.m=!0;return this};
function $h(a){a.network||(a.network=new Yh);var b=new Mh({logSource:a.logSource,Jb:a.Jb?a.Jb:qh,sessionIndex:a.sessionIndex,lf:a.j,eb:a.l,Hb:!1,bd:a.m,Uc:a.Uc,network:a.network});Ec(a,b);if(a.h){var c=a.h,d=Uh(b.i);Ng(d,7,c)}a.componentId&&(b.componentId=a.componentId);a.yb&&(b.yb=a.yb);a.pageId&&(b.pageId=a.pageId);a.i&&((d=a.i)?(b.experimentIds||(b.experimentIds=new rh),c=b.experimentIds,d=d.serialize(),Ng(c,4,d)):b.experimentIds&&J(b.experimentIds,4));Xh(b.i);a.network.Qb&&a.network.Qb(a.logSource);
a.network.Xe&&a.network.Xe(b);return b}
;function ai(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;G.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new Zh(a,"0"),a.componentId=b,Ec(this,a),c!==""&&(a.j=c),d&&(a.l=!0),e&&(a.h=e),g&&(a.network=g),b=$h(a));this.h=b}
y(ai,G);
ai.prototype.flush=function(a){var b=a||[];if(b.length){a=new eh;for(var c=[],d=0;d<b.length;d++){var e=b[d];var f=new dh;f=Ng(f,1,e.l);for(var g=[],h=0;h<e.fields.length;h++)g.push(e.fields[h].F);f=Cg(f,g,Uf);g=[];h=[];for(var k=v(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.j;for(var p=e.yc(l)||[],r=[],t=0;t<p.length;t++){var w=p[t],x=w&&w.h;w=new ah;switch(m){case 3:x=Number(x);Number.isFinite(x)&&Fg(w,1,bh,Pf(x));break;case 2:x=Number(x);
if(x!=null&&typeof x!=="number")throw Error("Value of float/double field must be a number, found "+typeof x+": "+x);Fg(w,2,bh,x)}r.push(w)}m=r;for(p=0;p<m.length;p++){r=m[p];t=new ch;r=Ig(t,ah,2,r);t=l;w=[];x=[];for(var C=0;C<e.fields.length;C++)x.push(e.fields[C].G);for(C=0;C<x.length;C++){var F=x[C],K=t[C],N=new Zg;switch(F){case 3:Fg(N,1,$g,Vf(String(K)));break;case 2:F=Number(K);Number.isFinite(F)&&Fg(N,2,$g,Nf(F));break;case 1:Fg(N,3,$g,Jf(K==="true"))}w.push(N)}Jg(r,Zg,1,w);g.push(r)}}Jg(f,
ch,4,g);c.push(f);e.clear()}Jg(a,dh,1,c);b=this.h;b.H&&(a instanceof Gh?b.log(a):(c=new Gh,a=a.serialize(),a=Ng(c,8,a),b.log(a)));this.h.flush()}};function bi(){}
bi.prototype.serialize=function(a){var b=[];ci(this,a,b);return b.join("")};
function ci(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),ci(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),di(d,c),c.push(":"),ci(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":di(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var ei={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},fi=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function di(a,b){b.push('"',a.replace(fi,function(c){var d=ei[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),ei[c]=d);return d}),'"')}
;function gi(){}
gi.prototype.h=null;gi.prototype.getOptions=function(){var a;(a=this.h)||(a=this.h={});return a};var hi;function ii(){}
$a(ii,gi);hi=new ii;function ji(a){wd.call(this);this.headers=new Map;this.Ga=a||null;this.i=!1;this.P=this.T=null;this.l=this.da="";this.j=this.ba=this.m=this.W=!1;this.H=0;this.A=null;this.xa="";this.ia=!1}
$a(ji,wd);var ki=/^https?$/i,li=["POST","PUT"],mi=[];function ni(a,b,c,d,e,f,g){var h=new ji;mi.push(h);b&&h.listen("complete",b);h.h.add("ready",h.Rd,!0,void 0,void 0);f&&(h.H=Math.max(0,f));g&&(h.ia=g);h.send(a,c,d,e)}
n=ji.prototype;n.Rd=function(){this.dispose();Ib(mi,this)};
n.send=function(a,b,c,d){if(this.T)throw Error("[goog.net.XhrIo] Object is active with another request="+this.da+"; newUri="+a);b=b?b.toUpperCase():"GET";this.da=a;this.l="";this.W=!1;this.i=!0;this.T=new XMLHttpRequest;this.P=this.Ga?this.Ga.getOptions():hi.getOptions();this.T.onreadystatechange=Xa(this.nd,this);try{this.getStatus(),this.ba=!0,this.T.open(b,String(a),!0),this.ba=!1}catch(g){this.getStatus();oi(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if(typeof d.keys==="function"&&typeof d.get==="function"){e=v(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=B.FormData&&a instanceof B.FormData;!(Cb(li,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=v(c);for(d=b.next();!d.done;d=b.next())c=v(d.value),d=c.next().value,c=c.next().value,this.T.setRequestHeader(d,c);this.xa&&(this.T.responseType=this.xa);"withCredentials"in this.T&&this.T.withCredentials!==this.ia&&(this.T.withCredentials=this.ia);try{pi(this),this.H>0&&(this.getStatus(),this.A=le(this.hf,this.H,this)),this.getStatus(),this.m=!0,this.T.send(a),this.m=
!1}catch(g){this.getStatus(),oi(this,g)}};
n.hf=function(){typeof Na!="undefined"&&this.T&&(this.l="Timed out after "+this.H+"ms, aborting",this.getStatus(),xd(this,"timeout"),this.abort(8))};
function oi(a,b){a.i=!1;a.T&&(a.j=!0,a.T.abort(),a.j=!1);a.l=b;qi(a);ri(a)}
function qi(a){a.W||(a.W=!0,xd(a,"complete"),xd(a,"error"))}
n.abort=function(){this.T&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.T.abort(),this.j=!1,xd(this,"complete"),xd(this,"abort"),ri(this))};
n.U=function(){this.T&&(this.i&&(this.i=!1,this.j=!0,this.T.abort(),this.j=!1),ri(this,!0));ji.Ba.U.call(this)};
n.nd=function(){this.V||(this.ba||this.m||this.j?si(this):this.Ae())};
n.Ae=function(){si(this)};
function si(a){if(a.i&&typeof Na!="undefined")if(a.P[1]&&ti(a)==4&&a.getStatus()==2)a.getStatus();else if(a.m&&ti(a)==4)le(a.nd,0,a);else if(xd(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(ui(a))xd(a,"complete"),xd(a,"success");else{try{var b=ti(a)>2?a.T.statusText:""}catch(c){b=""}a.l=b+" ["+a.getStatus()+"]";qi(a)}}finally{ri(a)}}}
function ri(a,b){if(a.T){pi(a);var c=a.T,d=a.P[0]?function(){}:null;
a.T=null;a.P=null;b||xd(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function pi(a){a.A&&(B.clearTimeout(a.A),a.A=null)}
n.isActive=function(){return!!this.T};
n.isComplete=function(){return ti(this)==4};
function ui(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=nc(1,String(a.da)),!a&&B.self&&B.self.location&&(a=B.self.location.protocol.slice(0,-1)),b=!ki.test(a?a.toLowerCase():"");c=b}return c}
function ti(a){return a.T?a.T.readyState:0}
n.getStatus=function(){try{return ti(this)>2?this.T.status:-1}catch(a){return-1}};
n.getLastError=function(){return typeof this.l==="string"?this.l:String(this.l)};function vi(){}
vi.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
ni(a.url,function(d){d=d.target;if(ui(d)){try{var e=d.T?d.T.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.td,a.timeoutMillis,a.withCredentials)};
vi.prototype.ec=function(){return 1};function wi(a,b,c){this.logger=a;this.event=b;if(c===void 0||c)this.h=xi()}
wi.prototype.start=function(){this.h=xi()};
wi.prototype.done=function(){this.h!=null&&this.logger.jc(this.event,xi()-this.h)};
function yi(){}
yi.prototype.Cc=function(){};
yi.prototype.jc=function(){};
yi.prototype.Ha=function(){};
yi.prototype.Aa=function(){};
function zi(a,b,c,d,e){d=d===void 0?"":d;G.call(this);this.Ea=b;this.A=d;this.i=new Map;this.j=new Map;b=new Zh(1828,"0");b.h="21";b.network=new vi;e&&(d=new Ug,e=Cg(d,e,Mf),b.i=e);this.m=new ai(1828,"","",!1,"",$h(b));this.h=new me(this.m);c&&(this.h.l=1E5,c=this.h,c.flushInterval=3E4,c.h.setInterval(3E4));this.da=new se(this.h);this.ga=new ve(this.h);this.ia=new we(this.h);this.ba=new re(this.h);this.H=new te(this.h);this.P=new ue(this.h);this.errorCount=new ze(this.h);this.W=new ye(this.h);new xe(this.h);
new Ae(this.h);new Be(this.h);new Ce(this.h);this.l=Wg(a);a=new qe(this.h);this.i.set("h",1);this.i.set("u",2);this.i.set("k",3);this.i.set("P",4);this.i.set("p",5);this.j.set(25,1);this.j.set(26,2);this.j.set(27,3);this.j.set(28,4);a.h.Ab("/client_streamz/bg/fic",this.Ea);Ec(this,this.m);Ec(this,this.h)}
y(zi,G);zi.prototype.Cc=function(){this.ga.h.Ab("/client_streamz/bg/fsc",this.l,this.Ea)};
zi.prototype.jc=function(a,b){if(a==="t")this.da.record(b,this.l,this.Ea);else if(a==="n")this.ia.record(b,this.l,this.Ea);else if(a==="h"||a==="u"||a==="k"||a==="P"||a==="p"){if(a=this.i.get(a))this.H.h.Ab("/client_streamz/bg/fcc",a,this.Ea),this.P.record(b,a,this.Ea)}else this.W.record(b,a,"",this.A,this.Ea)};
zi.prototype.Ha=function(a){var b=this.j.get(a);b?this.ba.h.Ab("/client_streamz/bg/fiec",this.l,this.Ea,b):this.errorCount.h.Ab("/client_streamz/bg/cec",a,"",this.A,this.Ea)};
zi.prototype.Aa=function(){this.h.Aa()};
function xi(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function Ai(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Bi(a){function b(t,w,x){Promise.resolve().then(function(){p.done();d.h&&d.ea.Aa();m.resolve({Nd:t,af:w,Rg:x})})}
function c(t,w,x,C){if(h){var F="k";w?F="h":x&&(F="u");F!=="k"?C!==0&&d.ea.jc(F,t):d.i<=0?(d.ea.jc(F,t),d.i=Math.floor(Math.random()*200)):d.i--}}
G.call(this);var d=this;this.h=!1;this.i=Math.floor(Math.random()*200);var e=a.program;var f=a.ge;var g=Math.random(),h=g<.3;a.Pd!=null&&(h=g<a.Pd);h&&(this.h=!0);var k=new G;this.addOnDisposeCallback(function(){d.j.then(function(t){t=t.af;d.ea.Aa();t==null||t();k.dispose()})});
if(a.Ge!==!1)if(a.ea)this.ea=a.ea;else{var l;Ec(k,this.ea=new zi(f,(l=a.Ea)!=null?l:"_",this.h))}else this.ea=new yi;var m=new Ai;this.j=m.promise;var p=new wi(this.ea,"t",!1);if(!B[f])throw this.ea.Ha(25),this.ea.Aa(),Error("EGOU");if(!B[f].a)throw this.ea.Ha(26),this.ea.Aa(),Error("ELIU");try{var r=B[f].a;p.start();this.l=v(r(e,b,!0,a.bh,c)).next().value;this.Ze=m.promise.then(function(){})}catch(t){throw this.ea.Ha(28),this.ea.Aa(),t;
}}
y(Bi,G);Bi.prototype.snapshot=function(a){var b=this;if(this.V)throw Error("Already disposed");this.ea.Cc();return this.j.then(function(c){var d=c.Nd;return new Promise(function(e){var f=new wi(b.ea,"n");d(function(g){f.done();b.h&&b.ea.Aa();e(g)},[a.Zc,
a.bf,a.nf,a.cf])})})};
Bi.prototype.zd=function(a){if(this.V)throw Error("Already disposed");this.ea.Cc();var b=new wi(this.ea,"n");a=this.l([a.Zc,a.bf,a.nf,a.cf]);b.done();this.h&&this.ea.Aa();return a};var Ci=window;ib("csi.gstatic.com");ib("googleads.g.doubleclick.net");ib("partner.googleadservices.com");ib("pubads.g.doubleclick.net");ib("securepubads.g.doubleclick.net");ib("tpc.googlesyndication.com");function Di(a){var b=Ei;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Fi(){var a=[];Di(function(b){a.push(b)});
return a}
var Ei={pf:"allow-forms",qf:"allow-modals",rf:"allow-orientation-lock",sf:"allow-pointer-lock",tf:"allow-popups",uf:"allow-popups-to-escape-sandbox",vf:"allow-presentation",wf:"allow-same-origin",xf:"allow-scripts",yf:"allow-top-navigation",zf:"allow-top-navigation-by-user-activation"},Gi=Cd(function(){return Fi()});
function Hi(){var a=Ii(),b={};Db(Gi(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Ii(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Ji(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Ki=(new Date).getTime();function Li(){var a=Mi;return Tg(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
;function Ni(a){wd.call(this);var b=this;this.A=this.j=0;this.Da=a!=null?a:{pa:function(e,f){return setTimeout(e,f)},
qa:function(e){clearTimeout(e)}};
var c,d;this.i=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.l=function(){return z(function(e){return e.yield(Oi(b),0)})};
window.addEventListener("offline",this.l);window.addEventListener("online",this.l);this.A||Pi(this)}
y(Ni,wd);function Qi(){var a=Ri;Ni.h||(Ni.h=new Ni(a));return Ni.h}
Ni.prototype.dispose=function(){window.removeEventListener("offline",this.l);window.removeEventListener("online",this.l);this.Da.qa(this.A);delete Ni.h};
Ni.prototype.va=function(){return this.i};
function Pi(a){a.A=a.Da.pa(function(){var b;return z(function(c){if(c.h==1)return a.i?((b=window.navigator)==null?0:b.onLine)?c.B(3):c.yield(Oi(a),3):c.yield(Oi(a),3);Pi(a);c.h=0})},3E4)}
function Oi(a,b){return a.m?a.m:a.m=new Promise(function(c){var d,e,f,g;return z(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,Aa(h,2,3),d&&(a.j=a.Da.pa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.P=[h.j];h.l=0;h.v=0;a.m=void 0;a.j&&(a.Da.qa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?xd(a,"networkstatus-online"):xd(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:Ba(h),g=!1,h.B(3)}})})}
;function Si(){this.data=[];this.h=-1}
Si.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Si.prototype.get=function(a){return!!this.data[a]};
function Ti(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Ui(){this.blockSize=-1}
;function Vi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.v=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
$a(Vi,Ui);Vi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function Wi(a,b,c){c||(c=0);var d=a.m;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;e<80;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;e<80;e++){if(e<40)if(e<20){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else e<60?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
Vi.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.v,f=this.i;d<b;){if(f==0)for(;d<=c;)Wi(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Wi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Wi(this,e);f=0;break}}this.i=f;this.l+=b}};
Vi.prototype.digest=function(){var a=[],b=this.l*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.v[c]=b&255,b/=256;Wi(this,this.v);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Xi(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Yi(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Zi(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Xi(a).match(/\S+/g)||[],b=Cb(a,b)>=0);return b}
function $i(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Zi(a,"inverted-hdpi")&&Yi(a,Array.prototype.filter.call(a.classList?a.classList:Xi(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function aj(){}
aj.prototype.next=function(){return bj};
var bj={done:!0,value:void 0};aj.prototype.mb=function(){return this};function cj(a){if(a instanceof dj||a instanceof ej||a instanceof fj)return a;if(typeof a.next=="function")return new dj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new dj(function(){return a[Symbol.iterator]()});
if(typeof a.mb=="function")return new dj(function(){return a.mb()});
throw Error("Not an iterator or iterable.");}
function dj(a){this.h=a}
dj.prototype.mb=function(){return new ej(this.h())};
dj.prototype[Symbol.iterator]=function(){return new fj(this.h())};
dj.prototype.i=function(){return new fj(this.h())};
function ej(a){this.h=a}
y(ej,aj);ej.prototype.next=function(){return this.h.next()};
ej.prototype[Symbol.iterator]=function(){return new fj(this.h)};
ej.prototype.i=function(){return new fj(this.h)};
function fj(a){dj.call(this,function(){return a});
this.j=a}
y(fj,dj);fj.prototype.next=function(){return this.j.next()};function M(a){G.call(this);this.m=1;this.j=[];this.l=0;this.h=[];this.i={};this.A=!!a}
$a(M,G);n=M.prototype;n.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.m;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.m=e+3;d.push(e);return e};
n.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Bb(a)}return!1};
n.Bb=function(a){var b=this.h[a];if(b){var c=this.i[b];this.l!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Ib(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
n.Ya=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];gj(this.h[g+1],this.h[g+2],d)}else{this.l++;try{for(e=0,f=c.length;e<f&&!this.V;e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.l--,this.j.length>0&&this.l==0)for(;c=this.j.pop();)this.Bb(c)}}return e!=0}return!1};
function gj(a,b,c){Rd(function(){a.apply(b,c)})}
n.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Bb,this),delete this.i[a])}else this.h.length=0,this.i={}};
n.U=function(){M.Ba.U.call(this);this.clear();this.j.length=0};function hj(a){this.h=a}
hj.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new bi).serialize(b))};
hj.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
hj.prototype.remove=function(a){this.h.remove(a)};function ij(a){this.h=a}
$a(ij,hj);function jj(a){this.data=a}
function kj(a){return a===void 0||a instanceof jj?a:new jj(a)}
ij.prototype.set=function(a,b){ij.Ba.set.call(this,a,kj(b))};
ij.prototype.i=function(a){a=ij.Ba.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
ij.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function lj(a){this.h=a}
$a(lj,ij);lj.prototype.set=function(a,b,c){if(b=kj(b)){if(c){if(c<Za()){lj.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Za()}lj.Ba.set.call(this,a,b)};
lj.prototype.i=function(a){var b=lj.Ba.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Za()||c&&c>Za())lj.prototype.remove.call(this,a);else return b}};function mj(){}
;function nj(){}
$a(nj,mj);nj.prototype[Symbol.iterator]=function(){return cj(this.mb(!0)).i()};
nj.prototype.clear=function(){var a=Array.from(this);a=v(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function oj(a){this.h=a;this.i=null}
$a(oj,nj);n=oj.prototype;n.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
n.set=function(a,b){pj(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
n.get=function(a){pj(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){pj(this);this.h.removeItem(a)};
n.mb=function(a){pj(this);var b=0,c=this.h,d=new aj;d.next=function(){if(b>=c.length)return bj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
n.clear=function(){pj(this);this.h.clear()};
n.key=function(a){pj(this);return this.h.key(a)};
function pj(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Kd(Error("Storage mechanism: Storage unavailable"))}
;function qj(){var a=null;try{a=B.localStorage||null}catch(b){}oj.call(this,a)}
$a(qj,oj);function rj(a,b){this.i=a;this.h=b+"::"}
$a(rj,nj);rj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
rj.prototype.get=function(a){return this.i.get(this.h+a)};
rj.prototype.remove=function(a){this.i.remove(this.h+a)};
rj.prototype.mb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new aj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var O={},sj=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";O.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
O.Nc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var tj={nb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
dd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},uj={nb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
dd:function(a){return[].concat.apply([],a)}};
O.Ye=function(){sj?(O.lb=Uint8Array,O.Ja=Uint16Array,O.Id=Int32Array,O.assign(O,tj)):(O.lb=Array,O.Ja=Array,O.Id=Array,O.assign(O,uj))};
O.Ye();var vj=!0;try{new Uint8Array(1)}catch(a){vj=!1}
function wj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new O.lb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var xj={};xj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var yj={},zj,Aj=[],Bj=0;Bj<256;Bj++){zj=Bj;for(var Cj=0;Cj<8;Cj++)zj=zj&1?3988292384^zj>>>1:zj>>>1;Aj[Bj]=zj}yj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^Aj[(a^b[d])&255];return a^-1};var Dj={};Dj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function Ej(a){for(var b=a.length;--b>=0;)a[b]=0}
var Fj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],Gj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],Hj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],Ij=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],Jj=Array(576);Ej(Jj);var Kj=Array(60);Ej(Kj);var Lj=Array(512);Ej(Lj);var Mj=Array(256);Ej(Mj);var Nj=Array(29);Ej(Nj);var Oj=Array(30);Ej(Oj);function Pj(a,b,c,d,e){this.Ad=a;this.ae=b;this.Zd=c;this.Ud=d;this.xe=e;this.hd=a&&a.length}
var Qj,Rj,Sj;function Tj(a,b){this.cd=a;this.vb=0;this.Wa=b}
function Uj(a,b){a.Z[a.pending++]=b&255;a.Z[a.pending++]=b>>>8&255}
function Vj(a,b,c){a.ja>16-c?(a.oa|=b<<a.ja&65535,Uj(a,a.oa),a.oa=b>>16-a.ja,a.ja+=c-16):(a.oa|=b<<a.ja&65535,a.ja+=c)}
function Wj(a,b,c){Vj(a,c[b*2],c[b*2+1])}
function Xj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function Yj(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=Xj(d[e]++,e))}
function Zj(a){var b;for(b=0;b<286;b++)a.ra[b*2]=0;for(b=0;b<30;b++)a.bb[b*2]=0;for(b=0;b<19;b++)a.ka[b*2]=0;a.ra[512]=1;a.Pa=a.zb=0;a.ya=a.matches=0}
function ak(a){a.ja>8?Uj(a,a.oa):a.ja>0&&(a.Z[a.pending++]=a.oa);a.oa=0;a.ja=0}
function bk(a,b,c){ak(a);Uj(a,c);Uj(a,~c);O.nb(a.Z,a.window,b,c,a.pending);a.pending+=c}
function ck(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function dk(a,b,c){for(var d=a.aa[c],e=c<<1;e<=a.Na;){e<a.Na&&ck(b,a.aa[e+1],a.aa[e],a.depth)&&e++;if(ck(b,d,a.aa[e],a.depth))break;a.aa[c]=a.aa[e];c=e;e<<=1}a.aa[c]=d}
function ek(a,b,c){var d=0;if(a.ya!==0){do{var e=a.Z[a.Gb+d*2]<<8|a.Z[a.Gb+d*2+1];var f=a.Z[a.Bc+d];d++;if(e===0)Wj(a,f,b);else{var g=Mj[f];Wj(a,g+256+1,b);var h=Fj[g];h!==0&&(f-=Nj[g],Vj(a,f,h));e--;g=e<256?Lj[e]:Lj[256+(e>>>7)];Wj(a,g,c);h=Gj[g];h!==0&&(e-=Oj[g],Vj(a,e,h))}}while(d<a.ya)}Wj(a,256,b)}
function fk(a,b){var c=b.cd,d=b.Wa.Ad,e=b.Wa.hd,f=b.Wa.Ud,g,h=-1;a.Na=0;a.qb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.aa[++a.Na]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Na<2;){var k=a.aa[++a.Na]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Pa--;e&&(a.zb-=d[k*2+1])}b.vb=h;for(g=a.Na>>1;g>=1;g--)dk(a,c,g);k=f;do g=a.aa[1],a.aa[1]=a.aa[a.Na--],dk(a,c,1),d=a.aa[1],a.aa[--a.qb]=g,a.aa[--a.qb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.aa[1]=k++,dk(a,c,1);while(a.Na>=
2);a.aa[--a.qb]=a.aa[1];g=b.cd;k=b.vb;d=b.Wa.Ad;e=b.Wa.hd;f=b.Wa.ae;var l=b.Wa.Zd,m=b.Wa.xe,p,r=0;for(p=0;p<=15;p++)a.Ka[p]=0;g[a.aa[a.qb]*2+1]=0;for(b=a.qb+1;b<573;b++){var t=a.aa[b];p=g[g[t*2+1]*2+1]+1;p>m&&(p=m,r++);g[t*2+1]=p;if(!(t>k)){a.Ka[p]++;var w=0;t>=l&&(w=f[t-l]);var x=g[t*2];a.Pa+=x*(p+w);e&&(a.zb+=x*(d[t*2+1]+w))}}if(r!==0){do{for(p=m-1;a.Ka[p]===0;)p--;a.Ka[p]--;a.Ka[p+1]+=2;a.Ka[m]--;r-=2}while(r>0);for(p=m;p!==0;p--)for(t=a.Ka[p];t!==0;)d=a.aa[--b],d>k||(g[d*2+1]!==p&&(a.Pa+=(p-g[d*
2+1])*g[d*2],g[d*2+1]=p),t--)}Yj(c,h,a.Ka)}
function gk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ka[l*2]+=g:l!==0?(l!==e&&a.ka[l*2]++,a.ka[32]++):g<=10?a.ka[34]++:a.ka[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function hk(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do Wj(a,l,a.ka);while(--g!==0)}else l!==0?(l!==e&&(Wj(a,l,a.ka),g--),Wj(a,16,a.ka),Vj(a,g-3,2)):g<=10?(Wj(a,17,a.ka),Vj(a,g-3,3)):(Wj(a,18,a.ka),Vj(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function ik(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.ra[c*2]!==0)return 0;if(a.ra[18]!==0||a.ra[20]!==0||a.ra[26]!==0)return 1;for(c=32;c<256;c++)if(a.ra[c*2]!==0)return 1;return 0}
var jk=!1;function kk(a,b,c){a.Z[a.Gb+a.ya*2]=b>>>8&255;a.Z[a.Gb+a.ya*2+1]=b&255;a.Z[a.Bc+a.ya]=c&255;a.ya++;b===0?a.ra[c*2]++:(a.matches++,b--,a.ra[(Mj[c]+256+1)*2]++,a.bb[(b<256?Lj[b]:Lj[256+(b>>>7)])*2]++);return a.ya===a.Mb-1}
;function lk(a,b){a.msg=Dj[b];return b}
function mk(a){for(var b=a.length;--b>=0;)a[b]=0}
function nk(a){var b=a.state,c=b.pending;c>a.R&&(c=a.R);c!==0&&(O.nb(a.output,b.Z,b.Ob,c,a.wb),a.wb+=c,b.Ob+=c,a.Pc+=c,a.R-=c,b.pending-=c,b.pending===0&&(b.Ob=0))}
function ok(a,b){var c=a.ta>=0?a.ta:-1,d=a.o-a.ta,e=0;if(a.level>0){a.K.wc===2&&(a.K.wc=ik(a));fk(a,a.ic);fk(a,a.cc);gk(a,a.ra,a.ic.vb);gk(a,a.bb,a.cc.vb);fk(a,a.Vc);for(e=18;e>=3&&a.ka[Ij[e]*2+1]===0;e--);a.Pa+=3*(e+1)+14;var f=a.Pa+3+7>>>3;var g=a.zb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)Vj(a,b?1:0,3),bk(a,c,d);else if(a.strategy===4||g===f)Vj(a,2+(b?1:0),3),ek(a,Jj,Kj);else{Vj(a,4+(b?1:0),3);c=a.ic.vb+1;d=a.cc.vb+1;e+=1;Vj(a,c-257,5);Vj(a,d-1,5);Vj(a,e-4,4);for(f=0;f<e;f++)Vj(a,a.ka[Ij[f]*
2+1],3);hk(a,a.ra,c-1);hk(a,a.bb,d-1);ek(a,a.ra,a.bb)}Zj(a);b&&ak(a);a.ta=a.o;nk(a.K)}
function R(a,b){a.Z[a.pending++]=b}
function pk(a,b){a.Z[a.pending++]=b>>>8&255;a.Z[a.pending++]=b&255}
function qk(a,b){var c=a.ld,d=a.o,e=a.wa,f=a.md,g=a.o>a.ma-262?a.o-(a.ma-262):0,h=a.window,k=a.Xa,l=a.Ia,m=a.o+258,p=h[d+e-1],r=h[d+e];a.wa>=a.gd&&(c>>=2);f>a.u&&(f=a.u);do{var t=b;if(h[t+e]===r&&h[t+e-1]===p&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.ub=b;e=t;if(t>=f)break;p=h[d+e-1];r=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.u?e:a.u}
function rk(a){var b=a.ma,c;do{var d=a.Gd-a.u-a.o;if(a.o>=b+(b-262)){O.nb(a.window,a.window,b,b,0);a.ub-=b;a.o-=b;a.ta-=b;var e=c=a.hc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.K.na===0)break;e=a.K;c=a.window;f=a.o+a.u;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,O.nb(c,e.input,e.hb,g,f),e.state.wrap===1?e.J=xj(e.J,c,g,f):e.state.wrap===2&&(e.J=yj(e.J,c,g,f)),e.hb+=g,e.kb+=g,c=g);a.u+=c;if(a.u+a.sa>=3)for(d=a.o-a.sa,a.M=a.window[d],
a.M=(a.M<<a.Ma^a.window[d+1])&a.La;a.sa&&!(a.M=(a.M<<a.Ma^a.window[d+3-1])&a.La,a.Ia[d&a.Xa]=a.head[a.M],a.head[a.M]=d,d++,a.sa--,a.u+a.sa<3););}while(a.u<262&&a.K.na!==0)}
function sk(a,b){for(var c;;){if(a.u<262){rk(a);if(a.u<262&&b===0)return 1;if(a.u===0)break}c=0;a.u>=3&&(a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o);c!==0&&a.o-c<=a.ma-262&&(a.S=qk(a,c));if(a.S>=3)if(c=kk(a,a.o-a.ub,a.S-3),a.u-=a.S,a.S<=a.Dc&&a.u>=3){a.S--;do a.o++,a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o;while(--a.S!==0);a.o++}else a.o+=a.S,a.S=0,a.M=a.window[a.o],a.M=(a.M<<a.Ma^a.window[a.o+1])&a.La;else c=kk(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(ok(a,!1),a.K.R===0))return 1}a.sa=a.o<2?a.o:2;return b===4?(ok(a,!0),a.K.R===0?3:4):a.ya&&(ok(a,!1),a.K.R===0)?1:2}
function tk(a,b){for(var c,d;;){if(a.u<262){rk(a);if(a.u<262&&b===0)return 1;if(a.u===0)break}c=0;a.u>=3&&(a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o);a.wa=a.S;a.pd=a.ub;a.S=2;c!==0&&a.wa<a.Dc&&a.o-c<=a.ma-262&&(a.S=qk(a,c),a.S<=5&&(a.strategy===1||a.S===3&&a.o-a.ub>4096)&&(a.S=2));if(a.wa>=3&&a.S<=a.wa){d=a.o+a.u-3;c=kk(a,a.o-1-a.pd,a.wa-3);a.u-=a.wa-1;a.wa-=2;do++a.o<=d&&(a.M=(a.M<<a.Ma^a.window[a.o+3-1])&a.La,a.Ia[a.o&a.Xa]=a.head[a.M],a.head[a.M]=a.o);
while(--a.wa!==0);a.fb=0;a.S=2;a.o++;if(c&&(ok(a,!1),a.K.R===0))return 1}else if(a.fb){if((c=kk(a,0,a.window[a.o-1]))&&ok(a,!1),a.o++,a.u--,a.K.R===0)return 1}else a.fb=1,a.o++,a.u--}a.fb&&(kk(a,0,a.window[a.o-1]),a.fb=0);a.sa=a.o<2?a.o:2;return b===4?(ok(a,!0),a.K.R===0?3:4):a.ya&&(ok(a,!1),a.K.R===0)?1:2}
function uk(a,b){for(var c,d,e,f=a.window;;){if(a.u<=258){rk(a);if(a.u<=258&&b===0)return 1;if(a.u===0)break}a.S=0;if(a.u>=3&&a.o>0&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.S=258-(e-d);a.S>a.u&&(a.S=a.u)}a.S>=3?(c=kk(a,1,a.S-3),a.u-=a.S,a.o+=a.S,a.S=0):(c=kk(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(ok(a,!1),a.K.R===0))return 1}a.sa=0;return b===4?(ok(a,!0),a.K.R===0?3:4):
a.ya&&(ok(a,!1),a.K.R===0)?1:2}
function vk(a,b){for(var c;;){if(a.u===0&&(rk(a),a.u===0)){if(b===0)return 1;break}a.S=0;c=kk(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(ok(a,!1),a.K.R===0))return 1}a.sa=0;return b===4?(ok(a,!0),a.K.R===0?3:4):a.ya&&(ok(a,!1),a.K.R===0)?1:2}
function wk(a,b,c,d,e){this.he=a;this.we=b;this.ze=c;this.ue=d;this.ce=e}
var xk;xk=[new wk(0,0,0,0,function(a,b){var c=65535;for(c>a.za-5&&(c=a.za-5);;){if(a.u<=1){rk(a);if(a.u===0&&b===0)return 1;if(a.u===0)break}a.o+=a.u;a.u=0;var d=a.ta+c;if(a.o===0||a.o>=d)if(a.u=a.o-d,a.o=d,ok(a,!1),a.K.R===0)return 1;if(a.o-a.ta>=a.ma-262&&(ok(a,!1),a.K.R===0))return 1}a.sa=0;if(b===4)return ok(a,!0),a.K.R===0?3:4;a.o>a.ta&&ok(a,!1);return 1}),
new wk(4,4,8,4,sk),new wk(4,5,16,8,sk),new wk(4,6,32,32,sk),new wk(4,4,16,16,tk),new wk(8,16,32,32,tk),new wk(8,16,128,128,tk),new wk(8,32,128,256,tk),new wk(32,128,258,1024,tk),new wk(32,258,258,4096,tk)];
function yk(){this.K=null;this.status=0;this.Z=null;this.wrap=this.pending=this.Ob=this.za=0;this.I=null;this.Ca=0;this.method=8;this.sb=-1;this.Xa=this.Sc=this.ma=0;this.window=null;this.Gd=0;this.head=this.Ia=null;this.md=this.gd=this.strategy=this.level=this.Dc=this.ld=this.wa=this.u=this.ub=this.o=this.fb=this.pd=this.S=this.ta=this.Ma=this.La=this.zc=this.hc=this.M=0;this.ra=new O.Ja(1146);this.bb=new O.Ja(122);this.ka=new O.Ja(78);mk(this.ra);mk(this.bb);mk(this.ka);this.Vc=this.cc=this.ic=
null;this.Ka=new O.Ja(16);this.aa=new O.Ja(573);mk(this.aa);this.qb=this.Na=0;this.depth=new O.Ja(573);mk(this.depth);this.ja=this.oa=this.sa=this.matches=this.zb=this.Pa=this.Gb=this.ya=this.Mb=this.Bc=0}
function zk(a,b){if(!a||!a.state||b>5||b<0)return a?lk(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return lk(a,a.R===0?-5:-2);c.K=a;var d=c.sb;c.sb=b;if(c.status===42)if(c.wrap===2)a.J=0,R(c,31),R(c,139),R(c,8),c.I?(R(c,(c.I.text?1:0)+(c.I.Ta?2:0)+(c.I.extra?4:0)+(c.I.name?8:0)+(c.I.comment?16:0)),R(c,c.I.time&255),R(c,c.I.time>>8&255),R(c,c.I.time>>16&255),R(c,c.I.time>>24&255),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,c.I.os&255),c.I.extra&&c.I.extra.length&&
(R(c,c.I.extra.length&255),R(c,c.I.extra.length>>8&255)),c.I.Ta&&(a.J=yj(a.J,c.Z,c.pending,0)),c.Ca=0,c.status=69):(R(c,0),R(c,0),R(c,0),R(c,0),R(c,0),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,3),c.status=113);else{var e=8+(c.Sc-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.o!==0&&(e|=32);c.status=113;pk(c,e+(31-e%31));c.o!==0&&(pk(c,a.J>>>16),pk(c,a.J&65535));a.J=1}if(c.status===69)if(c.I.extra){for(e=c.pending;c.Ca<(c.I.extra.length&65535)&&(c.pending!==c.za||
(c.I.Ta&&c.pending>e&&(a.J=yj(a.J,c.Z,c.pending-e,e)),nk(a),e=c.pending,c.pending!==c.za));)R(c,c.I.extra[c.Ca]&255),c.Ca++;c.I.Ta&&c.pending>e&&(a.J=yj(a.J,c.Z,c.pending-e,e));c.Ca===c.I.extra.length&&(c.Ca=0,c.status=73)}else c.status=73;if(c.status===73)if(c.I.name){e=c.pending;do{if(c.pending===c.za&&(c.I.Ta&&c.pending>e&&(a.J=yj(a.J,c.Z,c.pending-e,e)),nk(a),e=c.pending,c.pending===c.za)){var f=1;break}f=c.Ca<c.I.name.length?c.I.name.charCodeAt(c.Ca++)&255:0;R(c,f)}while(f!==0);c.I.Ta&&c.pending>
e&&(a.J=yj(a.J,c.Z,c.pending-e,e));f===0&&(c.Ca=0,c.status=91)}else c.status=91;if(c.status===91)if(c.I.comment){e=c.pending;do{if(c.pending===c.za&&(c.I.Ta&&c.pending>e&&(a.J=yj(a.J,c.Z,c.pending-e,e)),nk(a),e=c.pending,c.pending===c.za)){f=1;break}f=c.Ca<c.I.comment.length?c.I.comment.charCodeAt(c.Ca++)&255:0;R(c,f)}while(f!==0);c.I.Ta&&c.pending>e&&(a.J=yj(a.J,c.Z,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.I.Ta?(c.pending+2>c.za&&nk(a),c.pending+2<=c.za&&(R(c,a.J&
255),R(c,a.J>>8&255),a.J=0,c.status=113)):c.status=113);if(c.pending!==0){if(nk(a),a.R===0)return c.sb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return lk(a,-5);if(c.status===666&&a.na!==0)return lk(a,-5);if(a.na!==0||c.u!==0||b!==0&&c.status!==666){d=c.strategy===2?vk(c,b):c.strategy===3?uk(c,b):xk[c.level].ce(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.R===0&&(c.sb=-1),0;if(d===2&&(b===1?(Vj(c,2,3),Wj(c,256,Jj),c.ja===16?(Uj(c,c.oa),c.oa=0,c.ja=0):c.ja>=8&&
(c.Z[c.pending++]=c.oa&255,c.oa>>=8,c.ja-=8)):b!==5&&(Vj(c,0,3),bk(c,0,0),b===3&&(mk(c.head),c.u===0&&(c.o=0,c.ta=0,c.sa=0))),nk(a),a.R===0))return c.sb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(R(c,a.J&255),R(c,a.J>>8&255),R(c,a.J>>16&255),R(c,a.J>>24&255),R(c,a.kb&255),R(c,a.kb>>8&255),R(c,a.kb>>16&255),R(c,a.kb>>24&255)):(pk(c,a.J>>>16),pk(c,a.J&65535));nk(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var Ak={};Ak=function(){this.input=null;this.kb=this.na=this.hb=0;this.output=null;this.Pc=this.R=this.wb=0;this.msg="";this.state=null;this.wc=2;this.J=0};var Bk=Object.prototype.toString;
function Ck(a){if(!(this instanceof Ck))return new Ck(a);a=this.options=O.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.K=new Ak;this.K.R=0;var b=this.K;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=lk(b,-2);else{e===8&&(e=9);var k=new yk;b.state=k;k.K=b;k.wrap=h;k.I=null;k.Sc=e;k.ma=1<<k.Sc;k.Xa=k.ma-1;k.zc=f+7;k.hc=1<<k.zc;k.La=k.hc-1;k.Ma=~~((k.zc+3-1)/3);k.window=new O.lb(k.ma*2);k.head=new O.Ja(k.hc);k.Ia=new O.Ja(k.ma);k.Mb=1<<f+6;k.za=k.Mb*4;k.Z=new O.lb(k.za);k.Gb=1*k.Mb;k.Bc=3*k.Mb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.kb=b.Pc=0;b.wc=2;c=b.state;c.pending=0;c.Ob=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.J=c.wrap===2?
0:1;c.sb=0;if(!jk){d=Array(16);for(f=g=0;f<28;f++)for(Nj[f]=g,e=0;e<1<<Fj[f];e++)Mj[g++]=f;Mj[g-1]=f;for(f=g=0;f<16;f++)for(Oj[f]=g,e=0;e<1<<Gj[f];e++)Lj[g++]=f;for(g>>=7;f<30;f++)for(Oj[f]=g<<7,e=0;e<1<<Gj[f]-7;e++)Lj[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)Jj[e*2+1]=8,e++,d[8]++;for(;e<=255;)Jj[e*2+1]=9,e++,d[9]++;for(;e<=279;)Jj[e*2+1]=7,e++,d[7]++;for(;e<=287;)Jj[e*2+1]=8,e++,d[8]++;Yj(Jj,287,d);for(e=0;e<30;e++)Kj[e*2+1]=5,Kj[e*2]=Xj(e,5);Qj=new Pj(Jj,Fj,257,286,15);Rj=new Pj(Kj,
Gj,0,30,15);Sj=new Pj([],Hj,0,19,7);jk=!0}c.ic=new Tj(c.ra,Qj);c.cc=new Tj(c.bb,Rj);c.Vc=new Tj(c.ka,Sj);c.oa=0;c.ja=0;Zj(c);c=0}else c=lk(b,-2);c===0&&(b=b.state,b.Gd=2*b.ma,mk(b.head),b.Dc=xk[b.level].we,b.gd=xk[b.level].he,b.md=xk[b.level].ze,b.ld=xk[b.level].ue,b.o=0,b.ta=0,b.u=0,b.sa=0,b.S=b.wa=2,b.fb=0,b.M=0);b=c}}else b=-2;if(b!==0)throw Error(Dj[b]);a.header&&(b=this.K)&&b.state&&b.state.wrap===2&&(b.state.I=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=wj(a.dictionary):
Bk.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.K;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.u)b=-2;else{b===1&&(a.J=xj(a.J,f,g,0));l.wrap=0;g>=l.ma&&(b===0&&(mk(l.head),l.o=0,l.ta=0,l.sa=0),c=new O.lb(l.ma),O.nb(c,f,g-l.ma,l.ma,0),f=c,g=l.ma);c=a.na;d=a.hb;e=a.input;a.na=g;a.hb=0;a.input=f;for(rk(l);l.u>=3;){f=l.o;g=l.u-2;do l.M=(l.M<<l.Ma^l.window[f+3-1])&l.La,l.Ia[f&l.Xa]=l.head[l.M],l.head[l.M]=f,f++;while(--g);
l.o=f;l.u=2;rk(l)}l.o+=l.u;l.ta=l.o;l.sa=l.u;l.u=0;l.S=l.wa=2;l.fb=0;a.hb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(Dj[b]);this.Bg=!0}}
Ck.prototype.push=function(a,b){var c=this.K,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=wj(a):Bk.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.hb=0;c.na=c.input.length;do{c.R===0&&(c.output=new O.lb(d),c.wb=0,c.R=d);a=zk(c,e);if(a!==1&&a!==0)return Dk(this,a),this.ended=!0,!1;if(c.R===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=O.Nc(c.output,c.wb);b=f;f=f.length;if(f<65537&&(b.subarray&&vj||!b.subarray))b=
String.fromCharCode.apply(null,O.Nc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=O.Nc(c.output,c.wb),this.chunks.push(b)}while((c.na>0||c.R===0)&&a!==1);if(e===4)return(c=this.K)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=lk(c,-2):(c.state=null,a=d===113?lk(c,-3):0)):a=-2,Dk(this,a),this.ended=!0,a===0;e===2&&(Dk(this,0),c.R=0);return!0};
function Dk(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):O.dd(a.chunks));a.chunks=[];a.err=b;a.msg=a.K.msg}
function Ek(a,b){b=b||{};b.gzip=!0;b=new Ck(b);b.push(a,!0);if(b.err)throw b.msg||Dj[b.err];return b.result}
;function Fk(a){if(!a)return null;a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue;var b;a?b=mb(a):b=null;return b}
;function Gk(a){return mb(a===null?"null":a===void 0?"undefined":a)}
;function Hk(a){this.name=a}
;var Ik=new Hk("rawColdConfigGroup");var Jk=new Hk("rawHotConfigGroup");function Kk(a){this.D=I(a)}
y(Kk,L);var Lk=new Hk("continuationCommand");var Mk=new Hk("webCommandMetadata");var Nk=new Hk("signalServiceEndpoint");var Ok={Ef:"EMBEDDED_PLAYER_MODE_UNKNOWN",Bf:"EMBEDDED_PLAYER_MODE_DEFAULT",Df:"EMBEDDED_PLAYER_MODE_PFP",Cf:"EMBEDDED_PLAYER_MODE_PFL"};var Pk=new Hk("feedbackEndpoint");function Qk(a){this.D=I(a)}
y(Qk,L);Qk.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new We(a,Te):Ue||(Ue=new We(null,Te));else if(a.constructor!==We)if(Se(a))a=a.length?new We(new Uint8Array(a),Te):Ue||(Ue=new We(null,Te));else throw Error();return J(this,1,a)};var Mi={gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",Of:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",Lf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",Pf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",Sf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",Rf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",Uf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",Tf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",If:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Hf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Jf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",Kf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",Mf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",Nf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Qf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED"};var Rk=new Hk("webPlayerShareEntityServiceEndpoint");var Sk=new Hk("playlistEditEndpoint");var Tk=new Hk("modifyChannelNotificationPreferenceEndpoint");var Uk=new Hk("unsubscribeEndpoint");var Vk=new Hk("subscribeEndpoint");function Wk(){var a=Xk;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function Yk(a){D("yt.ads.biscotti.lastId_",a)}
;function Zk(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var $k=B.window,al,bl,cl=($k==null?void 0:(al=$k.yt)==null?void 0:al.config_)||($k==null?void 0:(bl=$k.ytcfg)==null?void 0:bl.data_)||{};D("yt.config_",cl);function dl(){Zk(cl,arguments)}
function T(a,b){return a in cl?cl[a]:b}
function el(a){var b=cl.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var fl=[];function gl(a){fl.forEach(function(b){return b(a)})}
function hl(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){il(b)}}:a}
function il(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=T("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),dl("ERRORS",b));gl(a)}
function jl(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=T("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),dl("ERRORS",f))}
;var kl=/^[\w.]*$/,ll={q:!0,search_query:!0};function ml(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=nl(f[0]||""),h=nl(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Jb(k,h):c[g]=[k,h]}else c[g]=h}catch(r){var l=r,m=f[0],p=String(ml);l.args=[{key:m,value:f[1],query:a,method:ol===p?"unchanged":p}];ll.hasOwnProperty(m)||jl(l)}}return c}
var ol=String(ml);function pl(a){var b=[];Kb(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Db(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function ql(a){a.charAt(0)==="?"&&(a=a.substring(1));return ml(a,"&")}
function rl(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),ql(a.length>1?a[1]:a[0])):{}}
function sl(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=ql(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return tc(a,e)+d}
function tl(a){if(!b)var b=window.location.href;var c=nc(1,a),d=oc(a);c&&d?(a=a.match(lc),b=b.match(lc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?oc(b)===d&&(Number(nc(4,b))||null)===(Number(nc(4,a))||null):!0;return a}
function nl(a){return a&&a.match(kl)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function ul(a){var b=vl;a=a===void 0?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Ki;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ka){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?Ci:g;try{var h=g.history.length}catch(Ka){h=0}e.u_his=h;var k;e.u_h=(k=Ci.screen)==null?void 0:k.height;var l;e.u_w=(l=Ci.screen)==null?void 0:l.width;var m;e.u_ah=(m=Ci.screen)==null?void 0:m.availHeight;var p;e.u_aw=
(p=Ci.screen)==null?void 0:p.availWidth;var r;e.u_cd=(r=Ci.screen)==null?void 0:r.colorDepth}catch(Ka){}h=b.h;try{var t=h.screenX;var w=h.screenY}catch(Ka){}try{var x=h.outerWidth;var C=h.outerHeight}catch(Ka){}try{var F=h.innerWidth;var K=h.innerHeight}catch(Ka){}try{var N=h.screenLeft;var S=h.screenTop}catch(Ka){}try{F=h.innerWidth,K=h.innerHeight}catch(Ka){}try{var da=h.screen.availWidth;var va=h.screen.availTop}catch(Ka){}t=[N,S,t,w,da,va,x,C,F,K];try{var P=(b.h.top||window).document,ea=P.compatMode==
"CSS1Compat"?P.documentElement:P.body;var na=(new Ed(ea.clientWidth,ea.clientHeight)).round()}catch(Ka){na=new Ed(-12245933,-12245933)}P=na;na={};var La=La===void 0?B:La;ea=new Si;"SVGElement"in La&&"createElementNS"in La.document&&ea.set(0);w=Hi();w["allow-top-navigation-by-user-activation"]&&ea.set(1);w["allow-popups-to-escape-sandbox"]&&ea.set(2);La.crypto&&La.crypto.subtle&&ea.set(3);"TextDecoder"in La&&"TextEncoder"in La&&ea.set(4);La=Ti(ea);na.bc=La;na.bih=P.height;na.biw=P.width;na.brdim=t.join();
b=b.i;b=(na.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,na.wgl=!!Ci.WebGLRenderingContext,na);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var vl=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return pl(ul(a))});Za();navigator.userAgent.indexOf(" (CrKey ");var wl="XMLHttpRequest"in B?function(){return new XMLHttpRequest}:null;
function xl(){if(!wl)return null;var a=wl();return"open"in a?a:null}
function yl(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function zl(a,b){typeof a==="function"&&(a=hl(a));return window.setTimeout(a,b)}
;var Al="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(la(Al),["client_dev_set_cookie"]);function U(a){a=Bl(a);return typeof a==="string"&&a==="false"?!1:!!a}
function Cl(a,b){a=Bl(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function Bl(a){return T("EXPERIMENT_FLAGS",{})[a]}
function Dl(){for(var a=[],b=T("EXPERIMENTS_FORCED_FLAGS",{}),c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=T("EXPERIMENT_FLAGS",{});d=v(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var El={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Fl="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(la(Al)),Gl=!1;
function Hl(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&hl(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=xl();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;U("debug_forward_web_query_parameters")&&(a=Il(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Jl(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(p){jl(p)}}l.send(d);return l}
function Jl(a,b){b=b===void 0?{}:b;var c=tl(a),d=T("INNERTUBE_CLIENT_NAME"),e=U("web_ajax_ignore_global_headers_if_set"),f;for(f in El){var g=T(El[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=T("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||(oc(a)?!1:!0))){k=a;var l;if(l=U("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=oc(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=mc(nc(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!oc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!oc(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(p){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&oc(a)||(b["X-YouTube-Ad-Signals"]=pl(ul()));return b}
function Kl(a,b){b.method="POST";b.postParams||(b.postParams={});return Ll(a,b)}
function Ll(a,b){var c=b.format||"JSON";a=Ml(a,b);var d=Nl(a,b),e=!1,f=Ol(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=yl(k),m=null,p=400<=k.status&&k.status<500,r=500<=k.status&&k.status<600;if(l||p||r)m=Pl(a,c,k,b.convertToSafeHtml);l&&(l=Ql(c,k,m));m=m||{};p=b.context||B;l?b.onSuccess&&b.onSuccess.call(p,k,m):b.onError&&b.onError.call(p,k,m);b.onFinish&&b.onFinish.call(p,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=zl(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||B,f))},d)}return f}
function Ml(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=T("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=sl(a,b||{},!0);return a}
function Nl(a,b){var c=T("XSRF_FIELD_NAME"),d=T("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=T("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||oc(a)&&!b.withCredentials&&oc(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(U("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=ql(e),Ub(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):sc(e));f=e||f&&!Nb(f);!Gl&&f&&b.method!=="POST"&&(Gl=!0,il(Error("AJAX request with postData should use POST")));return e}
function Pl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,jl(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Rl(a):null)e={},Db(a.getElementsByTagName("*"),function(g){e[g.tagName]=Sl(g)})}d&&Tl(e);
return e}
function Tl(a){if(Ra(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=fb();d=e?e.createHTML(d):d;a[c]=new Vb(d)}else Tl(a[b])}}
function Ql(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function Rl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function Sl(a){var b="";Db(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Il(a){var b=window.location.search,c=oc(a);U("debug_handle_relative_url_for_query_forward_killswitch")||!c&&tl(a)&&(c=document.location.hostname);var d=mc(nc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=ql(b),f={};Db(Fl,function(g){e[g]&&(f[g]=e[g])});
return sl(a,f||{},!1)}
var Ol=Hl;var Ul=[{Ec:function(a){return"Cannot read property '"+a.key+"'"},
kc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ec:function(a){return"Cannot call '"+a.key+"'"},
kc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ec:function(a){return a.key+" is not defined"},
kc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Wl={Va:[],Sa:[{callback:Vl,weight:500}]};function Vl(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Xl(){this.Sa=[];this.Va=[]}
var Yl;function Zl(){if(!Yl){var a=Yl=new Xl;a.Va.length=0;a.Sa.length=0;Wl.Va&&a.Va.push.apply(a.Va,Wl.Va);Wl.Sa&&a.Sa.push.apply(a.Sa,Wl.Sa)}return Yl}
;var $l=new M;function am(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=bm(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=bm(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=bm(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function bm(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function cm(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=dm(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=am(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?dm(f+".ve",g,h,k):0;d+=f;d+=dm(e,a[e],b,c);if(d>500)break}}else c[b]=em(a),d+=c[b].length;else c[b]=em(a),d+=c[b].length;return d}
function dm(a,b,c,d){c+="."+a;a=em(b);d[c]=a;return c.length+a.length}
function em(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function fm(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function gm(){if(!B.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return B.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":B.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":B.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":B.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function hm(){this.df=!0}
function im(){hm.h||(hm.h=new hm);return hm.h}
function jm(a,b){a={};var c=[];"SESSION_ID"in cl&&c.push({key:"u",value:T("SESSION_ID")});if(c=qh(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(T("SESSION_INDEX",0)),c=isNaN(c)?0:c),U("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in cl||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in cl&&(a["X-Goog-PageId"]=T("DELEGATED_SESSION_ID"));return a}
;var km={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function lm(a,b,c,d,e){mh.set(""+a,b,{Nb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function mm(a){return mh.get(""+a,void 0)}
function nm(a,b,c){mh.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function om(){if(U("embeds_web_enable_cookie_detection_fix")){if(!B.navigator.cookieEnabled)return!1}else if(!mh.isEnabled())return!1;if(mh.h.cookie)return!0;U("embeds_web_enable_cookie_detection_fix")?mh.set("TESTCOOKIESENABLED","1",{Nb:60,Me:"none",secure:!0}):mh.set("TESTCOOKIESENABLED","1",{Nb:60});if(mh.get("TESTCOOKIESENABLED")!=="1")return!1;mh.remove("TESTCOOKIESENABLED");return!0}
;var pm=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",pm);function qm(){this.h=T("ALT_PREF_COOKIE_NAME","PREF");this.i=T("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=mm(this.h);a&&this.parse(a)}
var rm;function sm(){rm||(rm=new qm);return rm}
n=qm.prototype;n.get=function(a,b){tm(a);um(a);a=pm[a]!==void 0?pm[a].toString():null;return a!=null?a:b?b:""};
n.set=function(a,b){tm(a);um(a);if(b==null)throw Error("ExpectedNotNull");pm[a]=b.toString()};
function wm(a){return!!((xm("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
n.remove=function(a){tm(a);um(a);delete pm[a]};
n.clear=function(){for(var a in pm)delete pm[a]};
function um(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function tm(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function xm(a){a=pm[a]!==void 0?pm[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
n.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(pm[d]=c.toString())}};var ym={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},zm={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Am(){var a=B.navigator;return a?a.connection:void 0}
function Bm(){var a=Am();if(a){var b=ym[a.type||"unknown"]||"CONN_UNKNOWN";a=ym[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function Cm(){var a=Am();if(a!=null&&a.effectiveType)return zm.hasOwnProperty(a.effectiveType)?zm[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function V(a){var b=A.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(la(b))}
y(V,Error);function Dm(){try{return Em(),!0}catch(a){return!1}}
function Em(a){if(T("DATASYNC_ID")!==void 0)return T("DATASYNC_ID");throw new V("Datasync ID not set",a===void 0?"unknown":a);}
;function Fm(){}
function Gm(a,b){return Ri.ab(a,0,b)}
Fm.prototype.pa=function(a,b){return this.ab(a,1,b)};
Fm.prototype.Db=function(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var Hm=Cl("web_emulated_idle_callback_delay",300),Im=1E3/60-3,Jm=[8,5,4,3,2,1,0];
function Km(a){a=a===void 0?{}:a;G.call(this);this.i=[];this.j={};this.da=this.h=0;this.ba=this.m=!1;this.P=[];this.W=this.ga=!1;for(var b=v(Jm),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.l=0;this.vc=a.timeout||1;this.H=Im;this.A=0;this.xa=this.Be.bind(this);this.uc=this.gf.bind(this);this.Za=this.Md.bind(this);this.Cb=this.je.bind(this);this.Tb=this.Ee.bind(this);this.Ga=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!U("disable_scheduler_requestIdleCallback");(this.ia=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.xa)}
y(Km,G);n=Km.prototype;n.Db=function(a){var b=Za();Lm(this,a);a=Za()-b;this.m||(this.H-=a)};
n.ab=function(a,b,c){++this.da;if(b===10)return this.Db(a),this.da;var d=this.da;this.j[d]=a;this.m&&!c?this.P.push({id:d,priority:b}):(this.i[b].push(d),this.ba||this.m||(this.h!==0&&Mm(this)!==this.A&&this.stop(),this.start()));return d};
n.qa=function(a){delete this.j[a]};
function Nm(a){a.P.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
n.isHidden=function(){return!!document.hidden||!1};
function Om(a){return!a.isHidden()&&a.ia}
function Mm(a){if(a.i[8].length){if(a.W)return 4;if(Om(a))return 3}for(var b=5;b>=a.l;b--)if(a.i[b].length>0)return b>0?Om(a)?3:2:1;return 0}
n.Ha=function(a){var b=E("yt.logging.errors.log");b&&b(a)};
function Lm(a,b){try{b()}catch(c){a.Ha(c)}}
function Pm(a){for(var b=v(Jm),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
n.je=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ga=!0;Qm(this,b);this.ga=!1};
n.gf=function(){Qm(this)};
n.Md=function(){Rm(this)};
n.Ee=function(a){this.W=!0;var b=Mm(this);b===4&&b!==this.A&&(this.stop(),this.start());Qm(this,void 0,a);this.W=!1};
n.Be=function(){this.isHidden()||Rm(this);this.h&&(this.stop(),this.start())};
function Rm(a){a.stop();a.m=!0;for(var b=Za(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&Lm(a,e)}Sm(a);a.m=!1;Pm(a)&&a.start();b=Za()-b;a.H-=b}
function Sm(a){for(var b=0,c=a.P.length;b<c;b++){var d=a.P[b];a.i[d.priority].push(d.id)}a.P.length=0}
function Qm(a,b,c){a.W&&a.A===4&&a.h||a.stop();a.m=!0;b=Za()+(b||a.H);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&Lm(a,f);d=a.ga?0:1;d=a.l>d?a.l:d;if(!(Za()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&Lm(a,c)}while(c&&Za()<b)}a.m=!1;Sm(a);a.H=Im;Pm(a)&&a.start()}
n.start=function(){this.ba=!1;if(this.h===0)switch(this.A=Mm(this),this.A){case 1:var a=this.Cb;this.h=this.Ga?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,Hm);break;case 2:this.h=window.setTimeout(this.uc,this.vc);break;case 3:this.h=window.requestAnimationFrame(this.Tb);break;case 4:this.h=window.setTimeout(this.Za,0)}};
n.pause=function(){this.stop();this.ba=!0};
n.stop=function(){if(this.h){switch(this.A){case 1:var a=this.h;this.Ga?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
n.U=function(){Nm(this);this.stop();this.ia&&document.removeEventListener("visibilitychange",this.xa);G.prototype.U.call(this)};var Tm=E("yt.scheduler.instance.timerIdMap_")||{},Um=Cl("kevlar_tuner_scheduler_soft_state_timer_ms",800),Vm=0,Wm=0;function Xm(){var a=E("ytglobal.schedulerInstanceInstance_");if(!a||a.V)a=new Km(T("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function Ym(){Zm();var a=E("ytglobal.schedulerInstanceInstance_");a&&(Cc(a),D("ytglobal.schedulerInstanceInstance_",null))}
function Zm(){Nm(Xm());for(var a in Tm)Tm.hasOwnProperty(a)&&delete Tm[Number(a)]}
function $m(a,b,c){if(!c)return c=c===void 0,-Xm().ab(a,b,c);var d=window.setTimeout(function(){var e=Xm().ab(a,b);Tm[d]=e},c);
return d}
function an(a){Xm().Db(a)}
function bn(a){var b=Xm();if(a<0)b.qa(-a);else{var c=Tm[a];c?(b.qa(c),delete Tm[a]):window.clearTimeout(a)}}
function cn(){dn()}
function dn(){window.clearTimeout(Vm);Xm().start()}
function en(){Xm().pause();window.clearTimeout(Vm);Vm=window.setTimeout(cn,Um)}
function fn(){window.clearTimeout(Wm);Wm=window.setTimeout(function(){gn(0)},Um)}
function gn(a){fn();var b=Xm();b.l=a;b.start()}
function hn(a){fn();var b=Xm();b.l>a&&(b.l=a,b.start())}
function jn(){window.clearTimeout(Wm);var a=Xm();a.l=0;a.start()}
;function kn(){Fm.apply(this,arguments)}
y(kn,Fm);function ln(){kn.h||(kn.h=new kn);return kn.h}
kn.prototype.ab=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):zl(a,c||0)};
kn.prototype.qa=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
kn.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
kn.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var Ri=ln();
U("web_scheduler_auto_init")&&!E("yt.scheduler.initialized")&&(D("yt.scheduler.instance.dispose",Ym),D("yt.scheduler.instance.addJob",$m),D("yt.scheduler.instance.addImmediateJob",an),D("yt.scheduler.instance.cancelJob",bn),D("yt.scheduler.instance.cancelAllJobs",Zm),D("yt.scheduler.instance.start",dn),D("yt.scheduler.instance.pause",en),D("yt.scheduler.instance.setPriorityThreshold",gn),D("yt.scheduler.instance.enablePriorityThreshold",hn),D("yt.scheduler.instance.clearPriorityThreshold",jn),D("yt.scheduler.initialized",
!0));function mn(a){var b=new qj;this.h=(a=b.isAvailable()?a?new rj(b,a):b:null)?new lj(a):null;this.i=document.domain||window.location.hostname}
mn.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new bi).serialize(b))}catch(f){return}else e=escape(b);lm(a,e,c,this.i)};
mn.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=mm(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
mn.prototype.remove=function(a){this.h&&this.h.remove(a);nm(a,"/",this.i)};var nn=function(){var a;return function(){a||(a=new mn("ytidb"));return a}}();
function on(){var a;return(a=nn())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var pn=[],qn,rn=!1;function sn(){var a={};for(qn=new tn(a.handleError===void 0?un:a.handleError,a.logEvent===void 0?vn:a.logEvent);pn.length>0;)switch(a=pn.shift(),a.type){case "ERROR":qn.Ha(a.payload);break;case "EVENT":qn.logEvent(a.eventType,a.payload)}}
function wn(a){rn||(qn?qn.Ha(a):(pn.push({type:"ERROR",payload:a}),pn.length>10&&pn.shift()))}
function xn(a,b){rn||(qn?qn.logEvent(a,b):(pn.push({type:"EVENT",eventType:a,payload:b}),pn.length>10&&pn.shift()))}
;function yn(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function zn(a){return a.substr(0,a.indexOf(":"))||a}
;var An=De||Ee;function Bn(a){var b=Jc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var Cn={},Dn=(Cn.AUTH_INVALID="No user identifier specified.",Cn.EXPLICIT_ABORT="Transaction was explicitly aborted.",Cn.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Cn.MISSING_INDEX="Index not created.",Cn.MISSING_OBJECT_STORES="Object stores not created.",Cn.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Cn.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Cn.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Cn.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Cn.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Cn.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Cn.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Cn),En={},Fn=(En.AUTH_INVALID="ERROR",En.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",En.EXPLICIT_ABORT="IGNORED",En.IDB_NOT_SUPPORTED="ERROR",En.MISSING_INDEX=
"WARNING",En.MISSING_OBJECT_STORES="ERROR",En.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",En.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",En.QUOTA_EXCEEDED="WARNING",En.QUOTA_MAYBE_EXCEEDED="WARNING",En.UNKNOWN_ABORT="WARNING",En.INCOMPATIBLE_DB_VERSION="WARNING",En),Gn={},Hn=(Gn.AUTH_INVALID=!1,Gn.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Gn.EXPLICIT_ABORT=!1,Gn.IDB_NOT_SUPPORTED=!1,Gn.MISSING_INDEX=!1,Gn.MISSING_OBJECT_STORES=!1,Gn.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Gn.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Gn.QUOTA_EXCEEDED=!1,Gn.QUOTA_MAYBE_EXCEEDED=!0,Gn.UNKNOWN_ABORT=!0,Gn.INCOMPATIBLE_DB_VERSION=!1,Gn);function In(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?Dn[a]:c;d=d===void 0?Fn[a]:d;e=e===void 0?Hn[a]:e;V.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,In.prototype)}
y(In,V);function Jn(a,b){In.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Dn.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Jn.prototype)}
y(Jn,In);function Kn(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Kn.prototype)}
y(Kn,Error);var Ln=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Mn(a,b,c,d){b=zn(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof In)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new In("QUOTA_EXCEEDED",a);if(Fe&&e.name==="UnknownError")return new In("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Kn)return new In("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Ln.some(function(f){return e.message.includes(f)}))return new In("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new In("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",od:e.name})];e.level="WARNING";return e}
function Nn(a,b,c){var d=on();return new In("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function On(a){if(!a)throw Error();throw a;}
function Pn(a){return a}
function Qn(a){this.h=a}
function Rn(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=v(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=v(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Rn.all=function(a){return new Rn(new Qn(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={rb:0};f.rb<a.length;f={rb:f.rb},++f.rb)Rn.resolve(a[f.rb]).then(function(g){return function(h){d[g.rb]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
Rn.resolve=function(a){return new Rn(new Qn(function(b,c){a instanceof Rn?a.then(b,c):b(a)}))};
Rn.reject=function(a){return new Rn(new Qn(function(b,c){c(a)}))};
Rn.prototype.then=function(a,b){var c=this,d=a!=null?a:Pn,e=b!=null?b:On;return new Rn(new Qn(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){Sn(c,c,d,f,g)}),c.i.push(function(){Tn(c,c,e,f,g)})):c.state.status==="FULFILLED"?Sn(c,c,d,f,g):c.state.status==="REJECTED"&&Tn(c,c,e,f,g)}))};
Rn.prototype.catch=function(a){return this.then(void 0,a)};
function Sn(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Rn?Un(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Tn(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Rn?Un(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Un(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Rn?Un(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Vn(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Wn(a){return new Promise(function(b,c){Vn(a,b,c)})}
function Xn(a){return new Rn(new Qn(function(b,c){Vn(a,b,c)}))}
;function Yn(a,b){return new Rn(new Qn(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Zn=window,W=Zn.ytcsi&&Zn.ytcsi.now?Zn.ytcsi.now:Zn.performance&&Zn.performance.timing&&Zn.performance.now&&Zn.performance.timing.navigationStart?function(){return Zn.performance.timing.navigationStart+Zn.performance.now()}:function(){return(new Date).getTime()};function $n(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(W());this.i=!1}
n=$n.prototype;n.add=function(a,b,c){return ao(this,[a],{mode:"readwrite",la:!0},function(d){return d.objectStore(a).add(b,c)})};
n.clear=function(a){return ao(this,[a],{mode:"readwrite",la:!0},function(b){return b.objectStore(a).clear()})};
n.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
n.count=function(a,b){return ao(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).count(b)})};
function bo(a,b,c){a=a.h.createObjectStore(b,c);return new co(a)}
n.delete=function(a,b){return ao(this,[a],{mode:"readwrite",la:!0},function(c){return c.objectStore(a).delete(b)})};
n.get=function(a,b){return ao(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).get(b)})};
function eo(a,b,c){return ao(a,[b],{mode:"readwrite",la:!0},function(d){d=d.objectStore(b);return Xn(d.h.put(c,void 0))})}
n.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function ao(a,b,c,d){var e,f,g,h,k,l,m,p,r,t,w,x;return z(function(C){switch(C.h){case 1:var F={mode:"readonly",la:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?F.mode=c:Object.assign(F,c);e=F;a.transactionCount++;f=e.la?3:1;g=0;case 2:if(h){C.B(4);break}g++;k=Math.round(W());Aa(C,5);l=a.h.transaction(b,e.mode);F=C.yield;var K=new fo(l);K=go(K,d);return F.call(C,K,7);case 7:return m=C.i,p=Math.round(W()),ho(a,k,p,g,void 0,b.join(),e),C.return(m);case 5:r=Ba(C);t=Math.round(W());w=Mn(r,
a.h.name,b.join(),a.h.version);if((x=w instanceof In&&!w.h)||g>=f)ho(a,k,t,g,w,b.join(),e),h=w;C.B(2);break;case 4:return C.return(Promise.reject(h))}})}
function ho(a,b,c,d,e,f,g){b=c-b;e?(e instanceof In&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&xn("QUOTA_EXCEEDED",{dbName:zn(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof In&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=Math.pow(2,31)&&(c=0),xn("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),io(a,!1,d,f,b,g.tag),wn(e)):io(a,!0,d,f,b,g.tag)}
function io(a,b,c,d,e,f){xn("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
n.getName=function(){return this.h.name};
function co(a){this.h=a}
n=co.prototype;n.add=function(a,b){return Xn(this.h.add(a,b))};
n.autoIncrement=function(){return this.h.autoIncrement};
n.clear=function(){return Xn(this.h.clear()).then(function(){})};
function jo(a,b,c){a.h.createIndex(b,c,{unique:!1})}
n.count=function(a){return Xn(this.h.count(a))};
function ko(a,b){return lo(a,{query:b},function(c){return c.delete().then(function(){return mo(c)})}).then(function(){})}
n.delete=function(a){return a instanceof IDBKeyRange?ko(this,a):Xn(this.h.delete(a))};
n.get=function(a){return Xn(this.h.get(a))};
n.index=function(a){try{return new no(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Kn(a,this.h.name);throw b;}};
n.getName=function(){return this.h.name};
n.keyPath=function(){return this.h.keyPath};
function lo(a,b,c){a=a.h.openCursor(b.query,b.direction);return oo(a).then(function(d){return Yn(d,c)})}
function fo(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=In;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function go(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return v(d).next().value})}
fo.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new In("EXPLICIT_ABORT");};
fo.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new co(a),this.i.set(a,b));return b};
function no(a){this.h=a}
n=no.prototype;n.count=function(a){return Xn(this.h.count(a))};
n.delete=function(a){return po(this,{query:a},function(b){return b.delete().then(function(){return mo(b)})})};
n.get=function(a){return Xn(this.h.get(a))};
n.keyPath=function(){return this.h.keyPath};
n.unique=function(){return this.h.unique};
function po(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return oo(a).then(function(d){return Yn(d,c)})}
function qo(a,b){this.request=a;this.cursor=b}
function oo(a){return Xn(a).then(function(b){return b?new qo(a,b):null})}
function mo(a){a.cursor.continue(void 0);return oo(a.request)}
qo.prototype.delete=function(){return Xn(this.cursor.delete()).then(function(){})};
qo.prototype.getValue=function(){return this.cursor.value};
qo.prototype.update=function(a){return Xn(this.cursor.update(a))};function ro(a,b,c){return new Promise(function(d,e){function f(){r||(r=new $n(g.result,{closed:p}));return r}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Od,k=c.blocking,l=c.ef,m=c.upgrade,p=c.closed,r;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&xn("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:zn(a)});var w=f(),x=new fo(g.transaction);
m&&m(w,function(C){return t.oldVersion<C&&t.newVersion>=C},x);
x.done.catch(function(C){e(C)})}catch(C){e(C)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){xn("IDB_UNEXPECTEDLY_CLOSED",{dbName:zn(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function so(a,b,c){c=c===void 0?{}:c;return ro(a,b,c)}
function to(a,b){b=b===void 0?{}:b;var c,d,e,f;return z(function(g){if(g.h==1)return Aa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Od)&&c.addEventListener("blocked",function(){e()}),g.yield(Wn(c),4);
if(g.h!=2)g.h=0,g.l=0;else throw f=Ba(g),Mn(f,a,"",-1);})}
;function uo(a,b){this.name=a;this.options=b;this.j=!0;this.v=this.l=0}
uo.prototype.i=function(a,b,c){c=c===void 0?{}:c;return so(a,b,c)};
uo.prototype.delete=function(a){a=a===void 0?{}:a;return to(this.name,a)};
function vo(a,b){return new In("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function wo(a,b){if(!b)throw Nn("openWithToken",zn(a.name));return a.open()}
uo.prototype.open=function(){function a(){var f,g,h,k,l,m,p,r,t,w;return z(function(x){switch(x.h){case 1:return g=(f=Error().stack)!=null?f:"",Aa(x,2),x.yield(c.i(c.name,c.options.version,e),4);case 4:for(var C=h=x.i,F=c.options,K=[],N=v(Object.keys(F.xb)),S=N.next();!S.done;S=N.next()){S=S.value;var da=F.xb[S],va=da.He===void 0?Number.MAX_VALUE:da.He;!(C.h.version>=da.Fb)||C.h.version>=va||C.h.objectStoreNames.contains(S)||K.push(S)}k=K;if(k.length===0){x.B(5);break}l=Object.keys(c.options.xb);
m=h.objectStoreNames();if(c.v<Cl("ytidb_reopen_db_retries",0))return c.v++,h.close(),wn(new In("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());if(!(c.l<Cl("ytidb_remake_db_retries",1))){x.B(6);break}c.l++;return x.yield(c.delete(),7);case 7:return wn(new In("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),x.return(a());case 6:throw new Jn(m,l);case 5:return x.return(h);case 2:p=Ba(x);
if(p instanceof DOMException?p.name!=="VersionError":"DOMError"in self&&p instanceof DOMError?p.name!=="VersionError":!(p instanceof Object&&"message"in p)||p.message!=="An attempt was made to open a database using a lower version than the existing version."){x.B(8);break}return x.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:r=x.i;t=r.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw r.close(),c.j=!1,vo(c,t);return x.return(r);case 8:throw b(),p instanceof
Error&&!U("ytidb_async_stack_killswitch")&&(p.stack=p.stack+"\n"+g.substring(g.indexOf("\n")+1)),Mn(p,c.name,"",(w=c.options.version)!=null?w:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw vo(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,ef:b,upgrade:this.options.upgrade};return this.h=d=a()};var xo=new uo("YtIdbMeta",{xb:{databases:{Fb:1}},upgrade:function(a,b){b(1)&&bo(a,"databases",{keyPath:"actualName"})}});
function yo(a,b){var c;return z(function(d){if(d.h==1)return d.yield(wo(xo,b),2);c=d.i;return d.return(ao(c,["databases"],{la:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Xn(f.h.put(a,void 0)).then(function(){})})}))})}
function zo(a,b){var c;return z(function(d){if(d.h==1)return a?d.yield(wo(xo,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Ao(a,b){var c,d;return z(function(e){return e.h==1?(c=[],e.yield(wo(xo,b),2)):e.h!=3?(d=e.i,e.yield(ao(d,["databases"],{la:!0,mode:"readonly"},function(f){c.length=0;return lo(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return mo(g)})}),3)):e.return(c)})}
function Bo(a){return Ao(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function Co(a,b,c){return Ao(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function Do(a){var b,c;return z(function(d){if(d.h==1)return b=Em("YtIdbMeta hasAnyMeta other"),d.yield(Ao(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var Eo,Fo=new function(){}(new function(){});
function Go(){var a,b,c,d;return z(function(e){switch(e.h){case 1:a=on();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=An)f=/WebKit\/([0-9]+)/.exec(Jc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Jc()),f=!(f&&parseInt(f[1],10)>=602));if(f||Wc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
Aa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(yo(d,Fo),4);case 4:return e.yield(zo("yt-idb-test-do-not-use",Fo),5);case 5:return e.return(!0);case 2:return Ba(e),e.return(!1)}})}
function Ho(){if(Eo!==void 0)return Eo;rn=!0;return Eo=Go().then(function(a){rn=!1;var b;if((b=nn())!=null&&b.h){var c;b={hasSucceededOnce:((c=on())==null?void 0:c.hasSucceededOnce)||a};var d;(d=nn())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Io(){return E("ytglobal.idbToken_")||void 0}
function Jo(){var a=Io();return a?Promise.resolve(a):Ho().then(function(b){(b=b?Fo:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var Ko=0;function Lo(a,b){Ko||(Ko=Ri.pa(function(){var c,d,e,f,g;return z(function(h){switch(h.h){case 1:return h.yield(Jo(),2);case 2:c=h.i;if(!c)return h.return();d=!0;Aa(h,3);return h.yield(Co(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.B(6);break}f=e[0];return h.yield(to(f.actualName),7);case 7:return h.yield(zo(f.actualName,c),6);case 6:h.h=4;h.l=0;break;case 3:g=Ba(h),wn(g),d=!1;case 4:Ri.qa(Ko),Ko=0,d&&Lo(a,b),h.h=0}})}))}
function Mo(){var a;return z(function(b){return b.h==1?b.yield(Jo(),2):(a=b.i)?b.return(Do(a)):b.return(!1)})}
new Ai;function No(a){if(!Dm())throw a=new In("AUTH_INVALID",{dbName:a}),wn(a),a;var b=Em();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Oo(a,b,c,d){var e,f,g,h,k,l;return z(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(Jo(),2);case 2:g=m.i;if(!g)throw h=Nn("openDbImpl",a,b),U("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),wn(h),h;yn(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:No(a);Aa(m,3);return m.yield(yo(k,g),5);case 5:return m.yield(so(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=Ba(m),Aa(m,7),m.yield(zo(k.actualName,
g),9);case 9:m.h=8;m.l=0;break;case 7:Ba(m);case 8:throw l;}})}
function Po(a,b,c){c=c===void 0?{}:c;return Oo(a,b,!1,c)}
function Qo(a,b,c){c=c===void 0?{}:c;return Oo(a,b,!0,c)}
function Ro(a,b){b=b===void 0?{}:b;var c,d;return z(function(e){if(e.h==1)return e.yield(Jo(),2);if(e.h!=3){c=e.i;if(!c)return e.return();yn(a);d=No(a);return e.yield(to(d.actualName,b),3)}return e.yield(zo(d.actualName,c),0)})}
function So(a,b,c){a=a.map(function(d){return z(function(e){return e.h==1?e.yield(to(d.actualName,b),2):e.yield(zo(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function To(){var a=a===void 0?{}:a;var b,c;return z(function(d){if(d.h==1)return d.yield(Jo(),2);if(d.h!=3){b=d.i;if(!b)return d.return();yn("LogsDatabaseV2");return d.yield(Bo(b),3)}c=d.i;return d.yield(So(c,a,b),0)})}
function Uo(a,b){b=b===void 0?{}:b;var c;return z(function(d){if(d.h==1)return d.yield(Jo(),2);if(d.h!=3){c=d.i;if(!c)return d.return();yn(a);return d.yield(to(a,b),3)}return d.yield(zo(a,c),0)})}
;function Vo(a,b){uo.call(this,a,b);this.options=b;yn(a)}
y(Vo,uo);function Wo(a,b){var c;return function(){c||(c=new Vo(a,b));return c}}
Vo.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Qo:Po)(a,b,Object.assign({},c))};
Vo.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Uo:Ro)(this.name,a)};
function Xo(a,b){return Wo(a,b)}
;var Yo={},Zo=Xo("ytGcfConfig",{xb:(Yo.coldConfigStore={Fb:1},Yo.hotConfigStore={Fb:1},Yo),shared:!1,upgrade:function(a,b){b(1)&&(jo(bo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),jo(bo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function $o(a){return wo(Zo(),a)}
function ap(a,b,c){var d,e,f;return z(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:W()},g.yield($o(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(eo(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function bp(a,b,c,d){var e,f,g;return z(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:W()},h.yield($o(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(eo(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function cp(a){var b,c;return z(function(d){return d.h==1?d.yield($o(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(ao(b,["coldConfigStore"],{mode:"readwrite",la:!0},function(e){return po(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function dp(a){var b,c;return z(function(d){return d.h==1?d.yield($o(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(ao(b,["hotConfigStore"],{mode:"readwrite",la:!0},function(e){return po(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function ep(){G.call(this);this.i=[];this.h=[];var a=E("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(la(a)),this.h=a):(this.h=[],D("yt.gcf.config.hotUpdateCallbacks",this.h))}
y(ep,G);ep.prototype.U=function(){for(var a=v(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;G.prototype.U.call(this)};function fp(){this.h=0;this.i=new ep}
function gp(){var a;return(a=E("yt.gcf.config.hotConfigGroup"))!=null?a:T("RAW_HOT_CONFIG_GROUP")}
function hp(a,b,c){var d,e,f;return z(function(g){switch(g.h){case 1:if(!U("start_client_gcf")){g.B(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.l(b);d=Io();if(!d){g.B(3);break}if(c){g.B(4);break}return g.yield(dp(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(ap(c,b,d),3);case 3:if(c)for(var h=c,k=v(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function ip(a,b,c){var d,e,f,g;return z(function(h){if(h.h==1){if(!U("start_client_gcf"))return h.B(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Io())?c?h.B(4):h.yield(cp(d),5):h.B(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.B(0);g=c.configData;return h.yield(bp(c,b,g,d),0)})}
function jp(){if(!fp.h){var a=new fp;fp.h=a}a=fp.h;var b=W()-a.h;if(!(a.h!==0&&b<Cl("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=W());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
fp.prototype.l=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function kp(){return"INNERTUBE_API_KEY"in cl&&"INNERTUBE_API_VERSION"in cl}
function lp(){return{innertubeApiKey:T("INNERTUBE_API_KEY"),innertubeApiVersion:T("INNERTUBE_API_VERSION"),ke:T("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),jd:T("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Kg:T("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:T("INNERTUBE_CONTEXT_CLIENT_VERSION"),me:T("INNERTUBE_CONTEXT_HL"),le:T("INNERTUBE_CONTEXT_GL"),ne:T("INNERTUBE_HOST_OVERRIDE")||"",pe:!!T("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),oe:!!T("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:T("SERIALIZED_CLIENT_CONFIG_DATA")}}
function mp(a){var b={client:{hl:a.me,gl:a.le,clientName:a.jd,clientVersion:a.innertubeContextClientVersion,configInfo:a.ke}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=B.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=T("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=Dl();c.length>0&&(b.request={internalExperimentFlags:c});c=a.jd;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=gm()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(U("web_log_memory_total_kbytes")&&((e=B.navigator)==null?0:e.deviceMemory)){var f;e=(f=B.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=Bm())&&b&&(b.client.connectionType=a);U("web_log_effective_connection_type")&&
(a=Cm())&&b&&(b.client.effectiveConnectionType=a);U("start_client_gcf")&&(e=jp())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));T("DELEGATED_SESSION_ID")&&!U("pageid_as_header_web")&&(b.user={onBehalfOfUser:T("DELEGATED_SESSION_ID")});!U("fill_delegate_context_in_gel_killswitch")&&(a=T("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=v(Object.entries(ql(T("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=v(g.value);g=h.next().value;h=h.next().value;g==="cbrand"?d.deviceMake=h:g==="cmodel"?d.deviceModel=h:g==="cbr"?d.browserName=h:g==="cbrver"?d.browserVersion=h:g==="cos"?d.osName=h:g==="cosver"?d.osVersion=h:g==="cplatform"&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function np(a,b,c){c=c===void 0?{}:c;var d={};T("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":T("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||T("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||T("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().Cg:(a=jm(im()),U("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var op=typeof TextEncoder!=="undefined"?new TextEncoder:null,pp=op?function(a){return op.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function qp(a,b){this.version=a;this.args=b}
qp.prototype.serialize=function(){return{version:this.version,args:this.args}};function rp(a,b){this.topic=a;this.h=b}
rp.prototype.toString=function(){return this.topic};var sp=E("ytPubsub2Pubsub2Instance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.Bb;M.prototype.publish=M.prototype.Ya;M.prototype.clear=M.prototype.clear;D("ytPubsub2Pubsub2Instance",sp);var tp=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",tp);var up=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",up);var vp=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",vp);
D("ytPubsub2Pubsub2SkipSubKey",null);function wp(a,b){var c=xp();c&&c.publish.call(c,a.toString(),a,b)}
function yp(a){var b=zp,c=xp();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(tp[d])try{if(f&&b instanceof rp&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Ed){var l=new h;h.Ed=l.version}var m=h.Ed}catch(C){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{m=Reflect;var p=m.construct;
var r=k.args,t=r.length;if(t>0){var w=Array(t);for(k=0;k<t;k++)w[k]=r[k];var x=w}else x=[];f=p.call(m,h,x)}catch(C){throw C.message="yt.pubsub2.Data.deserialize(): "+C.message,C;}}catch(C){throw C.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+C.message,C;}a.call(window,f)}catch(C){il(C)}},vp[b.toString()]?E("yt.scheduler.instance")?Ri.pa(g):zl(g,0):g())});
tp[d]=!0;up[b.toString()]||(up[b.toString()]=[]);up[b.toString()].push(d);return d}
function Ap(){var a=Bp,b=yp(function(c){a.apply(void 0,arguments);Cp(b)});
return b}
function Cp(a){var b=xp();b&&(typeof a==="number"&&(a=[a]),Db(a,function(c){b.unsubscribeByKey(c);delete tp[c]}))}
function xp(){return E("ytPubsub2Pubsub2Instance")}
;function Dp(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&wp("meta_logging_csi_event",{timerName:a,ah:b})}
;var Ep=void 0,Fp=void 0;function Gp(){Fp||(Fp=Fk(T("WORKER_SERIALIZATION_URL")));return Fp||void 0}
function Hp(){var a=Gp();Ep||a===void 0||(Ep=new Worker(kb(a),void 0));return Ep}
;var Ip=Cl("max_body_size_to_compress",5E5),Jp=Cl("min_body_size_to_compress",500),Kp=!0,Lp=0,Mp=0,Np=Cl("compression_performance_threshold_lr",250),Op=Cl("slow_compressions_before_abandon_count",4),Pp=!1,Qp=new Map,Rp=1,Sp=!0;function Tp(){if(typeof Worker==="function"&&Gp()&&!Pp){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Qp.get(c.key);d&&(Up(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Qp.delete(c.key))}},b=Hp();
b&&(b.addEventListener("message",a),b.onerror=function(){Qp.clear()},Pp=!0)}}
function Vp(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:W(),ticks:{},infos:{}};if(Kp)try{var g=Wp(b);if(g!=null&&(g>Ip||g<Jp))d(a,c);else{if(U("gzip_gel_with_worker")&&(U("initial_gzip_use_main_thread")&&!Sp||!U("initial_gzip_use_main_thread"))){Pp||Tp();var h=Hp();if(h&&!e){Qp.set(Rp,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Rp});Rp++;return}}var k=Ek(pp(b));Up(k,f,a,c,d)}}catch(l){jl(l),d(a,c)}else d(a,c)}
function Up(a,b,c,d,e){Sp=!1;var f=W();b.ticks.gelc=f;Mp++;U("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Np&&(Lp++,U("abandon_compression_after_N_slow_zips")?Mp===Cl("compression_disable_point")&&Lp>Op&&(Kp=!1):Kp=!1);Xp(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Yp(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=W(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(Kp&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Wp(g);if(h!=null&&(h>Ip||h<Jp))return a;c=b?{level:1}:void 0;f=Ek(pp(g),c);var k=W();e.ticks.gelc=k;if(b){Mp++;if((U("disable_compression_due_to_performance_degredation")||U("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Np)if(Lp++,U("abandon_compression_after_N_slow_zips")||U("abandon_compression_after_N_slow_zips_lr")){b=Lp/Mp;var l=Op/Cl("compression_disable_point");Mp>0&&Mp%Cl("compression_disable_point")===0&&b>=l&&(Kp=!1)}else Kp=!1;Xp(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return jl(m),a}}else return a}
function Wp(a){try{return(new Blob(a.split(""))).size}catch(b){return jl(b),null}}
function Xp(a){U("gel_compression_csi_killswitch")||!U("log_gel_compression_latency")&&!U("log_gel_compression_latency_lr")||Dp("gel_compression",a,{sampleRate:.1})}
;function Zp(a){a=Object.assign({},a);delete a.Authorization;var b=qh();if(b){var c=new Vi;c.update(T("INNERTUBE_API_KEY"));c.update(b);a.hash=Ie(c.digest(),3)}return a}
;var $p;function aq(){$p||($p=new mn("yt.innertube"));return $p}
function bq(a,b,c,d){if(d)return null;d=aq().get("nextId",!0)||1;var e=aq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Zp(c),requestTime:Math.round(W())};aq().set("nextId",d+1,86400,!0);aq().set("requests",e,86400,!0);return d}
function cq(a){var b=aq().get("requests",!0)||{};delete b[a];aq().set("requests",b,86400,!0)}
function dq(a){var b=aq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(W())-d.requestTime<6E4)){var e=d.authState,f=Zp(np(!1));Qb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(W())),eq(a,d.method,e,{}));delete b[c]}}aq().set("requests",b,86400,!0)}}
;function fq(a){this.Xb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.pb=function(){};
this.now=Date.now;this.Ib=!1;var b;this.Bd=(b=a.Bd)!=null?b:100;var c;this.vd=(c=a.vd)!=null?c:1;var d;this.sd=(d=a.sd)!=null?d:2592E6;var e;this.qd=(e=a.qd)!=null?e:12E4;var f;this.ud=(f=a.ud)!=null?f:5E3;var g;this.X=(g=a.X)!=null?g:void 0;this.dc=!!a.dc;var h;this.ac=(h=a.ac)!=null?h:.1;var k;this.mc=(k=a.mc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.pb&&(this.pb=a.pb);a.Ib&&(this.Ib=a.Ib);a.Xb&&(this.Xb=a.Xb);this.Y=a.Y;this.Da=a.Da;this.ha=a.ha;this.fa=a.fa;this.sendFn=a.sendFn;
this.Kc=a.Kc;this.Hc=a.Hc;gq(this)&&(!this.Y||this.Y("networkless_logging"))&&hq(this)}
function hq(a){gq(a)&&!a.Ib&&(a.h=!0,a.dc&&Math.random()<=a.ac&&a.ha.Qd(a.X),iq(a),a.fa.va()&&a.Sb(),a.fa.listen(a.Kc,a.Sb.bind(a)),a.fa.listen(a.Hc,a.Wc.bind(a)))}
n=fq.prototype;n.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(gq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ha.set(d,this.X).then(function(e){d.id=e;c.fa.va()&&jq(c,d)}).catch(function(e){jq(c,d);
kq(c,e)})}else this.sendFn(a,b)};
n.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(gq(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Y&&this.Y("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.va()||this.Y&&this.Y("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return z(function(k){if(k.h==1)return k.yield(d.ha.set(e,d.X).catch(function(l){kq(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ha.set(e,this.X).catch(function(g){d.sendFn(a,b,e.skipRetry);
kq(d,g)})}else this.sendFn(a,b,this.Y&&this.Y("nwl_skip_retry")&&c)};
n.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(gq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ha.ob(d.id,c.X):e=!0;c.fa.gb&&c.Y&&c.Y("vss_network_hint")&&c.fa.gb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ha.set(d,this.X).then(function(g){d.id=g;e&&c.ha.ob(d.id,c.X)}).catch(function(g){kq(c,g)})}else this.sendFn(a,b,void 0,!0)};
n.Sb=function(){var a=this;if(!gq(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Da.pa(function(){var b;return z(function(c){if(c.h==1)return c.yield(a.ha.ed("NEW",a.X),2);if(c.h!=3)return b=c.i,b?c.yield(jq(a,b),3):(a.Wc(),c.return());a.i&&(a.i=0,a.Sb());c.h=0})},this.Bd))};
n.Wc=function(){this.Da.qa(this.i);this.i=0};
function jq(a,b){var c;return z(function(d){switch(d.h){case 1:if(!gq(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.B(2);break}return d.yield(a.ha.te(b.id,a.X),3);case 3:(c=d.i)||a.pb(Error("The request cannot be found in the database."));case 2:if(lq(a,b,a.sd)){d.B(4);break}a.pb(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.B(5);break}return d.yield(a.ha.ob(b.id,a.X),5);case 5:return d.return();case 4:b.skipRetry||(b=mq(a,
b));if(!b){d.B(0);break}if(!b.skipRetry||b.id===void 0){d.B(8);break}return d.yield(a.ha.ob(b.id,a.X),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function mq(a,b){if(!gq(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return z(function(m){switch(m.h){case 1:g=nq(f);(h=oq(f))&&a.Y&&a.Y("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.Y&&a.Y("nwl_consider_error_code")&&g||a.Y&&!a.Y("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.mc)){m.B(2);break}if(!a.fa.pc){m.B(3);break}return m.yield(a.fa.pc(),3);case 3:if(a.fa.va()){m.B(2);break}c(e,f);if(!a.Y||!a.Y("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.B(6);
break}return m.yield(a.ha.Lc(b.id,a.X,!1),6);case 6:return m.return();case 2:if(a.Y&&a.Y("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.mc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.B(8);break}return b.sendCount<a.vd?m.yield(a.ha.Lc(b.id,a.X,!0,h?!1:void 0),12):m.yield(a.ha.ob(b.id,a.X),8);case 12:a.Da.pa(function(){a.fa.va()&&a.Sb()},a.ud);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return z(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.B(2):h.yield(a.ha.ob(b.id,a.X),2);a.fa.gb&&a.Y&&a.Y("vss_network_hint")&&a.fa.gb(!0);d(e,f);h.h=0})};
return b}
function lq(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function iq(a){if(!gq(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ha.ed("QUEUED",a.X).then(function(b){b&&!lq(a,b,a.qd)?a.Da.pa(function(){return z(function(c){if(c.h==1)return b.id===void 0?c.B(2):c.yield(a.ha.Lc(b.id,a.X),2);iq(a);c.h=0})}):a.fa.va()&&a.Sb()})}
function kq(a,b){a.Hd&&!a.fa.va()?a.Hd(b):a.handleError(b)}
function gq(a){return!!a.X||a.Xb}
function nq(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function oq(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var pq;
function qq(){if(pq)return pq();var a={};pq=Xo("LogsDatabaseV2",{xb:(a.LogsRequestsStore={Fb:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&bo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),jo(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return pq()}
;function rq(a){return wo(qq(),a)}
function sq(a,b){var c,d,e,f;return z(function(g){if(g.h==1)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(rq(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:T("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(eo(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=W();tq(c);return g.return(f)})}
function uq(a,b){var c,d,e,f,g,h,k,l;return z(function(m){if(m.h==1)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(rq(b),2);if(m.h!=3)return d=m.i,e=T("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,W()],h=IDBKeyRange.bound(f,g),k="prev",U("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(ao(d,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(p){return po(p.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(r){r.getValue()&&(l=r.getValue(),a==="NEW"&&(l.status="QUEUED",r.update(l)))})}),3);
c.ticks.tc=W();tq(c);return m.return(l)})}
function vq(a,b){var c;return z(function(d){if(d.h==1)return d.yield(rq(b),2);c=d.i;return d.return(ao(c,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Xn(f.h.put(g,void 0)).then(function(){return g})})}))})}
function wq(a,b,c,d){c=c===void 0?!0:c;var e;return z(function(f){if(f.h==1)return f.yield(rq(b),2);e=f.i;return f.return(ao(e,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),Xn(h.h.put(k,void 0)).then(function(){return k})):Rn.resolve(void 0)})}))})}
function xq(a,b){var c;return z(function(d){if(d.h==1)return d.yield(rq(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function yq(a){var b,c;return z(function(d){if(d.h==1)return d.yield(rq(a),2);b=d.i;c=W()-2592E6;return d.yield(ao(b,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){return lo(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return mo(f)})})}),0)})}
function zq(){z(function(a){return a.yield(To(),0)})}
function tq(a){U("nwl_csi_killswitch")||Dp("networkless_performance",a,{sampleRate:1})}
;var Aq={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,
mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,
kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,mdeExporterEvent:497,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,externalVideoShareToYoutubeAttempt:501,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,mangoDailyNewVideosNotificationAttempt:40,
mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,cruiseControlEvent:445,qoeClientLoggingContext:446,
atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,
cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,shortsCreationFallbackEvent:493,vssData:491,castMatch:494,miniAppPerformanceMetrics:495,userFeedbackEvent:496,
kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500};var Bq={},Cq=Xo("ServiceWorkerLogsDatabase",{xb:(Bq.SWHealthLog={Fb:1},Bq),shared:!0,upgrade:function(a,b){b(1)&&jo(bo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function Dq(a){return wo(Cq(),a)}
function Eq(a){var b,c;z(function(d){if(d.h==1)return d.yield(Dq(a),2);b=d.i;c=W()-2592E6;return d.yield(ao(b,["SWHealthLog"],{mode:"readwrite",la:!0},function(e){return lo(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return mo(f)})})}),0)})}
function Fq(a){var b;return z(function(c){if(c.h==1)return c.yield(Dq(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Gq={},Hq=0;function Iq(a){var b=new Image,c=""+Hq++;Gq[c]=b;b.onload=b.onerror=function(){delete Gq[c]};
b.src=a}
;var Jq;function Kq(){Jq||(Jq=new mn("yt.offline"));return Jq}
function Lq(a){if(U("offline_error_handling")){var b=Kq().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Kq().set("errors",b,2592E3,!0)}}
;function Mq(){this.h=new Map;this.i=!1}
function Nq(){if(!Mq.h){var a=E("yt.networkRequestMonitor.instance")||new Mq;D("yt.networkRequestMonitor.instance",a);Mq.h=a}return Mq.h}
Mq.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Mq.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Mq.prototype.removeParams=function(a){return a.split("?")[0]};
Mq.prototype.removeParams=Mq.prototype.removeParams;Mq.prototype.isEndpointCFR=Mq.prototype.isEndpointCFR;Mq.prototype.requestComplete=Mq.prototype.requestComplete;Mq.getInstance=Nq;function Oq(){wd.call(this);var a=this;this.j=!1;this.i=Qi();this.i.listen("networkstatus-online",function(){if(a.j&&U("offline_error_handling")){var b=Kq().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new V(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;il(d)}Kq().set("errors",{},2592E3,!0)}}})}
y(Oq,wd);function Pq(){if(!Oq.h){var a=E("yt.networkStatusManager.instance")||new Oq;D("yt.networkStatusManager.instance",a);Oq.h=a}return Oq.h}
n=Oq.prototype;n.va=function(){return this.i.va()};
n.gb=function(a){this.i.i=a};
n.ee=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
n.Vd=function(){this.j=!0};
n.listen=function(a,b){return this.i.listen(a,b)};
n.pc=function(a){a=Oi(this.i,a);a.then(function(b){U("use_cfr_monitor")&&Nq().requestComplete("generate_204",b)});
return a};
Oq.prototype.sendNetworkCheckRequest=Oq.prototype.pc;Oq.prototype.listen=Oq.prototype.listen;Oq.prototype.enableErrorFlushing=Oq.prototype.Vd;Oq.prototype.getWindowStatus=Oq.prototype.ee;Oq.prototype.networkStatusHint=Oq.prototype.gb;Oq.prototype.isNetworkAvailable=Oq.prototype.va;Oq.getInstance=Pq;function Qq(a){a=a===void 0?{}:a;wd.call(this);var b=this;this.i=this.m=0;this.j=Pq();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Rq(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Rq(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){xd(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){xd(b,"publicytnetworkstatus-offline")})))}
y(Qq,wd);Qq.prototype.va=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Qq.prototype.gb=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Qq.prototype.pc=function(a){var b=this,c;return z(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return U("skip_network_check_if_cfr")&&Nq().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.gb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.va())})):c?d.return(c(a)):d.return(!0)})};
function Rq(a,b){a.rateLimit?a.i?(Ri.qa(a.m),a.m=Ri.pa(function(){a.l!==b&&(xd(a,b),a.l=b,a.i=W())},a.rateLimit-(W()-a.i))):(xd(a,b),a.l=b,a.i=W()):xd(a,b)}
;var Sq;function Tq(){var a=fq.call;Sq||(Sq=new Qq({Pg:!0,Ig:!0}));a.call(fq,this,{ha:{Qd:yq,ob:xq,ed:uq,te:vq,Lc:wq,set:sq},fa:Sq,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;jl(new V(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else il(b)},
pb:jl,sendFn:Uq,now:W,Hd:Lq,Da:ln(),Kc:"publicytnetworkstatus-online",Hc:"publicytnetworkstatus-offline",dc:!0,ac:.1,mc:Cl("potential_esf_error_limit",10),Y:U,Ib:!(Dm()&&Vq())});this.j=new Ai;U("networkless_immediately_drop_all_requests")&&zq();Uo("LogsDatabaseV2")}
y(Tq,fq);function Wq(){var a=E("yt.networklessRequestController.instance");a||(a=new Tq,D("yt.networklessRequestController.instance",a),U("networkless_logging")&&Jo().then(function(b){a.X=b;hq(a);a.j.resolve();a.dc&&Math.random()<=a.ac&&a.X&&Eq(a.X);U("networkless_immediately_drop_sw_health_store")&&Xq(a)}));
return a}
Tq.prototype.writeThenSend=function(a,b){b||(b={});b=Yq(a,b);Dm()||(this.h=!1);fq.prototype.writeThenSend.call(this,a,b)};
Tq.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Yq(a,b);Dm()||(this.h=!1);fq.prototype.sendThenWrite.call(this,a,b,c)};
Tq.prototype.sendAndWrite=function(a,b){b||(b={});b=Yq(a,b);Dm()||(this.h=!1);fq.prototype.sendAndWrite.call(this,a,b)};
Tq.prototype.awaitInitialization=function(){return this.j.promise};
function Xq(a){var b;z(function(c){if(!a.X)throw b=Nn("clearSWHealthLogsDb"),b;return c.return(Fq(a.X).catch(function(d){a.handleError(d)}))})}
function Uq(a,b,c,d){d=d===void 0?!1:d;b=U("web_fp_via_jspb")?Object.assign({},b):b;U("use_cfr_monitor")&&Zq(a,b);if(U("use_request_time_ms_header"))b.headers&&tl(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(W())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Hl(a,void 0,"POST",f,void 0);else if(T("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Hl(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new cb({url:a});if(k.j&&k.i||k.l){var l=mc(nc(5,a)),m;if(!(m=!l||!l.endsWith("/aclk"))){var p=a.search(vc),r=uc(a,0,"ri",p);if(r<0)var t=null;else{var w=a.indexOf("&",r);if(w<0||w>p)w=p;t=decodeURIComponent(a.slice(r+3,w!==-1?w:0).replace(/\+/g," "))}m=t!=="1"}var x=!m;break b}}catch(F){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var C=!0;break b}}catch(F){}C=!1}c=C?!0:!1}else c=
!1;c||Iq(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Vp(a,b.postBody,b,Ll,d)):Vp(a,JSON.stringify(b.postParams),b,Kl,d):Ll(a,b)}
function Yq(a,b){U("use_event_time_ms_header")&&tl(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(W())));return b}
function Zq(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Nq().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Nq().requestComplete(a,!0);d(e,f)}}
function Vq(){return oc(document.location.toString())!=="www.youtube-nocookie.com"}
;var $q=!1,ar=B.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:$q};D("ytNetworklessLoggingInitializationOptions",ar);function br(){var a;z(function(b){if(b.h==1)return b.yield(Jo(),2);a=b.i;if(!a||!Dm()&&!U("nwl_init_require_datasync_id_killswitch")||!Vq())return b.B(0);$q=!0;ar.isNwlInitialized=$q;return b.yield(Wq().awaitInitialization(),0)})}
;function cr(a){var b=this;this.config_=null;a?this.config_=a:kp()&&(this.config_=lp());Gm(function(){dq(b)},5E3)}
cr.prototype.isReady=function(){!this.config_&&kp()&&(this.config_=lp());return!!this.config_};
function eq(a,b,c,d){function e(w){w=w===void 0?!1:w;var x;if(d.retry&&h!="www.youtube-nocookie.com"&&(w||U("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(x=bq(b,c,l,k)),x)){var C=g.onSuccess,F=g.onFetchSuccess;g.onSuccess=function(S,da){cq(x);C(S,da)};
c.onFetchSuccess=function(S,da){cq(x);F(S,da)}}try{if(w&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Wq().writeThenSend(t,g):Wq().sendAndWrite(t,g);
else if(d.compress){var K=!d.networklessOptions.writeThenSend;if(g.postBody){var N=g.postBody;typeof N!=="string"&&(N=JSON.stringify(g.postBody));Vp(t,N,g,Ll,K)}else Vp(t,JSON.stringify(g.postParams),g,Kl,K)}else U("web_all_payloads_via_jspb")?Ll(t,g):Kl(t,g)}catch(S){if(S.name==="InvalidAccessError")x&&(cq(x),x=0),jl(Error("An extension is blocking network request."));else throw S;}x&&Gm(function(){dq(a)},5E3)}
!T("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&jl(new V("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new V("innertube xhrclient not ready",b,c,d);il(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(w,x){if(d.onSuccess)d.onSuccess(x)},
onFetchSuccess:function(w){if(d.onSuccess)d.onSuccess(w)},
onError:function(w,x){if(d.onError)d.onError(x)},
onFetchError:function(w){if(d.onError)d.onError(w)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.ne)&&(h=f);var k=a.config_.pe||!1,l=np(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},r=a.config_.oe&&f;r=r&&f.startsWith("Bearer");r||(p.key=a.config_.innertubeApiKey);var t=sl(""+h+m,p||{},!0);(E("ytNetworklessLoggingInitializationOptions")?
ar.isNwlInitialized:$q)?Ho().then(function(w){e(w)}):e(!1)}
;var dr=0,er=Yc?"webkit":Xc?"moz":Vc?"ms":Uc?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++dr});var fr={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function gr(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in fr||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function hr(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
gr.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
gr.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
gr.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var Mb=B.ytEventsEventsListeners||{};D("ytEventsEventsListeners",Mb);var ir=B.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",ir);
function jr(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return Lb(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Ra(e[4])&&Ra(d)&&Qb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function kr(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=jr(a,b,c,d);if(e)return e;e=++ir.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new gr(h);if(!Hd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new gr(h);
h.currentTarget=a;return c.call(a,h)};
g=hl(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),lr()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);Mb[e]=[a,b,c,g,d];return e}
function mr(a){a&&(typeof a=="string"&&(a=[a]),Db(a,function(b){if(b in Mb){var c=Mb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?lr()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete Mb[b]}}))}
var lr=Cd(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function nr(a){this.H=a;this.h=null;this.l=0;this.A=null;this.m=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.W=kr(window,"mousemove",Xa(this.ba,this));a=Xa(this.P,this);typeof a==="function"&&(a=hl(a));this.da=window.setInterval(a,25)}
$a(nr,G);nr.prototype.ba=function(a){a.h===void 0&&hr(a);var b=a.h;a.i===void 0&&hr(a);this.h=new Dd(b,a.i)};
nr.prototype.P=function(){if(this.h){var a=W();if(this.l!=0){var b=this.A,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.l);this.i[this.j]=Math.abs((d-this.m)/this.m)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.H();this.m=d}this.l=a;this.A=this.h;this.j=(this.j+1)%4}};
nr.prototype.U=function(){window.clearInterval(this.da);mr(this.W)};var or={};
function pr(a){var b=a===void 0?{}:a;a=b.De===void 0?!1:b.De;b=b.Wd===void 0?!0:b.Wd;if(E("_lact",window)==null){var c=parseInt(T("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);c==-1&&qr();kr(document,"keydown",qr);kr(document,"keyup",qr);kr(document,"mousedown",qr);kr(document,"mouseup",qr);a?kr(window,"touchmove",function(){rr("touchmove",200)},{passive:!0}):(kr(window,"resize",function(){rr("resize",200)}),b&&kr(window,"scroll",function(){rr("scroll",200)}));
new nr(function(){rr("mouse",100)});
kr(document,"touchstart",qr,{passive:!0});kr(document,"touchend",qr,{passive:!0})}}
function rr(a,b){or[a]||(or[a]=!0,Ri.pa(function(){qr();or[a]=!1},b))}
function qr(){E("_lact",window)==null&&pr();var a=Date.now();D("_lact",a,window);E("_fact",window)==-1&&D("_fact",a,window);(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function sr(){var a=E("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var tr=B.ytPubsubPubsubInstance||new M,xr=B.ytPubsubPubsubSubscribedKeys||{},yr=B.ytPubsubPubsubTopicToKeys||{},zr=B.ytPubsubPubsubIsSynchronous||{};function Ar(a,b){var c=Br();if(c&&b){var d=c.subscribe(a,function(){function e(){xr[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{zr[a]?e():zl(e,0)}catch(g){il(g)}},void 0);
xr[d]=!0;yr[a]||(yr[a]=[]);yr[a].push(d);return d}return 0}
function Cr(a){var b=Br();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Db(a,function(c){b.unsubscribeByKey(c);delete xr[c]}))}
function Dr(a,b){var c=Br();c&&c.publish.apply(c,arguments)}
function Er(a){var b=Br();if(b)if(b.clear(a),a)Fr(a);else for(var c in yr)Fr(c)}
function Br(){return B.ytPubsubPubsubInstance}
function Fr(a){yr[a]&&(a=yr[a],Db(a,function(b){xr[b]&&delete xr[b]}),a.length=0)}
M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.Bb;M.prototype.publish=M.prototype.Ya;M.prototype.clear=M.prototype.clear;D("ytPubsubPubsubInstance",tr);D("ytPubsubPubsubTopicToKeys",yr);D("ytPubsubPubsubIsSynchronous",zr);D("ytPubsubPubsubSubscribedKeys",xr);var Gr=Symbol("injectionDeps");function Hr(a){this.name=a}
Hr.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Ir(a){this.key=a}
function Jr(){this.i=new Map;this.j=new Map;this.h=new Map}
function Kr(a,b){a.i.set(b.oc,b);var c=a.j.get(b.oc);if(c)try{c.Wg(a.resolve(b.oc))}catch(d){c.Ug(d)}}
Jr.prototype.resolve=function(a){return a instanceof Ir?Lr(this,a.key,[],!0):Lr(this,a,[])};
function Lr(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.Dd!==void 0)var e=d.Dd;else if(d.mf)e=d[Gr]?Mr(a,d[Gr],c):[],e=d.mf.apply(d,la(e));else if(d.Cd){e=d.Cd;var f=e[Gr]?Mr(a,e[Gr],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(la(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Zg||a.h.set(b,e);return e}
function Mr(a,b,c){return b?b.map(function(d){return d instanceof Ir?Lr(a,d.key,c,!0):Lr(a,d,c)}):[]}
;var Nr;function Or(){Nr||(Nr=new Jr);return Nr}
;var Pr=window;function Qr(){var a,b;return"h5vcc"in Pr&&((a=Pr.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Pr.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Pr&&Pr.performance.mark&&Pr.performance.measure?2:0}
function Rr(a){var b=Qr();switch(b){case 1:Pr.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Pr.performance.mark(a+"-start");break;case 0:break;default:Xb(b,"unknown trace type")}}
function Sr(a){var b=Qr();switch(b){case 1:Pr.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Pr.performance.mark(c);Pr.performance.measure(a,b,c);break;case 0:break;default:Xb(b,"unknown trace type")}}
;var Tr=U("web_enable_lifecycle_monitoring")&&Qr()!==0,Ur=U("web_enable_lifecycle_monitoring");function Vr(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?ln():d;this.j=c;this.scheduler=d;this.i=new Ai;this.h=a;for(a={cb:0};a.cb<this.h.length;a={lc:void 0,cb:a.cb},a.cb++)a.lc=this.h[a.cb],c=function(e){return function(){e.lc.Ac();b.h[e.cb].nc=!0;b.h.every(function(f){return f.nc===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.lc),d=this.scheduler.ab(c,d),this.h[a.cb]=Object.assign({},a.lc,{Ac:c,
jobId:d})}
function Wr(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=v(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.nc||(a.scheduler.qa(c.jobId),a.scheduler.ab(c.Ac,10))}
Vr.prototype.cancel=function(){for(var a=v(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.nc||this.scheduler.qa(b.jobId),b.nc=!0;this.i.resolve()};
Vr.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function Xr(a){this.state=a;this.plugins=[];this.l=void 0;this.A={};Tr&&Rr(this.state)}
n=Xr.prototype;n.install=function(a){this.plugins.push(a);return this};
n.uninstall=function(){var a=this;A.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
n.transition=function(a,b){var c=this;Tr&&Sr(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Wr(this.j),this.j=void 0);Yr(this,a,b);this.state=a;Tr&&Rr(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Zr(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Zr(a,b){var c=b.filter(function(e){return $r(a,e)===10}),d=b.filter(function(e){return $r(a,e)!==10});
return a.A.Yg?function(){var e=A.apply(0,arguments);return z(function(f){if(f.h==1)return f.yield(a.Ke.apply(a,[c].concat(la(e))),2);a.yd.apply(a,[d].concat(la(e)));f.h=0})}:function(){var e=A.apply(0,arguments);
a.Le.apply(a,[c].concat(la(e)));a.yd.apply(a,[d].concat(la(e)))}}
n.Le=function(a){for(var b=A.apply(1,arguments),c=ln(),d=v(a),e=d.next(),f={};!e.done;f={Lb:void 0},e=d.next())f.Lb=e.value,c.Db(function(g){return function(){as(g.Lb.name);g.Lb.callback.apply(g.Lb,la(b));bs(g.Lb.name)}}(f))};
n.Ke=function(a){var b=A.apply(1,arguments),c,d,e,f,g;return z(function(h){h.h==1&&(c=ln(),d=v(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.B(0);f.tb=e.value;f.Vb=void 0;g=function(k){return function(){as(k.tb.name);var l=k.tb.callback.apply(k.tb,la(b));typeof(l==null?void 0:l.then)==="function"?k.Vb=l.then(function(){bs(k.tb.name)}):bs(k.tb.name)}}(f);
c.Db(g);return f.Vb?h.yield(f.Vb,3):h.B(3)}f={tb:void 0,Vb:void 0};e=d.next();return h.B(2)})};
n.yd=function(a){var b=A.apply(1,arguments),c=this,d=a.map(function(e){return{Ac:function(){as(e.name);e.callback.apply(e,la(b));bs(e.name)},
priority:$r(c,e)}});
d.length&&(this.j=new Vr(d))};
function $r(a,b){var c,d;return(d=(c=a.l)!=null?c:b.priority)!=null?d:0}
function as(a){Tr&&a&&Rr(a)}
function bs(a){Tr&&a&&Sr(a)}
function Yr(a,b,c){Ur&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
fa.Object.defineProperties(Xr.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function cs(a){Xr.call(this,a===void 0?"none":a);this.h=null;this.l=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.v},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var ds;y(cs,Xr);cs.prototype.i=function(a,b){var c=this;this.h=Gm(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
cs.prototype.v=function(a,b){this.h&&(Ri.qa(this.h),this.h=null);a(b==null?void 0:b.event)};
function es(){ds||(ds=new cs);return ds}
;var gs=[];D("yt.logging.transport.getScrapedGelPayloads",function(){return gs});function hs(){this.store={};this.h={}}
hs.prototype.storePayload=function(a,b){a=is(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
hs.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=js(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,la(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,la(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,la(this.smartExtractMatchingEntries(a))));return c};
hs.prototype.extractMatchingEntries=function(a){a=js(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,la(this.store[a[c]])),delete this.store[a[c]]);return b};
hs.prototype.getSequenceCount=function(a){a=js(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function js(a,b){var c=is(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&is(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(ks(b.auth,g[0])){var h=b.isJspb;ks(h===void 0?"undefined":h?"true":"false",g[1])&&ks(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),ks(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function ks(a,b){return a===void 0||a==="undefined"?!0:a===b}
hs.prototype.getSequenceCount=hs.prototype.getSequenceCount;hs.prototype.extractMatchingEntries=hs.prototype.extractMatchingEntries;hs.prototype.smartExtractMatchingEntries=hs.prototype.smartExtractMatchingEntries;hs.prototype.storePayload=hs.prototype.storePayload;function is(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function ls(a,b){if(a)return a[b.name]}
;var ms=Cl("initial_gel_batch_timeout",2E3),ns=Cl("gel_queue_timeout_max_ms",6E4),ps=Math.pow(2,16)-1,qs=Cl("gel_min_batch_size",5),rs=void 0;function ss(){this.l=this.h=this.i=0;this.j=!1}
var ts=new ss,us=new ss,vs=new ss,ws=new ss,xs,ys=!0,zs=B.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",zs);var As={};function Bs(){var a=E("yt.logging.ims");a||(a=new hs,D("yt.logging.ims",a));return a}
function Cs(a,b){if(a.endpoint==="log_event"){Ds();var c=Es(a),d=Fs(a.payload)||"";a:{if(U("enable_web_tiered_gel")){var e=Aq[d||""];var f,g,h,k=Or().resolve(new Ir(fp))==null?void 0:(f=gp())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!U("web_payload_policy_disabled_killswitch"))return;k=Gs(e.tier);if(k===400){Hs(a,b);return}}As[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};Bs().storePayload(e,a.payload);Is(b,c,e,d==="gelDebuggingEvent")}}
function Is(a,b,c,d){function e(){Js({writeThenSend:!0},U("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=f===void 0?!1:f;d=d===void 0?!1:d;a&&(rs=new a);a=Cl("tvhtml5_logging_max_batch_ads_fork")||Cl("web_logging_max_batch")||100;var g=W(),h=Ks(f,c.tier),k=h.l;d&&(h.j=!0);d=0;c&&(d=Bs().getSequenceCount(c));d>=1E3?e():d>=a?xs||(xs=Ls(function(){e();xs=void 0},0)):g-k>=10&&(Ms(f,c.tier),h.l=g)}
function Hs(a,b){if(a.endpoint==="log_event"){Ds();var c=Es(a),d=new Map;d.set(c,[a.payload]);var e=Fs(a.payload)||"";b&&(rs=new b);return new Ud(function(f,g){rs&&rs.isReady()?Ns(d,rs,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Es(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);zs[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Js(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new Ud(function(e,f){var g=Ks(c,d),h=g.j;g.j=!1;Os(g.i);Os(g.h);g.h=0;rs&&rs.isReady()?d===void 0&&U("enable_web_tiered_gel")?Ps(e,f,a,b,c,300,h):Ps(e,f,a,b,c,d,h):(Ms(c,d),e())})}
function Ps(a,b,c,d,e,f,g){var h=rs;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=U("enable_web_tiered_gel")?Bs().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):Bs().extractMatchingEntries(e),k.set(d,f);else for(d=v(Object.keys(As)),l=d.next();!l.done;l=d.next())l=l.value,e=U("enable_web_tiered_gel")?Bs().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):Bs().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(U("web_fp_via_jspb_and_json")&&c.writeThenSend||!U("web_fp_via_jspb_and_json"))&&delete As[l];Ns(k,h,a,b,c,!1,g)}
function Ms(a,b){function c(){Js({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=Ks(a,b),e=d===ws||d===vs?5E3:ns;U("web_gel_timeout_cap")&&!d.h&&(e=Ls(function(){c()},e),d.h=e);
Os(d.i);e=T("LOGGING_BATCH_TIMEOUT",Cl("web_gel_debounce_ms",1E4));U("shorten_initial_gel_batch_timeout")&&ys&&(e=ms);e=Ls(function(){Cl("gel_min_batch_size")>0?Bs().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=qs&&c():c()},e);
d.i=e}
function Ns(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(W()),k=a.size,l=(g===void 0?0:g)&&U("vss_through_gel_video_stats")?"video_stats":"log_event";a=v(a);var m=a.next();for(g={};!m.done;g={Gc:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Jc:void 0,Ic:void 0},m=a.next()){var p=v(m.value);m=p.next().value;p=p.next().value;g.batchRequest=Sb({context:mp(b.config_||lp())});if(!Qa(p)&&!U("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=p;(p=zs[m])&&
Qs(g.batchRequest,m,p);delete zs[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";Rs(g.batchRequest,h,g.dangerousLogToVisitorSession);U("always_send_and_write")&&(e.writeThenSend=!1);g.Jc=function(r){U("start_client_gcf")&&Ri.pa(function(){return z(function(t){return t.yield(Ss(r),0)})});
k--;k||c()};
g.Gc=0;g.Ic=function(r){return function(){r.Gc++;if(e.bypassNetworkless&&r.Gc===1)try{eq(b,l,r.batchRequest,Ts({writeThenSend:!0},r.dangerousLogToVisitorSession,r.Jc,r.Ic,f)),ys=!1}catch(t){il(t),d()}k--;k||c()}}(g);
try{eq(b,l,g.batchRequest,Ts(e,g.dangerousLogToVisitorSession,g.Jc,g.Ic,f)),ys=!1}catch(r){il(r),d()}}}
function Ts(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,Eg:!!e,headers:{},postBodyFormat:"",postBody:"",compress:U("compress_gel")||U("compress_gel_lr")};Us()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));return a}
function Rs(a,b,c){Us()||(a.requestTimeMs=String(b));U("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=T("EVENT_ID"))&&((c=T("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*ps/2)),c++,c>ps&&(c=1),dl("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Qs(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Ds(){var a;(a=E("yt.logging.transport.enableScrapingForTest"))||(a=Bl("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(gs=[],D("yt.logging.transport.enableScrapingForTest",!0),D("yt.logging.transport.scrapedPayloadsForTesting",gs),D("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),D("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
D("yt.logging.transport.scrapeClientEvent",!0))}
function Us(){return U("use_request_time_ms_header")||U("lr_use_request_time_ms_header")}
function Ls(a,b){return U("transport_use_scheduler")===!1?zl(a,b):U("logging_avoid_blocking_during_navigation")||U("lr_logging_avoid_blocking_during_navigation")?Gm(function(){if(es().currentState==="none")a();else{var c={};es().install((c.none={callback:a},c))}},b):Gm(a,b)}
function Os(a){U("transport_use_scheduler")?Ri.qa(a):window.clearTimeout(a)}
function Ss(a){var b,c,d,e,f,g,h,k,l,m;return z(function(p){return p.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=ls(d,Jk),g=(f=d)==null?void 0:f.hotHashData,h=ls(d,Ik),l=(k=d)==null?void 0:k.coldHashData,(m=Or().resolve(new Ir(fp)))?g?e?p.yield(hp(m,g,e),2):p.yield(hp(m,g),2):p.B(2):p.return()):l?h?p.yield(ip(m,l,h),0):p.yield(ip(m,l),0):p.B(0)})}
function Ks(a,b){b=b===void 0?200:b;return a?b===300?ws:us:b===300?vs:ts}
function Fs(a){a=Object.keys(a);a=v(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,Aq[b])return b}
function Gs(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Vs=B.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",Vs);
function Ws(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||W());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=sr();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!U("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Vs[b]=b in Vs?Vs[b]+1:0,a.sequence={index:Vs[b],groupKey:b},d.endOfSequence&&delete Vs[d.sequenceGroup]);(d.sendIsolatedPayload?Hs:Cs)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function vn(a,b,c){c=c===void 0?{}:c;var d=cr;T("ytLoggingEventsDefaultDisabled",!1)&&cr===cr&&(d=null);U("web_all_payloads_via_jspb")&&!c.timestamp&&(c.lact=sr(),c.timestamp=W());Ws(a,b,d,c)}
;D("ytLoggingGelSequenceIdObj_",B.ytLoggingGelSequenceIdObj_||{});var Xs=new Set,Ys=0,Zs=0,$s=0,at=[],bt=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function un(a){ct(a)}
function dt(a){ct(a,"WARNING")}
function et(a){a instanceof Error?ct(a):(a=Ra(a)?JSON.stringify(a):String(a),a=new V(a),a.name="RejectedPromiseError",dt(a))}
function ct(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||T("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||T("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),U("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(Ys>=5))){d=at;var k=fc(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var p=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var r=0;r<a.args.length&&!(p=cm(a.args[r],"params."+r,c,p),
p>=500);r++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(r in t){if(t[r]){var w="params."+r,x=em(t[r]);c[w]=x;p+=w.length+x.length;if(p>500)break}}else c.params=em(t)}if(d.length)for(r=0;r<d.length&&!(p=cm(d[r],"params.context."+r,c,p),p>=500);r++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);r={message:e,name:f,lineNumber:m,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(r.lineNumber=
r.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Zl();c=v(a.Va);for(d=c.next();!d.done;d=c.next())if(d=d.value,r.message&&r.message.match(d.Qg)){a=d.weight;break a}a=v(a.Sa);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(r)){a=c.weight;break a}a=1}r.sampleWeight=a;a=v(Ul);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.kc[r.name])for(e=v(c.kc[r.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=r.message.match(f.regexp)){r.params["params.error.original"]=d[0];e=f.groups;f={};
for(m=0;m<e.length;m++)f[e[m]]=d[m+1],r.params["params.error."+e[m]]=d[m+1];r.message=c.Ec(f);break}r.params||(r.params={});a=Zl();r.params["params.errorServiceSignature"]="msg="+a.Va.length+"&cb="+a.Sa.length;r.params["params.serviceWorker"]="false";B.document&&B.document.querySelectorAll&&(r.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));ib("sample").constructor!==gb&&(r.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&window.yterr(r);
if(r.sampleWeight!==0&&!Xs.has(r.message)){if(g&&U("web_enable_error_204"))ft(b===void 0?"ERROR":b,r);else{b=b===void 0?"ERROR":b;b==="ERROR"?($l.Ya("handleError",r),U("record_app_crashed_web")&&$s===0&&r.sampleWeight===1&&($s++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},U("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:r.message}}}}),vn("appCrashed",g)),Zs++):b==="WARNING"&&$l.Ya("handleWarning",r);if(U("kevlar_gel_error_routing")){g=b;h=h===
void 0?{}:h;b:{a=v(bt);for(c=a.next();!c.done;c=a.next())if(Bn(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:r.stack};r.fileName&&(c.filename=r.fileName);a=r.lineNumber&&r.lineNumber.split?r.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:r.message,errorClassName:r.name,
sampleWeight:r.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];T("FEXP_EXPERIMENTS")&&(h.experimentIds=T("FEXP_EXPERIMENTS"));d=T("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!el("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=v(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=r.params)for(e=v(Object.keys(d)),
f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=T("SERVER_NAME");e=T("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(vn("clientError",h),(g==="ERROR"||U("errors_flush_gel_always_killswitch"))&&Js(void 0,void 0,!1))}U("suppress_error_204_logging")||ft(b,r)}try{Xs.add(r.message)}catch(C){}Ys++}}}
function ft(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:T("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=v(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=T("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=v(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=T("SERVER_NAME");b=T("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Ll(T("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function gt(){this.register=new Map}
function ht(a){a=v(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Tg("ABORTED")}
gt.prototype.clear=function(){ht(this);this.register.clear()};
var jt=new gt;var kt=Date.now().toString();
function lt(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(kt)for(a=1,b=0;b<kt.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^kt.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var mt,nt=B.ytLoggingDocDocumentNonce_;nt||(nt=lt(),D("ytLoggingDocDocumentNonce_",nt));mt=nt;function ot(a){this.h=a}
n=ot.prototype;n.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
n.getAsJspb=function(){var a=new Qk;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&J(a,2,Nf(this.h.veType)),this.h.veCounter!==void 0&&J(a,6,Nf(this.h.veCounter)),this.h.elementIndex!==void 0&&J(a,3,Nf(this.h.elementIndex)),this.h.isCounterfactual&&J(a,5,Jf(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();Ig(a,Qk,7,b)}this.h.youtubeData!==void 0&&Ig(a,Kk,8,this.h.jspbYoutubeData);return a};
n.toString=function(){return JSON.stringify(this.getAsJson())};
n.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
n.getLoggingDirectives=function(){return this.h.loggingDirectives};function pt(a){return T("client-screen-nonce-store",{})[a===void 0?0:a]}
function qt(a,b){b=b===void 0?0:b;var c=T("client-screen-nonce-store");c||(c={},dl("client-screen-nonce-store",c));c[b]=a}
function rt(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function st(a){return T(rt(a===void 0?0:a))}
D("yt_logging_screen.getRootVeType",st);function tt(){var a=T("csn-to-ctt-auth-info");a||(a={},dl("csn-to-ctt-auth-info",a));return a}
function ut(){return Object.values(T("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function vt(a){a=pt(a===void 0?0:a);if(!a&&!T("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",vt);function wt(a,b,c){var d=tt();(c=vt(c))&&delete d[c];b&&(d[a]=b)}
function xt(a){return tt()[a]}
D("yt_logging_screen.getCttAuthInfo",xt);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==pt(c)||b!==T(rt(c)))if(wt(a,d,c),qt(a,c),dl(rt(c),b),b=function(){setTimeout(function(){a&&vn("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:mt,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function zt(){var a=Rb(At),b;return(new Ud(function(c,d){a.onSuccess=function(e){yl(e)?c(new Bt(e)):d(new Ct("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Ct("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Ct("Request timed out","net.timeout",e))};
b=Ll("//googleads.g.doubleclick.net/pagead/id",a)})).qc(function(c){if(c instanceof ae){var d;
(d=b)==null||d.abort()}return Zd(c)})}
function Ct(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
y(Ct,bb);function Bt(a){this.xhr=a}
;function Dt(){this.h=0;this.i=null}
Dt.prototype.then=function(a,b,c){return this.h===1&&a?(a=a.call(c,this.i))&&typeof a.then==="function"?a:Et(a):this.h===2&&b?(a=b.call(c,this.i))&&typeof a.then==="function"?a:Ft(a):this};
Dt.prototype.getValue=function(){return this.i};
Dt.prototype.isRejected=function(){return this.h==2};
Dt.prototype.$goog_Thenable=!0;function Ft(a){var b=new Dt;a=a===void 0?null:a;b.h=2;b.i=a===void 0?null:a;return b}
function Et(a){var b=new Dt;a=a===void 0?null:a;b.h=1;b.i=a===void 0?null:a;return b}
;function Gt(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:tl(a)?"same-origin":"cors",credentials:tl(a)?"same-origin":"include"};b={};for(var d=v(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Ht(){return oh()||(De||Ee)&&Bn("applewebkit")&&!Bn("version")&&(!Bn("safari")||Bn("gsa/"))||Zc&&Bn("version/")?!0:T("EOM_VISITOR_DATA")?!1:!0}
;function It(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Ok)if(Ok[d]==c.embeddedPlayerMode){b=Ok[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function Jt(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Kt;this.isTimeout=a instanceof Ct&&a.errorCode=="net.timeout";this.isCanceled=a instanceof ae}
y(Jt,bb);Jt.prototype.name="BiscottiError";function Kt(){bb.call(this,"Biscotti ID is missing from server")}
y(Kt,bb);Kt.prototype.name="BiscottiMissingError";var At={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Lt=null;function Mt(){if(U("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Ht())return Error("User has not consented - not fetching biscotti id.");var a=T("PLAYER_VARS",{});if(Pb(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(It(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Xk(){var a=Mt();if(a!==void 0)return Zd(a);Lt||(Lt=zt().then(Nt).qc(function(b){return Ot(2,b)}));
return Lt}
function Nt(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Kt;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Kt;a=a.id;Yk(a);Lt=Et(a);Pt(18E5,2);return a}
function Ot(a,b){b=new Jt(b);Yk("");Lt=Ft(b);a>0&&Pt(12E4,a-1);throw b;}
function Pt(a,b){zl(function(){zt().then(Nt,function(c){return Ot(b,c)}).qc(Bd)},a)}
function Qt(){try{var a=E("yt.ads.biscotti.getId_");return a?a():Xk()}catch(b){return Zd(b)}}
;var Bb=ja(["data-"]);function Rt(a){a&&(a.dataset?a.dataset[St()]="true":Wb(a))}
function Tt(a){return a?a.dataset?a.dataset[St()]:a.getAttribute("data-loaded"):null}
var Ut={};function St(){return Ut.loaded||(Ut.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function Vt(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||Rb(b);this.assets=a.assets||{};this.attrs=a.attrs||Rb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Vt.prototype.clone=function(){var a=new Vt,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];Pa(c)=="object"?a[b]=Rb(c):a[b]=c}return a};var Wt=["share/get_web_player_share_panel"],Xt=["feedback"],Yt=["notification/modify_channel_preference"],Zt=["browse/edit_playlist"],$t=["subscription/subscribe"],au=["subscription/unsubscribe"];var bu=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",bu);function cu(a){Zk(bu,arguments)}
;function du(a,b,c){eu(a,b,c===void 0?null:c)}
function fu(a){a=gu(a);var b=document.getElementById(a);b&&(Er(a),b.parentNode.removeChild(b))}
function hu(a,b){a&&b&&(a=""+Sa(b),(a=iu[a])&&Cr(a))}
function eu(a,b,c){c=c===void 0?null:c;var d=gu(a),e=document.getElementById(d),f=e&&Tt(e),g=e&&!f;f?b&&b():(b&&(f=Ar(d,b),b=""+Sa(b),iu[b]=f),g||(e=ju(a,d,function(){Tt(e)||(Rt(e),Dr(d),zl(function(){Er(d)},0))},c)))}
function ju(a,b,c,d){d=d===void 0?null:d;var e=Gd("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);dc(e,Gk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function gu(a){var b=document.createElement("a");zb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+kc(a)}
var iu={};function ku(a){var b=lu(a),c=document.getElementById(b),d=c&&Tt(c);d||c&&!d||(c=mu(a,b,function(){if(!Tt(c)){Rt(c);Dr(b);var e=Ya(Er,b);zl(e,0)}}))}
function mu(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Gk(a);Zb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function lu(a){var b=Gd("A");zb(b,new sb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+kc(a)}
;function nu(a){var b=A.apply(1,arguments);if(!ou(a)||b.some(function(d){return!ou(d)}))throw Error("Only objects may be merged.");
b=v(b);for(var c=b.next();!c.done;c=b.next())pu(a,c.value)}
function pu(a,b){for(var c in b)if(ou(b[c])){if(c in a&&!ou(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});pu(a[c],b[c])}else if(qu(b[c])){if(c in a&&!qu(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);ru(a[c],b[c])}else a[c]=b[c];return a}
function ru(a,b){b=v(b);for(var c=b.next();!c.done;c=b.next())c=c.value,ou(c)?a.push(pu({},c)):qu(c)?a.push(ru([],c)):a.push(c);return a}
function ou(a){return typeof a==="object"&&!Array.isArray(a)}
function qu(a){return typeof a==="object"&&Array.isArray(a)}
;function su(a){a=a===void 0?!1:a;G.call(this);this.h=new M(a);Ec(this,this.h)}
$a(su,G);su.prototype.subscribe=function(a,b,c){return this.V?0:this.h.subscribe(a,b,c)};
su.prototype.unsubscribe=function(a,b,c){return this.V?!1:this.h.unsubscribe(a,b,c)};
su.prototype.l=function(a,b){this.V||this.h.Ya.apply(this.h,arguments)};var tu="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function uu(a,b){var c=c===void 0?!0:c;var d=T("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=oc(window.location.href);e&&d.push(e);e=oc(a);if(Cb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),zb(d,a),a=d.href)if(a=pc(a),a=qc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:vt()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&vu(a,b,f)}else vu(a,b)}
function vu(a,b,c){a=wu(a);b=b?sc(b):"";c=c||5;Ht()&&lm(a,b,c)}
function wu(a){for(var b=v(tu),c=b.next();!c.done;c=b.next())a=xc(a,c.value);return"ST-"+kc(a).toString(36)}
;function xu(a){qp.call(this,1,arguments);this.csn=a}
y(xu,qp);var zp=new rp("screen-created",xu),yu=[],zu=0,Au=new Map,Bu=new Map,Cu=new Map;
function Du(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Eu({cttAuthInfo:xt(b)||void 0},b),g=v(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(Nb(k)||!k.trackingParams&&!k.veType)&&dt(Error("Child VE logged with no data"));if(U("no_client_ve_attach_unless_shown")){var l=Fu(h,b);if(k.veType&&!Bu.has(l)&&!Cu.has(l)&&!e){if(!U("il_attach_cache_limit")||Au.size<1E3){Au.set(l,[a,b,c,h]);return}U("il_attach_cache_limit")&&Au.size>1E3&&dt(new V("IL Attach cache exceeded limit"))}h=Fu(c,b);Au.has(h)?
Gu(c,b):Cu.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Fb(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?Hu("visualElementAttached",f,c):a?Ws("visualElementAttached",c,a,f):vn("visualElementAttached",c,f)}
function Hu(a,b,c){yu.push({Ce:a,payload:c,Mg:void 0,options:b});zu||(zu=Ap())}
function Bp(a){if(yu){for(var b=v(yu),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,vn(c.Ce,c.payload,c.options));yu.length=0}zu=0}
function Fu(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Gu(a,b){a=Fu(a,b);Au.has(a)&&(b=Au.get(a)||[],Du(b[0],b[1],b[2],[b[3]],!0),Au.delete(a))}
function Eu(a,b){U("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Iu(){try{return!!self.localStorage}catch(a){return!1}}
;function Ju(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Ku(a){if(Iu()){var b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Ju(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Lu(){if(!Iu())return!1;var a=Em(),b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Ju(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Mu(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(T("INNERTUBE_CLIENT_NAME")==="WEB"||T("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Nu(a){if(T("LOGGED_IN",!0)&&Mu()){var b=T("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=oc(window.location.href);c&&b.push(c);c=oc(a);Cb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=pc(a),(b=qc(b))?(b=wu(b),b=(b=mm(b)||null)?ql(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Mu()?(d||(d=T("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&uu(a,b)}}
;function Ou(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=T("EVENT_ID");d&&(b.ei||(b.ei=d));b&&uu(a,b);if(c)return!1;Nu(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;a=tc(a,e);Nu(a);f=a+f;var h=h===void 0?wb:h;a:if(h=h===void 0?wb:h,f instanceof sb)h=f;else{for(a=0;a<h.length;++a)if(b=h[a],b instanceof ub&&b.qe(f)){h=new sb(f);break a}h=void 0}g=g.location;h=yb(h||tb);h!==void 0&&(g.href=h);return!0}
;function Pu(a){if(Pb(T("PLAYER_VARS",{}))!="1"){a&&Wk();try{Qt().then(function(){},function(){}),zl(Pu,18E5)}catch(b){il(b)}}}
;var Qu=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Ru(){var a=a===void 0?window.location.href:a;if(U("kevlar_disable_theme_param"))return null;mc(nc(5,a));try{var b=rl(a).theme;return Qu.get(b)||null}catch(c){}return null}
;function Su(){this.h={};if(this.i=om()){var a=mm("CONSISTENCY");a&&Tu(this,{encryptedTokenJarContents:a})}}
Su.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Oa.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=v(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Tu(this,a)}};
function Tu(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&lm("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Uu=window.location.hostname.split(".").slice(-2).join(".");function Vu(){this.j=-1;var a=T("LOCATION_PLAYABILITY_TOKEN");T("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=Wu(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Xu;function Yu(){Xu=E("yt.clientLocationService.instance");Xu||(Xu=new Vu,D("yt.clientLocationService.instance",Xu));return Xu}
n=Vu.prototype;
n.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.l||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.l||
this.locationPlayabilityToken};
n.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,T("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=Wu(this))&&this.h.set("yt-location-playability-token",a,15552E3):lm("YT_CL",JSON.stringify({loctok:a}),15552E3,Uu,!0))};
function Wu(a){return a.h===void 0?new mn("yt-client-location"):a.h}
n.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=Wu(this))&&this.h.remove("yt-location-playability-token"):nm("YT_CL");this.l=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
n.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;T("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
n.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
n.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function Zu(a){var b={"Content-Type":"application/json"};T("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=T("EOM_VISITOR_DATA"):T("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=T("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=T("LOGGED_IN",!1);T("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=T("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=T("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=T("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=T("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=T("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;function $u(){this.h={}}
$u.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
$u.prototype.get=function(a){if(this.contains(a))return this.h[a]};
$u.prototype.set=function(a,b){this.h[a]=b};
$u.prototype.remove=function(a){delete this.h[a]};function av(){this.mappings=new $u}
av.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
av.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=Xb(b)}}return a};
new av;function bv(a){return function(){return new a}}
;var cv={},dv=(cv.WEB_UNPLUGGED="^unplugged/",cv.WEB_UNPLUGGED_ONBOARDING="^unplugged/",cv.WEB_UNPLUGGED_OPS="^unplugged/",cv.WEB_UNPLUGGED_PUBLIC="^unplugged/",cv.WEB_CREATOR="^creator/",cv.WEB_KIDS="^kids/",cv.WEB_EXPERIMENTS="^experiments/",cv.WEB_MUSIC="^music/",cv.WEB_REMIX="^music/",cv.WEB_MUSIC_EMBEDDED_PLAYER="^music/",cv.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",cv);
function ev(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=dv[b];if(c){c=new RegExp(c);for(var d=v(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(dv).forEach(function(g){var h=v(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=v(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function fv(){}
fv.prototype.v=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?km:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=f===void 0?!1:f;e=e===void 0?!1:e;var g=T("INNERTUBE_CONTEXT");if(g){g=Sb(g);U("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;h.clientName==="MWEB"&&h.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(h.clientFormFactor=T("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=
window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=k===void 0?!1:k;sm();var l="USER_INTERFACE_THEME_LIGHT";wm(165)?l="USER_INTERFACE_THEME_DARK":wm(174)?l="USER_INTERFACE_THEME_LIGHT":!U("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");
k=k?l:Ru()||l;h.userInterfaceTheme=k;if(!f){if(k=Bm())h.connectionType=k;U("web_log_effective_connection_type")&&(k=Cm())&&(g.client.effectiveConnectionType=k)}var m;if(U("web_log_memory_total_kbytes")&&((m=B.navigator)==null?0:m.deviceMemory)){var p;m=(p=B.navigator)==null?void 0:p.deviceMemory;g.client.memoryTotalKbytes=""+m*1E6}U("web_gcf_hashes_innertube")&&(k=jp())&&(p=k.coldConfigData,m=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},p&&(g.client.configInfo.coldConfigData=
p),m&&(g.client.configInfo.coldHashData=m),k&&(g.client.configInfo.hotHashData=k));p=rl(B.location.href);!U("web_populate_internal_geo_killswitch")&&p.internalcountrycode&&(h.internalGeo=p.internalcountrycode);h.clientName==="MWEB"||h.clientName==="WEB"?(h.mainAppWebInfo={graftUrl:B.location.href},U("kevlar_woffle")&&fm.h&&(p=fm.h,h.mainAppWebInfo.pwaInstallabilityStatus=!p.h&&p.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=gm(),
h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):h.clientName==="TVHTML5"&&(!U("web_lr_app_quality_killswitch")&&(p=T("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:p})),p=T("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:p}));if(!U("web_populate_time_zone_itc_killswitch")){b:{if(typeof Intl!=="undefined")try{var r=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(ea){}r=
void 0}r&&(h.timeZone=r)}(r=T("EXPERIMENTS_TOKEN",""))?h.experimentsToken=r:delete h.experimentsToken;r=Dl();Su.h||(Su.h=new Su);h=Su.h.h;p=[];m=0;for(var t in h)p[m++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:r,consistencyTokenJars:p});!U("web_prequest_context_killswitch")&&(t=T("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=t);r=sm();t=wm(58);r=r.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);r&&(g.user.lockedSafetyMode=
!0);U("warm_op_csn_cleanup")?e&&(f=vt())&&(g.clientScreenNonce=f):!f&&(f=vt())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Yu().setLocationOnInnerTubeContext(g);try{var w=ul(),x=w.bid;delete w.bid;g.adSignalsInfo={params:[],bid:x};var C=v(Object.entries(w));for(var F=C.next();!F.done;F=C.next()){var K=v(F.value),N=K.next().value,S=K.next().value;w=N;x=S;d=void 0;(d=g.adSignalsInfo.params)==null||d.push({key:w,value:""+
x})}var da;if(U("add_ifa_to_tvh5_requests")&&((da=g.client)==null?void 0:da.clientName)==="TVHTML5"){var va=T("INNERTUBE_CONTEXT");va.adSignalsInfo&&(g.adSignalsInfo.advertisingId=va.adSignalsInfo.advertisingId,g.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",g.adSignalsInfo.limitAdTracking=va.adSignalsInfo.limitAdTracking)}}catch(ea){ct(ea)}C=g}else ct(Error("Error: No InnerTubeContext shell provided in ytconfig.")),C={};C={context:C};if(F=this.i(a)){this.h(C,F,b);var P;
b="/youtubei/v1/"+ev(this.j());(F=(P=ls(a.commandMetadata,Mk))==null?void 0:P.apiUrl)&&(b=F);P=b;(b=T("INNERTUBE_HOST_OVERRIDE"))&&(P=String(b)+String(pc(P)));b={};U("web_api_key_killswitch")&&(b.key=T("INNERTUBE_API_KEY"));U("json_condensed_response")&&(b.prettyPrint="false");P=sl(P,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:P,ib:Gt(P),Oa:C,config:a};a.config.Wb?a.config.Wb.identity=c:a.config.Wb={identity:c};return a}ct(new V("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(fv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function gv(){}
y(gv,fv);function hv(){}
y(hv,gv);hv.prototype.v=function(){return{input:"/getDatasyncIdsEndpoint",ib:Gt("/getDatasyncIdsEndpoint","GET"),Oa:{}}};
hv.prototype.j=function(){return[]};
hv.prototype.i=function(){};
hv.prototype.h=function(){};var iv={},jv=(iv.GET_DATASYNC_IDS=bv(hv),iv);function kv(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function lv(){var a=kv();a.info||(a.info={});return a.info}
function mv(a){a=kv(a);a.metadata||(a.metadata={});return a.metadata}
function nv(a){a=kv(a);a.tick||(a.tick={});return a.tick}
function ov(a){a=kv(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function pv(a){a=ov(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function qv(a){var b=kv(a).nonce;b||(b=lt(),kv(a).nonce=b);return b}
;function rv(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function sv(a){a=a||"";var b=E("ytcsi.reference");b||(rv(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=rv(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},tv=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
X["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",X["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",X["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",X["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",X["asset.history"]="LATENCY_ACTION_CREATOR_CMS_ASSET_HISTORY",X["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",X["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",X["asset.metadata"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",X["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",X["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",X["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",X["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",X["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",X["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",X["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",
X["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",X["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",X["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",
X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",X["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",
X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",
X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",
X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",X["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",X["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",X["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",X["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",X["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",X["owner.bulk"]=
"LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",X["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",X["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",X["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",X["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",X["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",
X["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",X["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",X["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",X["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",X["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",X["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",X["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",X["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",X.parent_profile_settings=
"LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",
X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest="LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",
X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",
X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",
X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",X["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",
X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X);function uv(a,b){qp.call(this,1,arguments);this.timer=b}
y(uv,qp);var vv=new rp("aft-recorded",uv);var wv=B.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",wv);function xv(){this.h=0}
function yv(){xv.h||(xv.h=new xv);return xv.h}
xv.prototype.tick=function(a,b,c,d){zv(this,"tick_"+a+"_"+b)||vn("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
xv.prototype.info=function(a,b,c){var d=Object.keys(a).join("");zv(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,vn("latencyActionInfo",a,{cttAuthInfo:c}))};
xv.prototype.jspbInfo=function(){};
xv.prototype.span=function(a,b,c){var d=Object.keys(a).join("");zv(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,vn("latencyActionSpan",a,{cttAuthInfo:c}))};
function zv(a,b){wv[b]=wv[b]||{count:0};var c=wv[b];c.count++;c.time=W();a.h||(a.h=Gm(function(){var d=W(),e;for(e in wv)wv[e]&&d-wv[e].time>6E4&&delete wv[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new V("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||dt(c)),!0):!1}
;var Av=window;function Bv(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Cv(){var a;if(U("csi_use_performance_navigation_timing")||U("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Dv(e.requestStart),e.responseEnd=Dv(e.responseEnd),e.redirectStart=Dv(e.redirectStart),e.redirectEnd=Dv(e.redirectEnd),e.domainLookupEnd=Dv(e.domainLookupEnd),e.connectStart=Dv(e.connectStart),e.connectEnd=
Dv(e.connectEnd),e.responseStart=Dv(e.responseStart),e.secureConnectionStart=Dv(e.secureConnectionStart),e.domainLookupStart=Dv(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=U("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Dv(a){return Math.round(Ev()+a)}
function Ev(){return(U("csi_use_time_origin")||U("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=Av.performance||Av.mozPerformance||Av.msPerformance||Av.webkitPerformance||new Bv;var Fv=!1,Gv=!1,Hv={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Xa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||Bd,Y);function Iv(a,b){if(!U("web_csi_action_sampling_enabled")||!kv(b).actionDisabled){var c=sv(b||"");nu(c.info,a);a.loadType&&(c=a.loadType,mv(b).loadType=c);nu(pv(b),a);c=qv(b);b=kv(b).cttAuthInfo;yv().info(a,c,b)}}
function Jv(){var a,b,c,d;return((d=Or().resolve(new Ir(fp))==null?void 0:(a=gp())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Z(a,b,c){if(!U("web_csi_action_sampling_enabled")||!kv(c).actionDisabled){var d=qv(c),e;if(e=U("web_csi_debug_sample_enabled")&&d){(Or().resolve(new Ir(fp))==null?0:gp())&&!Gv&&(Gv=!0,Z("gcfl",W(),c));var f,g,h;e=(Or().resolve(new Ir(fp))==null?void 0:(f=gp())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Jv();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=Math.pow(2,47));e=f%1E5%e!==0;kv(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Iv(f,c));kv(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||U("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f-=Y.timeOrigin||Y.timing.navigationStart;try{Y.mark(e,{startTime:f})}catch(k){}}e=sv(c||"");e.tick[a]=b||W();if(e.callback&&e.callback[a])for(e=v(e.callback[a]),f=e.next();!f.done;f=
e.next())f=f.value,f();e=ov(c);e.gelTicks&&(e.gelTicks[a]=!0);f=nv(c);e=b||W();U("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=kv(c).cttAuthInfo;a==="_start"?(a=yv(),zv(a,"baseline_"+d)||vn("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):yv().tick(a,d,b,f);Kv(c);return e}}}
function Lv(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=er+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Mv(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=v(Object.entries(T("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=v(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Nv(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);$b(window)&&a.setAttribute("nonce",$b(window));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Ev(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Ov(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Eb(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Gb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Z("wffs",Dv(b.startTime)),Z("wffe",Dv(b.responseEnd)))}
function Pv(a){var b=Qv("aft",a);if(b)return b;b=T((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Qv(b[d],a);if(e)return e}return NaN}
function Qv(a,b){if(a=nv(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Kv(a){var b=Qv("_start",a),c=Pv(a),d=U("enable_cow_info_csi")||!Fv;b&&c&&d&&(wp(vv,new uv(Math.round(c-b),a)),Fv=!0)}
function Rv(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Hb(a,function(b){return b.name==="first-paint"}))return Dv(a.startTime)}a=Y.timing;
return a.ye?Math.max(0,a.ye):0}
;function Sv(a,b){hl(function(){sv("").info.actionType=a;b&&dl("TIMING_AFT_KEYS",b);dl("TIMING_ACTION",a);var c=Mv();Object.keys(c).length>0&&Iv(c);c={isNavigation:!0,actionType:tv[T("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=T("PREVIOUS_ACTION");d&&(c.previousAction=tv[d]||"LATENCY_ACTION_UNKNOWN");if(d=T("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=T("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=vt())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Lv();if(d===1||d===-1)c.isVisible=!0;mv();lv();
c.loadType="cold";d=lv();var e=Cv(),f=Ev(),g=T("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!U("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Z("srt",e.responseStart),d.prerender!==1&&Z("_start",f,void 0));d=Rv();d>0&&Z("fpt",d);d=Cv();d.isPerformanceNavigationTiming&&Iv({performanceNavigationTiming:!0},void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,
void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Ev()&&d.connectEnd-d.secureConnectionStart>0&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Ov();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Hv)Hv.hasOwnProperty(h)&&(e=Hv[h],
Nv(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=v(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Iv(c);c=ov();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=pv();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(mv().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=nv();e=ov();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Z(k,Qv(k));else if(U("log_repeated_ytcsi_ticks"))for(f=
v(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Z(k.slice(1),g);k={};d=!1;h=v(h);for(e=h.next();!e.done;e=h.next())d=e.value,nu(c,d),nu(k,d),d=!0;d&&Iv(k)}D("ytglobal.timingready_",!0);k=T("TIMING_ACTION");E("ytglobal.timingready_")&&k&&Tv()&&Pv()&&Kv()})()}
function Tv(){return hl(function(){return Uv()})()}
function Vv(a,b,c){hl(Iv)(a,b,c===void 0?!1:c)}
function Wv(a,b,c){return hl(Z)(a,b,c)}
function Uv(){return hl(function(){return"_start"in nv()})()}
function Xv(){hl(function(){var a=qv();requestAnimationFrame(function(){setTimeout(function(){a===qv()&&Wv("ol",void 0,void 0)},0)})})()}
var Yv=window;Yv.ytcsi&&(Yv.ytcsi.infoGel=Vv,Yv.ytcsi.tick=Wv);var Zv="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),$v=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function aw(a,b,c,d){this.v=a;this.fa=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Rb||(a.Rb={});a.Rb=Object.assign({},jv,a.Rb)}
function bw(a,b,c,d){if(aw.h!==void 0){if(d=aw.h,a=[a!==d.v,b!==d.fa,c!==d.l,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new V("InnerTubeTransportService is already initialized",a);
}else aw.h=new aw(a,b,c,d)}
function cw(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?km:c;var d=dw(a,b);return d?new Ud(function(e,f){var g,h,k,l,m;return z(function(p){switch(p.h){case 1:return p.yield(d,2);case 2:g=p.i;h=g.v(b,void 0,c);if(!h){f(new V("Error: Failed to build request for command.",b));p.B(0);break}Nu(h.input);l=((k=h.ib)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.l.df){var r=h.config,t;r=r==null?void 0:(t=r.Wb)==null?void 0:t.sessionIndex;t=jm(0,{sessionIndex:r});m=Object.assign({},
Zu(l),t);p.B(4);break}return p.yield(ew(h.config,l),5);case 5:m=p.i;case 4:e(fw(a,h,m)),p.h=0}})}):Zd(new V("Error: No request builder found for command.",b))}
function gw(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.j){d=v(Zv);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function fw(a,b,c){var d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,p,r,t,w,x,C,F,K,N,S,da,va,P,ea,na,La,Ka,Qg,Rg,ur,vr,wr;return z(function(ha){switch(ha.h){case 1:ha.B(2);break;case 3:if((e=ha.i)&&!e.isExpired())return ha.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Oa)==null?0:g.context)){ha.B(4);break}h=b.Oa.context;ha.B(5);break;case 5:k=v([]),l=k.next();case 7:if(l.done){ha.B(4);break}m=l.value;return ha.yield(m.Sg(h),8);case 8:l=k.next();ha.B(7);break;case 4:if((p=a.i)==null||!p.Xg(b.input,b.Oa)){ha.B(11);break}return ha.yield(a.i.Og(b.input,
b.Oa),12);case 12:return r=ha.i,U("kevlar_process_local_innertube_responses_killswitch")||gw(a,r,b),ha.return(r);case 11:return(x=(w=b.config)==null?void 0:w.Vg)&&a.h.has(x)?t=a.h.get(x):(C=JSON.stringify(b.Oa),N=(K=(F=b.ib)==null?void 0:F.headers)!=null?K:{},b.ib=Object.assign({},b.ib,{headers:Object.assign({},N,c)}),S=Object.assign({},b.ib),b.ib.method==="POST"&&(S=Object.assign({},S,{body:C})),((da=b.config)==null?0:da.Ie)&&Wv(b.config.Ie),va=function(){return a.fa.fetch(b.input,S,b.config)},t=
va(),x&&a.h.set(x,t)),ha.yield(t,13);
case 13:if((P=ha.i)&&"error"in P&&((ea=P)==null?0:(na=ea.error)==null?0:na.details))for(La=P.error.details,Ka=v(La),Qg=Ka.next();!Qg.done;Qg=Ka.next())Rg=Qg.value,(ur=Rg["@type"])&&$v.indexOf(ur)>-1&&(delete Rg["@type"],P=Rg);x&&a.h.has(x)&&a.h.delete(x);((vr=b.config)==null?0:vr.Je)&&Wv(b.config.Je);if(P||(wr=a.i)==null||!wr.Gg(b.input,b.Oa)){ha.B(14);break}return ha.yield(a.i.Ng(b.input,b.Oa),15);case 15:P=ha.i;case 14:return gw(a,P,b),d(),ha.return(P||void 0)}})}
function dw(a,b){a:{a=a.v;var c,d=(c=ls(b,Nk))==null?void 0:c.signal;if(d&&a.Rb&&(c=a.Rb[d])){var e=c();break a}var f;if((c=(f=ls(b,Lk))==null?void 0:f.request)&&a.Sd&&(f=a.Sd[c])){e=f();break a}for(e in b)if(a.Yc[e]&&(b=a.Yc[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function ew(a,b){var c,d,e,f;return z(function(g){if(g.h==1){e=(c=a)==null?void 0:(d=c.Wb)==null?void 0:d.sessionIndex;var h=g.yield;var k=jm(0,{sessionIndex:e});if(!(k instanceof Ud)){var l=new Ud(Bd);Vd(l,2,k);k=l}return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Zu(b),f)))})}
;var hw=new Hr("INNERTUBE_TRANSPORT_TOKEN");function iw(){}
y(iw,gv);iw.prototype.j=function(){return $t};
iw.prototype.i=function(a){return ls(a,Vk)||void 0};
iw.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(iw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function jw(){}
y(jw,gv);jw.prototype.j=function(){return au};
jw.prototype.i=function(a){return ls(a,Uk)||void 0};
jw.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(jw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function kw(){}
y(kw,gv);kw.prototype.j=function(){return Xt};
kw.prototype.i=function(a){return ls(a,Pk)||void 0};
kw.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(kw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function lw(){}
y(lw,gv);lw.prototype.j=function(){return Yt};
lw.prototype.i=function(a){return ls(a,Tk)||void 0};
lw.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function mw(){}
y(mw,gv);mw.prototype.j=function(){return Zt};
mw.prototype.i=function(a){return ls(a,Sk)||void 0};
mw.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function nw(){}
y(nw,gv);nw.prototype.j=function(){return Wt};
nw.prototype.i=function(a){return ls(a,Rk)};
nw.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};function ow(a,b){var c=A.apply(2,arguments);a=a===void 0?0:a;V.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
y(ow,V);var pw=new Hr("NETWORK_SLI_TOKEN");function qw(a){this.h=a}
qw.prototype.fetch=function(a,b,c){var d=this,e;return z(function(f){e=rw(d,a,b);return f.return(fetch(e).then(function(g){return d.handleResponse(g,c)}).catch(function(g){dt(g);
if((c==null?0:c.Yd)&&g instanceof ow&&g.errorType===1)return Promise.reject(g)}))})};
function rw(a,b,c){if(a.h){var d=mc(nc(5,xc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}a=c;U("wug_networking_gzip_request")&&(a=Yp(c));return new window.Request(b,a)}
qw.prototype.handleResponse=function(a,b){var c=a.text().then(function(d){if((b==null?0:b.re)&&a.ok)return Sg(b.re,d);d=d.replace(")]}'","");if((b==null?0:b.Yd)&&d)try{var e=JSON.parse(d)}catch(g){throw new ow(1,"JSON parsing failed after fetch");}var f;return(f=e)!=null?f:JSON.parse(d)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Jg(),c=c.then(function(d){dt(new V("Error: API fetch failed",a.status,a.url,d));return Object.assign({},d,{errorMetadata:{status:a.status}})}));
return c};
qw[Gr]=[new Ir(pw)];var sw=new Hr("NETWORK_MANAGER_TOKEN");var tw;function uw(){var a,b,c;return z(function(d){if(d.h==1)return a=Or().resolve(hw),a?d.yield(cw(a),2):(dt(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return dt(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Hg;return d.return(c)}dt(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function vw(){var a;return(a=T("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var ww=B.caches,xw;function yw(a){var b=a.indexOf(":");return b===-1?{od:a}:{od:a.substring(0,b),datasyncId:a.substring(b+1)}}
function zw(){return z(function(a){if(xw!==void 0)return a.return(xw);xw=new Promise(function(b){var c;return z(function(d){switch(d.h){case 1:return Aa(d,2),d.yield(ww.open("test-only"),4);case 4:return d.yield(ww.delete("test-only"),5);case 5:d.h=3;d.l=0;break;case 2:if(c=Ba(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(xw)})}
function Aw(a){var b,c,d,e,f,g,h;z(function(k){if(k.h==1)return k.yield(zw(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(ww.keys(),3)}c=k.i;d=v(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=yw(f),h=g.datasyncId,!h||a.includes(h)||b.push(ww.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function Bw(){var a,b,c,d,e,f,g;return z(function(h){if(h.h==1)return h.yield(zw(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=Em("cache contains other");return h.yield(ww.keys(),3)}b=h.i;c=v(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=yw(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Cw(){try{return!!self.sessionStorage}catch(a){return!1}}
;function Dw(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Ew(a){if(Cw()){var b=Object.keys(window.sessionStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Dw(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function Fw(){if(!Cw())return!1;var a=Em(),b=Object.keys(window.sessionStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Dw(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Gw(){uw().then(function(a){a&&(Lo(a),Aw(a),Ku(a),Ew(a))})}
function Hw(){var a=new Qq;Ri.pa(function(){var b,c,d,e,f;return z(function(g){switch(g.h){case 1:if(U("ytidb_clear_optimizations_killswitch")){g.B(2);break}b=Em("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Lo(h);Aw(h);Ku(h);Ew(h);return g.return()}c=Lu();d=Fw();return g.yield(Bw(),3);case 3:return e=g.i,g.yield(Mo(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.va()?Gw():a.h.add("publicytnetworkstatus-online",Gw,!0,void 0,void 0),g.h=0}})})}
;function Iw(){this.state=1;this.h=null}
n=Iw.prototype;n.initialize=function(a,b,c){if(a.program){var d,e=(d=a.interpreterUrl)!=null?d:null;if(a.interpreterSafeScript){var f=a.interpreterSafeScript;f?((f=f.privateDoNotAccessOrElseSafeScriptWrappedValue)?(d=fb(),f=new ac(d?d.createScript(f):f)):f=null,d=f):d=null}else d=(f=a.interpreterScript)!=null?f:null;a.interpreterSafeUrl&&(e=Fk(a.interpreterSafeUrl).toString());Jw(this,d,e,a.program,b,c)}else dt(Error("Cannot initialize botguard without program"))};
function Jw(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,du(c,function(){window[g]?Kw(a,d,g,e):(a.state=3,fu(c),dt(new V("Unable to load Botguard","from "+c)))},f)):b?(f=Gd("SCRIPT"),b instanceof ac?cc(f,b):f.textContent=b,f.nonce=$b(window),document.head.appendChild(f),document.head.removeChild(f),window[g]?Kw(a,d,g,e):(a.state=4,dt(new V("Unable to load Botguard from JS")))):dt(new V("Unable to load VM; no url or JS provided"))}
n.isLoading=function(){return this.state===2};
function Kw(a,b,c,d){a.state=5;try{var e=new Bi({program:b,ge:c,Ge:U("att_web_record_metrics"),Ea:"aGIf"});e.Ze.then(function(){a.state=6;d&&d(b)});
a.Mc(e)}catch(f){a.state=7,f instanceof Error&&dt(f)}}
n.invoke=function(a){a=a===void 0?{}:a;return this.Rc()?this.Fd({Zc:a}):null};
n.dispose=function(){this.Mc(null);this.state=8};
n.Rc=function(){return!!this.h};
n.Fd=function(a){return this.h.zd(a)};
n.Mc=function(a){Cc(this.h);this.h=a};var Lw=[],Mw=!1;function Nw(){if(!U("disable_biscotti_fetch_for_ad_blocker_detection")&&!U("disable_biscotti_fetch_entirely_for_all_web_clients")&&Ht()){var a=T("PLAYER_VARS",{});if(Pb(a)!="1"&&!It(a)){var b=function(){Mw=!0;"google_ad_status"in window?dl("DCLKSTAT",1):dl("DCLKSTAT",2)};
try{du("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Lw.push(Ri.pa(function(){if(!(Mw||"google_ad_status"in window)){try{hu("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Mw=!0;dl("DCLKSTAT",3)}},5E3))}}}
function Ow(){var a=Number(T("DCLKSTAT",0));return isNaN(a)?0:a}
;function Pw(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Qw(){Iw.apply(this,arguments)}
y(Qw,Iw);Qw.prototype.Mc=function(a){var b;(b=Pw())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.zd.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
Qw.prototype.Rc=function(){return!!Pw()};
Qw.prototype.Fd=function(a){return Pw().bgvmc(a)};function Rw(a){Xr.call(this,a===void 0?"document_active":a);var b=this;this.l=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.H},{from:"document_active",to:"document_disposed",action:this.v},{from:"document_disposed_preventable",to:"document_disposed",action:this.v},{from:"document_disposed_preventable",to:"flush_logs",action:this.m},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.m},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
y(Rw,Xr);Rw.prototype.H=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Rw.prototype.v=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Rw.prototype.m=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
Rw.prototype.i=function(){this.h=new Map};function Sw(a){Xr.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.m},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.v},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.m},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.m},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.v},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.v},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
U("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
y(Sw,Xr);Sw.prototype.i=function(a,b){a(b==null?void 0:b.event);U("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Sw.prototype.h=function(a,b){a(b==null?void 0:b.event);U("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Sw.prototype.v=function(a,b){a(b==null?void 0:b.event)};
Sw.prototype.m=function(a,b){a(b==null?void 0:b.event)};function Tw(){this.l=new Rw;this.v=new Sw}
Tw.prototype.install=function(){var a=A.apply(0,arguments),b=this;a.forEach(function(c){b.l.install(c)});
a.forEach(function(c){b.v.install(c)})};function Uw(){this.l=[];this.i=new Map;this.h=new Map;this.j=new Set}
Uw.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=vt(c===void 0?0:c)){a=this.client;d=new ot({trackingParams:d});var e=void 0;if(U("no_client_ve_attach_unless_shown")){var f=Fu(d,c);Bu.set(f,!0);Gu(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Eu({cttAuthInfo:xt(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Hu("visualElementGestured",f,d):a?Ws("visualElementGestured",d,a,f):vn("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
Uw.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new ot({trackingParams:a}),b,c===void 0?0:c)};
Uw.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.l.push([a,b]);else{var d=c;d=d===void 0?0:d;c=vt(d);a||(a=(a=st(d===void 0?0:d))?new ot({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Eu({cttAuthInfo:xt(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Hu("visualElementStateChanged",d,b):a?Ws("visualElementStateChanged",b,a,d):vn("visualElementStateChanged",b,d))}};
function Vw(a,b){if(b===void 0)for(var c=ut(),d=0;d<c.length;d++)c[d]!==void 0&&Vw(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Du(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Ww(){Tw.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));U("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));U("web_log_cfg_cee_ks")||Gm(Xw)}
y(Ww,Tw);Ww.prototype.j=function(){vn("finalPayload",{csn:vt()})};
Ww.prototype.h=function(){ht(jt)};
Ww.prototype.i=function(){var a=Vw;Uw.h||(Uw.h=new Uw);a(Uw.h)};
function Xw(){var a=T("CLIENT_EXPERIMENT_EVENTS");if(a){var b=Li();a=v(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&vn("genericClientExperimentEvent",{eventType:c});delete cl.CLIENT_EXPERIMENT_EVENTS}}
;function Yw(){}
function Zw(){var a=E("ytglobal.storage_");a||(a=new Yw,D("ytglobal.storage_",a));return a}
Yw.prototype.estimate=function(){var a,b,c;return z(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return($w()):d.return()})};
function $w(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",Yw);function tn(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
tn.prototype.Ha=function(a){this.handleError(a)};
tn.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":U("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":U("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":ax(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function ax(a,b){Zw().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:bx(c==null?void 0:c.usage),deviceStorageQuotaMbytes:bx(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function bx(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;function cx(a,b,c){G.call(this);var d=this;this.channel="widget";this.sessionId=this.h=this.commands=this.l=null;this.targetOrigin="*";this.j=c||T("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.i=b||null;this.m=!!a;this.listener=function(e){a:if(!(d.j!=="*"&&e.origin!==d.j||d.i&&e.source!==d.i||typeof e.data!=="string")){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(f==null||d.m&&(d.sessionId&&d.sessionId!==f.id||d.channel&&d.channel!==f.channel))&&f)switch(f.event){case "listening":e.origin!==
"null"&&(d.j=d.targetOrigin=e.origin);d.i=e.source;d.sessionId=f.id;d.h&&(d.h(),d.h=null);break;case "command":d.l&&(!d.commands||Cb(d.commands,f.func)>=0)&&d.l(f.func,f.args,e.origin)}}};
window.addEventListener("message",this.listener)}
y(cx,G);cx.prototype.sendMessage=function(a,b){if(b=b||this.i){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){dt(d)}}};
cx.prototype.U=function(){window.removeEventListener("message",this.listener);G.prototype.U.call(this)};var dx={},ex=(dx["api.invalidparam"]=2,dx.auth=150,dx["drm.auth"]=150,dx["heartbeat.net"]=150,dx["heartbeat.servererror"]=150,dx["heartbeat.stop"]=150,dx["html5.unsupportedads"]=5,dx["fmt.noneavailable"]=5,dx["fmt.decode"]=5,dx["fmt.unplayable"]=5,dx["html5.missingapi"]=5,dx["html5.unsupportedlive"]=5,dx["drm.unavailable"]=5,dx["mrm.blocked"]=151,dx["embedder.identity.denied"]=152,dx);var fx=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function gx(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function hx(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=v(fx);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function ix(a,b,c,d){if(Ra(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function jx(){var a=kx;this.l=[];this.isReady=!1;this.v={};this.j=[];this.i=[];this.A=!1;this.m=U("web_player_split_event_bus_iframe");var b=this.h=new cx(!!T("WIDGET_ID_ENFORCE")),c=this.Fe.bind(this);b.l=c;b.commands=null;this.h.channel="widget";if(b=T("WIDGET_ID"))this.h.sessionId=b;this.api=a;lx(this,"onReady",this.onReady.bind(this));lx(this,"onVideoProgress",this.Ue.bind(this));lx(this,"onVolumeChange",this.Ve.bind(this));lx(this,"onApiChange",this.Ne.bind(this));lx(this,"onPlaybackQualityChange",
this.Re.bind(this));lx(this,"onPlaybackRateChange",this.Se.bind(this));lx(this,"onStateChange",this.Te.bind(this));lx(this,"onWebglSettingsChanged",this.We.bind(this));lx(this,"onCaptionsTrackListChanged",this.Oe.bind(this));lx(this,"captionssettingschanged",this.Pe.bind(this))}
n=jx.prototype;
n.Fe=function(a,b,c){if(a==="addEventListener"&&b)a=b[0],a==="onReady"?this.api.logApiCall(a+" invocation",c):a==="onError"&&this.A&&(this.api.logApiCall(a+" invocation",c,this.errorCode),this.errorCode=void 0),this.api.logApiCall(a+" registration",c),this.v[a]||a==="onReady"||(b=mx(this,a,c),this.i.push({eventType:a,listener:b,origin:c}),this.m?this.api.handleExternalCall("addEventListener",[a,b],c):this.api.addEventListener(a,b),this.v[a]=!0);else if(this.api.isExternalMethodAvailable(a,c)){b=b||
[];if(b.length>0&&gx(a)){var d=b;if(Ra(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=hx(d[0],d[1]!==void 0?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];typeof e==="string"&&(e={mediaContentUrl:e,startSeconds:d[1]!==void 0?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=d[2];break b}d=null}e.videoId=d;e=hx(e);break;case "loadPlaylist":case "cuePlaylist":e=
ix(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);gx(a)&&nx(this,ox(this))}};
n.be=function(){this.isReady=!0;this.sendMessage("initialDelivery",ox(this));this.sendMessage("onReady");Db(this.l,this.wd,this);this.l=[]};
function nx(a,b){a.sendMessage("infoDelivery",b)}
n.wd=function(a){this.isReady?this.h.sendMessage(a):this.l.push(a)};
n.sendMessage=function(a,b){this.wd({event:a,info:b===void 0?null:b})};
function mx(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
n.onReady=function(){var a=this.h,b=this.be.bind(this);a.h=b;a=this.api.getVideoData();if(!a.isPlayable){this.A=!0;a=a.errorCode;var c=c===void 0?5:c;this.errorCode=a?ex[a]||c:c;this.sendMessage("onError",this.errorCode.toString())}};
function lx(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function ox(a){if(!a.api)return null;var b=a.api.getApiInterface();Ib(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substr(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
n.Te=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());nx(this,a)};
n.Re=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());nx(this,a)};
n.Se=function(a){nx(this,{playbackRate:a})};
n.Ne=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
n.Ve=function(){nx(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
n.Ue=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());nx(this,a)};
n.We=function(){var a={sphericalProperties:this.api.getSphericalProperties()};nx(this,a)};
n.Oe=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};nx(this,a)}};
n.Pe=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};nx(this,a)}};
n.dispose=function(){this.h=null;for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.m?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};function px(a,b){G.call(this);this.h={};this.started=!1;this.i=U("web_player_split_event_bus_iframe");this.connection=b;this.connection.subscribe("command",this.rd,this);this.api=a;this.start()}
y(px,G);n=px.prototype;n.start=function(){this.started||this.V||(this.started=!0,this.connection.jb("RECEIVING"))};
n.jb=function(a,b){this.started&&!this.V&&this.connection.jb(a,b)};
n.rd=function(a,b,c){if(this.started&&!this.V){var d=b||{};switch(a){case "addEventListener":typeof d.event==="string"&&this.addListener(d.event,c);break;case "removeEventListener":typeof d.event==="string"&&this.removeListener(d.event,c);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=qx(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=rx(a,c))&&this.jb(a,c))}}};
n.addListener=function(a,b,c){a in this.h||(b=this.Qe.bind(this,a),this.h[a]=b,this.addEventListener(a,b,c))};
n.Qe=function(a,b){this.started&&!this.V&&this.connection.jb(a,sx(a,b))};
n.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
n.addEventListener=function(a,b,c){this.i?this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
n.removeEventListener=function(a,b,c){this.i?this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function qx(a,b){switch(a){case "loadVideoById":return a=hx(b),[a];case "cueVideoById":return a=hx(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=ix(b),[a];case "cuePlaylist":return a=ix(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function rx(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function sx(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
n.U=function(){this.connection.unsubscribe("command",this.rd,this);this.connection=null;for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);G.prototype.U.call(this);delete this.api};function tx(a,b,c){su.call(this);this.j=a;this.i=b;this.id=c}
y(tx,su);tx.prototype.jb=function(a,b){this.V||this.j.jb(this.i,this.id,a,b)};
tx.prototype.U=function(){this.i=this.j=null;su.prototype.U.call(this)};function ux(a,b,c){G.call(this);this.h=a;this.origin=c;this.j=kr(window,"message",this.i.bind(this));this.connection=new tx(this,a,b);Ec(this,this.connection)}
y(ux,G);ux.prototype.jb=function(a,b,c,d){this.V||a!==this.h||(a={id:b,command:c},d&&(a.data=d),this.h.postMessage(JSON.stringify(a),this.origin))};
ux.prototype.i=function(a){if(!this.V&&a.origin===this.origin){var b=a.data;if(typeof b==="string"){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.V||c.l("command",b.command,b.data,a.origin)}}}};
ux.prototype.U=function(){mr(this.j);this.h=null;G.prototype.U.call(this)};var vx=new Qw;function wx(){return vx.Rc()}
function xx(a){a=a===void 0?{}:a;return vx.invoke(a)}
;function yx(a,b,c,d,e){G.call(this);var f=this;this.A=b;this.webPlayerContextConfig=d;this.uc=e;this.Za=!1;this.api={};this.ia=this.m=null;this.W=new M;this.h={};this.da=this.xa=this.elementId=this.Cb=this.config=null;this.ba=!1;this.j=this.H=null;this.Ga={};this.vc=["onReady"];this.lastError=null;this.Tb=NaN;this.P={};this.ga=0;this.i=this.l=a;Ec(this,this.W);zx(this);c?this.ga=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(Ax(this),Bx(this))}
y(yx,G);n=yx.prototype;n.getId=function(){return this.A};
n.loadNewVideoConfig=function(a){if(!this.V){this.ga&&(clearTimeout(this.ga),this.ga=0);var b=a||{};b instanceof Vt||(b=new Vt(b));this.config=b;this.setConfig(a);Bx(this);this.isReady()&&Cx(this)}};
function Ax(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.A,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.A:a.config.attrs.id=a.A);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
n.setConfig=function(a){this.Cb=a;this.config=Dx(a);Ax(this);if(!this.xa){var b;this.xa=Ex(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Ji(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Ji(Number(a)||a))};
function Cx(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Fx(a){var b=!0,c=Gx(a);c&&a.config&&(b=c.dataset.version===Hx(a));return b&&!!E("yt.player.Application.create")}
function Bx(a){if(!a.V&&!a.ba){var b=Fx(a);if(b&&(Gx(a)?"html5":null)==="html5")a.da="html5",a.isReady()||Ix(a);else if(Jx(a),a.da="html5",b&&a.j&&a.l)a.l.appendChild(a.j),Ix(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.H=function(){c=!0;var d=Kx(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?Dx(a.config):void 0;d&&d(a.l,e,a.webPlayerContextConfig,a.uc);Ix(a)};
a.ba=!0;b?a.H():(du(Hx(a),a.H),(b=Lx(a))&&ku(b||""),Mx(a)&&!c&&D("yt.player.Application.create",null))}}}
function Gx(a){var b=Fd(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function Ix(a){if(!a.V){var b=Gx(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.ba=!1;if(!Kx(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}Nx(a)}else a.Tb=setTimeout(function(){Ix(a)},50)}}
function Nx(a){zx(a);a.Za=!0;var b=Gx(a);if(b){a.m=Ox(a,b,"addEventListener");a.ia=Ox(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Ox(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.m&&a.m(g,a.h[g]);Cx(a);a.xa&&a.xa(a.api);a.W.Ya("onReady",a.api)}
function Ox(a,b,c){var d=b[c];return function(){var e=A.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new V("PlayerProxy error in method call",{error:f,method:c,playerId:a.A}),e.level="WARNING",e;}}}
function zx(a){a.Za=!1;if(a.ia)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ia(b,a.h[b]);for(var c in a.P)a.P.hasOwnProperty(c)&&clearTimeout(Number(c));a.P={};a.m=null;a.ia=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Cb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
n.isReady=function(){return this.Za};
n.addEventListener=function(a,b){var c=this,d=Ex(this,b);d&&(Cb(this.vc,a)>=0||this.h[a]||(b=Px(this,a),this.m&&this.m(a,b)),this.W.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
n.removeEventListener=function(a,b){this.V||(b=Ex(this,b))&&this.W.unsubscribe(a,b)};
function Ex(a,b){var c=b;if(typeof b==="string"){if(a.Ga[b])return a.Ga[b];c=function(){var d=A.apply(0,arguments),e=E(b);if(e)try{e.apply(B,d)}catch(f){throw d=new V("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.Ga[b]=c}return c?c:null}
function Px(a,b){function c(d){var e=setTimeout(function(){if(!a.V){try{a.W.Ya(b,d!=null?d:void 0)}catch(h){var f=new V("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.A,data:d,originalStack:h.stack});f.level="WARNING";throw f;}f=a.P;var g=String(e);g in f&&delete f[g]}},0);
Ob(a.P,String(e))}
return a.h[b]=c}
n.getPlayerType=function(){return this.da||(Gx(this)?"html5":null)};
n.getLastError=function(){return this.lastError};
function Jx(a){a.cancel();zx(a);a.da=null;a.config&&(a.config.loaded=!1);var b=Gx(a);b&&(Fx(a)||!Mx(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.l)for(a=a.l;b=a.firstChild;)a.removeChild(b)}
n.cancel=function(){this.H&&hu(Hx(this),this.H);clearTimeout(this.Tb);this.ba=!1};
n.U=function(){Jx(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new V("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.Ga=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Cb=this.config=this.api=null;delete this.l;delete this.i;G.prototype.U.call(this)};
function Mx(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function Hx(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Lx(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Kx(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function Dx(a){for(var b={},c=v(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?Rb(e):e}return b}
;var Qx={},Rx="player_uid_"+(Math.random()*1E9>>>0);function Sx(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?Fd(c):c;var e=Rx+"_"+Sa(c),f=Qx[e];if(f&&d)return Tx(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new yx(c,e,a,b,void 0);Qx[e]=f;f.addOnDisposeCallback(function(){delete Qx[f.getId()]});
return f.api}
function Tx(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var kx=null,Ux=null,Vx=null;
function Wx(){Xv();var a=sm(),b=wm(119),c=window.devicePixelRatio>1;if(document.body&&Zi(document.body,"exp-invert-logo"))if(c&&!Zi(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Zi(d,"inverted-hdpi")){var e=Xi(d);Yi(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Zi(document.body,"inverted-hdpi")&&$i();if(b!=c){b="f"+(Math.floor(119/31)+1);d=xm(b)||0;d=c?d|67108864:d&-67108865;d===0?delete pm[b]:(c=d.toString(16),pm[b]=c.toString());
c=!0;U("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in pm)pm.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(pm[f])));var f=d.join("&");lm(b,f,63072E3,a.i,c)}}
function Xx(){Yx()}
function Zx(){Wv("ep_init_pr");Yx()}
function Yx(){var a=kx.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function $x(){kx&&kx.sendAbandonmentPing&&kx.sendAbandonmentPing();T("PL_ATT")&&vx.dispose();for(var a=Ri,b=0,c=Lw.length;b<c;b++)a.qa(Lw[b]);Lw.length=0;fu("//static.doubleclick.net/instream/ad_status.js");Mw=!1;dl("DCLKSTAT",0);Dc(Vx,Ux);kx&&(kx.removeEventListener("onVideoDataChange",Xx),kx.destroy())}
;D("yt.setConfig",dl);D("yt.config.set",dl);D("yt.setMsg",cu);D("yt.msgs.set",cu);D("yt.logging.errors.log",ct);
D("writeEmbed",function(){var a=T("PLAYER_CONFIG");if(!a){var b=T("PLAYER_VARS");b&&(a={args:b})}Pu(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=T("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Sv("embed",["ol"]);c=vw();if(!c.serializedForcedExperimentIds){var d=rl(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=
d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)&&Sv("watch",["pbs","pbu","pbp"]);kx=Sx(a,c);kx.addEventListener("onVideoDataChange",Xx);kx.addEventListener("onReady",Zx);a=T("POST_MESSAGE_ID","player");T("ENABLE_JS_API")?Vx=new jx:T("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(Ux=new ux(window.parent,a,b),Vx=new px(kx,Ux.connection));Nw();U("ytidb_create_logger_embed_killswitch")||sn();a={};Ww.h||(Ww.h=new Ww);Ww.h.install((a.flush_logs={callback:function(){Js()}},a));
br();U("ytidb_clear_embedded_player")&&Ri.pa(function(){var f,g;if(!tw){var h=Or();Kr(h,{oc:sw,Cd:qw});var k={Yc:{feedbackEndpoint:bv(kw),modifyChannelNotificationPreferenceEndpoint:bv(lw),playlistEditEndpoint:bv(mw),subscribeEndpoint:bv(iw),unsubscribeEndpoint:bv(jw),webPlayerShareEntityServiceEndpoint:bv(nw)}},l=Yu(),m={};l&&(m.client_location=l);f===void 0&&(f=im());g===void 0&&(g=h.resolve(sw));bw(k,g,f,m);Kr(h,{oc:hw,Dd:aw.h});tw=h.resolve(hw)}Hw()})});
D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||wx);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||xx);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||Ow);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||Ou);D("yt.util.activity.init",E("yt.util.activity.init")||pr);D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||sr);
D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||qr);window.addEventListener("load",hl(function(){Wx()}));
window.addEventListener("pageshow",hl(function(a){a.persisted||Wx()}));
window.addEventListener("pagehide",hl(function(a){U("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?$x():a.persisted||$x()}));
window.onerror=function(a,b,c,d,e){b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var f=!1,g=el("log_window_onerror_fraction");if(g&&Math.random()<g)f=!0;else{g=document.getElementsByTagName("script");for(var h=0,k=g.length;h<k;h++)if(g[h].src.indexOf("/debug-")>0){f=!0;break}}f&&(f=!1,e?f=!0:(typeof a==="string"?g=a:ErrorEvent&&a instanceof ErrorEvent?(f=!0,g=a.message,b=a.filename,c=a.lineno,d=a.colno):(g="Unknown error",b="Unknown file",c=0),e=new V(g),e.name="UnhandledWindowError",e.message=g,
e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d),f?ct(e):dt(e))};
je=et;window.addEventListener("unhandledrejection",function(a){et(a.reason)});
Db(T("ERRORS")||[],function(a){ct.apply(null,a)});
dl("ERRORS",[]);}).call(this);
