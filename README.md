# inspec-plus

refer to https://hub.docker.com/r/chef/inspec for more usage detail. 
This derivative container was created to supply additional tools necessary for controls I regularly use.


```bash
docker run -it --rm -v $(pwd):/share mmenger/inspec-plus exec inspec-profile-name --input-file test.yml --chef-license accept-silent
```
