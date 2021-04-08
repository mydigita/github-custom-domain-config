# github-custom-domain-config
Full guideline for using custom domain to any github repository. 

## Step 1
Open your repositoy and click on Settings

![Repo](/images/open-repo.jpg)


## Step 2

Under the Github Pages -> Source, click on `None`, then select `master` or another branch, then `Save` it

![Select Page Branch](/images/select-page-branch.jpg)

This will publish your project with github-pages via selected branch. So, your site is live now at https://username.github.io/projectname. Now we will set custom domain to our github project. But before that we will edit our main domain DNS configuration. 

## Step 3

Add / point the following IP addresses to your custom domain in DNS zone with `A` record

* 185.199.108.153
* 185.199.109.153
* 185.199.110.153
* 185.199.111.153



## Step 4

Come back to your repository Settings-> Github Pages, then put your domain name to this field and click on `Update`


