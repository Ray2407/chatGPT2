<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
 <title>Single File PWA</title>
 <meta name="theme-color" content="#317EFB" />
 <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🚀</text></svg>">

 <!-- Embedded Web App Manifest -->
 <link rel="manifest" href="data:application/manifest+json,{
   &quot;name&quot;: &quot;Single File PWA&quot;,
   &quot;short_name&quot;: &quot;PWA&quot;,
   &quot;start_url&quot;: &quot;.&quot;,
   &quot;display&quot;: &quot;standalone&quot;,
   &quot;background_color&quot;: &quot;#ffffff&quot;,
   &quot;theme_color&quot;: &quot;#317EFB&quot;,
   &quot;icons&quot;: [
     {
       &quot;src&quot;: &quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAKCAMAAAC67D+PAAAAGFBMVEUAAAD///8AAAD///8AAAD///8AAAD///9fX1+V+nk+AAAAAXRSTlMAQObYZgAAAEpJREFUeNpNzEsOACAIBNHT8z91O/8VXDRp8RYBTtZbUdnwUuzK8Q4sK9xB2hxp5K8T3e2IgZVXxtoginXkYGE+JQ9AnNcFsELsKakAAAAASUVORK5CYII=&quot;,
       &quot;sizes&quot;: &quot;48x48&quot;,
       &quot;type&quot;: &quot;image/png&quot;
     }
   ]
 }">

 <style>
   body {
     font-family: sans-serif;
     margin: 0;
     padding: 0;
     height: 100vh;
     display: flex;
     justify-content: center;
     align-items: center;
     background: #eef1f5;
   }
   main {
     text-align: center;
   }
   h1 {
     color: #317EFB;
   }
   button {
     padding: 10px 20px;
     font-size: 1rem;
     margin-top: 20px;
     cursor: pointer;
   }
 </style>
</head>
<body>
 <main>
   <h1>🚀 Hello from a Single File PWA!</h1>
   <p>Everything is self-contained in this HTML file.</p>
   <button onclick="alert('PWA says hi!')">Click Me</button>
 </main>

 <!-- Embedded Service Worker -->
 <script>
   const swCode = `
     const cacheName = 'single-file-pwa-v1';
     self.addEventListener('install', e => {
       e.waitUntil(
         caches.open(cacheName).then(cache =>
           cache.addAll(['.'])
         )
       );
     });
     self.addEventListener('fetch', e => {
       e.respondWith(
         caches.match(e.request).then(response =>
           response || fetch(e.request)
         )
       );
     });
   `;
   if ('serviceWorker' in navigator) {
     const blob = new Blob([swCode], { type: 'application/javascript' });
     const swUrl = URL.createObjectURL(blob);
     navigator.serviceWorker.register(swUrl).then(reg => {
       console.log('Service Worker registered from blob:', reg);
     }).catch(console.error);
   }
 </script>
</body>
</html>
