## Laravel test on Zeit now

Works fine at [laravel.now.sh](https://laravel.now.sh) thanks to [Zeit.co](https://zeit.co/).

## Repo Deprecated

Zeit's new version has stopped supporting docker containers so this repo is not useful anymore. If you want to run Laravel Docker containers on a serverless environment read this step by step [tutorial](https://geshan.com.np/blog/2019/10/get-laravel-6-running-on-google-cloud-run-step-by-step-with-ci/) or check this new [repo](https://github.com/geshan/laravel6-on-google-cloud-run). Thanks!

### To try this repo now Zeit/now

Do the following

1. Install now cli `npm install -g now`
1. clone the repo: `git clone git@github.com:geshan/laravel-zeit-now.git`
1. `cd laravel-zeit-now`
1. `now --public --docker` (you might need to login once)
1. Wait for the container to build and deploy, then hit the URL to see something like `http://laravel.now.sh`
