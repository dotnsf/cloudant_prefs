# cloudant_prefs

Sample data to handle Japanese 47 prefectures for IBM Cloudant.

## How to import prefs.json into IBM Cloudant

- Use bulk-insert API in curl

    - `$ curl -u "username:password" -XPOST "https://username.cloudant.com/prefs/_bulk_docs -H "Content-Type: application/json" -d @prefs.json`


## Copyright

2018 K.Kimura @ Juge.Me all rights reserved.
