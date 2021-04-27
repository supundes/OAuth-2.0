# OAuth 2.0 Demonstration

<h3>For Testing Implement As Below</h3>
<ul>
  <li>Create a Facebook App. (https://developers.facebook.com)</li>
  <li>Create a folder named "OAuth-2.0" in the localhost folder (Written in PHP so Wamp, Xampp, etc...) and copy the content of this repository there.</li>
  <li>Change the following parameters in the following functions.
    <p>AUTH_URL($client_id,$redirect_url) -> change $client_id to your App ID </p>
    <p>get_auth_code($client_id, $redirect_uri, $auth_code, $appID_secret_base64) -> change $client_id, $appID_secret_base64=Base64 (YourAppID:AppSecret)</p></li>
  <li>Copy https://localhost/OAuth-2.0/index.php, https://localhost/OAuth-2.0/redirect.php, https://localhost/OAuth-2.0/server.php into "Valid OAuth Redirect URIs" field on Facebook App.</li>
  <li>Run the server. (Wamp,Xampp, etc...)</li>
  <li>Type "http://localhost/OAuth-2.0/index" in a browser window and proceed.</li>
</ul>
