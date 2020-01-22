# Heroku Buildpack for Salesforce - Org Development

## destroy apps and pipeline

```sh
heroku pipelines:destroy taka-demo-swtt2019
heroku apps:destroy -a taka-demo-swtt2019-dev -c taka-demo-swtt2019-dev
heroku apps:destroy -a taka-demo-swtt2019-staging -c taka-demo-swtt2019-staging
heroku apps:destroy -a taka-demo-swtt2019 -c taka-demo-swtt2019
rm -- "destroy-taka-demo-swtt2019.sh"
```

## Acknowledgement

This is forked from [official buildpack](https://github.com/heroku/salesforce-buildpack).
