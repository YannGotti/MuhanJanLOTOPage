<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="refresh" content="0; url=https://t.me/ИмяБота?start=da_auth_{{CODE}}">
  </head>
  <body>
    <p>Перенаправляем в Telegram...</p>
    <script>
      const code = new URLSearchParams(window.location.search).get('code');
      if (code) {
        window.location.href = `https://t.me/ИмяБота?start=da_auth_${code}`;
      }
    </script>
  </body>
</html>
