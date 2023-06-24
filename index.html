<!DOCTYPE html>
<html>
<head>
  <title>Client IP Address</title>
</head>
<body>
  <h1>Client IP Address:</h1>
  <p id="ipAddress"></p>

  <script>
    function getIPAddress() {
      return new Promise((resolve, reject) => {
        const peerConnection = new RTCPeerConnection();
        peerConnection.createDataChannel('');
      
        peerConnection.onicecandidate = (event) => {
          if (event.candidate) {
            const ipAddress = event.candidate.address || event.candidate.ip || '';
            resolve(ipAddress);
          }
        };
      
        peerConnection.createOffer()
          .then((offer) => peerConnection.setLocalDescription(offer))
          .catch(reject);
      });
    }

    // Get the IP address and update the page content
    getIPAddress()
      .then((ipAddress) => {
        const ipAddressElement = document.getElementById('ipAddress');
        ipAddressElement.textContent = ipAddress;
      })
      .catch((error) => console.error('Error:', error));
  </script>
</body>
</html>
