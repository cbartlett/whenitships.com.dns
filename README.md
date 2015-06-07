#README

## Install
`$ bundle `

## Edit Records

Edit the `records.json` file.

## Verify Everything

`bundle exec ruby validate.rb`

## Deploying new records

Just push this repo to github and continuous delivery will take care of the rest via:

`$ DNSIMPLE_USERNAME=my@email.tld DNSIMPLE_API_TOKEN=my_token bundle exec dns_deploy records.json `
