create some profile rc utils / aliases:

echo | openssl s_client -connect host:443 -showcerts | sed -ne '/-BEGIN CERTIFICATE-/,/-END CERTIFICATE-/p'
