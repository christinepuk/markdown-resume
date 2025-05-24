### s3 Commands 
cp cpukropski.html index.html
s3cmd --no-mime-magic --acl-public sync index.html s3://cpuk-resume
s3cmd setacl --acl-public --recursive  s3://cpuk-resume

Ref: https://www.linode.com/docs/guides/host-static-site-object-storage/#upload-your-static-site-to-linode-object-storage
