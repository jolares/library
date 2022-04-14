## Shell Commands


### Adding a PPA Public Key

`sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 40976EAF437D05B5`

**Notes:**

- Add each public key only once
- Ref: https://chrisjean.com/fix-apt-get-update-the-following-signatures-couldnt-be-verified-because-the-public-key-is-not-available/


### Downloading a file via http

`curl http://example-site-url.com/resource_filename --output desired_filename.csv`
