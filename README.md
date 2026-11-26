# instagrammable-app1


    function sendToBot() {
      const url = document.getElementById("igUrl").value.trim();
      if (!url) {
        alert("Please enter an Instagram URL.");
        return;
      }
      if (tg && tg.sendData) {
        tg.sendData(url);
      } else {
        alert("Open this page inside Telegram to send directly to the bot.");
      }
    }
  </script>
</body>
</html
