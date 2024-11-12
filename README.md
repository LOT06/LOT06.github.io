
<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "dte_bank_bg_V2.png"
    	width="auto" height="800"
         alt = "New Watson Assistant Bank" />
</head>
<script>
  window.watsonAssistantChatOptions = {
    integrationID: "b9b49222-ad04-410b-aeca-4f72eaa594a5", // The ID of this integration.
    region: "aws-us-east-1", // The region your integration is hosted in.
    serviceInstanceID: "20240227-1525-1134-808e-497d1e4816e6", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>
<body>
</body>

</html>
