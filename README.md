# Mobile App Landing Page

hello world


```bash
curl -H "Authorization: PVEAPIToken=root@pam!monitoring=aaaaaaaaa-bbb-cccc-dddd-ef0123456789" https://10.0.0.1:8006/api2/json/
```

```bash
curl https://103.154.241.36:8006/api2/json/nodes

curl: (60) schannel: SEC_E_UNTRUSTED_ROOT (0x80090325) - The certificate chain was issued by an authority that is not trusted.
More details here: https://curl.se/docs/sslcerts.html

curl failed to verify the legitimacy of the server and therefore could not
establish a secure connection to it. To learn more about this situation and
how to fix it, please visit the web page mentioned above.


root@pam!token_id
10330a3e-fb8f-4707-8d4e-f804eb9a8efc


PVEAPIToken=root@pam!token_id:10330a3e-fb8f-4707-8d4e-f804eb9a8efc


Ref; https://103.154.241.36:8006/pve-docs/chapter-pveum.html#pveum_tokens

To use an API token, set the HTTP header Authorization to the displayed value of the form PVEAPIToken=USER@REALM!TOKENID=UUID when making API requests, or refer to your API client’s documentation.


[Working Values]
PVEAPIToken=root@pam!token_id=10330a3e-fb8f-4707-8d4e-f804eb9a8efc

```
