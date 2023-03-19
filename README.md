<div align="center">
# discord-token-login

Discord hesabının tokenini alma ve token ile giriş yapma kodları.

Bu benim tarafımdan yapılmadı! (evet güvenlidir tokenlerinizi çalmaz).

# [Discord tokeni elde etme!](https://github.com/sqarlex/discord-token-login/blob/main/get-token.monkey)
```c# #merhaba biliyorum bu c# değil ama ben rengini beğendim.
(webpackChunkdiscord_app.push(
[[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!==void 0).exports.default.getToken()
```

# [Discord tokene giriş yapma!](https://github.com/sqarlex/discord-token-login/blob/main/token-login.monkey)
```c#
function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
}

login('TOKENI_BURAYA_YAPISTIR')
```
</div>
