
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
    integrationID: "9b8564a9-9dad-4a45-aef1-e0df55b9e165", // The ID of this integration.
    region: "aws-us-east-1", // The region your integration is hosted in.
    serviceInstanceID: "20240201-1640-0529-1052-568aeb82c85a", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>
<body></body>

</html>
