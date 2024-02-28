# Dehydrate-letsencrypt

This module uses a [bash based acme
client](thttps://github.com/lukas2511/dehydrated) for the letsencrypt project to
provide secure SSL/TLS based web service for apache.

This ansible role is likely to trigger some spurious changes. The main reason
for this is the sync described above. The wrapper runs daily as a cron job which
updates some of the information in the directory we are syncing. This could be
improved by being more selective in the sync.

### Credit: Ian Allison of PIMS