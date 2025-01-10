
<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "dte_bank_bg_V2.png"
    	width="auto" height="800"
         alt = "New Watson Assistant Bank" />
</head>

<script>
  window.wxOConfiguration = {
    clientVersion: "latest",
    orchestrationID: "a5970dd2-eb96-4b34-8aaf-1eafd075d02e",
    hostUrl: "https://dl.watson-orchestrate.ibm.com",
    rootElementId: "root",
    // token: "<CLIENT_JWT_GOES_HERE>"
  };
  setTimeout(function () {
    const script = document.createElement('script');
    script.src = `${window.wxOConfiguration.hostUrl}/webclient/wxoLoader.js`;
    script.addEventListener('load', function () {
      wxoLoader.init();
    });
    document.head.appendChild(script);
  }, 0);
</script>
<body>
</body>

</html>
